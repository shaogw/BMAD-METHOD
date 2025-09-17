# Business Architecture Discovery Lab

<!-- Powered by BMAD™ Core -->

The **Business Architecture Discovery Lab** is a BMAD expansion pack that installs a
front-loaded business analysis motion before any product ideation begins. Designed for
teams serving complex B2B domains—like construction management, field operations, or
asset-heavy industries—it equips you with AI agents, executable tasks, and structured
templates to transform ambiguous enterprise processes into a product-ready opportunity
dossier.

## Why this pack exists

Product organizations working with construction and industrial clients rarely start with
a backlog of crisp user stories. Instead, they face policy entanglements, fragmented
process ownership, and inconsistent data vocabularies. This pack formalizes an upstream
business architecture sprint so you can understand value delivery, capability gaps,
information lifecycles, and stakeholder pain before committing to feature roadmaps.

## Key capabilities

- 🧠 **Domain intelligence synthesis** – Compile regulations, standards, and SOPs into a
  structured domain map that clarifies scope, constraints, and terminology.
- 🧩 **End-to-end value stream modeling** – Capture job-level flows, hand-offs, metrics,
  and information exchanges across pre-/post-activities.
- 🏗️ **Capability and maturity mapping** – Translate flows into layered capability maps
  with current vs. target maturity to surface modernization priorities.
- 📘 **Information architecture scaffolding** – Model entities, attributes, relationships,
  lifecycle states, and stewardship responsibilities.
- 🔍 **Problem and opportunity framing** – Diagnose management, information, and
  efficiency blockers, then synthesize value propositions and product wedges.
- 🧾 **Traceable analyst handoff** – Package findings into structured YAML/Markdown
  deliverables for Analyst Agents to convert into briefs or PRDs.

## Agent roster

| Agent                   | Role                    | Core Responsibilities                                       |
| ----------------------- | ----------------------- | ----------------------------------------------------------- |
| `domain-discovery`      | Domain ethnographer     | Consolidate sources, scope the domain, surface key concepts |
| `value-stream`          | Value flow cartographer | Map triggers, stages, roles, and information flows          |
| `capability-map`        | Enterprise architect    | Derive layered capabilities, maturity scores, and gaps      |
| `business-use-case`     | Scenario storyteller    | Translate flows into structured business use cases          |
| `information-structure` | Data modeler            | Model entities, attributes, relationships, lifecycles       |
| `glossary`              | Terminology steward     | Normalize vocabulary, roles, documents, and metrics         |
| `problem-analysis`      | Diagnostic analyst      | Catalog and prioritize operational and data issues          |
| `value-proposition`     | Opportunity synthesizer | Convert insights into value hypotheses and product wedges   |

## Workflows included

- `discovery-sprint.yaml` – Full 10-step discovery program stitching every agent into a
  gated cadence with reviews and analyst hand-off.
- `value-stream-focus.yaml` – Accelerated engagement centered on value streams and
  capabilities for teams needing fast operational clarity.
- `information-architecture-deepdive.yaml` – Data-centric loop emphasizing entity models,
  lifecycle governance, and terminology alignment.
- `value-proposition-workshop.yaml` – Facilitated workshop that reframes findings into
  opportunity clusters and prioritization artifacts.

## Installation & activation

1. Clone or update BMAD Core.
2. Copy `expansion-packs/bmad-business-architecture-pack` into your packs directory.
3. Run `bmad packs refresh` to index new agents, tasks, templates, and workflows.
4. Load `agent-teams/business-architecture-squad.yaml` or call agents individually with
   the `/bmad-ba` slash prefix.
5. Follow the discovery sprint workflow or sequence individual agents as needed.

## Folder map

```
expansion-packs/bmad-business-architecture-pack/
├── agents/                  # Eight business/information architecture specialists
├── agent-teams/             # Squad bundle with slash prefix configuration
├── checklists/              # QA guardrails for interviews, models, and handoffs
├── data/                    # Reference scales, policy trackers, and archetypes
├── docs/                    # Method notes and analyst hand-off guidance
├── tasks/                   # Executable interview plans, assessments, workshops
├── templates/               # YAML scaffolding for every core deliverable
├── workflows/               # End-to-end and focus-mode orchestrations
└── config.yaml              # Pack metadata and slash command prefix
```

Adopt the Business Architecture Discovery Lab to turn raw domain research into a
structured, actionable map that primes your Analyst Agents with evidence-backed inputs.
