# DynamiQ: Intelligent Frequency-Aware Volume Boost

DynamiQ is an open-source and modular package of scripts that allow you to boost the volume of the audio from your Windows device. It enables you to use aggressive equalizer settings without sacrificing maximum attainable volume.

Binaural demo on MateBook X Pro: https://www.youtube.com/watch?v=o5kS3qjtLgI

### Use Cases:
DynamiQ is the best way to get much better sound from your laptop's speakers or other small speakers. Set an equalizer to correct the frequency response and put DynamiQ after it. You will get your desired frequency response yet be able to reach very high volumes when you turn it up.

### How It Works:

When more power output is demanded than possible, DynamiQ levels the bass on demand to free up just enough headroom to avoid clipping. The amount of bass attenuation varies with the loudness of the audio in real-time. This way, you're gauranteed the volume level you set but also the most ideal frequency response possible at that volume level.

### How to Install:

1. Make sure [Equalizer APO](https://sourceforge.net/projects/equalizerapo/ "Equalizer APO") is installed and working.
2. Make a folder called **DynamiQ** in **%ProgramFiles%\EqualizerAPO\config**. (Make sure it's NOT called 'DynamiQ-master'.)
3. [Download DynamiQ](https://github.com/Brad331/DynamiQ/archive/master.zip "DynamiQ") and extract its contents into that folder.
4. Include **DynamiQ\DynamiQ.txt** in your Equalizer APO config file, after any EQ you have for your speakers.
![alt text](https://github.com/Brad331/DynamiQ/raw/master/Include%20DynamiQ.png)
5. [Download APOpreamp](https://github.com/Brad331/APOpreamp.ahk/releases "APOpreamp") and put it in **%appdata%\Microsoft\Windows\Start Menu\Programs\Startup** so that it automatically starts at login.
6. Run APOpreamp.exe.


### How to Use:

Once your Windows volume is maxed out, keep pressing the volume up button on your keyboard to boost the gain.

### FAQ:
Q: Windows volume 100 is now much quieter and I have to use the Gain. Is that normal?

A: Yes, DynamiQ is designed to take advantage of the full amplifier headroom provided when the system volume is maximized. The Gain should give you back as much volume as before, if not more.

Q: Should I turn off DynamiQ when using headphones?

A: Yes, DynamiQ is not for headphones, so you should turn it off.

### Customization:
You can use Equalizer APO's Editor.exe to change the bass crossover frequency in BassComp.txt. I have it set at 120Hz, which is the point  in my equalizer setting below which bass starts to go up dramatically.

Feel free to experiment and modify any part of DynamiQ. Maybe you'll discover something new and even better! Just be careful not to blow your speakers. The first compressor in BassComp.txt is for speaker protection.


DynamiQ makes use of and includes a copy of [ReaComp](https://www.reaper.fm/reaplugs/ "ReaComp"), a VST plugin by Cockos.
