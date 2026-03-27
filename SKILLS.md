# Skills — exec-summarizer

This plugin provides the following skill:

## exec-summarizer

**Trigger phrases:**
- "summarize this"
- "give me a summary"
- "what is this about"
- "summarize for execs"
- "TL;DR"
- "brief me on this"
- "what are the key points"
- Sharing a file path or uploading a document without a specific instruction

**Supported file types:**
- PDF (`.pdf`)
- Word (`.docx`)
- PowerPoint (`.pptx`)
- Spreadsheet (`.xlsx`)
- Plain text (`.txt`, `.md`, etc.)

**Output structure:**

| Section | Description |
|---|---|
| Overview | Document type, purpose, author/source, scope |
| Top Takeaways | 3–5 most important insights, leading with highest impact |
| Issues / Blockers | Risks, gaps, unresolved questions |
| Next Steps | Actions, owners, deadlines (if mentioned) |

**Allowed tools:** `Read`, `Glob`, `Grep`

**Location:** `skills/exec-summarizer/SKILL.md`
