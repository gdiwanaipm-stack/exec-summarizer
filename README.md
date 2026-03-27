# exec-summarizer

A Claude Code plugin that summarizes documents into concise executive briefings.

## What it does

Reads any document (PDF, Word, PowerPoint, spreadsheet, plain text) and produces a structured summary for C-suite and VP-level audiences — covering overview, top takeaways, issues/blockers, and next steps.

## Triggers automatically on

- Sharing a file path or uploading a document
- Phrases like: "summarize this", "give me a summary", "TL;DR", "brief me on this", "what are the key points"

## Install

```bash
/install-plugin github.com/<your-username>/exec-summarizer
```

## Usage

```
/exec-summarizer path/to/document.pdf
```

Or just share a file and Claude will summarize it automatically.

## Output format

- **Overview** — document type, purpose, scope
- **Top Takeaways** — 3–5 most important insights
- **Issues / Blockers** — risks or unresolved questions
- **Next Steps** — actions, owners, deadlines
