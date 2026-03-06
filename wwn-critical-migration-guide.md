# WWN Critical Hit Migration Guide

Guide for translating WFRPG and PF2 critical hit effects into WWN (Worlds Without Number) mechanics.
See also [criticals-overview.md](mdc:criticals-overview.md) and [wwn-combat-modifiers.md](mdc:wwn-combat-modifiers.md).

---

## Penalty Equivalences Between Systems

### Hit Roll Modifiers

| WFRPG | PF2 | WWN |
|---|---|---|
| –10% WS/BS | –1 attack | **–1 to hit** |
| –20% WS/BS | –2 attack | **–2 to hit** |
| –30% WS/BS | –3 attack | **–3 to hit** |
| –40% WS/BS | –4 attack | **–4 to hit** |
| –60% WS/BS | –6 attack | **–6 to hit** |

### All-Tests / Global Penalties

| WFRPG | PF2 | WWN |
|---|---|---|
| –10% all tests | Sickened 1 | **–1 to hit, saves, and skill checks** |
| –20% all tests | Sickened 2–4 | **–2 to hit + disadvantage on saves and skill checks** |
| –30% all tests | Sickened 5–6 | **–4 to hit + disadvantage on all rolls** |

### Conditions

| WFRPG | PF2 | WWN |
|---|---|---|
| Stunned (1 turn) | Stunned 1 / Slowed 1 | **Stunned** — speed halved, disadvantage on attacks/saves/checks, no spells |
| Helpless | Stunned (extended) / Paralyzed | **Paralyzed** — no actions, attacks auto-hit |
| Knocked Down | Prone | **Prone** — –4 own melee attacks; adjacent enemies +2 to hit; distant ranged –2 to hit |
| Blinded | Blinded | **Blinded** — no ranged attacks; attackers have advantage; disadvantage on melee and sight-based saves |
| Deafened | Deafened | **Deafened** — cannot hear; immune to auditory effects |
| On Fire (clothes/hair) | Persistent fire damage | **Ignited** — 1d6 damage/turn; Luck save or Readied items take Item Damage |
| Dying (T test per turn) | Dying 1–4 | **Mortally Wounded** — incapacitated; dies in 6 rounds; stabilize via Int/Heal or Dex/Heal vs DC (10 + rounds MW); healer's pouch –2 DC |
| Critically Injured | Wounded (dying on next 0 HP) | **Frail** — dies at 0 HP; cannot naturally regain HP; 1 week bedrest or Int/Heal check to cure |

### Movement

| WFRPG | PF2 | WWN |
|---|---|---|
| M–1 | –5 ft Speed | **–5 ft movement** |
| M–2 | –10 ft Speed | **–10 ft movement** |
| M halved | Speed halved | **Movement halved** |
| M=0 | Immobilized | **Movement = 0** (Restrained or pinned) |
| M=1 | Speed 5 ft | **Movement = 5 ft** |

### Skill / Save Checks

| WFRPG | PF2 | WWN |
|---|---|---|
| WP test | Will save | **Mental save** |
| T test | Fortitude save | **Physical save** |
| Ag test / Reflex | Reflex save | **Evasion save** |
| Challenging (–10%) | Challenging (+1 DC) | **DC 6** (Challenging) |
| Hard (–20%) | Hard (+2 DC) | **DC 8** (Hard) |
| Very Hard (–30%) | Very Hard (+5 DC) | **DC 10** (Very Hard) |
| Formidable (–40%) | Incredibly Hard (+10 DC) | **DC 12** (Incredibly Hard) |
| Heal test (Surgery) | Medicine check (Expert) | **Int/Heal** check (specific DC) |

### Duration

| WFRPG | PF2 | WWN |
|---|---|---|
| 1 turn | 1 round | **1 round** |
| d10/2 turns | 1d4 rounds | **1d4 rounds** |
| d10 turns | 1d6 rounds | **1d6 rounds** |
| Rest of battle | Until end of encounter | **Rest of encounter** |
| Permanent | Permanent | **Permanent** (requires magic or long-term rest) |

### Cumulative Bleeding

| WFRPG | PF2 | WWN |
|---|---|---|
| –5% per turn (bleeding) | Sickened +1/turn | **–1 to all rolls per round** (bleeding) |
| –10% per turn (arterial) | Sickened +2/turn | **–2 to all rolls per round** (arterial bleeding) |
| –15% per turn (massive) | Sickened +3/turn | **–3 to all rolls per round** (massive hemorrhage) |

### Other Mechanics

| WFRPG | PF2 | WWN |
|---|---|---|
| Drop weapon (WP test) | Drop item (Will save) | **Mental save or drop weapon** |
| Infection (d10 days death) | Infection (1d6 days death) | **Physical save or Sickened** → death in **1d6 days** without Int/Heal DC 8+ |
| Permanent –5% Fel | –1 Charisma | **–1 Charisma** (permanent) |
| Permanent –10% WS | –1 attack (permanent) | **–1 to hit** (permanent) |
| Lost eye | Lost eye | **Blinded (one eye):** –4 to Shoot; disadvantage on Wis/Notice for sight |
| Severed limb | Severed limb | Limb destroyed; **Frail** from shock; requires magic to restore |
| Insanity Point | (narrative) | **+1 System Strain** or narrative trauma |
| d10 / d10÷2 | 1d6 / 1d4 | **1d6 / 1d4** |

---

## Severity Tiers

Using PF2 tier ranges:

| Tier | Levels | Description |
|------|--------|-------------|
| **Minor** | 1–7 | Superficial to moderate injuries; temporary penalties; no lasting harm |
| **Major** | 8–12 | Serious injuries; extended incapacitation; permanent penalties possible; death risk from complications |
| **Severe** | 13–15 | Mortal wounds or instant death; only powerful magic can save (if anything) |

---

## Mechanical Severity Groups

### Group I — Scratch (Levels 1–2)

**Expected WWN penalties:**

- **–1 to –2 to hit** for 1 round
- Lose **On Turn Action** (minor action loss)
- **Mental save** or drop weapon (arms only)
- **–5 ft movement** for 1 round (legs only)
- No lasting effects

### Group II — Light Wound (Levels 3–4)

**Expected WWN penalties:**

- **–2 to hit** for 1–1d4 rounds
- **Stunned** for 1 round (speed halved, disadvantage on all rolls)
- **Prone** (Evasion save to avoid)
- **Mental save** or drop weapon
- Minor bleeding effects (cosmetic, easily stopped)
- Movement halved for 1d4 rounds (legs)
- No permanent effects

### Group III — Wound (Levels 5–6)

**Expected WWN penalties:**

- **–2 to –4 to hit** for 1d6–2d4 rounds
- **Stunned** 1 round + **Physical save** each round to end
- **Slowed** (lose Move Action) with saves to end
- Limb partially useless until condition treated (Int/Heal DC 6–8)
- Lodged projectiles / weapon fragments require removal (Int/Heal check)
- Possible **permanent –1** to specific skill or attribute
- Infection risk post-battle (Physical save DC 6)
- **+1 System Strain**

### Group IV — Serious Wound (Levels 7–9)

**Expected WWN penalties:**

- **Stunned** for **1d4–1d6 rounds**
- **–4 to hit** and/or disadvantage on all rolls
- Limb **useless** until HP fully restored
- Fractures (4–6 weeks natural healing)
- **Permanent –1 to –2** to hit or specific attribute
- Cumulative bleeding: **–1 to all rolls per round** (Physical save DC 8 to stabilize)
- Infection risk: **Physical save DC 8** or death in **1d6 days** without Int/Heal treatment
- **+1d4 System Strain**

### Group V — Critical Wound (Levels 10–12)

**Expected WWN penalties:**

- **Paralyzed** for 1d4–1d6 rounds (or rest of encounter)
- **Permanent** major disability: lost eye (–4 to Shoot, disadvantage on Wis/Notice), permanent limb paralysis, permanent movement halved
- Cumulative arterial bleeding: **–2 to all rolls per round** (dies when any attribute effectively reaches 0)
- **Frail** condition (dies at 0 HP, cannot naturally regain HP)
- Death without magic within **1d6 turns/days**
- **Permanent –2 to –4** to attribute(s)
- Amputation may be required to prevent death (gangrene)
- **+1d6 System Strain** (likely Strained)

### Group VI — Mortal Wound (Levels 13–14)

**Expected WWN penalties:**

- **Mortally Wounded** — dies in **1d4 rounds** unless stabilized
- Stabilization requires **magical healing** (mundane Int/Heal insufficient or DC 12+)
- Even if saved: **Frail** + permanent major disability
- Severed limbs / destroyed organs
- **Maximum System Strain**

### Group VII — Death (Level 15)

**Expected WWN penalties:**

- **Instant death** — no saves, no stabilization
- Descriptively spectacular

---

## Critical Effects by Body Part

All tables below use **WWN mechanics only**. Weapon-specific variations follow each table.

### HEAD

| Group | WWN Mechanical Effect |
|-------|----------------------|
| **I (1–2)** | –1 to –2 to hit for 1 round. Lose On Turn action. |
| **II (3–4)** | –2 to hit for 1d4 rounds. Stunned 1 round. Mental save or drop weapon. Blood in eyes: Blinded until 1 action spent wiping; DC 6 flat check each round or blood returns until wound bandaged (Int/Heal DC 6). |
| **III (5–6)** | Stunned 1 round, then –2 to hit with Physical save each round to end. Slowed (lose Move Action) until Physical save. Deafened possible (ear injury). Permanent –1 Charisma (scarring). +1 System Strain. |
| **IV (7–9)** | Stunned 1d6 rounds. –4 to hit rest of encounter. Fractured jaw/skull — cannot speak or eat normally. Permanent –1 to –2 Charisma. Cumulative –1 to all rolls/round (internal bleeding). Infection: Physical save DC 8 or death in 1d6 days. +1d4 System Strain. |
| **V (10–12)** | Lost eye: –4 to Shoot, disadvantage on Wis/Notice (sight). Paralyzed rest of encounter. Permanent –1 to all checks. Death risk from brain hemorrhage: Physical save DC 10 each round or Mortally Wounded. +1d6 System Strain. |
| **VI (13–14)** | Prone + Mortally Wounded (dies in 1d4 rounds). Possible spinal cord damage → permanent Paralyzed (neck down). Only magical healing can save (effective DC 10+). Maximum System Strain. |
| **VII (15)** | Instant death. |

**Weapon-specific notes (Head):**

- **Arrow/Bullet:** Projectile lodged; maintains penalties until removed. Removal: Int/Heal DC 8 (2 Main Actions). Failed removal: nicks artery → Mortally Wounded.
- **Blunt/Unarmed:** Concussion-focused. Group III+: Physical save or Unconscious (0 HP non-lethal, revive in 10 min). Skull fracture at Group IV requires Int/Heal DC 10 trepanation.
- **Claws:** Infection risk one tier worse (filthy claws). Tearing removes flesh → worse scarring (extra –1 Charisma).
- **Cutting:** Clean cuts; easier healing (Int/Heal at –1 DC). Severed features (nose, ear) at Group IV+.
- **Flame:** Ignited condition (hair/clothes). Permanent Charisma damage one tier worse (burns/scarring). Group IV: Deafened permanent (crisped ear). Group V: Suffocating (inhaled flame).
- **Piercing:** Deep penetration; organ damage. Group IV+: projectile removal mechanics similar to Arrow.
- **Explosion:** Shrapnel fragments (multiple small projectiles). Each fragment: –1 to hit until removed. Int/Heal DC 8 per fragment.

---

### BODY

| Group | WWN Mechanical Effect |
|-------|----------------------|
| **I (1–2)** | –1 to –2 to hit for 1 round. Lose On Turn or Move action. |
| **II (3–4)** | –2 to hit for 1d4 rounds. Stunned 1 round. Prone (Evasion save to avoid). +1 System Strain. |
| **III (5–6)** | –2 to –4 to hit until condition treated (Int/Heal DC 6–8). Slowed until Physical save. Prone. Infection risk post-battle: Physical save DC 6 or Sickened (disease within 1 day). Lodged projectile/fragment: penalties persist until removed. +1 System Strain. |
| **IV (7–9)** | Stunned 1d6 rounds. –4 to all rolls rest of encounter. Slowed. Cumulative –1 to all rolls/round (bleeding). Prone. Fractures — useless until HP restored. Infection: Physical save DC 8 or death in 1d6 days. +1d4 System Strain. |
| **V (10–12)** | Paralyzed 1d6 rounds. Cumulative –2 to all rolls/round (arterial). Collapsed lung: Luck save each round or die. Permanent Paralyzed (waist down) possible: Physical save DC 10 or permanent. Frail. Only magic saves. +1d6 System Strain. |
| **VI (13–14)** | Paralyzed + Mortally Wounded (dies in 1d4–1d6 rounds). Entrails/organs exposed. No mundane save possible. Maximum System Strain. |
| **VII (15)** | Instant death. |

**Weapon-specific notes (Body):**

- **Arrow/Bullet:** Projectile lodged under ribs or in cavity. Removal: Int/Heal DC 6–8 (3 Main Actions). Failed removal: additional HP damage + delayed healing (recover 1 fewer HP next rest).
- **Blunt/Unarmed:** Internal organ damage. Group IV: cardiac arrhythmia — Physical save or instant death. Group V: pericardial bleeding → cumulative –3/round, no stabilization without magic.
- **Claws:** Ripping/tearing; worse infection risk. Filthy claws: infection saves at +2 DC.
- **Cutting:** Weapon may lodge in hip/rib. Removal: Str/Stab opposed check or Int/Heal DC 8. Gallbladder/organ puncture → infection.
- **Flame:** Ignited condition (clothes). Inhaled flame at Group IV+: Suffocating. Permanent –1 Str from chest muscle damage. Exposed bone → infection (Physical save DC 8).
- **Piercing:** Deep penetration. Group IV+: nicked heart — cumulative –2/round. Collapsed lung possible one tier earlier than other weapon types.
- **Explosion:** Shrapnel embedded in multiple locations. Peritonitis risk post-battle (Physical save DC 8). Multiple organ damage: treat as one severity group worse.

---

### ARMS

| Group | WWN Mechanical Effect |
|-------|----------------------|
| **I (1–2)** | –1 to –2 to hit for 1 round. Mental save or drop weapon held in that hand. |
| **II (3–4)** | Drop weapon. Arm numb/useless for 1 round. –2 to hit for 1d4 rounds. Mental or Physical save or drop held items. +1 System Strain. |
| **III (5–6)** | –2 to –4 to hit for 2d4 rounds. Arm useless until wound treated (Int/Heal DC 6–8). Permanent –1 to checks requiring fine manipulation with that hand. +1 System Strain. |
| **IV (7–9)** | Stunned 1d4–1d6 rounds. Arm useless until HP fully restored. –4 to all rolls. Fractures (collarbone, elbow). Permanent –2 to hit with that arm. Cumulative –1/round (arterial bleed). Infection: Physical save DC 8 or death in 1d6 days. +1d4 System Strain. |
| **V (10–12)** | Arm permanently paralysed/useless. Cumulative –2 to all rolls/round (arterial). Severed fingers (–1 per finger to that hand's checks). Amputation needed to prevent gangrene: Physical save DC 10 or death in 1d6 days. Frail. +1d6 System Strain. |
| **VI (13–14)** | Unconscious (0 HP non-lethal → Mortally Wounded). Arm severed/torn off. Mortally Wounded — dies in 1d4 rounds. Only magic saves. Maximum System Strain. |
| **VII (15)** | Instant death (weapon through armpit into chest/heart). |

**Weapon-specific notes (Arms):**

- **Arrow/Bullet:** Projectile embedded. Removal: Int/Heal DC 6–8 (2–3 Main Actions). Lodged in bone: Int/Heal DC 8 and 3 Main Actions. Failed removal: additional damage + delayed healing.
- **Blunt/Unarmed:** Fractures, dislocations. Wrist/forearm breaks at Group III. Dislocated shoulder at Group IV. Crushed joints → permanent –2 to that arm. Snapped elbow: arm useless permanently without magic.
- **Claws:** Tearing; fingers removed. Infection from filthy claws (save DC +2). Arm ripped off at elbow/shoulder at Group V–VI.
- **Cutting:** Severed fingers (1d4 at Group V). Severed tendons → permanent loss of grip. Arterial spray at Group V+. Arm severed at elbow/shoulder at Group VI.
- **Flame:** Ignited condition (clothes spread to body). Charred fingers/hand. Permanent –2 Str and –2 Dex for that arm from scarring. Arm burned off at Group VI.
- **Piercing:** Deep penetration; nerve damage. Brachial plexus damage at Group V: arm permanently Paralyzed unless magically healed within 1 day (Int/Heal DC 10).
- **Explosion:** Shrapnel in multiple locations. Each fragment: separate removal check. Nerve damage from blast wave → permanent –1 to that arm at Group IV+.

---

### LEGS

| Group | WWN Mechanical Effect |
|-------|----------------------|
| **I (1–2)** | –1 to hit for 1 round. –5 ft movement for 1 round. Stumble (cosmetic). |
| **II (3–4)** | –2 to hit for 1 round. Prone (Evasion save to avoid). Movement halved for 1d4 rounds. Evasion saves at Hard DC (DC 8) during that time. +1 System Strain. |
| **III (5–6)** | –2 to hit for 2d4 rounds. Slowed 1 round. Movement halved with Physical save to end. Evasion saves at Hard DC rest of encounter. Permanent –5 ft movement risk (Physical save DC 8 to avoid). +1 System Strain. |
| **IV (7–9)** | Stunned 1d4 rounds. –4 to all rolls rest of encounter. Movement reduced to 5 ft. Leg useless until HP restored. Evasion saves at Very Hard DC (DC 10). Permanent –5 to –10 ft movement. Permanent Evasion saves at Challenging DC (DC 6). Fractures. +1d4 System Strain. |
| **V (10–12)** | Paralyzed (helpless) 1d4–1d6 rounds. Permanent movement halved. Permanent Evasion saves at Hard DC (DC 8). Cumulative –1 to –2/round (femoral bleed). Fractures require 4–6 weeks healing. Amputation risk from gangrene: Physical save DC 10. Frail. +1d6 System Strain. |
| **VI (13–14)** | Unconscious. Femoral artery severed. Mortally Wounded — dies in 1d4–1d6 rounds. Leg torn off. No mundane save. Maximum System Strain. |
| **VII (15)** | Instant death (pelvis shattered, major arteries severed). |

**Weapon-specific notes (Legs):**

- **Arrow:** Foot pinned to ground (movement = 0 until removed; removal: 2 Main Actions, both hands). Projectile in knee: permanent –5 ft movement + Evasion saves at Challenging DC.
- **Bullet:** Hip joint lodged; gangrene risk (Physical save DC 8). Shattered kneecap: permanent movement halved. Infection from wadding: Physical save DC 6 post-battle.
- **Blunt/Unarmed:** Shattered kneecap; dislocated hip; crushed ankle. Open fractures at Group V (bone through skin → infection). Broken metatarsals: –10 ft movement permanent.
- **Claws:** Kneecap torn out. Hamstrings severed (leg useless). Toes ripped off. Leg ripped off at knee/hip at Group V–VI. Infection: save DC +2.
- **Cutting:** Severed Achilles tendon (permanent movement halved, Evasion saves Very Hard DC). Severed hamstrings. Foot/leg amputated at Group V–VI. Weapon lodged in thighbone.
- **Flame:** Ignited (clothes spread). Burned-off toes/foot. Fused knee joint: permanent movement = 5 ft, Evasion saves Very Hard DC. Charred stump at Group VI.
- **Piercing:** Deep thigh wound; nerve damage. Femoral artery nick at Group IV (cumulative –1/round, Physical save DC 8 to tourniquet). Deep organ damage in hip at Group V.
- **Explosion:** Shrapnel in knee (requires Int/Heal DC 8 surgery to remove). Nerve damage → permanent Paralyzed leg. Blast amputation at Group VI.

---

### BLEED (No Body Parts — General Wounds)

Bleed effects represent ongoing hemorrhage from any wound source. They have no specific body-part location and stack with location-specific criticals.

| Group | WWN Mechanical Effect |
|-------|----------------------|
| **I (1–2)** | Minor seeping wound. –1 to hit for 1 round. Physical save DC 6 to staunch (On Turn action). |
| **II (3–4)** | Moderate bleeding. –2 to hit until wound treated (Int/Heal DC 6, 1 Main Action). +1 System Strain. |
| **III (5–6)** | Persistent bleeding. Cumulative –1 to all rolls per round until staunched (Int/Heal DC 8, 2 Main Actions). Slowed from blood loss. +1 System Strain. |
| **IV (7–9)** | Heavy bleeding. Cumulative –1 to all rolls per round. Physical save DC 8 each round or lose additional –1 (accelerating). Stunned 1 round from blood loss. Unconscious when total penalty reaches –6. +1d4 System Strain. |
| **V (10–12)** | Arterial bleed. Cumulative –2 to all rolls per round. Frail. Unconscious when total penalty reaches –6, then Mortally Wounded. Only magic or Int/Heal DC 10 (3 Main Actions) can stop. +1d6 System Strain. |
| **VI (13–14)** | Massive hemorrhage. Cumulative –3 to all rolls per round. Mortally Wounded within 1d4 rounds. Only powerful magical healing can save. Maximum System Strain. |
| **VII (15)** | Instant exsanguination — death. |

**Notes on Bleed:**

- Bleed effects **stack** with body-part critical bleeding effects
- Multiple bleed sources use the **highest** cumulative rate, +1 per additional source
- Staunching a bleed wound requires both hands free and appropriate tools (healer's pouch reduces Int/Heal DC by 2)
- Cauterization (applying Flame): stops bleeding instantly but deals 1d6 damage and may cause Ignited; Physical save DC 6 or permanent scar (–1 Charisma)

---

*Last updated: Mar 2026. Based on WWN mechanics from [wwn-combat-modifiers.md](mdc:wwn-combat-modifiers.md) and critical tables from [criticals-overview.md](mdc:criticals-overview.md).*
