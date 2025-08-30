# Aliens versus Predator 2 Auto Launcher (No CD required)
This batch script will launch your AvP 2 game without the CD at all.

Put the .bat file(s) in your main AvP 2 directory, which is where the game is fully installed.
You will be able to launch the game without having the CD inserted afterwards.

Video instructions: https://youtu.be/6lGqZdoByNU

**This assumes that you have the game installed correctly!** So, before proceeding ensure you have the game installed correctly and it runs without a problem.

There are 2 batch files in this repo.
1. [Regular Launcher - AvP2Launch.bat](AvP2Launch.bat) This is the default batch file that you can use to launch your game.
2. [Widescreen Launcher - AvP2LaunchWideScreen.bat](AvP2LaunchWideScreen.bat) This is an optional batch file that launches the game at forced 1920 x 1080 resolution. 

These batch files do not modify your original game or add additional features. The Widescreen launcher simply launches the game in 'forced resolution widescreen'. 

You can also use these batch scripts, make copies of them and have a batch script that you can use to launch a specific mod or skins folder as you would simply need to write the parameters you use to load the mod in the game launcher appended at the end of your batch file.

### File avp2cmds.txt explained
This file tells LithTech.exe where and what game file assets to load. This file is typically created when AvP2 is successfully installed or after the AvP2 game launcher is started. A basic avp2cmds.txt is provided [here](avp2cmds.txt). You shouldn't need it unless you don't have an avp2cmds.txt in your game directory.
This file will also set some cvars based on your selections in the options menu of the AvP2 game launcher e.g. Disable Sound, Disable Music. This depends entirely on the selections you made in the launcher.

### Attention - Optional Widescreen launcher explained
Old lithtech games, like Aliens vs. Predator 2, were built and shipped supporting 4:3 aspect ratio screens that were typical at the time. You're probably already familiar with there being a lack of Widescreen resolutions like 1920 x 1080 in the graphics settings of these old LithTech games like AvP2. **However, old LithTech games can be forced** to render the game at resolutions that your GPU and monitor supports.
That is what AvP2LaunchWideScreen.bat does. You can inspect the contents of the batch file youself and see how it is setting 4 cvars to use the 1920 x 1080 resolution.
This isn't 100% widescreen support though as there are a couple of minor issues that become more apparent at larger resolutions. The game may render and it looks fine; however, the field of view, menu text, and UI scaling were not designed for the widescreen aspect ratio and the larger screen resolutions.

The widescreen batch file provided enables 'forced resolution widescreen'. If you launch in game and you do not like it, you can go to the game options menu and change the resolution back to one of the standard ones that the game supports -- this action effectively resets those cvars. 

For better higher resolution support and true widescreen, seek the community **'Master Server Patch version 2.4 and higher'**. This game mod implemented widescreen support and added it as an option in the game's graphics setting options. This is a community game mod that would need to be installed on your computer, but, it brings the best quality of life improvements to the game for modern machines in addition to re-enabling online multiplayer.
