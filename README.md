# Reset Plug-in Object Classes

Menu Command

## Version

1.1.2 - 08/10/2024

This plug-in is written in Vectorscript (Pascal) and can be used in any version of [Vectorworks](https://www.vectorworks.net) 2019 or newer.

## Description

Opens a dialog box allowing User to change all plug-in objects of matching types to a given class

## Instructions

1. Run menu command
2. Select desired Plug-in Object type to alter
3. Check **Change Class** checkbox
4. Select new **Class** from dropdown
5. If desired, check **Set Attributes By Class** checkbox to also set all attributes for affected PIO objects to be **By Class**
6. Press **OK** button to force desired Plug-in Objects to use newly chosen Classes

## Dialog Box Explanation

![Dialog Box Example](images/dialog-box-example.jpg)
1. Column listing all Plug-in Object (PIO) types found in the active drawing.
2. Column listing count of PIOs found in the active drawing.
3. Column listing the new Class chosen for the PIO.  PIOs with new Classes will be listed in <span style="color:red">Red</span>.
4. Column showing PIOs with **Set Attributes By Class** selected.
5. The currently selected PIO will by highlighted in the List Browser. Multiple PIOs may be selected at a time.
6. Checking the **Change Class** checkbox will set the PIO for Class replacement. Unchecking the box will clear the **New Class** and **By Class** columns for the selected PIOs.
7. Class drop-down menu. Use this to select the new Class for the selected PIOs.
8. Checking the **Set Attributes By Class** checkbox will set all Attributes for affected PIOs to be **By Class**.
9. Counter displaying number of affected objects in the active drawing.
10. **Help Box**, mousing over any dialog box element will display an explanation here.
11. Pressing the **OK** button will close the dialog box and change the Class of all PIOs with a chosen new Class.
12. Pressing the **Cancel** button will close the dialog box without affecting any PIOs.

## Installation Instructions

There are two methods of installation, direct download of the plug-in or through the **JNC Tools Free Manager** plug-in.

### Direct Download:

1. Download [source plug-in file](Reset%20Plug-in%20Obj%20Classes.vsm)
2. Place downloaded file inside the **Vectorworks User Folder** within the **Plug-ins** directory
3. Restart Vectorworks

### JNC Tools Free Manager

1. Run the [**JNC Tools Free Manager**](https://jncogs.github.io/JNC-Tools-Manager-Free/) menu command
2. Select the **Reset Plug-in Obj Classes** command
3. Press the **Install / Update** button
4. Press **Close** to close the dialog box
5. Restart Vectorworks

## Adding the Plug-in to your Workspace

1. Open the **Workspace Editor** by going to **Tools - Workspaces - Edit Current Workspace**
2. Select the **Menus** tab
3. In the box on the left, find and expand the **JNC** category
4. In the box on the right, find a suitable menu to place the command in, such as **Tools** or **Modify**
5. Click and drag the **Reset Plug-in Object Classes** command from the box on the left to the desired menu location in the box on the right
6. Click **OK** to close the editor

## Localization Instructions
The plug-in can be localized to your native language without having access to the source code.  This can be achieved by following the instructions below:

1. Open the **Plug-in Manager** by going to **Tools - Plug-ins - Plug-in Manager**
2. Select the **Third-party Plug-ins** tab
3. Select the **Reset Plug-in Obj Classes** command
4. Click the **Customize** button
5. Select the **Strings** tab
6. Double-click a category, such as **Dialog Strings**
7. Select a string to edit and press the **Edit** button
8. Write a new string and press the **OK** button until you are back to the **Plug-in Manager**

The categories for this plug-in are as follows:

- **3000** - *Dialog Strings*:  These strings are used in the dialog box and can all freely be changed
- **4000** - *Dialog Help Strings*:  These strings are used in the Help Box at the bottom of the dialog box and can all be freely changed
- **5000** - *Misc Strings*:  These strings serve  multiple purposes in the code, only string **5000** should be changed

## Release Notes

| Date | Version | Note |
| :---: | :---: | :--- |
| 12/07/2023 | 1.0.0 | Initial release |
| 12/08/2023 | 1.0.1 | Added ability to set objects By Class |
| 03/22/2024 | 1.1.1 | Fixed bug with Callout objects not taking By Class |
| 08/10/2024 | 1.1.2 | Fixed bug preventing User from unchecking Change Class checkbox |

## Known Bugs

No Known Bugs

## Feature Requests

No current Feature Requests


## License

Copyright (c) Jesse Cogswell (JNC Tools)

Permission is hereby granted, free of charge, to any person or organization
obtaining a copy of this software (the "User") and associated documentation files (the "Software"),
to use, reproduce, distribute, execute, and transmit the Software.

The User is not permitted to modify or attempt to reverse engineer the source code.  The User may
localize the Software using approved methods from within the Vectorworks software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
