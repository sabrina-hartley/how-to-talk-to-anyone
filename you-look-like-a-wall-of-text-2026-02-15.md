# You Look Like a Wall of Text

## Every word in your email was correct, and nobody read past the second line.

Dana spent thirty minutes writing a project update. Clear language, accurate details, solid reasoning. She covered the timeline change, the budget impact, the three decisions the team needed to make, and the context behind each one. She sent it to twelve people.

Two replied. One asked a question she'd already answered in paragraph four. The other forwarded it to their manager with the note: "TL;DR?" Dana's writing was fine. Her formatting made the entire message invisible.

The next week, she sent the same information with bold deadlines, a numbered decision list, and section headers. Eleven out of twelve replied within the hour. The words were identical. The structure changed everything.

### Why formatting is the cheapest fix in workplace communication

Nielsen Norman Group's eye-tracking research found that users scan content in an F-shaped pattern: they read the first line, skim the left edge of what follows, and abandon the rest. Making content scannable improved measured usability by [47%](https://www.nngroup.com/articles/concise-scannable-and-objective-how-to-write-for-the-web/). Combined with concise writing, that number hit 124%.

Most workplace emails ignore this entirely. They arrive as undifferentiated paragraphs where every sentence carries the same visual weight. The deadline sits in the same font as the background context. The action item blends into the rationale. Recipients have three seconds of attention and zero visual cues telling them where to spend it.

The fix requires no rewriting. You can take any email you've already drafted, apply eight formatting rules, and double the chance it gets read and acted on. Same words, different structure, completely different outcome.

Here are 8 rules that turn a wall of text into a message people actually use:

1. **Bold the one thing they must see.** The deadline, the ask, or the decision. One bolded phrase per section maximum. When you bold everything, you bold nothing, because the visual contrast that makes bold work disappears when the entire paragraph is heavy.

2. **Italic for context they can skip.** Background information, caveats, and "nice to know" details belong in italics. This signals "read this if you have time" without cluttering the primary message. Readers who need the context will read it; readers who already have it will skip to the next bold phrase.

3. **Reserve underline for links only.** Online readers have spent two decades learning that underlined text is clickable. Using underline for emphasis trains recipients to click on text that goes nowhere. It creates a micro-frustration that erodes trust in your formatting.

4. **Add headings when your email scrolls.** If the message extends past one screen, it needs section headers. Mobile recipients see three to four lines at a time. Headers let them jump to the section that matters to them and skip the sections that don't. An email with headers is a document. An email without them is a stream-of-consciousness.

5. **Bullet lists for parallel items, numbered lists for sequences.** Three or more items of the same type should become a list. Numbered when order matters (steps, ranked priorities, sequential dependencies). Bulleted when it doesn't (options, attendees, features). Prose that hides a list inside a paragraph forces readers to extract the structure themselves.

6. **One idea per paragraph, three sentences maximum.** Each paragraph earns its whitespace by containing exactly one point. If you need a fourth sentence, start a new paragraph. Short paragraphs create natural scanning points. Long paragraphs create walls.

7. **Front-load the ask.** The first line of the email should contain the action or decision needed. Everything after it is supporting context. Most people write emails like essays: background, reasoning, then the point. Flip it. Conclusion first, evidence second, background last.

8. **Whitespace is formatting.** A blank line between sections costs nothing and changes how the entire message feels. Dense blocks of text signal "this will take effort to parse" before a single word is read. Whitespace tells the reader "this is organized, and you can move through it quickly."

### Before and After

**Before** (wall of text):

> Hi team, I wanted to give a quick update on the Henderson project. We've hit a delay on the vendor integration due to an API change on their end, which means the original March 15 deadline is no longer realistic. After reviewing the scope with engineering, we think March 29 is achievable if we can get sign-off on the revised SOW by this Friday. The budget impact is minimal, roughly $4,200 in additional QA hours, which fits within our contingency. I need three things from this group: (1) confirmation that the March 29 date works for the client presentation, (2) approval on the $4,200 overage, and (3) someone to own the client communication about the timeline shift. Let me know your thoughts when you get a chance.

**After** (same words, formatted):

> Hi team,
>
> Quick update on the Henderson project.
>
> **The March 15 deadline is moving to March 29** due to an API change on the vendor integration side. Engineering reviewed the scope and confirmed March 29 is achievable if we get sign-off on the revised SOW by **this Friday**.
>
> *Budget impact: ~$4,200 in additional QA hours, within our existing contingency.*
>
> **I need three decisions from this group:**
>
> 1. Does March 29 work for the client presentation?
> 2. Is the $4,200 overage approved?
> 3. Who owns the client communication about the timeline shift?
>
> Please reply by EOD Thursday.

Same information. Same word count. The formatted version gets replies because readers can find the deadline in one second, skip the budget context if they already trust the number, and see exactly what they need to decide.

> ***Formatting is free, and it's the fastest way to double the effectiveness of every email you send.***

---

### Try it out: FREE Email Formatting Optimizer Prompt

Paste your draft email into your LLM, then paste the following prompt after it. The model will reformat your message for maximum scanability without changing a single word.

```
mode: post_generation_reprompt
task: "Use the immediately preceding draft in this thread as input and reformat it for maximum scanability while preserving every original word."
goal: "Output must be the exact same content reorganized with strategic formatting: bold, italic, headings, lists, whitespace, and paragraph breaks."
stance: "Format only. Zero rewriting. Every word in the output must appear in the input."
output_rules[6]:
  - return only the reformatted draft
  - no preface no framing and no wrap-up
  - no headings like Reformatted Version or Final Draft
  - no explanations or notes about what was changed
  - preserve every original word and phrase exactly
  - do not add remove or rephrase any content
non_negotiables[5]:
  - never add words that were not in the original
  - never remove words that were in the original
  - never rephrase or reword any sentence
  - never change tone emphasis or meaning through word choice
  - formatting changes only: bold italic headings lists whitespace paragraph breaks
format_rules[8]{id,name,when,how}:
  1,bold_the_ask,deadlines actions or decisions that require reader response,wrap the key phrase in bold markers
  2,italic_for_context,background info caveats or supporting detail readers may already know,wrap the contextual phrase or sentence in italic markers
  3,no_underline_emphasis,underline is used for emphasis instead of links,remove underline emphasis and use bold or italic instead
  4,add_headings,email extends beyond one screen or contains distinct topic sections,insert a short descriptive heading before each section
  5,convert_to_lists,three or more parallel items are embedded in a prose paragraph,extract into a bulleted list or numbered list if order matters
  6,paragraph_breaks,a paragraph contains more than one distinct idea or exceeds three sentences,split into separate paragraphs with one idea each
  7,front_load_the_ask,the action or decision needed appears after background context,move the ask to the first line and push context below it
  8,add_whitespace,sections run together with no visual separation,insert blank lines between sections and before lists
reformat_process[5]:
  - scan the draft for the primary ask and key deadlines
  - identify sections that serve different purposes: ask vs context vs detail
  - apply format_rules in priority order: front_load first then bold then lists then headings then whitespace
  - verify every original word still appears in the output
  - verify no new words were introduced
quality_gate[6]:
  - every word in the output must exist in the input
  - no word in the input may be missing from the output
  - bold is used on at most two phrases per section
  - italic is used only for skippable context not for emphasis
  - lists contain only items that were already parallel in the prose
  - formatting changes must improve scanability without altering meaning
few_shot_examples[3]{id,in,out}:
  s1,"I need the Q3 report finalized by Friday. The data is in the shared drive and Sarah has the latest client numbers.","**I need the Q3 report finalized by Friday.** *The data is in the shared drive and Sarah has the latest client numbers.*"
  s2,"We should switch vendors for three reasons: cost is 30% lower, onboarding takes two days instead of two weeks, and their API matches our current stack.","We should switch vendors for three reasons:\n\n1. Cost is 30% lower\n2. Onboarding takes two days instead of two weeks\n3. Their API matches our current stack"
  s3,"Hi team, quick update on the redesign. The homepage wireframes are approved. We still need sign-off on the mobile nav from product. Design will start the component library Monday. Please review the attached mockups before then.","Hi team, quick update on the redesign.\n\nThe homepage wireframes are approved. We still need **sign-off on the mobile nav from product.**\n\nDesign will start the component library Monday. **Please review the attached mockups before then.**"
input_source: prior_thread_message
```

That's all it takes. Same words, better structure, more replies. The people who format their emails well will always get faster responses, clearer decisions, and fewer "can you resend that?" follow-ups. The ones who send walls of text will keep wondering why nobody reads past the second line.

#### Your email was fine. Your formatting made it invisible.

It's why we're building [Rally](https://www.rally.ai/), communications optimized for employee engagement. Now that you know how to format for scanability, fix what your AI writes: [You Smell Like Bad AI](./you-smell-like-bad-ai-2026-02-14.md). Then fix who you write for: [How to Talk to Anyone](./README.md).

---

**Sources**

- Nielsen Norman Group, "[Concise, SCANNABLE, and Objective: How to Write for the Web](https://www.nngroup.com/articles/concise-scannable-and-objective-how-to-write-for-the-web/)." Found scannable formatting improved usability 47%; combined with concise writing, 124%.
- Nielsen Norman Group, "[F-Shaped Pattern For Reading Web Content](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content-discovered/)." Eye-tracking research on how users scan content.
- Nielsen Norman Group, "[5 Formatting Techniques for Long-Form Content](https://www.nngroup.com/articles/formatting-long-form-content/)." Users fixate on bolded text, headings, and bullet points when scanning.
- New Zealand Government, "[Use bold, italics, and underlining sparingly and consistently](https://www.pco.govt.nz/3.8)." Blocks of formatted text are less readable than regular text because visual contrast disappears.
