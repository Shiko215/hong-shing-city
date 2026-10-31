# Hong Shing City

Official world information portal for **Hong Shing (香城)**, the fictional East Asian metropolis of **Dragon Affairs**, an original game IP by **Aurora Studio**.

## v0.1
- City landing page
- District overview: Hong Shing Island, Central Island, West Island
- Economy and finance overview
- Transport and infrastructure overview
- Responsive layout

## Website imagery

The homepage includes one city-centre hero and seven street-level gallery images,
adapted from seven simulation-game screenshots and one Unreal Editor night-alley
screenshot supplied by the user. Edits retain
the source camera, streets, buildings, vehicles, and everyday urban character,
with refined materials/lighting and removal of debug overlays. The night-alley
adaptation reduces rendering noise and lifts shadows while retaining its neon
lighting, closed stalls, and narrow passage. Shop names, bank identities, logos,
and advertisements follow their respective original screenshots. These are visual
references, not Dragon Affairs gameplay screenshots or confirmed geography.
They are not assigned to specific islands. The page labels their source and use.

- Optimized WebP assets: `assets/images/`
- Generation prompts and provenance: [docs/image-prompts.md](docs/image-prompts.md)
- Asset dimensions and file sizes: [assets/images/manifest.json](assets/images/manifest.json)

This is a buildless static site. GitHub Pages serves `index.html` and `assets/`
from the repository root; there is no framework `public/` directory. Keep image
URLs relative (`assets/images/...`) so they work under `/hong-shing-city/` and
on a custom domain. Deploy the HTML, stylesheet, and image files together.

## Canon policy
Content should distinguish confirmed canon from draft and legacy material as the world bible grows.

© Aurora Studio. Hong Shing and Dragon Affairs are fictional.
