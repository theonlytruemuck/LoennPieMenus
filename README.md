# LoennPieMenus
This plugin for the celeste mapping tool Lönn brings over the infamously useful pie menus from blender to Lönn.

TLDR:
tab: tool selection
tab+lctrl: layer selection
tab+lshift: mode selection
tab+lctrl+lshift: material selection


you can press tab at any time and as long as you hold it, a pie menu for your tools will be present.
to confirm an entry, move your mouse in its direction and once it lights up blue you can just release tab and it will be selected.
if you move your mouse to the middle of the menu and release tab, the previously selcted option will be choosen.

if you just use tab the tool selection will be opened
this includes built in tools like Brush, Placement or selection, as well as modded tools such as another lönn plugins teleporter tool.

if you hold left ctrl while starting to press tab you will open the layer selection
the layer selection includes options like foreground and background tiles for Brush like tools,
or entities, triggers, decals for placement/selection tools

if you hold left shift while starting to press tab you will open the mode menu
this features things like line/fill for the Rectangle tool
or place/select for the room tool.

if you hold left shift and left ctrl while starting to press tab you will open the material menu
this includes tilesets for the brush likes
or entities/triggers/decals for the placment tool

if any menu is opened you will get a age counter in the middle.
you can scroll through the pages as long as you hold tab

if you go to Mods/LoennPieMenus101/Loenn/consts/settings.lua
you can find options to change font size padding, and CUSTOM HOTKEYS
as well as how many entries should be in each ring, and how many rings there should be on any page

This tool is still in development, please reprt any bugs or crashes you find. please add the crash report.


--completed:
	removal of any overlaps
	ring and page splitting

-- partially implemented:
	custom hotkey settings

--TODO:
	options to disable ring/page partition for individual tools
	searching for any menu longer than one page.
	lots of cleanup. the current codebase is abysmal.
	minifying. ugh i hate when code is readable and also like a bajillion gigabytes big.
