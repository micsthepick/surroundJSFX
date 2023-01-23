# Surround JSFX

## installation

see my other repoisitory, https://github.com/micsthepick/JSVocalRedIso, for an in depth guide to installing JSFX.
in addition to that, you may also need to download the Hesuvi HRIRs and put them in Data/hrir in order for the HRIR.jsfx effect to function, unless you don't need to use it.

## plugins

* `7.1 to 5.1` matrixes 7.1 to 5.1 audio
* `OOPS encoder` matrixes 5.1 audio to 2 channel
* `OOPS 7.1 decoder/encoder` will up and down mix (in a lossy manner) from 7.1 to 2.0 (the encoder encodes 7.1 tracks in 2.0, and decoder the opposite, but with a not insignificant delay)
* `quickupmix` is a series of experimental plugins to do the decoding process with less delay, but less effectiveness
* `white-phase` was made in the process of testing these plugins, it will output a stereo signal of white noise, with a pan that goes 180 degrees in the stereo field, allowing negatively correlated pans.
* `HRIR` is the newest addition, when supplied with a 7 or 14 channel HRIR impulse underneath the Data/hrir directory (HeSuVi format), it generates a binaural signal.
