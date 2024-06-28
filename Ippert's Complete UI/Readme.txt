Ippert's total UI version 1.5, inspired by eSanta.
EE version: https://steamcommunity.com/sharedfiles/filedetails/?id=1900866041
EE 1440p version : https://steamcommunity.com/sharedfiles/filedetails/?id=1936251924

******************************************

Hi there,

I have made an UI which is inspired by eSanta but tries to massively improve on it. It removes any useless/rarely used buttons and adds stuff which actually serves a purpose. 
The main feature of this UI is its multifunctionality, it can be used to play / observe live games / observe recorded games.

******************************************

Installation:

If you only plan on using this mod when playing via Voobly you can install the Voobly mod instead!
Voobly Mod: https://www.voobly.com/gamemods/mod/1378/Ippert-Complete-UI
Please read the tab "Installation Help" there too to learn how to enable/disable it.

!!!!!!!If you have already installed eSanta you can just put the new uimain.xmb into your data folder and delete the old one + the possible uimain.xml there!!!!!!! 

uimain.xmb [use the .xml for personal mod] (file in the data folder) goes into:
"...\Microsoft Games\Age of Mythology\data\"

The .ddt files in the textures\icons folder go into: 
"...\Microsoft Games\Age of Mythology\textures\icons"

The .ddt files in the texture\ui folder go into: 
"...\Microsoft Games\Age of Mythology\textures\ui"

If you've already installed eSanta but you care about AoM recorded games you should also insert the new .ddt file named "record game progress bar background" found in "textures\ui" into your corresponding folder.  
This will cause your progress bar to no longer glitch out but use the progress bar made for AoT.

******************************************

Uninstall: 

Delete all files you placed inside your folders.

******************************************

HOW TO USE THIS MOD:

The default state of the UI is always the playing state. The new buttons in the top right can be used to swap states. Swapping directly between REC and OBS mode is not possible, you must first go back to PLAY.

General changes:
- A lot of buttons around the minimap are gone since nobody ever used them and all of them can be hotkey'd or activated in another way in your game files. 
You can also hotkey camera reset and flare but people don't seem familiar with that so I left those 2 buttons.
Easymilitarydrag hotkey: map ("", "world", "configToggle(\"EasyDragMilitary\")").
Flashhitpointbarondamage: go to your user.cfg or create one in your startup folder and put this line in there: +flashhitpointbarsondamage
- You do no longer have the option to maximize the UI (pull all the art back up).
- The chat input box no longer overlaps the first 2 lines of chat so you can actually read what is being said there.
- The eSanta objectives button has been removed, the objectives menu can be pulled up by pressing F3 (default).

Playing state (PLAY) = default state
- You can no longer access the eSanta custom buttons in this mode since they're useless while playing and just take up space. 
- The AutoQueue button no longer overlaps with the waypoint button. 
- The panel left of the unit stat panel where you for example click to build a Villager can no longer be clicked through. So miss clicking will no longer result in you deselecting your current selection.

Observing live games (OBS)
- A lot of your UI elements are no longer visible since all those elements don't work/don't serve a purpose while observing (like control groups).
- eSanta's lighting modifier and screenshot buttons become visible.
- You get a button named GR which pulls up gather rates.
- Left of your minimap you can still see market trade rates.
- VOOBLY ONLY: Built in buttons to say !1/!2~~/!r/!t in allied chat to activate the map scripts and show resources / pop of the players / current techs being researched. 
These can be pulled up using the button right of the minimap. They will be displayed above the score and will have the same colour as the corresponding player.
They are hidden by default and each time you press the button 2 come up. Thus you can swap between 1v1 2v2 3v3 and 4v4 mode. 
Pressing the button when all 10 buttons are visible results into them becoming all hidden again, factually resetting the UI.

Observing recorded games (REC)
- The progress bar is hidden by default but you can switch it on with a new button. The "Loop" button is gone since it's so useless.
- In the top right you can see the idle Villagers / Fishing Ships / Caravans of the selected player.
- eSanta's lighting modifier, viewing angle modifier and screenshot buttons become visible.
- You get a button named GR which pulls up gather rates. And a button named GP which hides god powers and age text.
- VOOBLY: REC view does not have the observer buttons since they magically don't work while watching recorded games. 
Manually typing the commands in the chat still works though (only if there was an observer in the live game so you can swap to his perspective).

Reminder of functionalities people seem to forget have always been in eSanta:
- The top left buttons show idle houses and manors. But they're also clickable and actually do something. The top button will pull up the gather rates of the selected unit. 
The bottom button hides your age text and god powers but not your potential titan gate. This can be used to hide them when you're mythic and have used all god powers, so you can't accidently click on them.

Current gatherers on favor glitch:
This can sometimes glitch out and show: "villagers / monuments / heroes gathering / settlements" instead of numbers. 
This issue seems completely random and some people can have it glitched one game and fixed the other.
If you were playing norse and this glitch occured you couldn't clearly see your current favor since the "heroes gathering" text was so large. 
I have reduced the size of the textbox so it can no longer overlap with current favor and it will just say "heroes". 