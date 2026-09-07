# Build Ilawe Together

A one-page site presenting the community service record of **Prince Dr. Jerome Adegoke Akinola** — FCA · FCTI · FCILRMN · MJF · NLCF — and his vision and mission for the Stool of Alawe of Ilawe-Ekiti, Ekiti State, Nigeria.

## Contents

The page runs in one continuous sequence:

1. **The Record, In Figures** — 22 years of the Adegoke Akinola Awards, ~40 youths placed in employment, 14 students returned to the WASC examination, the 2011 naming of Adegoke Akinola-Adefolalu House
2. **Two Standing Commitments** — Giving Back to Ilawe-Ekiti; Empowering People & Families
3. **Evidence** — photographs and film of the library furniture, sports jerseys, sports equipment, the Mathematics prize, and NYSC accommodation
4. **Recognition** — the 2011 house naming and the 2025 letters from the Ekiti State Ministry of Education and the Teaching Service Commission
5. **Vision and Mission as Alawe** — the full statement and its eight pillars
6. **Commitment** — closing declaration

## Structure

```
index.html      the entire page — markup and styles, no build step
assets/         photographs, video, and video posters
```

There is no framework and no bundler. Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
```

## Publishing with GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.

## Design notes

- **Palette** — indigo-black `#111a30` for the processional bands, warm parchment `#f7f2e6` for reading, oxblood-coral `#8e2a22` and antique gold, drawn from Yoruba coral beadwork and indigo aso-oke. Light and dark themes are both defined.
- **Type** — Bodoni Moda (engraved display), Marcellus SC (inscriptional capitals), Spectral (body), served from Google Fonts.
- **Motif** — section dividers are a beadwork rule of alternating gold and coral dots.
- Media is optimised for the web; the two films were re-encoded from 10.3 MB to 3.0 MB.
