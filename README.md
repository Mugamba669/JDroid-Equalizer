#Welcome Equalizerjs a library built on webAudio Api
# start by initializing the Equalizer object
var musicfx = new Equalizer();
# It has methods such as
musicfx.getAudio() which initiates the audio engine.

 # getAudioControls() takes in selectors that handle the play pause functionality
 musicfx.getAudioControls();
 
e.g <buttton id="play">Play</button>
    musicfx.getAudioControls({play:"#play"});
