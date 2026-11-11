# Jan's Fabric 26.3 changelog

## 2026.11.11-2 (build 10, 2026-11-11)

ReTerraForged mixin fix for Fabric API 0.166.2 (BiomeModificationImpl.getSortedModifiers now takes RegistryAccess).

## 2026.11.11-1 (build 9, 2026-11-11)

Sync with Jan's live profile: Fabric API 0.166.2, Collective 8.86, MezzConfig 0.7.1, Mielon's The Sift 2.0.3, Carry On 2.12.2, Mendable Anvils 1.2.5, Metal Bundles 26.3.4, Villager Names 9.0; add Roguelike Dungeons 2.1.2; jansfixes 1.1.0 (DH dimension gate).

## 2026.11.09-1 (build 8, 2026-11-09)

Repair existing worlds rejected by duplicate Sift clock markers in older ReTerraForged preset exports. Filter only the recognized obsolete copied timeline in memory while preserving the installed Sift tide cycle and saved terrain configuration. Fix the actual preset GUI exporter to emit its registry patches instead of copying unrelated mods’ merged registry snapshots. Existing save archives and player settings are not rewritten. Native old-world registry and GUI-export checks pass on Linux and Windows; the new export also reloads on Linux. These are not exhaustive gameplay tests.

## 2026.11.08-2 (build 7, 2026-11-08)

Fix the crash when creating the first map texture; preserve biome-tinted map colours and subsequent map refreshes. Optimize BetterGrassify snow-neighbour checks without reducing configured layers or changing the selected visual result. Native map tests pass on Linux and Windows; original-versus-optimized snow checks pass 1,104 Linux and 816 Windows comparisons. Controlled snow-neighbour tests show lower temporary allocation; overall live FPS impact is still being measured. Previous cage and road-sign fixes are retained. Existing player settings are preserved.

## 2026.11.08-1 (build 6, 2026-11-08)

Synchronize the tested pack inventory, including updated dependencies and prepared mod repairs. Fix immediate Terraria crafting refresh; cloud/Distant Horizons occlusion; Cobblemon particle mapping, mint names, safe player-data handling and Self-Destruct/Explosion animations; ash willow offline growth and Moonlight shutdown; Supplementaries road-sign saving; Alex’s Caves rainbow shader corruption. Repair Anthology animation tracking for unassigned-ID cage preview entities. Targeted Linux/Windows native regressions and shader captures are recorded; these are not exhaustive tests of every mod or shader pack. Existing player configurations are preserved.

## 2026.11.07-2 (build 5, 2026-11-07)

Add Pet Cemetery and Weather Glass with Simple Clouds local-storm compatibility; update Create Fly with renderer and recipe lifecycle repairs. Native pet gameplay/save/rejoin passed on Linux; Weather Glass/Create checks passed on Linux and Windows. Existing player configurations are preserved.

## 2026.11.07-1 (build 4, 2026-11-07)

Repair vanilla and chitin shield blocking; add tiered hoe plant harvesting and Druidcraft guides; speed up crate search; fix Terraria ingredient Shift-click and hide modifier placeholders; hide undiscovered Pokemon names in Jade; clarify Pokemon drop rolls; add carried dynamic lights and repair rain/storm fog depth without shaders. Native Linux and Windows regressions passed. Existing player configurations are preserved.

## 2026.11.06-1 (build 3, 2026-11-06)

Fix cloud damage-camera projection; repair Antarchy worldgen bounds and Ultimate Mace model; restore actual Alex cave cavities and direct-generation preparation; move Atlas accessory slot and ship previously tested anvil/enchanting/Atlas fixes. Native Linux and Windows checks passed; cave generation tests concern new chunks.

## 2026.11.04-2 (build 2, 2026-11-04)

Fix Twilight Forest aurora render-pass crash. Exclude Simple Clouds sky and weather from Twilight Forest, including legacy dimension configurations.

## 2026.11.04 (build 1, 2026-11-04)

Initial Fabric 26.3 pack for friends. Existing player configurations are preserved.
