# Conceptual Architecture

Apver is currently defined as a concept, not as a committed implementation.

Its conceptual structure has four layers:

1. **Intent Layer** — a person describes the outcome they want.
2. **Workflow Layer** — Apver plans, generates, or installs independent workflow modules.
3. **Agent Execution Layer** — replaceable Agents, models, and runtimes execute workflows.
4. **Memory Layer** — layered, document-based memory preserves context in a readable and portable form.

Workflow modules are intended to be installable and distributable independently of the Apver main program. A future marketplace may support community development and free trading of these modules.

The architecture is local-first: core computation should not strongly depend on a platform cloud. This document records the architectural direction only and does not select technologies or define the main program.
