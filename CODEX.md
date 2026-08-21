# Codex plugins

This repository adds Codex-compatible manifests without changing the workflow logic already in the repository.

## Upstream source

Adapted from the open-source project [Today-Hbw/claude-code-dev-workflow](https://github.com/Today-Hbw/claude-code-dev-workflow).

The repository marketplace is `.agents/plugins/marketplace.json` and exposes:

- `forge-prd` — turns rough materials into a build-ready PRD.
- `dev-flow` — runs the full eight-step delivery workflow.
- `dev-flow-lite` — runs the four-step lightweight workflow.

Add this repository as a Codex marketplace, then install the plugin that matches the task.

## Contributors

- Today-Hbw
- Codex
