# Overview
This is a personal modpack designed to take after Simply Optimized, sharing its philosophy of focusing on accessibility and avoiding invasive changes. That said, there are a few things that differ from vanilla you may notice.
- [Sodium](https://modrinth.com/mod/sodium) "fixes" a few "bugs" with how the game is rendered, this is somewhat mitigated by [Sodium Shadowy Path Blocks (SSPB)](https://modrinth.com/mod/sodium-shadowy-path-blocks).
- [Better Block Entities](https://modrinth.com/mod/better-block-entities) allows block entities (duh) to be rendered from further than 64 blocks away. The only exceptions being sign text, since that's configurable, and banners, as their optimizations are disabled.
- The F3 menu will feature some mods like Sodium (again) and [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast).
- To quote [ishland](https://modrinth.com/user/ishland), "Biome borders may get shifted by one or two blocks in very rare cases due to the vanilla implementation being order-dependent."

## Why not x mod?
Chances are, a specific mod might not be worth including due to any issues that may stem from doing so, such as compatibility. Every mod in this modpack has been benchmarked by me on a relatively high-end computer (Ryzen 7 9800x3D, 5070 Ti), and some on a crappy laptop (Intel i5-4200u, 720M).
- [Nvidium](https://modrinth.com/mod/nvidium) - Slightly changes how the game looks and I get 4.6% less frames than with just Sodium installed.
- [Particle Core](https://modrinth.com/mod/particle-core) - Objectively slower than [AsyncParticles](https://modrinth.com/mod/asyncparticles) and I don't see any benefit from including both.
- [Gnetum](https://modrinth.com/mod/gnetum) - Actively reduces my frames by 7.3%.
- [Async Logger](https://modrinth.com/mod/asynclogger) - I have yet to see any real benefit from adding it.

I don't want to include any mods that can harm performance on newer devices, but if these mods help you specifically, good for you.

### Good mods that don't fit
- [C2ME OpenCL Acceleration Module](https://modrinth.com/mod/c2me-ocl) - Massively boosts world generation under the right circumstances, the caveat being it's incompatible with many mods and is currently experimental. 
- [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) - A good mod which reduces resource usage when the game isn't focused, very useful for laptops on battery or weaker devices. Doesn't fit the scope of the modpack.
