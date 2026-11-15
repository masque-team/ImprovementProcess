# Source-data derivations

The table `stage-catalog-summary.csv` is a **verified aggregate** from `Improvement Process.xlsx` worksheet `ชีต1` rows 3–207, excluding unrelated notes at rows 209–210.

**Definitions**:
- `catalog_rows`: a row with numeric project stage in column B
- `loop_flag_Y`: column K exactly Y
- `tower_R`: column R contains R as a RACI role
- `substantive_deliverables`: column J contains nonempty content other than `-`
- `rows_with_time_min_and_max`: both N and O numeric

**Important**:
- The sum includes **both** Stage 6.1 and Stage 6.2, which are **alternative** paths and not always performed together
- Loop flag count is **not** the number of actual rework events
- A zero `loop_flag_Y` count may mean **not captured**, especially Stage 9/11/12
- Deliverable entries are **not** unique document file counts
- Time data are per action/cycle bounds, not actual portfolio lead time
- Timestamp of verification: **2026-11-15** (source file snapshot received earlier in conversation).
