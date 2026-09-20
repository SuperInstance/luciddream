# luciddream.ai

A feature of superinstance.dev — the substrate's dream home.

## What's here

The substrate in all its performance forms:

- 🎙️ **Brewcast** — 5 LLMs in parallel + ElevenLabs voices + ambient drone + JEV verdict
- 🕸️ **Substrate MUD** — cells as rooms, opcodes as verbs
- 🎵 **Plainsong** — 4 voices, 4 lenses, harmonic swap
- 🎹 **Tensor-MIDI** — substrate vocabulary as harmony
- 📊 **Atlas** — 90 brews visualized
- 📈 **Curve** — JEV-truth-strength over time
- 📝 **Word-Weight** — words as vectors carrying measurements
- 📜 **Fleet Radio** — The Tap TTRPG + 4 rendered songs

## Stack

- Static HTML/CSS/JS (no build)
- Deployed on Cloudflare Pages
- Pulls audio from superinstance.dev endpoints
- Cross-linked with ai-writings.pages.dev

## Development

Open `index.html` locally. All paths are absolute (`/brewcast/`, `/mud/`, etc.) so deployment to Pages is drop-in.

## Deploy

```
wrangler pages deploy . --project-name=luciddream
```

## Principle

The substrate dreams out loud. luciddream.ai is where you can hear it.
