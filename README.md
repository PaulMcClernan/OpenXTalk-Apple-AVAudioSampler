# LCB_AppleAVAudioSampler
A LiveCode Builder Module that binds to Apple's AudioUnit Sampler Synth!

Version 0.1:

Proof of concept working on macOS, yeah!

Loads Apple's General MIDI Soundbank (gs_instruments.dls from inside the CoreAudio bundle).

Plays a note.

Version 0.2:

Loads DLS & SF2 from files on the fly with program change and bank selecting

Plays 2 notes

Version 0.3:

Loads DLS & SF2 from files on the fly with program change and bank selecting

Loads EXS24 (Logic/GarageBand sampler instruments) & Apple Sampler .AUPresets files

Plays some notes

Version 0.4:

Loads DLS & SF2 from files on the fly with program change and bank selecting

Loads EXS24 (Logic/GarageBand sampler instruments) & Apple Sampler .AUPresets files

Loads loose Sound Files (mp3,aiff,wav,etc.) files *

*this handler seems to crash quite a bit when loading more sounds, memory management issue.

Plays some notes

Version 0.5

Loads Downloadable Sound DLS, Sound Font SF2, Emagic/Apple EXS, and AUSampler.aupreset files.

Loads loose Sound Files (mp3,aiff,wav,etc.) files *Temp fix for problem loading individual audio files(s) turns out it was a bug in LiveCode Builder that should be fixed in the next LC Release.

Added a few functions to get info on state of the Audio Engine & AUSampler

Plays some notes
