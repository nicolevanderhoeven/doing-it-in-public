# Writing Process

*How Nicole and Iris write this book together.*
*Adapted from OpenSpec for prose. Established: April 5, 2026.*

---

## Philosophy

Nicole writes. Iris scaffolds, challenges, and edits.

The goal is for every word in the published book to have been read, judged, and either kept or changed by Nicole. AI can supplement thinking — it cannot supplant it. This process is designed to make that distinction concrete and visible at every stage.

Every stage is committed to the repository. Every decision is traceable. Anyone can read a finished chapter and follow its entire history: the intent that shaped it, the structure that preceded it, the challenges that strengthened it, and the drafts that became it.

---

## The Seven Stages

```
1. Intent       Nicole sets the argument
2. Design       Iris proposes structure
3. Challenge    Iris asks the hard questions
4. Writing Plan Iris generates, Nicole owns
5. Draft        Nicole writes
6. Review       Iris reads and responds
7. Revise       Nicole decides
```

---

## Stage 1: Intent
**Who:** Nicole  
**File:** `specs/chapters/[chapter-slug]/intent.md`  
**Committed by:** Nicole `[nicole]` or Iris on Nicole's behalf after conversation `[collab]`

Nicole defines the chapter before anyone drafts it. The intent document answers:

- **The argument** — what is this chapter claiming?
- **The audience** — who is this for, specifically?
- **The feeling** — what should a reader feel when they finish this chapter?
- **Personal material** — what experiences, stories, or observations from Nicole's life belong here?
- **What this chapter is NOT** — what to leave out or save for elsewhere

Iris can help Nicole draft the intent document in conversation, but Nicole must approve every line before it's committed. The intent is Nicole's contract with herself about what she's writing.

**The chapter does not proceed until the intent is approved.**

---

## Stage 2: Design
**Who:** Iris  
**File:** `specs/chapters/[chapter-slug]/design.md`  
**Committed by:** Iris `[iris]` via PR → Nicole approves before Stage 3

Iris takes the approved intent and proposes:

- **Section structure** — headings and flow, with one-line summaries of what each section does
- **Evidence and examples** — what vault material, research, or personal stories support each section
- **Sources** — relevant books, talks, notes from Nicole's vault to draw on
- **Open questions** — things the design doesn't resolve yet
- **Risks** — where the argument might be weak, what a sceptical reader will push back on, what's missing

The design is a proposal, not a directive. Nicole can approve it as-is, request changes, or restructure it entirely. Prose doesn't always follow its plan — the design is a starting point, not a constraint.

**The chapter does not proceed until the design is approved.**

---

## Stage 3: Challenge
**Who:** Iris  
**File:** `specs/chapters/[chapter-slug]/challenge.md`  
**Committed by:** Iris `[iris]` via PR  
**Nicole responds:** in conversation or by annotating the file before writing begins

After the design is approved, Iris asks 3–5 hard questions about the argument. These are the questions a sceptical, smart reader will bring to the chapter. Better to surface them before writing than to discover them in feedback.

Examples of the kinds of questions:
- "You're claiming X — but what about Y? How do you handle that objection?"
- "This section assumes the reader already believes Z. Do they?"
- "Is there a version of this argument that's more uncomfortable to make? Should you make it?"
- "Where does this argument break down? Are you addressing that, or avoiding it?"

Nicole answers in conversation. Her answers inform what she writes in Stage 5.
The challenge document and Nicole's responses are committed together so readers can see what the chapter was stress-tested against.

---

## Stage 4: Writing Plan
**Who:** Iris generates, Nicole owns  
**File:** `specs/chapters/[chapter-slug]/tasks.md`  
**Committed by:** Iris `[iris]` via PR → Nicole can add, remove, reorder before starting

Iris breaks the approved design into a writing task list. Tasks are small enough for a single sitting. Each task is something Nicole writes, not something Iris does.

Task format:
```markdown
- [ ] Write the opening anecdote (target: 200–300 words)
- [ ] Draft section: The authenticity question (target: 400 words)
- [ ] Find the right Kleon quote for the "show your work" argument
- [ ] Resolve: do we include the Jorge Arango example here or in Chapter 3?
- [ ] Write transition from section 2 to section 3
```

Nicole checks off tasks as she writes. The task file becomes a live record of progress.

---

## Stage 5: Draft
**Who:** Nicole  
**Committed by:** Nicole `[nicole]` directly to a chapter branch

Nicole writes. Iris does not touch the prose unless explicitly asked.

If Nicole wants Iris to write a section — a placeholder, a scaffold, a section she's genuinely stuck on — that is a deliberate choice Nicole makes explicitly. It is committed `[iris]` with a note in the provenance frontmatter. This is the exception, not the default.

Nicole commits drafts to a `nicole/[chapter-slug]-draft` branch. Partial drafts are fine — commit often, write freely.

When Nicole is ready for review, she opens a PR from her draft branch to `v4` and tags Iris.

---

## Stage 6: Review
**Who:** Iris  
**Method:** PR comments on Nicole's draft PR  
**Committed by:** Iris `[iris]` via review branch if changes are substantial

Iris reads the draft and responds with:

- **What's working** — specifically, not generically
- **What's unclear** — where a reader would lose the thread
- **Argument gaps** — where the claim isn't supported, or where a counterargument needs addressing
- **Socratic questions** — questions that invite Nicole to go deeper, not suggestions to add content
- **Edit suggestions** — specific, offered as options Nicole can take or leave. Iris suggests; Nicole decides.

What Iris does NOT do in review:
- Rewrite Nicole's prose (unless Nicole asks)
- Make the decision about whether to keep or cut something
- Add content that wasn't in the Writing Plan without flagging it as new

---

## Stage 7: Revise
**Who:** Nicole  
**Committed by:** Nicole `[nicole]`

Nicole reads Iris's review, decides what to take and what to ignore, and revises. There is no rule about how much to use — Nicole might take everything, nothing, or something in between.

When Nicole is satisfied, she merges her PR to `v4`.

---

## Provenance frontmatter

Every chapter file carries a record of who contributed what:

```yaml
provenance:
  intent_by: nicole
  design_by: iris
  first_draft_by: nicole
  iris_contribution: "structure proposal, challenge questions, PR review comments"
  nicole_contribution: "full draft, all personal stories, revision decisions"
  status: "draft | in-review | revised | published"
```

---

## Commit conventions (recap)

| Tag | Used when |
|-----|-----------|
| `[nicole]` | Nicole wrote or substantially revised this |
| `[iris]` | Iris generated this (Nicole has reviewed it) |
| `[collab]` | Emerged from conversation — neither fully owns it |
| `[process]` | Infrastructure, specs, process docs |

---

## Branch conventions

| Branch | Used for |
|--------|---------|
| `iris/[description]` | All Iris-initiated changes — always via PR |
| `nicole/[chapter-slug]-draft` | Nicole's chapter drafts |
| `v4` | Published / Nicole merges only |

---

## What this process makes visible

Someone reading this book can also read:
- What Nicole intended each chapter to do (intent)
- How Iris proposed to structure it (design)
- What hard questions were asked before writing (challenge)
- What the writing plan was (tasks)
- How the prose evolved from first draft to published (commit history)
- Who contributed what at each stage (provenance + commit tags)

This is not documentation added after the fact. It is the process, committed as it happens.

---

*The garage door is up.*
