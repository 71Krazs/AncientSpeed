# Faster Ancient Stations (3x)

A PalSchema mod for Palworld 1.0.3 that makes recipes exclusive to the **Ancient Workbench** and **Ancient Furnace** craft **3× faster**.

It changes only each selected recipe's `WorkAmount` to one third of its vanilla value. Recipes shared with another station are intentionally not touched.

## Included

- Every recipe listed by current game data as Ancient Workbench-only, including its schematic variants.
- Ancient Furnace-only recipes: **Soralite Ingot** and **Paloxite Ingot**.

## Requirements

- [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS)
- [PalSchema](https://www.nexusmods.com/palworld/mods/2361) 0.6.4 or later

## Install

Extract the `FasterAncientStations` folder into:

`<Palworld>/Pal/Binaries/Win64/ue4ss/Mods/PalSchema/mods/`

Restart Palworld after installing. If PalSchema auto reload is enabled, changing the recipe file can reload live.

## Compatibility

This patches `DT_ItemRecipeDataTable` recipe rows. It can conflict with any mod that changes the same recipes' `WorkAmount`.
