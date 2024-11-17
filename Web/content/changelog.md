---
title: "Mini Games Hub Changes"
---
# Mini Games Hub Changes
## New in version 0.0.4 (build 2024.11.17)
Please note that the Android version still cannot save data.
* This update Fixes a serious bug that the store item health drink is being incorrect. It's now changed to health potion, which is making wrong item. All health drinks that you have purchased will be transfered to health potion automatically. Thanks Jes Bel for report!
* Computer sequence in Blackjack will now more randomize and doesn't nearly always win or lose.
* Changes for Endless Battle mini game; These are changes that have been applied to Endless Battle mini game and thus it is best to group them into 1 for readability as many changes were made:
	* You can now select the map you want to play on. Of course, there is currently 1 map, but it will be expanded in the future.
	* Added items! Now, when an enemy dies, a random item will be spawned at its location which will be picked up if you're close enough with it.
	* Fixed inventory item speech on Android which causes the item to stop speaking. The positional speak of the inventory item has now been removed.
	* You can now rotate a full 180 degrees by pressing the S key. Android gesture not available.
* Improved in-game shortcuts announcement. At the start of Blackjack it will tell the shortcuts related to it depending on the platform you're on.
* Added test speaker in the main menu to test your speaker's position in realtime.
* Added the message that will speak upon the click of the "Check for Updates" icon.

## New in version 0.0.3 (build 2024.10.29)
* Changed the name to Mini Games Hub, and added a new mini game! Of course, new mini game suggestions are always welcome!
	* In this new mini game, you play blackjack. You can move up and down arrows to navigate through the game's structure. When you gained dollars, you can use them to buy health items, ammos, etc for Endless Battle mini game.
* Changes for Android; These are changes that have been applied to Android operating system as well as game UI related to it:
	* Upon opening the game on Android, it will play a sound file which suggests to turn off your screen reader and using a keyboard if possible. To skip the sound you can double tap with 1 finger on the screen.
	* Android platform can now select gender as the play game option is pressed.
	* You can now change settings on Android! Since forms aren't able to navigate on Android, a menu base system is added to it. Also note, to check or uncheck a checkbox in the menu, double tap with 2 fingers.
	* More Android gestures for Endless Battle: Swipe up with 3 fingers to check ammo, and swipe down with 3 fingers to check coordinates. Wo, near to 4 fingers!
	* Hopefully fixed screen reading problem on some Android devices by using an alternative screen reading method. Thanks several players for report!
	* Added Android number field. Uh, of course, this is simulation. Once the field is popped out you can click on the numbers you want to type, and click done button to finish. This is the only way that Android devices can type.
* Updates will now include about update build date. Eg build 2024.10.19.
* Added sounds for update available, started, and canceled.

## New in version 0.0.2 (build 2024.10.19)
* You can now press F1 on each store item to get its description.
* Fixed speech interrupting in menus, especially with Android having speech interrupt on. On Android if you want to force speech stop while you're in game play, triple tap with 1 finger.
* Fixed enemy death sound not playing in the correct listener.
* You can now click on "get system information" icon in the main menu to get information related to system, including its information and necessary debug logs. Only do this when it's necessary, for example if you asked a question related to device issue, so developer might need to ask you that information; only provide it when it is asked! The information you retrieved is encrypted, meaning only developers can extract its information, adding another possible security implementations to each information that you provide. This also means that even if the information is published publicly to the internet, no one will be able to access its original form.
* Decreased jump time a bit.
* Improved store related text strings.
* Information of the weapons have been removed from the weapon draw menu. Instead, you will have to press F1 to read the weapon's related information while you're at it.
* You can now rotate 90 degrees by pressing turn keys (Q and E) while holding down Shift. This 90 degrees rotation is not currently available by touch.
* In-game key shortcuts can now display base on the operating system!
* Added pluralization strings to items, for instance, store purchases.

## New in version 0.0.1 (build 2024.10.13)
* First release