# Your Reassurance Is Making Them Trust You Less

## When you tell a Farmer Six "don't worry," they hear "I haven't thought about what could go wrong."

![Farmer Six: Warmth](./img/farmer-six-warmth.png)

Your project lead emailed the team on Monday morning: "Big news — we're restructuring the Q3 roadmap. Details coming soon. Don't worry, everything is going to be great!"

Most of the team shrugged and moved on. One person didn't. They reread the email four times. They opened the org chart. They checked Jira for reassigned tickets. They messaged three coworkers asking if anyone knew more. By lunch, they'd drafted a contingency plan for their own workstream, because nobody else had acknowledged that "restructuring" means things could break.

Your announcement landed for most people as exciting news. For the Farmer Six, it landed as an unmitigated threat with a patronizing footnote. "Details coming soon" means there's no plan yet. "Don't worry" means you haven't done the risk assessment. "Everything is going to be great" means you're either lying or you haven't thought hard enough. Every sentence made them less safe, not more.

### The problem with generic communication

Most advice about workplace communication treats people as interchangeable. Write clearly. Be concise. Lead with empathy. These are fine defaults, and they fail constantly with specific people for specific reasons.

Personality science has mapped this for decades. The Enneagram identifies 27 distinct subtypes, each with a different instinctual drive that shapes how they filter, prioritize, and react to incoming messages. These are hardwired filters, running beneath conscious awareness, that determine whether your message lands or gets discarded before it's finished.

The Farmer Six filters every message through one question: **is this safe, and can I trust the person saying it?** They're scanning for gaps between what you're promising and what you've actually secured. Optimism without operational backing disqualifies you. They need you to show them the plan, name the risks, and prove the safety net exists.

### Meet the Farmer Six: "Warmth"


> Farmer Sixes express the passion of fear through a need for protection, for friendship, and for banding together with others. In seeking protective alliances, Farmer Sixes endeavor to be warm, friendly, and trustworthy, which is why they bear the name "Warmth." This most "phobic" of the Sixes has difficulty expressing anger, feels uncertain, and engages in a lot of self-doubt. For Farmer Sixes, fear manifests as insecurity, and they focus on relationships as a way of feeling safer in the world.


**Alliance as architecture.** Safety for this person is a network. They build protective relationships the way engineers build redundant systems. When your message uses isolating language ("Can you handle this on your own?"), you're cutting their safety net. They need to know who's on the team, who's accountable, and who has their back.

**Doubt as due diligence.** Their self-doubt functions as a scanning process. They're stress-testing every plan, every promise, and every timeline for the failure mode nobody mentioned. When you dismiss their concerns or hand-wave risks, you prove you haven't done the work. They trust people who acknowledge what could go wrong, not people who insist nothing will.

**Warmth as trust protocol.** They're warm because warmth builds alliances, and alliances build safety. But their warmth has a transactional core: they're tracking whether you're reliable, consistent, and honest. Overconfident promises, shifting commitments, or surprise changes all break the protocol. They need follow-through.

### 5 ways you're losing them before you start

1. **Springing surprises.** "Quick update — we've shifted direction on the product launch." Without context, rationale, and a clear what-happens-next, surprise changes spike their insecurity and erode trust instantly. Announce changes early, explain the reasoning, and lay out the impact before they have to ask.

2. **Dismissing their fear.** "You're overthinking this — it'll be fine." You just told them their threat-detection system is broken. It's not. It's the most finely tuned instrument in the room. Acknowledge the risk they've identified and provide specific mitigation. That's how you earn their trust.

3. **Making promises you can't guarantee.** "I promise this will be done by Friday, no issues." Overconfident guarantees reduce your credibility with someone who's already mentally cataloging everything that could prevent Friday delivery. State realistic commitments with backup plans for the scenarios that worry them.

4. **Using isolating language.** "This is your project now — run with it." What they heard: you're on your own, and if it fails, it's on you. Use "we"-focused phrasing. Name shared ownership. Make the support structure explicit, even if it seems obvious to you.

5. **Leaving ownership ambiguous.** "Someone should probably follow up on this." Who? By when? With what escalation path if it stalls? Ambiguous ownership creates anxiety loops where they feel responsible for everything and empowered for nothing. Assign roles, deadlines, and escalation contacts explicitly.

### What they actually want to hear

| What you sent | What would have landed |
|---|---|
| "Do not worry everything is fine." | "Current risk is X and mitigation is Y. We review status at 2 PM." |
| "Just trust the process." | "Here is the process owner, timeline, and fallback if issue A appears." |
| "Can you handle this alone?" | "We will handle this together. You own step one and I cover escalation." |

The Farmer Six needs operational certainty.

---

### Try it out: FREE Communication Optimizer for Farmer Sixes

Paste your draft message into your LLM, then paste the following prompt after it. The model will rewrite your message specifically for this subtype.

```
mode: communication_optimizer
target_subtype: FARMER_SIX
subtype_name: Warmth
instinct: self_preservation
core_drive: "create safety through trustworthy alliances clear protection and dependable connection"
communication_stance: "safety-first,reassuring,trust-building,alliance-oriented"
tone[4]:
  - warm over cold
  - steady over volatile
  - collaborative over isolating
  - clear over ambiguous
message_rules[6]:
  - begin by reducing uncertainty with concrete facts
  - communicate loyalty reliability and follow-through
  - include contingency plans and support contacts
  - invite questions and validate concerns
  - use collaborative language that signals partnership
  - close with a specific checkpoint and next step
anti_patterns[5]{id,pattern,why_it_fails,fix}:
  1,surprise_changes,spikes insecurity and distrust,announce changes early with rationale
  2,dismissing_fear,feels unsafe and invalidating,acknowledge risk and provide mitigation
  3,overconfident_promises,reduces credibility,state realistic commitments and backup plans
  4,isolating_language,weakens alliance security,use we-focused phrasing and shared ownership
  5,unclear_ownership,creates anxiety loops,assign roles and escalation path explicitly
few_shot[3]{id,generic,optimized}:
  1,"Do not worry everything is fine.","Current risk is X and mitigation is Y. We review status at 2 PM."
  2,"Just trust the process.","Here is the process owner timeline and fallback if issue A appears."
  3,"Can you handle this alone?","We will handle this together. You own step one and I cover escalation."
quality_gate[4]:
  - every message should increase felt safety
  - no reassurance without operational backing
  - keep alliance and responsibility explicit
  - end with a predictable next checkpoint
input_source: prior_thread_message
```

---

### Twenty-seven subtypes. One message.
The Farmer Six needs you to prove the safety net before they'll step forward. The Farmer Five ("Castle") needs you to prove you won't cross their boundaries before they'll engage at all. The Hunter Eight ("Possession") needs intensity and direct challenge, the very thing that would send the Farmer Six into a spiral. Same hallway, same office, three people filtering for completely different survival signals.

> ***Personalization determines whether your message gets read or discarded.***

The leaders who learn to match their message to each person's threat-detection system will build teams that move faster and trust deeper. Everyone else will keep wondering why their reassuring emails make certain people more anxious, not less.

#### "Don't worry" means twenty-seven different things to twenty-seven subtypes, and for this one, it means you haven't done your homework.

It's why we're building [Rally](https://www.rally.ai/), communications automatically optimized for each person's instinctual profile. See how we do it: [AI Smells Remover](./you-smell-like-bad-ai-2026-02-14.md).

---

**This is Part 16 of a 27-part series on subtype-specific communication.**

| | |
|---|---|
| Previous | [Hunter Five: Confidence](./HUNTER_FIVE_CONFIDENCE.md) |
| Next | [Teamer Six: Duty](./TEAMER_SIX_DUTY.md) |

[Back to series index](./README.md)
