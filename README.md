# musk-review

First-principles executive review skill for product proposals, technical architecture, growth strategies, and internal memos.

It is designed to feel like a hard-edged review room:

- lead with the verdict
- identify the real bottleneck
- say what to cut
- make the call

Use it when you want a sharper answer than a neutral brainstorm. This skill is built to reduce vague strategy into a concrete decision.

## Install

```bash
npx skills add https://github.com/RealFelixWang/musk-review-skill --skill musk-review
```

## Skill Path

```text
.claude/skills/musk-review
```

## What It Does

- Pressure-test proposals with first-principles reasoning
- Cut scope before optimizing complexity
- Surface the dominant bottleneck
- Turn vague plans into concrete decisions
- Rewrite overbuilt plans into a sharper wedge

## Main Use Cases

- Product proposal review
- Technical architecture review
- Growth strategy review
- Internal memo review
- Rewrite a broad proposal into something tighter and more executable

## Example Prompts

### Product proposal

```text
Review this AI meeting assistant plan with a Musk-style lens. We want transcription, summaries, action items, weekly reports, sales call scoring, knowledge base Q&A, and email drafting. Team is 4 people. Launch target is 3 months.
```

What you should expect:

- a blunt verdict on whether the scope is overbuilt
- the one bottleneck that matters most
- a clear statement of what to cut
- a narrower wedge to build first

### Technical architecture

```text
Review this architecture for a real-time voice AI platform. Current plan is Kubernetes on three clouds, Kafka for every event, and separate services for ASR, orchestration, CRM sync, scoring, analytics, and billing. We expect around 500 concurrent calls in the first six months.
```

What you should expect:

- a direct call on whether the system is overengineered
- the real bottleneck instead of generic architecture commentary
- a simpler near-term architecture path

### Growth strategy

```text
Review this growth plan like a high-pressure executive review. We are at $20k MRR and want to do SEO, affiliates, YouTube, X, Reddit, Product Hunt, cold email, and podcast sponsorships at the same time. Retention is mediocre.
```

What you should expect:

- a call on whether this is really a growth problem or a retention problem
- which channel sprawl to cut
- the one growth loop worth proving first

### Rewrite mode

```text
Rewrite this proposal into something that would actually get approved to build. Right now it tries to be a full platform with multiple user types, multiple entry points, and too many features.
```

What you should expect:

- one target user
- one painful problem
- one primary workflow
- one entry point
- one success metric

## Why This Is Useful

Most strategic reviews fail because they stay balanced and polite for too long. This skill is useful when you need a stronger answer to questions like:

- Are we solving the right problem?
- What is the real bottleneck?
- What should we cut right now?
- Should we proceed, narrow the scope, pause, or stop?
