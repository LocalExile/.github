# LocalExile

**A local, from-scratch server for the Path of Exile 3.29.3b client**, written in C# (.NET 10) and built by people and
AI agents working together.
You play on your own machine, against servers running on 127.0.0.1, with no internet connection to anything official.
Think TrinityCore, AzerothCore or MaNGOS, for Path of Exile.

[**LocalExile/LocalExile**](https://github.com/LocalExile/LocalExile) · [Discord](https://discord.gg/pd2Fd5M6Hd)

## What it does

- **Login and characters:** the client's own login protocol, accounts, character creation and saves.
- **The world:** towns, zones and area transitions, instances, waypoints, a port of the level generator.
- **Gameplay:** monsters and loot, skills and combat, levels and experience, the passive tree, gems.
- **Everything around it:** items, NPCs, shops, the stash, hideouts, quests and cosmetics.

What works, what is partly working and what isn't done yet is tracked per area in
[Agents/Status.md](https://github.com/LocalExile/LocalExile/blob/main/Agents/Status.md).
Showcase videos are in the [project README](https://github.com/LocalExile/LocalExile#showcase-most-recent-to-older).

## Getting started

You need your own installed copy of the 3.29.3b client.
The repository contains **no game files, keys or game data**: everything the servers need is generated locally from
your client.

The easiest way in: open a frontier model (such as Claude) in a clone of the repository, and ask it to read the
`Agents/` folder and set the project up on your machine.
The full guide, for people and agents alike, is
[Agents/GettingStarted.md](https://github.com/LocalExile/LocalExile/blob/main/Agents/GettingStarted.md).

## Contributing

Pull requests are welcome, from people and from AI agents.
Start with [AGENTS.md](https://github.com/LocalExile/LocalExile/blob/main/AGENTS.md) for the rules, then pick an item
from the [Roadmap](https://github.com/LocalExile/LocalExile/blob/main/Agents/Roadmap.md).
The protocol reference and the reverse-engineering notes are in
[Agents/docs](https://github.com/LocalExile/LocalExile/blob/main/Agents/docs/README.md).

## Notice

LocalExile is a fan project for fun and education.
It is not an official Grinding Gear Games product, and it is not affiliated with or endorsed by Path of Exile or
Grinding Gear Games.
It is meant for local play and learning, and does not support or sponsor public servers.
