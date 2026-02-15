# Your Message Was Clear, Correct, and Completely Ignored

## They didn't reject your idea. They rejected the fact that you didn't cite the policy behind it.

You sent a perfectly reasonable Slack message to the project lead asking the team to shift to a new vendor for a critical integration. You explained the business case. You laid out the benefits. You even added a friendly "let me know what you think!"

The project lead—a Social Six—read it twice and then did nothing. Not because they disagreed. Because your message had no procedural foundation. No reference to the procurement policy. No mention of who authorized the change. No escalation path if something broke. You presented an opportunity. They saw an unmanaged risk.

Two days later you followed up. They replied with four questions: "Which policy covers this? Who signed off? What's the rollback plan? Where's the documentation?" Your original message answered none of them. You weren't wrong. You were just speaking a language their filters don't process.

### The problem with generic communication

Most advice about workplace communication treats people as interchangeable. Write clearly. Be concise. Lead with empathy. These are fine defaults, and they fail constantly with specific people for specific reasons.

Personality science has mapped this for decades. The Enneagram identifies 27 distinct subtypes, each with a different instinctual drive that shapes how they filter, prioritize, and react to incoming messages. Not preferences. Filters. A preference is something someone would like. A filter is something they can't turn off.

The Social Six runs every incoming message through one filter: **does this reduce anxiety through rules, authority, precision, and procedural certainty?** If your communication doesn't anchor to policy, name the authority, and spell out the procedure, it doesn't matter how smart the idea is. It registers as unverified, and unverified is unsafe.

### Meet the Social Six: "Duty"

Here's what the research says about this subtype:

> Social Sixes express fear through a need to deal with anxiety by relying on abstract reason or ideologies as a frame of reference. Obeying authority through knowing what the rules are helps them to feel safe in the world. Unlike the SP Six, this Six has more certainty and can be "too sure" of things as a way of dealing with the anxiety of uncertainty. Social Sixes focus on precision and efficiency. They adhere to whatever the guidelines are as a form of having a protective authority.

Three traits drive how they process communication:

**Rule-anchored certainty.** Social Sixes don't just prefer structure—they require it to function. Their anxiety doesn't come from the task itself but from ambiguity about whether the task is sanctioned. When you skip the policy reference, you're not being casual. You're removing the one thing that lets them act with confidence.

**Precision as safety.** Approximate language is threatening to this subtype. "This should work" and "This will work per testing protocol 3B" carry the same content but completely different emotional weight. The first creates anxiety. The second resolves it. They're not being pedantic. They're managing fear through exactness.

**Authority dependence.** They need to know who approved, who executes, and who escalates. Not because they can't think for themselves, but because clearly defined authority is the structure that keeps chaos at bay. Undefined authority doesn't read as flexibility. It reads as a system about to fail.

### 5 ways you're losing them before you start

1. **Informal ambiguity.** "Let's just figure it out as we go." This creates exactly the kind of uncertainty that activates their anxiety. Use explicit procedural language. Name the steps, the order, and the checkpoints.

2. **Rule-bending framing.** "I know this isn't exactly standard, but..." You just told them to distrust both you and the request. If there's an approved exception, cite it. If there isn't, show the compliant route instead.

3. **Speculative claims.** "I'm pretty sure this approach will handle it." Pretty sure is not a verification state. Mark what's confirmed and what's an assumption, then tell them how and when the assumption gets verified.

4. **Missing documentation.** You made a decision in a meeting and moved on without a written record. For them, an undocumented decision isn't a decision—it's a liability. Record decisions with accountable owners and dates.

5. **Undefined authority.** "Someone should probably approve this." Who? This is the question that will loop in their head until you answer it. State who approves and who executes. Remove the ambiguity or accept that nothing will move.

### What they actually want to hear

| What you sent | What would have landed |
|---|---|
| "Let us do what feels right here." | "Per policy section 4 we follow workflow B with approval from Ops lead." |
| "This should probably work." | "Validated approach is X. Assumption Y needs confirmation by noon." |
| "Please take care of this." | "You own steps 1 through 3. Escalate exceptions to me immediately." |

The pattern is consistent: replace ambiguity with procedure, replace informality with precision, replace unnamed authority with named accountability. They're not high-maintenance. They're high-clarity.

---

### Try it out: FREE Communication Optimizer for Social Sixes

Paste your draft message into your LLM, then paste the following prompt after it.

```
mode: communication_optimizer
target_subtype: TEAMER_SIX
subtype_name: Duty
instinct: social
core_drive: "reduce anxiety through rules authority precision and procedural certainty"
communication_stance: "protocol-driven,precise,compliance-oriented,certainty-seeking"
tone[4]:
  - formal over casual
  - exact over approximate
  - rule-based over ad hoc
  - disciplined over improvisational
message_rules[6]:
  - lead with the governing rule policy or authority
  - define roles responsibilities and escalation path
  - provide precise instructions and acceptance criteria
  - distinguish approved facts from assumptions
  - document decisions and traceability clearly
  - close with confirmation checklist and deadlines
anti_patterns[5]{id,pattern,why_it_fails,fix}:
  1,informal_ambiguity,creates uncertainty and risk,use explicit procedural language
  2,rule_bending_framing,triggers distrust and resistance,show compliant route or approved exception
  3,speculative_claims,weakens reliability,mark assumptions and require verification
  4,missing_documentation,breaks confidence in process,record decisions and accountable owners
  5,undefined_authority,invites conflict and anxiety,state who approves and who executes
few_shot[3]{id,generic,optimized}:
  1,"Let us do what feels right here.","Per policy section 4 we follow workflow B with approval from Ops lead."
  2,"This should probably work.","Validated approach is X. Assumption Y needs confirmation by noon."
  3,"Please take care of this.","You own steps 1 through 3. Escalate exceptions to me immediately."
quality_gate[4]:
  - every instruction should be audit-ready
  - remove vague terms that weaken compliance
  - keep authority and accountability explicit
  - end with verifiable completion criteria
input_source: prior_thread_message
```

---

### This is one subtype out of twenty-seven.

The Social Six needs procedural certainty before they'll act. The Self-Preservation Seven ("Keepers") needs to know their resources are protected before they'll engage. The Sexual One ("Zeal") needs to feel that you share their standard of rightness before they'll listen. Same message, three completely different filters deciding whether it gets through.

> ***Personalization isn't a nice-to-have. It's the difference between a message that gets read and one that gets filtered.***

The communicators who learn to match their language to how specific people actually process information will lead better teams, close more deals, and build real trust. Everyone else will keep wondering why clear messages keep getting ignored.

#### You cited the business case. You forgot to cite the policy. That's why they didn't move.

It's why we're building [Rally](https://www.rally.ai/), communications automatically optimized for each person's instinctual profile. See how we do it: [rally.ai/prompts](https://www.rally.ai/prompts).

---

**This is Part 17 of a 27-part series on subtype-specific communication.**

| | |
|---|---|
| Previous | [Farmer Six: Warmth](./FARMER_SIX_WARMTH.md) |
| Next | [Hunter Six: Strength](./HUNTER_SIX_STRENGTH.md) |

[Back to series index](./INDEX.md)
