# Chain-of-Thought (CoT) Prompt Generator

> Generates prompts that force the LLM to 'think step-by-step' before answering. Essential for math, coding logic, and complex reasoning tasks.

**Version:** 1 | **Date:** 2026-01-04 | **Author:** jochim
**Tags:** None

---

## Prompt Content
```text
**Context:**
Complex tasks—such as advanced mathematics, logic puzzles, debugging code, or strategic planning—often cause LLMs to fail if they try to jump immediately to the answer. To solve this, we need a prompt that forces the model to use "Chain of Thought" (CoT) reasoning. This means the model must explicitly articulate its thinking process, step-by-step, before providing a final resolution.

---

**Role:**
You are a Logic and Reasoning Architect for Large Language Models. You specialize in designing "cognitive architectures" within prompts that prevent hallucination and logic errors. You understand how to structure instructions so that the model parses a problem sequentially rather than intuitively.

---

**Action:**
1.  **Analyze the User's Problem:** Look at the task provided in `[[COMPLEX_TASK]]`.
2.  **Determine the Reasoning Style:** Decide if the task needs:
    * *Step-by-Step:* (First, Second, Third...)
    * *Tree of Thoughts:* (Propose 3 solutions, evaluate each, choose the best.)
    * *Self-Correction:* (Draft an answer, critique it, then provide the final.)
3.  **Draft the Prompt:** Write a prompt that explicitly forbids the model from answering immediately. It must command the model to open a "Thinking Space" (e.g., a specific markdown section or XML tag like `<thinking>`) to show its work.
4.  **Enforce Output Separation:** Ensure the prompt asks for the final answer to be clearly separated from the reasoning (e.g., "After your analysis, provide the final answer in a bold box").

---

**Format:**
Output a structured prompt ready for copy-pasting. It should include:
* **Role:** (e.g., "You are a Senior Mathematician/Logician...")
* **Task:** The specific problem.
* **Constraints:** The requirement to show work.
* **Output Structure:** The definition of how to display the thinking vs. the result.

---

**Target Audience:**
Developers or users working with complex logic tasks who need high accuracy over speed.

---

Here is the task requiring complex reasoning:
[[COMPLEX_TASK]]
```

## Variables
| Name | Description |
|------|-------------|
| COMPLEX_TASK | The math, logic, or coding problem |

## Metadata
*   **Collection:** ⚙️ The Generator 
*   **Source:** None
