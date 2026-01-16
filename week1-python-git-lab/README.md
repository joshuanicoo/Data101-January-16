# Week 1 Python + Git Lab (Template)

Average bill length per penguin species

## Dataset chosen
Penguins  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv  
Recommended columns: `species` (category), `bill_length_mm` (numeric)

## How to run
```bash
python3 -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\Activate.ps1
pip install pandas matplotlib
pip freeze > requirements.txt
python analyze.py
```

## What it does
- Prints a chart showing the average beak length per penguin species.
- Generates `output/chart.png`

## Reflection (write 3–5 sentences)
Replace this section with your own reflection:
- What was the hardest part?
- What did you learn about Git commits (small commits, staging, meaningful messages)?

The group encountered several difficulties. First was, relearning the Git CLI due to some members' overeliance on GUI. Two is installing the python dependencies.

The group learned that small, clear commits are better than one big commit because they make it easier to track changes. Overall, it was helpful to practice the workflow of setting up a project step by step.
