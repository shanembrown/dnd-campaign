# Raker

## Class
Druid (Circle of the Land — Land's Aid variant, Primal Order: Warden)

## Race
Halfling

## Level
5

## Background
Criminal — orphaned young, Raker turned to a life of petty crime out of necessity rather than malice. Despite looking like a child (halfling), he's actually fairly old. As he aged he left that life behind, seeking simplicity and eventually finding his path as a Druid. He finds solace in nature and is driven by doing right by the world.

### Open Backstory Threads
- **Languages**: Knows Goblin (possibly from criminal underworld contacts?) and Elvish (connection to whoever introduced him to druidism?)
- **The transition**: What pulled Raker from crime to druidism? A mentor? A moment in nature? The Warden primal order suggests a deep protector instinct
- **Origins**: Where is Raker from? Being from outside the Wilden could explain his role as a neutral outsider in the faction politics
- **The child appearance**: Has he used looking like a kid to his advantage? Old soul in a young-looking body is a fun dynamic
- **Motivation**: No faction loyalty — Raker isn't aligned with the Groveborne, Crusaders, or anyone. He just wants to protect the natural world and do what's right

## Alignment
Neutral Good

## Stats
- STR 12, DEX 16, CON 14, INT 8, WIS 17, CHA 10
- AC 16, HP 39, Speed 30
- Proficiency +3 · Spell save DC 14 · Spell attack +6 · Initiative +6
- Spell slots: 4 / 3 / 2 · Prepared spells: 9
- Key skills: Stealth +6, Perception +6

## Notes
- Tank/battlefield control role in the party
- Uses Shillelagh for melee combat (keys off WIS)
- Halfling traits: Naturally Stealthy, Luck, Brave
- Languages: Common, Elvish, Goblin, Druidic
- Cantrips: Guidance, Shillelagh, Produce Flame (+ Shocking Grasp free from Temperate land)
- Wild Shape: knows 6 beast forms, up to CR 1/2 (next bump at level 8)

## Level 4 Advancement (completed)

Finalized in Foundry. The game runs on SRD 5.1/5.2 content only (no PHB/Xanathar's feats or cantrips loaded), which shaped the picks.

- **HP**: max now **32**
- **ASI**: **+2 WIS (15 → 17)** — War Caster wasn't available (not in SRD), so took the clean stat bump. Spell DC → 13, spell attack → +5, +1 prepared spell (7 total)
- **New cantrip**: **Produce Flame** (Thorn Whip not in SRD 5.2; Produce Flame is the reliable ranged fallback — 1d8 fire, doubles as a torch)
- **Wild Shape**: knows 6 beast forms, max CR 1/2

## Level 5 Advancement (completed)

Stepped through in Foundry. Automatic, no choices: proficiency **+2 → +3**, spell save DC **14**, spell attack **+6**, **3rd-level slots unlocked (4/3/2)**, prepared spells **7 → 9**, **Produce Flame → 2d8**, and the new feature **Wild Resurgence**.

- **HP**: took the average (+5, +2 CON) → **32 → 39**. Hit dice 5/5. *(The wiki previously listed 37 in error; Foundry had 32 at level 4.)*
- **New 3rd-level spells**: **Call Lightning** and **Dispel Magic**
- **Removed**: **Goodberry** (Wild Resurgence + Land's Aid cover the same ground better)
- **Circle of the Land finally configured** (Temperate) — four free spells that had never been granted. See below.
- No subclass feature at 5 (Natural Recovery arrives at level 6)

### Current prepared list

**Prepared: 8/9 — one slot still open.** Recommended pick: **Plant Growth** (non-concentration, quarters movement in a 100-ft radius, stacks with Call Lightning instead of competing with it for concentration).

| Level | Counts against the 9 | Free (outside the 9) |
|---|---|---|
| Cantrips | Shillelagh, Guidance, Produce Flame *(2d8, +6)* | **Shocking Grasp** *(circle)* |
| 1st | Thunderwave, Healing Word, Faerie Fire, Entangle | **Speak with Animals** *(ritual)*, **Sleep** *(circle)* |
| 2nd | Spike Growth, Pass without Trace | **Misty Step** *(circle)* |
| 3rd | **Call Lightning**, **Dispel Magic** | **Lightning Bolt** *(circle)* |

Key numbers: Call Lightning **120 ft, 60-ft cylinder, DEX DC 14, 3d10** · Lightning Bolt **100-ft line, DEX DC 14, 8d6** · Land's Aid **10-ft sphere, CON DC 14, 2d6 necrotic + 2d6 healing to one chosen creature** (scales 3d6 at lvl 10, 4d6 at 14).

**Speak with Animals** sits outside the 9 — it's set to **Ritual** preparation mode in Foundry, so it's free but can only be cast as a 10-minute ritual, never in combat. It has repeatedly been plot-critical (Wicks Hollow, the grey cat), so it stays.

### Why Call Lightning and Dispel Magic

- **Call Lightning** — two things the Foundry row doesn't show: it becomes **4d10 outdoors in a storm**, and it can be **re-fired as an action every round for 10 minutes on the same slot**. Far and away the best damage-per-slot option at this tier. Concentration, so it competes with Entangle / Spike Growth.
- **Dispel Magic** — no concentration. The party is entering Crusivar carrying Eldrix's unopened warded "M" scroll, both rites, the Hollowing Ledger and the Deck of Many Things. This is the utility slot that saves a session.

## Circle of the Land — now set up (Temperate)

**This had been giving Raker nothing since level 3** — the land type was never configured, so none of the bonus spells were ever granted. Fixed during the level-5 pass.

How it works: after **every long rest** you declare one land type — arid, polar, temperate, or tropical — and you get **everything in that land's column for your druid level and lower**, always prepared, **in addition to** your 9. You pick the *column*, not individual spells, and you can't mix columns. You still cast them with normal slots; the free part is the preparation.

| Land | Lvl 3 | Lvl 5 | Lvl 7 | Lvl 9 |
|---|---|---|---|---|
| **Arid** | Blur, Burning Hands, Fire Bolt | **Fireball** | Blight | Wall of Stone |
| **Polar** | Fog Cloud, Hold Person, Ray of Frost | **Sleet Storm** | Ice Storm | Cone of Cold |
| **Temperate** | Misty Step, Shocking Grasp, Sleep | **Lightning Bolt** | Freedom of Movement | Tree Stride |
| **Tropical** | Acid Splash, Ray of Sickness, Web | **Stinking Cloud** | Polymorph | Insect Plague |

**Currently set to Temperate.** Misty Step is the best thing on the table for a party being actively hunted; Lightning Bolt covers road ambushes.

- **Arid** on a day with an expected stand-up fight in the open — a free Fireball costs zero prepared slots. Bad pick while travelling with the wonder show's non-combatants.
- **Polar** for city infiltration — Fog Cloud + Hold Person is a strong sneaking kit.

### ⚙️ How to change land type in Foundry (manual — it is NOT automated)

The feature's own text says: *"This feature does not automate swapping between prepared spell options."* There is no land selector anywhere. You do it by hand:

1. Delete the old land's spells from the sheet.
2. Drag the new land's spells in from the SRD compendium (or use **+** on the spells tab).
3. For each one: open it → **Details** tab → set **Preparation Mode** to **"Always Prepared"**.

Step 3 is the whole trick — "Always Prepared" spells **don't count against the 9**. If the PREPARED counter jumps when you add them, one is still set to plain "Prepared."

Leave Temperate set up as the default and only re-point it when the DM signals what tomorrow looks like.

## Wild Resurgence (new at 5)

Once per turn, either:
- spend an unspent **Wild Shape use → gain a 1st-level spell slot**, or
- spend a **1st-level slot → regain a Wild Shape use** (this direction once per long rest)

Practically: Wild Shape uses that would have gone unspent become extra Healing Words, and since **Land's Aid** runs on Wild Shape uses, a 1st-level slot can buy another Land's Aid.

## Roleplay note

Raker's stage act as **The Lamplighter** runs on **Produce Flame** — which just doubled to **2d8**. Worth telling the DM the show got more impressive.

## Pending Mechanics Reminders
- **Concentration**: Entangle, Faerie Fire, Spike Growth, **Call Lightning** and Blur/Web (if you swap land) all require concentration — only one at a time. If hit, Con save DC = max(10, half damage taken) to keep the spell up.
- **Spell save DC** = **14** (8 + prof 3 + WIS 3).
- **Spell attack mod** = **+6**.
- **Prepared spells**: **9** per long rest from the full druid list — **plus** the four Circle of the Land spells (Always Prepared, outside the count) and Speak with Animals (ritual mode, outside the count).
- **Halfling Luck**: reroll natural 1s on any d20 test. Easy to forget.
