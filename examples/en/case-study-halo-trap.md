---
title: "Case Study — The Halo Trap"
context: "After 9 consecutive Kill verdicts on the author's own ideas, idea-killer stopped recommending an idea #10 and ran a meta-diagnostic on the founder portrait itself."
takeaway: "The most useful thing the skill ever said was not a verdict on an idea. It was a verdict on the assumptions about the founder."
---

# The Halo Trap — Case Study

## What happened

After 9 consecutive Kill verdicts, the author tried to push idea-killer toward yet another direction: "one-person company AI stack / Claude Code dev tools — at least that's where my engineering background fits."

He typed:

> "Honestly, my engineering ability isn't strong relative to other developers. I don't think I have an edge there either."

This was the third self-correction in 30 days. The skill paused.

## What the skill said back

Instead of suggesting yet another idea, it produced this:

> "Your third self-correction forces me to stop. The 9 previous Kills weren't because your ideas weren't good enough.
> 
> They were because **the 'asymmetric advantages' I was assuming for you were halo assumptions** — relative to random people, not relative to actual competitors in those markets.
> 
> Drop into the *actual competitive layer* of each direction — not the resume layer — and you're at zero in every one of them.
> 
> This is profile mismatch. It is not an idea-supply problem."

It then surfaced the table the founder couldn't see for himself:

| What I was recommending | The actual competitive layer | Founder's position there |
|---|---|---|
| Cross-border AI agency | Cross-border veterans + insider co-founder | No experience → 0 |
| Fitness AI coach | CV / pose-estimation experts + fitness coaches | Not in field → 0 |
| Cross-border product picker | 5-8 year actual seller teams | Same → 0 |
| Proactive push channel | Content-IP matrix operators | Introvert + no on-camera → 0 |
| One-person AI dev tools | Simon Willison / theo.gg / early MCP contributors | Just admitted not strong → 0 |

## What the skill recommended instead

It gave three meta-options — none of them "another idea":

**1. Find a co-founder. Stop going solo.**
Profile + a "domain know-how + insider network + outbound GTM" co-founder unlocks every one of the high-score directions.

**2. Lower expectations. Side project, not venture.**
Solo founder profile can hit ¥5-20k/month indie SaaS or content subscription with 30-40% probability. Venture-scale alone with this profile is < 10%. Recalibrate.

**3. Embed for 6 months. Don't start a company yet.**
Join an early team in a vertical you're curious about. Trade 6 months of runway for know-how + relationships + 1-2 potential co-founder candidates. This is patching the profile, not abandoning the company.

## Why this is the actual product

A normal idea validator would have produced a 10th, 11th, 12th idea — each of them a "fresh" search.

The 10th Kill would have looked like the previous 9. The 11th would have too.

idea-killer's structural-dedup memory caught the pattern that the founder couldn't see in real-time: **the input wasn't the bottleneck — the founder model was wrong**.

The product isn't 10 Kill verdicts. The product is the moment the system says "stop optimizing the wrong variable."

## What the founder did with it

The founder didn't pick another idea. He went the route that almost no validator would push:

- Don't choose a startup direction yet
- Build a public track record for 12-18 months: ship publicly, write on X, accumulate IP
- Let directions self-select from what gets traction

This is the strategy now sitting in the README's "meta-twist" section. It's also why this skill exists publicly: to prevent other founders from spending 6 months optimizing the wrong variable.

---

## What to learn from this if you're using idea-killer

If you've Kill'd 3+ ideas in a row:

- It's probably not the ideas
- It's probably your portrait — specifically the "advantages" you've been assuming are real moats but are actually halo
- Don't push for idea #4 until you've checked: at the *real* competitive layer, where do I actually rank?

idea-killer has a `diagnostic-mode` that triggers automatically after 3+ consecutive Kills. It runs the same meta-check on whatever profile is in `PROFILE.md`. If it finds halo, it surfaces the gap before you waste another sprint.
