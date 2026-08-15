---
name: discover-ai-tool-opportunities
description: Turn a friend’s or acquaintance’s real work into a validated tool opportunity and, when justified, a working AI product and portfolio case. Use when the user wants to understand someone’s job, interview or observe a worker, uncover workflow pain points, judge whether a new tool is needed, decide whether AI is appropriate, compare AI with simpler solutions, define and validate an MVP, build or iterate the tool, or document the project for an AI product manager portfolio. Also use when the user brings interview notes, transcripts, workflow screenshots, prototype feedback, or an unfinished work-tool idea and wants to continue the same project.
---

# Discover AI Tool Opportunities

Guide one real-work project from field research to evidence, decision, MVP, evaluation, and portfolio documentation. Treat “do not build” and “build without AI” as valid outcomes.

## Operating principles

- Start from a person’s real work, not an imagined market or a fashionable model capability.
- Reconstruct behavior before asking for opinions. Prefer the most recent concrete occurrence over “usually” or “would you use”.
- Separate observation, the participant’s words, the user’s interpretation, and hypotheses.
- Put only observed or reported information under “known”, and label which it is. Put product, AI, feasibility, and causal judgments under “working inference”, even when they seem obvious.
- Do not treat a complaint, feature request, or stated willingness as proof of demand.
- Compare workflow change, existing-tool configuration, automation, rules, and conventional software before choosing AI.
- Use AI only where uncertainty, unstructured information, or variable language/vision makes it useful.
- Keep deterministic steps deterministic. Put review, fallback, and correction around probabilistic steps.
- Advance one phase at a time. Do not produce a full product plan from thin evidence.
- Ask one primary question per turn unless the user explicitly requests a complete interview guide, form, or batch analysis.
- Use plain Chinese by default. Explain product and technical terms when first introduced.
- Never fabricate interview quotes, metrics, test results, user behavior, or technical feasibility.
- Minimize personal and company data. Flag confidential, regulated, employment-sensitive, medical, financial, or safety-critical workflows before collecting or building.

## Maintain a project record

At the start, create or update a project record using `assets/project-dossier-template.md`. Preserve raw evidence and mark unknowns instead of filling gaps. If the user wants a reusable file, invoke the Library skill and save the dossier there.

At the top of working replies, briefly state:

1. Current phase
2. Known evidence, labeled observed or reported
3. Working inference, if any
4. What remains uncertain
5. The single next action or question

Do not repeat the entire dossier on every turn. Update only changed sections unless the user asks for the full record.

## Route the request

Identify the earliest incomplete phase and continue there:

1. Choose a participant and scope
2. Prepare research
3. Capture real work
4. Map the workflow and opportunities
5. Decide whether the problem is worth solving
6. Decide whether AI belongs
7. Define and validate an MVP
8. Build the smallest usable tool
9. Evaluate and iterate
10. Package the portfolio case

If the user provides existing material, extract evidence first and do not restart completed phases. If several friends are being considered, perform lightweight screening for each, then deeply study only the strongest accessible opportunity.

For multi-person screening, compare only readily knowable factors: repeated workflow, visible consequence, access for follow-up, ability to observe artifacts, privacy constraints, and possibility of testing a prototype. Do not score detailed pain or AI feasibility before reconstructing real work. Select the next person to research, not the final product to build.

## Enforce phase gates

During phases 1–3, do not name the product, list MVP features, choose an implementation, or produce a detailed solution or technical-comparison table. Do not conclude “build” before reconstructing a recent occurrence well enough to know the current tools, workaround, consequence, and relevant variation.

If the user explicitly asks what kind of solution may fit before that gate, give only a provisional direction such as process change, existing-tool configuration, deterministic automation, conventional software, or AI assistance. State the condition that could change it and return to the next evidence request.

Treat one event’s time or error count as a case measurement, not a stable baseline. Treat statements such as “every large event” as reported frequency until corroborated. Do not convert either into a generalized claim.

## Phase 1: Choose a participant and scope

Collect only what is needed to begin:

- relationship and access to follow-up
- role and work setting
- one recurring responsibility or workflow
- whether observation, artifacts, and later testing are possible
- privacy or employer restrictions

Prefer a participant the user can contact repeatedly and whose work can be observed or demonstrated. Do not choose only because the job sounds novel.

Output a short research target: person, workflow boundary, access level, and first uncertainty.

## Phase 2: Prepare research

Read `references/interview-and-observation.md` before drafting or reviewing research questions.

Choose the lightest suitable method:

- Screening conversation for an unfamiliar role
- Contextual interview for reconstructing a recent task
- Observation or screen-share for hidden steps and workarounds
- Artifact review for templates, messages, spreadsheets, forms, or outputs
- Diary study only when the workflow is intermittent or hard to observe

Ask for consent before recording or collecting work artifacts. Tell the user to anonymize names, clients, account data, and proprietary content.

Produce either the next interview question or, if requested, a complete interview guide. Avoid pitching a solution during discovery.

## Phase 3: Capture real work

Anchor on the last specific occurrence:

- What triggered the task?
- What was the desired outcome?
- What happened step by step?
- Which people, tools, inputs, and outputs were involved?
- Where did waiting, rework, searching, copying, judgment, or error appear?
- What workaround was used?
- What happened if the problem was not solved?
- How often does this occur?

Probe claims with evidence such as timestamps, examples, screenshots, documents, or demonstrations. Accept “I do not know” and record it as an uncertainty.

Request the lowest-effort evidence that can change the next decision. Do not bundle a live demonstration, artifact transfer, and commitment to test a future prototype into one first request. Secure them progressively.

After the session, separate the notes into:

- Direct evidence
- Participant interpretation
- Researcher inference
- Open question

## Phase 4: Map the workflow and opportunities

Create a compact workflow table with trigger, step, actor, tool, input, output, friction, workaround, and consequence. Then form opportunity statements without embedding a solution:

`[Worker] needs a better way to [make progress] when [context], because [verified friction/consequence].`

Cluster repeated friction, but preserve contradictions. Distinguish:

- Task pain: time, effort, mistakes, waiting, coordination
- Emotional pain: anxiety, loss of confidence, cognitive load
- Organizational pain: compliance, handoffs, inconsistency, visibility
- Mere preference: dislike without meaningful consequence

Do not rank opportunities until evidence gaps are visible.

## Phase 5: Decide whether the problem is worth solving

Read `references/decision-frameworks.md`. Apply hard gates before scoring. Compare “build”, “research more”, “solve with a simpler change”, and “stop”.

Use evidence-backed ratings for frequency, consequence, current workaround failure, willingness to change, access to users, implementation feasibility, and portfolio learning value. Mark every rating as observed, reported, inferred, or unknown.

Recommend only one next decision:

- Stop and record why
- Gather a named missing piece of evidence
- Test a non-product process change
- Prototype a conventional tool
- Continue to AI suitability analysis

If hidden workflow rules are still unknown, recommend gathering the named evidence rather than listing the future tool’s features or selecting its technology.

## Phase 6: Decide whether AI belongs

Use the AI suitability and risk checks in `references/decision-frameworks.md`.

First decompose the workflow into individual tasks. For each task, compare:

1. Process or policy change
2. Existing-tool setup
3. Deterministic automation or rules
4. Conventional software
5. AI-assisted workflow

AI is promising when inputs are meaningfully unstructured or variable, acceptable examples/data exist, output quality can be evaluated, users can correct errors, and the cost of mistakes fits the review design. AI is weak when exactness is mandatory, the needed data is inaccessible, errors are hard to detect, or a few stable rules solve the task.

Output an AI role map:

- AI task
- deterministic surrounding steps
- human review point
- failure and fallback
- data required
- evaluation method

State the conclusion explicitly: AI core, AI assistive, no AI, or insufficient evidence.

## Phase 7: Define and validate an MVP

Read `references/build-validation-portfolio.md` before planning an experiment or MVP.

Write a falsifiable hypothesis linking user, situation, intervention, behavior, and measure. Define the smallest end-to-end slice that tests the riskiest assumption. Prefer, in order:

- Paper or clickable prototype
- Manual concierge test
- Wizard-of-Oz test
- Thin technical prototype
- Usable MVP

Set a baseline and decision threshold before testing. Include a failure criterion. Do not equate praise, clicks, or stated intent with workflow value.

Require the user to approve the problem statement and test plan before substantial implementation.

## Phase 8: Build the smallest usable tool

Inspect available artifacts and choose the simplest suitable implementation. Use relevant creation skills or tools for sites, code, documents, spreadsheets, images, or external integrations. Do not install or connect a service unless the user requests or authorizes it.

Keep the product architecture legible:

- real user input
- deterministic preprocessing
- narrow AI capability where justified
- structured output
- correction or confirmation
- logging of failures and edits

Create acceptance criteria before coding. Use synthetic or anonymized test data until real-data permission is clear. Verify the main user journey and obvious failure paths before handoff.

## Phase 9: Evaluate and iterate

Evaluate both product value and AI quality.

Product measures may include completion rate, time saved, rework, error reduction, adoption in the next real occurrence, and continued voluntary use. AI measures must reflect the actual task and may include accuracy, groundedness, extraction coverage, false positive/negative cost, latency, cost, edit distance, or reviewer agreement.

Keep a failure log. Separate model failure, prompt or retrieval failure, input-quality failure, interface failure, and wrong problem assumption. Change one important variable at a time when practical.

Choose continue, revise, narrow, remove AI, or stop. Do not hide negative results; they strengthen a credible portfolio case.

## Phase 10: Package the portfolio case

Use `references/build-validation-portfolio.md` to assemble a concise case study showing:

- Why this person and workflow were chosen
- What was observed and what remained uncertain
- The workflow and prioritized problem
- Alternatives considered and why AI was or was not selected
- MVP scope and product/AI architecture
- Evaluation design, results, failures, and iteration
- User contribution, decisions, and learning
- Demo, screenshots, artifacts, and next experiment

Protect the participant and employer. Anonymize sensitive content and obtain permission for any identifiable quote or screenshot.

Write the case at the user’s actual level: an AI product manager learner running a real project, not an expert or a fabricated founder story.

## Guardrails against common failure modes

- If the participant proposes a feature, return to the underlying event and desired outcome.
- If only one participant has been studied, call it a case-level signal, not market validation.
- If the user asks whether an idea is good, expose evidence and unknowns before giving a verdict.
- If the workflow is rare but catastrophic, assess risk separately from frequency.
- If the participant is enthusiastic because of friendship, seek behavioral commitment: another session, artifact access, real test, or actual use.
- If evidence comes from participant recall, label it reported rather than observed; do not place AI potential or solution feasibility under known facts.
- If only one occurrence has a time or error count, call it a case measurement rather than a stable baseline.
- If still in phases 1–3, describe at most a provisional solution direction and suppress feature lists, technical choices, and detailed solution tables.
- If automation could change employment, monitoring, evaluation, or pay, surface stakeholder and ethical risks.
- If AI output can cause material harm, require qualified review and narrow the prototype; do not present it as production-ready.
- If a simpler solution wins, preserve that comparison in the portfolio rather than forcing AI into the product.
