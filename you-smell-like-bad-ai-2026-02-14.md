# You Smell Like Bad AI

## Your colleagues won't say anything. They'll just start ignoring everything you send.

![2026-02-09-ai-smell-editorial-5 (1)](http://cdn.mcauto-images-production.sendgrid.net/8a6338b3baca540e/2b5e0fd1-05ed-4f60-a017-928615e079d8/2048x1143.png)

That email you pasted from ChatGPT and sent to your team? That strategy doc you prompted and dropped into the shared drive? Everyone has used these tools by now, they all know the outputs. And what you've been sending reeks of AI.

In software, Kent Beck coined the term [code smell](https://martinfowler.com/bliki/CodeSmell.html) for patterns that technically work but signal lazy engineering to anyone paying attention. Martin Fowler defined it as "a surface indication that usually corresponds to a deeper problem in the system." That same instinct now applies to workplace communications and your colleagues have cultivated a sixth sense for AI smells.

Here are 8 well-documented examples:

1. **Em-dash overuse.** Dashes used frequently to break up sentences, often in places where a comma or a period would do.

2. **Mixed metaphors.** Multiple unrelated figurative images in the same passage. "Moving the needle" and "planting seeds" in the same paragraph.

3. **Emoji.** Overuse and inserted to supply tone, warmth, or emphasis where the language itself does not carry the intended feeling.

4. **Via negativa parallels.** Defining a point by stating what it is not before stating what it is. "This is not about cost reduction. This is about strategic alignment."

5. **Verbose, structured rambling.** Prose that restates the same point in multiple ways instead of saying it once and moving on. 'Nuff said.

6. **LinkedIn staccato.** Short, line-broken sentences with dramatic spacing. Reads like a feed-style media post optimized for scrolling rather than a document written for a specific audience.

7. **Prompt-echoing.** Output that mirrors the instruction it received instead of executing on it. A section heading that says "(brief)" because the prompt asked for brevity. An opening line that says "Here is a concise summary" because the prompt asked for one. The model describes what it was told to do instead of doing it.

8. **Meta-explanation.** Passages that explain the structure or purpose of the document they appear in. A slide explaining why the deck exists. A paragraph justifying why a section was included.

And here is what most people miss:

> ***Using AI and being good at using AI are not remotely the same thing.***

Everyone in your office can prompt a model. That is not a skill anymore. That is typing. The difference between the people who use AI and the people good at using AI is that the good ones have learned to 1) recognize the patterns, 2) build prompts specifically to avoid them, and 3) edit what comes back and/or re-prompt the models.

---

### Try it out: FREE AI Smells Remover (RE)Prompt

Paste the following into your LLM after an output to get a new draft that is free of AI Smells! 

```Markdown
mode: post_generation_reprompt
task: "Use the immediately preceding draft in this thread as input and reprompt-rewrite it to remove AI smells while preserving meaning intensity persuasion and voice."
goal: "Output must read like final publish-ready copy from a sharp human editor not model-optimized text."
stance: "Pro AI mastery. The issue is low skill usage not AI itself."
output_rules[8]:
  - return only revised draft
  - no preface no framing and no wrap-up
  - no headings like Revised Draft or Final Version
  - no explanations or notes
  - "no mention of ai,prompts,rules"
  - preserve meaning and emotional force
  - "keep confident,specific,human voice"
  - do not introduce new smells while fixing old ones
non_negotiables[5]:
  - keep claims strong
  - keep energy high
  - "avoid bland/corporate/safe rewrites"
  - use concrete verbs and specific outcomes
  - keep one coherent metaphor across the full piece or switch to literal language
rewrite_process[6]:
  - treat the immediately preceding draft in this thread as first-pass model output and run a second-pass editorial reprompt
  - detect smells before rewriting
  - prioritize clarity and compression
  - remove redundancies and filler
  - replace hedging with direct assertions where accurate
  - run final smell pass then return only final copy
quality_gate[7]:
  - each sentence must earn its place
  - if removed text does not reduce understanding cut it
  - prefer concrete verbs over abstract phrasing
  - avoid instruction narration and meta framing
  - avoid dramatic line breaks unless intentional and rare
  - maintain one metaphor system or go literal
  - preserve persuasive force and specificity
smells[8]{id,name,definition,fix}:
  1,em_dash_overuse,dashes used to simulate sophistication rather than add meaning,replace dash emphasis with stronger sentence structure
  2,mixed_metaphors,incompatible figurative frames appear in the same passage,use one metaphor across paragraphs or go literal
  3,emoji_tone_substitute,symbols are used to carry tone that language should carry,remove emoji and carry warmth through wording and rhythm
  4,via_negativa_parallels,points are framed as not x but y instead of direct claims,lead with direct assertion and remove negation scaffolding
  5,verbose_structured_rambling,well organized prose spends words without reducing uncertainty,remove repeated points and triads then say it once and move on
  6,linkedin_staccato,short line broken fragments optimize for feed scanning not thought,collapse dramatic fragments into natural flow with punch
  7,prompt_echoing,text mirrors instructions instead of doing the work directly,delete instruction narration and start with content
  8,meta_explanation,text explains structure or intent instead of advancing argument,remove structure narration and use direct transitions
few_shot_examples[8]{id,in,out}:
  s1,"Work has changed — and most companies are still catching up.","Work changed under everyone's feet, and most companies are pretending it didn't."
  s2,"We're navigating a changing landscape. This lays the foundation for growth. Now teams can hit the ground running.","We're crossing rough terrain, and this clears the path so teams can move faster."
  s3,"This is a game-changer for our team! 🚀 We're so excited to roll this out 🎉","This is a game-changer for our team! We're so excited to roll this out."
  s4,"Not just an improvement. A complete transformation.","This fundamentally changes how the work gets done."
  s5,"It saves time, increases efficiency, and boosts productivity.","It cuts busywork in half."
  s6,"The future is here. It's not waiting. Neither should you.","The future arrived and it's not waiting for you to catch up."
  s7,"Here's a concise overview of the key takeaways.","Key takeaways:"
  s8,"In this section we'll outline the three key reasons why this matters for your organization.","Three reasons this matters:"
input_source: prior_thread_message
```

That's the bar now. Learn the smells, sharpen your prompting, and develop the editorial instinct to clear them from your work. The people who figure it out first will have a real advantage, and it will compound. Everyone else is trafficking at different levels of slop.

#### Nobody is going to tell you that you smell. Consider this the courtesy.

It's why we're building [Rally](https://www.rally.ai/), odor-free communications optimized for employee engagement. Now that you know how to fix how your AI writes, fix who it writes for: [How to Talk to Anyone — 27 Subtype Communication Guides](./README.md).


---

**Sources**

- Martin Fowler, "[Code Smell](https://martinfowler.com/bliki/CodeSmell.html)," martinfowler.com, 2006. Origin of the term coined by Kent Beck.
- Martin Fowler, *[Refactoring: Improving the Design of Existing Code](https://martinfowler.com/books/refactoring.html)*, 1999. The book where code smells were first cataloged.
- Northeastern University / Khoury College, "[AI slop is a common online nuisance. But what makes a piece of text 'slop'?](https://www.khoury.northeastern.edu/ai-slop-is-a-common-online-nuisance-but-what-makes-a-piece-of-text-slop/)" Research on AI text pattern frequency.
- Pham et al., "[Antislop: A Comprehensive Framework for Identifying and Eliminating Repetitive Patterns in Language Models](https://ui.adsabs.harvard.edu/abs/2025arXiv251015061P/abstract)," 2025. Found certain LLM writing patterns appear over 1,000x more frequently than in human text.
- Yenny Cheung, "[Technical Lessons Learned from Pythonic Refactoring](https://www.youtube.com/results?search_query=yenny+cheung+pycon+refactoring)," PyCon.de / Talk Python to Me #150. Discussion of code smells applied to Python.
- "[Slop Detector](https://slopdetector.org/)," slopdetector.org. Taxonomy of AI-generated content patterns.
