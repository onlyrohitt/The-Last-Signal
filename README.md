# The Last Signal

> A cinematic 3D signal-hunting adventure by **Rohit Sharma**.

Explore a silent neon city, recover seven signal fragments, uncover the archive, restore power to the abandoned laboratory, find the tower keycard and tune the final carrier wave.

## Play

This is a static browser game. No account, installer, backend or build step is required.

- **Play locally:** open `index.html` in a modern desktop browser, or serve this folder with a local static server.
- **GitHub Pages:** open **Settings → Pages**, set **Source** to **GitHub Actions** once, then the included workflow deploys the site automatically on every push to `main`. Expected URL: https://onlyrohitt.github.io/The-Last-Signal/.
- **Netlify:** import this repository, set the base directory to `/`, leave the build command empty, and set the publish directory to `.`.

The root `index.html` is the production entry point. The original development copies remain in `The-Last-Signal/`; the small root-level avatar copy keeps image loading consistent across GitHub Pages and Netlify.

## Controls

| Action | Desktop | Touch |
| --- | --- | --- |
| Move | W / A / S / D | Left joystick |
| Look | Mouse | Drag right side |
| Jump | Space | Jump button |
| Interact | E | Use button |
| Run | Shift | Run button |
| Pause | Escape / Pause | Pause button |

Progress and settings are saved locally in the browser on the device being used.

## Technical notes

- Three.js r128 for real-time 3D rendering.
- Web Audio API for generated ambient sound and effects.
- Procedural environment art and lighting.
- Responsive keyboard, mouse and touch controls.
- Static hosting compatible with Netlify and GitHub Pages.

The game loads Three.js and display fonts from public CDNs, so an internet connection is needed for those external libraries and fonts. WebGL must be enabled in the browser.

## Credits

Created by Rohit Sharma. Story, gameplay, code, procedural visuals and generated audio are part of this independent project.

- [Portfolio](https://rxhitstll.netlify.app)
- [LinkedIn](https://www.linkedin.com/in/rohit-sharma-6256a0220/)
- [Instagram](https://instagram.com/rxhit_stll)

## License

All rights reserved unless otherwise stated. The source is public for viewing and personal learning; ask the creator before redistributing the game or its assets.
