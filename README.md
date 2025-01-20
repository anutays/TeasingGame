# TeasingGame
TeasingGame is a program that plays a script created with TeasingGame Maker. TeasingGame Maker is not a malware or any harm to your computer.

The script can include such actions as displaying a window with a picture and text, changing the desktop wallpaper, opening a browser with a specific link, and other actions.

TeasingGame's actions are completely dependent on the script. Therefore, it may harm your computer in some way.

---The program is still under development.---

# How to use

1. Start TeasingGame Maker, enter the following parameters: Name program (window title), Author (displayed when the script is run), Size window, Show info (Show initial window when script starts), Name folder (the name of the folder where the files will be stored), Main window opacity, Icon. After that, click Create.

2. Next, we need to define what a scene and an event are. An event is an action that occurs in sequence according to a list. The scene is a storage of events. To add an event to a scene, you need to select the desired scene in the list, choose the desired event and click the Create button.
By default, the script starts with the first scene. After all events on the scene are finished, the events on the next scene immediately begin to happen. But if there is a Caption event on the scene, then the scene will switch only when you click on the window, even if all events have already taken place on this scene.
More details about all events below.

3. After you have created what you wanted, close the program. An Export folder will appear next to it. The created scripts will be located there. The script itself consists of a folder with files and an info.json file. You need to move TeaseGame.exe here. When you launch it, the created script will start playing. TeaseGame.exe can be renamed to anything you like.

# Available events

1. Caption - Moves the text and image that were specified to the window (all Caption elements are optional, so the window can be empty if desired).

2. MessageBox - Window with text. Stops the program. After pressing the button, the program continues to work.

3. Change opacity - Changes the opacity of the window. If it is 0%, the icon will disappear from the taskbar.

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
1. Event: download file.
2. Event: File Launch.
3. Event: Password entry window.
4. Event: Play sound.
5. Ability to create Caption with links to pictures.
6. Event branching.

In the third place:
1. Event: Create folder/file.
2. Event: Registry Change.
3. Event: Request for admin rights.
4. Event. Adding a program to startup.
5. Event. Windows theme change.
6. Ability to add video to Caption.
7. Event: Popups.

The program update activity depends on my workload and how popular the program will be. Or in the number of donations to me.

You can also write to me what features you want.

# Distribution

When playing the script, there will be no mention of the author (me). Perhaps in the future I will fix this. So if you want to upload the script somewhere and distribute it, I want you to somehow mention how it was created. But this is not necessary.
