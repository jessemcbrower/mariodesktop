# How to set icon images

1. Open an image in the icons folder. Press Command-A to select the full image, and then Command-C to copy it to your clipboard.

2. Select the icon you wish you change, and press Command-I to Get Info.

3. Click on the icon itself in this window so it's highlighted, then press Command-V to paste your new icon image.

4. For aliases, change the original first and then create a new alias; you'll need to do this for trash.

# Adding Trash to your desktop

1. In Finder, press Shift-Command-G and enter:

~/.Trash

2. Press command-I to Get Info, and replace the icon as desired.
 Then, open a terminal and type the following command exactly as written:

ln -s ~/.Trash ~/Desktop/Trash

# My theme

Mario: Macintosh HD, renamed to a single space character

? and Brick Boxes: Folders

Coins: Files

Mushroom: vmware shortcut / Windows 10

Goomba: A shortcut to ~/.Trash

# Things I want to do:

1. Add a top bar

2. Use the countdown as a clock

3. Use the coin count to reflect file count