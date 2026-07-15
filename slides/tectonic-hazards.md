<!-- deck
title: Chapter 2: Tectonic Hazards—Processes, Warning, and Risk
ratio: 16:9
author: Yu Wang
footer: CC BY-SA 4.0

theme: paper
-->

<!-- slide template=title -->
# Chapter 2: Tectonic Hazards
## Processes, warning, and risk 

<!-- slide 2col -->
## Learning objectives
<!-- @left -->
- {{sp[info] 2.1a–b}} Explain fault loading and rupture
- {{sp[info] 2.2a–b}} Read waves, magnitude, and intensity
- {{sp[info] 2.3a–b}} Connect volcano processes and signals
<!-- @right -->
- {{sp[info] 2.4a–b}} Explain tsunami generation and shoaling
- {{sp[info] 2.5a–b}} Evaluate warning and risk reduction

:::success
**Method:** process → observation → consequence → decision
:::

<!-- slide template=outline -->
# What we’ll cover
- 2.1 Fault loading and earthquake rupture
- 2.2 Seismic observations and uneven shaking
- 2.3 Volcano processes and cascading hazards
- 2.4 Tsunami generation and coastal transformation
- 2.5 Monitoring, warning, and risk reduction

<!-- slide -->
## Chapter logic
{{mermaid
flowchart LR
  A[Boundary process] --> B[Event]
  B --> C[Signal]
  B --> D[Hazard]
  C --> E[Warning]
  D --> F[Exposure + vulnerability]
  E --> G[Action]
  F --> H[Consequences]
  G --> H
}}

**Visual description:** Boundary processes create events, signals, and hazards; warning can support action, while exposure and vulnerability shape consequences.

<!-- slide template=section v=2 -->
# 2.1 Fault loading and rupture
## Slow motion, fast event

<!-- slide main-side 3/2 -->
## Elastic rebound is a causal cycle
<!-- @main -->
- Plate motion loads a region
- Friction can lock part of a fault
- Elastic strain accumulates
- Rupture propagates; waves radiate

:::warning
**Not a clock:** recurrence intervals and rupture sizes vary.
:::
<!-- @side -->
![Four-stage elastic rebound cycle](https://alembic.orz.how/d/doc-nclbcj0om1ty =480x)

<!-- slide 3col -->
## Motion predicts fault style
<!-- @left -->
{{sp[blue] Extension}}

**Normal fault**

Blocks move apart
<!-- @mid -->
{{sp[warning] Shortening}}

**Reverse / thrust**

Blocks approach
<!-- @right -->
{{sp[success] Lateral shear}}

**Strike-slip**

Blocks slide past

<!-- slide main-side -->
## Surface rupture is one observation
<!-- @main -->
![Road offset by the 2019 Ridgecrest earthquake](https://alembic.orz.how/d/doc-v387dcsi4zm6 =600x)
<!-- @side -->
- Visible offset records displacement
- Strong shaking extends beyond the break
- Many ruptures do not reach the surface
- Photo: Ken Hudnut, USGS; public domain

<!-- slide step -->
## Example — oblique motion
**Question:** Motion is 24 mm/yr toward a boundary and 10 mm/yr parallel. Is “pure thrust” adequate?

1. Toward motion → shortening dominates.
2. Parallel motion → lateral shear also matters.
3. Expect reverse/thrust plus strike-slip partitioning or ==oblique slip==.

<!-- slide template=section v=3 -->
# 2.2 Seismic observations
## One event, uneven shaking

<!-- slide 2col -->
## Hypocenter is not epicenter
<!-- @left -->
{{sp[warning] Hypocenter}}

- Initial rupture point
- Located within Earth
- Rupture spreads beyond it
<!-- @right -->
{{sp[info] Epicenter}}

- Surface point directly above
- Useful map reference
- Not the whole rupture area

<!-- slide -->
## Information can outrun stronger shaking
{{mermaid
sequenceDiagram
  participant R as Rupture
  participant S as Sensor
  participant C as Communication
  participant U as Distant user
  R->>S: P wave
  S->>C: Estimate
  C->>U: Alert
  R-->>U: Stronger shaking later
}}

**Visual description:** A sensor may detect the faster P wave and send an electronic alert before stronger shaking reaches a more distant user.

<!-- slide 2col -->
## Magnitude versus intensity
<!-- @left -->
**Magnitude**

- One source-size value
- Logarithmic scale
- Moment relates area, slip, rigidity
<!-- @right -->
**Intensity**

- Varies from place to place
- Depends on distance and wave path
- Modified by geology and structures

<!-- slide step -->
## Example — logarithmic source energy
**Question:** Approximately how does magnitude 7 compare with magnitude 5 if each unit is about 32 times more energy?

1. Difference = 2 magnitude units.
2. Ratio $\approx32^2=1024$.
3. Source energy is about ==one thousand times greater==.
4. Damage does not scale by the same fixed ratio.

<!-- slide template=section v=4 -->
# 2.3 Volcano processes
## One volcano, several pathways

<!-- slide 3col -->
## Where magma forms
<!-- @left -->
**Divergence**

Decompression melting
<!-- @mid -->
**Subduction**

Volatiles promote melting above slab
<!-- @right -->
**Hotspot**

Volcanism within a plate

:::info
Setting constrains possibilities; it does not uniquely predict eruption style.
:::

<!-- slide main-side 3/2 -->
## An eruption couples Earth and atmosphere
<!-- @main -->
![Atmospheric plume from the 2022 Hunga Tonga eruption](https://alembic.orz.how/d/doc-43h3me40z8uc =620x)
<!-- @side -->
- Plumes transport ash and gases
- Wind changes where material travels
- A dramatic image is not a template for every eruption
- NASA / Kayla Barron; public domain

<!-- slide quad -->
## Hazards need different actions
<!-- @tl -->
**Lava**

Topography and exclusion zones
<!-- @tr -->
**Ash / tephra**

Wind, roofs, aviation, breathing
<!-- @bl -->
**Pyroclastic current**

Fast, hot ground-hugging flow
<!-- @br -->
**Lahar**

Water-rich debris follows valleys

<!-- slide 2col -->
## Monitor a pattern, not one signal
<!-- @left -->
- Earthquake locations and types
- Ground deformation
- Gas composition or flux
- Thermal and visual change
<!-- @right -->
:::success
**Stronger inference:** independent changes agree with a plausible mechanism.
:::

:::warning
No single signal proves an eruption time or style.
:::

<!-- slide step -->
## Example — changing volcano
**Question:** Shallow seismicity, outward deformation, and gas output all increase. Does eruption tomorrow follow?

1. Multiple streams indicate a changing system.
2. Change may justify preparation or an alert-level review.
3. Timing and outcome remain uncertain.
4. Report ==observations + alternatives + action thresholds==.

<!-- slide template=section v=5 -->
# 2.4 Tsunami systems
## Rapid water displacement to coastal inundation

<!-- slide 2col -->
## Not every offshore earthquake qualifies
<!-- @left -->
**Source requirement**

- Rapid displacement
- Large water volume
- Geometry and vertical motion matter
<!-- @right -->
**Other sources**

- Landslides
- Volcanic processes
- Other rapid displacement events

<!-- slide -->
## The coast transforms the wave
![Tsunami propagation and shoaling from deep ocean to coast](https://alembic.orz.how/d/doc-cnosomim7i4w =920x)

- Deep water: long, low, fast
- Shallow water: slower, shorter wavelength, potentially greater run-up

<!-- slide 2col 3/2 -->
## Wave speed depends on depth
<!-- @left -->
$$c=\sqrt{gd}$$

For $g\approx10\ \text{m/s}^2$ and $d=5000\ \text{m}$:

$$c\approx224\ \text{m/s}\approx806\ \text{km/h}$$
<!-- @right -->
:::warning
This is an approximate deep-ocean speed—not a local run-up forecast.
:::

<!-- slide step -->
## Example — unsafe waiting rule
**Claim:** “I will evacuate only if the sea withdraws.”

1. A crest may arrive before a trough.
2. Withdrawal is not guaranteed.
3. Waiting wastes time after strong or long shaking.
4. Follow natural and official warnings; ==move promptly==.
5. First wave need not be largest.

<!-- slide template=section v=6 -->
# 2.5 Warning and risk
## Detection is only one link

<!-- slide quad -->
## Four questions, four terms
<!-- @tl -->
**Monitoring**

What is changing now?
<!-- @tr -->
**Forecasting**

How likely in a window?
<!-- @bl -->
**Prediction**

What future time, place, size?
<!-- @br -->
**Early warning**

What action after detection?

<!-- slide -->
## Hazard is not disaster risk
![Flow from tectonic process through hazard, exposure, vulnerability, and risk reduction](https://alembic.orz.how/d/doc-zvqu892i85da =900x)

<!-- slide 2col -->
## A warning system is human + technical
<!-- @left -->
- Sensors and resilient power
- Rapid analysis
- Redundant communication
- Accessible, multilingual messages
<!-- @right -->
- Trusted institutions
- Practiced protective action
- Feasible evacuation or shelter
- Feedback after false or missed alerts

<!-- slide step -->
## Example — sensors without access
**Scenario:** Fast sensors, one-language messages, no drills, and inaccessible routes.

1. Detection improved.
2. Communication excludes some users.
3. Protective action is not feasible for everyone.
4. Complete the chain with ==accessibility, redundancy, drills, and route redesign==.

<!-- slide template=closing -->
# From process to protection
- Plate motion explains where many hazards begin
- Observations constrain—but do not erase—uncertainty
- Source size differs from local consequences
- Risk reduction links science, infrastructure, communication, and action

## Source Adaptation Note
Adapted and reorganized for this teaching resource. Sources: Wikipedia contributors, [Plate tectonics](https://en.wikipedia.org/wiki/Plate_tectonics), [Lithosphere](https://en.wikipedia.org/wiki/Lithosphere), [Seafloor spreading](https://en.wikipedia.org/wiki/Seafloor_spreading), [Paleomagnetism](https://en.wikipedia.org/wiki/Paleomagnetism), [Wilson Cycle](https://en.wikipedia.org/wiki/Wilson_Cycle), [Earthquake](https://en.wikipedia.org/wiki/Earthquake), [Volcano](https://en.wikipedia.org/wiki/Volcano), [Tsunami](https://en.wikipedia.org/wiki/Tsunami), and [Earthquake early warning system](https://en.wikipedia.org/wiki/Earthquake_warning_system), licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).