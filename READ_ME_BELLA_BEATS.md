# Bellabeat Case Study: When Do Smart Device Users Actually Move?

**Tools:** R (tidyverse, ggplot2, lubridate) · Kaggle · Tableau Public
**Links:** [Full R notebook on Kaggle](https://www.kaggle.com/code/lwalker8264/bella-beats-capstone-project) · [Tableau dashboard](https://public.tableau.com/views/BellaBeatsDataPlotShowcase/Dashboard1)

---

## The question

Bellabeat makes health-focused smart devices for women. Their marketing team wanted to know:

1. What are the trends in how people use smart fitness devices?
2. How do those trends apply to Bellabeat customers?
3. How should those trends shape Bellabeat's marketing?

## The short answer

- **Activity peaks around 6:30 PM.** Most steps happen between 8 AM and 6:30 PM, with the biggest spike right after the typical workday ends.
- **Saturdays are the most active day, and Sundays drop off.** Across April and May 2016, Saturday step totals were consistently the highest of the week.
- **Recommendation:** time marketing to reach people on their way home from work (about 3 to 5 PM), and put more campaign effort into weekends.

![Daily Steps per Hour](Daily%20Steps%20per%20Hour.png)

---

## The data

- **Source:** [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) (Möbius, Kaggle), public domain (CC0)
- **What it contains:** daily activity, hourly steps and sleep records from 30 FitBit users who consented through an Amazon Mechanical Turk survey
- **Limitations I kept in mind:**
  - Only
