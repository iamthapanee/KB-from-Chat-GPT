# Knowledge Base สำหรับ Claude — นุ่น

อัปเดต 18 พฤศจิกายน 2026 · สถานะ **ร่าง**

ค้นหา KB ID ที่ต้องการ แล้วเปิดหน้าหมวดหรือหัวข้อย่อยที่เกี่ยวข้อง รหัสเป็นตัวอ้างอิงประจำหัวข้อเมื่อมีการปรับรายละเอียดในอนาคต ใช้ไฟล์ต้นฉบับล่าสุดและข้อกำหนดที่ได้รับยืนยันสำหรับการปฏิบัติงาน ดู [README](README.md), [AI Governance](00_AI_GOVERNANCE.md) และ [KB Schema](00_KB_SCHEMA.md) ประกอบ

## ทะเบียน KB ID

| KB ID | ชื่อเรื่อง |
|---|---|
| `WK-OBK-SOC-000` | **[ภาพรวมงาน SOC](One%20Bangkok/01-soc-overview.md)** |
| `WK-OBK-SOC-001` | [ภารกิจของ SOC](One%20Bangkok/01-soc-overview.md#wk-obk-soc-001-%E0%B8%A0%E0%B8%B2%E0%B8%A3%E0%B8%81%E0%B8%B4%E0%B8%88%E0%B8%82%E0%B8%AD%E0%B8%87-soc) |
| `WK-OBK-SOC-002` | [บทบาท Operator, Supervisor และ Super Admin](One%20Bangkok/01-soc-overview.md#wk-obk-soc-002-%E0%B8%9A%E0%B8%97%E0%B8%9A%E0%B8%B2%E0%B8%97-operator-supervisor-%E0%B9%81%E0%B8%A5%E0%B8%B0-super-admin) |
| `WK-OBK-SOC-003` | [ขอบเขตพื้นที่และเจ้าของงาน](One%20Bangkok/01-soc-overview.md#wk-obk-soc-003-%E0%B8%82%E0%B8%AD%E0%B8%9A%E0%B9%80%E0%B8%82%E0%B8%95%E0%B8%9E%E0%B8%B7%E0%B9%89%E0%B8%99%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B9%80%E0%B8%88%E0%B9%89%E0%B8%B2%E0%B8%82%E0%B8%AD%E0%B8%87%E0%B8%87%E0%B8%B2%E0%B8%99) |
| `WK-OBK-SYS-000` | **[ระบบที่ SOC ใช้งาน](One%20Bangkok/02-soc-systems.md)** |
| `WK-OBK-SYS-001` | [Mozart และ Qognify VMS](One%20Bangkok/02-soc-systems.md#wk-obk-sys-001-mozart-%E0%B9%81%E0%B8%A5%E0%B8%B0-qognify-vms) |
| `WK-OBK-SYS-002` | [Access Control และ Face Scan](One%20Bangkok/02-soc-systems.md#wk-obk-sys-002-access-control-%E0%B9%81%E0%B8%A5%E0%B8%B0-face-scan) |
| `WK-OBK-SYS-003` | [Sensetime, LPR และ Optimax](One%20Bangkok/02-soc-systems.md#wk-obk-sys-003-sensetime-lpr-%E0%B9%81%E0%B8%A5%E0%B8%B0-optimax) |
| `WK-OBK-SYS-004` | [บันทึกปัญหาระบบ](One%20Bangkok/02-soc-systems.md#wk-obk-sys-004-%E0%B8%9A%E0%B8%B1%E0%B8%99%E0%B8%97%E0%B8%B6%E0%B8%81%E0%B8%9B%E0%B8%B1%E0%B8%8D%E0%B8%AB%E0%B8%B2%E0%B8%A3%E0%B8%B0%E0%B8%9A%E0%B8%9A) |
| `WK-OBK-CASE-000` | **[Incident & Case Management](One%20Bangkok/03-incident-case-management.md)** |
| `WK-OBK-CASE-001` | [รับแจ้งและเปิดเคส](One%20Bangkok/03-incident-case-management.md#wk-obk-case-001-%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B9%81%E0%B8%88%E0%B9%89%E0%B8%87%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B9%80%E0%B8%9B%E0%B8%B4%E0%B8%94%E0%B9%80%E0%B8%84%E0%B8%AA) |
| `WK-OBK-CASE-002` | [จำแนกเหตุและตรวจหลักฐาน](One%20Bangkok/03-incident-case-management.md#wk-obk-case-002-%E0%B8%88%E0%B8%B3%E0%B9%81%E0%B8%99%E0%B8%81%E0%B9%80%E0%B8%AB%E0%B8%95%E0%B8%B8%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B8%AB%E0%B8%A5%E0%B8%B1%E0%B8%81%E0%B8%90%E0%B8%B2%E0%B8%99) |
| `WK-OBK-CASE-003` | [ประสานงานและยกระดับ](One%20Bangkok/03-incident-case-management.md#wk-obk-case-003-%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B8%AA%E0%B8%B2%E0%B8%99%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%A2%E0%B8%81%E0%B8%A3%E0%B8%B0%E0%B8%94%E0%B8%B1%E0%B8%9A) |
| `WK-OBK-CASE-004` | [Resolve และ Close](One%20Bangkok/03-incident-case-management.md#wk-obk-case-004-resolve-%E0%B9%81%E0%B8%A5%E0%B8%B0-close) |
| `WK-OBK-SLA-000` | **[SLA & KPI](One%20Bangkok/04-sla-kpi.md)** |
| `WK-OBK-SLA-001` | [Creation SLA](One%20Bangkok/04-sla-kpi.md#wk-obk-sla-001-creation-sla) |
| `WK-OBK-SLA-002` | [Acknowledgement SLA](One%20Bangkok/04-sla-kpi.md#wk-obk-sla-002-acknowledgement-sla) |
| `WK-OBK-SLA-003` | [Resolve และ Close SLA](One%20Bangkok/04-sla-kpi.md#wk-obk-sla-003-resolve-%E0%B9%81%E0%B8%A5%E0%B8%B0-close-sla) |
| `WK-OBK-SLA-004` | [ผลการประเมินและ KPI](One%20Bangkok/04-sla-kpi.md#wk-obk-sla-004-%E0%B8%9C%E0%B8%A5%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B9%80%E0%B8%A1%E0%B8%B4%E0%B8%99%E0%B9%81%E0%B8%A5%E0%B8%B0-kpi) |
| `WK-OBK-VP-000` | **[Virtual Patrol](One%20Bangkok/05-virtual-patrol.md)** |
| `WK-OBK-VP-001` | [แผนรอบตามความเสี่ยง](One%20Bangkok/05-virtual-patrol.md#wk-obk-vp-001-%E0%B9%81%E0%B8%9C%E0%B8%99%E0%B8%A3%E0%B8%AD%E0%B8%9A%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1%E0%B9%80%E0%B8%AA%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%87) |
| `WK-OBK-VP-002` | [เพิ่ม แก้ไข หรือยกเลิก Route](One%20Bangkok/05-virtual-patrol.md#wk-obk-vp-002-%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1-%E0%B9%81%E0%B8%81%E0%B9%89%E0%B9%84%E0%B8%82-%E0%B8%AB%E0%B8%A3%E0%B8%B7%E0%B8%AD%E0%B8%A2%E0%B8%81%E0%B9%80%E0%B8%A5%E0%B8%B4%E0%B8%81-route) |
| `WK-OBK-VP-003` | [ตรวจและรายงานผล](One%20Bangkok/05-virtual-patrol.md#wk-obk-vp-003-%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B8%9C%E0%B8%A5) |
| `WK-OBK-VP-004` | [ตรวจคุณภาพ Dashboard](One%20Bangkok/05-virtual-patrol.md#wk-obk-vp-004-%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B8%84%E0%B8%B8%E0%B8%93%E0%B8%A0%E0%B8%B2%E0%B8%9E-dashboard) |
| `WK-OBK-GT-000` | **[Guard Tour](One%20Bangkok/06-guard-tour.md)** |
| `WK-OBK-GT-001` | [แผนจุดตรวจและรอบ](One%20Bangkok/06-guard-tour.md#wk-obk-gt-001-%E0%B9%81%E0%B8%9C%E0%B8%99%E0%B8%88%E0%B8%B8%E0%B8%94%E0%B8%95%E0%B8%A3%E0%B8%A7%E0%B8%88%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%A3%E0%B8%AD%E0%B8%9A) |
| `WK-OBK-GT-002` | [จุดที่ข้ามและ Retail Revision](One%20Bangkok/06-guard-tour.md#wk-obk-gt-002-%E0%B8%88%E0%B8%B8%E0%B8%94%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%82%E0%B9%89%E0%B8%B2%E0%B8%A1%E0%B9%81%E0%B8%A5%E0%B8%B0-retail-revision) |
| `WK-OBK-GT-003` | [ติดตามผลและงานแก้ไข](One%20Bangkok/06-guard-tour.md#wk-obk-gt-003-%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%9C%E0%B8%A5%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B9%81%E0%B8%81%E0%B9%89%E0%B9%84%E0%B8%82) |
| `WK-OBK-SOP-000` | **[SOP, WI & แผนฉุกเฉิน](One%20Bangkok/07-sop-wi-emergency.md)** |
| `WK-OBK-SOP-001` | [SOP กับ WI](One%20Bangkok/07-sop-wi-emergency.md#wk-obk-sop-001-sop-%E0%B8%81%E0%B8%B1%E0%B8%9A-wi) |
| `WK-OBK-SOP-002` | [Checklist ตาม Mozart Security Event Type](One%20Bangkok/07-sop-wi-emergency.md#wk-obk-sop-002-checklist-%E0%B8%95%E0%B8%B2%E0%B8%A1-mozart-security-event-type) |
| `WK-OBK-SOP-003` | [ERP, BCP และ DRP](One%20Bangkok/07-sop-wi-emergency.md#wk-obk-sop-003-erp-bcp-%E0%B9%81%E0%B8%A5%E0%B8%B0-drp) |
| `WK-OBK-RPT-000` | **[รายงานและการวิเคราะห์](One%20Bangkok/08-reports-analysis.md)** |
| `WK-OBK-RPT-001` | [Daily, Weekly และ Monthly Report](One%20Bangkok/08-reports-analysis.md#wk-obk-rpt-001-daily-weekly-%E0%B9%81%E0%B8%A5%E0%B8%B0-monthly-report) |
| `WK-OBK-RPT-002` | [Weekly Highlights](One%20Bangkok/08-reports-analysis.md#wk-obk-rpt-002-weekly-highlights) |
| `WK-OBK-RPT-003` | [Security Trend และการวิเคราะห์รายพื้นที่](One%20Bangkok/08-reports-analysis.md#wk-obk-rpt-003-security-trend-%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%A7%E0%B8%B4%E0%B9%80%E0%B8%84%E0%B8%A3%E0%B8%B2%E0%B8%B0%E0%B8%AB%E0%B9%8C%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%9E%E0%B8%B7%E0%B9%89%E0%B8%99%E0%B8%97%E0%B8%B5%E0%B9%88) |
| `WK-OBK-RPT-004` | [Blacklist, Whitelist และ LPR](One%20Bangkok/08-reports-analysis.md#wk-obk-rpt-004-blacklist-whitelist-%E0%B9%81%E0%B8%A5%E0%B8%B0-lpr) |
| `WK-OBK-DATA-000` | **[ข้อมูล Mozart และ Dashboard](One%20Bangkok/09-mozart-data-dashboards.md)** |
| `WK-OBK-DATA-001` | [แหล่งข้อมูลและคีย์](One%20Bangkok/09-mozart-data-dashboards.md#wk-obk-data-001-%E0%B9%81%E0%B8%AB%E0%B8%A5%E0%B9%88%E0%B8%87%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%A1%E0%B8%B9%E0%B8%A5%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%84%E0%B8%B5%E0%B8%A2%E0%B9%8C) |
| `WK-OBK-DATA-002` | [นำเข้าซ้ำและข้ามเดือน](One%20Bangkok/09-mozart-data-dashboards.md#wk-obk-data-002-%E0%B8%99%E0%B8%B3%E0%B9%80%E0%B8%82%E0%B9%89%E0%B8%B2%E0%B8%8B%E0%B9%89%E0%B8%B3%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%82%E0%B9%89%E0%B8%B2%E0%B8%A1%E0%B9%80%E0%B8%94%E0%B8%B7%E0%B8%AD%E0%B8%99) |
| `WK-OBK-DATA-003` | [Module ใน Google Sheets Formula Pilot](One%20Bangkok/09-mozart-data-dashboards.md#wk-obk-data-003-module-%E0%B9%83%E0%B8%99-google-sheets-formula-pilot) |
| `WK-OBK-DATA-004` | [Monthly Database และ Central Summary](One%20Bangkok/09-mozart-data-dashboards.md#wk-obk-data-004-monthly-database-%E0%B9%81%E0%B8%A5%E0%B8%B0-central-summary) |
| `WK-OBK-TEAM-000` | **[กำลังคนและการพัฒนาทีม](One%20Bangkok/10-staffing-training.md)** |
| `WK-OBK-TEAM-001` | [ตารางกะและข้อกำหนดกำลังคน](One%20Bangkok/10-staffing-training.md#wk-obk-team-001-%E0%B8%95%E0%B8%B2%E0%B8%A3%E0%B8%B2%E0%B8%87%E0%B8%81%E0%B8%B0%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%81%E0%B8%B3%E0%B8%AB%E0%B8%99%E0%B8%94%E0%B8%81%E0%B8%B3%E0%B8%A5%E0%B8%B1%E0%B8%87%E0%B8%84%E0%B8%99) |
| `WK-OBK-TEAM-002` | [ส่งมอบกะและ Onboarding](One%20Bangkok/10-staffing-training.md#wk-obk-team-002-%E0%B8%AA%E0%B9%88%E0%B8%87%E0%B8%A1%E0%B8%AD%E0%B8%9A%E0%B8%81%E0%B8%B0%E0%B9%81%E0%B8%A5%E0%B8%B0-onboarding) |
| `WK-OBK-TEAM-003` | [การประเมินรายบุคคล](One%20Bangkok/10-staffing-training.md#wk-obk-team-003-%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B9%80%E0%B8%A1%E0%B8%B4%E0%B8%99%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%9A%E0%B8%B8%E0%B8%84%E0%B8%84%E0%B8%A5) |
| `WK-OBK-PLAN-000` | **[แผนงาน Audit และจัดซื้อ](One%20Bangkok/11-planning-audit-procurement.md)** |
| `WK-OBK-PLAN-001` | [Master Plan และติดตามงาน](One%20Bangkok/11-planning-audit-procurement.md#wk-obk-plan-001-master-plan-%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%87%E0%B8%B2%E0%B8%99) |
| `WK-OBK-PLAN-002` | [Audit, HIRA และ MOC](One%20Bangkok/11-planning-audit-procurement.md#wk-obk-plan-002-audit-hira-%E0%B9%81%E0%B8%A5%E0%B8%B0-moc) |
| `WK-OBK-PLAN-003` | [จัดซื้อและติดตามคู่ค้า](One%20Bangkok/11-planning-audit-procurement.md#wk-obk-plan-003-%E0%B8%88%E0%B8%B1%E0%B8%94%E0%B8%8B%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%84%E0%B8%B9%E0%B9%88%E0%B8%84%E0%B9%89%E0%B8%B2) |
| `WK-OBK-REF-000` | **[เทมเพลตและไฟล์อ้างอิง](One%20Bangkok/12-templates-references.md)** |
| `WK-OBK-REF-001` | [ทะเบียนไฟล์ต้นฉบับ](One%20Bangkok/12-templates-references.md#wk-obk-ref-001-%E0%B8%97%E0%B8%B0%E0%B9%80%E0%B8%9A%E0%B8%B5%E0%B8%A2%E0%B8%99%E0%B9%84%E0%B8%9F%E0%B8%A5%E0%B9%8C%E0%B8%95%E0%B9%89%E0%B8%99%E0%B8%89%E0%B8%9A%E0%B8%B1%E0%B8%9A) |
| `WK-OBK-REF-002` | [เทมเพลตรายงานและสไลด์](One%20Bangkok/12-templates-references.md#wk-obk-ref-002-%E0%B9%80%E0%B8%97%E0%B8%A1%E0%B9%80%E0%B8%9E%E0%B8%A5%E0%B8%95%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B9%81%E0%B8%A5%E0%B8%B0%E0%B8%AA%E0%B9%84%E0%B8%A5%E0%B8%94%E0%B9%8C) |
| `WK-OBK-REF-003` | [ข้อความประสานงาน](One%20Bangkok/12-templates-references.md#wk-obk-ref-003-%E0%B8%82%E0%B9%89%E0%B8%AD%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B8%AA%E0%B8%B2%E0%B8%99%E0%B8%87%E0%B8%B2%E0%B8%99) |
| `BP-PER-000` | **[บริบทการทำงานกับ AI และโปรเจกต์ส่วนตัว](Personnal/13-ai-and-personal-projects.md)** |
| `BP-PER-001` | [แนวทางทำงานกับ Claude](Personnal/13-ai-and-personal-projects.md#bp-per-001-%E0%B9%81%E0%B8%99%E0%B8%A7%E0%B8%97%E0%B8%B2%E0%B8%87%E0%B8%97%E0%B8%B3%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B8%81%E0%B8%B1%E0%B8%9A-claude) |
| `BP-PER-002` | [เจ้าน้อย ลอตเตอรี่ N3](Personnal/13-ai-and-personal-projects.md#bp-per-002-%E0%B9%80%E0%B8%88%E0%B9%89%E0%B8%B2%E0%B8%99%E0%B9%89%E0%B8%AD%E0%B8%A2-%E0%B8%A5%E0%B8%AD%E0%B8%95%E0%B9%80%E0%B8%95%E0%B8%AD%E0%B8%A3%E0%B8%B5%E0%B9%88-n3) |
| `BP-PER-003` | [POM POM HOUSE](Personnal/13-ai-and-personal-projects.md#bp-per-003-pom-pom-house) |
| `BP-PER-004` | [ข่าวติดฟีด](Personnal/13-ai-and-personal-projects.md#bp-per-004-%E0%B8%82%E0%B9%88%E0%B8%B2%E0%B8%A7%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%9F%E0%B8%B5%E0%B8%94) |
| `BP-PER-005` | [เที่ยวเฉิงตู มีนาคม 2027](Personnal/13-ai-and-personal-projects.md#bp-per-005-%E0%B9%80%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%A7%E0%B9%80%E0%B8%89%E0%B8%B4%E0%B8%87%E0%B8%95%E0%B8%B9-%E0%B8%A1%E0%B8%B5%E0%B8%99%E0%B8%B2%E0%B8%84%E0%B8%A1-2027) |
