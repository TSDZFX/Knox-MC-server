Royal Dih is the heavy tank of this server, he mainly uses crossbow rockets and dals high AOE damage 

Command block structure

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

4: Crossbows
```
/give @p minecraft:crossbow[item_name="Big Dih",enchantments={"minecraft:unbreaking":255,"minecraft:vanishing_curse":1,"minecraft:quick_charge":2,"minecraft:infinity":1}] 2
```

5: Short Fireworks 
```
/give @p firework_rocket[custom_data={rocket:"short"},item_name="Red Rocket",minecraft:enchantments={"minecraft:vanishing_curse":1},fireworks={flight_duration:0,explosions:[{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]},{shape:"small_ball",colors:[I;11743532]}]}] 128
```

6: Long Fireworks
```
/give @p firework_rocket[minecraft:enchantments={"minecraft:vanishing_curse":1},fireworks={flight_duration:2,explosions:[{shape:"large_ball",has_twinkle:0,has_trail:0,colors:[I;12801229],fade_colors:[I;12801229]},{shape:"large_ball",has_twinkle:0,has_trail:0,colors:[I;2651799],fade_colors:[I;3887386]},{shape:"large_ball",has_twinkle:0,has_trail:0,colors:[I;1973019,3887386,8073150,2651799,11250603,4408131,14188952,4312372,14602026,6719955,12801229,15435844],fade_colors:[I;1973019,11743532,3887386,5320730,2651799,11250603,6719955,12801229,15435844]},{shape:"large_ball",has_twinkle:0,has_trail:0,colors:[I;11743532,3887386,5320730,2437522,8073150,2651799,11250603,4408131,14188952,4312372,6719955,12801229,15435844],fade_colors:[I;1973019,11743532,4408131,4312372,6719955,12801229]},{shape:"creeper",has_twinkle:0,has_trail:0,colors:[I;11743532,3887386,2651799,4408131,4312372,6719955,12801229,15790320]},{shape:"burst",has_twinkle:0,has_trail:0,colors:[I;1973019,11743532,3887386,5320730,2437522,8073150,2651799,11250603,4408131,14188952,4312372,14602026,6719955,12801229,15435844,15790320],fade_colors:[I;1973019,11743532,3887386,5320730,2437522,8073150,2651799,11250603,4408131,14188952,4312372,14602026,6719955,12801229,15435844,15790320]},{shape:"large_ball",has_twinkle:0,has_trail:0}]}] 128
```

7: Armour 

Helmet
```
/item replace entity @p armor.head with minecraft:iron_helmet[minecraft:enchantments={"minecraft:vanishing_curse":1,"minecraft:protection":4},trim={pattern:silence,material:gold}]
```

Chest plate 
```
/item replace entity @p armor.chest with minecraft:iron_chestplate[trim={pattern:eye,material:gold},minecraft:enchantments={"minecraft:vanishing_curse":1,"minecraft:protection":4}]
```

Leggings 
```
/item replace entity @p armor.legs with minecraft:iron_leggings[minecraft:enchantments={"minecraft:vanishing_curse":1},trim={pattern:silence,material:gold}]
```

Boots
```
/item replace entity @p armor.feet with minecraft:iron_boots[minecraft:enchantments={"minecraft:vanishing_curse":1},trim={pattern:silence,material:gold}]
```

8: Food 
```
/give @p minecraft:golden_apple[minecraft:enchantments={"minecraft:vanishing_curse":1}] 64
```

9: Effects

Health Boost 
```
/effect give @p minecraft:health_boost infinite 14
```

Slowness
```
/effect give @p minecraft:slowness infinite 1
```

Regeneration 
```
/effect give @p minecraft:regeneration 10 255
```

10: Slowness arrows 
```
/give @p tipped_arrow[potion_contents={custom_effects:[{id:"minecraft:slowness",duration:800,amplifier:0}]},enchantments={"minecraft:vanishing_curse":2}] 192
```