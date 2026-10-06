# Lab 2 · One defensible feature

Pair: Benjamin Levit and Martin Olivares 
Notebook: Lab2_Levit_Olivares.ipynb
Data: w04_race_weekends_synthetic_v3.csv 

## Question
Can one feature made from information available before the race improve the top-10 prediction?

## Split
Train: weeks 1–10. Validation: weeks 11–14. Reserved test: weeks 15–18 (not scored).

## Runbook
1. Clone the repository; the notebook and w04_race_weekends_synthetic_v3.csv must be in the same folder.
2. Create an environment and install: pip install -r requirements.txt
3. Open the notebook and choose Kernel > Restart & Run All.
4. Expected result: no errors and the three-row score table. The reserved test (weeks 15–18) is not scored.
5. Seed: random_state=42; the data are fixed in the CSV, so results are deterministic.

## Who did what
- Benjamin: Defining the proposal, and analyzing to write the decision
- Martin: Create candidate feature, and comparing pipelines

