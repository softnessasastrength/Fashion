# Finishing Inventory — Chaos Incorporated Wardrobe System

**Document type:** Ember analysis document (not part of the original system). Written 2026-10-31 by Ember from a read of the staged copy at `~/workspace/chaos-fashion-spinoff/staged/wardrobe/`, a verbatim copy of the `wardrobe/` tree from the Chaos-Incorporated repo. The staged source was not modified.

**Read in full for this inventory:** `wardrobe-manifesto.md`, `wardrobe-architecture.md`, `build-plan.md`, `priority-system.md`, `full-wardrobe.md`, `color-system.md`, `translucent-system.md` (Soft Light), `warm-season-system.md` (Soft Heat), `cold-season-system.md` (Soft Cold), `formal-system.md` (Soft Formal), `phase-1-shopping-shortlist.md`, `item-template.md`, the wardrobe root `README.md`, and the category READMEs (accessories, dresses, outerwear, shoes, shoes/jelly, full-looks, bottoms/trousers, tops/translucent) plus `bottoms/bottoms-priority.md`. Sampled in depth: the vision + manufacturing-brief pairs for the ring statement dress, the quilted vest (the shallowest brief in the tree), the heart-emerald pendant, and the Anchor Heel brief structure; the jeans master template (`bottoms/jeans/jeans-template.md`); the four seasonal shopping shortlists; and representative single-file items and full looks. Counts below were verified by listing the files, not estimated.

**A note on personal details:** the source item files and shortlists contain personal sizing, measurement, and shopping specifics. This inventory records only that such details *exist*, and in which kinds of files (item files' Technical Specs and Sizing sections; briefs' sizing sections; shopping shortlists). No such specifics are transcribed here.

---

## 1. System map

### What it is

A complete, self-governing **wardrobe design system** for one wearer: romantic, whimsical garments (the docs' own shorthand: LoveShackFancy silhouette language × Target wearability) engineered for a 64″ (5′4″) frame, built around a single fixed reference object — the **Starlink One** ring (sterling silver, heart-cut emerald, chain-link motif) — whose material, color, and "soft shape held by hard architecture" logic generate the whole system's rules.

### Named parts

- **Governing doctrine:** `wardrobe-manifesto.md` ("The Chaos Incorporated Wardrobe Manifesto") — softness + structure, comfort as the aesthetic, patina over polish, fit before print, every soft piece needs one hard detail.
- **Fixed reference:** **Starlink One** (the ring; its own documentation lives *outside* this tree, in the original repo's `ring/` folder — see §5).
- **Closed palette:** 9 colors in `color-system.md` — Starlink Emerald (anchor), Sage, Cloud Ivory, Sterling Grey, Blush Mauve, Periwinkle, Lavender Mist, Midnight Navy, Jet Black. Silver-family hardware only, system-wide, no exceptions for gold.
- **Priority tiers:** Must-Have / High / Medium / Experimental (`priority-system.md`), with promotion rules (nothing reaches Must-Have untested; Experimental items get a trial of a season or ~10 wears, then are promoted or retired).
- **Phases:** Phase 1 Essentials → Phase 2 Expansion → Phase 3 Statement (`build-plan.md`).
- **Six garment categories:** Tops, Bottoms, Outerwear, Shoes, Accessories, Dresses (Dresses added mid-build, during Phase 3), plus a **Full Looks** assembly layer (not a garment category).
- **Four cross-category registers/capsules**, each with its own doctrine doc:
  - **Soft Light** — translucent/sheer register (`translucent-system.md`), with a non-negotiable opacity map; Experimental.
  - **Soft Heat** — warm-season capsule (`warm-season-system.md`).
  - **Soft Cold** — cold-season capsule (`cold-season-system.md`).
  - **Soft Formal** — rare-occasion event layer (`formal-system.md`); never Must-Have by design.
  - A fifth named register, **Soft Structure**, is the jelly footwear sub-line inside Shoes (`shoes/jelly/`), the material-translucent cousin of Soft Light.
- **Templates:** `item-template.md` (every item documents frame rationale, technical specs, fabric/feel, colorways, sourcing, pairings, Starlink One pairing, and system notes) and `bottoms/jeans/jeans-template.md`, a 13.4 KB master reference holding the shared fit logic for all ten jean silhouettes.

### Counts (verified by file listing)

| Measure | Count |
|---|---|
| Total files in the tree | **238** (234 Markdown + 4 empty `.gitkeep` placeholders) |
| System/doctrine/inventory docs at wardrobe root | 17 (incl. root README, 5 shopping shortlists) |
| Single-file item entries (numbered spec files) | **94** — matches `full-wardrobe.md`'s own stated count exactly |
| Full-look files | **14** files, numbered 01–13 (see §5: two different looks are numbered 01) |
| Items with full vision + manufacturing-brief treatment | **33 packages** (folder with README + `vision.md` + `manufacturing-brief.md` = 99 files) |
| Distinct designed items overall | **101** (94 single-file items + 7 that exist only as packages) + 14 full looks |

The 33 full-treatment packages, by category: **Shoes 15, Outerwear 11, Dresses 6, Accessories 1.**

- **Dresses (6/6)** and **Outerwear (11/11):** every numbered item also has a full package.
- **Accessories (1/9):** only the heart-emerald pendant has a package; the other 8 remain single-file.
- **Shoes (15 packages):** 8 packages expand numbered concept notes (Perfect Flat, Cloud Walker, Hug Boot, Barely There, block-heel pump, statement mule, rain/snow boot, yoga/recovery); 7 exist *only* as packages — Anchor One, Espadrille Wedge, Horsebit Loafer, Kitten Heel Mary Jane, Lug-Sole Boot, Wrap Ballet Flat, Jelly Sandal. One numbered shoe, the knee-high boot (05), has **no** package (see §5).
- **Tops (0/22), Bottoms (0/32), Full Looks (0/14):** no vision/brief packages at all — single-file spec format throughout, following `item-template.md`.
- **Template-only:** nothing in the tree is an unfilled template instance. `item-template.md` and `jeans-template.md` are reference documents, and every item file sampled follows the item template's full section structure (frame rationale → technical specs → fabric & feel → colorways → sourcing → pairings → Starlink One pairing → system notes). The tree contains no placeholder item files; a text sweep for TBD/TODO/placeholder markers found none (the single "placeholder" hit is prose inside a vision doc rejecting a thin fabric as "a placeholder").

Item-file status fields (tallied from the files' own **Status:** lines): roughly **70 Concept / 29 Sourcing / 0 Owned / 0 Retired** across item and register docs.

---

## 2. Status audit

The system is unusually honest about its own status — its two master documents state the position outright:

- `full-wardrobe.md`, header: "**Docs status:** all three phases are built (spec/design complete). **Physical status:** every item is still *Concept* or *Sourcing* — nothing fitted, purchased, or worn yet."
- `build-plan.md`, closing section: "every item in this system is still a *Concept* or *Sourcing* status — nothing has been physically fitted, purchased, or worn yet. 'Built' above means the design/spec/documentation work is done, not that the wardrobe physically exists."
- `phase-1-shopping-shortlist.md`: "Status legend: all still Concept/Sourcing until physically owned." Every buy-wave checkbox in every shortlist is unchecked (☐).
- The four seasonal/register doctrine docs and the jelly line README each carry "**Status:** Concept" in their headers. The Anchor Heel is listed as Concept even though it sits in the Phase 1 Must-Have core.

**The "Built" tension is real, named, and self-documented.** `build-plan.md` marks every category in every phase "Built" (Phase 1: "Phase 1 is complete across every category"), and the wardrobe README says "All three phases are built out." In plan usage, "Built" means *the documentation is written*. The plan itself flags the collision in its final section (quoted above) and redefines the word — but a reader who stops at the phase tables will still take away "complete" where the status fields say Concept/Sourcing. Every manufacturing brief is likewise headed "Revision: 1.0 (Draft — pending manufacturer confirmation…)" and carries a status note that it "is not a finalized production spec."

Two further status facts the plan records about itself:

- **The Phase 3 sequencing rule was overridden.** Plan rule: nothing enters Phase 3 until Phase 1 is complete and Phase 2 at least half-built per category. The plan records that this "was overridden at explicit request ('build all phases')" — Phase 3 pieces exist on paper but are, in the plan's words, "the aspirational layer, not the near-term shopping list."
- **Phase 1's definition of done is a documentation test, and it is met.** Done = at least one fully assembled documented outfit in `full-looks/` using only Phase 1 items, checked against the color system and the ring. The plan names three qualifying looks (the two 01 looks and 02).

**Verdict:** as a *design and documentation system*, the wardrobe is finished — complete catalogue, doctrine, palette, phases, sourcing waves, and assembly layer. As a *wardrobe*, nothing exists yet: zero items Owned, zero fits validated, zero manufacturer conversations held. "Finishing" this system is therefore not a writing task. It is the execution program in §3.

---

## 3. What "finished" would require (in the plan's own phase order)

The plan's own closing words set the agenda: "The next real milestone isn't more files — it's sourcing and physically fitting the Phase 1 pieces… which is the only way to validate any of the 64″-frame proportion reasoning in these files against reality. Start with `phase-1-shopping-shortlist.md` (buy wave A)."

### Step 1 — Phase 1 sourcing and fit validation (the gate for everything else)
- Execute **Buy Wave A** (7 line items: straight-leg jean, seamless legging, crew tees, ribbed tanks, Cloud Walker sneaker, Perfect Flat, everyday crossbody), then Waves B and C, per `phase-1-shopping-shortlist.md`. The shortlist states a Wave A budget ballpark of **~$600–$1,200** "if buying mid-range options" — the only consolidated figure the plan gives for Phase 1; per-item price ranges are given throughout.
- Every try-on runs the shortlist's six-point fit checklist (inseam/hem, rise, wrist clearance for the ring, silver-only hardware, 20-minute comfort test, palette check).
- After each purchase, the shortlist prescribes the bookkeeping: update the item file's Status → Owned (with the size/brand actually bought), check the boxes here and in `full-wardrobe.md`, and re-run the matching full look, noting fit issues.
- Wear-test the three Phase 1 full looks. This is the step that validates or falsifies the system's core bet — that its proportion rules work on the actual frame. The docs also rely on personal sizing/measurement specifics recorded inside individual item files (Technical Specs / Sizing sections) and the briefs' sizing sections; those exist at item level but there is **no single consolidated measurement/fit chart** anywhere in the tree.

### Step 2 — Phase 2 expansion and the seasonal registers
- Source the Phase 2 pieces per category (trousers/jogger, four intricate tops, three outerwear pieces plus blazer, Barely There + knee-high boot, three accessories, soft day dress), then the four seasonal shortlists — each with its own waves and a "Budget sketch" section — in the registers' stated source orders (Soft Light: sheer base + organza blouse first, overlay dress last; Soft Heat: hero jelly flat first, one warm-season trial before the other four jelly silhouettes; Soft Cold: turtleneck + fleece legging, coat late; Soft Formal: midi first, and only against real events).
- Experimental items then run their `priority-system.md` trial (a season / ~10 wears) and are promoted or retired — a feedback loop the system defines but, with nothing owned, has never run.

### Step 3 — Phase 3 statement pieces, and the custom/manufacturing track
Running underneath all three phases is a second, distinct execution track the docs keep separate from buying: **commissioning**. Thirty-three items have factory/jeweler-facing briefs, and every brief ends the same way — a list of open items for the manufacturer, and a "Requested Next Step" that is, in every sampled case, **one fit sample in one colorway before any multi-size or multi-colorway commitment** (ring dress: one Starlink Emerald fit sample; quilted vest: one Sterling Grey sample; Anchor Heel: prototype the Everyday Anchor variant first). The pendant's next step is a commission inquiry to Starlink One's own jeweler.

Between the documented system and physical garments on this track:
- **Patterns/tech packs: not present as artifacts.** The briefs are prose spec tables (silhouette, lengths, fabric type/weight/stretch, construction method, colorways) written to *start* a pattern-development and quoting conversation. There are no pattern files, no graded measurement charts, no size-run spec sheets in the tree. The one use of the words "tech pack" (`wardrobe-architecture.md`, on Anchor Heel: "3 variations, dedicated tech pack") refers to the manufacturing brief itself — no separate tech-pack file exists.
- **Open technical decisions the briefs explicitly leave to manufacturers:** boning-vs-shaping-liner construction (ring dress), fill weight/loft spec (quilted vest), last grading for a smaller frame (Anchor Heel and, by analogy, the vest's armhole), dye-lot color match of Starlink Emerald against the physical ring, stone sourcing for a small heart cut (pendant). Each brief names its own gating item — the ring dress's is a live sleeve-length validation against real arm movement, which the brief says "cannot be validated from a flat sketch."
- **Vendor selection is generic, not contracted:** a Shenzhen footwear manufacturer (Anchor Heel brief), a made-to-order atelier preferred over mass cut-and-sew (ring dress), Starlink One's jeweler (pendant). No vendor has been contacted per anything in the docs; no MOQs, lead times, sampling fees, or per-unit costs appear anywhere.
- **Budget: the custom track has none.** Budgets exist only on the shopping track (Wave A ballpark; per-item ranges; per-wave budget sketches in the seasonal shortlists; Soft Formal Wave F1 "Rough total: $330–$930"). No consolidated budget for the whole system exists in any doc.

### What the plan leaves unspecified (anywhere)
1. Any timeline or dates — phases are sequenced, never scheduled.
2. Any total budget, or any budget at all for prototyping/commissions.
3. Who sews/sews-alterations: hemming and fit alterations are assumed ("petite inseams where offered," "crop or petite before 'I'll hem it later'") but no tailor/alterations step, cost, or owner is named.
4. Care/maintenance and replacement cycles beyond per-item care notes and the jelly line's replace-when-sticky rule.
5. What happens to the documentation after execution — the update workflow exists (status flips, checkboxes, look re-runs) but no review cadence is set.

---

## 4. First-piece candidates

The plan runs two "firsts" in parallel, one per track:

**Shopping track — the plan's explicit first move:** Buy Wave A of `phase-1-shopping-shortlist.md`, whose first line item is the **straight-leg jean** (petite inseam). It is also first in `full-wardrobe.md`'s Must-Have core table, and `bottoms/bottoms-priority.md` ranks Jeans the #1 category ("the foundational bottom"). The Phase 1 outerwear pair tells a small sequencing story of its own: the Must-Have core lists the cropped denim jacket and chunky knit cardigan at **Concept** while most Wave A/B items sit at Sourcing — they are the Phase 1 pieces whose specs were written but whose sourcing examples were never developed to the same depth.

**Manufacturing track — the most completely specified item in the system: Anchor One (the Anchor Heel).** Evidence:
- Largest package in the tree: `vision.md` 13,742 bytes + `manufacturing-brief.md` 10,034 bytes — the brief alone is the biggest brief in the system.
- The brief is addressed to a named manufacturing context ("Footwear manufacturer, Shenzhen"), runs 10 sections including three fully-specced variations (Everyday Anchor — Must-Have; Dress Anchor and Travel Anchor — High), a dedicated Sizing & Last section, an open-items section, and a requested next step (`full-wardrobe.md`: "Prototype Everyday Anchor first").
- It is the system's reference standard: the dresses, outerwear, and accessories packages repeatedly describe their own treatment as "the Anchor One treatment," and other briefs borrow its last-grading principle.
- `phase-1-shopping-shortlist.md` singles it out as the one Phase 1 item that is "prototype path, not a same-day add-to-cart SKU" — i.e., the one Phase 1 piece that must be *made*, not bought.

**Recommendation on the plan's own logic:** the first physical *action* is Wave A (starting with the straight-leg jean) because every later validation depends on fitted Phase 1 basics; the first physical *make* is the **Anchor One Everyday Anchor prototype** — deepest brief, Must-Have tier, and the piece other categories' proportion math (jeans hems especially) already assumes exists. The ring statement dress is the system's named centerpiece ("the piece that most literally executes 'the wardrobe is designed around the ring'") and its brief recommends a single Emerald fit sample — but the plan itself files it as aspirational Phase 3, explicitly not the near-term move.

---

## 5. Gaps & inconsistencies

1. **Two different "01" full looks.** `full-looks/` holds 14 files numbered 01–13: `01-everyday-errands-look.md` and `01-structured-everyday-look.md` are different outfits sharing number 01. The build plan notices and turns it into a virtue ("Met, three times over"), and both `full-wardrobe.md` and `full-looks/README.md` reproduce the duplicate numbering in their tables, but the collision is never resolved — there is no 14.
2. **Shoes catalogue count disagrees across four documents.** Root README: "9 numbered + Anchor Heel + jelly." `full-wardrobe.md`: "94 item files" (which counts the 9 numbered shoes and 5 jelly silhouettes, and none of the 7 package-only shoes). `shoes/README.md`: a 15-row catalogue (14 named shoes + the jelly line). `wardrobe-architecture.md`: "the full 14-shoe catalogue" and "every one of the 14 numbered items now has its own full vision + manufacturing brief" — not true of the files: the **knee-high boot (numbered 05) has no package and does not appear in `shoes/README.md`'s catalogue table at all**, and the five jelly silhouettes have concept docs only, no vision/brief pairs. The architecture's "full coverage" claim for shoes is the one place the docs overstate what exists. (The equivalent claims for Dresses 6/6 and Outerwear 11/11 check out against the files.)
3. **Build-plan item counts drift from the built files.** The plan's Phase 1 tops scope says 6 basics + 6 intricate (files: 7 basics — the turtleneck arrived with the Soft Cold pass — and 10 intricate); its build-order summary says shoes and outerwear expanded "to 6" (files: 9 numbered shoes + 15 packages + 5 jelly; 11 outerwear). The plan was not updated after the later expansion passes; `full-wardrobe.md` and the category READMEs carry the accurate counts.
4. **Dual documentation for 26 items.** Each packaged item exists twice: the original numbered concept note and the vision+brief folder. Category READMEs say the concept notes are left "unmodified in substance" with a pointer line to the folder — a standing drift risk: edit one copy and the system disagrees with itself. (This is presumably deliberate backwards-compatibility: `full-looks/` and `jeans-template.md` link to the concept-note paths.)
5. **The system's fixed reference lives outside the system.** Manifesto, README, and `full-wardrobe.md` all anchor on Starlink One and link to `../ring/README.md` (and `../packaging/README.md`) — paths outside the `wardrobe/` tree and therefore **broken inside this staged copy**. A spin-off of `wardrobe/` alone severs its own foundation document: the ring's spec (the source of the palette's anchor color, the metal rule, and the chain-link scale the moto jacket and belt are told to match) is not in the tree. Relatedly, the manifesto's scope note points to "the note in the repo root README" for the separately-handled intimate/sleepwear categories — also outside this tree; no such category exists here.
6. **Documented dead ends (by design, but worth listing):** the long formal dress carries a hard sourcing gate — no sourcing without a real black-tie event and an already-owned formal heel; barrel/balloon jean colorway expansion is explicitly held ("compounding one unproven bet"); the Soft Formal register's F3 Emerald row in its shortlist has no price ("—") where every other row is priced.
7. **Stale scaffolding:** four empty `.gitkeep` files (`bottoms/`, `full-looks/`, `shoes/`, `tops/`) persist in folders that are fully populated.
8. **Status vocabulary wobble:** item-template defines Concept / Sourcing / Owned / Retired, but register docs apply "Concept" to whole capsules, one item carries the hybrid "Concept (pending physical fitting once sourced)," and `full-wardrobe.md`'s Phase 1 table lists two Must-Have outerwear pieces as Concept amid an otherwise Sourcing core — small, but the spin-off's first editing pass will trip over it.

---

## 6. Internal name

The system has no brand name of its own separate from its parent: the manifesto titles it **"The Chaos Incorporated Wardrobe"** — doctrine "for Renn's wardrobe system" — and `build-plan.md` calls it "Renn's Chaos Incorporated wardrobe." The wardrobe root README's own title is the plainest internal name: **"Renn Wardrobe."**

Named sub-identities inside it: the reference ring **Starlink One**; the flagship heel **Anchor One** ("The Anchor Heel"); the shoe catalogue's governing concept **"Warm Hug"** (softness that holds, structure that grounds — also echoed in the cold-season doc as "Warm Hug in reverse weather"); and the five registers **Soft Light, Soft Heat, Soft Cold, Soft Formal, Soft Structure**. For naming a spin-off repo, the candidates the documents themselves supply are *Renn Wardrobe* and *The Chaos Incorporated Wardrobe*; nothing in the tree uses any other name for the system as a whole.
