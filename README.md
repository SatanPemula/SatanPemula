# Debug Store Growtopia
- Growtopia store item name debug list, hopefully it's useful

- Discord Server : [Click Kontol](
https://discord.com/invite/mXUZ7Fj49u) 

### Creditod

```
BY : RaizelSatana

Discord : satanlua

Donate World : SatanPro 🗿

Don't ever admit that you wrote this, because I'm so tired of writing all this debugsh*t
```
### Example of Converting To Scriptod
- Genta Hax 
```lua
itemName = "world_lock"
itemPrice = 2000
item = {242}

function shit() 
for _, item in pairs(getInventory()) do
for _, x in pairs(item) do
if item.id == x then
sendPacket(3 -1, "action|drop\n|itemID|"..x)
sendPacket(3 -1,"action|dialog_return\ndialog_name|drop_item\nitemID|"..x.."|\ncount|"..item.amount)
sleep(200)
end
end
end
end

function getItemInv(item_) 
for _, item in pairs(getInventory()) do
if item.id == item_ then
return item.amount 
end
end
return 0
end

while getLocal().gems >= itemPrice do
if getItemInv(242) == 200 then
shit() 
sleep(math.random(180, 200))
else
sendPacket(2, "action|buy\nitem|".. itemName) 
sleep(math.random(180, 200)) 
end
end
```
### List 
```lua
"Player Items" = I
"World Building" = II
"Activites" = III
"Creativity" = IV
"Growtokens" = V
```
### ・I

```js
- Backpack Upgrade
itemName = "upgrade_bacpack"
itemPrice = dependsOnTheSlotBackpack
item = {-}

- Clothes Pack
itemName = "clothes"
itemPrice = 50
item = {
370,
3578,
372,
374,
42,
68,
40,
130,
270,
236,
142,
694,
10034,
140,
76,
48,
44,
34,
36,
122,
238,
66,
38,
90,
208,
272,
144,
2938
354,
138,
214,
11202,
342,
1846,
210,
234
}

- Rare Clothes Pack
itemName = "rare_clothes"
itemPrice = 500
item = {cari_sendiri_di_wiki}

- Infernal Shades
itemName = "infernal_shades"
itemPrice = 25000
item = {
12474
}

- Tidal Shades
itemName = "tidal_shades"
itemPrice = 25000
item = {
12476
}

- Verdant Shades
itemName = "verdant_shades"
itemPrice = 25000
item = {
12478
}

- Transmutabooth
itemName = "transmutation_device"
itemPrice = 25000
item = {
9170
}

- Contact Lens Pack
ItemName = "contact_lenses"
itemPrice = 15000 
item = {}

- Eye Drop Pack
itemName = "eye_drops"
itemPrice = 30000
item = {}

- Turtle Hat
itemName = "nyan_hat"
itemPrice = 25000
item = {}

- Tiny Horsie
itemName = "tiny_horsie"
itemPrice = 25000
item =

- Pleadian Star Ship
ItemName = "star_ship"
itemPrice = 25000
item =

- Dragon Hand
itemName = "dragon_hand"
itemPrice = 50000
item =

- Little Red Corvette
itemName = "corvette"
itemPrice = 25000
item =

- Stick Horse
itemName = "stick_horse"
itemPrice = 25000
item =

- Ambulance
itemName = "ambulance"
itemPrice = 25000
item =

- Riding Raptor
itemName = "raptor"
itemPrice = 25000
item =

- Mid-Pacific Owl
itemName = "owl"
itemPrice = 30000
item =

- Unicorn Garland
itemName = "unicorn"
itemPrice = 50000
item =

- StarBoard
itemName = "starboard"
itemPrice = 30000
item =

- Growley Motorcycle
itemName = "motorcycle"
itemPrice = 50000
item =

- Monkey On Your Back
itemName = "monkey_on_back"
itemPrice = 50000
item =

- Carrot Sword
itemName = "carrot_sword"
itemPrice = 15000
item =

- Red Bicycle
itemName = "red_bicycle"
itemPrice = 30000
item =

- Fire Truck
itemName = "fire_truck"
itemPrice = 50000
item =

- Pet Slime
itemName = "pet_slime"
itemPrice = 100000
item =

- Dabstep Low Top Sneakers
itemName = "dabstep_shoes"
itemPrice = 30000
item =
```

### ・II