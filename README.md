# Hong Shing City

Official world information portal for **Hong Shing (香城)**, the fictional East Asian metropolis of **Dragon Affairs**, an original game IP by **Aurora Studio**.

## v0.1
- City landing page
- District overview: Hong Shing Island, Central Island, West Island
- Economy and finance overview
- Transport and infrastructure overview
- Responsive layout

## Website imagery

The homepage includes one harbour hero image and three district illustrations.
Images are AI-generated world concept art, not gameplay screenshots or confirmed
architectural/geographic canon. The page labels them accordingly.

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
