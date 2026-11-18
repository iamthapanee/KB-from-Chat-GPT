---
kb_id: WK-OBK-SLA-003
title: "Resolve และ Close SLA"
description: "Resolve และ Close SLA และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: decision_rule
source_authority: working_draft
sensitivity: internal
---

# Resolve และ Close SLA

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SLA-003` |
| คำอธิบาย (Description) | Resolve และ Close SLA และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

Resolve ใช้ Security เท่านั้น จาก Created On ถึง Resolved On โดยเกณฑ์ CAT 1–4 คือ 30 / 240 / 1,440 / 4,320 นาที อ้างชื่อผู้ Resolve จาก [SOC-Resolve] ส่วน Close วัด Resolved On ถึง Closed On เกณฑ์ 15 นาที และใช้ Closed By ผูกชื่อจาก Master

## ข้อมูลนำเข้าและหลักฐาน

Created On, Resolved On, Closed On, CAT และผู้ดำเนินการ

## ขั้นตอนการปฏิบัติงาน

1. กรอง Security ตามขอบเขต
2. วัด Resolve และ Close แยกกัน
3. เทียบเกณฑ์แต่ละช่วง
4. ผูกผู้ Resolve และ Closed By

## จุดตรวจสอบและข้อจำกัด

ตัวอย่าง Resolve 09:00 และ Close 09:15 อยู่ที่ขอบเกณฑ์ 15 นาที ส่วนเวลาที่หายต้องแสดงตามหลักฐาน

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [Google Sheets Formula Pilot](https://docs.google.com/spreadsheets/d/17HHlAWEE3_nwV5QXphWn6qt-NBEGHYuAdCvzwwnlxBU/edit) และข้อตกลงการวิเคราะห์ Mozart เดือนพฤศจิกายน 2026
- [หมวด WK-OBK-SLA-000 — SLA & KPI](../04-sla-kpi.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-SLA-000 โดยใช้ KB ID เดิม |
