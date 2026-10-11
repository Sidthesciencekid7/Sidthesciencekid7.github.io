---
layout: page
title: Neuro-Therapeutic Designer
description: Machine learning tool that predicts whether a drug candidate can cross the blood-brain barrier
importance: 3
category: work
---

A machine learning application that predicts blood-brain barrier (BBB) permeability, to help screen drug candidates for neurological inflammation. Enter a molecule as a SMILES string and the tool predicts whether it can reach the brain.

**How it works**

- A Random Forest classifier trained on the MoleculeNet BBBP dataset (2,000+ compounds).
- RDKit converts each SMILES string into molecular descriptors: lipophilicity (LogP), molecular weight, polar surface area (TPSA) and hydrogen-bond donors.
- A rule that blocks molecules over 400 Da, to cut false positives.
- An interactive ipywidgets dashboard for testing new molecules.

**Results**

- 85.5% accuracy on the held-out test set, with a false positive rate under 15%.
- It flagged fluorinated drug analogs as more likely to cross the barrier than the parent compound. In the case study, curcumin difluoride scored far higher than curcumin, which makes it a candidate for Alzheimer's treatment.

**Stack:** Python, scikit-learn, RDKit, pandas, ipywidgets.

[Source code on GitHub](https://github.com/Sidthesciencekid7/Neuro-Therapeutic-Designer)
