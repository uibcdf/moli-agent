# MOLI Agent

**MOLI Agent is the optional scientific reasoning and agency component of the MOLI Platform.**

It operates across **Scientific Context** — Sabueso, Praxis, and Nextia — and **MolSysSuite**, while preserving human authority, scientific provenance, and reproducibility.

MOLI Agent is not the MOLI Platform itself. Platform-level architecture is maintained in [uibcdf/moli](https://github.com/uibcdf/moli).

## Role

MOLI Agent may:

- assemble structured Scientific Context;
- interpret scientific intent;
- inspect and reason over DiscoveryProjects;
- propose Questions, Hypotheses, Strategies, and next actions;
- use Praxis Capabilities and Protocols;
- invoke DiscoveryEngine;
- delegate MolSysSuite-specialist work to MolSys-AI Agent;
- access MolSysSuite or authorized external scientific engines directly when appropriate;
- interpret Results, Observations, and Evidence.

MOLI Agent is optional. Human scientists can operate the same scientific infrastructure without it.

## Boundary

MOLI Agent does **not** own Sabueso knowledge, Praxis methodology, Nextia project state, MolSysSuite modeling semantics, or scientific truth.

> **MOLI proposal ≠ scientific certification.**

## Status

This repository currently defines the implementation boundary for MOLI Agent. Code should be added only after its contracts with Scientific Context, DiscoveryEngine, Praxis, MolSysSuite, and MolSys-AI Agent are sufficiently specified.

See the frozen [MOLI Platform Architecture 1.0](https://github.com/uibcdf/moli/tree/main/architecture_1.0).
