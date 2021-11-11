===GHILLIE SUIT OVERHAUL v1.5 ===
Ghillie suit can be worn over other armors, reworked detection method and other tweaks to make the ghillie suit more useful nor too OP

Conflicts: addons which modify o_lcs.ltx, visual_memory_manager.script and trans_outfit.script. Patches are provided for Stealth, 
HD models and THAP. Additional patch for Mags Redux to prevent magazine unequipping and to remove loadout slots for ghillie.
If you have other conflicts or errors let me know in the comments or the anomaly discord(log and modlist required)
Recommended to use alongside Mora's AI more covered, Stealth, THAP/EFT hands pack(because the vanilla model and hands are quite bad) and 
Grok's/Nav's masks for the best experience

1. Ghillie Suit is now used as an attachment rather than a seperate outfit. It can be worn over
   any outfit that has a backpack slot(optional enabler for 2 novice outfits and exo category included)
2. All of its protection values are null and upgrade schemes are removed
3. The detection formula has been slightly reworked(the vanilla one was just horrible tbh). 
   It changes NPC vision range and field of view based on:
   a). The surface youre standing on. Only grassy and dirt surfaces allows you to stay hidden(this can be changed 
   in the script, guide provided)
   b). The player stance. Standing and running will get you easily detected, crouching allows you to approach enemies closer and being prone(Ctrl+Shift
  low crouch in anomaly terms) will let you approach them really really close and you can actually sneak past them
   c). The current weather. Its easier to stay hidden in rainy and foggy weather compared to clear and cloudy weather 
   d). The time of day, obviously its better to sneak at night
   e). But it you get detected somehow, you're no longer hidden and have to break line of sight by getting to cover if you wanna stay hidden again
   f). Don't be dumb, using flashlights and torches will get you detected even if you're wearing the suit. Why would you do that though?
   g) firing with a non-silenced weapon could give away your position
   Or if you want a dynamic experience you can use it alongside stealth addon(patch provided)
4. The actor visuals are managed in a realistic way. If you wear a ghillie over an outfit your visuals will change to the ghillie and 
	will revert if you unequip it. And the ghillie will be automatically unequipped if you want to equip a different main outfit. 
5. MCM support provided so you can tweak some settings to your liking
6. Added Mask overlay for ghllie which can be toggled on/off via MCM
7. Decreased price and weight for balancing purposes

Installation :
rather straight forward, copy gamedatas from
1) 00. Main addon 
2) Apply the correct patches for the ones you're using
3) Optional enabler for exos, nosorogs, protoexos, and novice outfit should you need it
Recommended to use Mod Organizer 2 as for any anomaly addon installation
 
known bugs/drawbacks
1. Some areas doesn't have grass even though classified as grass surfaces by the game and everything just depends on what the engine
   thinks rather than what you actually see. And I can't do anything about the engine
3. It seems random but ghillie sometimes gets unequipped on level change and maybe even on loading a save

Changelog :
v1.5 - updated patch for stealth 2.0 and updated gamemtl.xr (enemies dont see through bushes)
v1.4 - small hotfix to fix ghillie unequipping bug permanently and made some tweaks to the formula
v1.3 hotfix - fixed loading/level change bug permanently 
v1.3 - Big update. Updated patch to latest stealth addon 1.9.4, fixed few bugs with firing alert (with MCM sliders) and 
surface detection. Added russian translation for MCM
v1.2 - Updated patch for stealth to latest version 1.9.3 (with version 1.9.2 also provided just in case)
v1.1 - Fixed an error with patch for Mags Redux, its working now
v1.0.9 - Optimized a major portion of the scripts, slightly tweaked formula and added patch for Mags Redux
v1.0.8 - fixed an issue with artifacts getting unequipped, made the foliage overlay standalone, slight other tweaks. For those who don't use mod manager,
    you can delete the hud_exo12.dds from the previous versions
v1.0.7 - fixed an issue with ghillie overlay being triggered on changing settings + a few adjustments with stealth addon patch
v1.0.6 - improved the formula for stealth 1.9.2 users
v1.0.5 - Added foliage overlay, fixed a few bugs associated with equip/unequipping outfits and made alterations to the formula
v1.0.4 - fixed ghillie suit getting unequipped on looting, small changes to MCM sliders
v1.0.3 - fixed an error associated with stats_table


Credits to the whole Anomaly discord channel, especially 
ravenascendant for helping me with the scripts and for MCM
xcvb/bvcx for his guidance and help with for stealth addon compatibility
HarukaSai for letting me steal portions from his script like always :P
Grok and Ishmael for their additional assistance in scripting
Jurkonov for the screenshots
Nav's masks for the overlay texture
