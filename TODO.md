# THINGS I NEED TO DO BEFORE MONDAY

* Finish slides
* Create bug report for linux playback in chromium
* Make sure to install and test everything for mac
* read more about offlineWebAudio

* Compile list of os projects
* Compile list of os contributors to follow
* make giant list of resources
* make a folder of lots of images to use for the presentation

# loading sounds Audiotag vs webaudio
* audiotag vs webaudio
* loading sound example arrayBuffer
* mention offline

# controlling playback
* wrappers / audiotag / built in stuffz(audiotag)

# effects
* tunajs
* creating your own shit

# Visualizations
* code example
* fft
* linux bug
* cannot hookup prior to playing with example
* wavesurfer.js

# Server processing
* extreme sound stretch
* workers

# Other specs that compliment web audio
* getUserMedia/recorder.js
*


# abstractions
* audio tag isn't enough
 * vis, effects, manipulate audio, record audio, portable, collaborate with other people.
 * yay webaudio chris wilson, know his shit... super nice...

new AudioContext();

make request
decodeAudioBuffer;
createAudioBufferSource;
source.buffer = decode.

connect(audioContext.destination);

source.play(0);

createSource function (url) {
    return url;
}

* show loading

source.play(0);
source.stop();

function pause() {
var stopTime = context.currentTime;
source.stop();
}

function play () {
var x = context.currentTime + stopTime;

source.play(x);


source.pause()
source.skipForward
skipBackward
}


http://noisehack.com/custom-audio-effects-javascript-web-audio-api/

// tuna.js
var tuna = new Tuna(context);

var effect = new tuna.delay({

});

source.connect(effect.input);

analyserNode:


mpc2000xl facts
space on a floppy disk
play sounds that can fit on a floppy disk

simple sampler
it sucked

node webaudio / baudio

super stretch

recorder.js

clojure

web components

polymer

wavesurfer.js + tuna.js


still to come!
audacity type editing

startOffset += context.currentTime - startTime;

audioContext.decodeAudioBuffer()
