# Beyond the Prompt

**AI Lesson Planning Assistant · Human–AI co-design · Instructional quality review**

[Product case →](https://yifeng-lab.github.io/ai-lesson-planning-assistant/) · [Original Google AI Studio prompt →](https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%221Ph5oAo6cwEP6zrWP4niHhGKdZ2pJPBYE%22%5D,%22action%22:%22open%22,%22userId%22:%22110854234933948759033%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing)

## Product goal

Help Grade 6–12 teachers develop lesson drafts while retaining control over pedagogical priorities, classroom feasibility and quality review.

The project combines a structured generation prompt with a co-design activity and a proposed critique-mode extension.

## My contribution

- Created the original “Instructional Design Expert” tool using Google AI Studio.
- Defined five input fields and six requested output sections, including aligned assessment, differentiation, pedagogical rationale and cognitive load risks.
- Designed a hands-on co-design activity that lets educators prioritize inclusion, engagement, structure, timing and technology integration.
- Specified a complementary critique-mode workflow with four initial rubric dimensions, 1–5 scores and revision suggestions.
- Built teacher reflection into the activity to question generic outputs, unrealistic classroom suggestions and uncritical trust in AI scores.

## Workflow and implementation status

| Component | What the supplied materials establish |
| --- | --- |
| Original generator | Creator-provided original prompt and AI Studio link. Live access has not been verified. |
| Co-design activity | Five example refinement directions and discussion questions. No session results supplied. |
| Critique Mode | Extension request for a new tab or side-by-side review. Completed implementation is not demonstrated. |
| Evaluation | Proposed verification plan in this repository. No completed benchmark or impact metrics. |

## Files

| File | Purpose |
| --- | --- |
| [PROMPTS.md](PROMPTS.md) | Original generator prompt, co-design requests and critique extension specification |
| [ACTIVITY.md](ACTIVITY.md) | Facilitated co-design activity and teacher reflection questions |
| [EVALUATION.md](EVALUATION.md) | Proposed quality and workflow checks |
| [index.html](index.html) | Static product-case page |

## Technology and attribution

Original tool: Yi Feng, Google AI Studio. The supplied materials identify the model as **Gemini 3 Flash Preview**; the current model setting has not been inspected.

This repository hosts a static case study and documentation. It does not run a model, recreate the original AI Studio tool or provide a working Critique Mode. AI Studio access may require Google sign-in and sharing permission. No API keys or account credentials are included.

## Evidence boundaries

No generated lesson samples, implementation source, teacher trial results or measured preparation-time gains were supplied. The four initial critique dimensions do not yet have validated scoring anchors. Do not treat AI-generated scores as verified teaching quality.

To view locally, open `index.html`. No build step is required.
