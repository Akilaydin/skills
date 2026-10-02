---
name: clear-writing
description: >
  Clear, concise, unambiguous technical writing for fast human comprehension
  and verification. Use when the user asks for clear writing, simpler technical
  prose, less ambiguity, or explicitly activates clear-writing mode.
---

# Clear Writing

Write for fast human comprehension and verification.

Simplify presentation, not reasoning. Preserve technical substance.

Inspired by УТР and ASD-STE100, without treating either standard as a strict specification.

## Language

- Follow the user's language.
- Keep established technical terms when translation would reduce precision.

## Rules

1. Put one main idea in one sentence.
2. Prefer short sentences. Aim for about 20 words when practical.
3. Use direct word order.
4. Prefer active voice.
5. State the actor when it matters.
6. Use one term for one concept. Do not rotate synonyms for style.
7. Prefer concrete verbs over abstract noun phrases.
8. Prefer simple clauses over dense participial or nested constructions.
9. Remove filler, rhetorical flourishes, metaphors, and unnecessary jargon.
10. Put a condition before the action that depends on it.
11. Use numbered lists for ordered procedures and bullets for related facts.
12. Keep each paragraph focused on one topic.

## Accuracy

Clarity has priority over brevity.

Do not remove conditions, exceptions, uncertainty, relevant caveats, numbers, units, or necessary causal links.
Do not shorten text when shortening makes it less precise.

Keep code, commands, identifiers, API names, logs, error messages, and quotations unchanged unless the user asks otherwise.

## Tone

Use clear writing as a strong default, not as rigid bureaucracy.
Keep natural connective prose where it improves readability.
Do not force simplified grammar when normal grammar is equally clear.

## Instructions

For procedures:

1. Use imperative verbs.
2. Put one action in one step.
3. State prerequisites before dependent actions.
4. State expected results when they help verification.

Prefer:

> Run `dotnet restore`. Then build the solution.

Avoid:

> The restoration of dependencies should be performed prior to carrying out the build.

## Output format

Use the simplest format that makes the result easy to understand:

- prose for straightforward explanations;
- bullets for related facts;
- numbered lists for ordered actions;
- tables for comparisons;
- diagrams only when relationships or flows are substantially clearer visually.

Do not create a richer format only for presentation.

## Boundaries

Do not apply this style to creative writing or user-requested text with a different tone.

If the user explicitly activates clear-writing mode, keep it active for the conversation until the user asks for normal writing or disables it.
