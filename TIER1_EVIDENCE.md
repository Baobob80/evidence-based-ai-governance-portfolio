# Tier 1 Evidence v1.0

## Purpose

This document identifies the strongest evidence artifacts in the portfolio.

Tier 1 evidence is not a complete archive.

It is the minimum evidence set a reviewer should inspect first.

---

# 1. Controlled Email Intake Engine (CEIE)

## Evidence Type

Governance Architecture Repository

## Tier 1 Evidence

### Runtime Evidence Review 001

Path:

```text
docs/reviews/RUNTIME_EVIDENCE_REVIEW_001.md
```

Reason:

Demonstrates that the project moved beyond architecture description into runtime evidence review.

---

### Investigation Phase 001

Path:

```text
docs/reviews/INVESTIGATION_PHASE_001.md
```

Reason:

Demonstrates structured investigation discipline and root-cause oriented review.

---

### ERA 3 Readiness Gate

Path:

```text
docs/ERA3_READINESS_GATE.md
```

Reason:

Demonstrates governance restraint: architecture evolution is not allowed without repeated evidence of structural insufficiency.

---

### Pressure Observation 003

Path:

```text
docs/pressure/PRESSURE_OBSERVATION_003.md
```

Reason:

Represents pressure-based observation evidence under controlled governance validation.

---

# 2. Autonomy Readiness Checker (ARC)

## Evidence Type

Executable Governance Gate

## Tier 1 Evidence

### Deterministic Rule Engine

Paths:

```text
src/engine/evaluate.ts
src/engine/rules.ts
src/engine/types.ts
```

Reason:

Demonstrates executable rule-based governance evaluation rather than declarative governance language.

---

### Explainability Layer

Path:

```text
src/engine/explain.ts
```

Reason:

Demonstrates that evaluation output can be explained rather than only produced.

---

### Schema Boundary

Paths:

```text
src/schema/input.ts
src/schema/output.ts
```

Reason:

Defines explicit input and output boundaries for governance evaluation.

---

### Contract and Snapshot Tests

Paths:

```text
tests/api.contract.test.ts
tests/__snapshots__/api.contract.test.ts.snap
```

Reason:

Demonstrates API contract discipline and output stability.

---

### Regression and Fixture Evidence

Paths:

```text
fixtures/fixtures.json
fixtures/expected.json
tests/fixtures.test.ts
tests/engine.test.ts
```

Reason:

Demonstrates controlled input/output cases and repeatable evaluation behavior.

---

### Release / Hardening Signal

Evidence:

```text
v0.2.0 — deterministic engine hardened
```

Related commits:

```text
3c8db3d release: v0.2.0 – deterministic engine hardened
69b76cf test(hardening): strict schema + contract version + api snapshot
d20ca0e test(hardening): commit remaining snapshots
```

Reason:

Demonstrates a hardening and release checkpoint rather than a loose prototype state.

---

# 3. IPC Research Series

## Evidence Type

Public Governance Research

## Tier 1 Evidence

### IPC5 — Admissibility & Execution Boundary

Reason:

Introduces the distinction between correct decisions and admissible execution.

---

### IPC8 — Operational Momentum vs Authority

Reason:

Frames how operational momentum can begin to substitute formal authority signals.

---

### IPC9 — Declared Control vs Demonstrated Control

Reason:

Formalizes one of the strongest portfolio principles:

```text
The existence of a control is documentation.
The exercise of a control is evidence.
```

---

# 4. External Validation

## Evidence Type

Governance and Architecture Dialogue

## Tier 1 Evidence

### Piotr Reder

Theme:

Operational governance, AI Act, evidence, enforcement.

Reason:

Provides strong bridge between governance architecture and operational / regulatory reality.

---

### Emanuel Celano

Theme:

Governance observability, evidentiary continuity, decision boundaries.

Reason:

Founder-level validation of the distinction between governance declaration and governance observability.

---

### Oleksandr Shuliak

Theme:

Evaluation is not authority, accountability migration, responsibility preservation.

Reason:

Strengthens the portfolio’s authority-boundary and accountability-preservation themes.

---

### Kari Hyötylä

Theme:

Validity, admissibility, runtime enforcement.

Reason:

Strong external validation of the execution-boundary and admissibility framing.

---

### Ricardo Muro

Theme:

Execution boundary, state binding, system integrity.

Reason:

Deep architectural convergence around decision-to-state binding and system integrity.

---

### Jeremy Karrick

Theme:

Runtime governance, degradation, fail-closed admissibility, proof-carrying systems.

Reason:

High-signal technical governance discussion around runtime admissibility and proof discipline.

---

# 5. Publications and Contributions

## The AI Misalignment Problem

Evidence Type:

External publication contribution

Reason:

Demonstrates participation in governance-related public discourse beyond project repositories.

---

## Global AI Observatory / AI Barometer Contribution

Evidence Type:

External governance contribution

Reason:

Demonstrates movement from LinkedIn governance research into an external editorial governance channel.

---

# Tier 1 Summary

The portfolio’s strongest evidence is concentrated in five categories:

1. Runtime governance architecture
2. Executable governance gates
3. Public governance research
4. External expert validation
5. External publication / contribution record

This Tier 1 evidence set should be reviewed before lower-priority supporting materials.
