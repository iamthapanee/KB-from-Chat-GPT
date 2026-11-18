---
kb_id: WK-OBK-VP-004
title: "ตรวจคุณภาพ Dashboard"
description: "ตรวจคุณภาพ Dashboard และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: workflow
source_authority: working_draft
sensitivity: internal
---

# ตรวจคุณภาพ Dashboard

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-VP-004` |
| คำอธิบาย (Description) | ตรวจคุณภาพ Dashboard และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

เทียบยอดกับ raw data ของ Operator และรายงาน Mozart ตรวจกลุ่ม Route ตามไซต์ โดยเฉพาะคำนำหน้า SYM/FYI เมื่อโครงสร้าง raw data เปลี่ยน ให้ตรวจชื่อคอลัมน์ การจับคู่ Route และผลแสดงตัวเลขบนกราฟก่อนใช้รายงาน

## ข้อมูลนำเข้าและหลักฐาน

raw data Operator, รายงาน Mozart และชื่อคอลัมน์ใน Dashboard

## ขั้นตอนการปฏิบัติงาน

1. เทียบ header และชนิดข้อมูล
2. ทดสอบวันปกติและวันมีข้อมูลต่ำ
3. ตรวจ SYM/FYI และ Event Type
4. เทียบยอดบนกราฟ

## จุดตรวจสอบและข้อจำกัด

ครอบคลุมแท่งต่ำกว่าเกณฑ์แสดงผลเดิมและกรณีคอลัมน์ใหม่

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-VP-000 — Virtual Patrol](../05-virtual-patrol.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-VP-000 โดยใช้ KB ID เดิม |
