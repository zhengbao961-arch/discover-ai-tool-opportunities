# Opportunity and AI decision frameworks

Use these frameworks after at least one concrete workflow has been reconstructed.

## Hard gates

Pause or stop before scoring when any condition applies:

- No access to the worker for follow-up or testing
- The problem exists only as a hypothetical statement
- Required data cannot be accessed legally or practically
- A simpler process correction clearly removes the pain
- The tool would create unacceptable privacy, employment, safety, or compliance risk
- Success cannot be observed or evaluated

Before proposing a product or implementation, also require enough reconstruction of one recent occurrence to identify the current tools, workaround, consequence, and meaningful exceptions. Until then, return “research more” and name the smallest missing evidence.

A failed gate can become the next research question. Do not average it away with a high score elsewhere.

During discovery, a provisional category such as deterministic automation or AI assistance is allowed only to guide research. Do not turn that category into a feature list, architecture, product name, or technology selection before the gate passes.

## Opportunity score

Rate each dimension 0–3 and attach an evidence label. Do not calculate unknowns as zero.

| Dimension | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| Frequency | Rare or one-off | Monthly | Weekly | Daily or per case |
| Consequence | Preference only | Mild effort | Material time/rework | Revenue, compliance, safety, or severe blockage |
| Workaround gap | Existing method works | Annoying but reliable | Fragile or costly | Repeated failure or no viable method |
| Change commitment | No action | Verbal interest | Shares artifacts or time | Tests in real work or changes behavior |
| User access | No follow-up | One contact | Repeat access | Multiple reachable users/stakeholders |
| Feasibility | Major unknowns | Several hard dependencies | Thin prototype plausible | Small end-to-end slice is readily testable |
| Portfolio learning | Little new evidence | One narrow skill | Full product decision | Research, AI judgment, build, and evaluation |

Use the score to structure reasoning, not to manufacture certainty. Summarize strongest evidence, decisive unknown, and recommended action.

## AI suitability

Rate 0–3 with evidence:

| Dimension | Low suitability | High suitability |
|---|---|---|
| Input variability | Stable structured fields | Language, images, documents, or variable context |
| Rule sufficiency | Few reliable rules solve it | Rules become brittle or cannot capture judgment |
| Data/examples | Unavailable or prohibited | Accessible, representative examples exist |
| Evaluability | Quality is subjective and uncheckable | Output can be compared, reviewed, or measured |
| Error tolerance | One error causes serious harm | Errors are reversible and reviewable |
| Human feedback | No reviewer or correction loop | User naturally reviews and corrects |
| Economic fit | Cost/latency exceeds value | Cost and latency fit the workflow |

## AI role conclusions

- **AI core:** The central job depends on interpreting or generating variable content, and quality can be controlled.
- **AI assistive:** AI accelerates a bounded step while the user remains responsible for the final action.
- **No AI:** Deterministic automation or conventional software is more reliable and economical.
- **Insufficient evidence:** A data, risk, or evaluation assumption must be tested first.

## Risk review

For every AI task, record:

- plausible wrong output
- who notices it and how
- consequence before correction
- confidence or source information shown
- review requirement
- fallback when the model is unavailable or uncertain
- data retained and access boundaries

Do not call a prototype safe merely because a human is nominally “in the loop”. Verify that the person has time, context, authority, and a usable interface to review it.
