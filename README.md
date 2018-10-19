# DynamiQ: Intelligent Frequency-Aware Volume Boost

DynamiQ is an open-source and modular package of scripts that allow you to boost the volume of the audio from your Windows device.

How to Install:

1. Make sure [Equalizer APO](https://sourceforge.net/projects/equalizerapo/ "Equalizer APO") is installed and working.
2. Download [APOpreamp](https://github.com/Brad331/APOpreamp.ahk/releases "APOpreamp") and put it in *%Username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup* so that it automatically starts at login.
3. Download [DynamiQ](https://github.com/Brad331/DynamiQ/archive/master.zip "DynamiQ") and extract its contents into *%ProgramFiles%\EqualizerAPO\config\DynamiQ* (make this folder if needed).
4. Include *...\DynamiQ\DynamiQ.txt* in your Equalizer APO config file, after any EQ you have for your speakers.

![alt text](https://bradshacks.com/wp-content/uploads/2018/10/Include-DynamiQ.png)

DynamiQ makes use of [ReaComp](https://www.reaper.fm/reaplugs/ "ReaComp"), a VST plugin by Cockos.
