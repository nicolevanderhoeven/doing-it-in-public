---
title: "Chapter 6 - Tier 3: Automating your learning"
draft: true
description: 
tags:
  - 
---

[Back to outline](/#outline)

> **Status:** Draft skeleton — sections outlined, content to be written.

The hardest part of learning in public isn't the first month. It's the twelfth. The inspiration is gone, the novelty has worn off, and you're still showing up — or trying to. Automation is what makes the twelfth month possible. Not because machines can do your thinking for you, but because systematizing the parts that don't require your creativity frees you to apply that creativity where it actually matters. This chapter is about building the infrastructure that makes consistency less exhausting.

## Creating a content calendar

A content calendar sounds like something a corporate marketing team uses — color-coded spreadsheets, quarterly campaigns, approved messaging. It doesn't have to be that. A content calendar, at its simplest, is just a list of what you plan to publish and when. Even a rough one, even a flexible one, is enormously useful for a public learner because it moves publishing decisions from reactive (what should I post today?) to proactive (what am I publishing this week?).

The shift from reactive to proactive is bigger than it sounds. Reactive publishing is exhausting because it requires a fresh creative decision every time you sit down. Proactive publishing turns many of those decisions into execution — the decision was already made, now you just do the work. This is the creative equivalent of mise en place: having everything prepared before you start cooking so that when the time comes, you can focus on cooking instead of finding ingredients.

*[SEED: Share the actual Obsidian content calendar setup — fc-calendar plugin, how topics are seeded, how the publishing cadence was decided. Include the real-world experience of having a calendar and not sticking to it, and what that revealed.]*

### Deciding on publishing cadence, developing consistency

Consistency matters more than frequency. One good thing per week, every week, for a year is worth far more than five things per week for two months followed by silence. The right cadence is the one you can actually maintain — which means it needs to fit into your real life, not your aspirational life.

This is where most content creation advice fails people: it assumes that if you just want it enough, you can publish daily. Some people can. Most can't, sustainably. Figure out what your actual capacity is, build in buffer for the weeks when everything falls apart, and commit to that.

## Scheduling posts and creating a buffer

A buffer is a reserve of finished or nearly-finished content that you can draw from when you hit a bad week. When you're sick, when work is overwhelming, when you're traveling, when inspiration has completely abandoned you — a buffer means you can still publish something without having to create something from nothing while depleted.

Building a buffer feels counterintuitive when you're starting out, because you don't have enough content to create a buffer yet. The way to solve this is to batch: produce several pieces of content in a single productive period, then release them over time rather than all at once. A weekend of focused writing can create three or four weeks of buffer. This is worth doing.

*[SEED: Practical tutorial — how to schedule posts on different platforms. Mastodon scheduling, YouTube scheduling, newsletter drafts. How the Buttondown × Obsidian integration works.]*

### Feedback triage and prioritising

When you're publishing consistently and people are starting to respond, you'll encounter a new problem: there's too much feedback to process. Comments, messages, replies, emails — some of it is gold, some of it is noise, and some of it is just people being unkind on the internet. Feedback triage is the practice of systematically sorting through responses to find the signal in the noise.

A simple triage system: first, separate actionable feedback from non-actionable feedback. Actionable feedback suggests a specific change or reveals a specific misunderstanding. Non-actionable feedback is everything else — appreciation, criticism with no specifics, and the full spectrum of internet randomness. Of actionable feedback, separate the things you can address now from the things you want to think about and potentially address later. Everything else goes in a "maybe someday" bucket or gets discarded.

## Building a CI/CD pipeline for learning

In software development, a CI/CD pipeline automates the steps between writing code and shipping it — running tests, building artifacts, deploying to production. The goal is to make the path from "I made a thing" to "the thing is live" as short and automated as possible.

A learning pipeline works the same way: it automates the steps between capturing an idea and publishing it. The exact implementation will vary based on your tools and workflow, but the logic is universal. Something enters the system (a book highlight, a shower thought, a question someone asked me, something I noticed while working). It gets processed (turned into a note, connected to other notes, refined over time). It exits the system (as a post, a video, a chapter, a talk). The pipeline is what moves things through these stages without requiring you to make fresh decisions at every step.

*[SEED: Walk through the actual Iris/Obsidian pipeline: Readwise → highlights → atomic notes → content cards → video scripts / newsletter issues / book chapters. Show the Grafana-inspired "observability" angle — how to instrument your own learning pipeline so you can see where things are getting stuck.]*

*[SEED: Reference [[Building a continuous note-taking system]] — the CI/CD metaphor applied to note-taking.]*

### The learning pipeline as a system

The key insight of the learning pipeline is that your bottleneck is rarely where you think it is. Most people assume the hard part is capturing input — reading more, learning more, consuming more. But after a while, the hard part becomes processing: turning raw input into refined output. And after that, the hard part becomes distribution: getting finished work in front of the people who would benefit from it. Identifying where your personal pipeline is actually blocked is the first step to unblocking it.

*[SEED: The observability angle: if your learning pipeline were a distributed system, what metrics would you instrument? What does the dashboard look like? What does an alert look like? This is the chapter where Nicole's Grafana expertise really shows.]*
