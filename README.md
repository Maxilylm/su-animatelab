# AnimateLab

> Build CSS keyframe animations visually and copy the generated `@keyframes` rule.

**[Live demo](https://su-animatelab.vercel.app)**

Writing a keyframe animation usually means editing a stylesheet, reloading, and squinting at whether the timing feels right. AnimateLab keeps the animation running in a live preview while you edit it: add keyframes at any percentage offset, set opacity, transform, scale, rotation, and color on each, and adjust duration, delay, iteration count, direction, and fill mode. The `@keyframes` block plus the `animation` shorthand are regenerated as you go, syntax-highlighted and ready to copy.

## Features

- 12 starting presets — Fade In/Out, Slide Up/Down, Bounce, Shake, Pulse, Spin, Flip, Wiggle, Zoom In, Swing
- Keyframe timeline where you add, remove, and reposition stops by percentage offset
- Per-keyframe controls for opacity, transform, scale, rotate, and color, composed into a single `transform` declaration
- Timing controls: duration, delay, iteration count or infinite, direction (normal/reverse/alternate/alternate-reverse), and fill mode
- Easing presets plus a draggable cubic-bezier curve editor drawn on canvas
- Preview against four element types (box, circle, text, button), with replay and fullscreen, alongside syntax-highlighted `@keyframes` output you can copy to the clipboard

## Stack

- Vanilla JavaScript — a single `index.html` with no framework or runtime dependencies
- Canvas 2D API for the bezier curve editor
- Vite as the dev server and build tool

## Running locally

```bash
npm install
npm run dev
```

---

Part of a series of 91 small web apps. [Browse them all](https://su-slopmachine.vercel.app).
