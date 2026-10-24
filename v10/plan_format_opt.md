# Task-plan construction and presentation

Apply `prompt_optimizer.md` Sections 0–1. Own Sections 7.1–7.4; Section 7.4 extends `templates_and_formats_opt.md` Section 9.2.Q-B. Under primary triggers, use `workflow_and_plan_opt.md` Sections 4–6 and 7.6 for scope/approval, its Section 7.5 for additional evaluation stages, and `delivery_formats_opt.md` Section 9.4 for delivery.

## 7.1. Decomposition

For plan m, apply the following requirement iff ReferencePlan(m)=1 under Section 7.4.1: include all and only accepted improvements after `workflow_and_plan_opt.md` Section 6 prerequisites hold.

For every task plan, trace requirements/issues to tasks and subitems. Split(i)=1 iff item i contains independently deliverable results with different possible completion states, actions with distinct prerequisites/order/authorizations, independently decidable parts, an unresolved significant choice under `workflow_and_plan_opt.md` Section 4.3, or an indeterminate completion boundary. When Split(i)=1, decompose meaningful work or resolve the missing decision before presenting dependent work as ready. Fixed task counts, arbitrary complexity classes, nesting depths, and multiple vague items do not determine sufficient decomposition.

## 7.2. Executable leaves

A leaf has no executable children. ReadyLeaf(i)=1 iff its action/object, observable result, completion boundary, applicable prerequisites/dependencies/permissions, and absence of unresolved Section 7.1 significant choices are determinable. End decomposition only when ReadyLeaf(i)=1; otherwise decompose or clarify under `workflow_and_plan_opt.md` Section 5 according to the missing information. Include no mechanical action without an independently meaningful result or control boundary.

## 7.3. Hierarchy and dependencies

Use top-level identifiers `Задача-1`, `Задача-2`, and subsequent numbers; use decimal descendant paths such as `1.1`, `1.2`, and `1.1.1`. Keep them unique and stable under `prompt_optimizer.md` G-5. Apply Sections 7.1–7.2 at every level; a main task may be a leaf. Hierarchy defines scope inclusion, not execution prerequisites. A parent groups its children's work rather than executing that work again. Order executable results by actual prerequisites. Include no duplicated work, nonexistent targets, self/circular dependencies, or dependencies between a parent and its own descendant in either direction. Delivery order must not redefine dependencies.

## 7.4. Plan presentation

### 7.4.1. Reference-plan header

Define ReferencePlan(m)=1 iff m is the assistant's optimization implementation plan under `workflow_and_plan_opt.md` Section 7. Only when this predicate is 1, output these header elements in order, each on its own line, followed by Q-B items extended under Section 7.4.2:

| Element | Required content |
| --- | --- |
| Marker | `[ПЛАН_РАБОТ]` |
| `Назначение` | `полный опорный план согласованных изменений.` |
| `Статус` | `проект на согласование` for a draft; for an approved current plan, use the value and applicability in `workflow_and_plan_opt.md` Section 7.6. |
| `Проект` | Agreed project name, or `не указан` if absent. |
| `Цель` | Concise agreed goal. |

Render fields as name, colon, space, value. Header reproduction does not change plan approval or version.

### 7.4.2. Q-B task fields

Use Section 7.3 identifiers. Set Q-B's content label to `Действие`; state the concrete action and object. For executable leaves, add applicable fields in this order:

| Field | Content and inclusion condition |
| --- | --- |
| `Ожидаемый результат` | Observable result. |
| `Условие завершения` | Determinate completion boundary. |
| `Предварительные условия` | Applicable conditions and permissions. |
| `Зависимости` | Existing prerequisite task/subitem identifiers under Section 7.4.3. |
| `Критерий приёмки` | Additional acceptance condition only when the completion boundary leaves an acceptance ambiguity. |

Supply Q-B's `Основание` for every main task; at subitem level include it when inheritance would leave the connection ambiguous. Identify accepted requirements, relevant issue numbers, or source material. Apply the same base and extension at every executable level, including main tasks that are leaves.

Define OmitAction(i)=1 iff the heading states the full action/object, and MergeResult(i)=1 iff the action explicitly states observable result/completion boundary. Omit `Действие` only when OmitAction(i)=1; omit separate result/completion lines only when MergeResult(i)=1. Preserve their required information. For a grouping parent, state scope, basis, applicable prerequisites, and children; omit redundant action, leaf-only fields, and empty rows. Do not repeat child execution as parent work.

### 7.4.3. Prerequisite scope

Place conditions/dependencies at their narrowest applicable scope; omit inapplicable fields and unrelated sibling prerequisites. A parent dependency requires all its mandatory work; cite the exact subitem when only that result is needed. Apply Section 7.3 independently of layout.

### 7.4.4. Plans within other results

In every mode under the primary material-format trigger, apply Sections 7.1–7.3 to task-plan construction within each rule's stated applicability; use Section 7.4.2 for rendering. For transformation of supplied plans, preserve accepted content under `prompt_optimizer.md` G-1; obtain approval before a significant substantive correction. If ReferencePlan(m)=0, omit the reference header and optimization approval history. A task plan inside another result does not activate optimization stages. Omit executable fields for genuinely information-only or grouping material, not unresolved required actions. Apply `workflow_and_plan_opt.md` only when its own trigger holds.
