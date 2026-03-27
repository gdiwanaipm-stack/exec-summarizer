---
name: exec-summarizer
description: Summarize a document into a concise executive briefing. Pass a file path as the argument.
---

Summarize the document at $ARGUMENTS into a structured executive briefing.

Follow the exec-summarizer skill instructions exactly:
1. Read the file at the provided path.
2. Analyze the full content.
3. Output the summary using this structure:

**EXECUTIVE SUMMARY — [Document Title or Filename]**

**Overview**
- What is this document? (type, purpose, author/source if identifiable)
- What problem or topic does it address?
- Time period or scope covered (if applicable)

**Top Takeaways**
- 3–5 most important insights, decisions, or findings
- Lead with the most impactful point first

**Issues / Blockers**
- Risks, gaps, unresolved questions, or concerns raised in the document
- If none, state: "No blockers or issues identified."

**Next Steps**
- Actions, recommendations, or decisions required
- Include owners or deadlines if mentioned in the document
- If none, state: "No explicit next steps outlined."

Keep the entire summary under 300 words unless document complexity requires more.
