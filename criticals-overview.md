# Critical Hit Tables — Overview & Comparison

## Project Status

| System | Status | Notes |
|--------|--------|-------|
| **WFRPG** | ✅ Fully ready | All 9 weapon types × 4 body parts × 15 levels complete |
| **PF2** | 🔶 Mostly done | ~6/15 completed per Head/Body, ~3/15 per Arms/Legs. TODO entries exist for levels 7+ (some inconsistencies in penalty values remain) |
| **WWN** | ✅ Mechanical migration done | All 12 weapon types migrated to WWN mechanics. Bleed restructured (no body parts). Narrative text preserved from WFRPG/PF2. See [wwn-critical-migration-guide.md](mdc:wwn-critical-migration-guide.md) |

### WWN Completion Detail

Mechanical penalties migrated from WFRPG/PF2 to WWN (Mar 2026). Changes made:

- **Saves:** Will → Mental, Fortitude → Physical, Reflex → Evasion
- **Skills:** Medicine → Int/Heal, Athletics → Exert, Perception → Notice, Administer First Aid → Dex/Heal
- **DCs:** PF2 difficulty modifiers → WWN DC values (DC 6–14)
- **Conditions:** sickened N → –N to all rolls, slowed 1 → Slowed, slowed 2 → Stunned, flat-footed → –2 AC, dazzled → Blinded
- **WFRPG stats:** Fel → Charisma, IP → System Strain, W characteristic → HP
- **Bleed:** Restructured from 4 body parts to "Wounds" (no body parts), 15 new entries created
- **All TODO markers removed** from all 12 weapon types

| Weapon Type | Head | Body | Arms | Legs | Wounds |
|-------------|------|------|------|------|--------|
| Arrow | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Blunt | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Bullet | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Claws | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Cutting | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Flame | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Piercing | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Explosion | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Unarmed | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | 15/15 ✅ | — |
| Mental | — | — | — | — | 15/15 ✅ |
| Poison | — | — | — | — | 15/15 ✅ |
| Bleed | — | — | — | — | 15/15 ✅ |

### PF2 Completion Detail

| Weapon Type | Head | Body | Arms | Legs |
|-------------|------|------|------|------|
| Arrow | 6/15 | 6/15 | 6/15 | 3/15 |
| Blunt | 6/15 | 6/15 | 6/15 | 3/15 |
| Bullet | 6/15 | 6/15 | 3/15 | 3/15 |
| Claws | 6/15 | 6/15 | 3/15 | 6/15 |
| Cutting | 6/15 | 6/15 | 3/15 | 3/15 |
| Flame | 6/15 | 6/15 | 3/15 | 3/15 |
| Piercing | 6/15 | 6/15 | 3/15 | 3/15 |
| Explosion | 6/15 | 6/15 | 3/15 | 3/15 |
| Unarmed | 6/15 | 6/15 | 3/15 | 3/15 |
| Bleed | 0/15 | 0/15 | 0/15 | 0/15 |

---

## Severity Tiers (Official)

| Tier | WFRPG Levels | PF2 Levels |
|------|-------------|------------|
| Minor | 1–6 | 1–7 |
| Major | 7–9 | 8–12 |
| Severe | 10–15 | 13–15 |

---

## Mechanical Severity Groups

The 15 levels can be divided into **7 mechanical groups** based on the actual game-mechanics impact (not narrative flavour). These groups work across both systems.

| Group | Levels | WFRPG Tier | PF2 Tier | Mechanical Theme |
|-------|--------|-----------|----------|------------------|
| **I — Scratch** | 1–2 | Minor | Minor | Brief numeric penalty, 1 turn |
| **II — Light Wound** | 3–4 | Minor | Minor | Short conditions (stunned/slowed 1 turn), knocked down, penalty for a few turns |
| **III — Wound** | 5–6 | Minor | Minor | Extended conditions with saves to remove, dropped weapons, rest-of-battle minor penalties begin |
| **IV — Serious Wound** | 7–9 | Major | Major (PF2 8–9) / Minor (PF2 7) | Extended stunning/helplessness (d10/2 turns / 1d4 turns), useless limbs, fractures, permanent minor penalties |
| **V — Critical Wound** | 10–12 | Severe | Major (PF2 10–12) | Permanent major disabilities, cumulative bleeding, death risk without magic, lost eyes/limbs, paralysis |
| **VI — Mortal Wound** | 13–14 | Severe | Severe | Dying within d10/2 / 1d4 turns; only magic (if anything) can save |
| **VII — Death** | 15 | Severe | Severe | Instant death |

---

## Comparison Tables by Body Part

Below, for each body part the typical mechanical penalties are listed per group for each game system. Penalties are **aggregated across weapon types** (they follow very similar patterns; weapon-specific notes are below each table). Ranges (with dashes) or averages are used where values vary slightly across weapon types.

### HEAD

| Group | WFRPG Penalties | PF2 Penalties |
|-------|----------------|---------------|
| **I (1–2)** | –10% to –20% WS for 1 turn; lose 1 attack/parry | –1 to –2 attack for 1 turn; lose 1 action |
| **II (3–4)** | –10% to –20% WS for 1–d10/2 turns; stunned 1 turn; blood in eyes (–20% WS until wiped); possible drop weapon | Frightened 1; slowed 1 for 1 turn; dazzled (blood in eyes, repeating DC 6 flat check) |
| **III (5–6)** | Stunned 1 turn + saves to recover (WP or T); helpless until save; –10% WS rest of battle; –5% Fel permanent possible; hearing loss possible | Slowed 1 with saves to end; dazzled (repeating); sickened 2; –1 to Charisma-based checks |
| **IV (7–9)** | Stunned d10/2 turns; –20% all tests; fractured jaw/skull; –10% to –20% Fel permanent; infection risk (death in d10 days); cumulative –5% to –10% per turn (larynx crush) | *(mostly TODO)* Sickened 2–5; slowed 2 for 1d6 turns; stunned; –4 attack; frightened 2; removal checks required |
| **V (10–12)** | Lost eye (BS & sight-Perception halved); stunned until battle end; permanent –10% to –20% to WS/BS/Ag/Int/Fel; unconscious + death risk from brain bleed; infection risk | *(TODO)* Stunned until battle end; permanent –1 to all; lost eye; death risk from infection (1d4–1d6 days) |
| **VI (13–14)** | Unconscious; paralysis (neck down); dying in d10/2 turns; no mundane save | *(TODO)* Prone + dying in 1d4 turns; only very hard magic can save |
| **VII (15)** | Instant death | *(TODO)* Instant death |

**Weapon-specific notes (Head):**
- **Flame (WFRPG):** Clothes/hair on fire mechanics; permanent Fel loss from scarring (–10% to –20%); mute from fused voice box at lv 7–8
- **Flame (PF2):** Fire-catching actions; permanent scarring requires Medicine check to address; hearing loss from crisped ear
- **Blunt/Unarmed (WFRPG):** Concussion-focused; skull fracture → trepanation mechanics at lv 8; jaw breaks
- **Arrow/Bullet (WFRPG):** Projectile removal mechanics (requiring Heal/Ag tests, full actions); projectile lodged penalties persist until removed
- **Arrow/Bullet (PF2):** Removal requires Medicine or Thievery/Athletics checks; sickened condition while projectile lodged

---

### BODY

| Group | WFRPG Penalties | PF2 Penalties |
|-------|----------------|---------------|
| **I (1–2)** | –10% to –20% WS for 1 turn; lose half-action / 1 attack | –1 to –2 attack for 1 turn; –1 AC for 1 turn; frightened 1 |
| **II (3–4)** | –20% WS for 1 turn; stunned 1 turn; knocked prone; –20% parry; possible –10% WS d10/2 turns | Sickened 1; slowed 1 for 1 turn; prone (Fort save); –2 attack for 1d4 turns |
| **III (5–6)** | –10% to –20% WS d10/2 turns or rest of battle; stunned 1 turn; helpless until saves; post-battle infection risk (spleen); weapon lodged penalties | –2 to –4 attack until removed (Medicine check); sickened 1–2 with saves; prone + unable to use legs (Fort saves); flat-footed; post-battle infection risk (Tetanus) |
| **IV (7–9)** | Stunned d10 turns; helpless d10/2 turns; –20% to –30% all tests; M–2; fractures; useless until healed; cumulative –5% per turn (bleeding); infection risk (d10 days death) | *(mostly TODO)* Stunned; sickened 4; –4 all tests; slowed 2; cumulative sickened 1/turn; prone; death from infection risk |
| **V (10–12)** | Helpless d10 turns; cumulative –10% to –15% per turn to WS/BS/Ag/S (bleeding); permanent paralysis (waist down); –20% all tests; collapsed lung (20% death/turn); only magic saves | *(TODO)* –4 all tests; 50% chance collapsed lung; cumulative –2 to –3 per turn; permanent paralysis; death without magic |
| **VI (13–14)** | Helpless; dying in d10/2 turns to d10 turns; entrails spilled; only very hard magic can save | *(TODO)* Helpless; dying in 1d4–1d6 turns; no mundane save |
| **VII (15)** | Instant death | *(TODO)* Instant death |

**Weapon-specific notes (Body):**
- **Flame (WFRPG):** Clothes on fire (Ag tests to extinguish); permanent –10% S from chest muscle damage; inhaled flame → suffocation risk; exposed bone → infection
- **Flame (PF2):** Fire-catching actions (Reflex saves); dazzled from fire leaping to hair; permanent S reduction
- **Blunt (WFRPG):** Cardiac arrhythmia (T test or die at lv 9); pericardial sack bleed (cumulative –15%/turn, no save at lv 13)
- **Cutting (WFRPG):** Weapon lodged in hip mechanics; gallbladder/bladder puncture with infection; entrails spilled
- **Piercing (WFRPG):** Deep penetration; nicked heart (cumulative –10%/turn); collapsed lung
- **Explosion (WFRPG):** Shrapnel embedded; peritonitis risk post-battle; multiple organ damage

---

### ARMS

| Group | WFRPG Penalties | PF2 Penalties |
|-------|----------------|---------------|
| **I (1–2)** | –10% WS for 1 turn; WP test or drop weapon; lose 1 attack/parry | –1 to –2 attack for 1 turn; Will save or drop item |
| **II (3–4)** | Arm numb/useless for d10/2 turns; –20% WS 1 turn; drop weapon; –10% to –20% WS/S that arm for d10 turns | Drop weapon + arm numb 1 turn; –2 attack for 1d4 turns; Fort/Will saves or drop |
| **III (5–6)** | Drop + arm useless until projectile/condition removed; –20% WS that arm for battle; stunned 1 turn; permanent –5% to –10% fine manipulation; half SB that arm | –2 to –4 attack for 2d4 turns; arm useless until wounded removed; permanent –1 to –2 manipulation; flat-footed |
| **IV (7–9)** | Stunned d10/2 to d10 turns; arm useless until W restored; –20% to –30% all tests; permanent –10% to –20% WS/manipulation; fractures (collarbone, elbow); cumulative –5%/turn (arterial bleed) | *(mostly TODO)* Stunned 1d4–1d6 turns; arm useless; –4 all tests; sickened 4; permanent –2 attack with that arm |
| **V (10–12)** | Arm permanently paralyzed/useless; cumulative –5% to –10% per turn (arterial); –20% all tests; severed fingers (–5% per finger); amputation needed; death risk from gangrene (d10 days) | *(TODO)* Permanent arm paralysis; cumulative sickened 1–2/turn; amputation needed; gangrene death risk (1d6 days) |
| **VI (13–14)** | Unconscious; arm severed; dying in d10/2 to 2d10 turns from blood loss; only magic saves | *(TODO)* Unconscious; arm torn off; dying in 1d4 turns |
| **VII (15)** | Instant death (weapon through armpit into chest/heart) | *(TODO)* Instant death |

**Weapon-specific notes (Arms):**
- **Arrow/Bullet (WFRPG):** Projectile embedded mechanics; removal requires full actions + Heal/Ag tests; lodged projectile maintains penalties
- **Arrow/Bullet (PF2):** Removal via Medicine/Thievery checks; some projectiles permanently reduce W by 1
- **Claws (WFRPG):** Ripping/tearing; fingers removed; infection risk from filthy claws; arm ripped off at elbow/shoulder
- **Claws (PF2):** Cumulative sickened from bleeding (stops at sickened 4); infection from filthy claws
- **Cutting (WFRPG):** Severed fingers (d10/2); arm severed at elbow/shoulder; arterial spray
- **Blunt (WFRPG):** Fractures (wrist, forearm, collarbone, elbow); dislocated shoulder; crushed joints; nerve damage
- **Flame (WFRPG):** Charred fingers/elbow; arm burned off; fire on clothes spread mechanics; permanent –20% WS/Ag/S from scarring
- **Unarmed (WFRPG):** Dislocations; broken fingers; snapped wrist/elbow; throws

---

### LEGS

| Group | WFRPG Penalties | PF2 Penalties |
|-------|----------------|---------------|
| **I (1–2)** | –10% WS for 1 turn; lose 1 attack/parry; stumble | –1 attack for 1 turn; –3 next attack; –5 ft movement 1 turn |
| **II (3–4)** | –20% WS 1 turn; M halved d10/2 turns; Dodge Hard (–20%) d10/2 turns; stunned 1 turn; knocked prone | –2 attack for 1 turn; prone (Fort save); M halved for 1d4 turns; Reflex saves Hard (+2) |
| **III (5–6)** | –10% all tests d10 turns; stunned 1 turn; M–2; Dodge Hard (–20%) rest of battle; permanent M–1 risk; foot pinned (M=0 until removed) | Slowed 1 for 1 turn; dazzled (foot injury); –2 attack for 2d4 turns; flat-footed; M halved with Fort saves; permanent –1 AC risk |
| **IV (7–9)** | Stunned d10/2 turns; helpless d10/2 turns; –20% all tests rest of battle; M reduced to 1; Dodge Very Hard (–30%); fractures; useless leg until W restored; permanent M–1 to M–2; Dodge Challenging (–10%) permanent | *(mostly TODO)* Stunned 1d4 turns; sickened 2–4; M–2; Dodge Hard (+2); permanent M–5 ft; useless leg until wounded removed |
| **V (10–12)** | Helpless d10 to d10 turns; permanent M halved or M–2; Dodge Hard/Very Hard permanent; cumulative –5% to –10% per turn (femoral bleed); fractures require 4–6 weeks healing; amputation risk from gangrene | *(TODO)* –4 all tests; permanent M halved; Dodge Hard (+2) permanent; cumulative sickened/penalties; amputation risk |
| **VI (13–14)** | Unconscious; femoral artery severed; dying in d10/2 turns; leg torn off; inevitable death from blood loss | *(TODO)* Prone; dying in 1d4–1d6 turns; femoral artery severed; leg torn off |
| **VII (15)** | Instant death (pelvis shattered, major arteries severed) | *(TODO)* Instant death |

**Weapon-specific notes (Legs):**
- **Arrow (WFRPG):** Foot pinned to ground (M=0 until removed); projectile in knee causes permanent M–1 and Dodge Challenging
- **Bullet (WFRPG):** Hip joint lodged bullet; gangrene risk; permanent M halved from shattered kneecap; infection from wadding
- **Cutting (WFRPG):** Severed Achilles tendon; severed hamstrings; foot/leg amputated; weapon lodged in thighbone
- **Blunt (WFRPG):** Shattered kneecap; dislocated hip; crushed ankle; open fractures through skin
- **Claws (WFRPG/PF2):** Kneecap torn out; hamstrings severed; toes ripped off; leg ripped off at knee/hip
- **Flame (WFRPG):** Burned-off toes/foot; fused knee joint (permanent M=1, Dodge –30%); clothes on fire; charred stump
- **Explosion (WFRPG):** Shrapnel in knee (requires Surgery to remove); nerve damage → permanent paralysis; shrapnel amputation
- **Unarmed (WFRPG):** Dislocated hip; broken ankle/shinbone; popped kneecap; broken metatarsals

---

## Summary of Penalty Equivalences Between Systems

| WFRPG Mechanic | PF2 Equivalent |
|----------------|----------------|
| –10% WS for 1 turn | –1 attack for 1 turn |
| –20% WS for 1 turn | –2 attack for 1 turn |
| –10% WS for d10/2 turns | –1 attack for 1d4 turns |
| –20% all tests | –4 all tests / sickened 4 |
| –30% all tests | –5 to –6 all tests / sickened 5 |
| Stunned | Slowed 1–2 / Stunned |
| Helpless | Stunned / Paralyzed |
| Knocked down | Prone |
| Dodge Blow Challenging (–10%) | Flat-footed or AC–1 |
| Dodge Blow Hard (–20%) | Reflex saves Hard (+2 DC) |
| Dodge Blow Very Hard (–30%) | Reflex saves Very Hard (+5 DC) |
| M–1 | Movement –5 ft |
| M–2 | Movement –10 ft |
| M halved | Movement halved |
| WP test or drop weapon | Will save or drop item |
| T test or fall unconscious | Fortitude save or unconscious |
| Cumulative –5%/turn (bleeding) | Cumulative sickened 1/turn |
| Cumulative –10%/turn (arterial) | Cumulative sickened 2/turn |
| Heal test (Surgery Talent) | Medicine check (Expert proficiency) |
| Challenging (–10%) test | Challenging (+1 DC) check |
| Hard (–20%) test | Hard (+2 DC) check |
| Very Hard (–30%) test | Very Hard (+5 DC) check |
| Insanity Point (IP) | (no direct equivalent; narrative) |
| Fel reduction | Charisma penalty |
| d10 / d10/2 | 1d6 / 1d4 |

---

## Weapon Types

Both systems share the same weapon/damage types with body-part-specific tables:

| Weapon Type | Has Body Parts | Notes |
|-------------|---------------|-------|
| Arrow | Yes | Ranged; projectile embedded/removal mechanics |
| Blunt | Yes | Fractures, concussions, internal bleeding |
| Bullet | Yes | Ranged; projectile lodged; infection from wadding |
| Claws | Yes | Tearing; infection from filthy claws; savage removal |
| Cutting | Yes | Slashing; severing; weapon lodging |
| Flame | Yes | Burns; fire-catching; scarring; inhaled flame |
| Piercing | Yes | Deep penetration; organ damage; withdrawal mechanics |
| Explosion | Yes | Shrapnel; mixed piercing/cutting; fragment embedding |
| Unarmed | Yes | Bruises; breaks; dislocations; grapple/throw |
| Mental | No (Wounds only) | PF2: 3/15 completed; WWN: 15/15 migrated |
| Poison | No (Wounds only) | PF2: 3/15 completed; WWN: 15/15 migrated |
| Bleed | No (Wounds only, WWN) | PF2: 0/15; WWN: 15/15 (new entries, no body parts) |
