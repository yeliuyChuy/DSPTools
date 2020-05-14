# DSPTools
 
 A quick implementation and deployment of some DSP algortihms
 
 ## Table of Contents

- [Convolver](#Convolver)

## Convolver

A fast fourier transform based implementation which facilitates the convolution processing. It imparts acoustics characteristic of arbitrary systems, e.g. room and HRTF, on the given signal. To properly use it,

1. Make sure your IR file and audio file have same number of channels at same sampling rate

2. Select your files and output folder in GUI, then simply click Process.

![](https://github.com/yeliuyChuy/DSPTools/blob/master/pics/Convolver_GUI.png)

Tips: In consideration of the purpose of using, some open source Impulse Response library are used in demo and suggested here:

| Purpose      | Corpus    | 
| ---------- | :-----------:  | 
| Space Simulation    | [Isophonics](http://isophonics.net/content/room-impulse-response-data-set)| 
| HRIR     | [LISTEN by Ircam](http://recherche.ircam.fr/equipes/salles/listen/)|

Demo: [Original Wav](https://github.com/yeliuyChuy/DSPTools/blob/master/demo/convolver_oud_%20original.wav), [Processed Wav](https://github.com/yeliuyChuy/DSPTools/blob/master/demo/convolver_oud_output.wav)

Other commercial libraries by [Waves](https://www.waves.com/downloads/ir-convolution-reverb-library) and [Boom Library](https://www.boomlibrary.com/sound-effects/outdoor-impulse-responses/) might interest those sound designers.
