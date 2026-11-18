---
kb_id: WK-OBK-DATA-000
title: "ข้อมูล Mozart และ Dashboard"
description: "ข้อมูลต้นทาง การนำเข้า และโครงสร้างรายงาน Mozart"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# 9. ข้อมูล Mozart และ Dashboard

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-DATA-000` |
| คำอธิบาย | ข้อมูลต้นทาง การนำเข้า และโครงสร้างรายงาน Mozart |
| เจ้าของข้อมูล | นุ่น |
| อัปเดตล่าสุด | 18 พฤศจิกายน 2026 |
| สถานะ | ร่าง (Draft) |

## ขอบเขตการใช้

ใช้เป็นบริบทสำหรับ Claude และใช้ตรวจหัวข้อที่ต้องอ้างอิงต่อ ขั้นตอนและเกณฑ์ปฏิบัติงานจริงอ้างอิงเอกสารหรือไฟล์ฉบับที่นุ่นยืนยันล่าสุดตามขอบเขตงาน

## WK-OBK-DATA-001 แหล่งข้อมูลและคีย์

Cases.csv และ AlarmListingV2_New.xlsx เป็นข้อมูลนำเข้า Master.xlsx ใช้ผูกข้อมูลอ้างอิง เช่น User ID, ชื่อ, Event และ Location ใช้ Case ID เป็นคีย์ หลีกเลี่ยงการเดา Location จากคำที่คล้ายกัน และส่งรายการที่ผูกไม่ได้ให้ตรวจ

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](09-mozart-data-dashboards/WK-OBK-DATA-001.md)

## WK-OBK-DATA-002 นำเข้าซ้ำและข้ามเดือน

นำเข้าแบบ upsert ตาม Case ID เพื่อให้เคสเดิมสะท้อนสถานะล่าสุดและรักษาข้อมูลเดือนที่อยู่นอกช่วงนำเข้า เมื่อข้อมูลซ้อนเดือน ตรวจค่าที่เปลี่ยน รายการซ้ำ และผลรวมหลังอัปเดต บันทึกช่วง Export และเวลานำเข้าเพื่อให้กลับไปเทียบไฟล์ได้

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](09-mozart-data-dashboards/WK-OBK-DATA-002.md)

## WK-OBK-DATA-003 Module ใน Google Sheets Formula Pilot

บันทึกขอบเขตของ Creation SLA, Security Resolve, Security Close, Security Trend, Pass/Fail Summary, Location Map, Sensetime VA และ Case Status Tracker งานต่อยอดที่เคยขอรวม Event Type Analysis และ Case Ranking พร้อมช่วงวัน สัปดาห์ และเดือน ตรวจชีทจริงก่อนระบุสถานะใช้งานของแต่ละ Module

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](09-mozart-data-dashboards/WK-OBK-DATA-003.md)

## WK-OBK-DATA-004 Monthly Database และ Central Summary

แบบที่วางไว้ให้ฐานรายเดือนเก็บข้อมูลรายละเอียด Central Summary เก็บผลสรุปสำหรับ Dashboard และ Control Database เก็บการตั้งค่า แหล่งข้อมูล และประวัตินำเข้า ยืนยันคีย์ รูปแบบวันที่ และวิธีส่งยอดแก้ไขข้ามเดือนไปสรุปกลางก่อนสร้างหรือเปลี่ยนไฟล์จริง

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](09-mozart-data-dashboards/WK-OBK-DATA-004.md)

## แหล่งอ้างอิง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [Google Sheets Formula Pilot](https://docs.google.com/spreadsheets/d/17HHlAWEE3_nwV5QXphWn6qt-NBEGHYuAdCvzwwnlxBU/edit) และข้อตกลงการวิเคราะห์ Mozart เดือนพฤศจิกายน 2026

[กลับไปยังสารบัญหมวด](README.md) · [ค้นด้วย KB ID](../CLAUDE_KB_Index.md)
