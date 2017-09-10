# LootTables
Loot tables for each world

由於自訂的戰利品表，是分數各世界，彼此並不流通。本專案以各個世界資料夾為主，伺服器管理者再使用 soft link 的方式，將資料夾綁到世界資料夾。例如：

```
$ cd ~/SpigotServer/AlphaWorld/data
$ ln -s ~/LootTables/AlphaWorld loot_tables
```
