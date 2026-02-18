---
layout: default
title: "Chapter 8: How Senior Developers Actually Choose Tools"
---

# Chapter 8: How Senior Developers Actually Choose Tools

> *Here's the secret nobody tells you early enough: the developers you admire most don't have strong opinions about frameworks. They have strong opinions about problems.*

Watch a junior developer choose a technology for a new project. They'll probably pick the one they know. Or the one that's trending. Or the one they've been meaning to learn. The decision is centered on the tool itself — its features, its reputation, its community, its novelty.

Now watch a senior developer choose a technology for a new project. The conversation is almost unrecognizably different. They'll start with the problem. What are the constraints? What's the team's experience? What's the maintenance story? What's the deployment environment? What happens when this thing needs to scale, or change, or be handed off to someone else?

The tool comes last, if it comes at all. Sometimes the senior developer's recommendation is "use whatever you already know." Sometimes it's "this problem has specific requirements that make X the right choice." Sometimes it's "honestly, any of these would work — pick the one your team can hire for."

That's the shift. And it takes most developers years to make it.

## The Boring Answer

Here's what experienced developers have figured out that newer developers haven't: for the vast majority of projects, the technology choice doesn't matter nearly as much as you think.

Not that it's irrelevant. Not that there aren't cases where the choice is critical. But for most web applications, most APIs, most data pipelines, most CRUD systems — which is to say, for most of the software that actually exists — the difference between a good implementation in Python and a good implementation in TypeScript and a good implementation in Go is much smaller than the difference between a good implementation and a bad one in any of those languages.

The boring answer to "what technology should I use?" is almost always: "whichever one your team is productive in." That's not a non-answer. It's the answer. Because the bottleneck for most software projects is not the language or the framework. It's the humans — their understanding of the problem, their communication, their ability to write clear code, their willingness to test and document and maintain.

Senior developers know this because they've seen it. They've watched a beautifully architected system in the "right" language fail because the team didn't understand the problem. They've watched a scrappy prototype in the "wrong" language succeed because the team moved fast, iterated, and actually talked to users. After enough of these experiences, the reverence for technology choice starts to fade, replaced by a healthy respect for the factors that actually determine success.

## The Decision Framework

When senior developers do care about the technology choice — when the decision actually matters — they tend to think about a consistent set of questions. Not about the technology in isolation, but about the technology in context.

**What does the team know?** A technology that the team doesn't know is a technology the team has to learn, and learning takes time and introduces risk. The "best" tool that nobody on the team has used is often worse than the "good enough" tool that everyone knows. This isn't anti-intellectual — it's practical. The time spent learning a new framework is time not spent solving the actual problem. Sometimes that trade-off is worth it. Usually, it isn't.

**What's the hiring pool?** If you're building a team, or if the current team might change, the availability of developers matters. A niche language might be technically superior, but if you can't hire for it — or if hiring takes three times as long — that superiority comes at a significant cost. Senior developers think about this because they've been on the team that couldn't find someone to maintain the system built in the technically perfect but obscure language.

**What's the ecosystem like?** Not just "does a library exist for this," but deeper questions. Are the libraries maintained? Are there multiple options for critical dependencies, or are you locked into a single library maintained by one person? Is there good documentation? Is there a community that will help when you're stuck?

**What's the maintenance story?** Every technology choice is also a maintenance commitment. How will this look in three years? Will the framework still be supported? Will the language still be actively developed? Will you be able to upgrade dependencies without a six-month project? Senior developers have been burned by the technology that was perfect at adoption and unmaintainable three years later. They think about the long game because they've lived the long game.

**What are the actual constraints?** Sometimes there are genuine technical requirements that narrow the field. If you need sub-millisecond latency, that limits your language choices. If you need to run on embedded hardware, that limits them further. If you need to interface with a specific legacy system, that might dictate the technology entirely. Senior developers know how to distinguish between real constraints and aesthetic preferences.

## The Heuristics

Over time, experienced developers develop heuristics — not rules, but patterns that serve them well more often than not.

**"Use boring technology."** This heuristic, memorably articulated by Dan McKinley, captures something important: new and exciting technologies carry hidden costs. They have less documentation, fewer known failure modes, smaller communities, and more bugs. Boring technology — the stuff that's been around long enough to have its edge cases mapped — is often the responsible choice. Not always. But often enough that "boring" should be the default you deviate from intentionally, not the other way around.

**"Optimize for the team, not the architecture diagram."** A system that looks beautiful on a whiteboard but that half the team can't work with is worse than a system that looks simple on a whiteboard and that everyone can contribute to. Technical elegance is worth less than team velocity.

**"The best tool is the one that lets you think about the problem instead of the tool."** If you're spending more time fighting the framework than solving the problem, the framework is wrong — regardless of how technically impressive it is. A good tool disappears. A great tool feels like an extension of your thinking. A wrong tool is all you can think about.

**"Reversibility matters."** Some technology choices are easy to reverse. Others lock you in for years. Senior developers weight their consideration accordingly. An easy-to-reverse choice can be made quickly and cheaply. A hard-to-reverse choice deserves more analysis. But even the hard-to-reverse choices don't deserve infinite analysis — at some point, you have to commit and learn.

## What This Means for You

If you're early in your career, this chapter might feel deflating. You want the technology to matter, because you've invested in learning a specific one, and the idea that it mostly doesn't matter threatens that investment.

But here's the reframe: if the technology choice matters less than you thought, then your skills matter more than you thought. Your ability to understand problems, to communicate clearly, to write maintainable code, to debug systematically, to work well on a team — these things matter enormously, and they go with you everywhere, regardless of the stack.

The senior developers who seem relaxed about technology choices aren't relaxed because they don't care. They're relaxed because they've learned to invest their caring in the right places. They care intensely about clarity, about simplicity, about solving the right problem, about building systems that can be understood and maintained by humans. They care less about which language those systems are written in, because experience has taught them that the language is the least interesting variable.

This isn't nihilism. It's maturity. And it's incredibly freeing. When the technology choice becomes less fraught, everything else becomes lighter too. You can evaluate new tools without anxiety. You can switch stacks without crisis. You can have a conversation about technology that's actually about technology, instead of being about identity.

That's the level you're working toward. And it's closer than you think.

---

*Next: [Chapter 9 - The Polyglot Mindset](09-the-polyglot-mindset.html)*
