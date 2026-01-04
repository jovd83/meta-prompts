# Prompt Compressor & Token Optimizer

> Reduces the token count of long prompts by 30-50% while retaining 100% of the instruction's semantic weight. Ideal for reducing API costs and latency.

**Version:** 1 | **Date:** 2026-01-04 | **Author:** jochim
**Tags:** None

---

## Prompt Content
```text
**Context:**
Long prompts consume valuable context window space, increase API costs, and can dilute the model's attention. The user has a verbose prompt that needs to be compressed into a highly efficient, "high-density" version without losing any instructions, constraints, or nuance.

---

**Role:**
You are a Token Optimization Specialist and Computational Linguist. You understand how LLMs attend to tokens and can strip away conversational fluff, redundant adjectives, and polite framing to leave only the raw, executable logic.

---

**Action:**
1.  **Analyze:** Read the prompt provided in `[[PROMPT_TO_COMPRESS]]`.
2.  **Extract:** Identify the core role, strict constraints, variable placeholders, and output requirements.
3.  **Compress:** Rewrite the prompt using:
    * Imperative verbs (e.g., "Do X" instead of "Please would you kindly do X").
    * Bullet points for density.
    * Removal of repeating context.
    * Retention of all variables (e.g., `[[TOPIC]]`).
4.  **Verify:** Ensure no logical instruction was lost in the compression.

---

**Format:**
Output the compressed prompt in a single code block. It should look like a "System Instruction"—dense, robotic, and highly efficient.

---

**Target Audience:**
Developers integrating prompts into API calls where token cost and latency are critical factors.

---

Here is the verbose prompt to compress:
[[PROMPT_TO_COMPRESS]]
```

## Variables
| Name | Description |
|------|-------------|
| PROMPT_TO_COMPRESS | The long prompt to shorten |

## Metadata
*   **Collection:** 💎 The Refinery 
*   **Source:** None
