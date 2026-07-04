# Sonic profile & energy system

Source: Thomas's own sonic-identity self-analysis (childhood sound memory → Queen → Deftones/Eno/Jon Hopkins → Krishna Das). This isn't a Kirtan-only spec — it's the identity that should organize **both** Orchestra mode and Kirtan mode, and it defines the structure Push 2.0 should be built around.

## Part 1 — The Sanctuary Architect identity

Three childhood threads run through everything he's ever been drawn to, devotional or secular:

1. **Close-mic intimacy** — soothed by humming/murmuring as an infant; responds to voice proximity and prosody over performance.
2. **Tactile, mechanical rhythm** — banging on things as a kid; drawn to steady, predictable, hand-made or mechanical pulses.
3. **Structure as antidote to chaos** — hated crowds and erratic wind; craves highly predictable, almost mathematical frameworks that let the guard down completely.

Those three threads show up identically across genres:

| Childhood instinct | Classic rock pivot | Modern/ambient | Devotional |
|---|---|---|---|
| Soft murmurs & hums | Queen's overdubbed vocal walls | Elbow's Guy Garvey (chest-resonant baritone, choir swells) | Kirtan call-and-response |
| Banging on everyday items | Roger Taylor's theatrical drums | Jon Hopkins' tactile organic micro-beats | Tabla / hand-drum tala |
| Hating chaotic wind/crowds | Sinking into the couch, world-building | Brian Eno's static ambient architecture | Drone as sanctuary |

He doesn't consume music, he **occupies** it — treats a track as three-dimensional architecture he steps inside of ("world-building"), and uses it actively to regulate his nervous system. That's also why immersive sound can feel dangerous when he's depleted (took months to let music back in after his worst breakup) — the instrument should be something he chooses to open, not something that overwhelms by default. Worth keeping in mind for how intense/immersive the default patch states are, not something to over-engineer around now.

**Practical takeaway:** the vinyl corpus for Orchestra mode should not be limited to devotional/Indian classical records. Eno- and Hopkins-style ambient, Elbow-style choral/brass, and even Deftones/Queen-adjacent atmospheric material are all valid, on-identity source material.

## Part 2 — The four energies (the organizing structure)

This is the structure that should run through the whole system, Orchestra and Kirtan alike.

| Energy | Traditional domain | Acoustic signature | Devotional exemplar | Secular exemplar | Traditional color |
|---|---|---|---|---|---|
| **Saraswati** | voice, creativity, clarity (Vāc, the veena) | bright, high, fluid, air/water, intellectually complex | Classical Saraswati ragas, veena/sitar | Queen's melodic/harmonic density | White |
| **Shiva** | pulse & stillness | mathematical, repetitive, still — the antidote to chaos | Shiva Tandava Stotra, Om Namah Shivaya loops, damaru | Brian Eno's static ambient architecture | Ash / blue-grey |
| **Ganesha** | earth anchor, root (Mulaudhara) | heavy, low, foot-stomping, unshakeable | Ganesha kirtan (Jai Ganesha, Ganesha Sharanam), low brass, clay drums | Jon Hopkins' tactile organic beats; Rammstein's mechanical pulse | Red / vermillion |
| **Krishna / Hanuman** | devotion, heartbeat, and divine play/sweetness (bhakti prema) | deep, raw baritone, wall-of-voices call-and-response (Hanuman) fused with bansuri-led melodic warmth and playful sweetness (Krishna) | Krishna Das — literally "servant of Krishna," and the whole Neem Karoli Baba/Ram Dass lineage this rig sits in blends Krishna and Hanuman devotion as one continuous practice; also Bhagavan Das ("Govinda"), Nina Rao | Elbow's choir swells, Deftones' whisper-to-wall dynamic, Queen's vocal overdubs | Orange / saffron (Hanuman's sindoor), with Krishna's blue/peacock registers showing up as the melodic-sweetness end of the bank rather than a separate color |

**Why Krishna and Hanuman are one bank, not two:** this rig's own lineage — Neem Karoli Baba, Ram Dass, Krishna Das — doesn't treat Krishna and Hanuman as separate devotional tracks; Krishna Das's name and repertoire *are* that fusion. Splitting them into two quadrants would fragment something that's structurally one energy in the tradition this project draws from. Bansuri (already flagged as a target "warm" instrument below) is Krishna's signature instrument — it belongs in this bank as the melodic/sweet counterweight to Hanuman's heavier, grounded wall-of-voices.

**The Saraswati paradox, and why it matters structurally:** Saraswati is what he's intellectually drawn to (voice, creativity, clarity) but traditional Saraswati music — bright, fast, sitar/veena-driven — doesn't match his acoustic wiring. Krishna Das's own *Saraswati* recording works because he delivers it through **Shiva/Krishna-Hanuman register**: earth/fire grounding an air/water deity. So the Saraswati bank should exist (don't erase what he consciously loves) but should default to a grounded arrangement rather than a bright/airy one — the same move Krishna Das makes.

## Part 3 — Structural mapping onto Push 2.0

**Both Orchestra mode and Kirtan mode organize around these four energies as the primary structural unit.** This replaces "one vinyl source per pad bank" (the original #8 proposal) and "pads select drone root/raga" (the original #17 proposal) with a consistent, energy-first layout that transfers muscle memory between modes.

- **Pad grid:** divide the 8x8 grid into four quadrants (4x4 each), one per energy — Saraswati, Shiva, Ganesha, Krishna/Hanuman. Within a quadrant, pads hold variations/intensity levels for that energy's player or drone+tala combination.
- **Color coding (Push 2 RGB pad protocol):** light each quadrant in its traditional color — white (Saraswati), ash/blue-grey (Shiva), red (Ganesha), orange (Krishna/Hanuman). Within the Krishna/Hanuman quadrant, the register/density encoder (below) sweeps between Hanuman's grounded weight and Krishna's melodic sweetness rather than needing a second color. This gives an instant physical/visual read on which energy is live, in keeping with the "sound is tactile, not abstract" wiring — the instrument should be *felt* at a glance, not just heard.
- **Encoders (consistent across both modes):**
  1. Energy select / crossfade between quadrants
  2. Tempo (vilambit → drut)
  3. Register/density bias (pulls a bank toward brightness or grounding — this is the control that lets you do the "Krishna Das move" and pull Saraswati down into Shiva/Krishna-Hanuman territory, or sweep the Krishna/Hanuman bank itself between bansuri-led sweetness and heavy wall-of-voices weight)
  4. Drone depth
  5–8. Mode-specific: AI morph/temperature in Orchestra mode, call-and-response intensity/AI response speed in Kirtan mode
- **Touchstrip and scene launch stay mode-level** (overall dynamics, structural transitions) — not tied to a single energy.

### Orchestra mode (#8) — vinyl/AI is the point
Each energy quadrant = one RAVE-trained player whose vinyl source matches that energy's acoustic signature (see sourcing table below), not an arbitrary vinyl-source-per-bank assignment. Four coherent voices — Saraswati, Shiva, Ganesha, Krishna/Hanuman — rather than four unrelated timbres. Orchestra mode's whole premise depends on the vinyl → Demucs → RAVE pipeline, so that dependency is unavoidable here.

### Kirtan mode (#17) — instrument path first, AI is an enhancement
Kirtan mode does **not** need to wait on vinyl/RAVE to be playable. Each energy quadrant = a drone root (harmonium-style sampler/VST patch) + tala pattern (Drum Rack of tabla/hand-drum one-shots) + a melodic voice (bansuri for the Krishna/Hanuman bank), all sourced off-the-shelf — see #22. This gets a fully playable instrument onto Push 2.0 without touching Demucs or training a single RAVE model. AI call-and-response (#16) and vinyl-derived texture layer in afterward, on top of a working instrument — they are not prerequisites for one. The raga/tala choices in the Kirtan spec (#13) should still be defined per energy (see table below), just built from instruments first.

## Part 4 — Corpus sourcing per energy

| Energy | Look for | Avoid / use sparingly |
|---|---|---|
| Saraswati | Keep minimal; if sourced, blend under a grounding drone rather than running bright/solo | Sitar, veena, or fast flute run on its own without grounding |
| Shiva | Eno-style static ambient drone; Om Namah Shivaya-style chant records; damaru-adjacent percussion | Anything melodically busy — Shiva's signature is stillness and repetition |
| Ganesha | Jon Hopkins-style tactile organic percussion; heavy low brass/clay drums; Rammstein-style mechanical pulse (Orchestra only) | Light/thin percussion — Ganesha needs weight |
| Krishna / Hanuman | Krishna Das (the anchor reference for this whole bank), Nina Rao, Miten (with Deva Premal), Bhagavan Das ("Govinda"), Shyamdas, Jai Uttal; bansuri flute lines for the Krishna/melodic-sweetness end; Elbow, Deftones, Queen (secular, Orchestra only) | Solo/spotlight vocal delivery — this bank is communal, wall-of-voices, not a soloist showcase |

**General warm/cool markers, applied within any energy bank:**

| | Warm (source this) | Cool/airy (avoid) |
|---|---|---|
| Instrumentation | Harmonium, tabla, bansuri (low register), cello, tanpura drone | Sitar, veena, high-pitched violin, fast flute, cymbals |
| Vocal style | Deep, gravelly, chanting, communal, slow-building | High-pitched, operatic, fast-paced, sharp, solo-focused |
| Tempo | Vilambit (slow) to madhya (medium) | Drut (fast) or erratic/changing time signatures |

## Part 5 — Two build tracks, not one

**Instrument track (start here — no vinyl, playable fast):**
- **#22** Kirtan instrument palette (harmonium drone, tabla, bansuri per energy — off-the-shelf sounds)
- **#14 / #15** Drone and tala layers, built directly on #22's instruments, parameterized per energy (tempo range, register bias) rather than a single global setting
- **#17** Kirtan Push layout — the four-quadrant, color-coded structure, wired to the #22 instruments
- **#13** Kirtan spec — ragas, tala cycles, drone roots defined per energy, targeting the instrument palette

**AI/vinyl track (runs in parallel or after, feeds Orchestra mode + optional Kirtan enhancement):**
- **#1 / #2** Signal chain, Demucs install
- **#4 / #6** First vinyl processed, first RAVE model — source against the Ganesha or Krishna/Hanuman signature first; most forgiving, and most central to the identity
- **#8** Orchestra Push layout — the four-energy-quadrant structure, one RAVE player per energy
- **#16** Kirtan call-and-response — an AI voice layered onto the working instrument from the track above, not a co-requisite for it

Do not let the AI/vinyl track gate the instrument track. A fully playable, four-energy Kirtan instrument on Push 2.0 should exist before any vinyl has been processed.
