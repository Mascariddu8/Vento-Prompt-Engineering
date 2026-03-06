# 🧠 Vento Prompt Library

A shared collection of tested, reusable prompts to support teams throughout each phase.

---

## 📁 Repository Structure

```
vento-prompt-library/
├── README.md
├── CONTRIBUTING.md
│
├── 01-exploration/         # Idea generation, opportunity scouting, trend analysis
├── 02-market/              # Market sizing, competitor analysis, landscape mapping
├── 03-validation/          # Hypothesis testing, customer discovery, interview synthesis
├── 04-strategy/            # Positioning, go-to-market, business model design
├── 05-product/             # PRD, user stories, roadmap, UX feedback
├── 06-tech/                # Architecture, code review, debugging, documentation
├── 07-marketing/           # Copy, content, SEO, social media, branding
├── 08-fundraising/         # Pitch deck, investor memo, Q&A prep, term sheet review
├── 09-legal/               # Contract review, NDA, compliance, regulatory research
├── 10-finance/             # Financial modeling, unit economics, projections
└── 11-operations/          # SOPs, hiring, reporting, email templates
```

Each folder contains `.md` files, one per prompt or per closely related prompt group.

---

## 📝 Prompt Format

Every file follows this template:

```markdown
# [Prompt Name]

**Category:** exploration / market / validation / ...  
**Recommended model:** Claude / GPT-4 / Gemini / any  
**Author:** @name  
**Last updated:** YYYY-MM-DD

## Description
A short explanation of what this prompt does and when to use it.

## Prompt

```
[Paste the full prompt here]
```

## Variables
- `[VARIABLE_1]` — description
- `[VARIABLE_2]` — description

## Example output
(Optional) A sample response or screenshot.

## Notes
Tips, variants, known limitations.
```
---

## 🔍 How to Find a Prompt

- **Browse by folder** if you already know the category
- Use **GitHub Search** (`t` to open the file finder, or search within code)
- Check the [Prompt Index](#prompt-index) below

---

## 📋 Prompt Index

> Maintained manually — add your row when you open a PR.

| Name | Category | Description | Author |
|------|----------|-------------|--------|
| _(example)_ Pain Point Extractor | validation | Extracts pain points from interview transcripts | @andrea |
| _(example)_ Market Sizing Model | market | Generates a TAM/SAM/SOM breakdown from a brief | @name |

---
