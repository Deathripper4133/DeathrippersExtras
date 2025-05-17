# Squad Modding
 This Repo showcases the features I've made for the Squad Modding Community. These are crude unlike complete plug n play mods. This is more or less meant to share 'core' features. Expect ALL provided UIs to be DEMO versions, basically not intended for actual use. 
 >Note: Not all of the features I've made for other mods will be posted, some will remain private. In other words I will not release ALL of the stuff I've worked on.

I dont really plan to upkeep these features outside of maybe game breaking bugs. Listed below are all the projects of this repo and their features.

## Projects

### Kit Manager
The basic mechanic of the kit manager allows you to change your kit (Inventory + Soldier) or choose between changing only Soldier/Inventory. When choosing a soldier, you can also specify the biome. Optionally, you can leave the default choice of "Layer Based," which will choose a soldier mesh that fits the current layer (ie Desert Map will choose Desert Soldier Variants).

Additional Features
1. Keybind
    * Players can access the KitManager UI through a keybind. 
    * Keybind: Backspace
    >Can be disabled.

2. Loadout Cache
    * In game deployable that allows players to access the KitManager UI in case keybind is disabled.

3. Respawns
    * After selecting a custom kit and Respawing, it will auto switch you back to your custom kit. 
    * Switching Deploy Role ("Vanilla Role") either through Deployment Screen or a Radial Menu will disable auto switch upon respawn (unless you switch back before respawn).
    * Auto Switcher will change you to the correct Vanilla Role upon death so you can get your custom kit once respawned.
        >Auto Switcher can be disabled.

4. Scroll Box and Search Bar
    * Unfortunately I got no idea how to sort kits into Factions so for the time being we got a big ol list and a search bar
    * On the brightside this shows ALL kits regardless of if they are in a factionsetup.

5. Share and Repack
    * Quick Repack (Hotkey)
        * Will repack (merge) your current mag with the last mag in your weapons inventory. Then add the mag(s) to weapons inventory.
            >you will have to reload.

    * Quick Share (Hotkey) 
        * Item or Magazine with another person. Hotkey will share item/mag #2. 

Video Showcase: https://youtu.be/mgvzLo90xT8 

5. Continued
    * Quick Share UI
        * Will share the selected mag/item instead of #2 in weapons inventory.

    * Precise Repack UI
        * Balance out mags or top off a mag by precisely adding bullets from another selected mag.

    * Quick Repack UI 
        * The same function as hotkey except you can choose a mag to quickly repack into.

    * Precise Repack (Hotkey)
        * Allows players to precise repack the weapon in their hand, however locks weapon usage during and after a short delay

Video Showcase: https://youtu.be/sfC8w2s2H3U

Special thanks to Mekki for the "RoleUtilities" he posted. I've only done a handful of changes to his code but otherwise the inventory switching is mostly done by his code.


6. Inventory Viewer
    * Will be able to see others' inventory
        * Disarm Player 
            * Will remove all items of inventory and add BP_Surrender

        * Restrain Player 
            * Will add BP_Surrender, switch to surrender, and lock weapon input

        * Request Ammo (not available while in admin cam)
            * Players can request Items/Mags from each other.
        
        * Remove Equippables
            * Players' SLs/CMD can remove items from their inventory

Video Showcase: https://youtu.be/dsXS9yfoARU

7. Insert/Replace/Remove items from inventory
    * Not much else to say, you Insert, Replace, and Remove stuff from  your Inventory now

Video Showcase: https://youtu.be/0n-iHUvkgR8


### Mod Menu
Basic Menu that will be used to access other projects' UI

Keybind: "U"

### Night Vision
Allows players to see at night... Actor includes 4 Materials (Green, Blue, Multicolor, Yellow) and allows for additional materials to be added easily (and categorized for easy tracking/disabling)

Additional Features
* Basic UI
    1. Cycle Options
        * Cycles through all available options before turning off NVGs

    2. NVG Type
        * Select a specific type to use (ie green, blue)

    3. Tube Count
        * How many tubes display the NVG material

    4. Tube Location
        * When tube count is single; determines where the single tube is located

    5. Emergency shut OFF
        * Turns off NVGs incase keybind is broken or smth

Video Showcase: https://youtu.be/NvTXIMXEnDY

* Admin Menu UI: will be able to toggle use of certain features
    * Per Team Options
    * Toggle NVG use (can keybind be pressed)
        * White/Black list of Categories (ie can allow only thermals or disable all thermals from being used)
    * Toggle NVGs (toggle on/off)
    * Toggle Parameter Changes (can player change the following)
        * Cycle NVGs
        * Tube Type
        * Tube Count
        * Tube Location

Video Showcase: https://youtu.be/JqlKpEnpV1w


