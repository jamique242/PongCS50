# PongCS50
Pong Game - programmed using love 2D

This project was created to meet requirements for a gaming class where we programmed using love/.lua . Love is an open source framework you can use to create 2D games. In order to compile the main.lua file you must first download the LOVE application. 

The version of LOVE being used is 0.10.2: 
MacOS - https://love2d.org/forums/viewtopic.php?f=4&t=86718
Windows 64 bit - https://bitbucket.org/rude/love/downloads/love-0.10.2-win64.zip

Windows - the easiest way to run the game is to drag the folder onto either love.exe or a shortcut to love.exe. Remember to drag the folder containing main.lua, and not main.lua itself.You can also launch the game from the command line:
"C:\Program Files\LOVE\love.exe" "C:\games\mygame"
or
"C:\Program Files\LOVE\love.exe" "C:\games\packagedgame.love"

Mac OS X -
On Mac OS X, a folder or .love file can be dropped onto the love application bundle. On the Mac Terminal (command line), you can use love like this (assuming it's installed to the Applications directory):
open -n -a love "~/path/to/mygame"
However, the above method will not output printed text to the terminal window. To do that, you will need to execute the love binary inside the application bundle directly:
/Applications/love.app/Contents/MacOS/love ~/path/to/mygame

for more information/help visit: https://love2d.org/wiki/Getting_Started
