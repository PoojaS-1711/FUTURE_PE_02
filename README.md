# AI-Powered UGC Ad Content Generator 🤖🎬

**By:** PoojaS-1711

**Internship:** Future Interns — Prompt Engineering Track

**Tool Used:** Claude (Anthropic)

---

## What This Project Is

This repository contains a reusable AI prompt system that generates high-converting UGC (User Generated Content) style ad scripts for beauty and consumer brands.

UGC ads work because they feel real — like an honest customer review, not a polished commercial. This system uses structured prompts to produce that authentic tone at scale.

---

## Business Case Study

| Field | Details |
|---|---|
| Brand | Lakmē India |
| Product | Be-jewel Multichrome Eyeshadow |
| Problem Solved | Eyeshadow that creases and fades during long workdays — forcing constant touch-ups |
| Target Audience | Working women and brides-to-be |
| Platform | Instagram Reels |
| Ad Framework | Hook → Problem → Solution → Proof → CTA |

---

## What the System Generates

One prompt run produces a complete UGC Content Pack:

| Output | Description |
|---|---|
| 3 Hooks | Three different angles — Fear, Curiosity, Direct Benefit |
| 45-second video script | Full scene-by-scene breakdown with visuals, audio, and text-on-screen |
| 2 CTAs | One urgency-based, one benefit-driven |
| 2 Instagram Captions | One punchy, one story-driven, both with hashtags |

---

## Repository Structure

```
FUTURE_PE_02/
├── README.md
├── prompts/
│   └── ugc_master_prompt.md       — Reusable prompt framework
└── generated-campaigns/
    └── lakme_bejewel_campaign.md  — Full generated UGC content pack
```

---

## How to Use This for Any Product

1. Open `prompts/ugc_master_prompt.md`
2. Fill in the 6 input variables at the top
3. Paste the full prompt into Claude (claude.ai)
4. Copy the output into your content calendar, brief your creator, or post directly

The prompt is reusable for any beauty product, D2C brand, or local business.

---

## Prompt Logic — Why It Works

**1. Role assignment:** The prompt tells Claude it is a UGC creator, not a brand copywriter. This shifts the output from polished ad language to conversational, authentic script writing.

**2. Tone rules:** Specific phrases and speaking patterns are defined so the script sounds like a real person, not an AI.

**3. Verified claims only:** The prompt explicitly instructs the system to use only claims from the official product page. This prevents false advertising and keeps the content legally safe.

**4. Framework enforcement:** The Hook → Problem → Solution → Proof → CTA structure is baked into the prompt so every output follows proven ad conversion logic.

**5. Three hook angles:** Each run generates a Fear hook (best for reach), a Curiosity hook (best for saves), and a Direct Benefit hook (best for conversions) — giving the creator options to A/B test.

---

## Key Learnings

- UGC that sounds like an ad fails. The tone has to feel like a real person's genuine reaction.
- Unverified product claims are a legal risk — always ground scripts in what the brand actually says.
- Three different hook angles serve three different algorithm behaviors on Instagram — reach, saves, and conversions are not the same goal.
- The problem statement in the script matters more than the product features. Lead with frustration, not specs.

---

## Tool Used

**Claude by Anthropic** — claude.ai

No paid API. No coding. Structured prompt run in the Claude chat interface.

---

*This project was completed as part of the Future Interns Prompt Engineering Virtual Internship Program.*
