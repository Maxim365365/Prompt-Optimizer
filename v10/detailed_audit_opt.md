# Detailed-audit method

Apply `prompt_optimizer.md` Sections 0 and 1.4. Own DA-0 and Sections 1–5.

## DA-0. Run boundary

Use `prompt_optimizer.md` T-DETAILED-AUDIT for activation and Section 1 for object selection, boundaries, and access.

Define CompleteRunReading=1 iff this entire current governing methodology and every selected review file's entire current contents have been obtained for the run. A new completed detailed audit requires CompleteRunReading=1; apply `prompt_optimizer.md` Section 0.2 to governing reads for every request. If required method reading is incomplete, stop method-dependent work. For incomplete review data use Section 2.2; local findings never satisfy this completion predicate.

Use `prompt_optimizer.md` Section 4 for separately requested work.

## 1. Assessment boundary

Assess only criteria 1–18 under their applicability/compliance conditions. The free-audit checklist and governing contract add no grading grounds. Use `audit_evidence_opt.md` Section 3/E-1, including Section 3.6 for necessary outside-criteria observations without grade penalties. Trigger T-AUDIT-REPORT before composing assessments/findings and use `templates_and_formats_opt.md` Sections 9.1–9.3. Criterion names and assessment literals here are Russian service outputs.

## 2. Assessment procedure

### 2.1. Evidence and grades

For criterion k, define Determinate(k)=1 iff available evidence establishes its applicability and supports exactly one assignment below over the declared scope. If Determinate(k)=1, assign that grade; otherwise use verification status `Не проверено: недостаточно данных`, identifying the unresolved provision, missing evidence, and unsupported conclusion. This status is not a fifth grade; unknown is neither noncompliance nor inapplicability.

| Grade | Assignment condition |
| --- | --- |
| `Полное соответствие` | The full-compliance condition holds throughout the applicable scope. |
| `Частичное соответствие` | Some relevant parts or intended cases satisfy the condition and others do not. |
| `Полное несоответствие` | The criterion applies and none of its relevant parts satisfy the condition. |
| `Неприменимость` | The required object or applicability condition is established as absent. |

Use `prompt_optimizer.md` G-3 to admit a supported assignment, not to collapse these outcomes. Apply criterion-specific applicability in Sections 4–5 and evidence admission through `audit_evidence_opt.md` Section 3.3.

### 2.2. Partial review data

Identify each incompletely read review file and the evidenced limitation. Withhold conclusions requiring unavailable material. Limit supported passage-level findings expressly to those passages; list them separately from any whole-criterion status. If the overall grade lacks support, use Section 2.1's verification status. Distinguish omissions from inaccessible evidence under `audit_evidence_opt.md` Section 3.2. Do not label this partial work a completed audit.

### 2.3. Explanations

For partial compliance, identify satisfied and unsatisfied parts and explain how the existing mechanism operates. For complete noncompliance, identify unfulfilled conditions. For inapplicability, identify the absent object/condition. Locate the relevant selected text or established omission. Full compliance needs no separate explanation; explain unverified states under Section 2.1. Apply the evidence owner to every alleged deficiency, including criterion-specific risk and shared-cause reasoning.

### 2.4. Summary

Use `templates_and_formats_opt.md` Section 9.3 for aggregation and repetition. Category counts describe results, not quality. A shared cause establishes neither independence nor equivalence of affected criteria; aggregate only under the agreed method.

## 3. Core criteria

For each criterion, assess the complete applicable condition below. Apply the specific downgrade evidence where stated together with Section 2 and the evidence owner.

### `Требование-1 — однозначность`

Require wording that permits no materially different required actions, execution conditions, or results. To lower the grade, establish at least two readings allowed by the full applicable context, including definitions, scope, exceptions, and priority, and explain their different consequences. Exclude readings rejected by that context. Require neither equal likelihood nor an observed failure.

### `Требование-2 — непротиворечивость`

Require all simultaneously applicable instructions to be jointly executable after scope, exceptions, and priority. To lower the grade, identify incompatible rules and an intended-use situation where both apply; explain why those mechanisms do not resolve the conflict. Different instructions for different conditions do not establish contradiction.

### `Требование-3 — отсутствие дублирования`

Require one definition per normative rule, without repetition lacking a distinct condition, exception, or necessary function. To lower the grade, identify repeated obligations and locations and explain why the repetition adds no necessary function. A reference, template application, or stage reminder proves neither redundancy nor necessity by its form alone.

### `Требование-4 — чёткость требований`

Require every requirement's action/property, object, and applicability to be determinable without execution-changing guesses.

### `Требование-5 — строгость требований`

Require each mandatory obligation and its compliance boundary to distinguish satisfaction from nonsatisfaction. To lower the grade, identify an obligation whose boundary remains indeterminate after the full applicable context and the necessary missing condition. An evaluative term alone establishes no defect; qualitative properties need no numerical threshold when their boundaries are otherwise determinate.

### `Требование-6 — лаконичность`

Require every retained wording/explanation to preserve a necessary meaning, condition, precision, or reliability function; permit no removal without losing such a function. Brevity must retain necessary definitions, restrictions, and exceptions.

### `Требование-7 — компактность`

Require related provisions not to need assembly from dispersed passages where combination preserves conditions, exceptions, precision, reliable execution, and organization.

### `Требование-8 — отсутствие перегруженности`

Require each rule, example, and detail to relate to the task and define/clarify execution or prevent a specific interpretation error; exclude unrelated or unnecessary elements.

### `Требование-9 — сопровождаемость`

Require authoritative definitions, affected provisions, and coordinated-update dependencies to be traceable without guessing their relationships.

## 4. Clarification, approval, and planning

### 4.A. Applicability of criteria 10–11

Define NeedClarification=1 iff intended use anticipates missing input materially affecting meaning, scope, or result and requiring a user answer. Apply criterion 10 when this need is established. Define NeedApproval=1 iff the task requires user approval of decisions or approval is necessary to respect applicable constraints. Apply criterion 11 when this need is established.

If a need is established absent, assign inapplicability with explanation. If its presence/absence cannot be determined, use verification status, not inferred absence. To lower a grade, substantiate both necessity and the unmet condition. Missing questions or approvals alone establish no defect.

### `Требование-10 — уточняющие вопросы`

When applicable, require needed questions, determinable clarification conditions, and a gate stopping answer-dependent actions until the necessary answer is received.

### `Требование-11 — пошаговое согласование`

When applicable, require sequential user decisions with defined approval objects/timing and gates preventing dependent actions before corresponding approval.

### 4.B. Applicability of criteria 12–14

Define NeedPlan=1 iff a plan is an explicitly required deliverable or necessary means of the task under its purpose and operating conditions. Apply criteria 12–14 when established. A general preference for stepwise work or the occurrence of the word “plan” does not establish necessity. If absence of need is established, assign inapplicability; if applicability remains unknown, use verification status. A needed but absent plan is assessable noncompliance, not inapplicability.

### `Требование-12 — детализация плана`

When applicable, require plan items defining concrete task content and observable results without reconstruction by guesswork.

### `Требование-13 — структура плана`

When applicable, require unambiguous task/subtask membership and distinctions; grouping must not replace descriptions of independently meaningful actions.

### `Требование-14 — последовательность плана`

When applicable, require prerequisite results and transition conditions determining execution order and preventing dependent work before its required results.

## 5. Modular architecture

Define Modular=1 iff the reviewed prompt is actually divided among multiple files. Apply criteria 15–18 when Modular=1. If nonmodularity is established, assign inapplicability to each with that explanation. Do not infer modules from references to external information; use Section 2.1 when architecture is unresolved.

### `Требование-15 — межфайловые ссылки`

Require every cross-file reference to identify an existing file/provision unambiguously; permit no absent targets.

### `Требование-16 — условия подключения файлов`

Require each dependent file's reading/application conditions and deadline to be determinate; permit no rule use before its required reading.

### `Требование-17 — порядок применения инструкций`

Require determinate cross-file application and conflict resolution without arbitrary priority choices or unresolvable priority/loading cycles.

### `Требование-18 — согласованность связанных требований`

Require compatible cross-file definitions, conditions, restrictions, and expected results; no file may make another jointly applicable requirement impossible to satisfy.
