# Prompt Pack: AI Agent Workflow for Early-Stage Pitch Decks

Use these prompts in sequence. The founder should edit the outputs at each step instead of accepting them blindly.

## Prompt 1 — Startup Context Intake

```text
Act as a startup narrative analyst.

I am an early-stage founder preparing a pitch deck.
First, read my startup notes and extract:
1. the startup's core idea
2. target customer
3. problem being solved
4. current alternatives
5. why this matters now
6. business model hypothesis
7. traction or validation evidence
8. biggest assumptions or gaps

Then return:
- a concise startup summary in plain English
- a bullet list of claims that are evidence-backed
- a bullet list of claims that are assumptions only
- a bullet list of missing information needed for a credible pitch deck

Use simple language. Do not invent facts. Mark uncertainty explicitly.

Here are my notes:
[PASTE NOTES]
```

## Prompt 2 — Narrative Strategy

```text
Act as a pitch deck strategist for a very early-stage startup.

Using the startup context below, propose 3 possible pitch narratives.
For each narrative, provide:
- the central message
- who it would resonate with
- the main risk of using that narrative

Then recommend the strongest narrative for an incubation-stage startup and explain why.

Constraints:
- keep it grounded in available evidence
- avoid hype language
- optimize for clarity and credibility

Startup context:
[PASTE CLEANED SUMMARY]
```

## Prompt 3 — Deck Outline

```text
Act as an expert startup fundraising coach.

Create a 10-12 slide pitch deck outline for the startup below.

For each slide include:
- slide title
- purpose of the slide
- 3 to 5 bullet points with suggested content
- what evidence would strengthen the slide

Use this structure unless a better structure is justified:
1. Title
2. Problem
3. Customer / market context
4. Solution
5. Product
6. Business model
7. Traction / validation
8. Competition / alternatives
9. Go-to-market
10. Team
11. Roadmap / milestones
12. Ask

Rules:
- do not invent metrics
- note when evidence is weak
- prefer specificity over polished generic language
- write for early-stage investors or mentors

Startup context:
[PASTE CLEANED SUMMARY]
```

## Prompt 4 — Skeptical Investor Review

```text
Act as a skeptical early-stage investor reviewing this deck outline.

For each slide:
- identify what is unclear, weak, generic, unsupported, or risky
- list the toughest question an investor would ask

Then provide:
- the 3 slides most in need of improvement
- the missing evidence that matters most
- the top 5 objections to this startup story overall

Be direct and specific. Do not soften the critique.

Deck outline:
[PASTE OUTLINE]
```

## Prompt 5 — Rewrite Weak Slides

```text
Act as a pitch deck editor.

I will give you 3 weak slides from my outline plus the investor critique.
Rewrite each slide to be:
- clearer
- more specific
- more evidence-driven
- better suited for an incubation-stage startup

For each rewritten slide, provide:
- revised title
- revised bullets
- one sentence explaining what changed
- one sentence describing what proof is still missing

Do not fabricate evidence.

Startup context:
[PASTE CLEANED SUMMARY]

Weak slides and critique:
[PASTE MATERIAL]
```

## Prompt 6 — Convert Outline Into Slide Copy

```text
Act as a concise startup slide writer.

Turn this pitch deck outline into first-draft slide copy.

Constraints:
- each slide should be concise
- keep the language plain and investor-friendly
- avoid buzzwords
- do not exceed 40 words per slide unless necessary
- if a slide lacks evidence, write a placeholder note in brackets

Output format:
- Slide number
- Slide title
- Slide copy

Outline:
[PASTE REVISED OUTLINE]
```

## Prompt 7 — Design Brief for Presentation Tool

```text
Act as a presentation design brief writer.

Based on this pitch deck, create a design brief for building the slides in a presentation tool.

Include:
- overall tone
- visual style
- recommended slide density
- where charts or product screenshots should be used
- where a simple diagram would work better than text
- 3 design mistakes to avoid

Do not redesign the business narrative. Focus only on presentation quality.

Deck content:
[PASTE DECK COPY]
```

## Prompt 8 — Final Pre-Flight Check

```text
Act as a final reviewer before this deck is shown to mentors or investors.

Review the deck and provide:
1. the top strengths
2. the top weaknesses
3. any slide that sounds generic
4. any claim that needs proof
5. any section that feels out of order
6. a final pass recommendation:
   - ready for review
   - needs one more revision
   - not ready

Keep the review concise and practical.

Deck:
[PASTE DECK COPY]
```

## Fast Version for Founders Short on Time

```text
Act as a startup pitch deck agent.

Using my notes, do the following in order:
1. summarize the startup
2. identify missing information
3. propose the strongest pitch narrative
4. create a 10-12 slide deck outline
5. critique the outline like a skeptical investor
6. rewrite the 3 weakest slides

Rules:
- do not invent facts
- mark assumptions clearly
- prefer clarity over polish
- write for an early-stage incubation audience

My notes:
[PASTE NOTES]
```

## Facilitator Exercise Prompt

```text
Act as a workshop assistant for early-stage founders.

A participant has limited startup notes and needs help creating a first pitch deck outline.

Your job:
- extract the most important facts
- identify missing pieces without being discouraging
- create a practical 10-slide outline
- flag the 3 slides that most need founder evidence

Use plain language suitable for founders with mixed business experience.
Do not invent information.

Participant notes:
[PASTE NOTES]
```
