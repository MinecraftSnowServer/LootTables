# LootTables
Loot tables for each world

由於自訂的戰利品表，是分數各世界，彼此並不流通。本專案以各個世界資料夾為主，伺服器管理者再使用 soft link 的方式，將資料夾綁到世界資料夾。例如：

```
$ cd ~/SpigotServer/AlphaWorld/data
$ ln -s ~/LootTables/AlphaWorld loot_tables
```

## Minecraft Native Loot Tables

```
minecraft:empty

minecraft:chests/abandoned_mineshaft
minecraft:chests/desert_pyramid
minecraft:chests/end_city_treasure
minecraft:chests/igloo_chest
minecraft:chests/jungle_temple
minecraft:chests/jungle_temple_dispenser
minecraft:chests/nether_bridge
minecraft:chests/simple_dungeon
minecraft:chests/spawn_bonus_chest
minecraft:chests/stronghold_corridor
minecraft:chests/stronghold_crossing
minecraft:chests/stronghold_library
minecraft:chests/village_blacksmith
minecraft:chests/woodland_mansion

minecraft:entities/bat
minecraft:entities/blaze
minecraft:entities/cave_spider
minecraft:entities/chicken
minecraft:entities/cow
minecraft:entities/creeper
minecraft:entities/donkey
minecraft:entities/elder_guardian
minecraft:entities/ender_dragon
minecraft:entities/enderman
minecraft:entities/endermite
minecraft:entities/evocation_illager
minecraft:entities/ghast
minecraft:entities/giant
minecraft:entities/guardian
minecraft:entities/horse
minecraft:entities/husk
minecraft:entities/iron_golem
minecraft:entities/llama
minecraft:entities/magma_cube
minecraft:entities/mule
minecraft:entities/mushroom_cow
minecraft:entities/ocelot
minecraft:entities/parrot
minecraft:entities/pig
minecraft:entities/polar_bear
minecraft:entities/rabbit
minecraft:entities/sheep
minecraft:entities/shulker
minecraft:entities/silverfish
minecraft:entities/skeleton
minecraft:entities/skeleton_horse
minecraft:entities/slime
minecraft:entities/snowman
minecraft:entities/spider
minecraft:entities/squid
minecraft:entities/stray
minecraft:entities/vex
minecraft:entities/villager
minecraft:entities/vindication_illager
minecraft:entities/witch
minecraft:entities/wither_skeleton
minecraft:entities/wolf
minecraft:entities/zombie
minecraft:entities/zombie_horse
minecraft:entities/zombie_pigman
minecraft:entities/zombie_villager

minecraft:entities/sheep/black
minecraft:entities/sheep/blue
minecraft:entities/sheep/brown
minecraft:entities/sheep/cyan
minecraft:entities/sheep/gray
minecraft:entities/sheep/green
minecraft:entities/sheep/light_blue
minecraft:entities/sheep/lime
minecraft:entities/sheep/magenta
minecraft:entities/sheep/orange
minecraft:entities/sheep/pink
minecraft:entities/sheep/purple
minecraft:entities/sheep/red
minecraft:entities/sheep/silver
minecraft:entities/sheep/white
minecraft:entities/sheep/yellow

minecraft:gameplay/fishing
minecraft:gameplay/fishing/fish
minecraft:gameplay/fishing/junk
minecraft:gameplay/fishing/treasure
```
