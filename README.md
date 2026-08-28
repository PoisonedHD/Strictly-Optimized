# Overview
This is a performance modpack designed to take after Simply Optimized, sharing its philosophy of focusing on accessibility and avoiding invasive changes. That said, you may notice a few things that differ from vanilla.
- [Sodium](https://github.com/CaffeineMC/sodium) "fixes" a few "bugs" with how the game is rendered, this is somewhat mitigated by [Sodium Shadowy Path Blocks (SSPB)](https://github.com/Rynnavinx/sodium-shadowy-path-blocks).
- [Better Block Entities](https://github.com/EdeenMC/betterblockentities) allows block entities (duh) to be rendered from further than 64 blocks away. The only exceptions being sign text, since that's configurable, and banners, as their optimizations are disabled.
- Sodium adds new video settings and completely overhauls the menu for them.
- The F3 menu will feature some mods like Sodium (again) and [ImmediatelyFast](https://github.com/RaphiMC/ImmediatelyFast).
- To quote [ishland](https://github.com/ishland), "Biome borders may get shifted by one or two blocks in very rare cases due to the vanilla implementation being order-dependent."

## Why not x mod?
Chances are, a specific mod might not be worth including due to any issues that may stem from doing so, such as parity or compatibility. Every mod in this modpack and the ones listed here have been benchmarked by me on a relatively high-end computer (Ryzen 7 9800x3D, 5070 Ti), and some on a crappy laptop (Intel i5-4200U, 720M).
- [Nvidium](https://github.com/MCRcortex/nvidium) - Slightly changes how the game looks and I get 4.6% less frames than with just Sodium.
- [Particle Core](https://github.com/fzzyhmstrs/pc) - Objectively slower than [AsyncParticles](https://github.com/Harveykang/AsyncParticles) and I don't see any benefit from using both.
- [Gnetum](https://github.com/decce6/Gnetum) - Actively reduces my frames by 7.3% and causes issues with a few mods.
- [Async Logger](https://github.com/decce6/AsyncLogger) - I have yet to see any real benefit from adding it.
- [Optimized Block Entities](https://github.com/maDU59/OptimisedBlockEntities) - Consistently runs ever so slightly slower than BBE for me and is a bit more visually intrusive despite what the description claims.

### Good mods that don't fit
- [C2ME OpenCL Acceleration Module](https://github.com/RelativityMC/C2ME-fabric) - Massively boosts world generation under the right circumstances, the caveat being it's incompatible with many mods and is currently experimental. 
- [Dynamic FPS](https://github.com/juliand665/Dynamic-FPS) - A good mod which reduces resource usage when the game isn't focused, very useful for laptops on battery or weaker devices. Doesn't fit the scope of the modpack.

## Other platforms

<p align="center">
  <a href="https://www.curseforge.com/minecraft/modpacks/strictly-optimized"><img src="https://cdn.modrinth.com/data/cached_images/3259d06439daa95d4bfad5b738daf545c60da5cf.png" alt="CurseForge"/></a> <a href="https://modrinth.com/modpack/strictly-optimized"><img src="https://cdn.modrinth.com/data/cached_images/3cda7a49e1f99e73d342a553cce85b85bbda939d.png" alt="Modrinth"/></a>
</p>
