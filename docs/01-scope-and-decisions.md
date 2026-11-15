# 01 — Scope, Stakeholders & Interview Decisions

## Purpose
สร้างหลักฐาน As-Is ให้ผู้บริหารเห็นว่า **IT Solution (Tower)** ถูกใช้ Capacity อย่างไรตั้งแต่เริ่ม Strategy Project จนส่งมอบ Operations โดยเฉพาะงาน Non-core SDLC, งานวนกลับ, การอนุมัติและงานเอกสาร

## In scope (confirmed in conversation)
- **Assist Channel เท่านั้น**: Process Catalog มาจากการเก็บข้อมูลภายในโดเมนนี้; อีกประมาณ 5 domains ยังไม่ได้ลงเก็บข้อมูล
- Project levels มี 4 ระดับ: **Strategy** (โฟกัสปัจจุบัน), Major, Normal, Standard
- งานอาจ initiate โดย **Business/Executives หรือ IT**; IT BP และ Tower ร่วมเก็บ Requirement และประเมินผลกระทบ
- เป้าหมายปัจจุบันเป็น **As-Is / evidence first**: เล่า Pain Points ให้หนักแน่นก่อนแนะนำ To-Be
- ครอบคลุม **12 Project Stages และ After Go-live Support**; มี Resource path 6.1 / 6.2 เป็นทางเลือก
- การนำเสนอ: 7 workstreams (เวอร์ชันแก้ล่าสุด), 12 stages, action-level detail; การวนกลับแสดงด้วยเส้นแดง
- ไม่มีการนำการประมาณจากภาพ AI มาแทนค่าจาก Excel โดยอัตโนมัติ

## Key stakeholders
| Role | Confirmed role / involvement |
|---|---|
| Business / Budget Owner | Initiator ได้; กรณี business-led ใช้งบฝั่ง Business อนุมัติ |
| IT BP | รับ/ประสาน Requirement, ประเมินกับ Tower, ช่วยจัดการ budget |
| IT Solution / Tower | Impact/Solution assessment, เอกสารและประสาน approvals, procurement support, SDLC, fact finding เมื่อมี change |
| Solution Architecture (SoArc) | ประเมินผลกระทบสถาปัตยกรรมร่วมกัน |
| Security / EA COE | Security, infrastructure, enterprise architecture assessment |
| CIO / Committee | พิจารณา IT-led appraisal / Strategy change decisions |
| SCB | Budget defense, ตรวจความสมเหตุสมผล |
| RVM / Procurement | Resource/vendors, e-bidding / commercial cross-check |
| IT PM (PMO) | PM ของโครงการ ร่วม kick-off และ track execution |
| Operations / APO | ผู้รับส่งมอบและ support หลัง Go-live |

> Role ownership ต่อ Action ต้องยึด RACI ในไฟล์ต้นทางและยืนยันก่อนทำ To-Be

## Confirmed process nuances
1. หลัง Requirements และ Impact Assessment พร้อม → เข้าสู่ Approval
2. Business-led approval โดยผู้ถืองบ; IT-led proposal ต้องผ่าน appraisal ที่เกี่ยวข้องกับ Business / CIO
3. หลัง budget approval มี SCB defense และ resource allocation/acquisition
4. IT Solution สามารถขอ quotation vendor ได้เอง; Procurement เป็นผู้ cross-check/process การจัดซื้อ
5. Kick-off ต้องมีผู้เกี่ยวข้องตาม RACI และอธิบายวัตถุประสงค์/ผลกระทบ
6. เมื่อ Requirements เปลี่ยนกลางทางหรือกระทบ node อื่น ต้องทำ impact / replan; Tower เป็นผู้ให้ fact สำคัญใน Committee
7. Strategy projects โดยทั่วไปมี Committee ร่วม Business, IT BP, IT PM, และ Tower ให้ข้อมูล

## Presentation message
> **IT Solution is not only delivering technology. It is absorbing process workload from requirement through approvals, procurement and post-go-live support.**

## Confidence
- **Confirmed by discussion:** scope, stage concept, actor roles, emphasis on As-Is, loop-visual expectation
- **Evidence from workbook:** action-level details/columns/flags/counts
- **Not yet measured:** real effort hours, actual parallel path, actual cycle-time and cost of rework
