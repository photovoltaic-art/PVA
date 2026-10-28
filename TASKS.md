# PVA — tasks

Tasks for the PVA organisation itself: the manifesto, the website and the organisation on GitHub. Tasks for SUNDIAL live in its own repo ([FORK-TASKS.md](https://github.com/photovoltaic-art/SUNDIAL/blob/main/FORK-TASKS.md)).

> Updated 22 Oct 2026.

## Domain

- [ ] **Register `photovoltaic.art`.** Check the renewal price before paying: some .art names renew at a premium rate.
- [ ] Check `fotovoltaica.art` (Italian front door, redirect only). Register only if cheap.
- [ ] **Verify the domain for the organisation:** organisation Settings → Pages → verified domains (a DNS TXT record). This stops anyone else pointing a GitHub site at the domain or its subdomains.
- [ ] DNS for the manifesto site: `photovoltaic.art` → GitHub Pages for this repo (A/AAAA records for the apex, `www` as a CNAME).
- [ ] DNS for SUNDIAL Bosa: `bosa.photovoltaic.art` → CNAME to `photovoltaic-art.github.io`, set as the custom domain in the SUNDIAL repo's Pages settings.
- [ ] Turn on **Enforce HTTPS** in both repos once the certificates are issued.

## Single-page site (photovoltaic.art)

- [x] **First draft, English only (28 Oct 2026):** `docs/index.html`, the logo, the statement, a short text on retired panels, the nine principles, works (SUNDIAL; no. 2 shown only as "in design"), make your own. Enable Pages from `docs/` (Settings → Pages).
- [ ] **One page, built from `MANIFESTO.md`:** the opening, the nine principles, the works index, "make your own". Italian and English with a language switch; no tracking, no cookies, no external scripts beyond fonts.
- [ ] Publish with GitHub Pages from this repo (`docs/index.html`, or the repo root), custom domain `photovoltaic.art`.
- [ ] Link SUNDIAL's entry to `bosa.photovoltaic.art` once that site is live, and to the SUNDIAL repo.
- [ ] A short footer: the organisation link, and "Draft · not yet licensed for reuse" until the release.

## Manifesto

- [ ] Native Italian reader checks the tone of the Italian version.
- [ ] Final read of the nine principles against SUNDIAL as built (after the field test).

## Organisation

- [ ] Create a `.github` repo with `profile/README.md`: a short version of the manifesto shown on the organisation's front page.
- [ ] Turn on two-factor authentication for every owner.
- [ ] Add a second owner when there is someone trusted to hold it.

## Works

- [x] **No. 2, SUNSET:** linked from the README and the manifesto's works table (22 Oct 2026). Make its repository public (Settings → General → Danger Zone → Change visibility). Its tasks live in its own repo (`TASKS.md`). GO TO BED, the concept it grew from, moved there on 22 Oct 2026 with its format, carry test and test bed.

## Growth model ([GROWTH.md](GROWTH.md))

- [ ] Terms of node ownership from year 2: given, adopted or paid for; when an owner leaves (GROWTH.md 3.4).
- [ ] Upkeep, insurance and permissions with nine owners.
- [ ] Whether SUNDIAL's annual event continues after year 1.
- [x] The manifesto's closing line (27 Oct 2026): *Like the sun that powers them, the works are made to be held in common* / *Come il sole che le alimenta, le opere nascono per essere un bene comune*.
- [ ] How PVA's authorship is described once the works are a commons.
- [x] Growth by forking, nine panels per town, never linked (GROWTH.md 5, 27 Oct 2026).
- [ ] A list of towns on photovoltaic.art, for forks that send their link.
- [x] The path in GROWTH.md: one-panel artist's proof (SUNDIAL only, PVA's, outside the edition), nine-panel SUNDIAL, the same nine as SUNSET (27 Oct 2026).
- [x] Completion criteria and the node catalogue (GROWTH.md 6, 27 Oct 2026): each repo complete when trialled and reproducible, then licensed; SUNSET licensed after further nodes are built and tested.

## Manifesto (22 Oct 2026)

- [x] Principle 1 rewritten so it fits both works: the panel stays in view; what is added serves what it does with the sun.
- [x] Principle 3: a battery may store the panel's own sun, never the grid's.
- [x] Principle 4 (27 Oct 2026): works "wake with the light and rest when their sun runs out", matching principle 3's stored sun.
- [x] The first line (27 Oct 2026): *Every PVA public installation is an edition of nine panels: never more, never less* / *Ogni installazione pubblica PVA è un'edizione di nove pannelli: mai di più, mai di meno.*
- [ ] Native Italian reader checks the rewritten principles 1, 3 and 4, the SUNSET row, the first line and the closing line.

## Release (last)

- [ ] Licence for the manifesto text (CC BY 4.0, matching SUNDIAL's texts) when SUNDIAL is released.
