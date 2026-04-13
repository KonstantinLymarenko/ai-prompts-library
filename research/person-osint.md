# Person Intelligence Report

**Purpose:** Build a structured intelligence profile on a public figure or professional from open sources.

---

## Prompt

```
You are an OSINT analyst. Your task is to build a structured intelligence profile based on publicly available information.

Subject: {{full name}}
Context: {{why this research is needed / what decision it informs}}

Using only open-source information, produce a report with these sections:

1. **Identity & Background**
   - Full name variants, known aliases
   - Approximate age / location
   - Education and professional background

2. **Digital Footprint**
   - Social media presence (platforms, usernames, activity level)
   - Professional profiles (LinkedIn, GitHub, personal site)
   - Published content (articles, interviews, posts)

3. **Professional Network**
   - Known employers, clients, partners
   - Key relationships and affiliations
   - Organizational memberships

4. **Key Claims vs. Evidence**
   - What they claim publicly
   - What can be independently verified
   - Any inconsistencies worth noting

5. **Risk Signals** (if any)
   - Legal records, controversies, reputational issues
   - Conflicting information across sources

6. **Confidence Assessment**
   - Rate confidence (High / Medium / Low) for each section
   - List sources used

Format: structured report, professional tone. Flag unverified claims explicitly.
```

---

## Variables

| Variable | Example |
|----------|---------|
| `{{full name}}` | John Smith |
| `{{why this research is needed}}` | due diligence before a business partnership |

## Tips

- Add known details upfront to anchor the model: *"Known email: j.smith@company.com, LinkedIn: linkedin.com/in/..."*
- Ask for sources inline: the model will caveat what it can't verify
- Run follow-up: *"Expand section 3 with LinkedIn connections if visible"*

## Best for

Due diligence, partnership vetting, competitive intelligence, journalism research
