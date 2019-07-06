You download this file from CNCDEN.com

Special thanks to Dave at DCOM Productions for his help.  -  http://www.dcomproductions.net



This script will give your map an introduction on the screen at the beginning, much like the scrolling intro script for Generals did. Just one little file to edit and your all set to go.


First, open up the map.str file in a text editor like notepad. You'll see the following:

MapIntro:01
"Text 1"
End

MapIntro:02
"Text 2"
End

MapIntro:03
"Text 3"
End

Where it says "Text 1", replace those words with whatever you want to introduce your map. For example, put in your map name. Leave the quotations in place. Do the same for "Text 2" and "Text 3". You can have your map name, who it was made by, and whatever you want for the third text...for me, I just put in "Enjoy the Map!"

Now save the file and place that map.str file inside your map folder with all the other files. That part is done.

Next fire up the World Builder Editor. You'll have to import the 'IntroScript.scb' file into the map you want your introduction to show up on. It's very simple to do. At the top menu you'll see 'Edit'. Click on that, then scroll down to 'Scripts' and click on that. This opens up the scripting section of World Builder. Click on the 'PlyrCivilian' folder. Now in the left menu near the bottom you'll see a button that says 'Import Scripts'. Click on that and then go to where you have your 'IntroScript.scb' file. I usually just place it on the desktop so I can find it easily. Choose the 'IntroScript.scb' file for importing, then click ok. You have now imported that file into the 'PlyrCivilian' folder. That's all you need to do. 

Just fire up your game, and you should see your intro text show up on the screen.