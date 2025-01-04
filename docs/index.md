# Welcome!
Welcome to the Audeal Wiki!

## What is Audeal?
Audeal is a simple header file wrapper for [miniaudio](https://miniaud.io), inteded for use in games or game engines.

## Audeal Example
```cpp
// ...
adl::Audio myAudio = adl::Audio(); // this is required to set up miniaudio.
adl::Sound mySound = adl::Sound(&myAudio.engine, "music.wav"); // init the sound
mySound.play(); // play the sound
// ...
```
