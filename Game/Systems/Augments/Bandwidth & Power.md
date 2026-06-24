# Bandwidth & Power

*Two resource systems operating at different time scales. Bandwidth is moment to moment. Power is session to session.*

---

## Bandwidth

Bandwidth represents the processing load on the framework at any given moment. Every active augment draws bandwidth. The framework has a ceiling determined by its tier and model.

### Usage States

**0–100% — Normal Operation**
System functions as intended. All augments perform at full capacity.

**100–120% — Soft Overload**
- Latency increases across augment responses
- Non-critical modules begin to be deprioritised by the priority system
- Noticeable but manageable degradation

**120–150% — Saturation State**
Selective degradation begins:
- Frame skipping in perception augments
- Delayed motor execution in limb augments
- NI compression artifacts appear — sensory information becomes unreliable

**150%+ — Critical Failure**
Hardware equivalent of a CPU that cannot handle its clock cycles. Thermal shutdown, risk of permanent hardware damage, potential loss of augment function. Avoid at all costs.

---

## Idle vs Peak Draw

Augments do not draw their maximum bandwidth at all times. Usage varies by activity:

- A network card on a non-hacker build idles near 0%
- Combat augments spike during use and return to idle between engagements
- Passive augments like subdermal armour draw nothing — they are not port connected

Players should understand their build's bandwidth profile across contexts, not just its theoretical maximum. A build that sits at 80% in combat may peak at 130% when two augments spike simultaneously.

---

## Sleep and Wake

Augments can enter a sleep state — drawing zero bandwidth but losing immediate availability.

- **Automatic in combat** — the priority system manages sleep and wake without player input
- **Manual outside combat** — players can sleep augments deliberately to free bandwidth

### Priority System

Each augment has a priority value. By default this is preset. Players may reorder priorities if needed.

Under bandwidth pressure the system automatically:
1. Deprioritises lower priority augments first
2. Puts non-critical augments to sleep if saturation approaches
3. Wakes augments when bandwidth allows and the augment is needed

### Wake Delay

Augments coming out of sleep have a wake delay before they are functional. This varies by:
- Augment type — some categories wake faster than others by nature
- Model and tier — within the same augment type, different models and tiers have different wake speeds. A faster waking augment may be preferable to a higher performing one for bandwidth-sensitive builds even if raw performance is lower.

Players will not be caught by wake delay unexpectedly — augment descriptions show wake delay values explicitly.

---

## Power

Power is the framework's battery charge. It drains during active use and must be replenished.

### Drain and Failure

Power drains faster under heavy augment use. Running out is not a clean game over — it is a situational hazard.

Collapsing from power failure in a safe location is an inconvenience. Collapsing in a forgotten district or hostile area creates real danger:
- Robbery while incapacitated
- Kidnapping with augments stripped
- Requiring recovery of items from wherever you fell

### Recharging

**Wireless sleep recharge** — the SOMA framework recharges passively during sleep. Full recharge, normal game rhythm, no cost.

**Wired fast charge** — connecting to a power source skips one to two in-game hours. Faster but requires being stationary and connected. A vulnerability in unsafe locations.

Charging infrastructure quality and safety varies significantly by district.

---

*See [[Augment System Overview]], [[Slot Categories]], [[Framework Tiers]].*
