---
kb_id: WK-OBK-SLA-000
title: "SLA & KPI"
description: "นิยาม SLA และการประเมินผลใน SOC Mozart Formula Pilot"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: decision_rule
source_authority: working_draft
sensitivity: internal
---

# 4. SLA & KPI

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SLA-000` |
| คำอธิบาย | นิยาม SLA และการประเมินผลใน SOC Mozart Formula Pilot |
| เจ้าของข้อมูล | นุ่น |
| อัปเดตล่าสุด | 18 พฤศจิกายน 2026 |
| สถานะ | ร่าง (Draft) |

## ขอบเขตการใช้

ใช้เป็นบริบทสำหรับ Claude และใช้ตรวจหัวข้อที่ต้องอ้างอิงต่อ ขั้นตอนและเกณฑ์ปฏิบัติงานจริงอ้างอิงเอกสารหรือไฟล์ฉบับที่นุ่นยืนยันล่าสุดตามขอบเขตงาน

## WK-OBK-SLA-001 Creation SLA

ใช้กับเคสที่ SOC เปิดจาก [SOC-INF], [SOC-VP] หรือ [SOC-Monitor] อ่านเวลารับแจ้งจาก Summary (N) และสิ้นสุดที่ Created On (G) เกณฑ์ CAT 1–4 ตามลำดับคือ 5 / 10 / 15 / 20 นาที กรณีเวลาข้ามวันหรือรูปแบบผิดและตีความได้มากกว่าหนึ่งทาง ให้ส่ง Manual Review

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](04-sla-kpi/WK-OBK-SLA-001.md)

## WK-OBK-SLA-002 Acknowledgement SLA

เริ่มที่ Created On (G) และสิ้นสุดที่เวลา [SOC-RSP] ที่เป็นการตอบสนองจริงครั้งแรกใน Operator Comments (AA) เกณฑ์ CAT 1–4 คือ 5 / 10 / 15 / 20 นาที ค่า 0 นาทีผ่านได้ การมี [SOC-RSP] หลายรายการที่แยกลำดับจริงไม่ได้ให้ส่ง Manual Review

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](04-sla-kpi/WK-OBK-SLA-002.md)

## WK-OBK-SLA-003 Resolve และ Close SLA

Resolve ใช้ Security เท่านั้น จาก Created On ถึง Resolved On โดยเกณฑ์ CAT 1–4 คือ 30 / 240 / 1,440 / 4,320 นาที อ้างชื่อผู้ Resolve จาก [SOC-Resolve] ส่วน Close วัด Resolved On ถึง Closed On เกณฑ์ 15 นาที และใช้ Closed By ผูกชื่อจาก Master

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](04-sla-kpi/WK-OBK-SLA-003.md)

## WK-OBK-SLA-004 ผลการประเมินและ KPI

กำหนดขอบเขต Security หรือ SOC Involved ตามตัวชี้วัดก่อนคำนวณ แสดง Pass, Fail, Need Review และ No Evidence พร้อมฐานคำนวณ แยกตัวชี้วัดรายทีมจากรายบุคคล เคสที่มีข้อมูลก่อนเริ่มเก็บชื่อในแท็กอาจต้องตรวจหลักฐานเพิ่ม ตรวจข้อยกเว้นเช่น Muted, Test และ The PARQ Fire Alarm PM ตามกติกาของรายงานที่ใช้

[อ่านข้อมูลนำเข้า ขั้นตอน และจุดตรวจสอบ](04-sla-kpi/WK-OBK-SLA-004.md)

## แหล่งอ้างอิง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [Google Sheets Formula Pilot](https://docs.google.com/spreadsheets/d/17HHlAWEE3_nwV5QXphWn6qt-NBEGHYuAdCvzwwnlxBU/edit) และข้อตกลงการวิเคราะห์ Mozart เดือนพฤศจิกายน 2026

[กลับไปยังสารบัญหมวด](README.md) · [ค้นด้วย KB ID](../CLAUDE_KB_Index.md)
