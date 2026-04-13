# Complex Task Decomposer

**Purpose:** Break down a vague or complex goal into a clear, executable action plan — useful before building automations or delegating to AI agents.

---

## Prompt

```
You are an expert at breaking down complex goals into executable steps for AI-assisted workflows.

Goal: {{describe what you want to achieve}}
Context: {{relevant background — tools available, constraints, team size}}
Output format: {{final deliverable — document, automation, report, etc.}}

Produce:

1. **Clarifying Questions** (max 5)
   — Things that, if answered, would significantly change the approach

2. **Step-by-Step Plan**
   — Number each step
   — For each step: what happens, who/what does it (human or AI), input required, output produced

3. **Automation Opportunities**
   — Which steps could be automated with n8n, Zapier, or an AI agent
   — Suggested tools for each

4. **Risk Points**
   — Where things are most likely to break or need human review

5. **Definition of Done**
   — How to know the goal is achieved

Be specific. Avoid vague steps like "research the topic" — instead write "search Google for X, collect top 5 results, extract Y."
```

---

## Tips

- Answer the clarifying questions yourself first, then re-run the prompt with answers included
- Use output as a blueprint for building an n8n workflow or Claude agent
