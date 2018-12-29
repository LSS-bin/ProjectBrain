----------------------------------------------
       Future Cartographer Audio Tools FE
 Copyright (C) 2015,2016 Future Cartographer
               Version 2.2.1
      http://www.futurecartographer.com/
        support@futurecartographer.com
----------------------------------------------

Hi there, thank you for using FC Audio Tools!

Documentation can be found here: http://www.futurecartographer.com/fcaudiotools-documents

If you have any questions, suggestions, comments or feature requests, please
drop by the FC Audio Tools forum, found here: http://forum.unity3d.com/threads/fc-audio-tools.342001/

If you like this package, please give it a review/rating in the AssetStore
as it will help me to improve the tools.


-----------
Wave Editor
-----------
Wave Editor provides the raw level editing of audio files to you.
You can edit such as cut/copy/paste.

If from your sound assets want to cut the silence part, you can use this.
If the volume of the sound assets who you want to use is not match, you can use this.
If you want to embed a loop point in your assets, you can use this.

To try it out.
1) Show WaveEditor tab. (Choose menu Window -> FCAudioTools -> Wave Editor)
2) Drop file to edit from project tab to the Wave Editor window.
3) Use the WaveEditor to the editing of the waveform.
4) Choose to save (overwrite or new file).


--------------
Level Adjuster
--------------
Are you troubled by the sound effects and music volume is incorrect?
Sound experts in your team, might have a different work.
Do not worry even in such a case. To drop the file you want to edit to Level Adjuster window.
And, while listening to each sound, moving the volume bar.
The sound is immediately able to preview.
I believe that it is difficult to adjust to listen?
The tool adds RMS-based analysis capabilities.

To try it out.
1) Show WaveEditor tab. (Choose menu Window -> FCAudioTools -> Level Adjuster)
2) Drop files to adjust from project tab to the Level Adjuster window.
3) Change sound level by the slider or using analyze.
4) Choose to save (all overwrite).


------------
Why tool"s"?
------------
I have plans to offer you the other tools in the future.
All of these will be included to the package of FC Audio Tools.
It will work on Windows, Mac OS X and Linux.

However, the FC Audio Tools is not a tool for the only sound professionals.
Developer beginners and hobbyist is, is to provide a package that can be safely processing the audio.
So, if there is that you are in trouble in the sound, please tell me whether it to me.


------------
Contact info
------------
For bugs, feature requests and a friendly chat, you can send an email to:
support@futurecartographer.com
http://www.futurecartographer.com/aboutme

I will always answer as soon as possible but please keep in mind that I am just one guy with a normal day job.


---------------------
Unity's version issue
---------------------

5.2.0 - 5.3.2
The crash problem of the editor by playback and script compile was fixed in Unity5.3.2p4.
FC Audio Tools does not recommend the use between Unity5.2.0 and 5.3.2.
Please use Unity5.3.3 or later. 

5.1.x
You will see that the undo histories remains after close the window.
This is because undoClear has a problem on 5.1.x.
You do not encount this problem on 5.2.0 or later.


---------------
Asset Uninstall
---------------
If you want to uninstall the FCAudioTools, please delete the 'Assets/FCAudioTools' directory.


-----------------
 Version History
-----------------

2.2.1

General
- FIX: GUI skins appearance in Unity5.6
- FIX: Compile error of sample scripts in Unity5.6
- FIX: Console warning message in Unity5.5 and Unity5.6


2.2.0

General
- FIX: Console warning message in Unity5.5

Wave Editor
- IMP: When click on the marker label, the name change dialog is displayed.
- IMP: Change mouse cursor on SampleLoop, Marker's label and message.


2.1.0
General
- NEW: Support editing undo/redo
- CHG: All settings move to Preferences. (Choose menu Edit -> Preferences -> FC Audio Tools)
- ADD: Open facebook page.

Level Adjuster
- FIX: Shared audioclip between Level Adjuser and Wave Editor


2.0.1
- NEW: First release


