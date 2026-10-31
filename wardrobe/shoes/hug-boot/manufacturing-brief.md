# The Hug Boot — Manufacturing Brief

**Document Type:** Technical Specification / Manufacturing Brief for factory quoting and prototyping
**Prepared for:** Footwear manufacturer, Shenzhen
**Revision:** 1.0 (Draft — pending factory confirmation of gusset+zip combination construction and stacked-heel sourcing)
**Governing doc:** [`vision.md`](vision.md) — read for design rationale; this document is the buildable spec.

**Status note, read first:** this brief translates an approved design direction into dimensions, materials, and construction methods for an initial quoting and prototyping conversation. Section 8 lists what needs factory engineering confirmation before tooling begins. This boot carries real downstream weight: `../../bottoms/jeans/jeans-template.md` depends on it fitting and existing as specified for several Must-Have and High-tier jean silhouettes to read as intended.

---

## 1. Product Overview

A women's Chelsea-style ankle boot, 1.5" stacked leather heel, elastic side gussets plus a functional side zip, shearling or microfiber lining, chain-link leather pull tab and emerald-tone zipper pull as the two Starlink One hardware references.

## 2. Heel & Boot Specification

| Parameter | Target | Tolerance |
|---|---|---|
| Heel height | 38mm (1.5") | ±1.0mm |
| Heel construction | Stacked leather block | Confirm factory's standard stacked-leather-heel process — this is a distinct construction method from a molded/covered heel core and not every factory runs both |
| Ankle cuff height | Standard Chelsea height, clearing the ankle bone | Confirm against reference silhouette |
| Toe shape | Rounded / soft almond | Confirm last toe-box profile against reference, not a generic descriptor |
| Elastic gusset width/placement | Standard Chelsea gusset, both sides | Confirm gusset elastic recovery spec — a gusset that loses elasticity quickly is a common Chelsea-boot quality failure point |
| Side zip | Functional, full opening for on/off | Confirm zip gauge and puller spec (Section 6) |

## 3. Construction Method — Gusset + Zip Combination

- **This is the single construction question most worth confirming before quoting:** some Chelsea styles omit the side zip entirely and rely on the elastic gusset alone for entry. Confirm with the factory that combining a functional zip with the elastic gusset (rather than choosing one or the other) is standard construction for their process, not a custom modification that adds unexpected cost or complexity.
- **Lining installation:** shearling or ultra-soft microfiber lining, installed for cool-weather warmth without adding bulk to the boot's silhouette — confirm lining thickness target with the factory against a "warm but not bulky" brief, similar in spirit to the Rain/Snow Boot's insulation brief (see [`../rain-snow-boot/manufacturing-brief.md`](../rain-snow-boot/manufacturing-brief.md)) though this boot is not a technical/waterproof build.
- **Footbed:** memory foam (4–6mm) over an EVA base, same build as the Anchor Heel's footbed spec (see [`../anchor-heel/manufacturing-brief.md`](../anchor-heel/manufacturing-brief.md) Section 4).

## 4. Materials

| Priority | Material | Tannage / Finish | Thickness | Used In |
|---|---|---|---|---|
| 1 | Smooth or lightly grained leather | Warm, patina-friendly finish, no heavy corrected-grain topcoat | 1.3–1.6mm | Jet Black colorway (flagship) |
| 2 | Brushed suede | Chrome or vegetable-tanned, natural nap, light water/stain guard only | 1.1–1.4mm | Midnight Navy colorway |

## 5. Starlink One Reference Details

- **Chain-link leather pull tab:** at the back heel, functioning as the actual pull-on tab — confirm chain-link scale matches the ring's own reference scale (see [`../../color-system.md`](../../color-system.md) and the Anchor Heel's own scale-matching note) and confirm the tab is load-bearing enough to function as a genuine pull-on aid, not purely decorative.
- **Emerald-tone zipper pull:** confirm colorfast method for the zipper-pull finish (anodized or durable-plated metal, not painted) against the `#0F5C3D` reference, and confirm the zip puller shape/size the factory's standard zipper hardware supplier can produce at this small scale.

## 6. Sizing & Last

- **Last grading, not linear scaling:** independently grade US 5–7, same rule as every other shoe in the catalogue.
- **Ankle cuff fit note:** confirm break-in/fit testing focuses on the ankle cuff line, not the toe box — this boot's most common fit complaint point differs from the rest of the catalogue's flats and low shoes.
- **Heel stability:** confirm the stacked leather heel construction reads as stable immediately in the first prototype — no "break-in period" should be needed or expected for heel stability.

## 7. Critical Technical Challenges — Open Items for Factory Conversation

1. **Gusset + functional zip combination (Section 3)** — confirm this is standard construction for the selected factory, not a custom modification; gating item for the quoting conversation.
2. **Stacked leather heel sourcing** — confirm the factory runs this heel construction as standard, separate from a molded/covered heel core capability.
3. **Lining thickness/warmth-without-bulk balance** — needs a physical sample to validate, not a spec-table number alone.
4. **Chain-link pull tab load-bearing test** — confirm the tab functions as a genuine pull-on aid at the sourced chain-link scale, not just a decorative attachment.
5. **Zipper-pull colorfast plating** — confirm against the `#0F5C3D` reference and get a physical color-match swatch before bulk hardware order.

## 8. Requested Next Step

A running prototype in the Jet Black leather colorway, single size (US 7), with the gusset+zip combination and stacked heel construction as the two specs to validate most carefully — both are gating questions for whether this factory's standard process supports the brief without custom tooling, and this boot's downstream dependency in the jeans system makes getting the construction right on the first sample more important than for most other items in the catalogue.
