## *Deadly Bloom* Legendary Rarity & Skin Fix

The *Deadly Bloom* rarity bug, as explained on **[Borderlands Wiki - Deadly Bloom](https://borderlands.fandom.com/wiki/Deadly_Bloom)** page:

> Though it displays in inventory as a purple-rarity item, ***the Deadly Bloom is internally classified as a legendary, and is part of the general legendary loot pool***. Because of this the shield has a small chance to be found from any suitable loot source, including from chests and other containers as well as from defeated enemies. 
>
### My solution to fix it:

Such a fix didn't seem to exist for TPS, though, so I took it upon myself to create one... and now, the *Deadly Bloom* has regained his *legit* Legendary rarity... instead of the Epic (purple) rarity.

To find a way to give a Legendary skin to the *Deadly Bloom* make me scratch my head more than once, because unlike the applied solution for the identical bug in BL2, I cannot use the following command:

`set GD_Shields.Material.Material5_Legendary_Nova_DeadlyBloom Material Item_Shields.Materials.Mati_ShieldTorgueLegendary`

... simply because *Item_Shields.Materials.Mati_ShieldTorgueLegendary* don't exist in TPS!!!

And if I make any modification in the actual *Item_Shields.Materials.Mati_ShieldTorgueEpic* used, this will not only apply to the *Deadly Bloom*, but also to all the Torgue Epic (purple) shields skins.

My solution to solve this problem properly, was to borrow the *Vladof Legendary Shield* skin and use it for the *Deadly Bloom*.

![TPS - Moxxi Signature Elegance Gear](https://imgur.com/hE3oOzV.jpg "Don't worry guys... even if my screen capture show French text, my mods are in English")

**Note:** The *Vertical Lines Pattern* are gone, but the *Deadly Bloom* look better with a Legendary skin... at least in my eyes  :wink: 

At least, no change needed to be done to the lootpool, as the *Deadly Bloom* is already in the (correct) Legendary pool.

Enjoy!

### Changelog:

- v1.0.0, November 17, 2018
  - Initial public release
 
### Compatibility:

- 100% compatible with the latest version of [TPS Community Patch](https://github.com/BLCM/BLCMods/tree/master/Pre%20Sequel%20Mods/Community%20Patch)

- Should be compatible with most other mods, as long as they do not touch the *Legendary Nova Shield Properties* or *Nova Spike Properties*

### To do:

- [ ] Find a way to get back the *Vertical Lines Pattern* for the skin.
- [ ] Might be tweaked later... if a better solution is found?
  
### Note: 

Any critique would be appreciated as I am still beginner to make Mods... and by the way, please leave constructive criticism if you make a video. 
Enjoy!

### Disclaimer

All files and content provided here were written by me (Astor), unless stated otherwise.

- They are free for personal use. You may use these mods in videos, or for streaming, as long as you give me proper credit. I would appreciate that you'll letting me know about it, and at least, provide a link to [Github.com/BLCM/BLCMods/Pre-Sequel Mods/Astor](https://github.com/BLCM/BLCMods/tree/master/Pre%20Sequel%20Mods/Astor).

- You may re-use small bits of code (e.g. formulas, behavior modifications, etc) for your own purposes, and let me know about it. 

- Ask me for permission first if you wish to use larger portions of this code, make a modified/improved version, include it in a mod pack, etc..., and don't forget to provide credit.

- Do not re-upload this mod or any of my mods anywhere without my explicit permission... ANYWHERE!

* * * * *



