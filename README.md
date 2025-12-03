# TeasingGame
TeasingGame is a program that plays a script created with TeasingGame Maker. TeasingGame Maker is not a malware or any harm to your computer.

The script can include such actions as displaying a window with a picture and text, changing the desktop wallpaper, opening a browser with a specific link, and other actions.

TeasingGame's actions are completely dependent on the script. Therefore, it may harm your computer in some way.

# Changes in 0.1.1

1. I changed a lot of things in the user interface, so there should be no problems with its display.

2. Also, previously created event parameters are not cleared after opening another tab.

I also posted the program code. Some antiviruses detect viruses in them, but this is a false positive.

# How to download

Method 1. Code (green button) - Download ZIP.

Method 2. On the right side of the site, find Releases - Find the required version of the program.

# How to use

1. Start TeasingGame Maker, enter the following parameters: Name program (window title), Size window, Name folder (the name of the folder where the files will be stored), Main window visible, Icon. After that, click Create.

2. Next, we need to define what a scene and an event are. An event is an action that occurs in sequence according to a list. The scene is a storage of events. To add an event to a scene, you need to select the desired scene in the list, choose the desired event and click the Create button.
By default, the script starts with the first scene. After all events on the scene are finished, the events on the next scene immediately begin to happen. But if there is a Caption event on the scene, then the scene will switch only when you click on the window, even if all events have already taken place on this scene.
More details about all events below.

3. After you have created what you wanted, close the program. An Export folder will appear next to it. The created scripts will be located there. The script itself consists of a folder with files and an info.json file. You need to move TeaseGame.exe here. When you launch it, the created script will start playing. TeaseGame.exe can be renamed to anything you like.

# Available events

1. Caption - Moves the text and image that were specified to the window (all Caption elements are optional, so the window can be empty if desired).

2. MessageBox - Window with text. Stops the program. After pressing the button, the program continues to work.

3. Visible window - Enable or disable visibility of the main window.

4. Change wallpaper.

5. Open link.

6. Time delay - During the time delay the program stops working, clicking on the window does not work.

7. Next scene - Go to the next scene. Mainly used with Caption and if you want to go to the next scene without clicking on the window.

8. Change size window.

# List of functionality that may be added (it may change)

In the first place:

1. Ability to open and edit an already created script.
2. Ability to change created events.
3. Ability to change the sequence of events.
4. Ability to copy event parameters to paste into a new one.

In the second place:
1. Caption optimization.
2. Event: download file.
3. Event: File Launch.
4. Event: Password entry window.
5. Event: Play sound.
6. Ability to create Caption with links to pictures.
7. Event branching.
8. Event: event back (creating something like a loop).
9. Improving the UI appearance.
10. Create a safe TeasingGame that alerts you to all events in the script.

In the third place:
1. Event: Create folder/file.
2. Event: Lock/unlock wallpaper.
3. Event: Disable/enable mouse/keyboard.
4. Event: Disable/enable task manager.
5. Event: Registry Change.
6. Event: Request for admin rights.
7. Event: Adding a program to startup.
8. Event: Windows theme change.
9. Ability to add video to Caption.
10. Event: Encrypt/decrypt file.
11. Event: Popups.
12. Event: Shutdown/restart your computer.

The program update activity depends on my workload and how popular the program will be. Or in the number of donations to me.

You can also write to me what features you want.

# Create a caption event example
![Add caption event picture](https://github.com/anutays/TeasingGame/blob/main/Create%20a%20caption%20event.PNG?raw=true)

# Distribution

When playing the script, there will be no mention of the author (me). Perhaps in the future I will fix this. So if you want to upload the script somewhere and distribute it, you can mention me. But this is not necessary.

# Known issues

# Other

My Twitter: x.com/Anutasissy

If you find any bugs, you can write to me here or in the Issues tab.

If you want to combine the script and the program, then see Single file Guide.txt, which is located here.

# Donate

Telegram bot: https://t.me/tribute/app?startapp=dmM2
