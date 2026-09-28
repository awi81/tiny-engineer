# Mods

Optional add-ons for Tiny Engineer. Stock robot parts live in [`3d_models/`](../3d_models/).

A mod can hold models and anything else (notes, images, firmware snippets). Printable geometry and Fusion source stay under that mod’s `3d_models/` folder.

## Layout

```text
mods/<mod_name>/
  README.md              # optional: what it is, non-model notes
  3d_models/
    cad/                 # Fusion source, when the mod has one
    parts/{servo_id}/    # exports; same idea as 3d_models/parts/
  ...                    # anything that is not a model
```

`parts/{servo_id}/` mirrors stock: `3mf/`, `stl/`, and `step/`. Example: [`halloween/`](halloween/).

## Workflow

Design, timeline, `PRINT_LAYOUT`, export, and checklist: [docs/3d/adding-parts.md](../docs/3d/adding-parts.md).

## Commits

`type(mods): summary`. Name the mod in the summary (`feat(mods): add desk clamp`). One scope for every mod. `feat(mods)` / `fix(mods)` do not version the stock CAD revision. Moving a mod into stock [`3d_models/cad/`](../3d_models/cad/) and [`3d_models/parts/`](../3d_models/parts/) is `feat(cad)`. Full rules: [CONTRIBUTING.md](../CONTRIBUTING.md).

## License

CAD and manufacturing exports under `mods/<mod_name>/3d_models/{cad,parts}/` are [CERN-OHL-S-2.0](../3d_models/LICENSE). See [NOTICE](../3d_models/NOTICE) for warranty and product-notice requirements.

When you distribute a Product based on a mod, cite that licence and use the mod’s own `3d_models` tree as the Source Location (for example `https://github.com/jamro/tiny-engineer/tree/main/mods/halloween/3d_models`).

This README and other files beside `3d_models/` are documentation under the [MIT License](../LICENSE).
