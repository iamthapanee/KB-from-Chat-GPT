---
kb_id: WK-OBK-CASE-002
title: "จำแนกเหตุและตรวจหลักฐาน"
description: "จำแนกเหตุและตรวจหลักฐาน และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# จำแนกเหตุและตรวจหลักฐาน

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-CASE-002` |
| คำอธิบาย (Description) | จำแนกเหตุและตรวจหลักฐาน และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

เลือก Event Category, Event Type, Sub Event Type และ CAT ตาม Mozart Master และลักษณะเหตุจริง แยกสิ่งที่ผู้แจ้งรายงานจากสิ่งที่ SOC ตรวจยืนยัน ใช้ภาพและผลตรวจหน้างานประกอบการระบุ Actual หรือ False หัวข้อที่ยังตีความไม่ได้ให้ส่งตรวจตามเกณฑ์ของไซต์

## ข้อมูลนำเข้าและหลักฐาน

Mozart Master, ภาพหรือรายงานหน้างาน และข้อมูล Alert

## ขั้นตอนการปฏิบัติงาน

1. ตรวจเหตุที่เกิดขึ้นจริง
2. ผูก Event Category, Type, Sub Type และ CAT ตาม Master
3. บันทึกเหตุผลประกอบ Actual/False

## จุดตรวจสอบและข้อจำกัด

คงชื่อ Event Type ตาม raw data เมื่อต้องกรอง และเก็บผลยืนยันกับเคส

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-CASE-000 — Incident & Case Management](../03-incident-case-management.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-CASE-000 โดยใช้ KB ID เดิม |
