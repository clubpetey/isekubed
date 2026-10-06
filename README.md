# Isekubed — wiki, resource-pack base and translations

This repository holds the public files for [Isekubed](https://www.curseforge.com/projects/1716861), a magic and
utility mod for Minecraft (NeoForge 1.21.1). The mod's source code is not here.

| Folder | What it is |
|---|---|
| `wiki/` | Source of the Isekubed wiki on [moddedmc.wiki](https://moddedmc.wiki). Generated, so please don't edit it directly. |
| `resourcepack/` | The mod's textures, models, blockstates, particles and fonts, laid out as a resource pack. Copy it to make your own. |
| `translations/` | Every piece of text in the mod: `lang/`, `dialogue/` (boss captions) and `documents/` (in-game books). |
| `CREDITS.md` | Third-party works used by the mod, and their licences. |

> **Spoiler warning:** `resourcepack/` and `translations/` are the mod's raw files. They contain riddles, quest hints,
> story dialogue and the rune alphabet. If you're playing, read [the wiki](https://moddedmc.wiki) instead.

## Translating

1. Copy `translations/assets/isekubed/lang/en_us.json` to your locale, e.g. `de_de.json`.
2. Copy the `en_us` folders under `dialogue/` and `documents/` the same way, if you want to translate those too.
3. Translate the values and leave the keys alone.
4. Open a pull request. Translations are merged into the next release of the mod.

A partial translation is welcome. Anything you leave out falls back to English.

## Licence

Isekubed © ClubPetey, All Rights Reserved. These files may be used to make resource packs and translations for
Isekubed. Third-party works keep their own licences; see `CREDITS.md` and `resourcepack/assets/isekubed/font/`.
