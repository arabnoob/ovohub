This is NOT Made by me, Credits to the owner.

Credits to Bloodball for Discord UI Script

i'm wasting my time for y'all to have a friendly documentation.

i will be releasing a lib, who knows? maybe not.



Showcase:
![](Showcases/Screenshot_20221124-165259_CapCut.jpg)





### Booting Up the Library

```lua

local DiscordLib = loadstring(game:HttpGet "https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/discord")()

```






### Making the Library's Title

```lua

local win = DiscordLib:Window("discord library")

```






### Creating a Server

```lua

local serverid = win:Server("Preview", "https://www.roblox.com/library/4689592025/White-Roblox-Icon")

```






### Creating a Channel

```lua

local channelid = serverid:Channel("testing")

```






### Creating a Button

```lua

channelid:Button(
    "Test",
    function()
    DiscordLib:Notification("Notification Title", "Description", "button text")
  end
)

```





### Creating a Separator

```lua

channelid:Separator()

```
