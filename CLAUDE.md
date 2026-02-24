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
- `locations/the-groveborn.md` (correct)
- `npcs/calef.md` (correct)
- `../npcs/calef.md` (wrong - causes 404s)
- `/locations/the-groveborn.md` (wrong - leading slash breaks links)

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
- **Current Location**: Wilden Reach — inside a cultist outpost on one of the jungle islands, just defeated Steam Mephits, taking a break (not a rest)
- **Current Goal**: Travel south through the Stagnant Swamp toward Southern Wilden

## Recent Events (current session)
- Party leveled to 3; Raker chose Circle of the Land (Land's Aid variant)
- Traveled south through Skyreach Mountains (fought spiders), arrived at Southreach
- Met Lightkeeper Istren Vale (Order of the Sentinel Guards) — military arm of Penance Crusaders, has divine connection to a god of light
- Found Ranger Greenward's hidden folio — observation notes on Wailing Tundra disturbances; "Strange disturbances. Need to talk with the Keeper."
- Istren confirmed via prayer that Greenward is on a quest for good; lent party his boat
- World revealed to be an archipelago called **Illium** — major islands: Wilden, Forden, Wailing Tundra (island), Wilden Isle, Wilden Reach
- Sailed to Wilden Reach, found Greenward frightened and asking for help urgently
- Discovered unexpected cultist outpost on jungle island — defeated cultists and 3 Steam Mephits
- Currently inside the outpost, taking a break (no rest taken)

## Previous Events

- Party traveled from Hightower back to The Groveborn, then headed south
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
