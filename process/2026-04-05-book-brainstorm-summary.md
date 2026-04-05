# Process Log: Book Pivot + Collaboration Setup

*Date: April 5, 2026 | ~16:41–19:51 UTC*
*Participants: Nicole van der Hoeven, Iris (OpenClaw)*
*See also: [transcript](transcripts/2026-04-05-book-brainstorm-transcript.md)*

---

## What we worked on

1. Drafted a revised outline for the book incorporating AI as a central theme
2. Brainstormed whether the book's premise holds up against existing books
3. Nicole decided to pivot the book to make AI central, not peripheral
4. Agreed on the book's new thesis
5. Designed the collaboration tracking structure for the book
6. Set up the repo: `PROCESS.md`, `specs/`, `process/`, commit conventions, chapter provenance

---

## Key decisions

### 1. The book needs a new spine, not just a new chapter

The 2024 outline was essentially *Show Your Work!* + PKM tiers — useful but not distinctive enough. The 2026 version makes AI the reason the book exists now.

Nicole's words: *"I think part of the reason I never got very far with the original book is that even then, it didn't have enough teeth."*

### 2. The new thesis

> *"AI can supplement your thinking, but it cannot — and should not — supplant it."*
> — Nicole van der Hoeven, April 5, 2026

The book argues that learning in public has never been more valuable than now — not despite AI, but because of it. When AI can produce competent output on demand, visibly doing the work yourself becomes the most human thing you can do.

### 3. Three essential features of the book (Nicole's words)

- The **observability angle** — systems engineering lens on learning; this runs through everything
- The **AI ethics angle** — how to use AI and not be used by it
- The **non-hustle frame** — learning in public because it makes you a better thinker, not to build a brand

### 4. What makes this book different from existing books

Reviewed: *Show Your Work!* (Kleon), swyx's "Learn in Public" essay, *Building a Second Brain* (Forte), *Ultralearning* (Young). Nicole's differentiation: lived experience of AI-augmented PKM, observability background, non-hustle philosophy, and the urgency of the AI question in 2026.

### 5. Collaboration tracking structure: Option 1 + 3 + 5

Nicole and Iris independently arrived at the same answer:
- **Git commit conventions** — `[iris]`, `[nicole]`, `[collab]`, `[process]` tags
- **Publish key conversations** — edited transcripts in `process/`
- **Adapted OpenSpec** — `specs/chapters/` with intent (Nicole) + design (Iris) + tasks per chapter

### 6. Session boundaries (new `dip-session` skill)

Nicole raised a legitimate concern: PRs are public the moment they're created. A new skill was created to manage explicit start/end boundaries for writing sessions. Nothing goes into a PR until Nicole says "end session."

---

## Open questions

- Does "Doing It in Public" remain the right title, or does the AI pivot want a new name/subtitle?
- Does the Tiers structure (Ch4–8) serve the new argument, or should structure follow the logic of the argument?
- Should the Introduction be updated to include an AI-era bookend alongside the Dutch story?

---

## Files created or changed this session

**In the repo:**
- `PROCESS.md` — collaboration methodology, commit conventions, branch/PR workflow
- `specs/README.md`
- `specs/book/intent.md` — book thesis and essential features
- `specs/book/outline.md` — working outline with status table
- `specs/chapters/introduction/intent.md`
- `specs/chapters/chapter-02-what-ai-changes/intent.md`
- `process/2026-04-05-brainstorm.md` *(pushed directly to v4 — superseded by this PR)*
- Updated provenance frontmatter on Introduction and Chapter 1

**In Nicole's Obsidian vault (output folder):**
- `DIP Book - Revised Outline - 2026-04-05.md`

**In Iris's workspace:**
- `skills/dip-session/SKILL.md` — new skill for session boundaries

---

## Note on the earlier direct push

The initial `[process]` setup commit and a follow-up correction were pushed directly to `v4` before the PR convention was established. This PR supersedes `process/2026-04-05-brainstorm.md` from that commit — if Nicole prefers, that file can be removed and replaced with this one.
