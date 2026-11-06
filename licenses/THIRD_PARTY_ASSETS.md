# Third-party assets

## Local typefaces

The runtime uses locally hosted, Cyrillic-subset WOFF2 derivatives from the official [Google Fonts repository](https://github.com/google/fonts). No font files are requested from the network at runtime.

- **Inter Tight:** `fonts/inter-tight-variable.woff2`; source `ofl/intertight/InterTight[wght].ttf`; licensed under the SIL Open Font License 1.1. The complete license is stored at `licenses/Inter-Tight-OFL.txt`.
- **Oswald:** `fonts/oswald-variable.woff2`; source `ofl/oswald/Oswald[wght].ttf`; licensed under the SIL Open Font License 1.1. The complete license is stored at `licenses/Oswald-OFL.txt`.

All photographs below are used under the [Pexels License](https://www.pexels.com/license/), which permits free website use and modification. Downloaded 21 August 2026. Each local version was cropped, desaturated, contrast-graded, resized, and converted to WebP.

| Local file | Creator | Individual source |
|---|---|---|
| `assets/hero-car.webp` | Matheus Bertelli | [Back view of a black sports car with red light](https://www.pexels.com/photo/back-view-of-a-black-sports-car-with-red-light-13870801/) |
| `assets/service-dsg.webp` | cottonbro studio | [Close-up of transmission gears](https://www.pexels.com/photo/close-up-of-transmission-gears-7568427/) |
| `assets/service-mechatronic.webp` | Sergei Starostin | [Mechanic working on car transmission](https://www.pexels.com/photo/mechanic-working-on-car-transmission-in-workshop-29181492/) |
| `assets/service-oil.webp` | Fatih Erden | [Mechanic checking the oil of a car](https://www.pexels.com/photo/a-mechanic-checking-the-oil-of-a-car-10490610/) |
| `assets/service-diagnostic.webp` | Fatih Erden | [Person using a laptop in a driver's seat](https://www.pexels.com/photo/person-using-a-laptop-while-sitting-on-a-driver-s-seat-10490631/) |

## Vehicle marque identifiers

The runtime keeps local SVG copies of the marque identifiers used in the first-screen service registry. The marks identify vehicle marques serviced by ДСГ ДОК; their presence does not imply manufacturer authorization, partnership, certification, or endorsement.

- `assets/brands/volkswagen.svg`, `audi.svg`, `skoda.svg`, `seat.svg`, `porsche.svg`, and `bmw.svg`: retrieved from the open-source [Simple Icons](https://simpleicons.org/) project; Simple Icons is distributed under the [CC0 1.0 Universal dedication](https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md). Brand marks remain subject to applicable trademark rights.
- `assets/brands/mercedes-benz.svg`: retrieved from [Wikimedia Commons, File:Mercedes-Benz Star 2022.svg](https://commons.wikimedia.org/wiki/File:Mercedes-Benz_Star_2022.svg). The file is identified there as a simple-geometry logo in the public domain; trademark restrictions may still apply.

## ДСГ ДОК logo lockup

- Primary lockup source supplied directly by the site owner as `eaa0616f-a91f-4d1d-89d4-6826ae469d10.jpg`.
- Exact finish-flag vector supplied directly by the site owner as `флаг.svg`; its seven source paths are embedded without geometric modification.
- Runtime derivative: `/assets/dsg-dok-logo-v3.svg`.
- The supplied reference included small partner marks; they were removed from the runtime SVG at the site owner's request.
