# Wardrobe Architecture

*The category map for the full system. Governed by [`wardrobe-manifesto.md`](wardrobe-manifesto.md); colors pull from [`color-system.md`](color-system.md); every item follows [`item-template.md`](item-template.md).*

---

## The Six Categories

*Originally five — Dresses was added during Phase 3 once a piece existed that didn't fit cleanly under Tops or Bottoms. See the note at the end of that section.*

### Tops (`/tops/`)
Split into four subfolders — originally two, matching the manifesto's soft/structure duality; `shirts/` and `translucent/` were added once pieces existed outside basics/intricate:
- **`basics/`** — solid tees, tanks, long-sleeves, turtleneck, base layers. Quiet, high-rotation, mostly Cloud Ivory / Sterling Grey / Midnight Navy. These exist to be layered under or paired with an intricate piece — they are not where the whimsy lives. **Built: 7 items.**
- **`intricate/`** — the LoveShackFancy x Target DNA: puff-sleeve blouses, smocked bodices, lace-trim camisoles, ribbon-tie necklines, ruffle detailing. This is where Blush Mauve, Periwinkle, and Lavender Mist do the most work. Every intricate top needs the manifesto's "one hard detail" — a structured cuff, a corseted or smocked bodice panel, a substantial (not flimsy) base fabric under any lace. **Built: 10 items**, including the puff-sleeve blouse and smocked top named in the Core Aesthetic Vision.
- **`shirts/`** — button-front woven shirts: an oversized flannel and a camp-collar print shirt. Neither is a quiet basic (both carry real pattern/print) nor a romantic intricate detail (no lace, ruffle, or smocking) — they're their own register, casual-with-personality rather than whimsical. This is also where the color system's print exception gets its most explicit workout: the camp-collar shirt is a deliberately re-colored "cool-toned Hawaiian" print (Starlink Emerald/Sage/Periwinkle) rather than the traditional warm red-orange-gold register, so it stays inside the brand's cool-undertone palette instead of importing a clashing print wholesale. **Built: 2 items.**
- **`translucent/`** — Soft Light tops (sheer long-sleeve base, organza/chiffon blouse, lace panel camisole). Governed by [`translucent-system.md`](translucent-system.md) opacity map — Experimental, not a Phase 1 foundation. **Built: 3 items.**

### Bottoms (`/bottoms/`)
The most built-out category — see [`bottoms/bottoms-priority.md`](bottoms/bottoms-priority.md) for the full ranking. Seven subfolders: `jeans/` (10), `leggings/` (8), `shorts/` (8), `trousers/` (2), `joggers/` (1), `skirts/` (2, Experimental — including Soft Light translucent midi), `overalls/` (1, Experimental).

### Outerwear (`/outerwear/`)
**Built: 11 items, every one now with its own full `vision.md` + `manufacturing-brief.md`** (see [`outerwear/README.md`](outerwear/README.md) for the complete named list) — the second category besides shoes and dresses to reach full coverage rather than a single flagship item.
- **Structured layers** — cropped denim jacket (Phase 1), lightweight trench (Phase 2), hardware-detailed moto jacket (Phase 3 statement, chain-link trim commissioned to match Starlink One's own scale, silver only per the color system), lightweight tailored blazer (Phase 2 High — dressier structure without moto heat, unlined/half-lined by design), wool wrap / winter coat (Phase 2 High Soft Cold), soft formal suit + evening wrap (Soft Formal — pick the suit or the Cocktail/Evening Dress first, not both on day one).
- **Soft layers** — chunky knit cardigan (Phase 1, the single highest ring-visibility risk item in the system given how knit bulk swallows the hand), quilted vest (Phase 2, soft-technical, the one outerwear piece with no sleeve at all and therefore no ring-visibility risk to solve for).
- **Romantic layers** — kimono duster (Phase 2) — the outerwear subcategory pulling most directly from the LoveShackFancy reference.
- **Soft Light** — sheer organza duster (Experimental) — translucent veil outerwear per [`translucent-system.md`](translucent-system.md), pure veil with no opacity of its own, unlike the Sheer Overlay Dress's attached underlayer.

### Shoes (`/shoes/`)
**Built: the full 14-shoe catalogue + the Soft Structure jelly sub-line** (see [`shoes/README.md`](shoes/README.md) for the complete named list). Every one fit-checked against a 64" frame (heel height changes leg-line math more at this height than at a taller one, so it's documented per item, not assumed), and every one of the 14 numbered items now has its own full `vision.md` + `manufacturing-brief.md`, not just a single concept note:
- **Everyday flats** — the Perfect Flat (Phase 1, ballet + loafer hybrid, hidden 0.5" wedge), the Wrap Ballet Flat (Medium, ribbon-wrap dance-costume reference, the deliberate inverse of the Perfect Flat's hidden engineering).
- **Sneakers** — the Cloud Walker (Phase 1, elegant-chunky, Gore-Tex option), the "quiet structure" workhorse, same logic as the straight-leg jean.
- **Loafers** — the Horsebit Loafer, a structured mini-heel loafer with a custom chain-link horsebit — the one everyday-tier shoe with a deliberately overt Starlink One reference, since the hardware is expected by genre convention rather than added for its own sake.
- **Boots** — the Hug Boot (Phase 1, Chelsea + Western hybrid, chain-link pull tab), knee-high boot (Phase 2, still a single concept note — see [`shoes/05-knee-high-boot.md`](shoes/05-knee-high-boot.md)), the Rain/Snow Boot (waterproof Chelsea — the one shoe in the whole system where the "moderate heel worn often" rule is deliberately overridden for ice/wet-weather safety), and the Lug-Sole Combat Boot (Experimental, a single bet on a trend-driven utility silhouette, the aesthetic-borrowing inverse of the Rain/Snow Boot's function-first case).
- **Heels** — block heel pump + the Statement Mule (both Phase 3 statement, 2.5–3", rare-occasion, two different silhouettes not a duplicate); [`anchor-heel/`](anchor-heel/) "Anchor One" (Must-Have, 2.0–2.25", everyday) — the moderate-heel-worn-often piece this category's own README argued was the better investment, built out with its own full vision doc and manufacturing brief given how deep the spec runs (3 variations, dedicated tech pack); the Kitten Heel Mary Jane (Medium, a demi-kitten heel that names and resolves the "thin heel vs. stable base" tension directly rather than avoiding it).
- **Sandals** — the Barely There Sandal (Phase 2, two versions: Everyday Strap and Dressy Slide, hybrid leather/fabric straps for durability without losing the delicate look), the Espadrille Wedge (High, jute-wedge warm-weather elevation, more stable than a block heel at the same height thanks to full ground contact), the Jelly Sandal (High, injection-molded PVC/TPU, a confirmed personal favorite built on a translucent Starlink Emerald colorway — the one deliberate, named single-item exception to the "materials chosen to patina" rule everywhere else in the system).
- **Recovery** — the Yoga/Recovery Shoe, the one shoe category with no competing design priority against maximum comfort.
- **Jelly (Soft Structure)** — [`shoes/jelly/`](shoes/jelly/) Experimental seasonal sub-line (5 silhouettes, shared molded footbed + silver chain-link hardware) — the line-level counterpart to the Jelly Sandal's single-item case above, breaking the same "patina over polish" rule but scoped to five silhouettes instead of one. Fills warm-weather water / wipeable / translucent-color gap the leather sandal and rain boot don't cover. Hero everyday jelly flat sources first; expand only after trial.

### Accessories (`/accessories/`)
**Built: 9 items.** This category carries the most direct Starlink One integration in the whole system:
- **Layering jewelry** — sterling silver layering necklace/bracelet set (Phase 1), a heart-emerald statement pendant (Phase 3 fine jewelry, now with its own full `vision.md` + jeweler-ready `manufacturing-brief.md` at [`accessories/heart-emerald-pendant/`](accessories/heart-emerald-pendant/) — the accessories category's first item to get the shoe catalogue's "Anchor One treatment") — chain-link detailing and stone color are deliberate callbacks to the ring's own design. This is where the ring gets "matched," not competed with.
- **Hair** — ribbons and silk scrunchies (Phase 2) — a signature LoveShackFancy x Target detail category, pulling heavily from Blush Mauve/Lavender Mist/Periwinkle.
- **Belts** — chain-link belt (Phase 2) — the single most direct hardware echo of Starlink One available in the accessories category.
- **Bags** — everyday crossbody bag (Phase 1) → statement shoulder bag (Phase 2) → evening clutch (Soft Formal); silver hardware only at every scale.
- **Scarves** — everyday silk scarf (Phase 2), styling flexibility (neck, bag, hair).
- **Cold hands** — soft gloves (Phase 2 Soft Cold), silver hardware only, ring-visibility modes documented.

### Dresses (`/dresses/`)
**Added during Phase 3.** A dress replaces both a top and a bottom at once and doesn't belong filed under either. **Built: 6 items, every one now with its own full `vision.md` + `manufacturing-brief.md`** (see [`dresses/README.md`](dresses/README.md) for the complete named list) — the first category besides shoes to get the full "Anchor One treatment" across its entire catalogue rather than a single flagship item: ring statement dress (Phase 3 ring showcase), sheer overlay (Soft Light, built last in that kit), soft day dress (Soft Heat, the one dress with a wash-and-wear rather than formal-fabric brief), soft formal midi (Soft Formal workhorse, source first), cocktail/evening dress (Soft Formal night, Medium tier), and the long formal dress (Experimental, floor length — carries a hard sourcing gate: no sourcing without a real calendar event and an already-owned formal heel). Separates still carry everyday rotation.

## Full Looks (`/full-looks/`)
Not a garment category — this is the assembly layer. **Built: 14 looks**, spanning Phase 1 essentials through Phase 3 statement, Soft Light / Soft Structure, Soft Heat, Soft Cold, and Soft Formal looks, each documenting a complete outfit and checking it against the color system and the ring (Soft Light checks [`translucent-system.md`](translucent-system.md); Soft Formal checks [`formal-system.md`](formal-system.md)).

## Soft Light (cross-category)
Not a garment folder root — doctrine lives in [`translucent-system.md`](translucent-system.md). Pieces are filed in their real categories (`tops/translucent/`, skirts, outerwear, dresses) and assembled in full-looks 04–07. Rhymes with Soft Structure jelly footwear; does not replace it.

## Soft Heat / Warm Season (cross-category)
Capsule map for warm weather: [`warm-season-system.md`](warm-season-system.md). Pulls Soft Structure, Soft Light, shorts, day dress, lightweight blazer, and statement bag into one rotation — not a separate garment root.

## Soft Cold / Cold Season (cross-category)
Capsule map for cool/cold weather: [`cold-season-system.md`](cold-season-system.md). Pulls turtleneck, fleece legging, wool coat, rain/snow boot, scarf, gloves into one rotation — mirror of Soft Heat.

## Soft Formal (cross-category)
Event-layer formal: [`formal-system.md`](formal-system.md). Workhorse midi, cocktail, soft suit, evening wrap, clutch, optional long dress — ceremony-correct without moto or gold. Full looks 11–13.

## Cross-Category Rules

1. **Every item lives in exactly one category/subcategory folder** and follows the priority tiers in [`priority-system.md`](priority-system.md).
2. **Color choices default to the 9-color palette** in `color-system.md` unless the item is explicitly an Experimental/Phase 3 bet.
3. **Hardware is silver-family only**, system-wide — this is a hard rule, not a per-item judgment call, because it's what keeps every accessory compatible with Starlink One by default.
4. **Fit rules from the manifesto apply everywhere**, not just bottoms — rise/inseam gets the most explicit treatment because bottoms was built first, but sleeve length, hem length, and proportion-to-64" apply with equal rigor to tops, outerwear, and dresses when that category is built.
