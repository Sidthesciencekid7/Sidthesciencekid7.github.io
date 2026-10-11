---
layout: page
title: QuarkClinical
description: AI platform for drafting and reviewing bioequivalence and PK clinical-trial protocols
importance: 1
category: work
---

QuarkClinical generates clinical-trial protocols for bioequivalence and biosimilar PK studies, then checks them against regulatory guidance (FDA, EMA, ICH M13A / M11).

**What it does**

- Drafts a full protocol from a drug name, using literature and label data.
- Runs deterministic engines for sampling schedules, safety gating, drug-drug interactions, randomization and sample size.
- Sample size comes from the R PowerTOST package, with a validated Python fallback.
- Role-based approvals, audit trail and per-organization data isolation for regulated workflows.
- Post-study module: non-compartmental analysis, bioequivalence analysis and an ICH E3-style report.

**Stack:** FastAPI, PostgreSQL, React, Clerk, Railway, Vercel, Claude API, R.

[Live app](https://frontend-pearl-eight-95.vercel.app)
