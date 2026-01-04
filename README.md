# MetaPrompts

A collection of advanced meta-prompts designed to generate, optimize, and evaluate other prompts. These prompts are crafted to enhance agentic behaviors, structured output, and reasoning capabilities in Large Language Models.

## 📂 Prompt Collection

### ⚙️ The Generator
*Prompts focused on creating high-quality, agentic, and structured outputs.*

| Prompt Name | Version | Description |
|-------------|:-------:|-------------|
| **[Agentic Prompt Generator](prompts/agentic-prompt-generator_v5.md)** | v5 | Generates prompts for agentic, tool-using, and methodically-reflective LLMs. |
| **[Chain of Thought (CoT) Generator](prompts/chain-of-thought-cot-prompt-generator_v1.md)** | v1 | Designs prompts that encourage step-by-step reasoning and logic. |
| **[C.R.I.S.P.E. Prompt Generator](prompts/c-r-i-s-p-e-prompt-generator_v2.md)** | v2 | Framework for Capacity, Role, Insight, Statement, Personality, and Experiment. |
| **[Few-Shot Data Synthesizer](prompts/few-shot-data-synthesizer_v1.md)** | v1 | Generates synthetic data examples for few-shot learning and context. |

### 🏗️ The Blueprint
*Frameworks and structures for defining comprehensive and robust prompts.*

| Prompt Name | Version | Description |
|-------------|:-------:|-------------|
| **[C.O.S.T.A.R. Prompt Generator](prompts/c-o-s-t-a-r-prompt-generator_v2.md)** | v2 | Creates structured prompts using the Context, Objective, Style, Tone, Audience, Response framework. |
| **[C.R.A.F.T. Prompt Generator](prompts/c-r-a-f-t-prompt-generator_v4.md)** | v4 | Sophisticated prompt generation using the CRAFT methodology for high-quality interactions. |
| **[Deep Research Prompt Generator](prompts/deep-research-prompt-generator_v6.md)** | v6 | Specialized for conducting deep, multi-step research tasks. |
| **[S.C.O.P.E. Prompt Generator](prompts/s-c-o-p-e-prompt-generator_v2.md)** | v2 | Scope, Context, Origin, Purpose, Audience framework generator. |

### 💎 The Refinery
*Tools for optimizing, evaluating, and refining existing prompts.*

| Prompt Name | Version | Description |
|-------------|:-------:|-------------|
| **[AI Mistake Detection & Classification](prompts/ai-mistake-detection-classification_v4.md)** | v4 | Detects and classifies errors in AI outputs to improve reliability. |
| **[Dynamic Variable Optimizer](prompts/generalize-and-optimize-structured-prompts-with-dynamic-variables_v2.md)** | v2 | Generalizes and optimizes structured prompts using dynamic variables for reusability. |
| **[Prompt Compressor & Token Optimizer](prompts/prompt-compressor-token-optimizer_v1.md)** | v1 | Compresses prompts to save tokens while maintaining core intent and instructions. |
| **[Prompt Evaluator](prompts/prompt-evaluator_v4.md)** | v4 | Critiques and scores prompts to identify weaknesses and areas for improvement. |
| **[R.T.F. Prompt Generator](prompts/r-t-f-prompt-generator_v2.md)** | v2 | Role, Task, Format framework for simple yet effective prompt structure. |

### 🔧 Utilities
*Helper prompts for format conversion and other utility tasks.*

| Prompt Name | Version | Description |
|-------------|:-------:|-------------|
| **[Template Converter (JSON/Jinja2)](prompts/template-conversion-to-json-or-jinja2_v2.md)** | v2 | Converts natural language prompts into structured JSON or Jinja2 templates. |

## � PromptHive import

This repository also contains a full import of the prompt collection in JSON format, ready for import into [PromptHive](https://github.com/jovd83/prompthive).

*   **File:** [`prompthiveJson/meta_prompts.json`](prompthiveJson/meta_prompts.json)
*   **Usage:** You can import this file directly into your PromptHive instance to restore or duplicate the entire "Meta Prompts" collection with all its metadata, tags, and structure preserved.

## �🚀 Usage

Select a prompt from the collection above to help you design, refine, or analyze your own LLM interactions. Each file contains detailed instructions and context settings.

## 🤝 Contribution

Feel free to browse, use, and adapt these prompts for your own projects.
