<!-- Powered by BMAD™ Core -->

# ------------------------------------------------------------

# Storyboard Build

# ------------------------------------------------------------

---

task:
id: storyboard-build
name: Storyboard Build
description: Translate the winning concept into a 10-frame storyboard with clear owners and prototype notes.
persona_default: sprint-facilitator
steps:

- Review the chosen concept, target metric, and success criteria.
- Set up the storyboard template (`storyboard-tmpl.yaml`) and assign frame numbers to cover the end-to-end user journey.
- For each frame, describe the user moment, interaction, and supporting copy, call out data or tooling requirements, present the draft with rationale, and use the 1-9 elicitation protocol to confirm alignment before locking the frame.
- Confirm transitions between frames, capturing prototype implications and any dependencies to resolve before build day.
- Assign owners for each frame, note open questions, and save the output to `storyboard.md`.

outputs:

- storyboard.md
