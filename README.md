# WhiteHeadIsland

This is Larvy's dumb ass map. Don't grief it and mess things up!

# Setup
0. Create a github account
1. Install the following programs:
  * [VSCode](https://code.visualstudio.com/docs/?dv=win64user)
  * [Git](https://git-scm.com/downloads/win)

2. Once they are both installed open VSCode and select Terminal>New Terminal
3. Setup your git credentials using
```
git config --global user.email "your@email.com"
git config --global user.name "Your Name"  
```
4. Create a new empty folder in your \Documents\My Games\ArmaReforgerWorkbench\addons
5. In VSCode and open that folder via File>Open Folder
6. In the Terminal, Clone the repo using ```git clone https://github.com/HeroicLarvy/WhiteHeadIsland.git```

# Workflow
1. Before starting work, open VSCode.
2. Open the folder of the repo if it is not already selected, via File>Open Folder
3. Open a terminal if one is not already open, via Terminal>New Terminal
4. Ensure your current working directory in the terminal matches the directory you cloned
   4.1 Use ```cd``` to change directories, use ```ls``` to see what folders are in your current directory.
5. Run ```git pull```
6. Do your work on Reforger tools 

Refer to the World Editor section before the next step if you are new

6. When finished, save and close ArmaReforger tools 
7. Open VSCode and within the terminal, enter the following commands
```
git add Path\ToYour\.LayerFileHere
git commit -m "Message containing what you did"
git push origin main
```

Always run ```git pull``` before starting any work to ensure you have the latest changes.

# World Editor
1. To get started, open Reforger tools and hit +Add Project and scan for projects
2. Double click project to open it
3. In the Enfusion Workbench, find the globe in the bottom left corner "thingnamehere.ent" and double click it
4. Once your World Editor loads, on the left within the Hierarchy, you will see a list of layers, right click and lock all of the layers that aren't yours
5. Right click and unlock your layer, then right click and set it as active
6. To place an object, look through your Resource Browser on the bottom center of your screen
7. Example object placement: go to ArmaReforger>Prefabs>Structures>Houses>Tiwb>House_Town_E_2I01
8. Drag the house to where you want to place it
9. Press W to switch to move mode, and drag the arrows on the object to move it
10. Press E to switch to rotate mode, drag the wedges around to rotate the object
11. To generate something, press V or select the vector tool on the top bar
12. Click the Vector Tool in the bottom right
13. For areas select New Polyline, for roads/bushlines select New Spline
14. Click on the ground where you want your line to start, hold ctrl and click to place another point
15. In Resource Browser naviigate to ArmaReforger>PrefabLibrary>Generators
16. Drag your desired Generator to your selected ShapeEntity inside your Hierarchy on the left

A video guide on the basics of World Editor tools: https://youtu.be/qhxZ-R805ts
