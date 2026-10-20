
1: gamemode 
```
gamemode @p survival 
```

2: Clear inventory 
```
@p clear
```

3: Effects clear
```
effect clear @p 
```

4: Food 
```
/give @p minecraft:golden_apple[minecraft:enchantments={"minecraft:vanishing_curse":1}] 64
```

5: Spear
```
/give @p minecraft:iron_spear[enchantments={"minecraft:unbreaking":255,"minecraft:lunge":4,"minecraft:vanishing_curse":1,"minecraft:sharpness":5}] 1
```

6: Armour

Chest plate
```
/item replace entity @p armor.chest with diamond_chestplate[minecraft:enchantments={"minecraft:vanishing_curse":1,"minecraft:protection":4},minecraft:trim={pattern:silence,material:netherite}]
```

Boots
```
/item replace entity @p armor.feet with minecraft:diamond_boots[trim={pattern:flow,material:netherite},minecraft:enchantments={"minecraft:vanishing_curse":1}] 1
```

7: Effects

Speed
```
/effect give @p minecraft:speed infinite 1
```

Strength
```
/effect give @p minecraft:strength infinite 2
```

Health 
```
/effect give @p minecraft:health_boost infinite 4
```

Saturation
```
/effect give @p minecraft:saturation 7 225
```

Regeneration 
```
/effect give @p minecraft:regeneration 7 13
```

