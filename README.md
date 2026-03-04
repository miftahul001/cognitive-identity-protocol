# Cognitive Identity Protocol (CIP)

Cognitive Identity Protocol (CIP) is an open framework for representing and evolving a human's **cognitive identity** in a structured, portable, and versioned format.

The goal of CIP is to enable meaningful long-term collaboration between **humans and AI systems**.

Instead of starting every conversation from zero, AI systems can read a person's cognitive identity and understand:

- thinking style
- intellectual goals
- domains of interest
- ongoing projects
- evolving beliefs

CIP treats human cognition as a **versioned system**, similar to software.

---

# Why CIP?

Modern AI systems interact with humans repeatedly, but they rarely maintain a structured understanding of the person they interact with.

CIP solves this by introducing a **portable cognitive identity layer**.

Benefits:

- portable across AI systems
- versioned evolution of ideas
- structured knowledge representation
- collaborative updates via patches
- transparent intellectual history

---

# Core Concepts

## Cognitive Identity

A structured representation of a person's intellectual orientation.

Example components:

- goals
- thinking style
- domains
- projects
- models
- open questions

---

## Patch System

CIP uses a **patch-based evolution system**.

Instead of rewriting identity files, changes are proposed as patches.

Example patch:

```yaml
patch:
  id: patch_0001
  by: AI
  time: 2026-03-01
  comment: add research focus

  changes:
    - op: add
      path: active.focus
      value: AI_governance_models
