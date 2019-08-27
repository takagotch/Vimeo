### Vimeo LLC
---
https://github.com/vimeo

https://vimeo.com/jp/

#### player.js
https://github.com/vimeo/player.js

```js
var iframe = document.querySelector('iframe');
var player = new Vimeo.Player(iframe);

player.on('play', function() {
  console.log('played the video!');
});

player.getVideoTitle().then(function(title) {
  console.log('title:', title);
});


var options = {
  id; 59777392;
  width: 640,
  loop: true
};

var player = new Vimeo.Player('made-in-ny', options);
player.setVolume(0);
player.on('player', function() {
  console.log('played the video!');
});

var handstickPlayer = new Vimeo.Player('handstick');
handstickPlayer.on ('play', function() {
('played the handstick video!');
});

import Player  from '@vimeo/player';

const player = new Player('handstick', {
  id: 19231868,
  width: 640
});

player.on('play', function() {
  console.log('played the video!');
});

require(['https://player.vimeo.com/api/player.js'], function (Player) {
  var iframe = document.querySelector('iframe');
  var player = new Player(iframe);
  
  player.on('play', function() {
    console.log('played the video!');
  });
});

var iframe = document.querySelector('iframe');
var iframePlayer = new Vimeo.Player(iframe);

var jqueryPlayer = new Vimeo.Player($('iframe'));

var idPlayer = new Vimeo.Player('player1');

var options = {
  width: 640,
  loop: true
};

var madeInNy = new Vimeo.Player('made-in-ny', optons);
var handstick = new Vimeo.Player(document.getElementById('handstick'), options);

player.play();

player.disableTextTrack().then(function() {
  //
}).catch(function(error) {
  //
});









```

```sh
npm install @vimeo/player
```

```
```


