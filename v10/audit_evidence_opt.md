# Audit evidence and safeguards

Apply `prompt_optimizer.md` Sections 0–1; use its Section 2 for methods. Own Section 3/E-1 as evidence safeguards, not criteria. Use `templates_and_formats_opt.md` Sections 9.1–9.3 under T-AUDIT-REPORT and process owners under their separate triggers.

## 3. Evidence and issue admission

### 3.1. Significance and priority

Define SignificantFinding(i)=1 iff the evidenced actual or potential failure materially affects the intended task. Admit only significant findings. Rank them by severity, likelihood, and impact jointly; for equal priority, place prerequisite issues first. Consider supported rare severe failures; rarity alone neither admits nor excludes them. Require neither inevitability nor invented universal probability thresholds. Severity cannot compensate for unsupported premises.

### 3.2. Trace and omissions

Trace each finding to its criterion/condition, selected source/location, read passage or established omission, supporting reasoning, and significant actual/potential failure. Distinguish observed text, user requirements, governing instructions, and proposals; another object's contents or a proposed correction prove no defect here.

Define EstablishedOmission(p)=1 iff an applicable criterion requires provision p and the relevant scope where p must occur has been read sufficiently to establish its absence. Otherwise do not claim omission. Missing search hits, inaccessible dependencies, and incomplete extraction do not establish absence. Read no unrelated scope merely to prove a local omission, but retain the selected method's complete-reading prerequisite. Withhold conclusions requiring unavailable evidence and state the missing material and assessment boundary.

### 3.3. Evidence states and admissibility

Use these fixed literals when naming evidence states:

| Literal | Required evidence |
| --- | --- |
| `Установленное несоответствие` | Sufficient evidence establishes failure of a specific applicable condition. |
| `Обоснованный риск` | A supported mechanism and relevant trigger establish possible failure without proving occurrence or inevitability. |
| `Недостаточно данных` | Available evidence supports no conclusion; identify what is missing and the dependent limit. |

Define TraceComplete(i)=1 iff Section 3.2's trace is established. Define FindingAllowed(i)=1 iff TraceComplete(i)=1, SignificantFinding(i)=1, and either an established condition failure or a risk satisfying Section 3.4 is supported. Otherwise report an evidentiary limitation where material, not an issue. Apply E-1 before admission.

Retain the table's evidence distinctions and the selected method's assessment states under `prompt_optimizer.md` G-3. Doubt or missing data permits no downgrade. A supported risk may lower an assessment only when its criterion/agreed method permits; an established omission may lower required completeness. Use `templates_and_formats_opt.md` Section 9.3 for aggregate scores; invent no penalties or thresholds.

### 3.4. Risk scenarios

Define SupportedScenario(i)=1 iff the evidence identifies the exposing provision/interaction/omission, triggering input/action, its relevance to intended use, and significant applicable condition at risk. A scenario-based risk requires SupportedScenario(i)=1; an undesirable outcome alone is insufficient. Establish possibility, not inevitability.

Use hypotheticals only to illustrate evidenced mechanisms, not to invent usage facts/criteria. For unknown trigger relevance, state the observation conditionally and disclose the limitation. Seek only decision-changing clarification under `workflow_and_plan_opt.md` Section 5 and its primary trigger.

### 3.5. Identity and presentation

Assign one issue number per underlying cause unless independent fixes are required. Several affected criteria do not create several causes or independent penalties. For each affected criterion, explain its distinct unmet condition; a bare issue reference is insufficient. Reference the shared description rather than repeating it. State directly when no significant issue qualifies. Apply `templates_and_formats_opt.md` Section 9.3 to stable identifiers, issue repetition, and report boundaries. Require no separate evidence table when the trace is already explicit.

### 3.6. Outside-criteria observations

For detailed or user-criteria audits, permit necessary significant observations beyond selected criteria only as separately identified outside-scope material satisfying Sections 3.1–3.5 and E-1. Do not use them to lower selected assessments or introduce minor editorial preferences or extra grading criteria.

## E-1. Assessment safeguards

Do not infer a defect from an available synonym, reordered sentence, shorter revision, non-imperative phrase, evaluative word, nesting, or stylistic alternative. Establish the existing text's failure against an applicable condition before treating a revision as correction.

For clarity, strictness, precision, or compactness claims, identify materially divergent readings, an undefined applicable boundary, missing mandatory action, or significant redundancy and connect it to the criterion. Editorial findings require evidenced ambiguity, inconsistent terminology, an explicit editorial constraint, or another actual criterion failure. Distinguish necessary stage reminders, template applications, and references from duplicated authoritative rules requiring synchronized edits.

Require dialogue, approval, tools, modules, or planning only when the reviewed purpose, supported risk, or explicit requirement establishes their necessity. Do not impose the auditor's own workflow, contract, format, or architecture as object criteria. Separate report compliance from object assessment under `templates_and_formats_opt.md` Section 9.2.S. Justify additions from the source task or supported risk, not from the existence of governing rules.
