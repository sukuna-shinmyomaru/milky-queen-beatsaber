# BeatSaber maps for Milky Queen songs

This is a collection of the Milky Queen songs I have mapped and can be played on BeatSaber. It is **required** that you own the song files to be able to play, I'm not uploading the songs here and they are needed to play.

## Index

[Milky Queen](#milky-queen)

[Map showcase](#map-showcase)

[Artwork](#-artwork)

[How to play the maps](#how-to-play-the-maps)

  - [Converting the song for BeatSaber](#converting-the-song-for-beatsaber)
  - [Song information](#song-information)

## Milky Queen

She is a VSinger that composes most of her music and also streams as a VTuber

[Twitter](https://twitter.com/milkyqueen_idol/) - [YouTube](https://www.youtube.com/@MilkyQueenVsinger)

[Milky Way (EP)](https://linkco.re/dy4ZpFgH)

## Map showcase

### Palace of Glass

**Normal** - 366 notes - 1.79 nps
[![Palace of Glass - Normal](https://img.youtube.com/vi/kincBdcyYj4/maxresdefault.jpg)](https://youtu.be/kincBdcyYj4)
**Hard** - 525 notes - 2.56 nps
[![Palace of Glass - Hard](https://img.youtube.com/vi/kooc_ygiHVw/maxresdefault.jpg)](https://youtu.be/kooc_ygiHVw)
**Expert** - 791 notes - 3.86 nps
[![Watch the video - Expert](https://img.youtube.com/vi/kincBdcyYj4/maxresdefault.jpg)](https://youtu.be/kincBdcyYj4)

**Hard** - 405 notes - 2.60 nps
[![Meteor - Hard](https://img.youtube.com/vi/TEuVHXZfqU4/maxresdefault.jpg)](https://youtu.be/TEuVHXZfqU4)
**Single Saber - Expert** - 359 notes - 2.31 nps
[![Meteor - Single Saber - Expert](https://img.youtube.com/vi/JDhlVuBoZaU/maxresdefault.jpg)](https://youtu.be/JDhlVuBoZaU)
**Expert+** - 715 notes - 4.59 nps
[![Meteor - Expert+](https://img.youtube.com/vi/SgDnngMdg24/maxresdefault.jpg)](https://youtu.be/SgDnngMdg24)

## Artwork

## How to play the maps
To play the map you need to place the song as a file called `song.ogg` alongside the other files, and the directory should look like this:

```
\CustomLevels
  \Palace of Glass - Milky Queen - Milky Way [EP]
     BPMInfo.dat
     cover.png
     ExpertStandard.dat
     HardStandard.dat
     Info.dat
     NormalStandard.dat
     song.ogg
```

The song must be encoded with _OGG Vorbis_. You'll have to add silence at the start of the song to match a beat where the map expects it.

### Converting the song for BeatSaber

You can generate the needed file `song.ogg` with [Audacity](https://www.audacityteam.org/) or any other audio editor. Audacity is open source and free, so I 

1. Get the song file(s): **[You can purchase/stream the EP songs here](https://linkco.re/dy4ZpFgH)**
2. To generate silence:
- With the selector at the start, go to Generate > Silence
- Enter the [value needed for the song](#song-information)
- Check that the first beat hits in the correct timestamp
- If not, undo the generated silence and change the interval duration until it fits. You can also insert a lot of silence and _slide_ the song segment on top of the silence segment until the first beat matches
3. To export as OGG Vorbis:
- Go to `File > Export Audio`
- Select `Format: Ogg Vorbis Files`
- Audio options recommended:
	- Channels: `Stereo`
	- Sample Rate: `44100` or `48000` Hz (should match your source file by default)
	- Quality: `8`
- Setting the File Name to `song.ogg` press _Export_ and place it along the other files

### Song information

Each mapped song has a beat where the map expects the first beat of the song, that's the result that matters. I'm also going to provide the silence interval I had to add use at the start, but **this might be different on other releases**

#### Palace of Glass
- First beat: `2.000` seconds (4th beat ingame, at 120 BPM)
- Silence to add: `1.525` seconds

#### Meteor
- First beat: `2.000` seconds (5th beat ingame, at 150 BPM)
- Silence to add: `1.525` seconds
