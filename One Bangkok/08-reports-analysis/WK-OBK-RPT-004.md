---
kb_id: WK-OBK-RPT-004
title: "Blacklist, Whitelist และ LPR"
description: "Blacklist, Whitelist และ LPR และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# Blacklist, Whitelist และ LPR

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-RPT-004` |
| คำอธิบาย (Description) | Blacklist, Whitelist และ LPR และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

แยกจำนวนบุคคลไม่ซ้ำ จำนวนครั้งแจ้งเตือนบุคคล จำนวนรถไม่ซ้ำ และจำนวนครั้งแจ้งเตือนรถ ตรวจรายการทดสอบและกติกาตัด False/Muted ตามรายงานก่อนนับ ระบุคีย์ที่ใช้ตัดซ้ำเพื่อให้ตรวจผลได้

## ข้อมูลนำเข้าและหลักฐาน

Alert export และตัวอ้างอิงตัดซ้ำตามกติกาของรายงาน

## ขั้นตอนการปฏิบัติงาน

1. แยกบุคคลและรถ
2. แยกจำนวนไม่ซ้ำกับจำนวนการแจ้งเตือน
3. ตัด Muted/False และรายการทดสอบตามเกณฑ์
4. เทียบยอด

## จุดตรวจสอบและข้อจำกัด

รายงานสรุปเป็นจำนวนและเก็บ identity-level evidence ในระบบต้นทาง

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-RPT-000 — รายงานและการวิเคราะห์](../08-reports-analysis.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-RPT-000 โดยใช้ KB ID เดิม |
