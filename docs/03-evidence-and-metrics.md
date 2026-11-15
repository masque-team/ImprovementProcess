# 03 — Source Evidence, Numbers & Calculation Rules

**Primary source:** `Improvement Process.xlsx`, worksheet `ชีต1`, Stage field in **B**, Tower Action **I**, Deliverable **J**, Loop flag **K**, Loop min/max **L/M**, days per round min/max **N/O**, Tower RACI **R**.

## Verified catalog counts (source snapshot from Nov 2026)

| Metric | Result | Correct interpretation |
|---|---:|---|
| Stage rows | **199** | Includes both 6.1 and 6.2 branches and approval/checkpoint rows |
| Rows marked Loop=Y | **156** | Potentially iterative catalog entries, **not** actual number of rework cycles |
| Rows with Tower containing R in column R | **196** | RACI responsibility at catalog row level, **not** 196 people or 196 executed tasks |
| Rows with meaningful named Tower Action (not blank or `-`) | **195** | Four rows have no substantive Action text |
| Deliverable entries with substantive content (not `-`/blank) | **195** | **Not 195 unique document files**; includes code, tests, support and other outputs |
| Rows with both time min and max numerically present | **171** | Others have incomplete or missing timing |
| Stage 8 rows | **100** | Concentrated group (not 100 steps of one mandatory serial path) |
| Stage 8 marked Loop=Y | **87** | Loop exposure, not actual repetition count |
| Stage 8 rows whose Deliverable mentions SRA | **54** | Workbook also labels its SRA checklist as `55 Topics`; reconcile 54 vs 55 before external claims |
| Stage 8 rows with User Request Form | **13** | Infrastructure request topics |
| Stage 11 + 12 rows | **14** | Includes go-live and post-go-live work; not all necessarily support |

## Time interpretation — critical

- `L/M` are **Min/Max loop counts**, as explained by the team.
- `N/O` are **Min/Max days per cycle**.
- Example **Step 1 IT Assessment**: 3–7 cycles at 3–15 days per cycle, producing **9–105 cycle-days (scenario bound)**.
- Example **Step 8 SRA**: 3–5 cycles at 10–20 days/cycle → **30–100 cycle-days per applicable action (scenario bound)**.
- Scenario bounds **are not** calendar duration of a project, not FTE / mandays, and not automatically waste. Many workstreams run in parallel, some actions share a common review cycle, and stages 6.1/6.2 are alternatives.
- A previous naive `Σ(actions × loop count × days)` across the entire catalog is **invalid as portfolio delivery time**.
- **7–10 months/project** is the team's indicative end-to-end range **from interviews**, not directly computed from the workbook. It should be labelled *reported / to validate* in a CEO slide.
- Data for 9, 11, 12 has no loop flags; do not convert blanks to `0 actual repeats`.

## Document taxonomy — proposed, not verified total

Presentation drafts explored **6 groups**:
1. SRA / readiness & compliance
2. Request forms, finance, approvals & procurement
3. Requirement, impact assessment, solution design
4. Governance slides, status, reporting & planning
5. Testing / QA / security evidence
6. Operations, runbook, handover, WR/WI

Previous draft graphics quoted **174 document-related entries** and grouped counts `55/45/32/22/12/8`. These were **heuristic classifications**, not a confirmed audit of unique document files. **Do not reproduce as audited numbers until classification rules and row-by-row mapping are reviewed.**

## What remains needed for a defensible CEO timing / savings claim

Project-level execution log with: `project_id`, `stage/action_id`, `start_at`, `end_at`, `owner`, `effort_hours`, `waiting_hours`, `loop_reason`, `parallel_group`, `document_id`, `approval_outcome`.

Then calculate:
- actual end-to-end lead time (p50/p75/p90)
- tower active work hours vs waiting days
- rework rate, first-pass approval and cycle time per action
- document unique count vs version count vs submission count
- post-go-live support hours / project, plus opportunity cost

## Source priority for contradictory figures
1. Original workbook **raw cells** for catalog quantities
2. Explicit workshop confirmations for process interpretation
3. Manual classification / assumptions labelled `proposed`
4. Generated illustrations (lowest evidentiary weight)

**Never infer criticality/efficiency percentage from a graphic** unless a documented calculation exists; past images used arbitrary 62% efficiency and some inaccurate stage counts.
