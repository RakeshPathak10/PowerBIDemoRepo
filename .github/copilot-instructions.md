# Power BI PBIP engineering instructions

- Treat PBIP, TMDL, PBIR, DAX, Power Query M, test assets, and deployment definitions as source-controlled engineering artifacts.
- Never expose credentials, tokens, tenant identifiers, customer data, or sampled business data.
- Prefer explicit measures, dimensional modeling, reusable transformations, documented relationships, and accessible report design.
- Review before editing. Explain assumptions and distinguish confirmed defects from recommendations requiring runtime validation.
- Keep generated changes narrow, reviewable, and reversible. Do not alter lineage tags, security roles, deployment targets, or environment settings without explicit instruction.
- Never publish, deploy, merge, or approve a release automatically.
- Cite exact repository paths and object names in findings.
- Use these severities: BLOCKER, HIGH, MEDIUM, LOW, INFO.
- For each deliverable state inputs used, assumptions, outputs created, validation steps, unresolved risks, and recommended next handoff.
