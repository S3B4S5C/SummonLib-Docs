# SummonLib

SummonLib is an asset-driven minion/summon library for Hytale server mods.  
It lets you define summons in JSON assets and then invoke or remove them through interactions and items—without hardcoding per-summon logic.

## What it does

- **Asset-driven summons**: define summon behavior and parameters via `SummonConfig` assets.
- **Two summon types** (current):
  - **MODEL**: a non-NPC model that follows the player using formation logic (no real navigation; ignores blocks).
  - **NPC_ROLE**: an NPC-based summon (currently focused on flying allies) that moves with actual navigation and collides with blocks.
- **Simple casting/removal**: wire summon actions through Interactions and RootInteractions for items to use.

## Links

- CurseForge **[Under Review]**.
- [Wiki / Documentation](https://github.com/S3B4S5C/SummonLib-Docs/wiki).
- Issues / Bug Reports / Suggestions: join the lib's [Discord Server](https://discord.gg/VRH5eh7y).

## Status

This project is actively developed and may change as new features (formations, additional summon behaviors, expanded tuning, etc.) are added.

## License

See `LICENSE`.
