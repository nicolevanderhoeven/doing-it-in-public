# Book Design: Proposed Outline

*Proposed by Iris | April 5, 2026*
*Based on Nicole's intent (see `specs/book/intent.md`)*
*Status: Awaiting Nicole's approval*

---

## Design rationale

The original 10-chapter outline was organised as a *how-to guide* with a complexity ladder (Tiers 0–4). That structure served a different book — a practical guide to learning in public. The new intent is an *argument with a practical core*: AI can do your knowledge work; should it?

This redesign does three things:

1. **Leads with the disruption** — Chapter 1 earns the reader's attention by naming what changed and why it matters. The original book assumed you already believed in learning in public. This one has to make the case in an AI world first.
2. **Foregrounds Nicole's distinctive angles** — the observability chapter (Ch5) is now a standalone, not a metaphor buried in a mindset chapter. It's her most unique contribution.
3. **Collapses the Tiers into one practical chapter** — five chapters of tiers was too granular for the argument being made. The tiers become a framework within one chapter, not the skeleton of the whole book.

**Kept from original:** Introduction (updated), the core arguments for learning in public (reframed as Ch2), Mindset (Ch4, updated), Pitfalls (Ch7), When to Learn in Private (Ch8).

**New:** Ch1 (the disruption), Ch3 (supplement not supplant), Ch5 (observability), Ch9 (the joy/conclusion).

---

## Proposed structure

### Introduction *(update existing)*

**Keep:** The Dutch story. It's still the perfect hook — personal, surprising, clear payoff.

**Add:** A 2026 bookend. The moment Nicole realised AI could have learned Dutch for her — fed her audio, generated responses, faked the fluency. And why doing it herself, publicly, was the whole point. This sets up the book's central tension before the reader knows there's a thesis.

**Update:** "my husband" → "my partner". Refresh the list of things Nicole has learned in public to include AI tools, Kubernetes, Grafana.

---

### Chapter 1: The Robots Are Writing Poetry *(new)*

**The disruption.** The book opens by naming what actually changed.

The tweet: *"A future where robots paint and write poetry while humans do menial tasks is not the future I signed up for."* This inverts the expected AI dystopia — we were supposed to be worried about machines taking our factory jobs, not our creative ones.

AI can now: write books, compose music, generate images, write code, hold conversations, synthesise research, and produce competent creative work in seconds. The question of whether it *can* do our knowledge work for us is answered. The question this book asks is different: **do we want it to?**

Sections:
- What AI can actually do now (concrete, honest, not hype or doom)
- The difference between *having the output* and *having the knowledge*
- Why this matters beyond career risk — what we lose if we stop learning ourselves
- The choice: not boycott, not surrender — something more interesting

---

### Chapter 2: The Case for Learning in Public *(from original — reframed)*

**Why learning in public has always been the answer** — and why it's even more so now.

This chapter carries the core arguments from the original book: the Greeks, accountability, impostor syndrome, the feedback loop, community and scenius. These arguments don't need to change; they need to be framed as the foundation for the AI argument. Learning in public isn't a nice idea that became urgent. It was always the right way to learn — AI just made it *necessary*.

Sections:
- The ancient case: the Athenians knew something we forgot
- Learning in the open makes you faster, more honest, and more connected
- The accountability effect: why witnesses matter
- Show your work: Austin Kleon's insight, updated for 2026
- Why output alone has never been enough

---

### Chapter 3: Supplement, Not Supplant *(new)*

**The third way.** Not boycott, not surrender.

This is where Nicole's own AI journey lives: from "no AI ever touches my vault" to pasting into ChatGPT to giving Iris access to 13,000 notes. The honest progression. And what she learned along the way about where AI helps and where it hurts.

"Being used by AI" is real and subtle. It looks like: your voice gradually sounding like everyone else's because you're all prompting the same model. It looks like forgetting how to start a blank page without a prompt to react to. It looks like publishing AI-generated "insights" and calling it learning.

Sections:
- Nicole's AI journey, honestly told
- What "being used by AI" actually looks like (dependency, voice erosion, the feedback loop, homogenisation)
- The test: can you explain it? Could you have gotten there eventually? Is the reasoning yours?
- Practical principles for intentional AI use
- AI as a thinking partner, not a thinking replacement

---

### Chapter 4: Mindset *(from original Ch2 — updated)*

**How to think about learning in public.** The original five pillars hold up: make it observable, continuous, fun, communal, intentional. This chapter updates each with an AI dimension and delivers the Manifesto for Learning in Public as a real, quotable artifact.

Sections:
- Make it observable (now includes: observable *to yourself* via AI tools, but see Ch5 for depth)
- Make it continuous (AI can automate parts of the pipeline — not the thinking)
- Make it fun (AI removes friction — don't let it remove the productive struggle)
- Do it in a group (AI can simulate community; it can't replace it)
- Make it intentional (exit criteria matter more when AI will generate forever)
- **The Manifesto for Learning in Public** ← written out in full here as a real artifact

---

### Chapter 5: The Observable Learner *(new — Nicole's signature chapter)*

**Observability applied to learning.** The most distinctive chapter in the book.

Nicole comes from DevOps and systems engineering. Observability — the ability to understand what's happening inside a complex system by examining its outputs — is her native lens. This chapter applies it to the human learner, and especially to the human+AI learning system.

In distributed systems, observability solves the black box problem: you can't inspect every internal state, so you instrument the system to emit signals you can measure. A learning process has the same problem. If you only see the output — the finished essay, the completed course, the passed exam — you can't tell if learning actually happened. Observability means making the *process* visible: the questions, the wrong turns, the moments of confusion and clarity.

When AI is involved, observability becomes a transparency layer for the collaboration itself. How can you tell which thinking was yours and which was the model's? The garage door metaphor: default to open, so your real brain work — not just your AI output — is traceable.

Sections:
- Observability in distributed systems: the black box problem
- Learning as a complex system: why output alone doesn't tell you if it worked
- Instrumenting your learning: what signals matter?
- The garage door: defaulting to visible
- Human + AI observability: making the collaboration traceable
- "Do Androids Dream of Second Brains?" — the PKM Summit talk's core question applied here
- Practical: what observable learning actually looks like (vault notes, commit history, public logs, this book)

---

### Chapter 6: Show Your Work (Even With AI) *(consolidated Tiers)*

**The practical guide.** How to actually do this, at whatever level you're at.

The original Tiers structure (0–4) is preserved here as a framework, not a chapter structure. The Tiers give readers a sense of scale and progression without demanding five separate chapters.

Sections:
- **Tier 0 — Start before you're ready:** TILs, social posts, the daily dispatch. What authentic microlearning looks like with AI (using AI to clarify what you already think, not to think for you).
- **Tier 1 — Build your system:** PKM, static site, version control for knowledge. AI-augmented PKM: the "write first, AI second" rule.
- **Tier 2 — Go deep:** Long-form essays, videos, talks. Your voice vs. AI polish. Using AI as editor, not author.
- **Tier 3 — Automate the plumbing:** Pipelines that serve your learning. What to automate (logistics) and what not to (thinking). Nicole's stack as a demonstration.
- **Tier 4 — Build community:** In an AI-saturated world, authentic community is the scarcest resource. The trust premium.

---

### Chapter 7: Pitfalls *(from original Ch8 — expanded)*

**What goes wrong.** The original pitfalls updated with AI-specific failure modes.

**Original pitfalls:** optimal quitting, art vs. exhibitionism, feedback noise, oversharing.

**New AI-specific pitfalls:**
- *Authenticity theater* — performing learning in public (posting AI-generated "insights") without doing the actual learning
- *The echo chamber* — AI trained on your notes reflects your beliefs back; your second brain becomes a hall of mirrors
- *Dependency* — you stop being able to think without AI; you mistake frictionlessness for understanding
- *Voice erosion* — gradual homogenisation; you start to sound like everyone else
- *Premature automation* — automating your pipeline before you understand what you're trying to learn

---

### Chapter 8: When to Learn in Private *(from original Ch9 — updated)*

**The necessary flip side.** When to close the garage door.

Some learning requires friction. Some things are worth doing slowly. Some thoughts are yours to keep. This chapter isn't a retreat from the book's thesis — it's the honest completion of it. Learning in public isn't everything, always. Knowing when NOT to is part of the discipline.

Updated sections:
- Strategic inauthenticity: when being private is the right call
- When to turn off AI entirely (language learning, developing your voice, sitting with confusion)
- AI privacy: what data you're actually giving away; how to tier your AI access
- The things worth doing in the dark: forming opinions, making mistakes quietly, thinking for yourself

---

### Chapter 9: For the Love of Learning *(new conclusion)*

**The joy.** This isn't just about career protection or AI ethics.

The book ends not with a warning but with an invitation. There is genuine, irreplaceable pleasure in understanding something new. In the specific click of an idea landing. In making something that came from your own confusion, your own curiosity, your own particular way of seeing. AI cannot take this from you. But you can give it away without noticing.

The final chapter is a celebration — of learning for its own sake, of the human learner in the AI age, of the strange joy of doing things in public. And an invitation to start.

---

## Open questions (for discussion before Nicole writes)

1. **Should Ch1 and Ch2 be combined?** The disruption (Ch1) and the original case for learning in public (Ch2) could be one chapter. Splitting them gives each room to breathe, but risks the reader waiting two chapters before the book's specific argument arrives.

2. **Is "The Robots Are Writing Poetry" the right chapter title for Ch1?** It's evocative and the tweet is real, but worth confirming Nicole likes this as the opening frame.

3. **Chapter 5 (Observability) placement** — it currently sits between Mindset and the practical Tiers chapter. Should it come earlier (as the philosophical framework) or later (as the practical layer on top of practice)?

4. **The Manifesto** — it's placed in Ch4 (Mindset). Should it be a standalone artifact in an appendix instead, something readers can pull out and keep?

5. **Should Nicole's specific AI setup (Iris, Obsidian, OpenClaw) appear explicitly?** It's her most credible demonstration of the thesis. But it may date the book quickly as tools change. Options: mention it explicitly as "here's what I use" with a note that tools change, or keep it abstract and point to the website/blog for current specifics.

---

## What this outline throws away

- The five separate Tier chapters (collapsed into Ch6)
- The original Chapter 1 title "The Case" (replaced by two stronger chapters)
- The Conclusion as a summary chapter (replaced by a joy/invitation chapter)

## What it keeps

- Introduction (Dutch story — too good to lose)
- All the original arguments for learning in public (reframed in Ch2)
- The Mindset chapter structure (updated in Ch4)
- Pitfalls (updated in Ch7)
- When to Learn in Private (updated in Ch8)
