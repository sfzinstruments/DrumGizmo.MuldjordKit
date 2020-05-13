# MuldjordKit v1.0

This is an old version of the MuldjordKit and it is meant to be used only with sfz players.

**This work is not to be used as in the original scope with the DrumGizmo software
and then don't contact the original authors for any reason about it.**

The current version can be downloaded from the [DrumGizmo website],
made using multichannel wav files, which at the present time seems not to be
supported by most sfz players,
while this version was originally made with stereo files.

Mapped by kinwie using ARIA SFZ Level 2.0 for ARIA Player / Sforzando,
converted to flac samples.

## Description

> The MuldjordKit is a Tama Superstar drumkit with all the bells and whistles.
The samples for this kit was actually recorded all the way back in 2010 when I
was recording / playing drums for the [Sepulchrum debut album].
When recording drums I always sample the kit in case we need a cymbal or a single
drum hit here and there to patch up the recordings.
It turns out that I sampled it so well that it can be used with DrumGizmo.

[Lars Muldjord].

- 2 kickdrums
- 3 hanging toms
- 1 floor tom
- 1 snare
- 1 hihat
- 2 crash cymbals
- 2 ride cymbals
- 1 china cymbal

This should be considered a metal or rock kit.

## License

The DRSKit drumkit source files are released under the

<a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/">
<img alt="Creative Commons License" style="border-width:0"
    src="https://i.creativecommons.org/l/by-nc/3.0/88x31.png" /></a>
<a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/">
Creative Commons Attribution-NonCommercial 3.0 Unported License</a>.

This means you can do with it whatever you wish as long as you don't make money
off the stuff you use it for.

## Installation

For the ARIA Player multi (.ariax) files to work properly, you need to place
the "DrumGizmo" folder into your ARIA Player / Sforzando `User files path` directory:

`[User files path]\DrumGizmo\MuldjordKit\`

then you can load the `ariax` files or just drag'n drop it to ARIA Player GUI.

## Usage

- Each sfz file (mic channel) has each kitpiece Bleed level control
  that can be accessed at the Controls page.
- All mic channels are mono audio so you need to do panning in your DAW tracks :
  - Amb : L-R
  - OH : L-R
  - Tom 1-2-3-4 : left -to- right
  - Hihat : a bit left
  - Ride : L-R
- If you don't have ARIA Player, then you can load each sfz file
  into 16 instances of sforzando.

**Notes**:

- The velocity range is distributed evenly.
- Added keys for muting the cymbals.
- You can change the key mapping of the drum notes to your likes very easily via
  keymap.txt with a text editor.

## Recording setup

### Microphone setup

- Close mic: Snare top: Shure Sm57
- Close mic: Snare bottom: Shure Sm57
- Close mic: Tom1: AKG C516 ML
- Close mic: Tom2: AKG C516 ML
- Close mic: Tom3: AKG C516 ML
- Close mic: FTom4: AKG C516 ML
- Close mic: Kick drum left inside barrel: AKG D112 + DDrum trigger
- Close mic: Kick drum right inside barrel: AKG D112 + DDrum trigger
- Close mic: Ride cymbal left: Shure Sm57
- Close mic: Ride cymbal right: Shure Sm57
- Close mic: Hihat: Shure Sm57
- Overhead left: Røde Nt5
- Overhead right: Røde Nt5
- Ambience: Focusing on entire kit placed a little further back in the room to the left: t.bone Rb500
- Ambience: Focusing on entire kit placed a little further back in the room to the right: t.bone Rb500

### Channel setup

All microphones are connected to its own channel when loading the kit in DrumGizmo.
16 channels total.
Remember to pan the relevant channels to give you a better stereo effect.

- Ch 1: Ambience left
- Ch 2: Ambience right
- Ch 3: Hihat
- Ch 4: Kickdrum left
- Ch 5: Kickdrum right
- Ch 6: Overhead left
- Ch 7: Overhead right
- Ch 8: Ride left
- Ch 9: Ride right
- Ch 10: Snare bottom
- Ch 11: Snare top
- Ch 12: Rack tom 1
- Ch 13: Rack tom 2
- Ch 14: Rack tom 3
- Ch 15: Floor tom
- Ch 16: Kick drum trigger signals

## Thanks

This is a very great Rock/Metal kit that contain all the bleed in every used
microphones just like the real recording!
Many big thanks to Lars Muldjord for kindly providing useful helps and done
this fantastic sample library, and to all the DrumGizmo team that has been very
kind making this kit available free for us.

[DrumGizmo website]:      https://www.drumgizmo.org/wiki/doku.php?id=kits:muldjordkit
[Sepulchrum debut album]: http://downloads.sepulchrum.net/Sepulchrum-The_Gardens_of_Necropolis-flac.zip
[Lars Muldjord]:          http://www.muldjord.com/
