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

5: Bow 
```
/give @p minecraft:bow[minecraft:enchantments={"minecraft:infinity":255,"minecraft:power":3,"minecraft:punch":3,"minecraft:vanishing_curse":1,"minecraft:unbreaking":255}]
```

6: Axe
```
/give @p minecraft:stone_axe[minecraft:enchantments={"minecraft:unbreaking":225,"minecraft:vanishing_curse":1}]
```

7: Armour

Helmet
```
/item replace entity @p armor.head with minecraft:turtle_helmet[enchantments={"minecraft:unbreaking":225,"minecraft:vanishing_curse":1},trim={pattern:snout,material:lapis}]
```

Elytra
```
/item replace entity @p armor.chest with minecraft:elytra[enchantments={"minecraft:unbreaking":3,"minecraft:vanishing_curse":1}] 1
```

Leggings
```
/item replace entity @p armor.legs with minecraft:chainmail_leggings[enchantments={"minecraft:unbreaking":225,"minecraft:vanishing_curse":1},trim={pattern:snout,material:lapis}]
```

Boots
```
/item replace entity @p armor.feet with minecraft:diamond_boots[enchantments={"minecraft:unbreaking":225,"minecraft:protection":3,"minecraft:feather_falling":255,"minecraft:vanishing_curse":1},trim={pattern:snout,material:lapis}]
```

8: Pearls
```
/give @p minecraft:ender_pearl[minecraft:enchantments={"minecraft:vanishing_curse":1}] 64
```

9: Arrow
```
/give @p minecraft:arrow[minecraft:enchantments={"minecraft:vanishing_curse":1}]
```

10: Effects

Health 
```
/effect give @p minecraft:health_boost infinite 2
```

Speed
```
effect give @p minecraft:speed infinite 1
```

Regeneration
```
effect give @p minecraft:regeneration 7 255
```

