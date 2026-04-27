# 至尊聖度母四壇城供養儀軌 · Ārya Tārā Sadhana

**The Sadhana of the Four-Mandala Ritual of Ārya Tārā — A Trilingual Parallel Edition**
*Compiled and Edited by Khenpo Kunga Rinchen · 堪布 根嘎仁波切 編校*

A beautiful, single-page online puja display with Tibetan · English · Chinese parallel text, designed for online practice and group recitation.

---

## ✦ What's inside

| File | Purpose |
|---|---|
| `index.html` | The complete puja — fully self-contained, no build step needed |
| `README.md` | This file |

The puja is structured as **20 sections** with a sticky side-index for quick navigation:

1. **Opening** — Title page, Lineage Supplication, Consecration of Offerings, Refuge & Bodhicitta, Four Immeasurables
2. **Mandala** — Invocation of Buddhas, Prostration to Three Jewels, First Mandala, Invocation of Tārā, Offerings to Tārā, Second Mandala
3. **The 21 Praises to Noble Tārā** — Each praise on its own anchor with Roman-numeral medallions
4. **Mantra & Aspirations** — Seven-Limb Prayer, Root Mantra (OṂ TĀRE TUTTĀRE TURE SVĀHĀ), six aspiration verses, 100-Syllable Mantra
5. **Conclusion** — Forgiveness, Request to Remain, Dedication, Auspiciousness verses, Final Auspiciousness, Colophon

---

## ✦ Design notes

- **Aesthetic** — Warm parchment palette echoing the original PDF, with sacred gold accents, a subtle noise-textured background, and a refined editorial layout.
- **Typography** —
  - *Tibetan*: Noto Serif Tibetan
  - *Chinese*: Noto Serif TC
  - *English / phonetics*: EB Garamond + Cormorant Garamond (italics)
- **Navigation** — Sticky side index on desktop, slide-out drawer on mobile (`☰ Index` button top-left)
- **Reading progress bar** at the very top
- **"Back to top" button** appears after scrolling
- **Smooth scroll-anchored sections** with subtle fade-in on entry
- **Active-section highlighting** in the index as you scroll
- **Print-friendly** — clean print layout (sidebar/UI hidden) so practitioners can print their own copy
- **Mobile responsive** — single-column layout below 900px

All deity images from the original PDF are *not* embedded (since they're copyrighted illustrations). The page is text-focused and runs anywhere with no asset dependencies beyond Google Fonts.

---

## ✦ How to deploy to your website

### Option 1 — Drop into any web host
Upload `index.html` to your web root (or any folder) and visit it. That's it.

```
your-website.com/tara-puja/index.html
```

### Option 2 — GitHub Pages
1. Create a new GitHub repo (e.g. `tara-puja`)
2. Upload `index.html` and `README.md`
3. Settings → Pages → Source: `main` / root
4. Visit `https://yourname.github.io/tara-puja/`

### Option 3 — Netlify / Vercel / Cloudflare Pages
Drag the folder into the deploy zone. Done in 30 seconds.

### Option 4 — WordPress / Wix / Squarespace
Use a "custom HTML" or "embed" block and paste the entire contents of `index.html` (or upload it as a static page).

---

## ✦ Customising

All colors, fonts, and spacing are CSS variables at the top of `index.html`:

```css
:root {
  --paper:    #f4ead5;   /* parchment background */
  --gold:     #b08338;   /* primary gold accent */
  --gold-deep:#8a5e21;   /* darker gold */
  --jade:     #5d7a5a;   /* subtle green wash */
  --vermilion:#a64030;   /* reserved for emphasis */
  --ink:      #2b211a;   /* main text */
  ...
}
```

Change these once and the entire palette updates.

To **add or rearrange verses**: each verse is a `<article class="verse">` block with up to four `<p>` lines (`.tib`, `.phon`, `.en`, `.zh`). Copy any block as a template.

To **add a new section**: copy any `<section class="section" id="...">` block, give it a unique `id`, and add a matching `<a href="#id">` entry in the sidebar `<aside class="toc">`.

---

## ✦ For online puja sessions

A few practical tips:

- **Screen-share** the page in Zoom/Google Meet — use `Ctrl/Cmd + scroll` to enlarge text for readers
- **Browser zoom** is honoured (the layout reflows gracefully)
- **Dark / light** — the parchment palette is gentle on eyes; no dark-mode flicker during long sessions
- **Print** a hard-copy backup with `Ctrl/Cmd + P` — the print stylesheet hides the sidebar and progress bar automatically
- **Share specific verses** by copying the URL with the `#anchor` (e.g. `…/index.html#praise-7` jumps directly to the 7th praise)

---

## ✦ Credits

- Sadhana compilation & editing: **Khenpo Kunga Rinchen** (堪布 根嘎仁波切)
- Web edition layout: prepared from the trilingual InDesign brief
- Fonts: [Noto Serif Tibetan](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan), [Noto Serif TC](https://fonts.google.com/noto/specimen/Noto+Serif+TC), [EB Garamond](https://fonts.google.com/specimen/EB+Garamond), [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) — all open-source via Google Fonts

---

> སརྦ་མངྒ་ལཾ
> *May all beings find liberation*
> 願一切眾生獲得解脫
