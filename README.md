# mcdocs

Modded Minecraft [mcdoc](https://github.com/SpyglassMC/vanilla-mcdoc) datapack schemas maintained for [Packraven](https://github.com/muon-rw/packraven).

## Schemas

- `mcdoc/apotheosis.mcdoc`: Apotheosis and Placebo (Minecraft 1.21.1+ and 26.1), converted from Shadows-of-Fire's schema documentation and verified against their Java codecs.
- `mcdoc/structure_weight_limit.mcdoc`: Repurposed Structures and YUNG's API, which raise the template pool weight limit from 150 to 5000 (Minecraft 1.20+, every loader).

## Planned Schemas
- Overgrown's Origins/Apoli
- Lithostitched

## Manifest format

Packraven fetches `manifest.json` at runtime and caches it locally alongside upstream `vanilla-mcdoc` and `misode.github.io` partner schemas. Each entry in `schemas` declares its `.mcdoc` path, module namespace, matching mod IDs, optional Minecraft version bounds (`minMinecraft`, `maxMinecraft`), and datapack folder-to-category mappings (`paths`).

## License

MPL-2.0. See [LICENSE](LICENSE).
