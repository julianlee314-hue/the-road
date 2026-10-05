# The Road — Career Mode Story Bible

> Education first: the curriculum is the medicine, the race is the sugar.
> Original 60s cartoon-racing spirit. No borrowed names, logos, characters, or car designs.

---

## Premise

Rulestown is a place where the roads only open for licensed drivers. Every plate on your dashboard is a racing license. Every topic is a lesson you prove on the track.

You arrive as a rookie with an empty garage and a borrowed car. A retired champion named **Marge Kettle** takes you on. She lost the biggest race of her life years ago by rushing one step — and she will not let you make the same mistake.

Somewhere on every circuit is a quiet racer in a plain helmet and an unmarked grey car. He races you. He beats you. He leaves clues. He is not your enemy.

Career Mode walks plates **1 through 9** (Precedence → Quadratics), where the skill is the *right order of moves*. Plates **10–15** are a lighter epilogue tour through Tube City. Calculus stays **The Sky** — a sequel hook, not this career.

---

## Cast

### You (the player)

- **Role.** Rookie driver, new to Rulestown.
- **Look.** Simple cream-and-red car with an *x²* door badge (same car as the splash). A helmet that starts plain and gains stickers as plates stamp.
- **Voice.** Mostly silent. The game speaks through Marge, Pip, and the Masked Driver’s clues.
- **Arc.** Learns that speed without order is a spin-out. Ends Act III ready for The Sky.

### Marge Kettle

- **Role.** Mentor. Retired champion. Mechanic. Owner of Kettle Garage.
- **Look.** Mid-sixties, silver hair in a bandana, oil-stained cream coveralls with a red stripe, thick black outline glasses she pushes up when she’s about to say something important. Always holding a wrench or a chalk stub.
- **Personality.** Warm, blunt, never cruel. She tells the truth about her crash without melodrama. She celebrates clean drives louder than fast ones.
- **Voice.** Short coaching lines. Garage metaphors. Example: *“Brackets first. Corners first. Same idea.”*
- **Secret.** Her son left town after the crash. She doesn’t know he’s been racing as the Masked Driver — until the reveal.

### The Masked Driver → Cole Kettle

- **Role.** Apparent rival. Secret friend. Real competition.
- **Look (masked).** Plain charcoal helmet with a cream stripe, unmarked grey car, no number, no sponsor stickers. Moves clean. Never celebrates.
- **Look (unmasked).** Late twenties, Marge’s jawline, quiet eyes. Same grey car, now with a small cream kettle painted on the hood.
- **Personality.** Precise. Patient. Competitive for real — he will not gift you a win. He drops clues because he wants you ready, not because he wants easy races.
- **Voice.** Almost none while masked. Notes under the wiper. Chalk on asphalt. One spoken line at the reveal.
- **Arc.** Left after Marge’s crash so no one would go easy on him. Came back under a mask to make sure the next driver through Kettle Garage wouldn’t rush the step she rushed.

### Pip

- **Role.** Pit crew. Marge’s grandkid (Cole’s niece/nephew). Asks the questions a student would ask.
- **Look.** Twelve-ish, overalls two sizes too big, clipboard, cream sneakers with red laces. Always chewing a pencil.
- **Personality.** Curious, a little chaotic, fiercely loyal. Spots the Masked Driver’s car before anyone else does.
- **Voice.** Questions. *“Why do matching parts only?”* *“What if I just… skip that?”*

---

## Why plates 1–9

| Plate | Math | Why it belongs in career |
|------:|------|--------------------------|
| 1 | Precedence | The racing line *is* order. |
| 2 | Powers | Combining like gears — same-base morphs. |
| 3 | Simplify | Matching parts only. |
| 4 | Expand | Distributing seats to every passenger. |
| 5 | Factor | Reverse-engineering what was multiplied. |
| 6 | Isolate | Same move on both lanes. |
| 7 | Inequalities | Track limits; flip when you reverse. |
| 8 | Systems | Two cars, one finish time. |
| 9 | Quadratics | The jump ramp’s arc — where it lands. |

Plates 10–15 still teach real math, but the “order of moves” metaphor thins out. They’re co-driver sightseeing: short strips, Hyperloop hops, light story. Calculus (Limits onward) is **The Sky** — another road, another career.

---

## Chapter flow (every plate)

1. **Comic strip** — 3–4 panels, wordless or nearly wordless, 60s limited animation (bold poses, speed lines, sound words).
2. **Guided drive** — the plate’s existing tutorial level, with one **Marge tip** on screen.
3. **Timed drills** — the plate’s levels, using existing Order / Calculate and the clock (30s · 1 min · 3 min · Endless).
4. **Stamp** — existing stamp rules. Stamping a level can unlock a Masked Driver clue.
5. **Act race** (end of Acts I–III) — Order or Calculate against his ghost time. Precision wins; a miss is a spin-out.

No gameplay code changes in this doc. Career Mode will *wrap* the levels, stamps, and modes already live.

---

## Act I — Street Circuit

Hometown lamps. Short corners. The racing line is drawn in chalk before every race.

### Chapter 1 · Permit · Precedence
**Title.** *The Racing Line*

**Math (plain).** Do the insides of brackets (and other high-priority ops) before the rest. Order matters.

**Racing metaphor.** The racing line through a corner has a sequence. Take it out of order and you spin.

**Comic strip (4 panels) — mock: `career/strip-1.html`**
1. You approach a tight lamp-post corner. Roadside signs flash `+`, `×`, `( )`.
2. The Masked Driver’s grey car threads the perfect line and passes you. **WHOOSH!**
3. You look down. Chalk on the asphalt: a big **`( )`**.
4. Cut to Kettle Garage. Marge taps the chalk mark on a blackboard: brackets first. Pip raises a hand.

**Marge’s tip.** *“Brackets first. Corners first. Same idea.”*

**Clue.** Chalk `( )` on the track after he passes you.

**Reward.** Permit road opens. First Masked Driver sighting logged in the garage scrapbook.

---

### Chapter 2 · Operator · Powers
**Title.** *Matching Gears*

**Math (plain).** Same-base powers multiply by adding exponents, divide by subtracting, and a power of a power multiplies exponents. Coefficients multiply separately.

**Racing metaphor.** Matching gears combine into a higher gear. Wrong gear = grind.

**Comic strip (4 panels)**
1. Garage workbench: two gears labeled `x³` and `x²` sitting apart.
2. You (or Pip) push them together. They morph into one gear: `x⁵`. Speed lines. **CLICK!**
3. A napkin under your wiper: `x³(x²)` → `x⁵` (no multiplication dots — just touching / brackets).
4. Marge nods at the napkin. The Masked Driver’s grey car is already gone from the alley.

**Marge’s tip.** *“Same base, same gear. Combine the teeth. Write the new power.”*

**Clue.** Napkin under the wiper: `x³(x²)`.

**Reward.** Operator plate drills unlock. Combine-exponents morph is the “universal” Powers gesture.

---

### Chapter 3 · Road · Simplify
**Title.** *The Parts Bin*

**Math (plain).** Only like terms combine — same variable and power (or constants). Keep pairing until nothing matches, then you’re done.

**Racing metaphor.** A mechanic only bolts matching parts together. Unlike parts stay in their bins.

**Comic strip (4 panels)**
1. Parts bins labeled `3x`, `2`, `5x`, `−4`. Pip tries to bolt `3x` to `2`. It won’t fit. **NOPE.**
2. You tap `3x` (yellow) then `5x` (green). They combine to `8x`.
3. Act I race start: checkered banner, Street Circuit. The Masked Driver’s grey car lines up beside you.
4. Finish: he wins by half a car length. His tire track cuts a perfect S through the like-terms chicane. You stare at the track marks.

**Marge’s tip.** *“Yellow, then green if they match. Red if they don’t. Hit Done when the bin is sorted.”*

**Clue / appearance.** Act I race. He wins by half a car. Tire track shows the perfect like-terms line.

**Reward.** Road license path completes. Act I scrapbook page stamps. Rival ghost time saved for rematches.

---

## Act II — Country Rally

Dust, hills, long straightaways. Mistakes cost more out here.

### Chapter 4 · Sport · Expand
**Title.** *Every Passenger Gets a Seat*

**Math (plain).** Distribution: the outside term multiplies every term inside the brackets.

**Racing metaphor.** One ticket collector walks the whole coach — every passenger gets a seat check.

**Comic strip (3–4 panels)**
1. A stagecoach with passengers `a`, `b`, `c`. A conductor holding `2` outside the door.
2. The conductor tags each passenger: `2a`, `2b`, `2c`. **STAMP STAMP STAMP.**
3. Ghost run: the Masked Driver’s car appears ahead for one clean lap of the expand line, then vanishes into the hills.
4. Pip: “He just… showed us?” Marge: “Pay attention.”

**Marge’s tip.** *“Outside reaches everyone inside. Don’t leave a passenger unchecked.”*

**Appearance.** Ghost run once — clean order, then gone.

**Reward.** Sport drills. Optional “ghost tip” replay on this chapter’s tutorial.

---

### Chapter 5 · Competition · Factor
**Title.** *What’s Inside the Engine*

**Math (plain).** Factoring undoes expanding — find what was multiplied to build this expression.

**Racing metaphor.** Reverse-engineer an engine: open the hood, find the common parts that built it.

**Comic strip (4 panels)**
1. Factory floor. A sealed engine crate stamped `6x + 9`.
2. You open it: gears `3` and `(2x + 3)` click into place.
3. Pip points out the window — the Masked Driver’s grey car is parked outside the factory. No driver visible.
4. A cream kettle sketch is chalked faintly on the factory brick (easy to miss).

**Marge’s tip.** *“Ask what was multiplied. Pull the common factor out front.”*

**Appearance.** Pip spots his car outside the factory. Faint kettle chalk on the wall (foreshadow).

**Reward.** Competition drills. Scrapbook “mystery kettle” sticker if you notice the chalk.

---

### Chapter 6 · Algebra · Isolate
**Title.** *Clearing Both Lanes*

**Math (plain).** Whatever you do to one side of an equation, you do to the other — until *x* stands alone.

**Racing metaphor.** Road crew clears both lanes the same way so the finish stays fair.

**Comic strip (4 panels)**
1. Two parallel lanes painted `=` between them. Traffic piled on both sides.
2. Same move on left and right: tow a `+3`, tow a `+3`. Balance holds.
3. Act II race. A debris crash slides toward you. The Masked Driver swerves, takes the hit, and you shoot through.
4. You cross first. He doesn’t stop. Grey car disappears into the dust. No wave.

**Marge’s tip.** *“Same move, both sides. Leave x alone at the finish.”*

**Appearance.** Act II race — he blocks a crash for you. You win for the first time. He leaves without talking.

**Reward.** Algebra path. First career win logged. Pip: “Why didn’t he stay?”

---

## Act III — Grand Tour

City lights. Bigger crowds. The Masked Driver stops pretending he’s only a shadow.

### Chapter 7 · Advanced · Inequalities
**Title.** *Track Limits*

**Math (plain).** Inequalities are boundaries. Multiply or divide by a negative and the inequality flips.

**Racing metaphor.** Stay inside the painted track limits. Drive in reverse and the limit arrow flips.

**Comic strip (3–4 panels)**
1. A track with painted limits `x > 2`. Your car hugs the legal side.
2. You reverse through a gate. The arrow on the limit sign flips. **FLIP!**
3. Clue on a roadside board: an arrow drawn backwards in grey chalk.
4. Marge in the garage flips a physical arrow card on the blackboard.

**Marge’s tip.** *“Negatives reverse the car — and the inequality.”*

**Clue.** Backwards arrow on a sign.

**Reward.** Advanced drills. Track-limits HUD accent for inequality cards.

---

### Chapter 8 · Expert · Systems
**Title.** *Two-Car Relay*

**Math (plain).** Two equations, one solution that satisfies both.

**Racing metaphor.** A two-car relay — both drivers’ times have to match the plan.

**Comic strip (4 panels)**
1. Two cars on a relay map: yours (cream-red) and his (grey).
2. Split paths labeled Eq 1 and Eq 2, meeting at a single checkpoint.
3. He partners with you for one race only — same line, same finish time. **SYNC.**
4. After the line he nods once (still masked) and peels off.

**Marge’s tip.** *“Both equations have to agree. One finish. One pair (x, y).”*

**Appearance.** He partners with you once. Real teamwork, then gone.

**Reward.** Expert drills. Dual-ghost overlay unlocked for rematches.

---

### Chapter 9 · Unlimited · Quadratics
**Title.** *Where the Ramp Lands*

**Math (plain).** Quadratics describe a parabola — find the roots, the vertex, where it lands.

**Racing metaphor.** The jump ramp’s arc. You don’t guess the landing. You calculate it.

**Comic strip (4 panels)**
1. A huge jump ramp. A dashed parabola arcs over the city.
2. Finale race: no ghost help. Him beside you. Checkered sky.
3. You land clean. He lands clean. At the line he unbuckles the charcoal helmet.
4. Cole Kettle. Marge’s son. He looks at you, then at the garage on the hill: *“I didn’t want you to rush the step she rushed.”*

**Marge’s tip.** *“Find where it lands. Guessing the ramp is how champions crash.”*

**Appearance / reveal.** Real race, no help. Helmet off: **Cole Kettle**. Left after Marge’s crash, raced masked so no one went easy, stayed to keep you from her mistake.

**Reward.** Unlimited license. Career Act III complete. Marge and Cole share a quiet garage scene. Hook line for the epilogue.

---

## Act races

| Act | When | Format | Stakes |
|-----|------|--------|--------|
| I | After Simplify (ch. 3) | Ghost time, Street Circuit | He wins by half a car. Tire-track clue. |
| II | After Isolate (ch. 6) | Ghost + rescue beat | He blocks a crash. You win. He leaves. |
| III | After Quadratics (ch. 9) | Head-to-head, no help | Reveal. Career climax. |

Races use existing Order / Calculate and clock settings. Misses = spin-out puffs (splash language). Clean streaks = boost speed lines.

---

## The reveal

Cole’s clues, in order, so a careful player can guess early:

1. Chalk `( )` — cares about order (ch. 1)
2. Napkin `x³(x²)` — knows Powers morphs (ch. 2)
3. Perfect like-terms tire track (ch. 3)
4. Ghost expand lap (ch. 4)
5. Faint kettle chalk at the factory (ch. 5) ← biggest hint
6. Blocks a crash, won’t talk (ch. 6)
7. Backwards arrow (ch. 7)
8. Partners once, nods (ch. 8)
9. Helmet off: Cole Kettle (ch. 9)

Marge’s reaction: pride, a little anger, a long hug. Pip: “I *knew* the grey car smelled like the garage.”

---

## Epilogue — Tube City (plates 10–15)

You and Cole co-drive city to city. Light story. Short strips. Hyperloop hops (see `VEHICLES.md`).

| Ch. | Plate | Math | City beat | Strip idea |
|----:|------:|------|-----------|------------|
| 10 | Commercial | Rationals | Old Canal District | Fractions as bridges — numerator over denominator spans. |
| 11 | Heavy | Radicals & logs | Undercity Tube | Squaring / unsquaring as opening a hatch; logs as “how many doublings.” |
| 12 | Function | Functions | Route Reader Hub | Machines that take an input ticket and stamp an output. |
| 13 | Sketch | Transforms | Shift Gate | The tube bends: slide, flip, stretch the graph-road. |
| 14 | Degree | Polynomials | Freight Yards | Longer trains = higher degree. |
| 15 | Growth | Exponentials | Boost Spire | Every checkpoint the beam doubles. |

**Final panel of ch. 15.** You and Cole on a rooftop. He points at the sky.

> “There’s another road up there.”

That’s the handoff to **The Sky** (Limits → Complex) — Mathera 2.0, not this career.

---

## Hooking into what already exists

Career Mode is a **wrapper**, not a rewrite.

| Existing | Career use |
|----------|------------|
| Plates 1–15 & stamps | Chapters gate on stamps / road tests already earned. |
| Tutorial levels | Guided drives with Marge tip overlay. |
| Order / Calculate | Act races and drills. |
| Clock (30s / 1 / 3 / Endless) | Career practice and act races. |
| Splash art language | Comic strips, rival ghost, spin-out / boost FX. |
| Scrapbook (new UI later) | Clues, kettle stickers, Act pages. |
| The Sky teasers (16–22) | Stay locked; epilogue points up. |

**Not in this pass:** no menu link, no code changes to gameplay, no altering stamp rules. Story bible + Act I strip mock only.

---

## Tone & art notes

- Ages **8+** for early acts; Act III can lean a touch older without getting dark.
- Wordless or nearly wordless panels. Sound words: **VROOM**, **SKREE**, **WHOOSH**, **CLICK**, **FLIP**, **SYNC**.
- Palette: red `#e2352c`, cream `#fff2d2`, sky `#73c6ec`, ink `#121212`, thick outlines, flat fills, speed lines.
- Limited animation mindset even in stills: bold held poses, one motion per panel.
- Math notation in story: **no multiplication dots**. Write `x³(x²)` or touching letters.

---

## Deliverables checklist

- [x] This bible — `CAREER.md`
- [x] Act I ch. 1 strip mock — `career/strip-1.html`
- [ ] Career menu entry (later)
- [ ] Remaining strips (later)
- [ ] Rival ghost / scrapbook UI (later)
