# SpiderSpawners

Adding Clones of Greydwarf nests to spawn MonsterLabZ spiders from them.

## Features

Tiny mod that uses

* [SpawnerCloner](https://valheim.thunderstore.io/package/FixItFelix/SpawnerCloner/)
* [MonsterLabZ](https://valheim.thunderstore.io/package/MonsterLabZ/MonsterLabZ/)
* [SpawnThat](https://valheim.thunderstore.io/package/ASharpPen/Spawn_That/)

And adds a set of complete and ready to use spawn configs for the spiders creatures of MonsterLabZ

This mod is using SpawnThat's world spawner ID range (make sure this doesn't conflict with other mods):
* WorldSpawner.4991 - WorldSpawner.4999

The setting defaults will create spider nests in those biomes:
* Black Forest
* Swamp
* Mountains
* Plains

### Additional handy information

For being able to better configure the creatures toughness (you will need to use any other mod to do so), I added a
file ```org.bepinex.plugins.creature.lister.defaults.yaml``` to the config folder of this mod. The file itself does not
do anything besides listing the default values of all spider creatures of MonsterLabZ. This information I created with
one of my other mods: [CreatureLister](https://valheim.thunderstore.io/package/FixItFelix/CreatureLister/)

### What this mod does NOT do

* adding creature difficulty (health/damage) configurations -> use for
  example [CreatureLevelAndLootControl](https://valheim.thunderstore.io/package/Smoothbrain/CreatureLevelAndLootControl/)
* adding proper drop configurations for these creatures, use for
  example [DropThat](https://valheim.thunderstore.io/package/ASharpPen/Drop_That/)

## Changelog

* 0.1.0 -> initial version

## Contact

* https://github.com/FelixReuthlinger/SpiderSpawners
* Discord: Flux#0062 (you can find me around some of the Valheim modding discords, too)