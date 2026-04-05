# Transcript: Book Pivot + Collaboration Setup

*Date: April 5, 2026 | ~16:41–19:51 UTC*
*Edited for clarity and relevance. Tangents and non-book content removed.*
*Session captured retroactively — no formal session boundary was in place at the time. The `dip-session` skill was created as a result of this conversation.*

---

**[Nicole]** Please draft a revised outline of DIP and output it to our folder.

**[Iris]** *(drafted and saved `DIP Book - Revised Outline - 2026-04-05.md` to the Obsidian output folder)*

Quick summary of what changed: added Chapter 2 (What AI Changes), AI section at every Tier chapter, "To stay human" added to Chapter 1, AI-specific pitfalls in Chapter 9, conclusion reframed for the AI era. One structural question flagged: whether the Tiers 0–4 framing is still serving the argument.

---

**[Nicole]** Help me think about the outline. I don't want to just improve the outline because it already exists. I wrote that two years ago, and I'm open to redoing it completely if that's what it takes to write a really good book. So please help me brainstorm a bit. What do you think about the overall premise of the book? Do you think it adds value, or are there other books that are already out there that do the same thing?

**[Iris]** Honest take: the premise adds value, but the current version isn't the book that needs to exist.

The existing outline is essentially *Show Your Work!* + PKM tiers. Kleon already wrote that in 2014. The other close competitor is swyx's "Learn in Public" essay — the founding document of this movement for developers. He's never written a full book. That's a real gap, but only if your book is substantially different.

What only you bring: the observability angle (DevOps lens on learning — nobody in this space is doing this), the AI question lived honestly (13,000-note vault, an AI reading your diary, still doing the thinking yourself), and the non-hustle frame (learning in public because it makes you a better thinker, not to build your brand).

The version worth writing has teeth: *In a world where AI can produce competent output on demand, learning in public is how you prove there's a person behind the ideas. It's proof-of-work. It's how you resist becoming a spectator of your own thinking.*

Hard questions: Who is this for exactly? What's the one sentence the book is arguing? Does the Tiers structure serve the argument? Should it still be called "Doing It in Public"?

---

**[Nicole]** I love when you push back on me. I think your points are valid. I think part of the reason I never got very far with the original book is that even then, it didn't have enough teeth. I want to pivot it to feature AI. I think you're right about observability and AI, as well as the no-hustle belief I have, should be essential features of the book.

I would like for the book to argue that learning in public has never been more valuable than now, in the age of AI. I want to talk about how to show your work with AI, how to use it without it using you, and how learning in public can hold you accountable and encourage you to think and plan and write and code for yourself — even if AI could technically do it all for you. I want to celebrate the unique joy that a human can still bring to any work they produce, while not shying away from using tools like AI to scaffold large projects. I want to talk about how AI can be used to supplement, not supp—

*(message cut off)*

---

**[Nicole]** ... not supplant thinking.

**[Iris]** Yes — *supplement, not supplant thinking.* That's the cleanest version of the central tension. Worth keeping that exact phrase somewhere visible while you write.

Here's what I'm hearing as the thesis:

> *Learning in public has never mattered more than it does now — not despite AI, but because of it. When AI can produce competent output on demand, the act of visibly, messily doing the work yourself becomes the most human thing you can do. This book is about how to use AI as a scaffold without letting it become a substitute for your own thinking.*

Does that land?

*(Iris also proposed a new structural framing: Why now → What changed → The human part → The AI part → The risks → The practice — as an alternative to the Tiers ladder.)*

Question left open: Is "Doing It in Public" still the right title?

---

**[Nicole]** Let's pause on the brainstorming for a second and talk about logistics. I would like you to help me write this book, but I think it would be very cool to measure and track and be open about our collaboration going forward. I want people to know what you've written, how you've helped, what I've written, what my intents have been. I was thinking about using OpenSpec to track that — but can you think of better ways to do it?

**[Iris]** OpenSpec is interesting but it's designed for software — worth adapting rather than using verbatim. Options:

1. Git commit conventions (`[iris]`, `[nicole]`, `[collab]`, `[process]`)
2. Chapter provenance frontmatter in each file
3. Publish key conversations in `process/`
4. A `PROCESS.md` explaining the methodology
5. Adapted OpenSpec — `specs/` with intent (Nicole), design (Iris), tasks per chapter

Recommendation: combine 1 + 3 + 5. Commit conventions are automatic and free. Publishing key conversations is the most on-brand thing for a book about doing it in public. Adapting OpenSpec for chapter planning makes the intent layer legible.

---

**[Nicole]** Yes please! I also wanted to do 1+3+5 so I'm super pleased you landed on that too. Yes, please set up the structure in the repo.

**[Iris]** *(set up `PROCESS.md`, `specs/`, `process/`, intent files, chapter provenance frontmatter — then pushed directly to `v4` twice by mistake)*

---

**[Nicole]** Wait, did you do a pull request or did you just push to main?

**[Iris]** Pushed directly to `v4` — twice. The commits are there. Going forward: every Iris change goes on an `iris/` branch and opens a PR. No more direct pushes.

---

**[Nicole]** Yes, please only do PRs from now on. Also, are we still going to be keeping the exact records of our conversations in the repo somewhere?

**[Iris]** Yes — that's what `process/` is for. The question is what level of detail: edited summaries only, verbatim excerpts, or both?

---

**[Nicole]** I like the idea of doing both. But maybe you can create a skill so that I can trigger it clearly when I want you to start a writing session with me and when I want to end it. That way I don't have to fear that you'll publish something private that doesn't relate to the writing of this book. Remember that PRs are already public too, so even if I don't merge it, people will still see what you've written there. I want to be able to clearly say when we start a session and when we end it, and I don't want you to be including anything in a PR that isn't within that clear start and end.

**[Iris]** *(created `skills/dip-session/SKILL.md`)*

Skill created. Trigger phrases: "start writing session" / "end writing session." Nothing goes to GitHub — not even as a PR — until you say end. PRs are public the moment they're created, so the session boundary is the only safe line.

---

**[Nicole]** Are you able to still capture our conversation from the point where I said "Please draft a revised outline of DIP and output it to our folder" today?

**[Iris]** Yes — opening a PR now.

---

*End of captured session.*
*This transcript was compiled retroactively from session context. No formal session boundary was in place — the `dip-session` skill was created as a direct result of this conversation. Future sessions will have explicit start/end markers.*
