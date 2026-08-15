# Build, validation, and portfolio guide

Use this guide after a problem and solution direction have evidence.

## Hypothesis format

`When [specific user] encounters [specific situation], providing [intervention] will change [observable behavior/outcome] from [baseline] to [threshold], because [mechanism].`

Name the riskiest assumption and a result that would disconfirm it.

## Match the test to the uncertainty

| Uncertainty | Cheapest useful test |
|---|---|
| Can the user understand the workflow? | Paper or clickable prototype |
| Will they provide the needed input? | Landing interaction or manual task test |
| Is the output valuable? | Concierge or Wizard-of-Oz result |
| Can AI perform the narrow task? | Representative offline evaluation set |
| Does it work in context? | Thin end-to-end prototype in a real occurrence |
| Will use continue? | Repeated voluntary use across occurrences |

## MVP boundaries

Include only:

- one primary user
- one trigger
- one end-to-end job
- the minimum inputs
- one useful output
- correction or confirmation
- basic failure handling
- measurement needed for the hypothesis

Defer multi-role administration, broad customization, growth features, and polish unless they are required to test the core assumption.

## Acceptance criteria

Write observable criteria for:

- successful main journey
- missing or malformed input
- low-confidence or unsafe AI output
- user correction
- data handling
- latency and cost boundary
- result logging

## Evaluation set

Build a small but representative set from anonymized real cases when permission allows. Include normal, edge, ambiguous, and failure-prone examples. Keep evaluation cases separate from prompt examples when possible.

Report sample size, collection method, scoring rule, baseline, result, and limitations. Do not generalize beyond the tested context.

## Portfolio evidence checklist

Capture along the way:

- anonymized interview or observation notes
- workflow map
- evidence table and discarded hypotheses
- alternative solutions comparison
- AI suitability and risk decision
- prototype versions
- test plan and evaluation cases
- result table and failure examples
- iteration decisions
- demo and screenshots
- personal reflection on what changed your mind

## Case-study outline

1. Context and access
2. Research question and method
3. Evidence from the real workflow
4. Problem selection and alternatives
5. Why AI, why assistive AI, or why no AI
6. MVP hypothesis and scope
7. Product flow and technical architecture
8. Evaluation and observed use
9. Failures and iteration
10. Outcome, limitations, and next experiment

Make the user’s contribution explicit. Avoid inflated market claims, invented business impact, or labels such as “production-ready” without corresponding evidence.
