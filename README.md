# datasets-ICA4
ICA 4 questions, code, and visualizations

## Description of datasets.sat_scores
SAT scores from different schoolds, teachers, and students.

## Question #1
What school had the student with the highest sat score?

```sql
SELECT school, sat_math+sat_verbal as Total_score
FROM datasets.sat_scores
ORDER BY Total_score DESC 
LIMIT 1
```

![datasets-ICA4]
