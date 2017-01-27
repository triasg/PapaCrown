# PapaCrown
PapaCrown is ESO Addon.  
Version: 1.6.3  
APIVersion: 100018  

PapaCrown Fixed & Improved made by @triase to continue work of @Area51Visitor on PapaCrown untill he return.   


Increases the size of leaders crown so no one has excuse for being lost .  

Changing the color of the icon is impossible, but you can change the texture file it references.   
For example, replace the line of code in the addon with this to get the red ebonheart pact banner:  

SetFloatingMarkerInfo(MAP_PIN_TYPE_GROUP_LEADER, 64, "EsoUI/Art/MapPins/AvA_flagEbonheart.dds")  

If you decide to change it...be sure to close your game and log back in; just reloading UI will crash it.  

- Edited function in attempt to stop crashing.