<!-- Powered by BMAD™ Core -->

# ------------------------------------------------------------

# Problem Priority Matrix

# ------------------------------------------------------------

---

task:
id: problem-priority-matrix
name: Problem Priority Matrix
description: Consolidate observed issues, classify root causes, and prioritize remediation opportunities.
persona_default: problem-analysis
steps: - Aggregate pain points and issues captured by discovery agents; ensure source references are preserved. - Classify each issue into Management, Information, Efficiency, Compliance, or Experience and note impacted metrics. - Hypothesize root causes, contributing factors, and affected capabilities, roles, and data objects. - Score severity, frequency, value leakage, and time-to-impact; calculate an overall priority ranking. - Identify quick wins vs. strategic investments; propose recommended owners and next actions. - Summarize findings for executive review and cue hand-off to Value Proposition Agent.
outputs: - problem-register.yaml - impact-assessment.csv - evidence-pack.md
