---
kb_id: WK-OBK-SYS-001
title: "Mozart และ Qognify VMS"
description: "Mozart และ Qognify VMS และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: system_profile
source_authority: working_draft
sensitivity: internal
---

# Mozart และ Qognify VMS

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SYS-001` |
| คำอธิบาย (Description) | Mozart และ Qognify VMS และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

ใช้ Mozart สำหรับ Case Management, Alarm Listing และ Virtual Patrol ตามฟังก์ชันที่ไซต์เปิดใช้ ใช้ Qognify VMS ตรวจภาพสดและย้อนหลังเพื่อยืนยันเวลาและพื้นที่ เมื่ออ้างหลักฐานในเคสให้บันทึก Camera ID, ช่วงเวลา และข้อสังเกตที่ตรวจได้

## ข้อมูลนำเข้าและหลักฐาน

Case ID, Camera ID, เวลารับแจ้งและเวลาจากระบบ

## ขั้นตอนการปฏิบัติงาน

1. ใช้ Mozart หาเคสและสถานะ
2. เปิดภาพช่วงที่เกี่ยวข้องใน Qognify
3. จดสิ่งที่เห็นพร้อมเวลา
4. ผูกหลักฐานกับเคสตามสิทธิ์

## จุดตรวจสอบและข้อจำกัด

ทบทวนเขตเวลาและตำแหน่งกล้องก่อนสรุปเหตุ

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-SYS-000 — ระบบที่ SOC ใช้งาน](../02-soc-systems.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-SYS-000 โดยใช้ KB ID เดิม |
