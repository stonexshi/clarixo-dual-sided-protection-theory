# CLARIXO Dual-Sided Protection Theory

**A dual-sided governance model for AI producers:**
- **LLM-side protection before execution**
- **User-side protection after behavior enters the real world**

---

## Why this theory exists

Most AI governance discussions are still fragmented.

Some focus on model safety.  
Some focus on runtime control.  
Some focus on auditability.  
Some focus on accountability, human oversight, or compliance.

All of these matter.

But in practice, organizations are often mixing together two very different infrastructure problems:

1. **How to keep AI behavior governable before it becomes a real-world consequence**
2. **How to preserve evidence, reviewability, and responsibility after that behavior enters the real world**

CLARIXO proposes that these are not one flat problem.

They are **two different protection sides**.

---

## Side 1: LLM-side protection

**LLM-side protection** refers to the control layer that operates **before consequential execution**.

Its role is to keep AI behavior:

- visible
- traceable
- reviewable
- interruptible
- governable

before the system crosses from runtime behavior into real-world consequence.

This side includes work such as:

- Runtime control
- Routing
- Fallback
- Guard behavior
- Review before execution
- Approval-bound continuation
- Execution governance

This side is not about making AI rigid through blunt restriction.

It is about preserving enough control, reversibility, and decision visibility before execution becomes difficult to redirect in a meaningful way.

---

## Side 2: User-side protection

**User-side protection** refers to the evidence and responsibility layer that operates **after AI behavior enters real workflows, real users, and real consequences**.

Its role is to preserve:

- evidence
- observation
- review context
- auditability
- structured case reading
- exportable review artifacts
- responsibility support

This side includes work such as:

- Evidence retention
- Observation surfaces
- Grouped review
- Audit Workspace
- Case export
- Review artifacts for downstream responsibility handling

This side is not mainly about runtime intervention.

It is about preventing AI behavior from disappearing into a responsibility vacuum after it has already affected the real world.

---

## Why both sides are necessary

If an organization only builds the first side, it may gain better runtime control but still lose the ability to explain, review, and defend what happened later.

If it only builds the second side, it may preserve evidence after the fact, but still fail to intervene before harmful or irreversible execution.

**LLM-side protection without user-side protection creates controllable systems with weak responsibility memory.**

**User-side protection without LLM-side protection creates reviewable systems with weak pre-execution control.**

CLARIXO argues that serious AI producers need both.

---

## The AI producer position

This model is built around the **AI producer**.

The AI producer sits between:

- model-side uncertainty
- runtime execution
- user-side consequence
- organizational accountability

That means the producer does not only need smarter models.

The producer needs infrastructure that can answer two different questions:

### Before execution
Can this behavior still be reviewed, redirected, paused, halted, or governed?

### After behavior enters the real world
Can this behavior still be reconstructed, reviewed, audited, and turned into responsibility-ready evidence?

That is the practical foundation of the dual-sided model.

---

## Current CLARIXO mapping

CLARIXO currently maps this theory into two sides.

### LLM-side
- Runtime
- AgentOps
- Approval Gateway

### User-side
- Evidence API
- Observation surfaces
- Audit Workspace

These modules do not represent a complete finished system in every dimension, but they already express the structural direction of the dual-sided model.

---

## Current status

CLARIXO’s current product direction already reflects this split:

- **Runtime / AgentOps / Approval Gateway** express the LLM-side governance path
- **Evidence API / Observation / Audit Workspace** express the user-side evidence and review path

This repository defines the methodology behind that structure.

---

## Core definition

**CLARIXO is dual-sided infrastructure for AI producers:**
- **LLM-side protection before execution**
- **User-side protection after behavior enters the real world**

---

## Notes on novelty

To our knowledge, current AI governance discussions remain fragmented across runtime control, auditability, accountability, observability, and compliance.

CLARIXO proposes a **dual-sided protection model** that organizes these concerns into:

- an **LLM-side protection problem before execution**
- a **user-side protection problem after behavior enters the real world**

The novelty of this framework is not that each individual concern is entirely new, but that they are restructured into a unified two-sided infrastructure model centered on the AI producer.

---

## Next documents

Planned extensions for this repository:

- `docs/foundation.md` — deeper methodological foundation
- `docs/current-state.md` — current CLARIXO product mapping and capability status
- `docs/anti-patterns.md` — common governance mistakes caused by one-sided thinking
- diagrams for LLM-side / user-side structure
