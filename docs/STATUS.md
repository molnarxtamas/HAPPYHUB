# HappyHub – állapot

_Frissítve: 2026-10-19. SZÜNETEL (2026-09-22 óta)._

## Mi ez
Magyar nyelvű oldal, amely csak jó híreket gyűjt a világból. GitHub Pages: https://bermolnar.github.io/HAPPYHUB/
(a repó a GitHubon azóta a molnarxtamas fiókhoz került át).

## Hol tart
- Statikus frontend (`index.html`, `script.js`), adat: `data/news.json`.
- `scripts/fetch-news.mjs` (napi 3× GitHub Action) jóhír-RSS-ekből angol jelölteket gyűjt a `data/pending.json`-ba (API-kulcs nélkül).
  A fordítás kézi: munka közben lefordítom, majd `scripts/merge-translations.mjs` áthelyezi a `news.json`-ba. Csak rövid kivonat + link
  (szerzői jog).
- **Munka előtt mindig `git pull`** – a folyamat naponta commitol.

## Nyitott
- Borítóképek a hírkártyákra (RSS-ben nincs jól használható kép; og:image vagy kategóriánkénti illusztráció – szerzői jogi szempontból).
- Dizájn-visszajelzés a v1-re. A `pending.json` feltorlódott – fordítás és összefésülés.
