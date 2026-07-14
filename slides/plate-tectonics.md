<!-- deck
title: Chapter 1: Plate Tectonics
ratio: 16:9
author: Yu Wang
footer: CC BY-SA 4.0
-->

<!-- slide template=title -->
# Chapter 1: Plate Tectonics
## From moving plates to a testable Earth system

<!-- slide 2col -->
## Learning objectives
<!-- @left -->
- {{sp[info] 1.1a}} Separate mechanical and compositional layers
- {{sp[info] 1.2a}} Predict geology from relative motion
- {{sp[info] 1.3a}} Trace oceanic-lithosphere recycling
<!-- @right -->
- {{sp[info] 1.4a}} Test spreading with magnetism and age
- {{sp[info] 1.5a}} Sequence and qualify a Wilson cycle

:::success
**Method:** model → prediction → observation → revision
:::

<!-- slide template=outline -->
# What we'll cover
- 1.1 Mechanical layers and moving plates
- 1.2 Boundary kinematics and surface expression
- 1.3 Creation, cooling, and recycling
- 1.4 Magnetic and age evidence
- 1.5 Ocean-basin life cycles

<!-- slide -->
## Chapter logic
{{mermaid
flowchart LR
  A[Mechanical layers] --> B[Plate motion]
  B --> C[Boundary processes]
  C --> D[Rock and geophysical records]
  D --> E[Reconstructions]
  E -. test .-> B
}}

**Visual description:** Mechanical structure permits motion, motion produces boundary processes, processes leave records, and records test reconstructions.

<!-- slide template=section v=2 -->
# 1.1 Mechanical layers
## What moves—and over what?

<!-- slide main-side 3/2 -->
## Two classifications, two questions
<!-- @main -->
- **Crust / mantle** → composition and mineralogy
- **Lithosphere / asthenosphere** → mechanical response
- Lithosphere = crust + cool uppermost mantle
- Asthenosphere = hotter, weaker upper mantle

:::warning
**Not a magma ocean:** the asthenosphere is mostly solid.
:::
<!-- @side -->
![Cross-section of rigid lithospheric plates above a weaker asthenosphere](https://alembic.orz.how/d/doc-0unfg3tjdxd3 =420x)

<!-- slide 2col -->
## Solid rock can still flow
<!-- @left -->
{{sp[blue] Short timescale}}

- Elastic response
- Brittle failure
- Earthquake rupture
<!-- @right -->
{{sp[success] Geologic timescale}}

- Viscous deformation
- Plastic strain
- Mantle convection

:::info
Behavior depends on temperature, pressure, stress, and time.
:::

<!-- slide step -->
## Example — name the boundary
**Question:** A boundary lies within the upper mantle. Rock above stays rigid for long periods; rock below deforms more readily. Must it be the crust–mantle boundary?

1. The observation concerns **mechanical behavior**.
2. The crust–mantle boundary is compositional.
3. Therefore it supports the ==lithosphere–asthenosphere boundary==.

<!-- slide template=section v=3 -->
# 1.2 Boundary kinematics
## Start with the arrows

<!-- slide -->
## Three idealized motions
![Three panels showing divergent, convergent, and transform plate-boundary motion](https://alembic.orz.how/d/doc-7udi8vgqz1hh =840x)

- Apart → create oceanic lithosphere
- Together → subduct or collide
- Lateral → transfer material; store elastic strain

<!-- slide main-side -->
## Divergence in the field
<!-- @main -->
![Almannagjá rift walls at Þingvellir in Iceland](https://alembic.orz.how/d/doc-yfkjdi3u2d6s =590x)
<!-- @side -->
- Faulting records extension
- Iceland exposes a broad ridge zone
- Field evidence must be combined with mapping, GPS, ages, and earthquakes

:::info
Photo: Olga Ernst, CC BY-SA 4.0.
:::

<!-- slide 2col -->
## Convergence has two endmembers
<!-- @left -->
**Oceanic subduction**

- Dense slab sinks
- Trench + dipping earthquake zone
- Fluids aid melting above slab
- Volcanic arc develops
<!-- @right -->
**Continental collision**

- Buoyant crust resists deep sinking
- Shortening thickens crust
- Fold-thrust belts and mountains
- Suture marks a vanished ocean

<!-- slide step -->
## Example — oblique convergence
**Question:** Relative velocity is 30 mm/yr toward a boundary and 18 mm/yr parallel to it. How should the boundary be described?

1. Toward-boundary motion is larger → **convergence dominates**.
2. Parallel motion is substantial → lateral shear matters.
3. Expect ==oblique convergence== with partitioned shortening and strike-slip motion.

<!-- slide template=section v=4 -->
# 1.3 Ridge-to-trench recycling
## Oceanic lithosphere has a life history

<!-- slide main-side 3/2 -->
## A product of submarine eruption
<!-- @main -->
![Museum specimen of pillow lava from Loihi Seamount](https://alembic.orz.how/d/doc-ye3pk0v8wwge =570x)
<!-- @side -->
- This specimen formed when basalt erupted into water
- Rapid cooling builds rounded pillows
- Pillow lava is a product—not a complete ridge

:::info
Photo: Ed Shiinoki, NPS; public domain.
:::

<!-- slide -->
## Cooling changes oceanic lithosphere
{{mermaid
flowchart LR
  A[Hot + thin at ridge] --> B[Moves outward]
  B --> C[Cools conductively]
  C --> D[Thickens + densifies]
  D --> E[Can subduct]
}}

**Visual description:** Oceanic lithosphere starts hot and thin, cools and thickens away from the ridge, then may become dense enough to descend at a subduction zone.

<!-- slide quad -->
## What contributes to motion?
<!-- @tl -->
**Slab pull**

Weight of cold sinking lithosphere
<!-- @tr -->
**Gravitational sliding**

Tendency away from elevated ridges
<!-- @bl -->
**Mantle flow**

Coupled response to thermal and density structure
<!-- @br -->
**Boundary forces**

Resistance, suction, and changing geometry

<!-- slide step -->
## Example — annual crust production
**Question:** A 1,500-km ridge opens at 60 mm/yr. What total seafloor area is produced each year?

1. $60\ \text{mm/yr}=6.0\times10^{-5}\ \text{km/yr}$
2. $A=L\Delta x$
3. $A=(1500)(6.0\times10^{-5})$
4. ==$A=0.090\ \text{km}^2/\text{yr}$==

<!-- slide template=section v=5 -->
# 1.4 Magnetic and age evidence
## The ocean floor records motion

<!-- slide 2col 3/2 -->
## Basalt can record field polarity
<!-- @left -->
- Iron-bearing minerals acquire magnetization as lava cools
- Earth's field reverses at irregular intervals
- Successive crustal bands preserve alternating polarity
- Later heating or alteration can overprint the record
<!-- @right -->
:::success
**Testable prediction:** Bands should be broadly parallel to the ridge and mirror one another across it.
:::

<!-- slide -->
## The mirror-image test
![Symmetric normal and reversed magnetic polarity bands across a ridge](https://alembic.orz.how/d/doc-e9vxc19oriwk =850x)

:::success
Youngest at the axis · older outward · same reversal sequence on both flanks
:::

<!-- slide 2col -->
## Half-rate versus full rate
<!-- @left -->
**One flank**

$$v_{1/2}=\frac{d}{t}$$

- Ridge to dated stripe
- Reports a half-spreading rate
<!-- @right -->
**Both flanks**

$$v_{full}=v_W+v_E$$

- Double only if symmetry is assumed
- $1\ \text{km/Myr}=1\ \text{mm/yr}$

<!-- slide step -->
## Example — asymmetric spreading
**Question:** An 8.0 Ma reversal is 160 km west and 184 km east of a ridge.

1. $v_W=160/8.0=20\ \text{mm/yr}$
2. $v_E=184/8.0=23\ \text{mm/yr}$
3. $v_{full}=20+23=43\ \text{mm/yr}$
4. ==Spreading is close to, but not perfectly, symmetric.==

<!-- slide template=section v=6 -->
# 1.5 Ocean-basin life cycles
## Scale boundary processes through time

<!-- slide -->
## Six stages of a Wilson cycle
![Clockwise Wilson cycle from rifting to collision](https://alembic.orz.how/d/doc-o7yahp9dqxek =760x)

:::warning
**Idealized sequence:** Real basins can be asymmetric, interrupted, or reorganized.
:::

<!-- slide 3col -->
## Opening, closing, inheritance
<!-- @left -->
**Opening**

- Rift
- Young sea
- Mature ocean
<!-- @mid -->
**Closing**

- Subduction
- Narrowing basin
- Collision
<!-- @right -->
**Inheritance**

- Suture remains
- Weakness may reactivate
- Later rifting can reuse it

<!-- slide main-side -->
## Reconstruction needs multiple constraints
<!-- @main -->
- Magnetic stripes + dated seafloor
- Paleomagnetic latitude and rotation
- Matching rock belts and structures
- Fossils and sedimentary environments
- Geometry and hotspot tracks
<!-- @side -->
:::warning
**Limits grow backward in time:** recycled seafloor removes direct records; paleomagnetism usually constrains longitude poorly.
:::

<!-- slide step -->
## Example — test a reconstruction
**Question:** Two 450 Ma continents are joined because their coastlines look complementary. What else is needed?

1. Compare dated rock belts and mountain structures.
2. Test fossil and sedimentary provinces.
3. Check paleomagnetic latitude and rotation.
4. Keep the limit visible: modern coasts are not original rift edges, and longitude may remain uncertain.

<!-- slide 2col -->
## Source adaptation
<!-- @left -->
Adapted and reorganized for this teaching resource. Source text is by **Wikipedia contributors**:

- [Plate tectonics](https://en.wikipedia.org/wiki/Plate_tectonics)
- [Lithosphere](https://en.wikipedia.org/wiki/Lithosphere)
- [Seafloor spreading](https://en.wikipedia.org/wiki/Seafloor_spreading)
<!-- @right -->
- [Paleomagnetism](https://en.wikipedia.org/wiki/Paleomagnetism)
- [Wilson Cycle](https://en.wikipedia.org/wiki/Wilson_Cycle)

Text license: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). See package attribution metadata for image credits and changes.

<!-- slide template=closing -->
# One thread
## Material behavior → motion → processes → evidence → reconstruction
