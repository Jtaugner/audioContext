# AudioContext
Fix for sounds in browser on IOS. If you need to run different sounds at the same time, your sounds play with a delay, or your sounds don't work at all - use it. This is useful for HTML5-games.
## Using
```js
//Path of sound
const url = 'done-level.mp3';
const doneLevelSound = new NewAudioContext(url);
...
doneLevel(){
    if(isSounds){
        doneLevelSound.play();
    }
}
```
Taken from https://stackoverflow.com/questions/12517000/no-sound-on-ios-6-web-audio-api
