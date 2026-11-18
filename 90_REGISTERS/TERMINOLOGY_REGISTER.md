---
kb_id: REG-TERM-001
title: "ทะเบียนคำศัพท์ (Terminology Register)"
description: "คำศัพท์ของ SOC และขอบเขตการตีความใน KB"
owner: "นุ่น"
last_updated: 2026-11-18
status: draft
domain: register
knowledge_type: definition
source_authority: working_draft
sensitivity: internal
---

# ทะเบียนคำศัพท์ (Terminology Register)

| รายการ | ข้อมูล |
|---|---|
| KB ID | `REG-TERM-001` |
| คำอธิบาย (Description) | คำศัพท์ของ SOC และขอบเขตการตีความใน KB |
| เจ้าของข้อมูล (Owner) | นุ่น |
| อัปเดตล่าสุด (Last Updated) | 18 พฤศจิกายน 2026 |
| สถานะ (Status) | ร่าง (Draft) |

| คำศัพท์ | ความหมายและขอบเขต | สถานะการใช้คำ | Knowledge Item |
|---|---|---|---|
| Case ID | รหัสอ้างอิงและคีย์นำเข้าของเคส | CONTEXT_ONLY | [WK-OBK-DATA-001](../One%20Bangkok/09-mozart-data-dashboards/WK-OBK-DATA-001.md) |
| Actual / False | ผลการตรวจยืนยันเหตุแจ้งเตือนตามหลักฐาน | CONTEXT_ONLY | [WK-OBK-CASE-002](../One%20Bangkok/03-incident-case-management/WK-OBK-CASE-002.md) |
| Creation SLA | รับแจ้งถึง Created On สำหรับแท็กที่เข้าเกณฑ์ | CONTEXT_ONLY | [WK-OBK-SLA-001](../One%20Bangkok/04-sla-kpi/WK-OBK-SLA-001.md) |
| Acknowledgement SLA | Created On ถึงเวลา SOC ตอบสนองจริงครั้งแรก | CONTEXT_ONLY | [WK-OBK-SLA-002](../One%20Bangkok/04-sla-kpi/WK-OBK-SLA-002.md) |
| Resolve / Close SLA | Resolve วัด Created On ถึง Resolved On และ Close วัด Resolved On ถึง Closed On | CONTEXT_ONLY | [WK-OBK-SLA-003](../One%20Bangkok/04-sla-kpi/WK-OBK-SLA-003.md) |
| Incomplete Routes | ผลรวม No Action และ Cancelled ตาม Virtual Patrol Dashboard | CONTEXT_ONLY | [WK-OBK-VP-003](../One%20Bangkok/05-virtual-patrol/WK-OBK-VP-003.md) |
| Security Sub Event Type | รายละเอียดระดับย่อยจากชีท Security สำหรับจับคู่ SOP/WI | CONTEXT_ONLY | [WK-OBK-SOP-002](../One%20Bangkok/07-sop-wi-emergency/WK-OBK-SOP-002.md) |
