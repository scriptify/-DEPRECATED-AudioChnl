# AudioChnl
### One Audio object, multiple effects. Easy.

## What is an AudioChnl?
It's an extension of the [Chnl](https://github.com/scriptify/Chnl) module: This module is made for playing, pausing, stopping and manipulating Audio-objects.

If you are not familiar with the [Chnl](https://github.com/scriptify/Chnl) module, [Just have a look at it](https://github.com/scriptify/Chnl).
## Usage
### Creating an AudioChnl
The constructor requires 2 arguments:
1. Your AudioContext
2. Your Audio-object

```javascript
const audioCtx = new AudioContext();
const audio = new Audio('song.mp3');
const audioChnl = new AudioChnl(audioCtx, audioObj);
```

### Methods
```javascript
.start()
```
```javascript
.stop()
```
```javascript
.pause()
```
### Example
```javascript
const audioCtx = new AudioContext();
const audio = new Audio('song.mp3');
const audioChnl = new AudioChnl(audioCtx, audioObj);
audioChnl.start();
```
