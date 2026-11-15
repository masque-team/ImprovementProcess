# Improvement Process — IT Solution / Tower (Assist Channel)

พื้นที่ความรู้ตั้งต้นสำหรับวิเคราะห์ **As-Is IT Project Delivery** จากการสัมภาษณ์ทีม และ Workbook `Improvement Process.xlsx` เพื่อสื่อสาร Pain Points ต่อ CIO / C-Level

> **สถานะ:** Working baseline (15 Nov 2026). ยืนยันเฉพาะสิ่งที่มีหลักฐานจาก Excel หรือคำตอบที่ Confirm แล้ว; ภาพแนวคิดและตัวเลขประเมินแยกไว้ต่างหาก

## เริ่มอ่านที่นี่

1. [Project scope & interview decisions](docs/01-scope-and-decisions.md) — ขอบเขต, Strategy Project, บทบาท และประเด็นที่ตกลงกัน
2. [As-Is 12 stages / 7 workstreams](docs/02-as-is-process.md) — Mapping Stage, Actions ตัวอย่าง, เส้นทางวนกลับ
3. [Excel evidence & metric definitions](docs/03-evidence-and-metrics.md) — จำนวนรายการ, Loop, Time และข้อควรระวัง
4. [Visualization and presentation briefs](docs/04-visual-storyboard.md) — CI ดำ/แดง, Executive Hook, Snakes & Ladders, Monopoly board
5. [Open decisions / validation backlog](docs/05-open-questions.md) — สิ่งที่ยังไม่ควรยืนยันต่อผู้บริหาร
6. [Update protocol](docs/06-update-protocol.md) — วิธีเก็บข้อสรุปจากการคุยครั้งถัดไป

## Executive narrative

**The bottleneck is inside the delivery process.** Tower เข้าไปช่วยตั้งแต่ Requirement, BRD, Architecture, Budget/Procurement จนถึง SDLC และหลัง Go-live ซึ่งทำให้งานประสาน เอกสาร การอนุมัติ และ Rework มารวมอยู่บนทีม IT Solution

Scope ปัจจุบันคือ **Strategy Project / Assist Channel** เท่านั้น; ยังไม่ได้เก็บข้อมูลจากอีก ~5 domains แม้ใช้กรอบ Process คล้ายกัน

## Data safety

- ตัวเลขเป็น **catalog/estimated scenario data**, ไม่ใช่สถิติจริงของทุกโครงการ
- Step 6.1 (Existing Resource) กับ 6.2 (Bidding) เป็น **alternative paths**
- ตัวเลขเวลา 7–10 เดือนเป็น **interview-based indication**, ยังไม่ใช่ actual lead-time จาก timestamp
- ห้ามใช้ยอด `Loop × Days` บวกทุก Action แล้วอ้างว่าเป็นเวลาจริงของโครงการ
- `Loop=Y` หมายถึงมีโอกาสวนซ้ำ **ไม่ใช่** วนซ้ำจริงจำนวนหนึ่งครั้ง
- ภาพก่อนหน้าบางรุ่นมีตัวเลข/ชื่อ Stage คลาดเคลื่อน: **Excel source is the authority**


## Verified data & editable visualization

- [Stage-level CSV](data/stage-catalog-summary.csv) — 199 rows / 156 Loop=Y / 196 Tower=R / 195 substantive deliverables / 171 with timing fields
- [Black/red Rework Board (SVG)](diagrams/as-is-rework-board.svg) — editable, source-grounded perimeter-board concept; cross-stage arrows are illustrative scenarios, not measured occurrences
- [Document metrics and definitions](docs/03-evidence-and-metrics.md) — precise column mapping and evidence caveats

## Source references

- Primary: `Improvement Process.xlsx` (provided in ChatGPT conversation; not copied to this repository)
- Summary document: Google Docs ที่ผู้ใช้ส่งไว้ก่อนหน้า (ใช้เป็น secondary, ยังไม่ได้ยืนยันว่าเนื้อหาตรงกับ workbook ทุกจุด)
- [Presentation working file](https://docs.google.com/presentation/d/1hXJcu9A46jPMUkJftHJlPJXTqU3n3vcS_k9r_nyPmwg/edit)
