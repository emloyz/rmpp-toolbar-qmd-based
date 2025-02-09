# repo of xovi extensions

> [!WARNING]  
> `toolbar.qmd` and `Gesture.qmd` is currently broken due to a qmldiff hash issue. For now, they are both unusable. The other mods work fine.
> Use `Gesture-temp-fix.qmd` and `toolbar-temp-fix.qmd` for now. 

This Repo consists of multiple Xovi(.qmd) extensions that are QoL improvements to the xochitl interface. This **needs** qt-resource-rebuilder.so to work.

Download the extensions from the corresponding folders to avoid issues. 

Instructions to install xovi can be found in [here](https://github.com/asivery/rmpp-xovi-extensions/blob/master/INSTALL.MD). 

The QMD files in this repo add a quicktools-like floating bar, and a layer management bar. Instructions to install xovi can be found in [here](https://github.com/asivery/rmpp-xovi-extensions/blob/master/INSTALL.MD). 

After which, copy the files to `/home/root/xovi/exthome/qt-resource-rebuilder/` and restart xovi. 

These QMDs were tested to work in 3.15/16 and 3.17. Any bugs should be reported in the repo issues. 


## Extensions

### 1. Edit.qmd
- Adds the ability to delete a stroke once selected by the selection tool.
  
![image](images/DelStroke.png)

### 2. favTagButton.qmd
- Adds 2 extra buttons to the search/new note floating button on the file explorer that lets you
open the favourites and tagged view with a click.

![image](images/favTagButton.png)

### 3. Gesture.qmd
- Adds a couple of gestures that are nice-to-have(Note: These have only been tested on right-handed mode. So left-handed mode would behave slightly differently)
1. Swipe on left edge of the page to open/close the toolbar(Swipe towards the edge to close it, swipe from the edge to open it)
2. While in fullscreen, swipe down from the toolbar icon to swap between the primary and secondary tool
3. Swipe with two-fingers from the left half of the bottom-edge to swap between eraser and pen
4. Swipe with two-fingers from the right half of the bottom-edge to swap between selection tool and pen
5. 4-Finger tap to open the document drawer

![image](images/Gestures.png)

### 4. recentsTag.qmd
- Adds a new menu to the document drawer that shows only tagged files, sort by last modified

![image](images/RecentsTag.png)

### 5. selectionBoth.qmd
- Adds the ability to select everything above the line

![image](images/selBoth.png)

### 6. toolbar.qmd
- Allows adding any tool with a preset colour and thickness
- Allows changing the added tool order
- Can be placed anywhere in the screen
- Can be minimised when not in use
- Snaps to the edges and horizontal/vertical center of the screen when moved
- Config persists between restarts(Enabled state, position, tools list)
- 3 Presets of tools to change to
- Floating Layers menu fully replaces system equivalent except for renaming the layer
- (New) Changes to a vertical bar when moved to the left/right edge of the screen

NOTE: the last couple of lines are commented with a ;. This adds an X button to the toolbar to close the document.

#### Moving the toolbars
##### Press and hold the left-most icon until it's highlighted. After which, press and drag the icon to move it around

#### To change tool order
To change the tool order, press and hold on any tool button(s) to show the arrows, and change the order using them.
Note: The arrows won't show up unless you have the base toolbar open.

#### To Minimize
Double tap the top-left icon


![image](images/menu.png)

*Menu*

![image](images/layer.png)

*Layer menu*

![image](images/toolbarHor.png)

*Toolbar Default*

![image](images/toolbarHorMove.png)

*Toolbar tool order change*

![image](images/toolbarHorFS.png)

*Toolbar while in fullscreen*

![image](images/toolbarVer.png)

*Toolbar when near the side edges*

![image](images/toolbarVerMove.png)

*Change Order Buttons*

![image](images/toolbarVerFS.png)

*fullscreen*

![image](images/min.png)

*Minimized*
