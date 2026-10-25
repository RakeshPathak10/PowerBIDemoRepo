---
agent: powerbi-release-readiness
description: Assess a Power BI release candidate from available evidence.
---
Assess release candidate ${input:candidate:branch, commit, or release identifier} targeting ${input:environment:target environment}.
Use available review, test, security, refresh, accessibility, validator, rollback, and operational evidence. Do not deploy or approve. Return READY, READY WITH CONDITIONS, or NOT READY.
