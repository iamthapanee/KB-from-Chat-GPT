# Knowledge Base สำหรับ Claude — นุ่น

อัปเดต 18 พฤศจิกายน 2026  
สถานะ **สารบัญร่างสำหรับตรวจและเติมเนื้อหา**

## วิธีใช้กับ Claude

ใช้ไฟล์นี้เป็นแผนผังหัวข้อสำหรับช่วยงานนุ่น เริ่มจากเลือกหมวดที่เกี่ยวข้อง แล้วอ่านไฟล์ต้นฉบับหรือข้อมูลล่าสุดที่นุ่นให้สำหรับงานนั้น ใช้ภาษาไทยเป็นหลัก และใช้ภาษาอังกฤษสำหรับรายงาน สไลด์ หรืออีเมลเมื่อนุ่นระบุ

เมื่อสรุปผลปฏิบัติงาน ให้ระบุช่วงเวลา ไซต์ ตัวกรอง และฐานคำนวณ ตรวจนิยามตัวชี้วัดจากต้นฉบับก่อนนำไปใช้ และระบุส่วนที่ต้องตรวจเพิ่มเติมเมื่อข้อมูลยังไม่ครบ

## สารบัญ

| # | หมวด | หัวข้อที่มีข้อมูลอ้างอิง |
|---|---|---|
| 1 | [ภาพรวมงาน SOC](One%20Bangkok/01-soc-overview.md) | บทบาท Supervisor และ Super Admin, ขอบเขตงาน, โครงการที่ดูแล, ทีมประสานงานและคู่ค้า, คำศัพท์และคำย่อ |
| 2 | [ระบบที่ SOC ใช้งาน](One%20Bangkok/02-soc-systems.md) | Mozart, Qognify VMS / CCTV, Honeywell EBI / UStar, Face Scan, Sensetime VA, LPR, Optimax Go / Here, ประวัติปัญหาระบบ |
| 3 | [Incident & Case Management](One%20Bangkok/03-incident-case-management.md) | การรับแจ้งและเปิดเคส, Event Category / Event Type / CAT, Actual / False, Escalation, หลักฐานและ Findings, Resolve / Close |
| 4 | [SLA & KPI](One%20Bangkok/04-sla-kpi.md) | Creation, Acknowledgement, Resolve และ Close SLA, Pass / Fail, Need Review / No Evidence, แท็ก `[SOC-RSP]` และ `[SOC-Resolve]`, KPI ทีมและรายบุคคล |
| 5 | [Virtual Patrol](One%20Bangkok/05-virtual-patrol.md) | ความถี่ตามความเสี่ยง, Route และตารางตรวจรายไซต์, การขอเพิ่มหรือแก้ไข Route, Planned / Completed / Incomplete, รายงานและ Dashboard |
| 6 | [Guard Tour](One%20Bangkok/06-guard-tour.md) | การตรวจผ่าน Optimax Go, จุดตรวจและรอบตรวจ, เหตุผลเมื่อข้ามจุดและการแจ้ง SOC, Guard Tour Revision สำหรับ Retail, รายงานผล |
| 7 | [SOP, WI & แผนฉุกเฉิน](One%20Bangkok/07-sop-wi-emergency.md) | Virtual Patrol, CCTV Request, Access Control, Crime Management, Crowd Control, การประสานงาน EOT, ERP / BCP / DRP, การซ้อมแผน |
| 8 | [รายงานและการวิเคราะห์](One%20Bangkok/08-reports-analysis.md) | Daily / Weekly / Monthly Report, Weekly Highlights พร้อมวิดีโอและแผนผัง, แนวโน้มตาม Location และ Event Type, Traffic Congestion, Wrong Direction, Intrusion, Blacklist / Whitelist และ LPR |
| 9 | [ข้อมูล Mozart และ Dashboard](One%20Bangkok/09-mozart-data-dashboards.md) | `Cases.csv`, `AlarmListingV2_New.xlsx`, `Master.xlsx`, Data Mapping, การอัปเดตด้วย Case ID และนำเข้าข้ามเดือน, Google Sheets Formula Pilot, Monthly Database / Central Summary / Control Database, Case และ Staff Performance Dashboard |
| 10 | [กำลังคนและการพัฒนาทีม](One%20Bangkok/10-staffing-training.md) | ตารางกะและวันหยุด, จำนวน Operator ต่อวัน, หน้าที่ Operator / Supervisor, Onboarding, การอบรมและประเมินผล |
| 11 | [แผนงาน Audit และจัดซื้อ](One%20Bangkok/11-planning-audit-procurement.md) | SOC Master Plan, ISO 45001 / HIRA, MOC เปลี่ยนบริษัท, เอกสารจัดซื้อและเหตุผลประกอบ PR, การติดตามคู่ค้าและงานแก้ไข |
| 12 | [เทมเพลตและไฟล์อ้างอิง](One%20Bangkok/12-templates-references.md) | แบบฟอร์มปฏิบัติงาน, อีเมลและข้อความประสานงาน, เทมเพลตรายงานและสไลด์, ไฟล์ต้นฉบับและเวอร์ชันที่ใช้งาน |
| 13 | [บริบทการทำงานกับ AI และโปรเจกต์ส่วนตัว](Personnal/13-ai-and-personal-projects.md) | รูปแบบภาษาและงานที่นุ่นชอบ, วิธีใช้และอัปเดต KB, เจ้าน้อย ลอตเตอรี่ N3, POM POM HOUSE, ข่าวติดฟีด, แผนเที่ยวเฉิงตู |

## การเติมเนื้อหาในรอบถัดไป

สำหรับแต่ละหัวข้อ ให้บันทึกชื่อไฟล์ต้นฉบับหรือแหล่งอ้างอิง วันที่ตรวจล่าสุด และสถานะ **มีเอกสารแล้ว / มีข้อมูลบางส่วน / ยังต้องจัดทำ** ก่อนขยายเป็นบทความ

ที่มาของสารบัญคือ KB ฉบับ 10 พฤศจิกายน 2026 และหัวข้องานที่นุ่นคุยต่อถึง 18 พฤศจิกายน 2026
