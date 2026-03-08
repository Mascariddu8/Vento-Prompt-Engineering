# The 'First Principles' Ideation Engine

**Category:** exploration  
**Recommended model:** Claude 3.5 Sonnet / o1-preview / GPT-4o  
**Author:** @Mascariddu8  
**Last updated:** 2026-03-06

## Description
A deep-thinking prompt designed to break down a stagnant industry or complex problem into its fundamental, undeniable truths, and then rebuild innovative solutions from scratch, circumventing analogical thinking.

## Prompt

```text
You are an expert in first principles thinking, possessing the analytical rigor of Elon Musk and the creative problem-solving of Richard Feynman.

I want to disrupt or deeply innovate in the following area/industry:
[INDUSTRY_OR_PROBLEM]

Please walk me through a rigorous First Principles analysis:

**Phase 1: Deconstruction**
Identify the fundamental assumptions, accepted "truths," and dogmas in this industry. Strip away all analogies, traditions, and "how things are currently done." Break the problem down into the absolute bedrock physical, economical, or human behavioral truths that cannot be debated. List 5-7 fundamental truths.

**Phase 2: Questioning Constraints**
Take the standard practices in this industry and subject them to extreme stress testing. For every "we have to do X because Y," ask "Why?" up to 5 times. Identify which bottlenecks are actually laws of physics/nature, and which are merely legacy human conventions or outdated regulations.

**Phase 3: Reconstruction**
Starting ONLY from the bedrock truths identified in Phase 1, build 3 completely novel, potentially radical approaches to solving the core customer need. Do not reference existing competitors. Do not use analogies. Design the system from the ground up to be 10x better, faster, or cheaper.

Use a structured, highly analytical tone. Be concise but deep.
```

## Variables
- `[INDUSTRY_OR_PROBLEM]` — The space you want to analyze (e.g., "The commercial real estate leasing market", "Last-mile grocery delivery").

## Example output
*(Generates a profound teardown of industry norms, separating fundamental constraints from artificial dogmas).*

## Notes
- Works exceptionally well with models capable of deep reasoning (like o1 or Claude Sonnet). 
- Best used in the very early stages of startup ideation.
