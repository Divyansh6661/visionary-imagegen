# Visionary — AI Image Generator

> Free AI image generation powered by [Pollinations AI](https://pollinations.ai)

🔗 **Live App:** [visionary-01.netlify.app](https://visionary-01.netlify.app)

---

## What it does

Visionary lets you generate AI images from text prompts — for free, with no hidden charges. Users connect their own Pollinations account and spend their own Pollen. No accounts, no subscriptions, no credit cards required beyond what Pollinations offers for free.

## Features

- 9 style presets — Photorealistic, Digital Art, Oil Painting, Anime, Sketch, MS Paint, Pixel Art, Watercolor, and more
- 4 aspect ratios — Square (1:1), Landscape (16:9), Portrait (9:16), Classic (4:3)
- 2 free-tier models — Flux Schnell and Z-Image Turbo
- Session gallery — browse and reload your recent generations
- Save images directly to your device
- BYOP (Bring Your Own Pollen) — users authorize their own Pollinations balance, no developer costs

## How it works

1. Visit the app and click **Connect Pollinations account**
2. Authorize via your Pollinations account — you choose your own budget
3. Write a prompt, pick a style and aspect ratio, hit **Generate**
4. Save or copy your image

## Built with

- [Pollinations AI](https://pollinations.ai) — image generation API
- Vanilla HTML, CSS, JavaScript — no frameworks, no build tools
- Single file app — fully self-contained in one `index.html`

## Run locally

No installation needed. Just open `index.html` in a browser — or host it anywhere static (Netlify, GitHub Pages, Vercel).

> Note: The BYOP OAuth redirect requires an `https://` URL to work. It won't function from a local `file://` path.

## API

Uses the [Pollinations AI API](https://gen.pollinations.ai/docs):

```
GET https://gen.pollinations.ai/image/{prompt}?model=flux&width=1024&height=1024&key=USER_KEY
```

## License

MIT
