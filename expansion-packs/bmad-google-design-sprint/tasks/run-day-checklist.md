<!-- Powered by BMAD™ Core -->

# ------------------------------------------------------------

# Run Day Checklist

# ------------------------------------------------------------

---

task:
id: run-day-checklist
name: Run Day Checklist
description: Execute the appropriate sprint-day checklist with interactive confirmations.
persona_default: sprint-facilitator
steps:

- Ask the user which day or checklist to run, offering numbered options based on available checklists.
- Load the selected checklist markdown and ensure context is understood before execution.
- For each checklist item, read the item with context and rationale, then confirm status using the mandatory 1-9 elicitation format (1 = mark complete and proceed; 2-9 = run deeper prompts or clarifications as needed).
- Capture any follow-up tasks or blockers surfaced during review and assign owners when possible.
- Summarize completion status, outstanding actions, owners, and deadlines, saving notes to `day-checklist-log.md`.

outputs:

- day-checklist-log.md
