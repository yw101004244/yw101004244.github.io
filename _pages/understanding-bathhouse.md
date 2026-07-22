---
permalink: /understanding/bathhouse-queue/
title: "The Bathhouse Queue Mystery: When a Bottleneck Moves"
excerpt: "Three hypotheses and a manager interview explain why an outdoor queue disappeared while the bathhouse remained crowded."
author_profile: true
share: false
comments: false
---

<p class="understanding-back"><a href="/understanding/">← Back to the Understanding Series</a></p>

<div class="understanding-article-meta">
  <span>Exploration 02</span>
  <span>Causal inference</span>
  <span>Queues & policy</span>
</div>

<div class="understanding-summary" markdown="1">
**In one sentence.** The bathhouse did not become less crowded; the manager increased the number of locker keys available at peak time, moving people through the entrance faster and relocating the visible queue from outside to the shower area inside.
</div>

## Observation

At around 10:30 p.m., the men's bathhouse in my residential area often had a long outdoor queue. Then, over several days, something changed: almost nobody waited outside, yet there were still many people lining up at individual shower-room doors inside.

Demand did not appear to have disappeared. The queue had changed location.

That distinction matters. A queue can vanish because the system has more total capacity, because fewer people arrive, or because one stage has become faster and pushed congestion downstream. The visible symptom alone does not identify the cause.

## The process

The bathhouse can be simplified into five stages:

<div class="understanding-flow" aria-label="Simplified bathhouse process">
  <div>Arrive outside</div>
  <div>Receive a locker key</div>
  <div>Change clothes</div>
  <div>Wait for a shower</div>
  <div>Wash and leave</div>
</div>

The key question was: **which stage changed?**

## Three hypotheses

### 1. Several faucets had failed

Fewer working faucets would reduce service capacity. With demand unchanged, that should usually make the upstream queue longer, not eliminate it. It also would not explain why people had suddenly moved from waiting outside to waiting inside. I considered this unlikely.

### 2. More people skipped lockers and changed inside

This could relocate people without changing the total number of users. But moving the same queue from one place to another is not enough: at least one stage must also have become faster, otherwise the outside admission rate would remain similar. The hypothesis was possible but incomplete.

### 3. More locker keys were released during the peak

The bathhouse has a fixed pool of locker keys. If only a small subset is placed at the entrance desk, key availability limits how many people can enter and change at once. If the manager releases many more keys during the evening peak, the entrance queue clears faster—even though shower capacity is unchanged.

This predicts exactly what I observed: fewer people outside, more people waiting near the showers, and no obvious reduction in total crowding.

## Validation

After showering, I asked the manager whether more keys had recently been placed on the desk. He confirmed it. Too many people had been waiting during the peak, so he had only recently begun releasing additional keys.

The timing also fit: during quiet periods I had seen roughly a dozen keys on the desk, while peak periods could have many dozens. The policy change increased access to the changing area without increasing the number of showers.

## Mechanism: the bottleneck moved

This was not simply “a shorter queue.” It was a local intervention in a multi-stage service system:

- **before:** limited keys throttled entry, so the queue accumulated outside;
- **after:** more keys increased admission, so congestion accumulated at the shower stage;
- **unchanged:** the ultimate washing capacity remained approximately the same.

The intervention still had practical value. Moving people indoors reduced outdoor crowding and exposure to late-night cold. It made the entrance look—and probably feel—better, even if total waiting time did not fall by the same amount.

## Evidence and limitations

The evidence combines repeated observation, process reasoning, and one interview with the manager. It is stronger than a guess but weaker than a controlled study. I did not record arrival rates, waiting times, key counts, shower duration, or the number of operating faucets.

Alternative factors—weather, schedules, or changes in demand—may have contributed. The manager's explanation identifies a real intervention; it does not prove it was the only cause.

## Open questions

- Did total waiting time decrease, or did only its location change?
- How many keys should be released to balance the entrance and shower queues?
- Does moving the queue indoors improve comfort enough to justify greater internal congestion?
- Could time-stamped counts distinguish a demand change from a capacity change?

The broader lesson is that a system can look improved when a visible bottleneck disappears, even while the underlying constraint remains. To understand the change, follow the flow—not only the queue you can see.

<div class="understanding-next" markdown="1">
Next: [The Bearing Wall and the Flowers →](/understanding/online-communities/)
</div>
