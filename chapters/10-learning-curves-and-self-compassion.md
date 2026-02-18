---
layout: default
---

# Chapter 10: Learning Curves and Self-Compassion

> *You wouldn't berate a junior developer for not knowing something. So why do you do it to yourself every time you open a new REPL?*

Let's talk about the thing that happens in the gap between deciding to learn something and actually knowing it. That gap — the learning curve — is where most developers abandon new technologies, and it has almost nothing to do with the technology being too hard. It has everything to do with the stories we tell ourselves while we're in it.

The learning curve for a new programming language or framework is rarely a smooth upward slope. It's more like a jagged line with plateaus, dips, and occasional cliffs. There are days when everything clicks and you feel like you're flying. There are days when you can't get a test to pass and you feel like you should go into a different profession entirely. And there are long stretches in between where nothing dramatic happens and you just grind, making slow progress that's invisible until you look back at where you were a month ago.

All of this is normal. All of this is the process working correctly. But the voice in your head doesn't know that.

## The Narrator Is Unreliable

When you're learning something new, there's a running internal monologue, and it's almost never kind. It says things like:

"Other people learn this faster."

"If you were really good at programming, this wouldn't be this hard."

"You should understand this by now. You've been at it for two weeks."

"Maybe this language just isn't for people like you."

This narrator sounds authoritative. It sounds like it's giving you useful information. But it's lying to you, or at best, it's making claims that are impossible to verify and almost certainly wrong.

Other people don't learn this faster — or if some do, it's because they have a different background, not because they have a better brain. Being good at programming has almost nothing to do with how quickly you learn new syntax; it has to do with how you think about problems, and that doesn't evaporate when you switch languages. Two weeks is nothing — learning a new ecosystem deeply takes months, and anyone who tells you otherwise is selling something. And there's no such thing as a language that's "not for people like you." There are languages that are harder to learn than others, but the difficulty is in the language, not in you.

The unreliable narrator is the biggest obstacle to learning. Not the technology. Not the documentation. Not the compiler errors. The voice in your head that interprets every stumble as evidence of inadequacy.

## The Dunning-Kruger Whiplash

You've probably heard of the Dunning-Kruger effect — the tendency for people with limited knowledge to overestimate their competence. What's less discussed is the flip side: the tendency for people with substantial knowledge to underestimate their competence and feel worse about their abilities than they should.

When you're learning a new stack, you get hit with a Dunning-Kruger whiplash. In your old stack, you were in the latter phase — you knew a lot, you underestimated what you knew, but your competence was evident in your work. In the new stack, you briefly pass through the overconfident phase (the tutorial makes it look easy) and then plummet into what feels like permanent incompetence.

The whiplash is intense because the contrast is vivid. You go from "I know what I'm doing" to "I have no idea what I'm doing" in the span of a single week. And because your self-worth is partially tied to your technical competence — because, as we've discussed, you've merged your identity with your stack — the fall feels personal.

But it's not personal. It's the learning curve doing exactly what learning curves do. The discomfort isn't a sign that something is wrong. It's a sign that you're growing, which always, without exception, involves a period of not being good at the new thing yet.

## What Self-Compassion Actually Means

Self-compassion in the context of learning isn't about letting yourself off the hook. It's not "don't try hard" or "lower your standards" or "be satisfied with mediocrity." It's about being realistic about the process and not adding unnecessary suffering to an already difficult experience.

Psychologist Kristin Neff describes self-compassion as having three components: self-kindness (treating yourself with the same care you'd offer a friend), common humanity (recognizing that struggle is universal, not a personal failing), and mindfulness (acknowledging your feelings without drowning in them).

Applied to learning a new technology stack, this looks like:

**Self-kindness:** "I'm struggling with the borrow checker, and that's okay. The borrow checker is hard. It was designed to enforce constraints that are genuinely difficult to internalize. I will figure it out, and it doesn't need to happen today."

Contrast this with the default developer inner monologue: "I can't believe I still don't understand the borrow checker. Am I stupid? Why is everyone else in this Discord channel getting it and I'm not?"

**Common humanity:** "Every developer who has ever learned Rust went through this exact phase. The people who are now experts were once as confused as I am. This is a shared experience, not a personal deficiency."

Contrast: "I'm the only person who finds this this hard. Everyone else just gets it."

**Mindfulness:** "I feel frustrated right now. That's a real feeling and it makes sense given what I'm experiencing. I don't need to act on it or make it mean something about my career. I can feel frustrated and keep going."

Contrast: "I'm so frustrated I should just give up. This clearly isn't for me."

## The Permission Structure

One of the most concrete things you can do for yourself when learning a new technology is to create an explicit permission structure. Write it down if you have to. Give yourself specific, named permissions:

*Permission to be slow.* Learning takes the time it takes. You are not behind.

*Permission to forget.* You will look up the same syntax three times, maybe ten times. This is how memory works. It's not a sign of failure.

*Permission to write bad code.* Your first code in a new language will not be idiomatic. It will probably look like your old language wearing the new language's clothes. This is fine. Idiom comes with time and exposure.

*Permission to not understand.* Some concepts won't click immediately. Some won't click for weeks. Some will only click when you encounter them in practice, not when you read about them in documentation. Let them be unclear for now.

*Permission to ask basic questions.* You are not "too experienced" to ask how something works. Experienced developers asking basic questions in new contexts is not imposture. It's learning.

These permissions sound trivially obvious when you read them. But try giving yourself these permissions in the moment, when you're frustrated and the code won't compile and it's been four hours. They're much harder to grant than to read.

## The Shape of Learning

It helps to understand what the learning curve actually looks like, so you can calibrate your expectations.

**The first day** is usually the best. Everything is new and interesting. The tutorial works. You get a "Hello, World" running and it feels like progress. Dopamine flows. You think: "I'm going to be good at this."

**The first week** is where reality sets in. You move past the tutorial and try to build something real. The ecosystem is confusing. The error messages don't match what Google says they mean. The thing that worked in the tutorial doesn't work in your project because of some environmental difference that took three hours to diagnose.

**The first month** is the valley. You know enough to be dangerous but not enough to be productive. You can write code, but it feels clunky. You can solve problems, but it takes five times longer than it would in your old stack. The temptation to go back — to retreat to the familiar — is strongest here.

**The second and third months** are the upslope. Things start clicking. You develop muscle memory for the syntax. You start to understand the idioms not just intellectually but intuitively. You begin to see the beauty in the design decisions that confused you earlier.

**Around six months** you start to feel competent. Not expert — competent. You can build things without constantly referring to documentation. You can read other people's code and understand it. You can have opinions about the ecosystem that are informed by experience.

Knowing this timeline won't make the valley less uncomfortable. But it might keep you from interpreting the valley as evidence that you've failed, when it's actually evidence that you're on schedule.

## Being Kind to the Learner You Are

At the end of the day, the developer struggling with a new learning curve is still you. Still the same person who overcame the learning curve of the first language, and the second, and every other hard thing they've ever learned.

The you who doesn't know how to declare a variable in Rust is the same you who designs distributed systems in your sleep. The you who can't get the TypeScript compiler to stop yelling is the same you who has opinions about database indexing that are worth real money.

The learning curve doesn't erase what came before. It just temporarily hides it. And the kindest, most productive thing you can do in that temporary hiding is to treat yourself the way you'd treat any other intelligent person learning something hard: with patience, with encouragement, and with the unshakable conviction that they'll get there.

Because you will.

---

*Next: [Chapter 11 - Going Deep vs. Going Broad](11-going-deep-vs-going-broad.html)*
