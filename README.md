# Loottable
Minecraft loot table with every item.
There are two tables: fullrandom.json, with a random count from 1 through 64, and random.json, only dropping one item.
## How to use
In a datapack, put this into <code>datapack/data/your_namespace/loot_tables/</code>, and access using <code>loot <give|insert|relpace|spawn> <Vector3 pos | Entity player> loot your_namespace:random.json</code>