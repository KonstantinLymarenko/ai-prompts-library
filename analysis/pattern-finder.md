# Pattern & Insight Extractor

**Purpose:** Feed raw data or text and get structured insights, patterns, and anomalies — without writing code.

---

## Prompt

```
You are a data analyst. I will give you raw data or text. Your job is to find patterns, outliers, and actionable insights.

Data type: {{what kind of data — responses, logs, list of names, table, etc.}}
Goal: {{what I'm trying to understand or decide}}

---
{{paste your data here}}
---

Analyze and produce:

1. **Key Patterns**
   — Recurring themes, clusters, or trends
   — What appears most frequently and why it might matter

2. **Outliers & Anomalies**
   — What doesn't fit the pattern
   — Why it might be significant

3. **Gaps**
   — What's missing that you'd expect to see
   — What questions the data can't answer

4. **Top 3 Actionable Insights**
   — Specific, concrete takeaways
   — Each with a recommended next step

5. **Confidence Level**
   — High / Medium / Low
   — What additional data would increase confidence

Format: bullet points. Flag assumptions explicitly.
```

---

## Tips

- Works well with: survey responses, job descriptions, competitor features lists, social media comments, log files
- Follow up with: *"Which insight is most important if I can only act on one?"*
- For large datasets: split into chunks and ask for a meta-analysis at the end
