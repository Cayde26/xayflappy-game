# Flappy Bird HTML5 — Character Animation Edition

A fan-made, browser-playable Flappy Bird-style game using the 27-frame character animation in `assets/character.png`. The frames play at 25 fps and face right.

## Run the game

From this folder, start a local web server:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000). Press `Ctrl+C` in the terminal to stop the server. Serving the files locally avoids browser restrictions on pages opened directly with `file://` URLs.

## Project files

- `index.html` is the game page and includes the visible credits.
- `index.min.js` is the browser-loaded game bundle, including Phaser and the compiled game code.
- `index.coffee` is the editable CoffeeScript source for the game.
- `assets/character.png` is the character sprite sheet; the remaining files in `assets/` provide the background, pipes, ground, and sound effects.

## Credits and rights

### Game code

This project is based on [infoekcz/Flappy-Bird-HTML5](https://github.com/infoekcz/Flappy-Bird-HTML5/), which is a fork of [hyspace/flappy](https://github.com/hyspace/flappy), originally by Shan Zhou. The upstream project identifies its code as MIT-licensed.

### Character artwork and animation

The artwork was drawn and animated by [Darcie](https://folly.milktruckers.com/), commissioned by [XayXay](https://www.youtube.com/@XayXayYT).

The original Flappy Bird graphics and sound effects retain their respective original rights; the upstream project notes that they are not covered by the code license. The commissioned character artwork and animation are credited separately and are not relicensed here.


