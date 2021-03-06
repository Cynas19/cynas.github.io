# cynas.github.io

2.01: Fixed some "or"s that should have been "and"s; updated chest bosses with a letter identifier and changed default off icons to dim instead of grayscale based on community feedback.

Release Notes for SMRPG Randomizer Tracker 2.0 by Cynas (https://www.twitch.tv/cynas)

Thank Yous

A HUGE thank you to Strizer86, who helped troubleshoot the code on this update and constantly offered encouragement and inspiration.

Thanks also to the SMRPG randomizer community, with special thanks to the knowledgeable and forward-thinking folks who helped with chest logic, Natalie and patcdr!

One last thank you to the SMRPG randomizer developers, without whom the game we love would be lesser.  You're the REAL heroes here, and we hope you know that we appreciate your hard work.  Special thanks to Pidge who took the time to chime in, offer advice, and give us a glimpse of the future of the randomizer.

Changelog (1.0 --> 2.0)

-Yaridovich fixed (was incorrectly coded as "yardovich", whoops).

-The original variants (Items Only, Items with Characters, and Items with Characters and Bosses) have gotten a layout and broadcast layout update, which eliminates most of the dead space.

-I ended up doing so many variations that I threw in a similar layout, "Items with Bosses" that mostly follows the same scheme as the previous three.

-Added a new "Minimalist" layout and broadcast layout for those with very little space in their stream/monitor.  This only tracks stars and key items that can gate boss/star progression (Castle Key 1 & 2 to Nimbus Land, and the Bambino Bomb to Moleville Mines).

-Map tracking is here!!  For tracking with a map, it is highly recommended that you use the boss icon (left click) to indicate that the location is checked, and the check mark (right click) to indicate that the boss has been defeated.  There are three new layouts to customize your SMRPG Randomizer experience:

 -"Key Item Shuffle and Star Hunt" layout has absolutely everything this tracker has to offer: stars, key items, characters, bosses, the map with boss locations, key item locations, shop locations, and randomized item locations (both chests and npc rewards) complete with working gates and pinned locations.  You can even use the pins to remind you which shops to revisit in the future but dropping an icon into the dotted square.  This version of the tracker is ideal for those playing with the Key Item Shuffle, or the future Star Hunt mode where key items and stars can be found anywhere.  The drawback is that this tracker can get fairly crowded.  This variant uses the broadcast layout from "Items with Characters and Bosses".

 -"Full Tracker" subtracts randomized item locations from the above, and uses the same broadcast layout, "Items with Characters and Bosses".

 -"Map with Items and Characters" subtracts the boss icon column, but bosses locations can still be tracked using the map.  This variant uses the broadcast layout from "Items with Characters" to save screen real estate on your stream as well as your desktop.

Notes:
There are some known imperfections with this release.  Most rely on the user having some understanding of the randomizer.

-Yo'Ster Isle is listed as accessible with no requirements.  The real requirement is to use the exit from the Pipe Vault to access Yo'Ster Isle.  We got around this on Grate Guy's Casino by requiring the Bright Card, but there wasn't an intuitive solution to Yo'Ster Isle that didn't require the user to have a similar or greater amount of knowledge.

-Only the shops can capture icons.  It could very easily be done with bosses as well, but the only good application of this is for the flag "Bosses Do Not Scale With Locations".  If there's enough demand, I could reinstate this at a later date.  For this release, simplicity was the goal.

-Vista Hill (no significance), Midas River (1 randomized item), Pipe Vault (7 randomized items), Booster Pass (2 + 3 randomized items), and Booster Hill (flower mini-game) are only shown in the "Key Item Shuffle and Star Hunt" variant, since they do not have bosses, key items, stars, or shops.

-The Ghost's shop at the Sea and Sunken Ship locations are the same, but is only listed at the Sea.  It is assumed that if a user encounters that shop and intends to return to it later (the principle use of pinning a location) that they are vastly more likely to revisit it at the Sea location, or do it while they complete the Sunken Ship.  The former justifies the arrangement in the tracker, and the latter is a user with enough knowledge of the randomizer to understand why the shop is only listed at the Sea.

-The shop run by imposters at Seaside Town is listed as accessible after the Shed Key is obtained and used, even though it shouldn't be (I'll try and come up with a solution to this).

-The key item located in the Kero Sewers (originally the "Cricket Jam" in non-randomized games), is listed at Land's End because the only (currently known) way to access it is from Land's End.

-Bowser's Keep is always listed as open, but may not be depending on your flag set.  This is another case where it was easier to trust the user to know what flags they picked than to add a bunch of options for one location.

-The Factory location only opens when star 6 is marked on the tracker, but depending on the user's flag set it may not open until star 7.

---------------------

SMRPG Randomizer Tracker 1.0 by Cynas Release Notes!

Thank Yous

First and foremost, thanks to the following people; without their help, this project would never have gotten off the ground:

-Emosaru (core, troubleshooting, release)

-Beenieweenie (troubleshooting, idea exchange)

-JRJathome (troubleshooting)

-Natalie (troubleshooting)

-Fouton (inspirational design, code layout)

What's in the Package

The install comes with several layout options (you can change them easily by clicking the gear icon, "installed packages", "SMRPG Randomizer Tracker by Cynas", and pick the layout you like best):

-Items Only (stars, keys, flags, key progression items) - many of these icons are "progressive", and clicking the icon has multiple stages - in open mode, you may wish to note not only when you acquire a key item, but when use it/turn it in.

-Items with Characters - in addition to the above, adds portraits of the player characters.  In open mode, you have the option of randomizing your starting party member(s) and those that you encounter later in the game.  These portrait panels indicate to your audience the characters you've recruited thus far.

-Items with Characters and Bosses - adds bosses to the tracker in addition to the above.  Because of the boss shuffle option in open mode randomizer, none of these icons are progressive, however, right-clicking the portrait will place a checkmark over the boss portrait.  This is in place so that you can not only mark bosses as defeated (left-click), but also check off the location checked as well (right-click).

Other Features and Future Plans

Variable Sprites for Icons
Lots of work went into creating icons that are memorable and interesting, and even the fonts are ripped from the game for a very authentic look.  So much so that Yardovich broke the tracker once.  Refights have different sprites to keep things interesting, and make your stream look awesome, just like the randomizer you're playing!

Full Chathud Support
The command list for ChatHUD is ever growing for this pack.  If you need help activating ChatHUD for your new tracker, send me a DM, or parse the discord for Emosaru's release notes to enable ChatHUD (I can also tell you how to add custom commands for each icon on the tracker).  Below is a link to the pastebin that has a full list of working commands for each icon on the tracker.

https://pastebin.com/AhjkyvKQ

Layout Update
The layout is just okay.  I have a couple more ideas I'd like to implement when I get more time:

-Changing the star layout to be more like games star pieces screen.  I'd like to have an alternative layout that instead of organizing bosses in chronological order, has them grouped (e.g. jagger, jinx1, jinx2, and jinx3 all in the same row).

-Multiple grids of different sizes.  There's a few blank spaces that I can eliminate that is easy to do on paper, but difficult for me to execute in code.

-Additional parameter tracking.  I'd like to add icons that allow you to track the number of FP and treasure chests checked.

Thank you for considering my (first) tracker.  I'm open to feedback and ideas for improvements!
