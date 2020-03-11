# AudioContext
Fix for sounds in browser on IOS. If you need to run different sounds at the same time, your sounds play with a delay, or your sounds don't work at all - use it.
## Using
```
const doneLevelSound = new NewAudioContext('done-level.mp3');
      ...
      doneLevel(){
        if(isSounds){
          doneLevelSound.play();
        }
      }
```
