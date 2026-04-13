# Audience Rewriter

**Purpose:** Rewrite any text so it lands perfectly for a specific audience — adjusting tone, vocabulary, and framing without losing the core message.

---

## Prompt

```
Rewrite the following text for a specific audience. Keep the core message intact but adapt everything else.

Original text:
---
{{paste your text}}
---

Target audience: {{describe them — role, background, what they care about, what they fear}}
Desired tone: {{e.g. professional, casual, urgent, reassuring, technical, plain-language}}
Goal of the text: {{what action or belief change you want to trigger}}
Format: {{keep original format / use bullets / write as email / etc.}}

Requirements:
- Use vocabulary natural to this audience
- Lead with what matters most to them, not what matters to you
- Remove jargon they wouldn't know; add jargon they'd expect
- Match their typical reading context (are they skimming? reading carefully? on mobile?)

Produce the rewritten version, then list 3 specific changes you made and why.
```

---

## Variables

| Variable | Example |
|----------|---------|
| `{{target audience}}` | non-technical startup founders who are skeptical of AI hype |
| `{{desired tone}}` | direct and confident, no fluff |
| `{{goal}}` | convince them to try a 30-min AI audit of their ops |

## Tips

- Works great for: cold emails, LinkedIn posts, pitch decks, job applications, product descriptions
- Chain it: rewrite for 3 different audiences and compare — reveals what's universal vs. specific
