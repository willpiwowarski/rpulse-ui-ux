# rPulse UI/UX

Functional and visual contracts for the rPulse Vue 3 application.

This repo does not run. It defines what the application must look like and do,
in a form both engineers and coding agents can follow. Application code lives
in the rPulse app repo; this repo is the source of truth for the contract.

## Structure

| Path | Purpose |
|---|---|
| `Purpose.md` | Repo purpose and high-level application vision (SRD) |
| `AGENTS.md` | Entry point coding agents read first |
| `agents/` | Agent identity definitions |
| `index-of-terms/` | Shared vocabulary for every element, field, and action |
| `shell/` | The static application shell, identical across apps |
| `visual-elements-library/` | Reusable buttons, icons, logos |
| `mock-screens/` | Proposed screens as .png references |
| `complete-screens/` | Approved screens — locked, never refactored |
| `mock-data/` | Schema-coherent sample data |
| `rpulse/` | Application main folder |
