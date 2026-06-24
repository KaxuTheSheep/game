# Core Stack

*The prerequisite layer. Nothing else works without these.*

---

## Overview

The core stack is the set of augments required before any other augmentation is possible. They are not optional for augmented builds — they are the infrastructure everything else runs on.

Players start with a base SOMA framework. The rest of the core stack must be acquired, though early faction alignment or NPC relationships may provide access quickly.

---

## Components

### Framework
The base integration layer. Determines bandwidth ceiling, port count, battery capacity, and recharge rate. Every other augment connects through it.

Choosing a framework is the most significant augment decision a player makes. It sets the ceiling for everything that follows. See [[Framework Tiers]] for full detail.

**Prerequisites:** None. This is the first augment.

---

### MPU — Multiprocessing Unit
The central processing hardware. Handles all computational work across the augment system:
- CPU — general processing and system coordination
- GPU — visual and spatial processing
- NPU — neural network operations
- TPU — network and connectivity processing
- Cache and high bandwidth memory serving each processor

Housed in the chest cavity for thermal management and surgical access reasons. Signal travel between MPU and brain-adjacent augments has a measurable round trip delay — addressed at the premium end by local processing in limb augments rather than by moving the MPU itself.

**Prerequisites:** Framework installed.

---

### Neural Interface (NI)
The brain to framework signal layer. Reads brain activity and converts it to statistical data that the Neural Network can interpret. Also receives processed signals back from the Neural Network and translates them into neural information the brain can understand.

The NI is the point where the augment system becomes personal — it is literally reading and writing to the brain. Quality and installation precision here affects the entire system's fidelity.

**Prerequisites:** Framework, MPU.

**Sub-slot:** Neural Network.

---

### Neural Network (NN)
A highly specialised AI running on the NPU. Takes the statistical brain activity data from the NI and translates it to machine code the system can act on. Runs the reverse process for return signals.

The NN is the only core stack component that is a genuine preference item. Different manufacturers produce NNs with different translation philosophies — response prioritisation, signal interpretation weighting, latency profiles. Experienced augment users often swap the default NN for one that suits their cognitive style.

Sits as a sub-slot of the NI — dependent on it, but independently replaceable.

**Prerequisites:** Framework, MPU, NI.

---

### Network Card (NC)
Connects the augment system to external networks. Contains its own instruction set and a local mini-processor that aggregates data from multiple antenna distributed across the body, then routes through the TPU.

Technically optional — the rest of the core stack functions without it. In practice near-universal because disconnection from network access is a significant functional and social disadvantage in New Halcyon.

Certain builds — particularly those concerned with surveillance or operating in areas with hostile network environments — may deliberately omit or disable the NC. A player without a network card is harder to track and harder to hack.

**Prerequisites:** Framework, MPU.

---

## Dependency Summary

```
Framework
└── MPU
    ├── Neural Interface
    │   └── Neural Network (sub-slot, swappable)
    └── Network Card (optional, near-universal)
```

Everything outside the core stack requires the relevant core stack component to function. An eye augment sending visual data requires the NI and NN to process it. A network-dependent augment requires the NC. A computationally demanding augment requires sufficient MPU capacity.

---

*See [[Augment System Overview]], [[Framework Tiers]], [[Bandwidth & Power]], [[Slot Categories]].*
