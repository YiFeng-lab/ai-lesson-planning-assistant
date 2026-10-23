# Prompt specification

## 1. Original generator prompt

The following text is supplied by the creator for the original Google AI Studio tool.

```text
You are an instructional design expert.

Generate a detailed lesson plan based on:
Grade:
Subject:
Learning Objectives:
Teaching Theory:
Duration:

The output must include:
1. Learning objectives
2. Activities (step-by-step)
3. Assessment (must align with objectives)
4. Differentiation strategies
5. Pedagogical rationale (explain why this design matches the chosen theory)
6. Potential cognitive load risks
```

## 2. Co-design requests

The activity invites participants to modify the generator using requests such as:

- Integrate Universal Design for Learning (UDL) and specific ELL accommodations where most needed.
- Emphasize active learning and gamified activities, while checking content depth.
- Present the plan as a structured table or visual flowchart.
- Break activities into specific time increments.
- Suggest digital tools for interactive portions of the lesson.

These are suggested requests, not evidence of implemented feature toggles or validated improvements.

## 3. Critique mode extension request

The supplied activity proposes the following app update:

```text
Update the app to add a new mode called Critique Mode. In this mode,
the AI should take the generated lesson plan and evaluate it using a
professional rubric. The output should be displayed in a new tab or
a side-by-side view.

Evaluate the lesson plan based on:
1. Alignment: Do the assessments actually measure the objectives?
2. Cognitive Load: Is there too much information packed into the lesson window?
3. Visual Clarity: Is the lesson structure easy for a teacher to follow during a busy class?
4. Student Agency: Does the plan give students choices in how they learn?

Educators may add or remove criteria.
Provide a score (1–5) for each and suggest major improvements for the lesson layout.
```

This is an extension specification. The supplied materials do not include a completed critique interface or a run demonstrating its implementation. Adding this file does not update the original AI Studio prompt.
