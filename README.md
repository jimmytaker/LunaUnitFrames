# LunaUnitFrames
Unit Frames for WoW 1.12.1


Feel free to fork this but give credit (at least author & link to this github)

DO NOT REUPLOAD! LINK HERE INSTEAD.


paypal.me/LunaUnitFrames

Donations are non-refundable / don't entitle you to anything


## HIGHLIGHTS:
-An amazing tag system lets you completly customize the text being displayed

-A huge selection of bar textures and fonts to choose from

-Buff timers. (for your own)

-Totem timers

-Shows your mana while in cat / bear form

-XP and Reputation Bar

-You can reset instances via the right click menu

-All bars are positionable in a custom order. You can make the portrait into a bar too or disable it

-Enemy castbar

-Predicts incoming heals on you, your target, party and raid (also shows other people if they have this addon)

-Shows incoming resurrections from cast start till the accept window expires

-Range checker for the party and raid

-Energy ticker

-The fastest healthbars of all the raidframes out there (Actually blizzards are the same since its the same method of updating every frame but don't tell anyone)

-Raidframes show units with aggro by an indicator

-Click casting interface (no 3rd party addon required)

-Mouseover casting system: Use /lunamo or /lunamouseover followed by your spell of choice to make the macro behave like a normal spell button on your bar but when you are over a frame it casts on that target

Example:

/script if nil then CastSpellByName("Greater Heal(Rank 1)") end
/lunamo Greater Heal(Rank 1)

The first line in this macro is equal to a '#show' you might know from live WoW. With this, bar addons that color your bar depending on if you have the mana for the spell will pick it up even though its a macro. Its optional.



Download the newest version and follow the development at: [LunaUnitFrames](https://github.com/jimmytaker/LunaUnitFrames/tree/TurtleWoW)
This supports MobHealth3 (but you have to install it :D ).
Get BonusScanner if you are a healer to factor in any bonus healing you might have.


## FAQ

Q: After downloading your addon doesn't show up in the game.
A: Please remove the "-master" from the folder name.

Q: How do i open the configuration?
A: Try /luf /luna or /lunaunitframes

Q: How do i move stuff?
A: There is an unlock button in the configuration. Raidframes are moved by dragging their text (GRP1 etc).

Q: Can i have spinning timers on anything other than player?
A: No, not possible with the vanilla client. There could be unreliable timers but i'm not gonna do that.

Q: Why is there no 40y range check?
A: There is a 40y check but it doesn't work as reliable as the 30y one. Read point 4 of this post and point 1 of this one for a detailed explaination.

Q: Why can't i see health values for enemys?
A: As stated above you have to install [MobHealth3](http://legacy.curseforge.com/media/files/72/65/mobhealth3-mobhealth3-3-2.zip). Also read point 3 of this post.

Q: How do i turn off portraits??
A: Turn portrait to bar -> Choose portrait from the second dropdown -> move the slider below that dropdown all the way to the left.

Q: I am getting tons of LUA errors!
If you get LUA errors please post something like a report from ImprovedErrorFrame and what you were doing at the time. Or anything else that might help to describe the issue.
