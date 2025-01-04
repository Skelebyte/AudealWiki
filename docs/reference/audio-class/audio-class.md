# `adl::Audio`
`adl::Audio` is the class that manages miniaudio. It contains the miniaudio engine, or `ma_engine` required for the audio to play. It must be initialized when you start the program, or before you try to play any sounds. There is only a need for 1 instance of `adl::Audio`.
## Usage
```cpp
// ...
adl::Audio myAudio = adl::Audio();
// ...
```

The `adl::Sound` class requires an `adl::Audio` 

host with `mkdocs serve`