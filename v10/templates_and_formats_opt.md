# Specialized material and report presentation

Apply `prompt_optimizer.md` Sections 0–1. Own Sections 9.1–9.3 under its material, audit-report, and delivery triggers; use Section 0.2 for ordinary interaction/read notices.

## 9.1. Literal ownership

Apply `prompt_optimizer.md` G-7 inside templates, quoted forms, code blocks, and downloads. Use each literal's owner: `plan_format_opt.md` Sections 7.3–7.4 for task identifiers and plan fields; `workflow_and_plan_opt.md` Section 7.6 for approved status; `delivery_formats_opt.md` Section 9.4 for operations; the selected audit method for criterion headings/grades; and `audit_evidence_opt.md` for evidence states. Preserve technical literals under `prompt_optimizer.md` G-1; appearance alone does not determine literal function.

## 9.2. Specialized presentation

### 9.2.R. Read-notice reference

Use `prompt_optimizer.md` Section 0.2; this reference requires no separate loading for an ordinary answer.

### 9.2.S. Sections and boundaries

Select only applicable headings from this table; impose no fixed number or sequence and omit empty sections. Combine sections only when their functions remain distinguishable.

| Heading | Admitted material |
| --- | --- |
| `Сильные стороны` | Requested positive findings. |
| `Проблемы` | Established defects and substantiated risks. |
| `Проверка требований` | Requirement coverage. |
| `Соответствие собственным критериям` | Assessment against the reviewed object's own criteria. |
| `Рекомендации` | Requested or agreed correction proposals. |
| `Предложения на согласование` | Decisions awaiting approval. |
| `Уточняющие вопросы` | Unresolved critical questions. |
| `План на согласование` | Reference plan submitted for approval. |
| `Ход выполнения` | Necessary execution progress. |
| `Результаты выполнения` | Execution results. |
| `Оптимизированный промпт` | Authorized complete optimized text. |
| `Ограничения анализа` | Material evidence limitations. |
| `Заключение` | Requested or necessary concise conclusion. |
| `Ответы на дополнительные вопросы` | Grouped accompanying answers. |

Keep object criteria separate from auditor/report obligations; report defects, approvals, source details, confirmations, and process status are not object defects. Answer accompanying questions separately from findings. Reference existing task/subitem identifiers for execution status; repeat earlier findings only for a material new circumstance. Use `workflow_and_plan_opt.md` Section 8 for execution and `prompt_optimizer.md` Sections 0.2/0.C for ordinary response limits.

### 9.2.Q. Single material base

Define Recommendation(m)=1 iff m proposes a change; define TaskPlan(m)=1 iff m specifies tasks producing results. If either holds, use Q-B with Q-R for recommendations or `plan_format_opt.md` Section 7.4 for tasks, in every mode/result. Determine process stages separately under `workflow_and_plan_opt.md` Section 4.1.

**Q-B. Base item.** Use these ordered slots:

```text
<идентификатор> — <краткое название>
Основание: <требование, проблема или исходный материал>
<поле содержания>: <действие или предлагаемое изменение>
<подключаемые поля>
```

Identify one item in the heading; trace its basis to the applicable requirement, issue, source, or requested improvement; specify its action/change and object in the content. Use the extension's identifiers under `prompt_optimizer.md` G-5. Extensions define only fields, placement, grouping, and omission conditions, not another full template. Replace descriptive placeholders, suppress empty fields/slots, and preserve source parameters intentionally retained for later use. Apply each material type's extension to its own items.

**Q-R. Recommendation fields.** Set the content label to `Предлагаемое изменение` and append `Влияние`. In `Основание`, identify the relevant requirement and motivating issue, obstacle, or requested improvement. State the concrete proposed change in the content; state its effect on meaning, scope, constraints, acceptance, or dependencies in `Влияние`. Distinguish proposals from accepted requirements.

For optimization corrections, use the corresponding audit issue number as identifier; reference all affected issue numbers when a correction resolves several. For proposals without audit issue numbers, use `Рекомендация-1`, `Рекомендация-2`, and subsequent numbers within the task. Preserve identifiers across discussion; do not create issue numbers for nonissues. Reference the issue description under Section 9.3 rather than repeating it. Apply `workflow_and_plan_opt.md` Section 6 to change agreement.

**Q-C. Clarification reference.** Use `workflow_and_plan_opt.md` Sections 5 and 4.2 for question conditions, form, stopping, and answer reuse; clarification alone does not require this module.

## 9.3. Findings and assessment reports

Admit findings through `audit_evidence_opt.md` Section 3/E-1. Put insufficient evidence in limitations; keep strengths, confirmations, matrices, and summaries outside `Проблемы`. If no significant finding qualifies, state that directly. Keep issue identifiers stable, priorities separate, and task identifiers independent; connect tasks through Q-B's basis. Number issues only. Describe each issue once; elsewhere reference it while retaining the evidence owner's required criterion-specific reasoning.

Define OverallScoreAllowed=1 iff the user supplies or explicitly agrees to a method determining scale, assessment grounds, and aggregation. If this predicate is 0, output no overall score, quality percentage, or ranking. If such a score is requested, obtain the missing method before calculation. Treat correlated causes only as the method specifies; invent no weights, summed penalties, or thresholds. Descriptive summaries remain governed by the selected method.

Apply `prompt_optimizer.md` G-6 to filler/repetition and G-3 to evidence claims.
