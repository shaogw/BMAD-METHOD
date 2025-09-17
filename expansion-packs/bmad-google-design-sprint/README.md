# Google Design Sprint Lab

<!-- Powered by BMAD™ Core -->

Welcome to the **Google Design Sprint Lab**, a BMAD expansion pack crafted for teams that
need to validate critical product bets in five focused days. Inspired by the original
Google Ventures methodology, this pack equips you with AI facilitators, templates,
checklists, and workflows that replicate the cadence of Understand → Diverge → Decide →
Prototype → Test.

## Why this pack exists

Traditional design sprints demand relentless coordination, disciplined facilitation, and
meticulous documentation. The Google Design Sprint Lab transforms that workload into an
AI-assisted operating system: agents that coach and critique, executable tasks that keep
the team on schedule, and ready-to-run workflows that hold everyone accountable to the
process.

## Key capabilities

- 🧭 **Sprint orchestration** – Use five-day or condensed workflows to run end-to-end
  sprints with automated hand-offs between agents.
- 🧠 **Expert personas** – Activate facilitators, deciders, researchers, prototype leads,
  sketch coaches, and test analysts, each wired to the right tasks, templates, and data.
- 🛠️ **Executable rituals** – Launch structured How Might We clustering, lightning demos,
  Crazy Eights, storyboard builds, prototype stand-ups, and test debriefs.
- 📋 **QA guardrails** – Apply day-by-day checklists that prevent schedule slip, missing
  assets, or research lapses.
- 📄 **Battle-tested templates** – Generate sprint briefs, interview notes, storyboard
  frames, prototype build plans, and usability test kits with full elicitation support.
- 📚 **Reference vault** – Surface agendas, inspiration prompts, and tooling guidance right
  from agent dependencies.

## Agent roster

| Agent                         | Role                                                               | Core Responsibilities |
| ----------------------------- | ------------------------------------------------------------------ | --------------------- |
| `sprint-facilitator`          | Keeps sprint on schedule, shapes challenges, manages collaboration |
| `product-decider`             | Aligns business goals, makes final calls, secures prototype focus  |
| `customer-insight-researcher` | Preps experts, maps journeys, synthesizes interviews               |
| `solution-sketch-coach`       | Guides ideation, lightning demos, Crazy Eights sessions            |
| `prototype-lead`              | Plans scope, allocates build responsibilities, unblocks makers     |
| `test-analyst`                | Designs usability sessions, moderates tests, synthesizes learnings |

## Workflows included

- `google-design-sprint.yaml` – Full five-day sprint with linked rituals and deliverables.
- `design-sprint-lite.yaml` – Accelerated three-day validation sprint for time-boxed
  experiments.
- `usability-test-day.yaml` – Stand-alone Friday testing loop for teams reusing the kit.

## Installation & activation

1. Clone or update BMAD Core.
2. Copy `expansion-packs/bmad-google-design-sprint` into your BMAD packs directory.
3. Run `bmad packs refresh` to index new agents, tasks, and workflows.
4. Activate the team bundle via `bmad team load agent-teams/google-design-sprint-team.yaml`.
5. Launch the five-day sprint workflow or summon agents individually using the `/bmad-gds`
   slash prefix.

## Folder map

```
expansion-packs/bmad-google-design-sprint/
├── agents/                  # Six sprint specialists with command wiring
├── agent-teams/             # Team bundle for quick activation
├── checklists/              # Logistics and QA guardrails for each sprint day
├── data/                    # Reference sheets, prompts, and agendas
├── docs/                    # Executive brief and roadmap
├── tasks/                   # Executable rituals and collaboration scripts
├── templates/               # YAML templates for structured deliverables
├── workflows/               # End-to-end orchestration YAMLs
└── config.yaml              # Pack metadata and slash command prefix
```

With the Google Design Sprint Lab installed, your team can compress weeks of decision
making into a single sprint, all while documenting every step with consistent rituals and
AI-powered facilitation.
