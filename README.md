![Image of HTML5](https://github.com/rodrmig/myspace-music-player/blob/master/img/demo.png?raw=true)

# Myspace Music Player

This music player is a clone from the popular social network "Myspace" from the mid 2000's.

## Installation

Clone this repository to your machine.

```bash
git clone https://github.com/rodrmig/myspace-music-player
```

## Usage
Open `demo.html` for a live demo. See the following code snippet from `js/app.js` for setup.

```javascript
let settings = {
  containerID: 'myspace-music-player',
  song: 'Feel_Good.mp3',
  artist: 'Syn_Cole',
  audioFilePath: 'audio/Syn_Cole-Feel_Good.mp3'
};

let musicPlayer = new MyspaceMusicPlayer(settings);
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
