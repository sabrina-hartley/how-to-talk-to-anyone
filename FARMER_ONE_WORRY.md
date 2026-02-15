# The Nicest Person on Your Team Has Already Found Three Errors in Your Email

![Farmer One: Worry](./img/farmer-one-worry.png)

## They'll just stop trusting you.

Last Tuesday, a project lead sent a Slack message to their most reliable team member: "Can you clean this up when you get a chance? Just make it better."

The intent was casual delegation: quick task, trusted person, easy handoff. The recipient, a Farmer One, read it six times. Clean *what* up? To what standard? What does "better" mean? Is "when you get a chance" today or this week? And "just make it better" implies it's currently bad, but nobody specified *how* it's bad.

They didn't reply for forty minutes. They were building a mental checklist of every possible interpretation, trying to figure out how to do it right without a definition of right. By the time they started, they were anxious, slightly resentful, and already bracing for the goalposts to move.

### The problem with generic communication

Most advice about workplace communication treats people as interchangeable. Write clearly. Be concise. Lead with empathy. These are fine defaults, and they fail constantly with specific people for specific reasons.

Personality science has mapped this for decades. The Enneagram identifies 27 distinct subtypes, each with a different instinctual drive that shapes how they filter, prioritize, and react to incoming messages. These are hardwired filters, running beneath conscious awareness, that determine whether your message lands or gets discarded before it's finished.

The Farmer One runs every incoming message through a single filter: **does this meet the standard, and can I execute it correctly?** Their instinctual drive is to be good and correct through disciplined self-improvement, keeping anger tightly contained beneath a warm, agreeable surface. If your message introduces ambiguity about what "correct" means, you've activated their deepest anxiety.

### Meet the Farmer One: "Worry"


> Farmer Ones are the true perfectionists of the three Ones. They express the passion of anger through working hard to make themselves and the things they do more perfect. In this subtype, anger is the most repressed emotion; the defense mechanism of reaction formation transforms the heat of anger into warmth, resulting in a friendly and benevolent character.


**Anger converted to warmth.** This person is frustrated by your sloppy email. They will never tell you that. The defense mechanism of reaction formation means their anger shows up as agreeableness, even friendliness. You'll think they're fine, but they're containing a critique they believe would be inappropriate to voice, and they're redirecting that energy into doing the work more carefully than you asked them to.

**Perfectionism as survival strategy.** For this subtype, getting something wrong registers as a moral failure. Every ambiguous instruction creates a minefield. They need explicit standards because standards are the only thing that makes the anxiety quiet down. Give them a checklist and they're your most reliable person. Give them "just figure it out" and you've created a stress spiral.

**Orderly execution as trust signal.** They judge your communication by its precision. A message with typos, vague timelines, or shifting criteria tells them you don't care as much as they do. And if you don't care, they can't trust the process. Discipline in your message signals discipline in your thinking.

### 5 ways you're losing them before you start

1. **Vague expectations.** "Can you take a look at this and tighten it up?" This creates immediate anxiety about doing it wrong. There's no standard to measure against, no criteria for success, and no way to know when they're done. State the explicit standard and acceptance criteria: what "done" looks like, what quality bar applies, when it's due.

2. **Sloppy wording.** "Lets circle back tmrw and see were at." Every misspelling and imprecise phrase signals carelessness and weak discipline. To someone who runs on precision, this registers as disrespect. Use precise terms and unambiguous instructions. Proofread. It takes thirty seconds and buys you hours of trust.

3. **Emotional pressure.** "I'm really counting on you for this—it would mean so much to me." This feels manipulative and destabilizing. They don't want to manage your feelings on top of managing the work. Keep tone steady and fact-anchored. Tell them what to do, not how to feel about doing it.

4. **Moving goalposts.** "Actually, I changed my mind on the format—can you redo the last section?" Nothing erodes their trust faster than shifting criteria after execution begins. It tells them the standard was never real. Lock criteria before execution starts, and if you must change scope, acknowledge the shift explicitly.

5. **Critique without a corrective path.** "This isn't quite what I was looking for." This triggers a self-judgment loop with no exit. They'll replay the failure endlessly without knowing what to fix. Pair every critique with a specific corrective step: what's wrong, what to change, and what "right" looks like.

### What they actually want to hear

| What you sent | What would have landed |
|---|---|
| "Can you clean this up when you get a chance?" | "Please align this to the published standard by 4 PM. Use the checklist below." |
| "This is close but not quite right." | "Two issues block approval: section headers and citation format. Fix these and it is ready." |
| "I know you care and I appreciate your effort." | "Your rigor shows. Apply these three edits and quality will meet the bar." |

For this subtype, precision *is* warmth. Telling them exactly what to do is the most respectful thing you can say.

---

### Try it out: FREE Communication Optimizer for Farmer Ones

Paste your draft message into your LLM, then paste the following prompt after it. The model will rewrite your message specifically for this subtype.

```
mode: communication_optimizer
target_subtype: FARMER_ONE
subtype_name: Worry
instinct: self_preservation
core_drive: "be good and correct through disciplined self-improvement while keeping anger contained"
communication_stance: "standards-first,calm,precision-guided,improvement-oriented"
tone[4]:
  - calm over dramatic
  - exact over approximate
  - respectful over confrontational
  - orderly over improvisational
message_rules[6]:
  - lead with the standard being protected
  - define error criteria and success criteria up front
  - provide stepwise improvements with clear quality checks
  - acknowledge effort and integrity before critique
  - use neutral language and avoid emotional pressure
  - close with one concrete next action and timing
anti_patterns[5]{id,pattern,why_it_fails,fix}:
  1,vague_expectations,creates anxiety about doing it wrong,state explicit standards and acceptance criteria
  2,sloppy_wording,signals carelessness and weak discipline,use precise terms and unambiguous instructions
  3,emotional_overdrive,feels manipulative and destabilizing,keep tone steady and fact anchored
  4,moving_goalposts,erodes trust in fairness,lock criteria before execution
  5,critique_without_path,triggers self-judgment loops,pair every critique with a corrective step
few_shot[3]{id,generic,optimized}:
  1,"Can you clean this up when you get a chance?","Please align this to the published standard by 4 PM. Use the checklist below."
  2,"This is close but not quite right.","Two issues block approval: section headers and citation format. Fix these and it is ready."
  3,"I know you care and I appreciate your effort.","Your rigor shows. Apply these three edits and quality will meet the bar."
quality_gate[4]:
  - every sentence should reduce ambiguity
  - no praise or critique without operational detail
  - keep sequencing explicit from standard to action
  - preserve dignity while tightening execution
input_source: prior_thread_message
```

---

### Twenty-seven subtypes. One message.
The Farmer One needs standards and precision before they can act. Compare that to the Hunter One ("Zeal"), who channels anger outward as reforming intensity and wants your conviction, not your checklist. Or the Teamer Two ("Ambition"), who filters every message through strategic influence and expects you to acknowledge their power. Same workplace, same Slack channel, completely different filters running beneath the surface.

> ***Personalization determines whether your message gets read or discarded.***

Every person on your team has a filter like this. Most senders never learn what it is. The ones who do get better work, faster responses, and fewer misunderstandings, because they wrote the right message for the right person.

#### Match their frequency and your most reliable people become the easiest to reach.

It's why we're building [Rally](https://www.rally.ai/), communications automatically optimized for each person's instinctual profile. See how we do it: [AI Smells Remover](./you-smell-like-bad-ai-2026-02-14.md).

---

**This is Part 1 of a 27-part series on subtype-specific communication.**

| | |
|---|---|
| Next | [Teamer One: Non-Adaptability](./TEAMER_ONE_NON_ADAPTABILITY.md) |

[Back to series index](./README.md)
