---
kb_id: WK-OBK-SLA-004
title: "ผลการประเมินและ KPI"
description: "ผลการประเมินและ KPI และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: decision_rule
source_authority: working_draft
sensitivity: internal
---

# ผลการประเมินและ KPI

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SLA-004` |
| คำอธิบาย (Description) | ผลการประเมินและ KPI และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

กำหนดขอบเขต Security หรือ SOC Involved ตามตัวชี้วัดก่อนคำนวณ แสดง Pass, Fail, Need Review และ No Evidence พร้อมฐานคำนวณ แยกตัวชี้วัดรายทีมจากรายบุคคล เคสที่มีข้อมูลก่อนเริ่มเก็บชื่อในแท็กอาจต้องตรวจหลักฐานเพิ่ม ตรวจข้อยกเว้นเช่น Muted, Test และ The PARQ Fire Alarm PM ตามกติกาของรายงานที่ใช้

## ข้อมูลนำเข้าและหลักฐาน

ขอบเขต KPI, ข้อยกเว้น และรายการเคสตรวจสอบ

## ขั้นตอนการปฏิบัติงาน

1. เลือกขั้น SLA และกลุ่มเคส
2. ระบุจำนวนในแต่ละสถานะ
3. ตรวจรายชื่อผู้ดำเนินการ
4. เทียบยอดกับข้อมูลต้นทาง

## จุดตรวจสอบและข้อจำกัด

แยก Review จาก No Evidence และระบุฐานคำนวณทุกเปอร์เซ็นต์

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
