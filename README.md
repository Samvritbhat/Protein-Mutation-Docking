# Protein Mutation & Stability Study (Computational Biochemistry)

**Author:** [Samvrit Bhat], 10th grade, Troy, MI  
**Focus:** Biochemistry + Chemistry + Structural Biology

## Research Question
How do different amino acid substitutions affect predicted protein stability (ΔΔG)?

## Why this matters
Protein mutations can disrupt folding and function and contribute to disease. Predicting mutation impacts helps guide research and drug discovery.

## Protein Studied
Protein: Hemoglobin (starter)  
Source: RCSB Protein Data Bank (PDB)

## Tools
- RCSB PDB (structure database)
- PyMOL (protein visualization)
- Stability prediction tools (mCSM / DUET / FoldX where available)
- Excel/Python (data analysis and graphs)

## Folder Structure
- `data/` → mutation dataset + results tables
- `images/` → PyMOL screenshots + graphs
- `notes/` → research notes and references
- `poster/` → poster PDFs
- `slides/` → presentation slides

## Current Status
- Week 1: repo setup + PyMOL setup + first structure screenshots (in progress)

## Next Steps
- Choose 12 mutations (6 near functional region, 6 far)
- Predict ΔΔG for each mutation
- Create graphs and summarize results
- Build a mini poster and deliver a 2-minute talk




































March 15th:
A major limitation of this analysis is that $\Delta\Delta G$ predicts folding stability, not functional viability. Mutations like V67D show positive stability (+0.66) but are clinically pathological because they disrupt Heme affinity. Similarly, E6V shows near-neutral stability but causes catastrophic protein aggregation (Sickle Cell) which a single-protein simulation cannot detect.
