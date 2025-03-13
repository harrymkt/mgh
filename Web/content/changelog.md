---
title: "Mini Games Hub Changes"
---
# Mini Games Hub Changes
## New in version 0.0.7 (build 2025.03.13)
- Added translation system! This is still in its early development, and all strings might not be available to translate. Translations live in the lang folder, with a subfolder with the language code prefix. To translate the program, copy the main fallback translation folder (en) with your own language prefix. After translations you may send to me.
- You can now copy menu items with Control+C, or triple tap with three fingers on Android.
- Introducing a new mini game (Archery)! This is a game where you will shoot a flying plane that is moving from side to side. This game fully supports Android gestures. Read more about the game in the documentation section on the website.
- Removed auto updating because it may cause some devices with slow internet so that they can't start the game. Updates are now require manual checks.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- Removed coordinate checking. You don't need it.
	- Fixed enemy detection to spawn.
	- XP for Bear is slightly increased, and all enemies have increased their health.
	- Introducing a new weapon (Axe)! This weapon is better than Sword as a melee weapon and is available for resurrection 2. This causes the Sword to shorten its range as the Axe takes place on it.
	- Introducing magic attacks! Press the M key, or double tap with one finger on the top right of the screen on Android, to bring up the magic spells which can be casted if you have enough magic energy. The magic energy can be gained as the enemies are killed, and will not reach over 100. Note that availability of magic spells is based on your resurrection, and in some case, level is also included.
	- Some weapons damage has been reduced.
	- Fixed the S key to turn a full 180 degrees.
	- You can now get coin as an item when you kill an enemy.
	- Hitting your target with weapon is now harder as you now need to exactly face in the direction. Better listen, use headphones.

## New in version 0.0.6 (build 2025.01.01)
First of all, **Happy new year!**
- Dice Match can now generate below 1 number, in which case you will lose dollar. This is completely randomized anyway. As such, you can now press faster.
	- Dice Match now has buffer support. Note this is only for non Android users.
- The game will now auto check for updates at startup. You can turn it off in the settings if you want to, but it is recommended to keep it on, as that option can be removed in the future if needed.
- Added a checkbox in the settings to control whether item loop sounds are played. Thanks "Way Yan Soe" for his suggestion!
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- Enemies can now spawn base on your map and the number of your resurrection. This means that bigger and bigger enemies will you likely to find as your resurrection goes higher. This acts just like a starting point for an expansive map system that will be available in the near future.
	- Introducing a new enemy or animal (Lion)! Watch out! This animal is big, and take a lot of damage than previous enemies, with the approximate estimation that you will be killed is two hits. Don't worry newbies, you will only find them at resurrection 4 or above. Suggestion? Well, stay away from them, and shoot from a greater distance. They also have a slight higher range than Bears, which is another thing to care of.
	- The game now speaks who kills you as soon as you die.
	- Fixed bullet shoot range.

## New in version 0.0.5 (build 2024.12.08)
- Fixed the download URL for update.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- Items in the map will now play a loop sound which will indicate where they are.
	- Added a new weapon (Knife)! This is small and lightweight, doing only a small amount of damage though it is faster than the Sword. You should get this weapon when your resurrection is 1 or above. Now, the Sword range is increased while the Knife has a shorter range.
	- Added a new enemy (Bear!) Be careful, it does a little higher amount of damage than Wolf.
	- Require experience point will now randomize.
	- You can now customize the spawn time of enemy and it is set to 10 seconds by default.
- Added buffer! This means that you can review informations that you've missed. For example, alerts and in-game important notifications. You can press left and right brackets to switch between buffers (holding down Shift will move to top or bottom), and you can press the Comma key or Period key to move through the current buffer (holding down Shift will move to top or bottom). Android gestures not supported.
- Introducing a new mini-game: Dice Match! The objective is to roll the dice, which contain two numbers, each ranging from 1 to 6. If the two numbers match, you'll earn money equal to 0 to 20 times their total. There you go, Android gamers, because this mini game fully supports gestures and thus keyboard is not required!

## New in version 0.0.4 (build 2024.11.17)
Please note that the Android version still cannot save data.
- This update Fixes a serious bug that the store item health drink is being incorrect. It's now changed to health potion, which is making wrong item. All health drinks that you have purchased will be transfered to health potion automatically. Thanks "Jes Bel" for report!
- Computer sequence in Blackjack will now more randomize and doesn't nearly always win or lose.
- Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	- You can now select the map you want to play on. Of course, there is currently 1 map, but it will be expanded in the future.
	- Added items! Now, when an enemy dies, a random item will be spawned at its location which will be picked up if you're close enough with it.
	- Fixed inventory item speech on Android which causes the item to stop speaking. The positional speak of the inventory item has now been removed.
	- You can now rotate a full 180 degrees by pressing the S key. Android gesture not available.
- Improved in-game shortcuts announcement. At the start of Blackjack it will tell the shortcuts related to it depending on the platform you're on.
- Added test speaker in the main menu to test your speaker's position in realtime.
- Added the message that will speak upon the click of the "Check for Updates" icon.

## New in version 0.0.3 (build 2024.10.29)
- Changed the name to Mini Games Hub, and added a new mini game! Of course, new mini game suggestions are always welcome!
	- In this new mini game, you play blackjack. You can move up and down arrows to navigate through the game's structure. When you gained dollars, you can use them to buy health items, ammos, etc for Endless Battle mini game.
- Changes for Android; These are changes that have been applied to Android operating system as well as game UI related to it:
	- Upon opening the game on Android, it will play a sound file which suggests to turn off your screen reader and using a keyboard if possible. To skip the sound you can double tap with 1 finger on the screen.
	- Android platform can now select gender as the play game option is pressed.
	- You can now change settings on Android! Since forms aren't able to navigate on Android, a menu base system is added to it. Also note, to check or uncheck a checkbox in the menu, double tap with 2 fingers.
	- More Android gestures for Endless Battle: Swipe up with 3 fingers to check ammo, and swipe down with 3 fingers to check coordinates. Wo, near to 4 fingers!
	- Hopefully fixed screen reading problem on some Android devices by using an alternative screen reading method. Thanks several players for report!
	- Added Android number field. Uh, of course, this is simulation. Once the field is popped out you can click on the numbers you want to type, and click done button to finish. This is the only way that Android devices can type.
- Updates will now include about update build date. Eg build 2024.10.19.
- Added sounds for update available, started, and canceled.

## New in version 0.0.2 (build 2024.10.19)
- You can now press F1 on each store item to get its description.
- Fixed speech interrupting in menus, especially with Android having speech interrupt on. On Android if you want to force speech stop while you're in game play, triple tap with 1 finger.
- Fixed enemy death sound not playing in the correct listener.
- You can now click on "get system information" icon in the main menu to get information related to system, including its information and necessary debug logs. Only do this when it's necessary, for example if you asked a question related to device issue, so developer might need to ask you that information; only provide it when it is asked! The information you retrieved is encrypted, meaning only developers can extract its information, adding another possible security implementations to each information that you provide. This also means that even if the information is published publicly to the internet, no one will be able to access its original form.
- Decreased jump time a bit.
- Improved store related text strings.
- Information of the weapons have been removed from the weapon draw menu. Instead, you will have to press F1 to read the weapon's related information while you're at it.
- You can now rotate 90 degrees by pressing turn keys (Q and E) while holding down Shift. This 90 degrees rotation is not currently available by touch.
- In-game key shortcuts can now display base on the operating system!
- Added pluralization strings to items, for instance, store purchases.

## New in version 0.0.1 (build 2024.10.13)
- First release