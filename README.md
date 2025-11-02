# Deterministic Narrative Game System

A framework for building choice-driven narrative games where outcomes follow **logic**, not randomness.
The system emphasizes **consistent world rules**, **coherent NPC behavior**, and **consequences that persist** across the course of play.

---

## Overview

This system models a world that:

* Is **fully constructed before play** (fixed map, factions, goals).
* Tracks **time and opportunity cost** through a Master Clock.
* Represents NPCs as agents with **clear motives and priorities**.
* Resolves actions through **cause and effect**, not dice rolls.

Player success depends on **observation, decision-making, and inference** rather than chance.

---

## Core Structures

### World Model

* The environment is static in structure but dynamic in state.
* Exploration reveals information; it does not alter topology.
* Social, legal, and cultural norms apply until superseded by necessity.

### NPC Logic

NPCs are defined by:

* **Goals**
* **Constraints**
* **Risk tolerance**
* **Memory of interactions**

Their behavior changes when pressures change, but it remains internally consistent.

### Time and Consequences

* Actions consume time.
* Time affects opportunity, resource availability, and situational stability.
* Delays shift the state of the world even without direct player involvement.

---

## Conflict Engines

### Shifting Allegiances

A network-based social system where:

* Supporting one character may undermine trust with another.
* Alliances form and erode based on observed behavior.
* Loyalty is conditional and context-dependent.

### Nemesis Model (Adversarial Intelligence)

A design pattern for a single, high-agency antagonist who:

* Observes the player's decisions
* Identifies behavioral patterns
* Responds by exploiting predictable weaknesses

No randomness is used; pressure escalates logically.

---

## Realism Guidelines

Clarifications included to prevent common misunderstandings found in fiction and games:

* **Armor:** Plate allows mobility; disabling an armored target relies on grappling and directed thrusts.
* **Cover:** Drywall and light materials do not meaningfully stop projectiles; denser layered barriers matter.
* **Injury:** Outcomes follow real trauma progression (blood loss, fatigue, impairment).
* **Weapons:** Small blades are close-range and decisive, not secondary or cinematic props.

The goal is internal coherence rather than simulationism for its own sake.

---

## Example Outcome Chain (Illustrative)

**Decision:** The player chooses to aid one character during a crisis.

**Immediate Result:** That character becomes more cooperative.

**Secondary Effect:** Another character perceives the act as neglect or favoritism.

**Long-Term Outcome:** Social support shifts; resource access and trust networks realign.

The system does not create these effects dynamically; they follow from predetermined character motives and world conditions.

---

## Intended Applications

* Narrative games with **persistent state**
* Tabletop or solo roleplay where **logic replaces dice**
* Fiction prototypes requiring **consistent character behavior**

---

## Full Rules

See the full design document in this repository for detailed mechanics, structures, and scenario examples.

