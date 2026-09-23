# TRACE-X — Minimal SIH Demo Website

This version is intentionally presentation-first and minimal.

## What changed
- Demo laptop is the main hero element and appears near the top of the page.
- The video is set to autoplay + muted + loop, so evaluators see motion immediately.
- Reduced cards, badges and secondary content.
- "VIEW PROTOTYPE" opens the real TRACE-X application.
- "UNMUTE DEMO" enables audio when needed.

## Run locally

```powershell
python -m http.server 5500
```

Open:
http://localhost:5500

## Add your real demo recording

Replace:
`assets/prototype-demo.mp4`

with your actual TRACE-X prototype recording. Keep the same filename.

## Set the prototype link

Edit `config.js`:

```js
const PROTOTYPE_URL = "https://your-real-tracex-url/";
```

The button will open that URL.

## Browser autoplay note

Modern browsers normally allow autoplay only when the video is muted. Therefore the demo video starts automatically without sound. The evaluator can click `UNMUTE DEMO` if audio is included.
"# TraceX" 
