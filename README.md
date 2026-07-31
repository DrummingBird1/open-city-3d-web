# Open City 3D — Web Build

Browser-playable export of [Open City 3D](https://github.com/) (Godot 4, procedural open-world
sandbox: walk/drive, deliveries, wanted/police, day-night, weather).

This repo contains **only the compiled Web (WebAssembly) export** — no engine source, no project
files. It's the static output of Godot's HTML5 export target, deployed as-is.

Built with Godot 4.8.dev2, `nothreads` variant (no COOP/COEP headers required), Compatibility
(WebGL2) renderer — a few Forward+-only rendering features from the desktop build (SDFGI, SSAO,
SSR, volumetric fog, occlusion culling) are unavailable in this renderer and are disabled
automatically at runtime.
