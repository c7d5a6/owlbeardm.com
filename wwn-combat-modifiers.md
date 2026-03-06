# WWN Combat — Buffs, Penalties & Modifiable Values

Source: [kedom.owlbeardm.com — WWN Combat](https://kedom.owlbeardm.com/guide/rules/wwn/combat.html)

---

## WWN Core Mechanics

### Attack Rolls

Attack rolls use **d20** (same as Pathfinder 1e / D&D). Roll d20 + combat skill + class attack bonus + attribute modifier vs target's Armor Class.

### Saving Throws

Four saves. DC is **constant per level**: **15 – character level** (minimum 1).

| Save | Covers |
|---|---|
| **Physical** | Enduring bodily harm — poison, disease, exhaustion, death effects |
| **Evasion** | Dodging area effects, traps, explosions |
| **Mental** | Resisting psychic attacks, illusions, compulsions, fear |
| **Luck** | Random misfortune, effects that bypass other saves |

### Skill Rolls

Skills use **2d6 + skill rank + attribute modifier** vs a Difficulty Class.

**Skill ranks:** –1 (untrained), 0 (basic), 1, 2, 3, 4

**Difficulty scale:**

| Rank of Difficulty | DC | Label |
|---|---|---|
| Untrained | 6 | Challenging |
| Trained | 8 | Hard |
| Expert | 10 | Very Hard |
| Master | 12 | Incredibly Hard |
| Legendary | 14 | Near Impossible |

**Cross-system difficulty mapping:**

| WWN DC | WWN Label | WFRPG Test Difficulty | PF2 DC Adjustment |
|---|---|---|---|
| 6 | Challenging | Challenging (–10%) | Standard (DC 15) |
| 8 | Hard | Hard (–20%) | Hard (+2 DC) |
| 10 | Very Hard | Very Hard (–30%) | Very Hard (+5 DC) |
| 12 | Incredibly Hard | Formidable (–40%) | Incredibly Hard (+10 DC) |
| 14 | Near Impossible | Heroic (–50%) | Nearly Impossible (+15 DC) |

### Skill List

| Skill | Primary Use in Combat / Criticals |
|---|---|
| **Administer** | Organize logistics, identify treachery — non-combat |
| **Connect** | Find useful people, call on organizations — non-combat |
| **Convince** | Persuade; covers social pressure and morale effects |
| **Craft** | Repair shields, weapons, patch wounds with tools |
| **Exert** | Run, swim, climb, jump, throw, labor — physical feats; used for Shoving and grapple-adjacent actions |
| **Heal** | Stabilize Mortally Wounded allies, treat wounds, cure disease/poison; critical for post-crit recovery |
| **Know** | History, geography, natural science — academic lore |
| **Lead** | Inspire and command followers; affect NPC morale |
| **Magic** | Cast/analyze spells; lore about magic and mages |
| **Notice** | Spot ambushes, hidden objects, sensory details — used in Surprise checks (Wis/Notice) |
| **Perform** | Sing, orate, compose; social/entertainment |
| **Pray** | Religious rites, divine lore, identify holy figures |
| **Punch** | Fight unarmed / natural weapons; grapple and brawl — unreliable without a Focus |
| **Ride** | Ride mounts, drive carts, care for animals |
| **Sail** | Sail/repair ships, navigate, manage sailors |
| **Shoot** | Fire bows, crossbows, throw ranged weapons — used in ranged attack rolls |
| **Sneak** | Move silently, hide, pick pockets/locks, defeat traps — used in Surprise checks (Dex/Sneak) |
| **Stab** | Fight with melee weapons — core combat skill for hit rolls, Dual-Wield, Shoving, Shield Shattering, Screening |
| **Survive** | Hunt, navigate, mitigate hazards, craft basic tools |
| **Trade** | Buy/sell, appraise goods, black-market dealings |
| **Work** | Catch-all profession skill; varies by background |

**Combat-relevant skills at a glance:**

| Situation | Skill Used |
|---|---|
| Melee attack roll | Stab |
| Ranged attack roll | Shoot |
| Unarmed / grapple | Punch |
| Shoving a foe | Str/Stab opposed check |
| Shattering a shield | Str/Stab opposed check |
| Screening an ally (blocking) | Str/Dex + combat skill (Stab/Shoot/Punch) |
| Surprise (attacker) | Dex/Sneak |
| Surprise (defender) | Wis/Notice |
| Stabilizing a downed ally | Int/Heal or Dex/Heal |

### Conditions

Conditions are ongoing detrimental (or situational) effects imposed by abilities, attacks, or environment. Most end via a set duration, a successful skill check, or a saving throw. Secondary conditions listed in parentheses are lifted automatically when the primary condition ends, but lost System Strain and Ability Score damage must be recovered normally.

| Condition | Mechanical Effect | How to End |
|---|---|---|
| **Blinded** | Cannot use ranged attacks or abilities. Immune to visual effects. Attackers have **advantage** vs Blinded creature. Blinded creature has **disadvantage** on melee attacks and sight-based saves. | Cure the source (magic, remove blindfold, etc.) |
| **Cursed** | Suffers an ill effect listed in parentheses. | Lift the curse (specific process per curse) |
| **Deafened** | Cannot hear. Immune to auditory effects. Can still be damaged by destructive sonic waves. | Cure the source |
| **Dissolving** | Takes **1d6 damage** at start of turn. At end of turn: Luck save or all Readied corrosion-susceptible items gain 1 point of Item Damage. | Remove contact with corrosive material |
| **Enthralled** | Must follow commands of the enthraller (issued as On Turn actions). Suicidal/nature-violating orders allow a **Mental save** to break free. | Varies by source: incapacitate enthraller (Psychic), dispel (Magic), antidote (Disease/Poison) |
| **Frail** | Dies at 0 HP. Cannot naturally regain HP. | 1 week bedrest **or** DC Int/Heal check (one attempt only) |
| **Grappled** | Cannot move. Can only attack with unarmed strikes. Takes automatic unarmed damage from grappler at end of each round. | Succeed on contested **Str/Punch** check |
| **Ignited** | Takes **1d6 damage** at start of turn. At end of turn: Luck save or all Readied fire-susceptible items gain 1 point of Item Damage. | Spend Main + Move action to stop/drop/roll; ally spends Main Action to beat out flames; immersion in water |
| **Invisible** | Cannot be seen. Melee attacks against invisible creature take **–4 to hit**. Ranged attacks are impossible. | End the effect/spell |
| **Mortally Wounded** | Completely incapacitated. Dies in **6 rounds** unless stabilized. Stabilization: Dex/Heal or Int/Heal vs DC (10 + rounds Mortally Wounded); healer's pouch reduces DC by 2. Stabilized → becomes Frail. | Stabilize (see above) |
| **Paralyzed** | Cannot take any action, use any ability, or succeed on any save requiring motion or vocalization. Attack rolls against Paralyzed creature **automatically hit**. | End the source effect |
| **Petrified** | Turned to stone. AC becomes **22**. Cannot be carried as Readied/Stowed. Suspended: no HP recovery, no System Strain recovery, but immune to ongoing effects. Damage dealt while petrified may kill upon cure. | Kill associated creature or complete a Major Project |
| **Poisoned** | Suffers the effect listed in parentheses for the duration. | Antidote, Purge Ailment, or similar |
| **Prone** | Melee attacks made at **–4 to hit**. Ranged attacks against prone creature: **–2 to hit**. Melee attacks against prone creature: **+2 to hit**. | Spend a **Move Action** to stand up |
| **Restrained** | Speed becomes **0 ft**. Disadvantage on any roll requiring motion. Cannot cast spells or use weapons larger than a shortsword. Attack rolls against Restrained creature are made with **advantage**. | End the source (cut bonds, end spell, etc.) |
| **Sickened** | Suffers the effect listed in parentheses; may be consistent or compound over time. | Purge Ailment or similar; or disease recovery rules |
| **Slowed** | Loses their **Move Action**. | End of condition duration |
| **Strained** | At maximum System Strain. Cannot normally heal or use certain abilities. Certain abilities trigger additional effects "if Strained". | Reduce System Strain (rest, etc.) |
| **Stunned** | Speed **halved**. Disadvantage on attack rolls, saves, and skill checks requiring focus. Cannot cast spells. | End of scene (unless imposed as part of another condition) |
| **Suffocating** | Runs out of air after **1 round per point of Constitution**. Once out of air, takes damage equal to **Hit Dice** per round. Remaining still quadruples the time. NPCs assumed to have Con 10. | Reach air |
| **Swallowed** | Gains Restrained + Suffocating. Takes damage equal to swallower's **Hit Dice** at start of each turn. | Swallower dies **or** deal damage to swallower ≥ its Hit Dice |

**Advantage / Disadvantage in WWN:** Roll twice and take the better (advantage) or worse (disadvantage) result.

**Cross-system condition mapping:**

| WWN Condition | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Blinded** | Blinded (–WS/BS; enemy +WS/BS) | Blinded |
| **Deafened** | Deafened | Deafened |
| **Dissolving** | Acid damage per turn | Persistent acid damage + item damage |
| **Enthralled** | Dominated / Charmed | Controlled / Fascinated |
| **Frail** | Critically Injured / Dying slowly | Wounded (dying on next 0 HP) |
| **Grappled** | Grappled (no movement, limited attacks) | Grabbed |
| **Ignited** | On Fire (1d6/turn, clothes spread) | On Fire — persistent fire damage + item damage |
| **Invisible** | Invisible (–40% to hit / impossible ranged) | Invisible |
| **Mortally Wounded** | Dying (T test per turn or die in d10 turns) | Dying 1–4 |
| **Paralyzed** | Paralyzed (no actions, auto-hit) | Paralyzed |
| **Petrified** | Petrified (rare, GM-specific) | Petrified |
| **Poisoned** | Poisoned (custom effects) | Poisoned |
| **Prone** | Knocked Down (–20% attacks, enemy +10%) | Prone |
| **Restrained** | Restrained (speed 0, limited actions) | Restrained |
| **Sickened** | Various disease/poison conditions | Sickened 1–4+ |
| **Slowed** | Loses Half Action | Slowed 1 |
| **Strained** | Fatigued / Exhausted (loaded System Strain) | Drained / Fatigued |
| **Stunned** | Stunned (lose actions, halved M) | Stunned 1 / Slowed 1 |
| **Suffocating** | Suffocating (T tests, CON-based) | Suffocating (rounds = CON mod) |
| **Swallowed** | Swallowed (immobilized + suffocating + damage) | Swallowed Whole |

---

## Master Cross-System Conversion Table

Reference for designing WWN critical hit tables. Maps every WWN mechanical concept to its nearest WFRPG and PF2 equivalent. See also [criticals-overview.md](mdc:criticals-overview.md).

### Hit Roll Modifiers

| WWN Mechanic | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **–1 to hit** | –10% WS/BS | –1 to attack roll |
| **–2 to hit** | –20% WS/BS | –2 to attack roll |
| **–4 to hit** | –40% WS/BS | –4 to attack roll |
| **–6 to hit** | –60% WS/BS | –6 to attack roll |
| **+2 to hit** | +20% WS/BS | +2 circumstance bonus to attack |
| **+4 to hit** | +40% WS/BS | +4 circumstance bonus to attack |
| **+6 to hit** | +60% WS/BS | +6 circumstance bonus to attack |
| **Cannot attack with two-handed ranged** | Cannot attack with bows/crossbows in melee | Cannot use two-handed ranged in melee |

### Damage Modifiers

| WWN Mechanic | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **+1 to damage** | +1 damage (roughly +5–10%) | +1 to damage roll |
| **+2 to damage** | +2 damage | +2 to damage roll |
| **+3 to damage** | +3 damage | +3 to damage roll |
| **Shock X/AC** (guaranteed minimum damage) | Automatic partial hit / no exact equivalent | Persistent damage (closest concept; guaranteed chip) |
| **Shock bypassed** (Swarm Attack) | No equivalent — all attacks can miss | Ignore resistances / always deal persistent |

### Armor Class (Defensive) Modifiers

| WWN Mechanic | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **+2 AC** | –20% to all incoming attack rolls | +2 circumstance bonus to AC |
| **–2 AC** | +20% to all incoming attack rolls | –2 to AC |
| **Immune to Shock** (Total Defense) | Immune to automatic/partial hits | Immune to persistent damage from attacks |

### Conditions & States

| WWN Mechanic | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Prone** | Knocked Down | Prone |
| **Helpless / Unconscious** (0 HP non-lethal) | Helpless / Stunned until recovered | Unconscious |
| **Unable to act** (spell disrupted, etc.) | Stunned (loses all actions) | Stunned 1+ |
| **Dying** (0 HP) | Dying (T test or death) | Dying 1+ |

### Movement

| WWN Mechanic | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Full movement (30 ft)** | M4 (Move 4 × 5 ft = ~20 ft) / M5 (~25 ft) | Speed 25–30 ft |
| **Movement halved** | M–2 or halved | –10 ft or Speed halved |
| **Movement ×2** (Charge) | Charge move (double M) | Stride twice |
| **Movement = 0** (immobilized) | M=0 / Rooted | Immobilized |

### Action Economy

| WWN Action Type | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Main Action** | Full Action | Single Action (×1) or Two-Action Activity |
| **Move Action** | Half Action (movement) | Single Action (Stride / Step) |
| **On Turn Action** | Free Action (own turn only) | Free Action |
| **Instant Action** | Free Action / Reaction (any time) | Reaction or Free Action |
| **Loses Main Action** | Loses Full Action / Stunned | Slowed 1 |
| **Loses Move Action** | Loses Half Action | Slowed 1 (action lost to movement) |
| **Delayed / Held Action** | Delay / Hold | Ready Action |

### Duration

| WWN Duration | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Until next turn** | Until next turn | Until start of next turn |
| **For the round** | For this turn/round | Until end of round |
| **1 round** | 1 turn | 1 round |
| **d6 rounds** | d10/2 turns | 1d4 rounds |
| **Rest of encounter** | Rest of battle | Until end of encounter |
| **10 minutes** (non-lethal recovery) | ~10 minutes | ~10 minutes |
| **Permanent** | Permanent (requires surgery/magic) | Permanent (requires magic/long rest) |

### Skill & Saving Throw Checks

| WWN Mechanic | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Opposed skill check** | Opposed test (e.g. WS vs WS) | Opposed check / contested roll |
| **Attribute/skill check** (e.g. Str/Stab) | Characteristic test (e.g. S or WS) | Skill check (e.g. Athletics) |
| **+1 bonus on opposed check** | +10% on opposed test | +1 circumstance on opposed check |
| **Wis/Notice** | Per/Awareness | Perception |
| **Dex/Sneak** | Ag/Stealth | Stealth |
| **Str/Stab** | S/WS | Athletics/attack |
| **Int/Heal or Dex/Heal** | Heal (Intelligence-based) | Medicine |

### Damage Type / Source Mapping

| WWN Concept | WFRPG Equivalent | PF2 Equivalent |
|---|---|---|
| **Normal weapon damage** | Hit (rolled damage) | Struck (rolled damage) |
| **Shock damage** | Auto-damage / grazing hit | Persistent damage / splash |
| **Non-lethal damage** | Non-lethal strike | Nonlethal trait |
| **Psychic / emotional damage** | Insanity Points / Fear | Mental damage / Fear condition |
| **Magical weapon bonus** | Magical weapon bonus | Potency rune bonus |

---

## 1. Hit Roll Modifiers (Standard Table)

| Circumstance | Modifier |
|---|---|
| Shooting at a **distant prone** foe | **–2** to hit |
| Shooting or meleeing an **adjacent prone** foe | **+2** to hit |
| **Melee attacking while prone** | **–4** to hit |
| Target is **at least half behind cover** | **–2** to hit |
| Target is **almost completely in cover** | **–4** to hit |
| **Thrown** attack while being meleed by a foe | **–4** to hit |
| **Bow** (two-handed) while being meleed | **N/A** — impossible |
| **One-handed ranged / thrown** weapon while being meleed | **–4** to hit |
| No **level-0 skill** in the weapon being used | **–2** to hit |

---

## 2. Dual-Wielding

**Requirement:** Stab-1 skill minimum.

| Effect | Value |
|---|---|
| Bonus to **damage rolls** | **+2** |
| Bonus to **Shock** | None (damage bonus does NOT apply to Shock) |
| Penalty to **hit rolls** | **–1** |

---

## 3. Charge

**Requirements:** Must move at least 10 ft in a straight line. Uses both Move **and** Main Action.

| Effect | Value |
|---|---|
| Bonus to **hit** (melee or thrown) | **+2** |
| Penalty to own **AC** (for rest of round) | **–2** |
| Extra movement allowed | Up to **×2 normal move** |

---

## 4. Snap Attack (Instant Action)

Sacrifices the combatant's Main Action for an immediate attack.

| Effect | Value |
|---|---|
| Penalty to **hit roll** | **–4** |

---

## 5. Swarm Attack (up to 4 attackers)

The final attacker in the swarm gets cumulative bonuses from each other surviving attacker, up to 3 extras.

| Effect | Per extra attacker | Maximum (3 extras) |
|---|---|---|
| Bonus to **hit** | **+2** | **+6** |
| Bonus to **damage** | **+1** | **+3** |
| Bonus to **Shock** | None | None |
| Damage cap | Cannot exceed the weapon's normal maximum | — |
| Shock bypass | Shock **always** harms target even if AC is too high, shield is used, or Focus grants immunity | — |

---

## 6. Total Defense (Instant Action)

Costs the combatant their Main Action for the round.

| Effect | Value |
|---|---|
| Bonus to **Armor Class** (until next turn) | **+2** |
| **Shock immunity** (for this round) | Full — including from Swarm Attacks |

---

## 7. Going Prone

| Who is affected | Effect |
|---|---|
| **Distant ranged attackers** targeting the prone combatant | **–2** to hit |
| **Adjacent melee enemies** targeting the prone combatant | **+2** to hit |
| The prone combatant making **melee attacks** | **–4** to hit |
| Prone movement speed | **Halved** (crab-walking) |

---

## 8. Shock Damage — What Modifies It

| Modifier | Adds to Shock? |
|---|---|
| Attacker's **relevant attribute modifier** | ✅ Yes |
| **Magical weapon bonus** | ✅ Yes |
| Damage bonuses **explicitly noted** as adding to Shock | ✅ Yes |
| All other damage bonuses (Focuses, etc.) | ❌ No |

**Rule:** A hit never does *less* damage than what the weapon's Shock rating would deal. If the rolled damage is lower, use the Shock value instead.

---

## 9. Shatter a Shield

Opposed **Str/Stab** skill check — defender gets a bonus.

| Effect | Value |
|---|---|
| Defender's bonus to the opposed check | **+1** |
| Weapon requirement | Axe, mace, Focus-improved unarmed, or other crushing/hewing weapon |
| Result on attacker win | Shield is broken (magical shields immune) |

---

## 10. Screen an Ally (Move Action)

The screener intercepts attacks on an ally within 10 ft.

| Effect | Value |
|---|---|
| Max attackers screened per round | Equal to screener's **combat skill level** (e.g. Stab-2 = 2 attackers) |
| Requirement | **Level-0 or better** combat skill |
| Multiple screeners | Attacker must beat all blockers — lowest-rolling successful screener is attacked |

---

## 11. Initiative

| Roll | Formula |
|---|---|
| Group initiative | **1d8 + highest Dex modifier** in the group |
| Tiebreaker | **PC party wins** all ties |
| NPC modifier | Usually **+0**, unless GM decides otherwise |

---

## 12. Surprise

Resolved by an opposed skill check: **Wis/Notice** (targets) vs **Dex/Sneak** (attackers).

| Result | Effect |
|---|---|
| Attackers win | **Full round of free action** before initiative is rolled |
| Defenders win | No surprise; combat proceeds normally |
| Narrative effect | May prompt a **Morale check** for undisciplined/non-military targets (GM discretion) |

---

## 13. Ranged Attacks in Melee

| Weapon type | Effect |
|---|---|
| **Two-handed ranged** (bow) | Cannot be used at all when an armed melee enemy is in melee range |
| **One-handed ranged / thrown** | Can be used at **–4 to hit** |

---

## 14. Non-Lethal Attacks

| Effect | Condition |
|---|---|
| Attacker can knock target **unconscious/helpless** instead of killing | When a non-lethal attack brings target to 0 HP |
| Target revives with **1 HP** after **10 minutes** | — |
| Psychic/emotional attacks | Bring target to helpless shock/confusion for **10 minutes** at 0 HP |

---

## 15. Casting a Spell — Disruption

| Circumstance | Effect |
|---|---|
| Caster suffered **HP damage this round** | Cannot cast |
| Caster **drew or sheathed an item** with spellcasting hand | Cannot cast |
| Caster **severely jostled** this round | Cannot cast |
| Caster takes **HP damage while mid-cast** | Spell **fizzles** — spell slot is wasted |

---

## 16. Summary: Modifiable Attributes & Values

The following numeric values can be altered by combat circumstances, abilities, and actions:

| Attribute / Value | Modified By |
|---|---|
| **Hit Roll (d20 + modifiers)** | Cover, prone, dual-wield, charge, snap attack, swarm attack, skill level, melee while using ranged |
| **Damage Roll** | Dual-wield (+2), swarm attack (+1 per ally, max +3), attribute modifier, magical bonus |
| **Shock Damage** | Attribute modifier, magical weapon bonus, explicit Shock bonuses |
| **Armor Class (AC)** | Total Defense (+2), Charge (–2 to own AC for the round) |
| **Shock Immunity** | Total Defense (full immunity for the round), Swarm Attack (bypasses Focus/shield immunity) |
| **Movement Speed** | Prone (halved), climbing/swimming/rough terrain (halved), Run action (full move rate) |
| **Actions Available** | Total Defense (costs Main Action), Charge (costs Move + Main), Snap Attack (costs Main), Hold An Action (converts rest of actions to Instant) |
| **Opposed Skill Checks** | Shatter a Shield (defender +1), Screen an Ally (attacker must beat screener's roll) |
| **Initiative Order** | Hold An Action (act as Instant later), Delay an Action (acts after a chosen participant) |
| **Spell Casting Ability** | HP damage, item draw/stow, jostling — all prevent casting; damage mid-cast wastes slot |

---

*Last updated: Mar 2026. Based on the WWN (Worlds Without Number) ruleset as presented at [kedom.owlbeardm.com](https://kedom.owlbeardm.com/guide/rules/wwn/combat.html).*
