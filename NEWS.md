
# GiottoData 0.2.12.0 (2024/05/22)

## Bug fixes
- fix onload image subobject reconnection when generated from dev directory as opposed to lib directory

## Breaking changes
- `gDataDir()` has been made an internal

## Enhancements
- Additional params can now be passed to `GiottoClass::loadGiotto()` from `loadGiottoMini()` through `...`
- `init_gobject` param for `loadGiottoMini()`

## New
- `generate_mini_subobjects()` for rebuilding the mini subobjects


# GiottoData 0.2.11.0 (2024/05/21)

## Changes
- Mini CosMx rebuilt for GiottoClass 0.3.1
- Mini Visium rebuilt for GiottoClass 0.3.1. Added both the "alignment" and "image" (H&E) images. "image" was also spatially re-aligned
- Mini starmap rebuilt for GiottoClass 0.3.1
