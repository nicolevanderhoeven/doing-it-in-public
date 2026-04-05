# How This Book Is Being Made

*Doing It in Public* is being written in public — and that includes being transparent about how AI is involved in writing it.

This book argues that learning in public has never mattered more than it does in the age of AI. It would be dishonest to write that book without being open about how AI helped write it.

---

## The Collaboration

This book is a collaboration between **Nicole van der Hoeven** (author) and **Iris** (an AI assistant built on Claude, running via [OpenClaw](https://openclaw.ai)).

**Nicole's role:**
- Sets the intent for every chapter — the argument, the audience, the feeling
- Writes from personal experience
- Revises, rewrites, and makes all final decisions
- Decides what stays and what goes

**Iris's role:**
- Researches and surfaces relevant material from Nicole's Obsidian vault (~13,000 notes)
- Drafts initial structures and skeletons based on Nicole's intent
- Generates options for Nicole to react to, not conclusions to accept
- Tracks the process and keeps the specs up to date
- Does NOT make decisions about what the book argues — that's Nicole's

The goal: AI as scaffold, not substitute. Every word that ends up in the published book has been read, judged, and either kept or changed by Nicole.

---

## Commit Conventions

Every commit to this repo is tagged to show who drove the change:

| Tag | Meaning |
|-----|---------|
| `[nicole]` | Nicole wrote or substantially revised this |
| `[iris]` | Iris generated this draft (Nicole has reviewed it) |
| `[collab]` | Emerged from conversation — neither fully owns it |
| `[process]` | Infrastructure, specs, process docs |

Examples:
```
[iris] Chapter 2: initial draft from vault research and brainstorm
[nicole] Chapter 2: rewrote AI section, added personal anecdotes
[collab] Book intent: pivoted to AI-era focus (April 2026)
[process] Set up specs/ and process/ folder structure
```

---

## The Specs System

Every chapter has a folder in `specs/chapters/`. Each folder contains:

- **`intent.md`** — Nicole's intent for the chapter: what it argues, who it's for, what the reader should feel. Written by Nicole before drafting begins.
- **`design.md`** — Iris's proposed structure: sections, flow, vault sources to draw from, open questions. Generated after intent is set.
- **`tasks.md`** — What still needs to be done on this chapter. Updated as work progresses.

The specs are committed alongside the content. Anyone can read a chapter and then read what it was *supposed* to do — and see how the two compare.

---

## Chapter Provenance

Each chapter file includes frontmatter tracking its lineage:

```yaml
provenance:
  intent_by: nicole
  first_draft_by: iris
  current_draft_by: nicole
  iris_contribution: "initial structure, vault research, AI section outline"
  nicole_contribution: "full rewrite of intro, all personal stories, revised AI section"
```

This isn't about credit — it's about honesty. The reader deserves to know.

---

## The Process Log

Key conversations and decisions are captured in `process/`. These are lightly edited records of the actual collaboration: brainstorms, pivots, disagreements, decisions. They're published because the process is part of the book.

---

## Why This Matters

This book is about using AI to supplement your thinking, not supplant it. The way this book is being written is a demonstration of that thesis.

If you're curious about what that actually looks like in practice — messy, iterative, sometimes Iris drafts something and Nicole throws it out, sometimes Nicole asks a question and Iris surfaces a vault note from three years ago that reframes the whole thing — you can read the process log and the specs. It's all here.

*The garage door is up.*

---

## Branch and PR workflow

All changes from Iris go through a pull request. Never directly to `v4`.

**Iris's workflow:**
1. Create a branch: `iris/<description>` (e.g., `iris/chapter-2-draft`, `iris/specs-update`)
2. Commit with the appropriate tag (`[iris]`, `[process]`, etc.)
3. Push the branch and open a PR
4. Nicole reviews and merges

Nicole can push directly to `v4` at any time.

**Exception: build-critical fixes** (broken YAML, workflow files, broken dependencies) may be pushed directly to `v4` without a PR when the site is actively broken and the change is trivially small. Nicole confirmed this on April 5, 2026.

*Note: The initial process setup commit (2e965de) was pushed directly to v4 by mistake. Subsequent Iris commits go through PRs except for build-critical fixes as above.*
