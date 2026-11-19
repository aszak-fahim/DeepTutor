Failed to create stream fd: Operation not permitted
Failed to create stream fd: Operation not permitted
Failed to create stream fd: Operation not permitted
# Changelog

This file records the fork's starting point and changes made in this checkout. Upstream release history is summarized to make the inherited baseline clear; consult [upstream releases](https://github.com/HKUDS/DeepTutor/releases) for the complete record. Dates use the upstream release dates.

## Fork changes

### 2026-11-20 — Documentation foundation (unreleased)

- Added project overview, setup, environment configuration, and basic usage guidance.
- Documented the current architecture, persistence layout, API routing, and initial AI Teacher direction.
- Added fork contribution, security, license-summary, and changelog policies.
- No runtime code or behavior changed.

## Inherited upstream baseline

### v1.7.3 — 2026-11-16

- Added flexible reading and book editing, richer search and agent connections, and clearer learning records.
- Improved model streaming and desktop upgrades.

### v1.7.2 — 2026-11-06

- Added complete desktop downloads, selected-text speech, easier model setup, Korean interface preview, and NVIDIA NIM embeddings.
- Improved mastery, retrieval, and update reliability.

### v1.7.1 — 2026-11-01

- Added desktop previews, broader localization, password changes, checked video lessons, Anki/calendar exports, and additional providers.
- Included broad reliability improvements.

### v1.7.0 — 2026-10-28

- Introduced modular installation, a refreshed learning workspace, block notebooks, narrated video lessons, and resumable embedding checkpoints.
- Improved tutoring reliability and reorganized optional features as independently packaged modules.

### v1.6.15 — 2026-10-19

- Upstream release analyzed by the planning PDF and its proposed fork baseline.
- Included reviewed learning-path changes, grouped assessments, bounded tutoring memory, chat recovery, parsing improvements, retrieval comparisons, and native Gemini speech.

## Breaking changes

- The fork has not introduced a breaking change as of 2026-11-20.
- Upstream `v1.7.0` changed installation/package modularity compared with `v1.6.15`. Review the matching migration guide before moving between those baselines; do not assume commands or extension contracts are identical.
