# GentaHax Structure

## logToConsole

・logToConsole(std::string)

A structure representing a log for displaying text
## Example Methode
```lua
function log(str)
logToConsole(str)
end
log("Hello Kontol :D") -- print to Console.
```
## sleep

・sleep(int) // int ( sleep time in ms )
## Example Methode
```lua
sleep(1000) = 1 Sec.
```
## findPath

・findPath(int_x, int_y, int_delayMs) 
delay is Optional.
## Example Methode
```lua
findPath(0,0)
```
## sendPacket

・sendPacket(int_type, std::string pkt) // Type,Packet
## Example Methode
```lua
world = "GHAXTEST"
id = "0"
sendPacket(3, "action|join_request\nname|".. world .. "|".. id)
```
## sendPacketRaw

・sendPacketRaw(bool send_to_client, TankPacketStruct packet)
### Example Methode
```lua
function wearCloth(item) 
  sendPacketRaw(false, {
    value = item, 
    type = 10
  })
end
wearCloth(98)
```
## getWorld

・world * getWorld() -- Return World Name
### Example Methode
```lua
logToConsole("i Standing in World : ".. getWorld().name..":D")
```
## getTiles

・ngentod Haha :D
### Example Methode
```lua
for _, tile in pairs(getTiles()) do
if tile.fg == 242 then
logToConsole(" i Found World Lock in Postion ".. tile.x.. ",".. tile.y)
end
end
```
## getTileExtra
