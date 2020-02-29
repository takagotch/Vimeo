### Vimeo LLC
---
https://github.com/vimeo

https://vimeo.com/jp/

https://vimeo.com/user81422182







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

var options = {
  width: 640,
  loop: true
};

var madeInNy = new Vimeo.Player('made-in-ny', options);
var hardstick = new Vimeo.Player(document.getElementById('handstick'), options);


player.play(0;

player.disableTextTrack().then(function() {
  //
}).catch(function(error) {
  //
});

player.getLoop().then(Function(loop) {
});

player.setColor('#00adef').then(function(color) {
}).catch(Function(error) {
});

var onPlay = function(data) {
};
player.on('play', onPlay);

var onPlay = function(data) {
};
player.on('play', onPlay);
play.off('play', onPlay);
player.off('play');

player.loadVideo(7969781).then(function(id) {
}).catch(function(error) {
  switch (error.name) {
    case 'TypeError':
      break;
    case 'PasswordError':
      break;
    case 'PrivacyError':
      break;
    default:
      break;
  }
});

player.ready().then(function() {
});

player.enableTextTrack('en').then(function(track) {
}).catch(function(error) {
  switch (error.name) {
    case 'InvalidTrackLanguageError':
      break;
    case 'InvalidTrackError':
      break;
    default:
      break;
  }
});

player.pause().then(function() {
}).catch(function(error) {
  switch(error.name) {
    case 'PasswordError':
      break;
    case 'PrivacyError':
      break;
    default:
      break;
  }
});

player.play().then(function() {
}).cathc(function(error) {
  switch(error.name) {
    case 'PasswordError':
      break;
    case 'PrivacyError':
      break;
    default:
      break;
  }
});

player.unload().then(function() {
}).catch(function(error) {
});

player.destroy().then(function() {
}).catch(function(error) {
});

player.getAutopause().then(function(autopause) {
}).catch(function(error) {
  switch (error.name) {
    case 'UnsupportedError':
      break;
    default:
      break;
  }
});

player.setAutopause(false).then(function(autopause) {
}).catch(function(error) {
  switch(error.name) {
    case 'UnsupportedError':
      break;
    default:
      break;
  }
});

player.getBuffered().then(function(buffered) {
}).catch(function(error) {
});

player.getColor().then(function(color) {
}).catch(function(error) {
});

player.setColor('#00adef').then(function(color) {
}).catch(function(error) {
  switch(error.name) {
    case 'ContrastError':
      break;
    case 'TypeError':
      break;
    case 'EmbedSettingsError':
      break;
    default:
      break;
  }
});

player.addCuePoint(15, {
}).then(function(id) {
  switch(error.name) {
    case 'UnsupportedError':
      break;
    case 'RangeError':
      break;
    default:
      break;
  }
});

player.removeCuePoint('09ecf4e4-b587-42cf-ad9f-e666b679c9ab').then(function(id) {
}).catch(function(error) {
  switch (error.name) {
    case 'UnsupportedError':
      break;
    case 'InvalidCuePoint':
      break;
    default:
      break;
  }
})


palyer.setVolume(0.5).then(function(volume) {
}).catch(function(error) {
  switch (error.name) {
    case 'RangeError':
      break;
    default:
      break;
  }
});

player.on('eventName', function(data) {
});


```

```sh
npm install @vimeo/player
```

```
```


