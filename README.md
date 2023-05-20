# Unit Frames for WoW 1.12.1

**Feel free to fork this but give credit (at least author & link to this github)**

**DO NOT REUPLOAD! LINK HERE INSTEAD.**


#### Player & Target
![Alt text](http://i.imgur.com/ON0y6Qw.png)

#### Raid Frames
![Alt text](http://i.imgur.com/oZn1sxT.png)


## HIGHLIGHTS:
**- An amazing tag system lets you completly customize the text being displayed**<br/>
**- A huge selection of bar textures and fonts to choose from**<br/>
**- Buff timers. (for your own)**<br/>
**- Totem timers**<br/>
**- Shows your mana while in cat / bear form**<br/>
**- XP and Reputation Bar**<br/>
**- You can reset instances via the right click menu**<br/>
**- All bars are positionable in a custom order. You can make the portrait into a bar too or disable it**<br/>
**- Enemy castbar**<br/>
**- Predicts incoming heals on you, your target, party and raid (also shows other people if they have this addon)**<br/>
**- Shows incoming resurrections from cast start till the accept window expires**<br/>
**- Range checker for the party and raid**<br/>
**- Energy ticker**<br/>
**- The fastest healthbars of all the raidframes out there (Actually blizzards are the same since its the same method of updating every frame but don't tell anyone)**<br/>
**- Raidframes show units with aggro by an indicator**<br/>
**- Click casting interface (no 3rd party addon required)**<br/>
**- Mouseover casting system: Use /lunamo or /lunamouseover followed by your spell of choice to make the macro behave like a normal spell button on your bar but when you are over a frame it casts on that target**<br/>

**Example:**

**/lunamo Greater Heal**

**The first line in this macro is equal to a '#show' you might know from live WoW. With this, bar addons that color your bar depending on if you have the mana for the spell will pick it up even though its a macro. Its optional.**



**Download the newest version and follow the development at: [LunaUnitFrames](https://github.com/jimmytaker/LunaUnitFrames/tree/TurtleWoW)
This supports [MobHealth3](http://legacy.curseforge.com/media/files/72/65/mobhealth3-mobhealth3-3-2.zip) (but you have to install it).
Get [BonusScanner](http://www.curseforge.com/media/files/66/890/bonusscanner-1-2.zip) if you are a healer to factor in any bonus healing you might have.**


## FAQ

**Q: After downloading your addon doesn't show up in the game.**<br/>
**A: Please remove the "-master" from the folder name.**

**Q: How do i open the configuration?**<br/>
**A: Try /luf /luna or /lunaunitframes**

**Q: How do i move stuff?**<br/>
**A: There is an unlock button in the configuration. Raidframes are moved by dragging their text (GRP1 etc).**

**Q: Can i have spinning timers on anything other than player?**<br/>
**A: No, not possible with the vanilla client. There could be unreliable timers but i'm not gonna do that.**

**Q: Why is there no 40y range check?**<br/>
**A: There is a 40y check but it doesn't work as reliable as the 30y one. Range works the same way as it does in (non modified) all other Raidframes (sRaid, Grid, etc...). There is an easy way to check for up to 30y with the UI functions but the 40y check is based on combatlog. This means if you are standing in IF you won't see 40y because others are not producing combat log events. But if you are in a raid and others do something every like 3 seconds they are refreshed as "in range". I know there is other hacks of raidframes out there where every unit in the raid gets targeted every 0.5 seconds to see if a 40y spell is in range but that heavily affects performance and/or other behavior of the frames.**

**Q: Why can't i see health values for enemys?**<br/>
**A: As stated above you have to install [MobHealth3](http://legacy.curseforge.com/media/files/72/65/mobhealth3-mobhealth3-3-2.zip). If you have installed it correctly you should see HP numbers after the mob lost 10% health. By default MobHealth3 doesn't save its data between sessions so you would have to wait those 10% again after relogging / reloading UI.**

**Q: How do i turn off portraits??**<br/>
**A: Turn portrait to bar -> Choose portrait from the second dropdown -> move the slider below that dropdown all the way to the left.**

**Q: I am getting tons of LUA errors!**<br/>
**A: If you get LUA errors please post something like a report from ImprovedErrorFrame and what you were doing at the time. Or anything else that might help to describe the issue.**

**Q: Can i donate?**<br/>
**A: paypal.me/LunaUnitFrames (Donations are non-refundable / don't entitle you to anything)**
