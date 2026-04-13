# AI Agent System Prompt Builder

**Purpose:** Design a reliable system prompt for an AI agent with a specific role, constraints, and output format.

---

## Prompt

```
You are a prompt engineer specializing in AI agent design.

I need a system prompt for an AI agent with the following specs:

Agent role: {{what the agent does}}
Target user: {{who will interact with it}}
Main tasks: {{list 2-4 core tasks}}
Constraints: {{what it must never do}}
Output format: {{how it should respond — tone, length, structure}}
Tools available: {{list tools if any, or "none"}}

Write a complete system prompt that:
- Defines the agent's identity and purpose clearly
- Sets behavior boundaries (what it does and doesn't do)
- Specifies output format and tone
- Handles edge cases (off-topic requests, ambiguous input)
- Is between 200-400 words

Then explain in 3 bullet points why you made the key design choices.
```

---

## Variables

| Variable | Example |
|----------|---------|
| `{{what the agent does}}` | answers customer support questions for a SaaS product |
| `{{who will interact with it}}` | paying customers, non-technical |
| `{{list 2-4 core tasks}}` | answer FAQ, troubleshoot errors, escalate to human |
| `{{what it must never do}}` | make promises about refunds, discuss competitors |
| `{{output format}}` | friendly, concise, max 3 sentences per reply |
| `{{tools available}}` | search knowledge base, create support ticket |

## Tips

- Test the generated system prompt by role-playing edge cases: *"What if user asks something off-topic?"*
- Iterate: paste the prompt back and ask *"What are the weakest parts of this system prompt?"*
