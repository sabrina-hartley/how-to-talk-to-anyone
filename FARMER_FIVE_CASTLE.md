#### FARMER FIVE - CASTLE

# The Coworker Who Ghosts Your Slack Messages Isn't Rude. You're Just Loud.

## Keep pinging them and you'll get silence because you've become the threat.

![Farmer Five: Castle](./img/farmer-five-castle.png)

You wrote a friendly Slack message to a senior engineer on your team. "Hey! Just checking in — wanted to see how you're feeling about the project direction. Would love to hop on a quick call to brainstorm some ideas. I think your perspective would really add a lot!"

Warm, enthusiastic, collegial, and for a Farmer Five, a three-alarm fire.

They didn't see friendliness. They saw: an unstructured teamer demand (the call), an emotional labor request (how are you *feeling*?), a vague scope with no exit (brainstorm), and an implicit obligation disguised as a compliment (your perspective would add a lot). Four boundary violations in three sentences. They didn't respond. Your message required more energy to navigate than you realize, and they calculated, correctly, that ignoring it was cheaper than managing you.

### The problem with generic communication

Most advice about workplace communication treats people as interchangeable. Write clearly. Be concise. Lead with empathy. These are fine defaults, and they fail constantly with specific people for specific reasons.

Personality science has mapped this for decades. The Enneagram identifies 27 distinct subtypes, each with a different instinctual drive that shapes how they filter, prioritize, and react to incoming messages. These are hardwired filters, running beneath conscious awareness, that determine whether your message lands or gets discarded before it's finished.

The Farmer Five runs every incoming message through one filter: **does this protect or violate my boundaries, privacy, and self-sufficiency?** They're evaluating whether engaging with your message will cost more energy than they can afford. If your communication demands teamer performance, emotional disclosure, or open-ended interaction, you've already been sorted into the "drain" category, and they don't have a budget for drains.

### Meet the Farmer Five: "Castle"


> The Farmer Five expresses avarice through a focus on boundaries — a need to be "encastled" in a sanctuary where they feel protected from intrusion and have control over their boundaries. Farmer Fives have a passion for being able to hide behind walls and know that they have everything they need to survive within those walls. They are the least expressive of the three Fives and they try to limit their needs and wants so that they can avoid being dependent on others.


**Boundary as operating system.** Boundaries *are* the architecture of their cognition. Every interaction is measured against the cost of engagement. When you send a message that's open-ended, socially loaded, or scope-ambiguous, you're asking them to expend energy they've specifically organized their life to conserve.

**Minimal expressiveness.** They're the quietest Five variant, which means your silence-based feedback loops are useless. Silence means they haven't decided the ROI of responding is worth it yet. If you escalate because they didn't reply, you confirm their instinct that you're expensive to deal with.

**Self-sufficiency as identity.** They have structured their world so they don't need anyone. Messages that imply interdependence, emotional need, or collaborative intimacy conflict with their core self-concept. They accept teamwork only when it stays within their availability budget.

### 5 ways you're losing them before you start

1. **Pinging again (and again).** "Hey, just circling back on this!" "Following up again — any thoughts?" Each ping costs them energy and adds teamer debt they didn't agree to. Batch your requests into one clear message, give them a single response window with a deadline, and stop.

2. **Vague asks that force cognitive labor.** "Can we discuss the project sometime?" Discuss what? What decision? What do you need from them specifically? Undefined scope means they have to do your thinking for you before they can even start their own. State the exact decision needed and the context required to make it.

3. **Asking them to open up.** "I'd love to hear how you're really feeling about the team dynamic." This violates their privacy like an uninvited houseguest opening their closets. Keep communication task-focused. If you need personal information, make it optional and explain specifically why it's relevant.

4. **Booking a meeting with no agenda.** "Let's sync for 30 minutes tomorrow." To discuss *what*, toward *what outcome*, with *what preparation*? A meeting without an agenda signals that you don't respect efficiency, which means you don't respect their energy. Send the agenda, the intended outcome, and the prep materials before you even propose the meeting.

5. **Emotionally loaded framing.** "I'm really concerned about this and I need us to align urgently." The emotional pressure creates a demand to match your intensity, and they won't. They'll withdraw instead. Use factual language, define the scope clearly, and let them engage on the substance without managing your feelings too.

### What they actually want to hear

| What you sent | What would have landed |
|---|---|
| "Hey just checking in again about this." | "Decision needed: approve option A or B by 3 PM. Details attached." |
| "Can we hop on a call and talk through ideas?" | "Please review this brief and return comments asynchronously by tomorrow noon." |
| "I really need your support here." | "Need your technical judgment on two risks. Reply with preferred mitigation." |

The Castle needs information that doesn't come with strings attached.

---

### Try it out: FREE Communication Optimizer for Farmer Fives

Paste your draft message into your LLM, then paste the following prompt after it. The model will rewrite your message specifically for this subtype.

```
mode: communication_optimizer
target_subtype: FARMER_FIVE
subtype_name: Castle
instinct: self_preservation
core_drive: "maintain safety through boundaries privacy and self-sufficiency with minimal dependency"
communication_stance: "low-intrusion,autonomy-first,information-dense,privacy-respecting"
tone[4]:
  - concise over chatty
  - neutral over emotionally loaded
  - precise over interpretive
  - asynchronous over interruptive
message_rules[6]:
  - start with purpose and required decision in line one
  - provide complete information in compact structure
  - respect boundaries and avoid teamer pressure
  - offer async response windows and low-interruption channels
  - minimize emotional signaling and unnecessary pleasantries
  - close with independent next step and deadline
anti_patterns[5]{id,pattern,why_it_fails,fix}:
  1,repeated_pings,feels intrusive and depleting,batch requests and set one response window
  2,vague_requests,forces extra cognitive load,state exact decision needed and context
  3,forced_vulnerability,violates privacy boundaries,keep communication task-focused and optional on personal detail
  4,meeting_without_agenda,signals inefficiency,send agenda outcome and prep material first
  5,emotionally_loaded_framing,creates pressure and withdrawal,use factual language and clear scope
few_shot[3]{id,generic,optimized}:
  1,"Hey just checking in again about this.","Decision needed: approve option A or B by 3 PM. Details attached."
  2,"Can we hop on a call and talk through ideas?","Please review this brief and return comments asynchronously by tomorrow noon."
  3,"I really need your support here.","Need your technical judgment on two risks. Reply with preferred mitigation."
quality_gate[4]:
  - remove every non-essential sentence
  - keep structure scan-friendly and complete
  - protect autonomy and boundary integrity
  - finish with one clear decision request
input_source: prior_thread_message
```

---

### Twenty-seven subtypes. One message.
The Farmer Five wants you to stay out of their castle unless you bring a clear purpose. The Farmer Six ("Warmth") wants the opposite and needs you to come closer, signal trustworthiness, and prove you're a reliable ally. The Hunter Seven ("Suggestibility") filters for imaginative possibility and rose-colored optimism. Same Slack message, three completely different threat assessments.

> ***Personalization determines whether your message gets read or discarded.***

The communicators who learn to match their message to each person's instinctual filter will get responses, build trust, and move work forward. Everyone else will keep wondering why smart people ignore their perfectly reasonable emails.

#### Your message is addressed to a person who doesn't exist: the generic coworker with no walls.

It's why we're building [Rally](https://www.rally.ai/), communications automatically optimized for each person's instinctual profile. See how we do it: [AI Smells Remover](./you-smell-like-bad-ai-2026-02-14.md).

---

**This is Part 13 of a 27-part series on subtype-specific communication.**

| | |
|---|---|
| Previous | [![Hunter Four: Competition](./img/thumbs/hunter-four-competition.png)](./HUNTER_FOUR_COMPETITION.md) [Hunter Four: Competition](./HUNTER_FOUR_COMPETITION.md) |
| Next | [![Teamer Five: Totem](./img/thumbs/teamer-five-totem.png)](./TEAMER_FIVE_TOTEM.md) [Teamer Five: Totem](./TEAMER_FIVE_TOTEM.md) |

[Back to series index](./README.md)
