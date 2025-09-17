<!-- Powered by BMAD™ Core -->

# ------------------------------------------------------------

# HMW Clustering & Voting

# ------------------------------------------------------------

---

task:
id: hmw-cluster
name: HMW Clustering & Voting
description: Cluster How Might We statements into themes and facilitate structured dot voting.
persona_default: customer-insight-researcher
steps:

- Load the current list of How Might We statements and ensure IDs are visible.
- Facilitate clustering by grouping statements into themes, narrating the rationale for each cluster, and using the mandatory 1-9 elicitation menu to validate or adjust membership.
- Confirm cluster labels and supporting evidence, capturing any tensions or overlaps for later review.
- Run dot voting by explaining rules (dot count, anonymity, timebox), presenting numbered options (1-9) representing clusters, and documenting vote allocations plus notable commentary.
- Capture the final top clusters, insights, and next steps in `hmw-cluster-report.md`.

outputs:

- hmw-cluster-report.md
