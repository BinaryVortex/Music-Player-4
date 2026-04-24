# Music Player 4

A clean, lightweight music player built with HTML, CSS, and JavaScript.

![App screenshot](Screenshot%202024-09-11%20131827.png)

## Overview

This project is a simple web-based music player that demonstrates how to build a responsive UI and audio controls using vanilla web technologies. It includes play/pause, next/previous track, progress bar, volume control, and a playlist view.

## Features

- Play / Pause
- Next / Previous track
- Seek using progress bar
- Volume control
- Simple playlist UI
- Responsive layout (desktop & mobile)

## Technologies

- HTML
- CSS
- JavaScript (vanilla)

## Getting started

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Music-Player-4.git

2. Open `index.html` in your browser (or serve the folder with a local static server):

   - Double-click `index.html`, or
   - Use a simple server, for example with Python 3:
     ```bash
     python -m http.server 8000
     # then open http://localhost:8000 in your browser
     ```

3. The player should load and be ready to use.

## Add your own tracks

- Add audio files to the `assets` folder (or any folder you prefer).
- Update the playlist array in `script.js` to include your tracks and metadata (title, artist, file path, cover image if used).

Tip: Keep file paths relative so the player can load audio and images correctly.

## Customization

- Edit `style.css` to change the look and feel.
- Modify `script.js` to change behavior (shuffle, repeat, keyboard shortcuts, etc.).

## Contributing

Contributions are welcome — open an issue or submit a pull request with improvements, bug fixes, or new features.

## Screenshot

The screenshot above shows the player UI. The image file included in the repository is `Screenshot 2024-09-11 131827.png`.

## License

No license specified. If you'd like to add one, include a `LICENSE` file in the repository (MIT is a good default for small projects).
