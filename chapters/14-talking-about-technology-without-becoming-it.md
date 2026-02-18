---
layout: default
---

# Chapter 14: Talking About Technology Without Becoming It

> *There's a difference between "I think TypeScript is great for this use case" and "I'm a TypeScript person." One is an opinion. The other is a cage you built yourself.*

We talk about technology constantly. In standups and retrospectives, in architecture meetings and code reviews, on social media and in blog posts, over coffee and over Slack. Technology discussion is the ambient conversation of our profession. It's how we share knowledge, make decisions, and establish credibility.

But not all technology talk is created equal. Some of it is genuinely useful — the kind that illuminates trade-offs, shares hard-won experience, and helps people make better decisions. And some of it is identity performance — the kind that's really about signaling which tribe you belong to, defending your past choices, or establishing your position in the professional hierarchy.

The difference between these two modes of conversation is subtle but consequential. One makes you a better developer. The other makes you a more entrenched one.

## The Language of Attachment

Listen to how developers talk about technology and you'll notice a spectrum. On one end, there's detached evaluation:

"Rails has good conventions for CRUD applications, but the magic can make debugging harder for larger teams."

"Go's simplicity is a real advantage for operational code, though the lack of generics was a legitimate limitation for library authors."

"React's component model maps well to how designers think about UI, which reduces the translation layer between design and implementation."

These statements have opinions. They even have strong preferences. But they're expressed as assessments of trade-offs — evaluations of tools in context. The speaker is outside the technology, looking at it.

On the other end of the spectrum, there's identity expression:

"I could never go back to a language without a good type system."

"We're a Ruby shop and that's not changing."

"I don't trust anyone who willingly uses PHP in 2025."

These statements aren't really about technology at all. They're about the speaker's relationship to the technology. "I could never go back" is about identity, not capability. "We're a Ruby shop" is about tribal allegiance, not architecture. "I don't trust anyone who uses PHP" is about social hierarchy, not technical merit.

The first mode leads to good decisions. The second mode leads to defensiveness, closed-mindedness, and the kind of arguments where everyone gets upset and nothing gets resolved.

## Having Opinions Without Being Them

Opinions about technology are good. You should have them. Strong opinions, even. Opinions formed by experience are one of the most valuable things you bring to a team. The problem isn't having opinions. It's fusing with them.

There's a useful distinction in psychology between "holding" a belief and "being" a belief. When you hold a belief, it's something you carry — you can examine it, update it, set it down if the evidence changes. When you are a belief, it's structural — challenging the belief feels like challenging you, and updating the belief feels like losing part of yourself.

The developer who holds the opinion "TypeScript is a good choice for large codebases" can engage with counterarguments. They can say "that's a fair point, I hadn't considered that" or "I still disagree, but here's why." The conversation is about the technology.

The developer who is the opinion "TypeScript is the right choice" can't really engage with counterarguments, because every counterargument lands as a personal attack. Their response to criticism is emotional rather than analytical. The conversation becomes about them.

The shift from holding to being happens gradually, and the way you talk about technology is both a symptom and a cause. Every time you say "I'm a TypeScript person" instead of "I prefer TypeScript for this kind of project," you reinforce the fusion a little bit. Every time you dismiss an alternative without engaging with it — "yeah, that's not really my thing" — you build the wall a little higher.

## The Practice of Detachment

Detachment doesn't mean not caring. It means caring about the right things. You can care deeply about building good software without caring whether that software is built in your preferred language. You can care deeply about code quality without needing your specific definition of quality to be universal.

Here are some practical ways to talk about technology from a place of detachment rather than attachment:

**Lead with the problem, not the solution.** Instead of "we should use Postgres," try "we need a database that handles complex queries well and has strong consistency guarantees — Postgres does that, though there might be other options worth considering." This frames the technology as a means to an end, not an end in itself.

**Use provisional language.** "Based on what I know" and "in my experience" and "I could be wrong about this" aren't weakness — they're accuracy. Your opinions are based on your experience, which is necessarily limited. Acknowledging that doesn't diminish your expertise. It makes it more trustworthy.

**Steelman the alternative.** Before arguing against a technology choice, genuinely try to articulate the best case for it. "I can see why someone would choose MongoDB for this — the flexibility of the document model is appealing and the initial development speed would be fast. My concern is..." This shows you've actually engaged with the other perspective, which makes your disagreement much more credible.

**Separate the evaluation from the decision.** "This is a good technology" and "this is the right choice for us" are different statements. A technology can be excellent and still not be right for your team, your timeline, your constraints. Keeping these separate prevents technology arguments from becoming binary good/bad judgments.

## Conversations That Actually Help

The best technology conversations — the ones that actually lead to better decisions — share some common characteristics.

They focus on **trade-offs rather than verdicts**. Every technology choice involves giving something up to get something else. Good conversations explore what you're trading, rather than declaring one option the winner. "What do we lose if we go with X? What do we gain?" is a much more productive question than "Is X good?"

They include **context**. "React is great" means nothing. "React is great for our team of five JavaScript developers building a complex single-page application with lots of interactive state" means something. Context is what turns generic opinions into useful guidance.

They acknowledge **uncertainty**. Nobody knows how a technology choice will play out over three years. Pretending you do isn't confidence — it's arrogance. The most useful technology conversations include honest acknowledgment of what you don't know, what might change, and what could go wrong.

They're **curious rather than combative**. "Why did you choose that approach?" asked genuinely is the beginning of a useful conversation. "Why on earth would you choose that approach?" asked dismissively is the beginning of a fight. Tone matters more in technology discussions than we want to admit.

## The Meeting Room Test

Here's a practical test for whether your technology talk has crossed from evaluation into identity: imagine you're in a meeting and someone proposes using a technology you've previously argued against. How do you feel?

If you feel curious — "interesting, what's changed that makes them think this is the right call?" — you're in evaluation mode. You're assessing the proposal on its merits.

If you feel threatened — "they're trying to push out the technology I championed" — you're in identity mode. The proposal isn't landing as a technical suggestion. It's landing as a challenge to something you've tied yourself to.

The second reaction is human and understandable. But noticing it is the first step to not being controlled by it. You can feel the threat response and still choose to engage from evaluation mode. "I notice I'm feeling defensive about this. Let me set that aside and actually evaluate the proposal." That internal move is one of the most powerful things an experienced developer can learn to do.

## What Changes When You Detach

When you can talk about technology without being it, conversations get better. Not just your conversations — the ones around you, too. Because detachment is contagious.

When the senior developer in the room says "I've been a Kubernetes advocate, but I think for this project we should consider something simpler," it gives everyone else permission to change their minds too. When the tech lead says "I was wrong about that architecture choice, here's what I'd do differently," it creates a culture where being wrong is safe and updating your views is valued.

The opposite is also true. When the loudest voice in the room treats every technology discussion as a battle, everyone else either picks a side or shuts up. Neither produces good decisions.

You get to choose which kind of engineer you are in those rooms. Not just for yourself, but for the culture you're building around you.

---

*Next: [Chapter 15 - The Burnout of Over-Identification](15-the-burnout-of-over-identification.html)*
