# Minecraft ComputerCraft Utilities

## 1. Stairs (mining turtle)
Builds 1-block width stairs.
Usage: `stairs X`, where X is depth.
Note: The turtle must be refueled. Turtle will fill blocks underneath from inventory if nothing is there. Filled-in blocks: "minecraft:dirt","minecraft:cobblestone". Update `get_solid_block_list()` function if need more.

## 2. Fractal Dig (mining turtle)
Digs area, filles the bottom layer with dirt, cobblestone or stone.
Usage: `fractal_dig X Y HEIGHT`
Note: The turtle must be refueled. Turtle will fill blocks underneath from inventory if nothing is there. Filled-in blocks: "minecraft:dirt","minecraft:cobblestone", "minecraft:stone". Update `get_solid_block_list()` function if need more.
