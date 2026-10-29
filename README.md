<p align="center">
  <a href="https://florae.aarya.cyou/"><img src="docs/banner.svg" alt="Florae — an editorial botanical plate with a crimson rose" width="100%"></a>
</p>

# Florae

*A flower a month, from the edge of the map.* · [Visit the site](https://florae.aarya.cyou/)

Florae is a concept for a botanical archive and monthly specimen atelier. Warm paper, crimson petals, field coordinates, and carefully set serif type give each flower the presence of a museum plate. The experience invites visitors to explore four specimens and the imagined stories of the places they came from.

![Florae website showing its rose specimen and editorial opening](docs/media/florae.jpg)

## For developers

Florae is a single-page JavaScript site built with Vite, Three.js, GSAP, Lenis, and Tailwind CSS. The source is in `src/`; 3D assets are in `public/models/`.

```bash
npm ci
npm run dev
```

For a production build, run `npm run build`. Cloudflare Pages uses that command and `dist` as the output directory; the repository also includes `wrangler.jsonc`.

## Rights and credits

The project keeps its different rights scopes separate:

| Material | Terms |
| --- | --- |
| Adapted source code | [MIT license](LICENSE), with the original copyright retained |
| Florae-specific banner and original project presentation | [Florae content notice](LICENSE-FLORAE.md) |
| Zyrix Dev name and marks, where referenced | [Zyrix Dev brand notice](LICENSE-ZYRIXDEV.md) |
| 3D models and the screenshot above | [Asset licenses](docs/ASSET-LICENSES.md) |
| Libraries and web fonts | [Third-party notices](docs/THIRD-PARTY-NOTICES.md) |

The source project and contributors are acknowledged in [Credits](docs/CREDITS.md).
