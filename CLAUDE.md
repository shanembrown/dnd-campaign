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
- `npcs/klif.md` (correct)
- `../npcs/klif.md` (wrong - causes 404s)
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

- **Party Level**: 2
- **Party**: Raker (Druid), Danior (Cleric), Das (Fighter), Hazik (Wizard)
- **Main Antagonist**: Eldrix Mortivar (fallen Penance Crusader, dark necromancer)

## Workflow

When the user describes campaign events:
1. Update relevant location/NPC/faction files
2. Update README.md if current location or goal changes
3. Add new entries to _sidebar.md for new content
4. Commit and push when requested
