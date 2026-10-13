# Config Card Maker

Make an animated “I’m attending Config” card for Instagram: add your name, position and photo, then download a 1080 × 1440, 60 fps MP4 or a PNG.

**Live tool:** https://gopustaxlabs.github.io/config-card-maker/

## What it does

- A text cursor types “Hi there”, a colour wave floods the card, and dozens of Figma-style pieces swoop in to build the photo shape before dissolving into your photo.
- Click the photo on the card to move or resize it, Figma-style: drag to move, drag a corner or pinch to scale, scroll to zoom.
- **Download video**: H.264 MP4 rendered frame by frame (1080 × 1440, 60 fps, 10 s), so playback is perfectly smooth and quality doesn’t depend on your computer’s speed.
- **Download PNG** at 1x, 2x or 4x.
- Works on phones: playback and downloads sit in a dock at the bottom of the screen.

Fast MP4 export needs a browser with WebCodecs (Chrome or Edge). Other browsers record the animation in real time instead.

## Run locally

It’s a single file. Open `index.html` in a browser, or serve the folder:

```sh
npx http-server .
```

## Credits

- Config wordmark from [config.figma.com](https://config.figma.com). Figma and Config are trademarks of Figma, Inc. This is a fan-made tool, not affiliated with Figma.
- Fonts: [Satoshi](https://www.fontshare.com/fonts/satoshi) (poster) and [Geist](https://vercel.com/font) (editor).
- MP4 muxing: [mp4-muxer](https://github.com/Vanilagy/mp4-muxer).
