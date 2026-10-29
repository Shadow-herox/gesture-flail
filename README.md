# Gesture Flail

A browser game controlled by your hand through the webcam. Make a fist to steer the blue ball and swing the red weight on its spring tether to smash incoming enemies before they touch you.

Hand tracking runs in the browser using [MediaPipe Hands](https://developers.google.com/mediapipe). If the camera isn't available, the mouse controls the ball instead.

## How to play

- ✊ **Fist** — move the ball (it follows your palm)
- ✋ **Open hand** — the ball stops following
- Hitting an enemy with the tether scores **+5**; every second survived scores **+1**
- Game over when an enemy touches the ball or the weight

## Run it

Open `index.html` in a modern browser (Chrome works best) and allow camera access. Some browsers only allow the camera over `https://` or `localhost`, so if it's blocked, serve the folder locally:

```bash
npx serve .
```

## Built with

HTML5 Canvas, vanilla JavaScript, MediaPipe Hands
