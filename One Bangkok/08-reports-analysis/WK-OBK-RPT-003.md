---
kb_id: WK-OBK-RPT-003
title: "Security Trend และการวิเคราะห์รายพื้นที่"
description: "Security Trend และการวิเคราะห์รายพื้นที่ และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# Security Trend และการวิเคราะห์รายพื้นที่

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-RPT-003` |
| คำอธิบาย (Description) | Security Trend และการวิเคราะห์รายพื้นที่ และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

ใช้ Security Event Category รวม Sensetime ตามกติกา Pilot และกรอง Muted/Test ตามขอบเขตรายงาน แสดง Actual/False ตามหลักฐาน แยก Traffic Congestion, Vehicle Going Wrong Direction และ Intrusion ตามชื่อในข้อมูลต้นทาง เจาะ Location, Camera ID และจำนวนเหตุ แล้วตรวจยอดรวมก่อนเขียนข้อสรุป

## ข้อมูลนำเข้าและหลักฐาน

Security export, Event Type, Location, Camera ID และ Actual/False

## ขั้นตอนการปฏิบัติงาน

1. กรองตามเกณฑ์รายงาน
2. รวมจำนวนตาม Event Type และพื้นที่
3. ตรวจรายการที่อยู่หลายกลุ่ม
4. ตามกลับถึง Case ID เมื่อยอดต่าง

## จุดตรวจสอบและข้อจำกัด

ก่อนสรุปแนวโน้ม ให้เทียบช่วงเวลา ตัวกรอง และการรวม Sensetime ให้ตรงกัน

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-RPT-000 — รายงานและการวิเคราะห์](../08-reports-analysis.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-RPT-000 โดยใช้ KB ID เดิม |
