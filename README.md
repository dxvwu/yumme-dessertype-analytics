# yumme-dessertype-analytics

Analytics + SQL portfolio project for **Yumme.club — DessertType**, an illustrated personality quiz MVP.

This repo documents a phase-based approach to product analytics:

- Phase 1: Synthetic survey research (available now)
- Phase 2: Real survey research (planned)
- Phase 3: Post-launch engagement analytics (planned)

---

## Phase 1: Synthetic Research (Current)

Phase 1 uses a synthetic multiple-choice survey dataset to prototype the analytics workflow and generate early product insights.

This phase helps answer questions like:

- What quiz length do users prefer?
- Which result formats feel most shareable?
- Are users likely to download or retake the quiz?

Note: Phase 1 data is synthetic and is not presented as real user research.

---

## Repo Structure

```text
synthetic_research_phase/
  survey_data/
    dessertype_survey_synthetic_mc_only_clean.csv
  sql_queries/
    phase1_insights.sql
  notes/
    findings_summary.md

real_research_phase/ (placeholder)

engagement_analytics_phase/ (placeholder)
```

---

## Tools Used

- SQLite (SQL querying)
- Google Sheets (optional CSV viewing)
- Looker Studio (planned dashboarding)

---

## Next Steps

- Replace synthetic survey data with real survey exports (Phase 2)
- Track post-launch engagement events such as:
  quiz_start, quiz_complete, share_click, download_click, retake_click

---

## Project Context

DessertType is part of Yumme.club, a cozy illustrated quiz experience designed to create highly shareable, collectible personality results.

