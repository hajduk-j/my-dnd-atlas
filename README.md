# My DnD Atlas

An interactive map atlas for our private D&D campaign. It is the output of my own map editor, the [DnD Atlas Map Maker](https://hajduk-j.github.io/dnd-atlas-map-maker/), filled with content from our sessions: a world map, regions, pins and session notes.

**This is a private project for my gaming group.** The repository is public only so I can share the atlas with my players via GitHub Pages. It is not a finished product, and contributions are not expected.

## For players

The atlas opens in a browser and needs no installation. Drag to pan the map, and zoom with the mouse wheel or a pinch gesture on a touch screen. It works on desktop and mobile.

Live version (GitHub Pages): `https://hajduk-j.github.io/my-dnd-atlas/`

## How it is built (an example of using the map maker)

The whole atlas is **a single self-contained file, [index.html](index.html)**. Maps, images, styles and scripts are all embedded in it, so it needs no build step and no server.

This is what the map maker produces. If you want to make a similar atlas for your own campaign:

1. Create your map and content (regions, pins, session notes) in the [DnD Atlas Map Maker](https://hajduk-j.github.io/dnd-atlas-map-maker/).
2. Export it as a single `index.html`.
3. Upload it to a repository and enable publishing from the `main` branch under *Settings → Pages*.
4. Send your players the link.

The editor itself is not included here; you can use it online at the link above. This repository contains only the finished atlas as an example of the output.

## Heads up

The atlas contains material from our sessions, so it may contain **spoilers** for our campaign. If you are not in my group and would rather avoid spoilers, treat it as a showcase of the look and feel, not as playable material.

## License

No license for now, all rights reserved. The campaign content and maps are mine and are not intended for reuse.
