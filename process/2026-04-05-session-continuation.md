# Session Summary: Book Design Through Stage 4

*April 5, 2026 — approximately 19:51–21:34 UTC*
*Continuation of the session captured in `process/2026-04-05-book-brainstorm-summary.md`*

---

## What we worked on

The second half of the April 5 session completed Stages 2–4 of the writing process (Design → Challenge → Writing Plan) and got the site live with the new outline.

---

## Stage 2 (Design) — Two iterations

### v1 (PR #4, superseded)
Iris proposed a 9-chapter outline as a direct response to Nicole's intent statement. Key structural decisions from v1:
- Chapters 1 + 2 (disruption + case for learning in public) kept separate
- "The Observable Learner" as a dedicated chapter
- Tiers collapsed from five separate chapters into one

### Nicole's feedback on v1
Five open questions were posed. Nicole answered:
1. **Combine Ch1 + Ch2** — jump straight to the meat; no warmup
2. **Keep "The Robots Are Writing Poetry"** as the chapter 1 title
3. **Observable Learner placement** — stays where it is
4. **Manifesto** — possibly both in-chapter AND as a standalone artifact
5. **PKM as a fourth pillar** — this was the substantive new direction

Nicole's framing: the four pillars are `PKM × Learning in public × Observability × AI`. PKM should be named up front and woven throughout. Nick Milo's distinction between *taking* notes and *making* notes should be credited — but correctly: it's a PKM principle, not an AI one.

### Correction: Nick Milo attribution
Iris initially wrote "AI handles the taking, you do the making" and attributed this framing to Nick Milo. Nicole corrected this: his taking/making distinction is a PKM concept about passive capture vs. active synthesis — nothing to do with AI. Fixed in the design doc.

### v2 (PR #5, approved and merged)
Revised outline with the four pillars explicit throughout:

```
Introduction
Ch1  — The Robots Are Writing Poetry (combined disruption + case)
Ch2  — Supplement, Not Supplant
Ch3  — Mindset (+ Manifesto)
Ch4  — The Observable Learner
Ch5  — Show Your Work (Even With AI) — Tiers
Ch6  — Building Your Stack [new]
Ch7  — Pitfalls
Ch8  — When to Learn in Private
Ch9  — For the Love of Learning
```

The new Ch6 ("Building Your Stack") is the practical implementation chapter Nicole asked for — how to actually set up the four-layer system (PKM, AI, observability, publishing).

---

## Stage 3 (Challenge) — PR #6, merged

Five hard questions posed to Nicole before writing begins. Her answers, verbatim:

**Q1: Who is this book for — can it reach exhausted AI users?**
> I would try to emphasize that they shouldn't be outsourcing their thinking to AI. They should be outsourcing all the dreary bits, like scaffolding and structuring and publishing and editing once the thinking is done. I want to show them that it's precisely when they outsource the thinking itself that they can quickly feel out of their depth, because they're no longer at the wheel. I want to show them how to remain in control of AI and the kind of thoughts they put out into the world. They don't have to use AI as a productivity tool. They can use it as a wellness tool.

**Q2: Where is the line between AI-assisted and AI-replaced?**
> I think the test can't be anything quantitative. For me the test is just about joy. Do I feel happy about what I know about the topic? Would I have been as happy without AI? I also want to point out that the attribution problem has always existed. If I go to a conference talk and then I write about what I learned, can I say that that work is entirely mine? Of course not. All I can do is be open about where I got those ideas. I think too many people try to protect their ideas like a scarce resource, when the open discourse of ideas almost always leads to better insights.

**Q3: Is "learning in public" actually the answer — or just one option?**
> I don't think it's the only way to solve this problem, but it's a way that I've found works really well. I think you can do deep work and be an ultralearner even in public. Those are not necessarily just for private work. But I think that especially with AI, NOT showing your work makes it more dubious for others (did you really do that, or did AI do it?) and less useful (because people can't follow your train of thought). But I don't want to say learning in public is the only way to learn. That's why I wanted to have that chapter about learning in private.

**Q4: Can the observability metaphor carry non-technical readers?**
> I want to write about observability in a way that everyone can understand, not just those in DevOps like me. I've done several talks about this and I'm confident I can explain this without using jargon.

**Q5: The non-hustle frame vs. Nicole's actual career**
> It can be both! I do what I do because I love it and choose it consistently. But the whole starving artist mentality is really damaging to the creative spirit, which also needs to eat. The ideal would be to make enough money from this to sustain you — but luckily, that does tend to come easily when you learn in public.

### Four things the answers crystallised
1. **"AI as a wellness tool"** — the reframe that reaches exhausted users; doing your own thinking is how you stay connected to your own mind
2. **Joy as the test** — simple, non-quantitative, impossible to game; echoes Ch2 to Ch9
3. **Two new AI-era costs of not showing your work** — credibility ("did AI do that?") and usability ("I can't follow your reasoning")
4. **The honest non-hustle frame** — joy and professional sustainability are complementary; the starving artist mentality is the false choice

---

## Stage 4 (Writing Plan) — PR #7, open

Master task list in `specs/book/tasks.md`. Every task is Nicole's, sized for a single sitting.

**Suggested writing order:** Ch4 (Observable Learner — knows cold from talks) → Ch2 (most personal, sets the voice) → Ch1 → Introduction update → Ch3/5/6 → Ch7/8 → Ch9 (last).

**Target:** ~17,300 words. Tight and argued.

**Six unresolved decisions** flagged in the task list (most urgent: find and verify the exact tweet for Ch1).

---

## Site work

- **Homepage (PR #8, merged):** `content/index.md` rewritten with new 9-chapter outline and 2026 AI-era framing
- **Deploy fix (PR #9, merged):** GitHub Actions workflow had four deprecated action versions (`upload-pages-artifact@v2` was using the killed `upload-artifact@v3` internally); bumped all to current versions
- **YAML frontmatter fix (direct push):** Six old chapter files had unquoted colons in YAML titles, crashing the Quartz build; all fixed
- **Minor fix (direct push):** Removed `{#outline}` anchor tag from homepage heading (Quartz was rendering it as literal text)
- **Branch rule clarified:** PRs for content changes; direct push OK for build-critical fixes (Nicole confirmed April 5, 2026). Documented in `PROCESS.md`.

---

## Open questions remaining

- [ ] Find and verify the exact tweet for Ch1 (author, platform, date, wording)
- [ ] The Manifesto: in-chapter only, or also a standalone artifact?
- [ ] Ch4: include "Do Androids Dream" material explicitly?
- [ ] Ch6: name tools explicitly vs. principle-level + website pointer?
- [ ] Ch5: Tiers as flowing prose or with formal headings?
- [ ] The ski mountain moment: Introduction or Ch2?
- [ ] PRs #2, #7 still open for Nicole's review

---

## Files changed or created in this session

**Repo (`doing-it-in-public`):**
- `specs/book/intent.md` — Nicole's intent statement, verbatim
- `specs/book/design.md` — v2 outline (approved)
- `specs/book/challenge.md` — Stage 3 questions + Nicole's answers
- `specs/book/tasks.md` — Stage 4 writing plan
- `content/index.md` — homepage rewritten for new outline
- `.github/workflows/deploy.yml` — action versions bumped
- `content/Doing It in Public/Chapter 3–7, 10.md` — YAML frontmatter fixed
- `PROCESS.md` — branch rule clarified

**Workspace:**
- `memory/2026-04-05.md` — session memory written (two flushes)
- `memory/dip-session-active.json` — session state (cleared on session end)
