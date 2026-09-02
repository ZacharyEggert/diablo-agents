---
name: amp-listing
description: Research guitar amplifier specifications, confirm details with the user, and assemble the information into a consistent sales listing format.
argument-hint: "[amplifier details]"
user-invocable: true
disable-model-invocation: true
---

Research a given guitar amplifier based on the provided details, using reliable online sources where available (1st party websites, Sweetwater, manufacturer specifications).

Ask the user for details on the specific example being listed:

- Serial number
- Year of manufacture
- Condition Grade (e.g., New, Mint, Excellent, Very Good, Good, Fair, Poor) as well as any specific notes on wear or damage
- Modification details (if any)
- Accessories included (e.g., footswitch, cables, cover - do not assume the unit has accessories, always confirm with the user)
- Color (if the model has multiple color options)

Confirm the details researched with the user before assembling the information into a consistent sales listing format:

- Model and make
- Year of manufacture (if inferred from serial number)
- Wattage, Speaker configuration, Tube configuration
- Control layout and types (e.g., knobs, switches, digital interface)
- Onboard Effects (if any)

Assemble the confirmed details into a consistent sales listing format:

```text

<Title: Make, Model, Series, Formfactor, Year, Color>

<Description: Brief overview of the amplifier, highlighting key features and unique aspects - this section is more editorial and narrative in nature>

<Condition: Condition grade and any specific notes on wear or damage>

Specifications:

<Specifications: Detailed technical specifications of the amplifier, including make, model, (submodel, serial), year, power output, speaker configuration, tube configuration, channels, controls (global and per-channel), and any other relevant technical details - this is a hard-facts section, no editorializing, in a bullet-point (Aspect: Value) format>

What's Included:

<What's Included: List of items included with the amplifier, such as power cables, footswitches, covers, etc.>

```

When the copy is assembled and there are no more questions or clarifications needed from the user, the listing can be considered "done"; offer to copy it to the clipboard.

---

For listing examples, see `examples/` directory.
