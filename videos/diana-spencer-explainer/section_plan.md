# Diana Spencer: Vulnerability as Weapon

## Film Direction

**Palette:** 60% warm paper base (canvas) / 30% hairline rules + repeated canvas layering (no surface token — this preset layers with hairlines) / 10% accent: brand-primary (ink blue) carries hero words, active diagram elements, and the critical stamp beats; brand-accent (crimson) reserved as a single flash for defiance moments only. Deco-4 pink and deco-3 cyan appear as rare particle scribbles only — never as fills.

**Type:** Display tier = hero thesis words and scene-defining terms only. Mono uppercase with wide tracking = eyebrows, datelines, catalog tags (voice: "FIELD REPORT / 1917 / JUNE 1994"). Body = card copy, step labels, supporting context in sentence case. Scribble (Caveat voice) = marginal annotations, one handwritten aside per scene. Hero vs. eyebrow = four-dimensional contrast: size + weight + case + spacing.

**Motion:** Entries on `EASE.entry` (heavy intent for hero words and diagram panels; snappy for chips and pills). Idle on `EASE.drift` at the subtle floor (±2-3 px / ±1-2% scale, 2.5-4s cycle). Exits: scenes hold the final frame (no exit tweens — harness handles Tier-B clip transitions). Budget: ONE root-level macro camera move per scene (slow dolly-in or slow drift) + at most one breathing hero as the secondary live slot; everything else rests.

**Ambient:** Full-bleed paper-grain overlay (from `paper-grain-overlay` component) on every scene — this is the atmospheric constant. No mesh gradients, no dual-radial swell, no scanlines, no halftone on top of it. Paper is the ground.

**Never (film-wide):** No mesh gradients, no bokeh, no purple-blue AI gradients, no neon-on-black, no glow bloom. No counter-rotation to 0° on tilted elements — the off-axis tilt is the system's identity. No bounce or elastic easings.

**Transitions:** Two Tier-B types only: `blur-crossfade` (default — warm backgrounds are close but the emotional shift is large) and `push-slide` (forward narrative momentum moments).

**Stillness-before-climax:** Scenes 6 and 11 only — the ungloved hand reveal and the empty flagpole rupture both earn the dramatic comma.

**Register mix:** Scenes 1/4/8/11/12 = kinetic typography + abstract graphics. Scenes 2/9 = diagram/schematic (family tree, spy-file map). Scenes 3/5/10 = layered abstract graphics with pinned-card clusters. Scenes 6/7 = SVG-led ink-drawing register. Scene 12 = data-viz overview + kinetic type. No captured assets (assetCandidates all empty).

## Scene 1: The Impossible Setup

**Effects:** [`3d-text-depth-layers`, `discrete-text-sequence`, `sine-wave-loop`]
**Duration:** 5.0s
**Continuity:** break
**Transition:** blur-crossfade

**SFX:**

- `impact-bass-1.mp3` at 0.3s, volume 0.4 — hero number "19" slams onto the page

Startled, cold, no fanfare — the paper slaps the desk before the eye is ready. Kinetic typography register, centered composition: a single massive display-tier number "19" occupies 55% of canvas height, three-layer offset shadow (`3d-text-depth-layers`) giving it the weight of a gravestone. `discrete-text-sequence` swaps in three quick text states below it — each a short dateline fragment — landing on the final paradox phrase. Macro motion: hard slow push-in on the scene root across the full 5s. `sine-wave-loop` keeps only the hero number breathing ±1% after it settles. Eyebrow mono chip ("ZERO TRAINING") sits top-left. No supporting cards — the empty space is the pressure. Eye exits into the page-turn cut.

## Scene 2: More Royal Than the Royals

**Effects:** [`svg-path-draw`, `dynamic-content-sequencing`, `sine-wave-loop`]
**Duration:** 6.0s
**Continuity:** break
**Transition:** push-slide RIGHT

Wry, almost dry — a diagram proving an irony too good not to sketch. Diagram register, rule-of-thirds composition: an ink-drawn dual family tree fills the left 65%, with two vertical lineages — Windsor and Spencer — rendered as branching SVG paths that draw themselves via `svg-path-draw`. The Spencer line is taller, older, planted with firmer ink weight. A horizontal dashed connector bridges them at the marriage node. `dynamic-content-sequencing` staggers in the year labels (1917 Windsor name-change vs. Tudor century marks) along the branches, paced to the narration. Mono uppercase dateline eyebrow: "TUDOR LINEAGE / 500 YRS." Macro motion: slow drift left-to-right, parallax on the two columns. `sine-wave-loop` keeps the marriage-node glyph breathing as the single live slot. Eye lands on the family tree's right trunk heading into the next cut.

## Scene 3: The Wound She Carried In

**Effects:** [`asr-keyword-glow`, `card-morph-anchor`, `sine-wave-loop`]
**Duration:** 7.0s
**Continuity:** break
**Transition:** blur-crossfade

Quiet dread, the rhythm slows to a held breath. Layered abstract graphics, asymmetric 60/40 composition: a tall pinned-card (the "diary entry" surface) on the left 60% carries three stacked line-items — the want for a boy, the unnamed week, the footsteps on gravel — each entering in sequence. `asr-keyword-glow` pulses the key wound-words ("unnamed," "loss") as they arrive, a soft ink-blue glow that fades quickly — emphasis, not spectacle. `card-morph-anchor` handles the card's initial drop onto the page (morph from a collapsed strip). Right 40% is intentional negative space: a single fine-ink vertical rule and a scribble marginal note in the Caveat voice ("the palace never read this file"). Macro motion: slow dolly-in on the scene root. `sine-wave-loop` keeps only the marginal scribble drifting ±2px. No glow on the card borders — this is grief, not a feature reveal.

## Scene 4: The Firm

**Effects:** [`3d-text-depth-layers`, `discrete-text-sequence`, `svg-path-draw`]
**Duration:** 6.0s
**Continuity:** break
**Transition:** blur-crossfade

**SFX:**

- `impact-bass-2.mp3` at 0.4s, volume 0.45 — THE FIRM stamp lands

Cold clarity, institutional snap. Kinetic typography + abstract graphics register, centered composition: a massive display-tier headline "THE FIRM" stamps onto the paper with a three-layer ink-shadow (`3d-text-depth-layers`), rotated −4° in the stamp aesthetic. A crimson border-stamp rectangle frames it (brand-accent, single flash). `discrete-text-sequence` cycles three alternate identities below — "Wealth preservation," "Image control," "Zero tolerance" — each replacing the last, machine-gun rhythm. `svg-path-draw` traces a sparse org-chart below the stamp at ~3.5s: three boxes on a hairline hierarchy connected to one block at top labeled THE FIRM. Macro motion: slow push-in on the scene root. No secondary live element — the stamp commands the frame. Eye exits clean into the next cut.

## Scene 5: The Fatal Mismatch

**Effects:** [`split-tilt-cards`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 6.0s
**Continuity:** break
**Transition:** zoom-through

Suffocating, the scale difference is the horror. Layered abstract graphics, split-screen (asymmetric 70/30) composition: two vertically opposed cards side by side with `split-tilt-cards` — left card (large, 70%) shows a simple ink-silhouette figure dwarfed under towering institutional columns (drawn with hairlines at display scale); right card (small, 30%) holds the three corporate-language words: "Bulimia → Glitch / Self-harm → Embarrassment / Depression → Brand risk." `asr-keyword-glow` pulses the relabeled words on the right card as they enter — the glow here reads as the cold eye of corporate review, not warmth. Macro motion: slow zoom-in on the scene root. `sine-wave-loop` keeps the small figure drifting ±2px — alone, not breathing. Accent stays on the word labels only; the figure card is ink on paper with no accent. Eye enters the dissolve into Scene 6 via blur.

## Scene 6: The Ungloved Hand

**Effects:** [`svg-path-draw`, `svg-icon-enrichment`, `sine-wave-loop`]
**Duration:** 6.0s
**Continuity:** break
**Transition:** blur-crossfade

**SFX:**

- `chime.mp3` at 2.8s, volume 0.3 — the hand fully extends; the stillness-before-climax holds

Electrified awe, rhythm pulls back to a single breath. SVG ink-drawing register, centered composition with enormous negative space: a single open hand, drawn in thick ink strokes via `svg-path-draw` starting from the wrist and revealing to the fingertips over ~2.5s, occupies the center 45% of the canvas. `svg-icon-enrichment` adds a subtle pulse in the palm — an ink-ring radiating outward at ~3.0s, suggesting the moment of contact. **Stillness-before-climax:** at ~2.5s the hand is fully drawn; 0.65s of silence holds before the marginal scribble appears ("no glove / 1987") in Caveat voice at the lower right. Mono dateline eyebrow: "AIDS WARD / APRIL 1987." Macro motion: slow drift — the camera barely moves, holding the hand as the subject. `sine-wave-loop` keeps only the ink-ring breathing ±1%. Eye follows the hand as it morphs open toward the crowd in Scene 7 (continue seam).

## Scene 7: The Currency of Empathy

**Effects:** [`center-outward-expansion`, `svg-path-draw`, `sine-wave-loop`]
**Duration:** 7.0s
**Continuity:** continue

Dawning recognition, rhythm expands — the single hand becomes a field. SVG + abstract graphics register, layered-depth composition: the open hand from Scene 6 persists at center, and `center-outward-expansion` drives a cluster of smaller ink-figure silhouettes outward from it — a crowd reaching back, distributed on the canvas at varying scales and opacities to create depth (larger-closer, smaller-farther). `svg-path-draw` traces connecting dashed lines between hand and figures as they land, one arc at a time, like a network diagram being drawn live. Macro motion: slow push-in on the scene root — the crowd expands as the camera moves toward it. `sine-wave-loop` keeps the crowd cluster drifting ±2px as a single correlated mass. Mono eyebrow: "CONSENT THE CROWN COULDN'T MANUFACTURE." At handoff (~6.5s): figures are fully landed at final positions, hand sits at center, dashed arcs are fully traced — ready for the break into Scene 8.

## Scene 8: The Revenge Dress

**Effects:** [`3d-text-depth-layers`, `asr-keyword-glow`, `card-morph-anchor`]
**Duration:** 7.0s
**Continuity:** break
**Transition:** blur-crossfade

**SFX:**

- `ping.mp3` at 0.5s, volume 0.4 — bold silhouette snaps into frame

Fierce exhilaration, sudden and sharp — the silence that buries a story. Kinetic typography + abstract graphics, rule-of-thirds composition: a bold ink-silhouette dress figure is anchored at the upper-left third intersection, occupying ~45% of canvas height. `card-morph-anchor` morphs the silhouette's bounding card from a collapsed headline strip. Tabloid-style strip labels frame the figure — three horizontal ink-band strips (top: "JUNE 1994"; left: "CHARLES ADMITS"; right: "DIANA STEPS OUT") — text set in display tier with tight tracking, heavy weight. `3d-text-depth-layers` gives depth to the key word "OUT" — the word that wins. `asr-keyword-glow` pulses "erased" and "front pages" as the narration passes them (crimson accent flash, then returns to ink). Macro motion: slow drift. No secondary live element beyond the glow pulse. Eye exits toward the classified-file slide right.

## Scene 9: The War of the Tapes

**Effects:** [`svg-path-draw`, `discrete-text-sequence`, `sine-wave-loop`]
**Duration:** 6.0s
**Continuity:** break
**Transition:** push-slide LEFT

Conspiratorial thrill — a diagram drawn in secret. Diagram/schematic register, asymmetric 60/40 composition: a spy-file folder schematic drawn via `svg-path-draw` opens on the left 60% — folder cover, then inside reveals a cassette tape sketch (two reels connected by a tape path drawn live), then three handwritten labels appear on the tape ("Session 1," "Session 2," "SMUGGLED"). Right 40% holds a route diagram: a dashed-line path from a palace silhouette outline (hairlines) to a bicycle icon (ink mark) to an open book/pages (the author). `discrete-text-sequence` pulses a secondary text strip cycling: "PALACE → BASKET → AUTHOR." Macro motion: slow dolly-in on the scene root. `sine-wave-loop` keeps the cassette reels rotating — the single live element within the drawing. Stamp in top-right: "CLASSIFIED / RECEIVED" rotated −4°. Eye exits via push-slide into the ink-splash opening of Scene 10.

## Scene 10: The Cultural Canvas

**Effects:** [`scale-swap-transition`, `asr-keyword-glow`, `sine-wave-loop`]
**Duration:** 6.0s
**Continuity:** break
**Transition:** blur-crossfade
**Hierarchy:** simple

Unsettled complexity — the same face in fragments, no single reading. Layered abstract graphics, triptych composition: three equal-width panels each carry a different ink rendering of the same abstract face-silhouette (a Rorschach-style ink-blot structure, same base shape, rotated and mirrored). `scale-swap-transition` drives each panel entering — the center panel first (scale in), then left and right (coordinated shrink-in/spring-out from center outward). `asr-keyword-glow` pulses the key term "canvas" in the eyebrow chip at ~3.5s — brand-primary glow, soft. Below each panel, a short label in mono uppercase: "THE ESTABLISHMENT" / "THE MARGINALIZED" / "THE MIRROR." Macro motion: slow drift, all three panels correlated. `sine-wave-loop` keeps only the center panel breathing ±1% — the focal point. No accent on the panels themselves — the labels do the semantic work. Eye exits clean into the stark cut of Scene 11.

## Scene 11: The Empty Flagpole

**Effects:** [`svg-path-draw`, `3d-text-depth-layers`, `sine-wave-loop`]
**Duration:** 7.0s
**Continuity:** break
**Transition:** blur-crossfade

**SFX:**

- `impact-bass-1.mp3` at 0.1s, volume 0.35 — the bare pole appears on the cut
- `whoosh-cinematic.mp3` at 0.0s, volume 0.25 — cinematic swell rising through the scene

Grief turning to vindication — a single object as argument. Kinetic typography + abstract graphics, centered composition with extreme negative space: a single ink flagpole drawn vertically via `svg-path-draw` from base to top over ~1.5s, flag-end bare, halts. The pole occupies 15% of canvas width, centered, with the empty flag-end suggesting absence without labeling it. Below the pole, a one-word display-tier statement enters in three-layer offset shadow via `3d-text-depth-layers`: "CRUELTY." — the word the public read in the empty flagpole. **Stillness-before-climax:** at ~4.5s, after "CRUELTY." lands, 0.6s of silence holds before the counter-statement arrives: a smaller body-tier line beneath — "Queen breaks protocol. Grief. Public." — entering on `EASE.entry`. Macro motion: slow push-in on the scene root, barely perceptible. `sine-wave-loop` keeps only the pole itself drifting ±1.5px — alone, upright, still. Eye exits into the zoom-out of Scene 12.

## Scene 12: The Blueprint

**Effects:** [`center-outward-expansion`, `asr-keyword-glow`, `svg-path-draw`]
**Duration:** 7.0s
**Continuity:** break
**Transition:** zoom-through

Haunted recognition — all the sketches connect, and the playbook is still running. Data-viz / kinetic typography, layered-depth composition: opens on a wide view suggesting a notebook spread — all 11 prior visual motifs represented as small thumbnail sketches at varying positions across the canvas (drawn via `svg-path-draw` in staggered sequence, total stagger ~450ms), connecting to each other with hairline dashed arcs. `center-outward-expansion` drives the arc-lines radiating outward from a central node labeled "THE BLUEPRINT." At ~4.5s, `asr-keyword-glow` pulses the words "playbook" and "still running" in the hero headline — display tier, centered, brand-accent (crimson) flash only here, last accent beat in the film. Macro motion: slow pull-back (counter of the zoom-through transition), revealing the whole map. The final frame: notebook map fully drawn, headline centered, a closing ink stamp "WRITTEN IN BLOOD" rotated −4° at lower-right. No secondary live element after the arc-draw completes — settle and hold for the final 2s.
