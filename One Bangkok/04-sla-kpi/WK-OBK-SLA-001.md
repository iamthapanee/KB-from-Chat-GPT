---
kb_id: WK-OBK-SLA-001
title: "Creation SLA"
description: "Creation SLA และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: decision_rule
source_authority: working_draft
sensitivity: internal
---

# Creation SLA

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SLA-001` |
| คำอธิบาย (Description) | Creation SLA และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

ใช้กับเคสที่ SOC เปิดจาก [SOC-INF], [SOC-VP] หรือ [SOC-Monitor] อ่านเวลารับแจ้งจาก Summary (N) และสิ้นสุดที่ Created On (G) เกณฑ์ CAT 1–4 ตามลำดับคือ 5 / 10 / 15 / 20 นาที กรณีเวลาข้ามวันหรือรูปแบบผิดและตีความได้มากกว่าหนึ่งทาง ให้ส่ง Manual Review

## ข้อมูลนำเข้าและหลักฐาน

Summary (N), Created On (G), CAT และชนิดแท็ก

## ขั้นตอนการปฏิบัติงาน

1. ตรวจแท็กที่เข้าเกณฑ์
2. แปลงเวลาให้ตรงวัน
3. หาผลต่างระดับนาที
4. เทียบเกณฑ์ CAT
5. บันทึกหลักฐานที่ใช้

## จุดตรวจสอบและข้อจำกัด

ตัวอย่าง CAT 1 รับแจ้ง 07:30 เปิด 07:35 เท่ากับ 5 นาทีและผ่าน หากเวลา 22.22 ให้ตรวจต้นฉบับก่อนปรับรูปแบบ

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
