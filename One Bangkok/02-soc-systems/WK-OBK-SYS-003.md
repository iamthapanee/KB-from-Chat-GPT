---
kb_id: WK-OBK-SYS-003
title: "Sensetime, LPR และ Optimax"
description: "Sensetime, LPR และ Optimax และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: system_profile
source_authority: working_draft
sensitivity: internal
---

# Sensetime, LPR และ Optimax

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SYS-003` |
| คำอธิบาย (Description) | Sensetime, LPR และ Optimax และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

Sensetime Video Analytics สร้างเหตุแจ้งเตือนเพื่อให้ตรวจยืนยันจากภาพ License Plate Recognition ใช้ตรวจรายการทะเบียนและการแจ้งเตือนรถ Optimax Go ใช้ติดตาม Guard Tour ส่วน Optimax Here ใช้กับ Face Scan หรือ Attendance ตามการตั้งค่าของไซต์

## ข้อมูลนำเข้าและหลักฐาน

Alert ID, กล้องหรือจุดตรวจ และชื่อระบบต้นทาง

## ขั้นตอนการปฏิบัติงาน

1. จำแนกแหล่งแจ้งเตือนก่อนตรวจ
2. เทียบภาพหรือบันทึกต้นทาง
3. จัดเก็บผลแยกตามประเภทงาน เช่น Actual/False หรือสถานะรอบตรวจ

## จุดตรวจสอบและข้อจำกัด

สำหรับ LPR รายงานจำนวนแบบสรุป ส่วนหลักฐานทะเบียนใช้ตามสิทธิ์

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-SYS-000 — ระบบที่ SOC ใช้งาน](../02-soc-systems.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-SYS-000 โดยใช้ KB ID เดิม |
