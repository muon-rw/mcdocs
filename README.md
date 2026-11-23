# mcdocs

Modded Minecraft [mcdoc](https://github.com/SpyglassMC/vanilla-mcdoc) datapack schemas maintained for [Packraven](https://github.com/muon-rw/packraven).

## Schemas

- `mcdoc/apotheosis.mcdoc`: Apotheosis, Placebo (gear sets, wanderer trades, brewing mixes), Apothic Enchanting (enchanting stats, infusion recipes), and Apothic Spawners (spawner modifier recipes) for Minecraft 1.21.1+ and 26.1.
- `mcdoc/apotheosis_legacy.mcdoc`: 1.20.x Apotheosis and Zenith bosses, wanderer trades, and enchanting stats.
- `mcdoc/bettercombat.mcdoc`: Better Combat weapon attributes (1.20.1, 1.21.1, and 26.1+).
- `mcdoc/dynamic_difficulty.mcdoc`: Dynamic Difficulty dimension, entity, biome, and structure leveling settings plus the `entity_level` loot condition (1.21+).
- `mcdoc/irons_spellbooks.mcdoc`: Iron's Spells 'n Spellbooks spell config overrides, upgrade orb types, Alchemist Cauldron recipes, loot functions, and loot modifiers (1.20+).
- `mcdoc/irons_jewelry.mcdoc`: Iron's Gems 'n Jewelry materials, parts, patterns, and loot modifiers (1.20+).
- `mcdoc/legendary_survival_overhaul.mcdoc`: Legendary Survival Overhaul temperature, thirst, and body damage data definitions plus loot modifiers (1.20+).
- `mcdoc/global_loot_modifiers.mcdoc`: Forge, NeoForge, and Porting Lib global loot modifier indices, base modifiers, built-in `add_table` serializers, and loader loot conditions.
- `mcdoc/farmers_delight.mcdoc`: Farmer's Delight cooking, cutting, and special recipes, loot modifiers, and loot functions (1.20+).
- `mcdoc/tiered.mcdoc`: Tiered / TieredZ / Tierify item attributes and reforge item mappings (1.20+).
- `mcdoc/loot_integrations.mcdoc`: Loot Integrations chest loot table bindings (1.20+).
- `mcdoc/curios.mcdoc`, `mcdoc/accessories.mcdoc`, `mcdoc/trinkets.mcdoc`: Curios, Accessories, and Trinkets slot, entity, and group definitions (1.20+).
- `mcdoc/structure_weight_limit.mcdoc`: Repurposed Structures and YUNG's API, which raise the template pool weight limit from 150 to 5000 (Minecraft 1.20+, every loader).

## Planned Schemas

- Overgrown's Origins / Apoli
- Lithostitched
- Numismatic Overhaul (+ Reforged)

## Manifest format

Packraven fetches `manifest.json` at runtime and caches it locally alongside upstream `vanilla-mcdoc` and `misode.github.io` partner schemas. Each entry in `schemas` declares its `.mcdoc` path, module namespace, matching `modIds` and optional `loaders`, optional Minecraft version bounds (`minMinecraft`, `maxMinecraft`), and datapack folder-to-category mappings (`paths`).

## License

MPL-2.0. See [LICENSE](LICENSE).
