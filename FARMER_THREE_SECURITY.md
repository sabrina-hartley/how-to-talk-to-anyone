# The Hardest Worker on Your Team Doesn't Trust a Word of Your Praise

![Farmer Three: Security](./img/farmer-three-security.png)

## They wanted proof, and you gave them adjectives.

A VP closed out the quarterly review with a handwritten note to their top engineer: "You are amazing and always so helpful. The team couldn't do it without you!" They meant it. They were genuinely grateful.

The engineer, a Farmer Three, read it, nodded politely, and felt nothing. Worse than nothing. A faint irritation. "Amazing" compared to what standard? "Always so helpful" in what measurable way? "Couldn't do it without you" is the kind of thing you say to everyone. It's the participation trophy of workplace praise. This person shipped three features under budget and ahead of schedule, and the feedback they got could have been written by someone who didn't read a single commit message.

The VP thought they'd strengthened the relationship. The engineer quietly started updating their resume. The note confirmed something they'd suspected for months: leadership doesn't actually track the quality of their work. They track how things *look*.

### The problem with generic communication

Most advice about workplace communication treats people as interchangeable. Write clearly. Be concise. Lead with empathy. These are fine defaults, and they fail constantly with specific people for specific reasons.

Personality science has mapped this for decades. The Enneagram identifies 27 distinct subtypes, each with a different instinctual drive that shapes how they filter, prioritize, and react to incoming messages. These are hardwired filters, running beneath conscious awareness, that determine whether your message lands or gets discarded before it's finished.

The Farmer Three runs every message through a credibility detector: **is this backed by substance, or is it just image?** Their core drive is to earn security through quality, integrity, and disciplined productivity. They want to *be* good. And they can spot the difference between grounded recognition and hollow flattery faster than anyone in the room. If your message prioritizes style over substance, you've triggered the exact thing they spend their life trying to avoid.

### Meet the Farmer Three: "Security"


> The Farmer Three has a sense of vanity for having no vanity. This Three also wants to be admired by others, but avoids openly seeking recognition. Not just satisfied with looking good, the Farmer Three strives to be good. They are determined to be a good person—to match the perfect model of how a person should be. Being the perfect model of quality implies virtue, and virtue implies a lack of vanity. Farmer Threes seek a sense of security through being good, working hard, and being effective and productive.


**Vanity for having no vanity.** This is the countertype Three. They distrust the very thing other Threes pursue. Flashy praise, image-heavy language, and superlatives without evidence all register as the kind of surface-level recognition they've built their identity against. When you call them "amazing," they hear you performing appreciation instead of demonstrating it.

**Security through substance.** Their sense of safety comes from doing quality work. Messages that connect to real output, measurable progress, and verified craft signal that you're operating on their level. Messages that float in the zone of "great vibes" and "awesome energy" signal that you're not tracking what actually matters.

**Workmanlike discipline.** They value efficiency and credibility in communication because it mirrors how they approach their own work. A concise, well-structured message with clear deliverables tells them you respect their time and their standards. A verbose, hype-heavy message tells them you care more about impression management than execution.

### 5 ways you're losing them before you start

1. **Hype without proof.** "This could be a huge win for us!" Reads as vanity and risk. Where are the deliverables? What's the evidence? Practical claims backed by data earn engagement. Enthusiasm without substance earns suspicion. Back every claim with a specific deliverable or data point.

2. **Style over substance.** "Let's make this look really impressive for the board." This undermines credibility. They want to make things *be* good. Prioritize craft quality and execution detail over appearance language.

3. **Moral flattery without verification.** "You're such an ethical leader and the team really looks up to you." When praise references character but isn't tied to specific verified work, it feels manipulative. They know what flattery sounds like because they've spent their life avoiding it. Recognize character through concrete examples of the work that demonstrates it.

4. **Ambiguous scope.** "Take the lead on this and make sure it goes well." This threatens their effectiveness because they can't optimize what isn't defined. What's the scope? What's the timeline? What's the quality bar? Define all three and they'll overdeliver. Leave them undefined and they'll waste energy trying to infer what you actually want.

5. **Time-wasting preamble.** "So I was thinking over the weekend, and I had this conversation with Sarah about how we might approach..." They're already scanning for the point. Every sentence beyond the objective and the required output signals inefficiency and disrespect for their time. Start with the objective and the required output.

### What they actually want to hear

| What you sent | What would have landed |
|---|---|
| "This could be a great win for us." | "Deliverable is due Thursday with these three quality checks." |
| "You are amazing and always so helpful." | "Your consistency is high. Complete steps A and B and we ship." |
| "Let us make this look impressive." | "Let us make this accurate reliable and ready for production." |

For this subtype, communication that sounds like a pitch triggers distrust. Communication that sounds like a production plan triggers engagement. They want to be deployed.

---

### Try it out: FREE Communication Optimizer for Farmer Threes

Paste your draft message into your LLM, then paste the following prompt after it. The model will rewrite your message specifically for this subtype.

```
mode: communication_optimizer
target_subtype: FARMER_THREE
subtype_name: Security
instinct: self_preservation
core_drive: "earn security and admiration through quality integrity and disciplined productivity"
communication_stance: "quality-proof,reliability-first,quiet-achievement,integrity-driven"
tone[4]:
  - professional over flashy
  - efficient over verbose
  - credible over hyped
  - steady over performative
message_rules[6]:
  - lead with quality standard and reliability requirement
  - show competence through concrete output and evidence
  - connect recognition to substance and ethics
  - keep communication concise and workmanlike
  - provide measurable milestones and completion criteria
  - close with the next production step and owner
anti_patterns[5]{id,pattern,why_it_fails,fix}:
  1,hype_without_proof,reads as vanity and risk,back claims with deliverables and data
  2,style_over_substance,undermines credibility,prioritize craft quality and execution detail
  3,moral_flattery_only,feels manipulative,recognize character through verified work
  4,ambiguous_scope,threatens effectiveness,define scope timeline and quality bar
  5,time_wasting_preamble,signals inefficiency,start with objective and required output
few_shot[3]{id,generic,optimized}:
  1,"This could be a great win for us.","Deliverable is due Thursday with these three quality checks."
  2,"You are amazing and always so helpful.","Your consistency is high. Complete steps A and B and we ship."
  3,"Let us make this look impressive.","Let us make this accurate reliable and ready for production."
quality_gate[4]:
  - each sentence should strengthen credibility
  - eliminate image language not tied to output
  - keep requests measurable and executable
  - preserve respect for disciplined craftsmanship
input_source: prior_thread_message
```

---

### Twenty-seven subtypes. One message.
The Farmer Three needs substance and credibility before they'll trust your message. Compare that to the Teamer Three ("Prestige"), who actually *wants* the spotlight and filters for status and visible achievement. Or the Farmer One ("Worry"), who also values discipline and standards but processes communication through anxiety about correctness rather than credibility. Same drive for quality, completely different filter mechanisms determining what gets through.

> ***Personalization determines whether your message gets read or discarded.***

The leaders who learn to match their recognition to how each person actually processes it will retain their best performers. Everyone else will keep writing heartfelt notes that land as noise, wondering why their top people keep leaving.

#### Your best people are motivated by your standards.

It's why we're building [Rally](https://www.rally.ai/), communications automatically optimized for each person's instinctual profile. See how we do it: [AI Smells Remover](./you-smell-like-bad-ai-2026-02-14.md).

---

**This is Part 7 of a 27-part series on subtype-specific communication.**

| | |
|---|---|
| Previous | [Hunter Two: Seduction](./HUNTER_TWO_SEDUCTION.md) |
| Next | [Teamer Three: Prestige](./TEAMER_THREE_PRESTIGE.md) |

[Back to series index](./README.md)
