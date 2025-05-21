# Creative Music Visualizer 

## Overview
This interactive project is a dynamic music visualizer built using p5.js and the Web Audio API. It supports six unique visualizations controlled by keyboard inputs (1–6), and includes real-time microphone input for the final visualization.

## Features
- Choose from five preloaded songs
- Play/pause and shuffle buttons
- Real-time audio analysis using `p5.FFT`
- Visualization 6 uses your microphone as input
- Visual effects rendered using p5.js in WEBGL mode

## Controls
- Press keys `1` to `6` to switch between different visualizations.
- Use the control panel to:
  - Play/pause the music
  - Shuffle through tracks
  - Select a specific track

## How to Run
1. Host the project using a local web server (e.g., VSCode Live Server, Python `http.server`)
2. Ensure the `mp3/` directory contains `song1.mp3` through `song5.mp3`
3. Open `index.html` in your browser (HTTPS recommended for microphone support)

## Technologies Used
- HTML5 + CSS3
- JavaScript (p5.js, p5.sound, dat.GUI)
- WebGL canvas rendering

## Reflection
This project blends creativity with technical skills in signal processing and real-time rendering. It encourages user interaction while leveraging music theory concepts and sound analysis, demonstrating a bridge between computer science and digital arts.

