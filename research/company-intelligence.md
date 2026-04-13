# Company Intelligence Brief

**Purpose:** Rapid structured overview of a company — useful before sales calls, partnerships, or competitive analysis.

---

## Prompt

```
Act as a business intelligence analyst. Produce a concise intelligence brief on the following company.

Company: {{company name}}
Website: {{url if known}}
Research goal: {{what decision this informs}}

Cover:

1. **Company Overview**
   - What they do (one paragraph, plain language)
   - Founded, HQ, size (employees / revenue if public)
   - Business model (B2B / B2C / SaaS / marketplace / etc.)

2. **Product & Market**
   - Core product or service
   - Target customer segment
   - Key differentiators vs. competitors

3. **Traction & Signals**
   - Funding history (if startup)
   - Recent news, hires, product launches
   - Growth signals (job postings, traffic trends, press)

4. **Tech Stack** (if relevant)
   - Tools and technologies visible from public sources
   - Integrations, APIs, platforms they build on

5. **People**
   - Founders and key executives
   - Notable advisors or investors

6. **Red Flags / Open Questions**
   - Anything unusual, inconsistent, or worth investigating further

Keep it factual. Mark anything inferred or unverified. Use bullet points, not paragraphs.
```

---

## Variables

| Variable | Example |
|----------|---------|
| `{{company name}}` | Acme Corp |
| `{{url if known}}` | acme.com |
| `{{what decision this informs}}` | evaluating them as a potential client |

## Tips

- Paste in their homepage text to ground the model in real data
- Follow up with: *"What questions should I ask them in a discovery call based on this brief?"*
