---
kb_id: WK-OBK-SLA-002
title: "Acknowledgement SLA"
description: "Acknowledgement SLA และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: decision_rule
source_authority: working_draft
sensitivity: internal
---

# Acknowledgement SLA

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SLA-002` |
| คำอธิบาย (Description) | Acknowledgement SLA และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

เริ่มที่ Created On (G) และสิ้นสุดที่เวลา [SOC-RSP] ที่เป็นการตอบสนองจริงครั้งแรกใน Operator Comments (AA) เกณฑ์ CAT 1–4 คือ 5 / 10 / 15 / 20 นาที ค่า 0 นาทีผ่านได้ การมี [SOC-RSP] หลายรายการที่แยกลำดับจริงไม่ได้ให้ส่ง Manual Review

## ข้อมูลนำเข้าและหลักฐาน

Created On (G), Operator Comments (AA), CAT และ [SOC-RSP]

## ขั้นตอนการปฏิบัติงาน

1. ตรวจข้อความตอบสนองจริงครั้งแรก
2. ผูกวันและเวลา
3. คำนวณระดับนาที
4. ส่งรายการกำกวมไป Manual Review

## จุดตรวจสอบและข้อจำกัด

เวลาเปิดและตอบอยู่ในนาทีเดียวกันให้ผล 0 นาที การตอบซ้ำควรคงข้อความหลักฐานที่เลือก

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
