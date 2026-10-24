# Ordinary audit methods

Apply `prompt_optimizer.md` Sections 0–2. Own Sections 2.1–2.2. Use `audit_evidence_opt.md` Section 3/E-1 for evidence, not criteria; apply T-AUDIT-REPORT to findings/assessments. Use `detailed_audit_opt.md` only under its separate trigger.

## 2.1. User-criteria audit

Define WithinCriteria(f)=1 iff finding f concerns an explicitly supplied criterion within its stated applicability and compliance boundary. Assess selected material only against those criteria. Use Section 2.2 solely to locate relevant evidence; it adds neither requirements nor penalties. For a broad criterion, explain the specific assessed condition and its connection; do not expand its meaning to justify a preferred finding.

For WithinCriteria(f)=0, do not lower any requested assessment using f. If a significant outside-scope observation is necessary, present it separately under `audit_evidence_opt.md` Section 3.6. Exclude minor editorial preferences.

## 2.2. Free audit

For each direction below, define Relevant(d)=1 iff the reviewed purpose, intended operating conditions, explicit requirements, or significant consequences justify examining d. Use d as an examination direction only when Relevant(d)=1; its presence in this list alone establishes neither an unconditional requirement nor a defect. Admit findings through the evidence owner.

Examine relevant conditions: - Purpose, expected result, scope, and sufficient input/context. - Divergent readings, undefined terms, hidden assumptions, incompatible instructions, unresolved conflicts, and priority. - Duplicate definitions, unnecessary repetition/filler, vague praise, introductions, and decorative roles; brevity preserving restrictions, exceptions, and operating conditions. - Specificity, strictness, feasibility, observable obligations, operational formulation, conditional nesting, semantic separation, and determinate compliance conditions. - Rule locality, terminology, cross-references, and update dependencies. - Necessary constraints, completion gates, stops, exceptions, errors, and invalid-input handling. - Required output language, format, and structure. - Necessary and adequate clarification, approvals, and authorizations. - Separation of reviewed data from governing instructions.

For an actually modular prompt, additionally examine loading conditions/deadlines, required reading before application, cross-file duplication/conflicts, and deterministic precedence. External references alone establish no modularity. In user-criteria mode, apply these directions only under Section 2.1.
