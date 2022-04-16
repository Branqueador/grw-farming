# How to change grw-farming prices

#### Go to line 54, and there you can change min and max price that it  gives randomly
#### The stuff bellow is near line 54

```lua
Config.ItemList = {
    ["orange"] = math.random(20, 40),
    ["milk"] = math.random(30, 45),
	["corn_kernel"] = math.random(7, 14),
    ["corn_packet"] = math.random(120, 240),
    ["milk_pack"] = math.random(120, 240),
	["fruit_pack"] = math.random(120, 240),
	["grapejuice"] = math.random(100, 150),
	["wine"] = math.random(150, 250),
	["packedbeef"] = math.random(250, 550),
	["packedpig"] = math.random(250, 450)
}
```

