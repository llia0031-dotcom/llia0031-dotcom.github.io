# jason-d-e.github.io

Personal site of Liang Liyuan: https://jason-d-e.github.io/

A portfolio of projects around one question: can every sentence an AI writes show its evidence? Chinese pages sit at the root, English pages under `/en/`.

## What is here

- `index.html`, `en/`: the home page, with the cover, the ring of projects, the method, the screens, the iteration log and a short About.
- `work/<project>/`, `en/work/<project>/`: one page per project, with a one-minute summary, the evaluations and their numbers, the iterations and the limits.
- `static/`, `media/`: the stylesheets, scripts, fonts, recordings and pictures those pages use.
- `cairn.html`, `tracedesk.html`: the earlier addresses of two case studies. Each now sends the reader on to the project's page under `work/`, so that existing links keep working.

This repository holds the built pages. The sentences and numbers on them are generated from each project's evaluation records, so a page never carries a number that was typed in by hand.

## Credits

- Built with [Astro](https://astro.build/) (MIT). [Matter.js](https://brm.io/matter-js/) (MIT) moves the tags on the About screen, and the icons come from [IconPark](https://github.com/bytedance/IconPark) (Apache-2.0).
- The pages that stack over one another follow the idea of Codrops' [StickySections](https://github.com/codrops/StickySections) (MIT), written anew for this site.
- Fonts, loaded through Fontsource: Merriweather, Noto Serif SC, Noto Sans SC and Geist, all under the SIL Open Font License 1.1.
