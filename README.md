1) Map the button colours on a direct relationship between the continuous spectrum of frequencies of electromagnetic energy in the band of visible light and the pitches of sound in a relationship to continuous frequency spectrum of sound that are 40 octaves (a factor of 240 = 1,099,511,627,776) below the frequencies of visible light.

See: https://www.flutopedia.com/sound_color.htm

2) Enables a new direct microtonal/edoOctave+note steps from layout straight to MIDI note mode. The pitchbend emulation from nearest 12 tone mode can now be disabled from the menu (and is disabled by default), so the real MIDI steps will be sent directly through to your DAW to synth with scala/tun tuning instead, but the internal synth will still also play the correct frequency notes.  
3) Additionally MIDI notes that go < 0 or > note 127 will now be blacked out on the keyboard when in direct mode rather than wrapping round
4) Centre note 60 better when in direct MIDI mode, and transpose will also shift the keys correctly for the direct MIDI mapping
5) Physics Colors of Sounds mode is always the default color map now (so also put it at the bottom of the Color change menu to save clicking back through it again anyway)

Outstanding issues: 

* The satutation/intensity could be distributed more to discern shades between adjacent tones a bit more by deliberately scaling the saturation or lightness a little bit further, but for now have just set th colours to be the same level of vividness and saturation
* the led hardware itself i think pushes yellow oranges and greens a little off towards each other so could do with some calibration

I haven't done C++ in years, so needs optimisation and tidyup

Todo:

1) Make bosanquet-wilson always the default in various tunings to save time
2) Make build script to copy new/modified scales from my scales library in to code from scales folder whenever ran
