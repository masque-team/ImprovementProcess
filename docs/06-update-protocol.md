# 06 — Project Memory / Git Update Protocol

Use this repository as the **source of project context** in future ChatGPT conversations. Nothing will be synchronized automatically unless a future conversation explicitly requests or authorizes a GitHub update.

## After every substantive discussion
1. Read `README.md` and the relevant docs first
2. Distinguish decisions marked **Confirmed**, **Proposed**, **Unknown**, **Superseded**
3. Add a dated entry to `docs/decision-log.md` including: question, exact approved decision, actor/source, impact, files to update
4. Update only affected docs, diagrams or data tables; never silently rewrite confirmed decisions
5. Update `docs/05-open-questions.md` when a question is answered
6. Commit with a meaningful message: `docs: confirm <topic> (YYYY-MM-DD)`
7. Link the commit to the user and summarize what changed

## Rules
- **ห้ามคิดเอง ให้คอนเฟิร์มก่อน** if ambiguity would change official requirements or measured facts
- Original Excel + meeting confirmation outrank AI visuals
- Do not commit unreviewed personal/company-sensitive raw data or full vendor quotations
- Do not turn convenience percentages, assumed durations or illustrative flow arrows into official KPIs
- Preserve one canonical current answer; mark obsolete views as Superseded with date and rationale
- For multiple simultaneous editors, use a branch/PR rather than overwrite directly on main

## Suggested future folders
```
data/          # Verified action-level exports with source row IDs
docs/          # Interview notes, decisions, metrics, pain points, To-Be hypotheses
diagrams/      # Source-editable Mermaid / SVG flows and boards
assets/review/  # Draft visuals only, clearly marked unverified
slides/        # Approved final executive deck
```

## Starter prompt to continue work
> Read `masque-team/ImprovementProcess` first. Summarize confirmed As-Is process, source metrics and pending decisions. Then ask one concrete clarification before proposing a change. Do not infer real lost days from catalog loop ranges. When I approve a new decision, update the relevant Markdown and commit it to the repo.
