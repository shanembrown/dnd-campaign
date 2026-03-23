# Claude Context

This is a **D&D Campaign Wiki** built with Docsify and hosted on GitHub Pages.

## Purpose

A knowledge base for tracking an active D&D campaign, including:
- Player characters
- NPCs
- Locations
- Factions
- Items
- Session notes

## Tech Stack

- **Docsify** - lightweight documentation site generator
- **GitHub Pages** - hosting
- **Markdown** - all content files

## Link Format

**Important**: All internal links must use absolute paths from the doc root:
- `locations/the-groveborne.md` (correct)
- `npcs/calef.md` (correct)
- `../npcs/calef.md` (wrong - causes 404s)
- `/locations/the-groveborne.md` (wrong - leading slash breaks links)

## Directory Structure

```
pcs/           # Player characters
npcs/          # Non-player characters
locations/     # Places in the world
factions/      # Groups and organizations
items/         # Notable items
```

## Current Campaign State

- **Party Level**: 3
- **Party**: Raker (Druid), Danior (Cleric), Das (Fighter), Hazik (Wizard)
- **Main Antagonist**: Eldrix Mortivar (fallen Penance Crusader, dark necromancer)
- **Current Location**: The Groveborne — resting, awaiting Finn and Creel
- **Current Goal**: Investigate telepathy rings with Finn and Creel; potentially mend rift between Groveborne and Penance Crusaders; learn Abyssal
- **Companion**: Ranger Greenward (traveling with party)

## Recent Events (current session)
- Interrogated Xellath — referenced "the one who oversees all" (likely Eldrix Mortivar), killed himself via incantation when asked where he came from
- Found Abyssal inscription on Xellath — Istren Vale destroyed it (zealotry, not malice)
- Discovered telepathy rings — cultist communication network. Hazik wore one: heard cacophony of voices in unknown language, entered trance state. Can isolate individual voices but can't understand the language.
- Ring knocked Greenward unconscious — divinity stone (touched to chest) revived him and others
- Found altar behind summoning ritual — central skull (sigils placed in eye sockets, table glowed green), 4 colored skulls (blue, green, red, black). Needs 8 rings total; party has 2.
- Hazik arcana check: altar is very dark magic. Party chose to return later with all 8 rings.
- Fought additional cultist + 2 skeletons on the way out of the temple
- Returned to Southreach — Istren Vale seemed "off," insisted party travel with him to Crusader Keep
- Long rested at Southreach, then headed to The Groveborne (Greenward guided safely, no encounters)
- Re-encountered Clak and Saz in The Rootpath — payback for the frog incident: smacked Raker, turned Das into a frog via Elfpanada. Hazik retaliated with Misty Step + force-fed Saz an Elfpanada causing uncontrollable laughter.
- Purchased treats from the Shadow Baker: 3 empanadas (1 = hunger for 1 hr, 1 = sickness for 1 hr, 1 = instant death; unknown which is which)
- Traded plants with Sage Nightbloom (botanist) for potions
- Consulted Keeper Caelwyn Oakseeker: Crusaders once friends but now too zealous; they understand Abyssal best; party could mediate as outsiders
- Crusader Keep is the only Penance Crusaders stronghold in Wilden; their capital is on Forden
- Keeper summoned Finn and Creel (Groveborne Rangers) to investigate the rings — arriving in a few days
- Session ended with party resting at The Groveborne

## Previous Events

- Explored the Wilden Reach Temple — symmetrical layout, two secret passages (passphrase: "Klaatu barada nikto")
- Major battle: fought Xellath, Zaelar, cultists, skeletons, and Wights. Zaelar killed; Xellath captured.

- Party leveled to 3; Raker chose Circle of the Land (Land's Aid variant)
- Traveled south through Skyreach Mountains (fought spiders), arrived at Southreach
- Met Lightkeeper Istren Vale (Order of the Sentinel Guards) — military arm of Penance Crusaders, has divine connection to a god of light
- Found Ranger Greenward's hidden folio — observation notes on Wailing Tundra disturbances; "Strange disturbances. Need to talk with the Keeper."
- Istren confirmed via prayer that Greenward is on a quest for good; lent party his boat
- World revealed to be an archipelago called **Illium** — major islands: Wilden, Forden, Wailing Tundra (island), Wilden Isle, Wilden Reach
- Sailed to Wilden Reach, found Greenward frightened and asking for help urgently
- Discovered unexpected cultist outpost on jungle island — defeated cultists and 3 Steam Mephits
- Party traveled from Hightower back to The Groveborne, then headed south
- Met Calef (ex-Ranger) in The Rootpath — left Rangers voluntarily, won't guide party but shared route info (swamp is harder than mountains, path through mountains on the far side)
- Met The Shadow Baker in The Rootpath — sells magical baked goods; donut turns eater into a frog (Saz), orange gillette held by Hazik (effect unknown)
- Defeated Morwen the Hag in the Stagnant Swamp — confirmed Circle of the Occult member
- Morwen's ritual used liquid to raise the dead as undead; same demonic magic as Featherthorne Hollow
- Found Morwen's Recipe Book and colored liquids; known effects: 1/2 purple+green = grey ooze, 1/3 green+clear+red = acid, 1/3 purple+red+clear = no effect
- Second Sigil of the Occult found at Morwen's hut

## Workflow

When the user describes campaign events:
1. Update relevant location/NPC/faction files
2. Update README.md if current location or goal changes
3. Add new entries to _sidebar.md for new content
4. Commit and push when requested
