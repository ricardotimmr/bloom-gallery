# bloom-gallery

A photography portfolio website built around a parallax gallery experience. Clean, quiet, and a little alive.

---

## Concept

The site lives somewhere between a gallery wall and a greenhouse. A warm off-white background, not sterile, more like paper or linen, with two large orchids flanking the edges at low opacity. The orchids aren't decoration for decoration's sake; they breathe. Either animated to bloom slowly in CSS, or using sped-up video of real orchids blooming played on loop. The effect should feel ambient, not distracting.

The gallery is the centerpiece: a horizontal infinite scroll spanning the full viewport width, with a parallax effect on the images as you move through them. Already coded. The images don't just slide — they have depth.

---

## Pages

### `/` — Gallery
The main experience. Full-width horizontal gallery with parallax scrolling. Orchids in the background. Minimal navbar at the top. Nothing competes with the images.

### `/playground` — Grid
An infinite scrolling image grid. All images, no constraints. Click any image to open a modal — the modal shows the image and a written piece: either about that specific photo or about the shooting session it came from. A place to get lost in the archive.

### `/info` — Info
About the project / photographer. Kept simple. Probably just text and maybe one image.

---

## Design

- **Background**: Off-white, warm. Think uncoated paper, not a hospital wall.
- **Orchids**: Two large orchids, left and right edges, low opacity. Animated bloom (CSS or video TBD).
- **Navbar**: As minimal as possible. Logo or wordmark left, three navigation links. That's it.
- **Typography**: TBD, needs to feel considered. Probably something with a little character, not a system font.
- **Gallery**: Already built. Horizontal infinite scroll, full viewport width, parallax on images.
- **Modal**: Opens on image click in the playground. Shows image + text. Clean overlay.

---

## Stack

Built with React, Vite, TypeScript, Claude Code.

---

## Status

Early concept / in progress.
