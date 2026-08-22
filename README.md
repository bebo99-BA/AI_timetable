# AI Timetable Scheduler (CSP)

An AI-based university timetable generator that uses Constraint Satisfaction Problem (CSP) techniques to build a conflict-free class schedule, deployed as a web app.

## Overview
This project generates the ERU Spring 2026 timetable by modeling course scheduling as a CSP — assigning courses, rooms, and time slots while satisfying constraints like no overlapping classes or double-booked rooms. The solution logic lives in `Case_1 (2).ipynb`.

## Live App
🔗 https://eru-timetable-app.vercel.app

## Tech Stack
- Python
- CSP solving (constraint satisfaction)
- pandas
- Jupyter Notebook

## Files
- `Case_1 (2).ipynb` — CSP model and solving logic
- `ERU_Timetable_Spring2026 (1).xlsx` — generated timetable (Excel)
- `ERU_Timetable_Spring2026_CSP.csv` — generated timetable (CSV)

## How to Run
```bash
git clone https://github.com/bebo99-BA/AI_timetable.git
cd AI_timetable
pip install pandas jupyter
jupyter notebook "Case_1 (2).ipynb"
```

## Author
**Ahmed Mahmoud (Bebo)** — Business Analytics student, Egyptian Russian University
[GitHub](https://github.com/bebo99-BA)
