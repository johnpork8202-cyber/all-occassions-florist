# Second Brain

This repo is a personal knowledge base — a "second brain" — shared between John and Claude.

**How it works:**

1. **You put information in** — paste anything into `brain/inbox.md` (links, notes, rants, half-ideas, transcripts). No formatting required.
2. **Claude organizes it** — at the start of a session, Claude reads `CLAUDE.md` and `brain/index.md`, files whatever landed in the inbox, and can pull any of this knowledge into the conversation.
3. **It stays current on its own** — a scheduled routine web-searches AI / Anthropic / platform news daily and appends a dated digest to `brain/news/ai-anthropic.md`, so Claude knows recent events past its training cutoff.

**Layout:**

```
CLAUDE.md              Instructions Claude reads automatically each session
brain/
  index.md             Map of everything in the brain
  inbox.md             Drop zone — paste anything here, Claude files it
  news/
    ai-anthropic.md    Living digest of AI / Anthropic / Claude / platform news
  notes/               Organized notes, filed by Claude from the inbox
```

> Note: the repo is still named `all-occassions-florist` from an earlier idea.
> It can be renamed to something like `second-brain` in GitHub → Settings → Repository name;
> nothing here breaks if you do.
