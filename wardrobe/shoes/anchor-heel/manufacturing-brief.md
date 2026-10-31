# Anchor One — Manufacturing Brief

**Document Type:** Technical Specification / Manufacturing Brief for factory quoting and prototyping
**Prepared for:** Footwear manufacturer, Shenzhen
**Revision:** 1.0 (Draft — pending factory confirmation of last grading, sole construction feasibility, and material sourcing)
**Governing doc:** [`vision.md`](vision.md) — read for design rationale; this document is the buildable spec and the language intended to go directly to a factory contact.

**Status note, read first:** this brief translates an approved design direction into dimensions, materials, and construction methods for an initial quoting and prototyping conversation. It is not a finalized production spec — Section 9 lists what needs factory engineering confirmation before tooling begins.

---

## 1. Product Overview

A women's block-heel shoe, 2.0–2.25" (50–57mm) heel height, engineered for maximum daily wearability and stability rather than height. Three variations share a common last and construction method with material/finish differences (Section 7). Blake-stitch construction, full leather or leather/rubber composite soles, memory-foam-topped footbed, replaceable top-lift.

## 2. Heel Specification

| Parameter | Target | Tolerance |
|---|---|---|
| Heel height | 50–57mm (2.0–2.25") per variation | ±1.0mm |
| Heel top width (breast) | 34mm × 30mm | ±0.5mm |
| Heel base width (top-lift, ground contact) | 28mm × 24mm | ±0.5mm |
| Heel taper profile | Soft, gradual taper from breast to base — **not** a stiletto taper | Confirm via physical sample against reference silhouette, not spec alone |
| Effective pitch angle | 8–10° | Achieved via 5–8mm hidden forefoot platform, not heel height alone — see Section 3 |
| Top-lift material | TPR (thermoplastic rubber), 60–65 Shore A | ±3 Shore A |
| Top-lift attachment | Screw or nail-set, field-replaceable | Confirm standard factory hardware for serviceable top-lifts |
| Heel core material | Reinforced wood or high-density polymer | Confirm factory standard vs. custom requirement |
| Heel attachment method | Heel nail/dowel through shank + adhesive bond | Standard block-heel attachment method — confirm factory default matches this, not a lighter cemented-only attachment |

## 3. Sole & Platform Construction

- **Construction method: Blake stitch (or Blake-Rapid).** Explicitly not Goodyear welt — Blake construction is required for the slimmer, more flexible sole profile this design depends on for its comfort brief. Confirm this is within the factory's standard capability before quoting; not all footwear factories run both construction methods, and this is a gating requirement, not a preference.
- **Hidden forefoot platform:** 5–8mm platform under the ball of the foot, concealed within the sole construction (not visible as a platform shoe from the outside) — reduces effective heel pitch from a true 12–14° (at 50–57mm heel height with no platform) down to the 8–10° target in Section 2. Confirm achievable platform height within the chosen sole construction without adding visible bulk to the silhouette.
- **Outsole:** leather sole with rubber forefoot/heel inserts for the Everyday and Dress Anchor variations; full rubber outsole with tread pattern for the Travel Anchor variation (Section 7).
- **Toe shape:** rounded/soft almond — confirm toe-box last shape explicitly, not assumed from a generic "round toe" descriptor, since rounding degree varies significantly between last makers.

## 4. Footbed / Insole Build

| Layer | Spec |
|---|---|
| Sock lining (top, skin contact) | Soft napped leather or moisture-wicking textile |
| Comfort layer | **Memory foam, 4–6mm** (Everyday/Dress), **6–8mm** (Travel — see Section 7), visco-elastic, target density 3–4 lb/ft³ |
| Support layer | EVA base, 6–8mm, firmer density than the memory foam layer above it |
| Arch support | Moderate contoured support built into the footbed — not a rigid/orthotic-level support |

Confirm factory's standard memory foam density/sourcing against the 3–4 lb/ft³ target; this is a meaningful comfort variable and should not be left to a generic "cushioned footbed" spec without a density confirmation.

## 5. Materials

| Priority | Material | Tannage / Finish | Thickness | Used In |
|---|---|---|---|---|
| 1 | Aniline nappa calfskin | Vegetable-tanned or veg-chrome combination, full aniline dye, **no corrected grain / no pigmented topcoat** | 1.2–1.4mm | Everyday Anchor (primary), Dress Anchor (option) |
| 2 | Brushed suede | Chrome or vegetable-tanned, natural brushed nap, light water/stain guard only | 1.0–1.3mm | Dress Anchor (primary) |
| 3 | Semi-aniline calf leather | Chrome-tanned, light semi-aniline protective finish | 1.2–1.5mm | Travel Anchor (primary) |

**Critical sourcing note:** the aniline (uncorrected-grain) leather finish in priority material #1 is a deliberate, non-negotiable choice — it's what allows the leather to visibly patina and soften with wear, which is a core brand requirement, not a cosmetic preference. Do not substitute a corrected-grain or heavily pigmented leather as a "close enough" alternative even if it's more readily available or cheaper — flag any sourcing difficulty here rather than substituting quietly.

## 6. Starlink One Reference Details

- Blind-debossed heart-and-chain-link mark on the sock lining, positioned at the ball-of-foot area. Confirm minimum feature size the factory's debossing tooling can hold at this small scale.
- A single fine Starlink Emerald thread run along the inside edge of the heel-breast stitch line. Confirm thread color-matching process against the brand's existing color reference (see `../../color-system.md`) and whether this requires a custom thread order or is achievable from factory-standard thread stock in a close match.

## 7. Three Variations — Spec Summary

| Spec | Everyday Anchor | Dress Anchor | Travel Anchor |
|---|---|---|---|
| Priority tier | Must-Have | High | High |
| Height | 2.0" / 50mm | 2.25" / 57mm | 2.0" / 50mm |
| Material | Aniline nappa (priority 1) | Suede or aniline nappa | Semi-aniline calf (priority 3) |
| Colorway | Cloud Ivory, Sterling Grey | Blush Mauve, Jet Black, Starlink Emerald (seasonal) | Midnight Navy, Sterling Grey |
| Sole | Leather + rubber inserts | Full leather, hand-burnished edge | Full rubber outsole, tread pattern |
| Memory foam thickness | 4–6mm | 4–6mm | 6–8mm (upgraded) |
| Heel taper | Standard per Section 2 | Slightly more tapered, same base-width stability range | Standard per Section 2 |

**Recommended build order for sampling:** Everyday Anchor first (proves the core last, construction method, and comfort spec), then Dress and Travel as material/finish variants off the same validated last — not three parallel, independent development tracks. This keeps the first prototype round focused on the specs that are actually shared risk (last shape, Blake construction feasibility, platform concealment) rather than splitting factory attention across three simultaneous builds.

## 8. Sizing & Last

- **Size run:** US 5–10, with sizes 5–7 requiring **independent last grading**, not linear scaling down from an 8–9 master last. This is the single most important sizing note in this brief — flag explicitly during the quoting call, since linear grading is the factory-default shortcut and produces visibly wrong toe-box proportions at the smaller end of the run.
- **Width options:** Medium (M) as standard/first-production width; Narrow (B) and Wide (W) as a second-phase addition once M is validated. Target ball-of-foot widths at US size 7: B ≈ 3.3", M ≈ 3.5", W ≈ 3.7" — confirm factory's standard width grading increments against these targets.
- **Heel counter:** substantial soft padding at the heel counter/Achilles area on all widths — call out explicitly as a fit-quality requirement, not left to standard factory padding defaults.

## 9. Critical Technical Challenges — Open Items for Factory Conversation

1. **Blake-stitch capability confirmation** — gating requirement; confirm before any other conversation, since not all factories run this construction method.
2. **Hidden platform concealment** — confirm the 5–8mm forefoot platform can be built into the sole without visible bulk or an obvious "platform shoe" silhouette change.
3. **Last grading for sizes 5–7** — confirm the factory will independently grade small sizes rather than linearly scale, and get this in writing as a QC requirement, not an assumption.
4. **Aniline leather sourcing** — confirm supply chain access to true uncorrected-grain aniline nappa calfskin; this is a more specialized material than standard corrected-grain leather and may affect MOQ, cost, and lead time.
5. **Replaceable top-lift hardware** — confirm factory's standard approach to serviceable (screw/nail-set) top-lifts vs. a permanently fused top-lift, and get a sample of the service/replacement process.
6. **Memory foam density sourcing** — confirm 3–4 lb/ft³ (Everyday/Dress) and the upgraded Travel Anchor spec are both achievable from factory-standard foam suppliers or require a custom foam order.
7. **Debossed insole detail tooling** — confirm minimum feature size for the heart-and-chain-link mark at sock-lining scale.
8. **Thread color match for the heel-breast Starlink Emerald detail** — confirm against `../../color-system.md`'s hex reference and whether custom thread dyeing is needed.

## 10. Requested Next Step

A running prototype of the **Everyday Anchor** variation only, in a single size (recommend US 7 as the reference/fit sample size) and a single colorway (Cloud Ivory), before any production tooling or multi-size/multi-variation commitment. Given the number of construction-method and material decisions still flagged as open (Section 9), a single proof-of-concept prototype is the right next step to de-risk before scaling to the full three-variation, multi-width production plan.
