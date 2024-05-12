# FoundryVTTDaggerheartSWB
This is my Simple Worldbuilding hack for the Daggerheart RPG beta playtest. It only covers level one content at this time, it is largely an engine for you to play your own games.

In order to install this you will need to download and install FoundryVTT v11. Within FoundryVTT install the "Simple Worldbuilding" system, and the following modules:

Auto-Rotate,
Bar Brawl,
Break Time,
Card Hand Mini Toolbar,
Dice so Nice!,
Dice Tray,
Drag Upload (Get Over Here!),
Effect Macro,
Follow Me!,
Freeform Character Sheet,
Item Macro,
Jack Kerouac's Animated Spell Effects,
Jack Kerouac's Animated Spell Effects: Cartoon,
Jack Kerouac's Animated Tokens,
JB2A - Jules and Ben's Animated Assets - Free Content,
Lancer Initiative,
libWrapper,
Patrol,
Pings,
Polyglot,
PopOut!,
Popout Resizer,
Sequencer,
Settings Extender,
Simple Worldbuilding Plus,
socketlib,
Stairways (Teleporter),
Tagger,
Template Macro,
The Forge,
Tidy UI - Game Settings,
Token Attacher,
Token Auras,
Tokenizer,
Token Magic FX,
Token Says,
Token Z,
Warp Gate

---Playtest v1.4.1 Updates---

Cleaned up some of the macros, character sheets, and items.

---Playtest v1.4 Updates!---

Then create a world with the title "Daggerheart" and close FoundryVTT. Download the zip within this repository. Unzip the "daggerheart" folder into your FoundryVTT world folder, and overwrite everything. You should be able to open the world, update it to your version, and  then play!

This product was created using the Darrington Press Community Gaming License. The Daggerheart Open Beta Materials are owned and copyrighted by Darrington Press, LLC. All rights reserved.

This product is based on the following Public Game Content created and owned by Darrington Press: Daggerheart Open Beta Materials, Darrington Press, LLC, 2024, available at daggerheart.com

This product is Adaptive from or based on content created and owned by Darrington Press. Daggerheart Open Beta Materials, Darrington Press, LLC, 2024, available at daggerheart.com.

v1.4 Update Notes:

Updated ALL MACROS! They now use either the first selected token, or if no token is selected then they use the actor assigned to that player. Animations may still require a token selected, but the rolling is now good for it. This is most useful for the GM, and makes it possible for players to control multiple tokens (but also has the risk of rolling from the wrong ones.)

Added a Freeform Sheet for v1.3, it is now broken so you don't need the module but it might be worth fixing. Also added "Bar Brawl" so you can easily see a character's status.

Created a "Trait Dialog" macro so players can have one hotkey for all the traits, which leaves 9 buttons for other hotkey slots. Updated the advantage, and disadvantage to use v1.4 rules and incorporated them into this dialog, and the trait rolls. The class templates were deleted, and not updated, but in the "GM Only" macro folder there is an easy way to add them to a character sheet instead of using the sheet itself. These are the "Experience, Background, and Connection Modifier" macro, and the "Freeform Sheet Trait Adjuster" macro.

Fixed the Beastform item macro, and created guidelines for adding new forms which includes changing the radius, and making the player token invisible, so the level 1 tokens are actually small and you can make the higher level beastforms larger.

Tore down my monoliths, reconfigured the character sheet (shoutout to my player K2 for their CSS) and made more modular macros which refer to one another. This was a lot of work but it will save A LOT of work for higher level play. Created the possibility of "sheet reference" macros, but this also reduced the ability to use macros from the hotkey bar. Win some, lose some; to accommodate this I created a "Macro Hotkey Template" where you replace the UUID with the item from the item tab. It does not work with item UUIDs from the character sheet. Updated all ancestries, communities, classes, subclasses, and domains to the new format. Added the "mixed ancestry" (an example "sheet reference" macro) and made all ancestry features their own item, so when you have a mixed ancestry you can customize it on the character sheet.   

Changed the PC weapon macros so that the number of dice (per proficiency) is shown. These can only be rolled from the chat, if you want to use the character sheet you need to use the "Damage Dice" formula button from the character, not the buttons from the item sheet.

Made armors equippable, and unequippable through their item macro! Much appreciation to u/probabilityunicorn for highlighting this flaw in the system, as well as other bugs early in development. A macro for shields was made and does work, but isn't implemented.

Added all of the treasure from the roll table! My suggestion is to have the players roll 1 or more d12, then change the roll table formula to their result and "roll" so they get to see their reward. Then add it to their sheet. High probability that I missed any of these treasure changes if they happened in v1.4.

Created a new "NPC Weapon Template" to make rolling and animating their attacks easier. Added an "Environment Template" but no environments.

Quickstart Adventure, Class Templates, Ranger Companion Template, and cards are not updated to the v1.4 version, I thought it was better to get this released (similar to what they did for v1.3!) This may come out in a later update, but more likely I will be shifting my focus to the small team of people actually working on a dedicated Daggerheart system for Foundry!

---Playtest v1.3 Updates!---

Advantage/Disadvantage: Updated the in-line roll on character sheets to be a d12 instead of a d6.

Damage Thresholds: Adjusted all class and Quickstart character damage thresholds.

Fear, Hope, and Stress Points: Maximum for these pools are set to 6/6/6.

Ancestry: Clank, Daemon, Drakona, Dwarf, Elf, Faerie, Faun, Galapa, Goblin, Human, Katari, Orc, and Ribbet updated.

Community: Highborne, Ridgeborne, Seaborne, Wanderborne, and Wildborne updated.

Class: Damage thresholds updated, and Subclass features removed. Rally, Unstoppable, Ranger's Focus, Hide, Prayer Dice, Channel Raw Power, Battle Strategist, and Combat Training (you need to manually add the damage) updated. Added Attack of Opportunity to Warrior class.

Subclass: All adjusted. Ranger companion sheet updated.

Domain: Bare Bones, Book of Ava, Book of Illiat, Book of Tyfar, Deft Maneuvers, Inspirational Words, I See It Coming, Nimble, Rain of Blades updated.

Gold: "Fortune" removed, "Coins" added, and all maximum values changed to 10 (the macro will roll them over when they go over 9.) THIS MACRO WAS A BEAR TO DEAL WITH!!! My world still has hoards.   

Equipment: All starting Armors and Weapons updated. Saber replaced with Cutlass. 

Tokens: All items on character sheets/templates were replaced with the latest version, and although the "Quickstart Adventure" was removed from the Playtest, it wasn't removed from my World! Adversary template, and adversaries updated.

Character Specific Items: I was previously handling effects like "Not Good Enough" by making new items and adjusting their macros. To future-proof this, such things will either need to be made on your side or done manually. You can ask me, or refer to old world versions to see how I did these.

Quickstart Adventure: Adversaries outside of this adventure were removed. I made my best guess for the quickstart adversaries, and I tried to update them to the new template.

To match Daggerheart's modus operandi I have made all Hit Points, Armor Slots, and Stress points start at zero. 

---Some known issues!---

Sometimes the in-line roller reads the character's trait (typically proficiency) as zero. The "Damage Dice" button still seems to work though. Your quickest solution is to move forward and just roll the dice from the dice tray when this happens. A long-term fix seems to be creating a new item, and then just copying everything over to it.

With a recent Forge/Foundry/System update a lot of my efforts broke, and I had to manually go through it all (even before 1.3 was released.) If you notice any of the item macros, or hotkey macros don't work then please let me know. This will be my last update release until v1.4 of the playtest! I will be tweaking it until the next release as these glitches and bugs arise.

v1.2 Update Notes:

Put character traits into a table, including a "Modified" section, and their typical functions.

Corrected some background and connection questions. Corrected some items. Updated to the latest version of Foundry and Simple Worldbuilding, then had to correct... everything!

Updated macro format to resist deprecation (basically ".data.data" was changed to ".system" and occasionally "actor" or "item" was changed to "actorizer" or "itemizer" to make macros work better.)

Created a new macro for most items, which includes animation and automatic rolling for many which compares the roll to the target's difficulty (or evasion, if they have one), detects criticall successes, spits out the item to the chat for easy damage and feature reference, and players can drag the macro from the item description into their hotkey bar. 

Updated the druid's "Beastform" to be a dialog box macro. This ONLY works from the macro, the item will put it into the chat. The beastforms are still their own items, after activating you will need to use the character sheet items. I have it set up so that when you click the macro it ends all beastforms, so if you want to end it then activate it and hit "cancel." No homebrew is without a little jank, I will try to fix this before update 1.5.

Finished the quickstart adventure maps, including modifications to the text to make it run more smoothly (IMHO) and suggestions if you don't want to use the pregenerated characters. I completed this in 150 minutes with four players, moving at a brisk pace, and with a five minute break after the treehouse but that was 1.2.  

Added the pregenerated character sheets, their token art, and their hands. 

Changed how player hands and vaults work, now the GM is responsible for dragging player cards to their vault from the relevant deck (which duplicates it) and then the player can draw the cards from their vault to their hand.

Added small descriptions to all of the starting items (if the description is empty my macro to display them in chat doesn't work.)

Added a rollable loot table. I did not create any of these item sheets, just made the loot table for random rewards. Just like with higher level play, you'll need to add these yourself or wait for a later update when I (might) add them.
