---
kb_id: WK-OBK-DATA-001
title: "แหล่งข้อมูลและคีย์"
description: "แหล่งข้อมูลและคีย์ และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# แหล่งข้อมูลและคีย์

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-DATA-001` |
| คำอธิบาย (Description) | แหล่งข้อมูลและคีย์ และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

Cases.csv และ AlarmListingV2_New.xlsx เป็นข้อมูลนำเข้า Master.xlsx ใช้ผูกข้อมูลอ้างอิง เช่น User ID, ชื่อ, Event และ Location ใช้ Case ID เป็นคีย์ หลีกเลี่ยงการเดา Location จากคำที่คล้ายกัน และส่งรายการที่ผูกไม่ได้ให้ตรวจ

## ข้อมูลนำเข้าและหลักฐาน

Cases.csv, Alarm Listing และ Master ที่ยืนยัน

## ขั้นตอนการปฏิบัติงาน

1. ตรวจ Case ID และช่วง Export
2. แยกคอลัมน์ timestamp กับ mapping
3. ตรวจรายการผูกไม่ได้
4. บันทึกเวอร์ชัน Master

## จุดตรวจสอบและข้อจำกัด

รักษาค่าต้นฉบับของ Event Type และส่ง ID หรือ Location ที่จับคู่ไม่ได้ให้ตรวจ

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [Google Sheets Formula Pilot](https://docs.google.com/spreadsheets/d/17HHlAWEE3_nwV5QXphWn6qt-NBEGHYuAdCvzwwnlxBU/edit) และข้อตกลงการวิเคราะห์ Mozart เดือนพฤศจิกายน 2026
- [หมวด WK-OBK-DATA-000 — ข้อมูล Mozart และ Dashboard](../09-mozart-data-dashboards.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-DATA-000 โดยใช้ KB ID เดิม |
