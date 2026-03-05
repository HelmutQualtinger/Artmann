# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A self-contained HTML5 biographical slideshow about the Austrian poet H.C. Artmann (1921–2000). No build tools, no dependencies — pure HTML, CSS, and vanilla JavaScript in a single file.

## Development

Open directly in a browser:
```bash
open hc-artmann-slideshow.html
```

No build step, no server required.

## Structure

- `hc-artmann-slideshow.html` — Complete slideshow (all styles, scripts, and content inline)
- `assets/` — JPG images referenced by the slideshow (portraits, book covers)

## Architecture

The slideshow uses absolute-positioned slides with opacity transitions. Navigation is handled via keyboard (arrow keys), click (dots/buttons), and touch (swipe). All slides share a consistent two-panel layout: left panel (year/era/image), right panel (text content). The final slide embeds lyrikline.org via iframe for audio playback.
