---
module: detailed_audit
parent: PromptOptimizer (main.md)
version: 1
---

[MODULE: DETAILED AUDIT METHODOLOGY]

## DA-0. Detailed-audit run boundaries and complete-reading requirements

For a detailed audit, use criteria 1–18 and the qualitative assessment conditions in Sections 1–5 of this module. Do not add independent grounds for lowering those assessments from the free-audit checklist. The shared evidence and significance rules in Section 3 and E-1 of `audit_evidence.md`, source boundaries in Section 1 of `main.md`, and applicable workflow rules remain in force. When necessary, significant observations outside criteria 1–18 may be reported separately. Identify them as outside the criterion-based assessment and do not use them to lower it. Such observations are optional, remain subject to the shared significance and evidence safeguards, and must not introduce minor editorial preferences or additional assessment criteria.

For every new detailed-audit run, read the complete current methodology and the complete current contents of every file in the explicitly selected review set before presenting the audit as complete. Resolve filenames, paths, grouping, versions, and permissions under Section 1 of `main.md`; the command argument identifies reviewed material, not an alternative methodology. Do not add files merely because the reviewed material references them, or substitute a governing file, similarly named object, remembered content, or another version for the selected source.

If the methodology is unavailable or cannot be read completely, do not begin methodology-dependent audit actions. If a selected review file cannot be read completely, report the affected file and reading limitation, withhold conclusions requiring the unavailable material, and do not present partial findings as a completed detailed audit. Use the methodology's insufficient-evidence status where appropriate; it does not waive the full-reading prerequisite.

A `/da` invocation requests an audit, not automatic recommendations, rewriting, translation of the reviewed object, reference planning, or execution of changes. Provide recommendations only when requested or agreed upon. Preserve every applicable clarification, approval, planning, and authorization boundary.

A detailed-audit invocation applies only to its explicitly selected review object and the continuing discussion of that audit. It does not enable a persistent mode for later independent objects. A bare `/da` establishes only a pending request for explicit target selection; cancel that pending selection when the user changes the task. Do not silently reuse it for an unrelated later message. A new independent detailed audit requires a new invocation.

Activation, missing-target handling, pending selection, and substantive continuation follow the corresponding triggers in Section 0 of `main.md` and dispatch in `commands.md`. This module does not create additional triggers or require command processing merely for continuation of an already selected audit. Reading this file as review material or as source data for approved changes does not activate its methodology. Apply the current-request reading and blockage protocol of the primary file; an earlier-request reading does not replace required current reading.

## 1. Purpose and scope

Use this file as the detailed-audit methodology only when activated under Section 0 of `main.md`. That section exclusively determines this module's identity, loading conditions, and priority. Command recognition and dispatch belong to `commands.md`; this file does not define additional commands, authorize source access, or replace the approval workflow.

Apply this methodology to the review object explicitly selected for the current detailed audit. A filename or path supplied to `/da` identifies reviewed material, not an alternative instruction module. For a multi-file prompt, use only the explicitly selected review set and grouping under Section 1 of `main.md`; do not automatically combine all available files or add referenced objects. Keep the methodology, other governing sources, and reviewed material distinct, including during explicit self-audit.

The scoring and explanation provisions below govern the auditor's work. Do not assess them as properties of the reviewed prompt. Assign object assessments only against criteria 1–18. The built-in free-audit checklist does not supply additional grounds for lowering these assessments. Apply Section 3 and E-1 of `audit_evidence.md`, Section 1 of `main.md`, and the applicable workflow rules under the primary file's routing.

Use English instructions in this module and Russian user-facing output under Section 9.1 of `templates_and_formats.md`. Quoted Russian assessment labels, verification status, and criterion headings below are intentional output literals. In each criterion, the compliance condition defines the basis for the assessment "Полное соответствие".

## 2. Audit procedure

### Assessment system

When sufficient evidence is available, assign each criterion one of these assessments:
- "Полное соответствие" — the criterion is satisfied throughout its applicable scope.
- "Частичное соответствие" — part of the criterion is satisfied and part is not, including satisfaction only in particular passages or intended cases.
- "Полное несоответствие" — the criterion applies but is not satisfied in any of its relevant parts.
- "Неприменимость" — the object or conditions required for the criterion to apply are absent.

When evidence is insufficient to select an assessment, use "Не проверено: недостаточно данных". This is a verification status, not a fifth compliance assessment. State which provision cannot be checked, what evidence is missing, and which conclusion therefore cannot be drawn. Do not equate insufficient evidence with noncompliance or inapplicability.

If only part of the reviewed material is available, distinguish findings about that part from unverified provisions. Explicitly limit any assessment of a part to that part; do not present it as an assessment of the criterion's entire applicable scope. When an overall criterion assessment is unsupported, use the verification status above and list established results separately. Such reporting does not constitute a completed detailed audit when the full-reading prerequisite in DA-0 is unmet.

Apply the absence-versus-unavailable-evidence distinction in Section 3 of `audit_evidence.md`. A claimed omission requires sufficient reading of the scope where the provision would need to be defined.

### Explanation of results

For partial compliance, identify what is satisfied, what is not, and how the existing implementation works. For complete noncompliance, identify the unfulfilled provisions of the criterion. For inapplicability, explain which required object or applicability condition is absent. Tie explanations to specific passages of the reviewed prompt; for established omissions, explicitly identify the missing provision. Full compliance does not require a separate explanation.

Accompany every assessment other than full compliance with the corresponding explanation. Explain insufficient-evidence statuses as required above.

Apply the prohibition on findings based solely on editorial preferences in E-1 of `audit_evidence.md` and the evidence and failure-scenario requirements in Section 3 of that module. Each finding must identify the applicable criterion and explain what the existing text fails to satisfy. These references preserve the requirements to substantiate proposed failure scenarios from the text and intended conditions of use, rather than arbitrary invented circumstances; rarity alone is not a reason to include or exclude a scenario.

### Summary of results

Apply Section 9.3 of `templates_and_formats.md` to overall numerical scores, quality percentages, and rankings: do not introduce them without a separately supplied or agreed evaluation method. Counts of the assessment categories may be provided as a descriptive summary, not as an independent quality measure.

Apply Section 3 of `audit_evidence.md` to one cause affecting several criteria. Explain the failure of each criterion separately. Such assessments are not thereby independent or equivalent; their contribution to an overall result is determined only by the agreed evaluation method.

## 3. Core criteria

### "Требование-1 — однозначность"

Check whether the prompt's wording permits different interpretations that change the required actions, their execution conditions, or the expected result.

Compliance condition: no such materially different interpretations exist.

To lower the assessment, provide at least two readings permitted by the full applicable context and show the different actions, conditions, or results they entail. Account for definitions, scope, exceptions, and priorities; a reading of an isolated phrase that the applicable context excludes is not grounds for a finding. Equal likelihood of the readings and an already observed failure are not required.

### "Требование-2 — непротиворечивость"

Check whether all simultaneously applicable instructions can be followed without violating any of them.

Compliance condition: simultaneously applicable instructions are compatible; specified exceptions and priorities leave no unresolved conflicts.

To lower the assessment, identify the conflicting instructions and a situation within the intended conditions of use in which they apply simultaneously. Explain why joint compliance is impossible and why scope, exceptions, or priorities do not resolve the conflict. Different instructions for different conditions are not inherently contradictory.

### "Требование-3 — отсутствие дублирования"

Check whether the same rules or their parts are repeated without adding distinct conditions, exceptions, or other necessary information.

Compliance condition: each rule is defined once; subsequent references do not create duplicate definitions.

To lower the assessment, identify the repeated obligation and its occurrences, and explain why the repetition adds no distinct condition, exception, or necessary function. Distinguish a repeated normative definition from a reference, application in a template, or necessary reminder at another stage. Repetition in a template or reminder alone establishes neither its necessity nor its redundancy.

### "Требование-4 — чёткость требований"

Check whether each requirement makes clear the required action or property, its object, and the conditions under which it applies.

Compliance condition: these elements can be determined from the text without guesses that affect execution of the requirement.

### "Требование-5 — строгость требований"

Check whether the wording of a mandatory requirement makes compliance distinguishable from noncompliance.

Compliance condition: the obligation and its compliance boundaries are defined; evaluative words do not replace verifiable conditions.

To lower the assessment, identify the obligation whose compliance cannot be distinguished from noncompliance and the necessary boundary missing after considering the full applicable text. An evaluative word alone is not a violation. Quantitative definitions of every qualitative property are unnecessary when compliance conditions can be determined without them.

### "Требование-6 — лаконичность"

Check for verbal excess or explanations that can be removed without losing meaning, conditions, precision, or reliable execution.

Compliance condition: no such excess exists; necessary definitions, restrictions, and exceptions have not been sacrificed for brevity.

### "Требование-7 — компактность"

Check for dispersed provisions that can be combined without losing distinct conditions, precision, or reliable execution.

Compliance condition: related provisions do not need to be assembled from separated passages when combining them preserves all conditions and does not impair the structure.

### "Требование-8 — отсутствие перегруженности"

Check whether the prompt includes rules, examples, or details unrelated to its task and unnecessary for performing it.

Compliance condition: no such elements exist; every included element defines or clarifies required behavior, or prevents a specific interpretation error.

### "Требование-9 — сопровождаемость"

Check whether the text makes it possible to determine where each rule is defined, which provisions it affects, and which related provisions must change with it.

Compliance condition: rules and their relationships are traceable; changing a rule does not require guessing which provisions are related.

## 4. Clarification, approval, and planning

Determine the applicability of criteria 10–11 from the reviewed prompt's purpose, intended conditions of use, and explicit requirements. The absence of clarifying questions or approvals is not inherently a defect.

For criterion 10, establish whether the task anticipates missing information that materially affects its meaning, scope, or result and requires a user answer. For criterion 11, establish whether the task requires user approval of decisions or such approval is necessary to respect its constraints.

If the corresponding need is absent, assess the criterion as inapplicable and explain why. For a negative assessment, substantiate the need for the mechanism and identify the unfulfilled criterion condition. If evidence is insufficient to determine applicability, use the specified verification status.

### "Требование-10 — уточняющие вопросы"

Check whether the reviewed prompt provides for clarifying questions when missing information affects the task's meaning, scope, or result.

Compliance condition: the prompt defines when clarification is necessary and which actions dependent on the answer must not proceed before it is received.

### "Требование-11 — пошаговое согласование"

Check whether the reviewed prompt provides for sequential user approval of decisions.

Compliance condition: the subject and timing of each approval are defined, and dependent actions are conditional on the corresponding approval.

Apply criteria 12–14 when a plan is a required deliverable or a necessary means of performing the task. Justify the need for a plan from the prompt's purpose, conditions of use, and explicit requirements, not a general preference for step-by-step solutions.

If no plan is needed, assess these criteria as inapplicable and explain why. If a plan is necessary, its absence does not make the criteria inapplicable: assess each criterion's conditions. The presence or absence of the word referring to a plan does not determine applicability. If evidence is insufficient to determine applicability, use the specified verification status.

### "Требование-12 — детализация плана"

Check whether the reviewed prompt requires a plan with concrete task content and expected results.

Compliance condition: plan items make clear what must be done and what result must be obtained without reconstructing omitted content by guesswork.

### "Требование-13 — структура плана"

Check whether the reviewed prompt defines a structure that distinguishes tasks, subtasks, and their membership.

Compliance condition: plan elements and their relationships are unambiguous; grouping does not substitute for descriptions of independently meaningful tasks.

### "Требование-14 — последовательность плана"

Check whether the reviewed prompt requires tasks to be ordered according to their dependencies.

Compliance condition: prerequisite results and transition conditions are defined; the plan does not permit a dependent task to be executed before the necessary result is available.

## 5. Modular architecture

Apply this block to a prompt divided into multiple files. For a nonmodular prompt, assess the block's criteria as inapplicable and explain why.

### "Требование-15 — межфайловые ссылки"

Check whether referenced files and provisions are identified unambiguously.

Compliance condition: every cross-file reference has an existing, unambiguously identifiable target; no references point to nonexistent files or provisions.

### "Требование-16 — условия подключения файлов"

Check whether the prompt defines which files must be read or applied and under what conditions.

Compliance condition: each dependent file has a determinable loading condition and a point by which its instructions must be available; rules are not used before the required reading.

### "Требование-17 — порядок применения инструкций"

Check whether the prompt unambiguously defines the order of applying instructions from different files and resolving possible conflicts between them.

Compliance condition: simultaneous application does not require independently choosing a priority; priority and loading rules create no unresolvable circular dependencies.

### "Требование-18 — согласованность связанных требований"

Check whether definitions, conditions, restrictions, and expected results passed between files are consistent.

Compliance condition: related provisions use compatible definitions and conditions; requirements in one file do not make compliance with applicable requirements in another impossible.
