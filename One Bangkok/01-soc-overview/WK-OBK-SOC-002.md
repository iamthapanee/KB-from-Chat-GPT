---
kb_id: WK-OBK-SOC-002
title: "บทบาท Operator, Supervisor และ Super Admin"
description: "บทบาท Operator, Supervisor และ Super Admin และจุดตรวจสอบก่อนนำไปใช้"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: one_bangkok_soc
knowledge_type: role_profile
source_authority: working_draft
sensitivity: internal
---

# บทบาท Operator, Supervisor และ Super Admin

| รายการ | ข้อมูล |
|---|---|
| KB ID | `WK-OBK-SOC-002` |
| คำอธิบาย (Description) | บทบาท Operator, Supervisor และ Super Admin และจุดตรวจสอบก่อนนำไปใช้ |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

## วัตถุประสงค์และขอบเขต

Operator เฝ้าระวัง ตรวจสอบข้อเท็จจริง เปิดหรือรับเคส ประสานหน้างาน และบันทึกการดำเนินการ Supervisor ตรวจคุณภาพเคส ติดตาม SLA และประสานเหตุที่ต้องยกระดับ ส่วน Super Admin เป็นบทบาทดูแลระบบหรือการตั้งค่าตามสิทธิ์ที่ได้รับ การอนุมัติและสั่งการให้อ้างอิง Authority Matrix ของโครงการ

## ข้อมูลนำเข้าและหลักฐาน

JD, รายการสิทธิ์ และ Authority Matrix ฉบับไซต์

## ขั้นตอนการปฏิบัติงาน

1. ระบุว่าใครเฝ้าระวัง ใครตรวจคุณภาพ และใครอนุมัติ
2. ส่งคำขอเปลี่ยนสิทธิ์ให้ผู้มีอำนาจ
3. เก็บผลอนุมัติและผลทดสอบ

## จุดตรวจสอบและข้อจำกัด

สิทธิ์ Super Admin ใช้อ้างขอบเขตระบบ ส่วนอำนาจสั่งการอ้าง Authority Matrix

## แหล่งข้อมูลและเอกสารที่เกี่ยวข้อง

- สารบัญตั้งต้นของรีโปและ KB ฉบับ 10 พฤศจิกายน 2026
- [หมวด WK-OBK-SOC-000 — ภาพรวมงาน SOC](../01-soc-overview.md)
- [แนวทางกำกับการใช้ AI](../../00_AI_GOVERNANCE.md)
- [ทะเบียน KB ID](../../CLAUDE_KB_Index.md)

## ประวัติการเปลี่ยนแปลง

| วันที่ | การเปลี่ยนแปลง |
|---|---|
| 2026-11-18 | แยกเป็น Knowledge Item รายเรื่องจากหมวด WK-OBK-SOC-000 โดยใช้ KB ID เดิม |
