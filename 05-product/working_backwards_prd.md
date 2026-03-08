# The 'Working Backwards' Product Spec

**Category:** product  
**Recommended model:** Claude 3.5 Sonnet / GPT-4o / Gemini 1.5 Pro  
**Author:** @SeniorPromptEngineer  
**Last updated:** 2026-03-06

## Description
Inspired by Amazon's famous "Working Backwards" methodology, this prompt helps product managers draft a reverse-engineered PRD starting from the press release and FAQ, ensuring the product is fundamentally user-centric before any engineering begins.

## Prompt

```text
Act as a Principal Product Manager at a top-tier tech company. We are ideating a new product/feature called [PRODUCT_NAME].

Your task is to write a "Working Backwards" document to define this product from the customer's perspective. The document must include strictly these components:

1. **The Press Release (PR):** Write a compelling, 1-page press release announcing the completed product. It must include:
   - Heading: Name the product in a way the reader will understand.
   - Sub-heading: A one-sentence summary of the market and target customer.
   - Date & Location.
   - Summary: A summary of the product and the benefit.
   - Problem: The problem the product solves.
   - Solution: How the product elegantly solves the problem.
   - Executive Quote: A quote from a spokesperson in our company.
   - Customer Quote: A quote from a hypothetical customer experiencing the benefit.
   - Call to Action: How to get started.

2. **The FAQ (External):** Write 5 tough questions a skeptical customer or tech journalist would ask upon reading the PR, along with our transparent answers.

3. **The FAQ (Internal):** Write 5 tough questions our internal engineering, legal, or finance teams would ask about feasibility, costs, and risks, along with our strategic answers.

Here is the raw context and idea for the product:
[PRODUCT_IDEA_CONTEXT]
```

## Variables
- `[PRODUCT_NAME]` — The working title of the feature or product.
- `[PRODUCT_IDEA_CONTEXT]` — The core concept, target audience, and primary value proposition.

## Example output
*(Will generate a highly polished, Amazon-style 2-page document).*

## Notes
- It is highly recommended to run this prompt first *before* writing any technical user stories or Jira tickets.
- The "Internal FAQ" section often highlights unseen regulatory or technical risks.
