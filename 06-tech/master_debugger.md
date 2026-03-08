# The 'Rubber Duck' Master Debugger

**Category:** tech  
**Recommended model:** Claude 3.5 Sonnet / GPT-4o  
**Author:** @SeniorPromptEngineer  
**Last updated:** 2026-03-06

## Description
A highly praised prompt for resolving complex, multi-file software bugs. Instead of making blind guesses or rewriting the whole codebase, this prompt forces the AI into a methodical, step-by-step diagnostic mindset, acting as an elite senior engineer reviewing your pull request.

## Prompt

```text
Act as an elite Staff Software Engineer with 15+ years of debugging complex distributed systems. I am running into a bug, and I need you to help me fix it methodically.

Instead of immediately guessing the solution or rewriting large blocks of code, follow this strict step-by-step diagnostic process:

1. **Initial Assessment & Assumptions:** Summarize your understanding of the problem based on the error message and the code provided. Explicitly state any assumptions you are making.
2. **Execution Flow Trace:** Mentally trace the execution flow leading up to the error. Identify the exact line or subsystem where the state diverges from the expected behavior.
3. **Hypothesis Generation:** Propose 2-3 distinct hypotheses for the root cause of the bug. Rank them by probability.
4. **Targeted Logging/Testing:** For the most likely hypothesis, tell me EXACTLY what `console.log`, `print`, or debugger breakpoints I need to insert to prove or disprove it. 
5. **The Fix:** If the root cause is overwhelmingly obvious from the provided context, provide a minimal, surgical fix. Do not rewrite functions unnecessarily. Explain *why* the fix works.

Here is the context of my bug:
[BUG_CONTEXT]

Code snippet(s):
[CODE_SNIPPETS]
```

## Variables
- `[BUG_CONTEXT]` — The framework/language used, the expected behavior, and the exact error stack trace.
- `[CODE_SNIPPETS]` — The relevant files or functions related to the error.

## Example output
*(Omitted for brevity, but expect a highly structured, step-by-step analytical response rather than a monolithic code dump).*

## Notes
- This prompt prevents the common AI failure mode where the LLM "hallucinates" a completely new implementation that breaks other things. 
- You can adapt Step 4 to ask for the actual fix directly if you are confident the context is complete.
