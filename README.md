# Boards

Infinite whiteboards

## Status

Not finished

## Usage

Best used with a tablet. Boards are saved to local storage and restored whenever you start the app.

* Click and drag to draw. There is only one color and thickness. There is no eraser.
* Right click and drag the mouse to move the drawing around. The space is infinite.
* Press `CMD-Z` to undo your last pen stroke. You have infinite undos. There is no redo.
* Press `CMD-N` to start a new blank board.
* Press `CMD-U` to upload to a gist. You will be prompted for a username, password, and title. A shareable [RawGit](https://rawgit.com/) URL will be opened in your default browser.
* Press `CMD-S` to save the board to disk.

## Building

```
$ npm install
$ make darwin
```

Requires `npm` and [`electron-packager`](https://github.com/electron-userland/electron-packager). Only OSX at the moment.

## To do

* Open old boards
* Images
* Zooming

## License

Copyright © Ramsey Nasser 2015. Provided under the [MIT License](http://opensource.org/licenses/MIT).
