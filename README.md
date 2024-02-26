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

```ruby
- Upgrade Backpack
itemName = upgrade_bacpack
itemPrice = dependsOnTheSlotBackpack
item = {-}

- Clothes
itemName = clothes
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

- Rare Clothes
itemName = rare_clothes
itemPrice = 800
item = {
https://growtopia.fandom.com/wiki/Rare_Clothes_Pack
}

- Infernal Shades
itemName = infernal_shades
itemPrice = 
item = {}

- Tidal Shades
itemName = tidal_shades
itemPrice =
item = {}

- Verdant Shades
itemName = verdant_shades
itemPrice = 
item = {}

- Transmutation
itemName = transmutation_device
itemPrice =
item = {}

- Contact Lens
ItemName = contact_lenses
itemPrice = 
item = {}

- Eye Drops
itemName = eye_drops
itemPrice = 
item = {}

- Nyan Hat
itemName = nyan_hat
itemPrice =
item = {}

- Tiny Horsie
itemName = tiny_horsie
itemPrice =
item =
```
