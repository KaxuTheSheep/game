# Slot Categories

*What can be installed, where, and how many.*

---

## Port vs Non-Port Augments

Not all augments use framework ports. See [[Augment System Overview]] for the full logic.

Structural augments — skeleton, joints, subdermal sectional armour — do not communicate with the framework and use no ports. Everything else does.

---

## Core Stack

Prerequisites for all other augmentation. See [[Core Stack]] for full detail.

| Slot | Count | Notes |
|---|---|---|
| Framework | 1 | Base layer, determines bandwidth ceiling and port count |
| MPU | 1 | Central processing, housed in chest cavity |
| Neural Interface | 1 | Brain to framework signal layer |
| Neural Network | 1 | Sub-slot of NI, swappable, preference item |
| Network Card | 1 | Optional but near universal, separate implant |

---

## Sensory

| Slot | Count | Notes |
|---|---|---|
| Eyes | 1 | Paired system, both eyes treated as one unit |
| Audio | 1 | Paired system, both ears treated as one unit |
| Input Sensors | Multiple | Additive, stack additional sensor types independently |

Eyes and audio are paired systems for signal symmetry reasons — the neural network interprets bilateral sensory data and mismatched units create processing conflicts.

---

## Limbs

| Slot | Count | Notes |
|---|---|---|
| Arms | 2 | One per arm, independent. Asymmetric builds are valid |
| Legs | 1 | Paired system, both legs treated as one unit |

### Arm Sub-Slots
Each arm slot contains sub-slots for integrated weapons or tools. These are separate decisions from the arm augment itself.

### Partial Replacements
Arm augments exist on a spectrum of invasiveness — hand only, forearm and below, full arm. These are types within the arm slot rather than separate categories. A hand-level augment is a conservative arm augment choice, not a different slot.

### Local Processing
Premium arm and leg augments contain local processors that handle repetitive physical tasks — recoil control, melee timing, blocking, movement correction — without routing through the MPU. This reduces latency for those tasks and lowers effective bandwidth draw compared to budget equivalents that route everything centrally.

---

## Structural

Structural augments use no ports and draw no bandwidth. They are passive physical enhancements.

| Slot | Count | Notes |
|---|---|---|
| Skeleton — Arms | 2 | One per arm section, prerequisite for heavy arm augments |
| Skeleton — Legs | 2 | One per leg section, prerequisite for heavy leg augments |
| Joints | Multiple | Connection points between sections, see below |

### Skeleton
Skeletal reinforcement serves two purposes:
- **Prerequisite** — heavy limb augments require skeletal reinforcement in that section to anchor properly under combat stress
- **Survivability** — raises the threshold before section-based status effects trigger, and increases resistance to severance even after a section reaches 0 HP

A player can invest in skeleton without limb augments for pure survivability purposes. A heavily armoured biological arm with reinforced bone is a legitimate build choice.

### Joints
Joint augments protect the connection points between body sections. Damaged joints affect movement speed, agility, and create weak points that bladed weapons can exploit for severance. Joint augments reduce these vulnerabilities and can extend range of motion and response speed beyond biological limits.

---

## Dermal

| Slot | Count | Notes |
|---|---|---|
| Sectional Armour | One per body section | Independent per section |
| Full Body Dermal | 1 | Whole body systems, all or nothing |

### Sectional Armour
Subdermal plating installed per body section. Each section is independent — players can prioritise coverage. Full body coverage is expensive and for most builds unnecessary.

Armour reduces incoming damage. Heavy armour provides severance resistance — making clean severance harder even at 0 HP section damage.

### Full Body Dermal
Systems that operate across the entire body surface. Camo skin is the primary example. One slot, covers everything, cannot be partially installed.

### Dermal vs Skeleton
Both serve survivability but differently:
- **Dermal** — reduces incoming damage before it registers
- **Skeleton** — structural integrity, affects how the body holds up after damage gets through

Stacking both on a section provides compounding survivability benefit. Each contribution remains distinct.

---

## Biological

| Slot | Count | Notes |
|---|---|---|
| Organ Augments | One per organ | Content defined in item database |

Organ augments split broadly into performance enhancement (augmented heart, lungs affecting stamina and exertion) and survival functions (filtration, synthetic food deficiency mitigation). Specific catalogue is content design, out of scope here.

---

## Section Reference

Body sections for HP and slot purposes:

- Head / Neck
- Upper Torso
- Lower Torso
- Upper Arm (x2)
- Lower Arm (x2)
- Upper Leg (x2)
- Lower Leg (x2)

Head and neck at 0 HP — instant death.
Critical torso sections at 0 HP — instant death.
Remaining sections at 0 HP — status effects and potential severance by bladed weapons.

---

*See [[Augment System Overview]], [[Bandwidth & Power]], [[Core Stack]], [[Framework Tiers]].*
