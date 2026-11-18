---
kb_id: WK-OBK-DATA-004
title: "Monthly Database และ Central Summary"
description: "Monthly Database และ Central Summary และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# Monthly Database และ Central Summary

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-DATA-004` |
| คำอธิบาย (Description) | Monthly Database และ Central Summary และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

แบบที่วางไว้ให้ฐานรายเดือนเก็บข้อมูลรายละเอียด Central Summary เก็บผลสรุปสำหรับ Dashboard และ Control Database เก็บการตั้งค่า แหล่งข้อมูล และประวัตินำเข้า ยืนยันคีย์ รูปแบบวันที่ และวิธีส่งยอดแก้ไขข้ามเดือนไปสรุปกลางก่อนสร้างหรือเปลี่ยนไฟล์จริง

## ข้อมูลนำเข้าและหลักฐาน

Monthly Database, Central Summary และ Control Database ที่วางแบบไว้

## ขั้นตอนการปฏิบัติงาน

1. กำหนดเจ้าของข้อมูลและคีย์
2. กำหนดวิธีคำนวณยอดสรุป
3. ทดสอบเคสเปิดเดือนหนึ่งแต่ปิดอีกเดือน
4. ทบทวนวิธีส่งผลย้อนหลัง

## จุดตรวจสอบและข้อจำกัด

จัดเก็บเดือนต้นทางและเดือนรายงานให้ตรวจสอบได้เมื่อสถานะเปลี่ยนข้ามเดือน

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
