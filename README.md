# TRACE-X SIH Minimal Demo Website

A minimal presentation website for the TRACE-X prototype.

## YouTube Demo Video

The laptop screen uses a YouTube embedded video instead of bundling a large MP4.

Open `config.js` and replace:

```js
const YOUTUBE_VIDEO_ID = "YOUR_VIDEO_ID";
```

with the ID from your YouTube URL.

Example:

`https://www.youtube.com/watch?v=AbCdEf12345`

becomes:

```js
const YOUTUBE_VIDEO_ID = "AbCdEf12345";
```

The demo attempts to:
- autoplay the YouTube video muted
- loop the video
- keep the video inside the laptop screen
- provide a SOUND ON button
- keep the VIEW PROTOTYPE buttons working

## Prototype URL

The prototype button currently points to:

`https://siddhant2037.github.io/SIH-2026/`

Change `PROTOTYPE_URL` in `config.js` if the final deployment URL changes.

## Notes

Browser autoplay policies generally allow muted autoplay but may block autoplay with sound. The website therefore starts the YouTube demo muted and provides a sound control.

Open `index.html` in a browser or host the folder using any static web host.
