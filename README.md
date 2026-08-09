# Jastip Premium — Static Site

Website katalog jastip (jasa titip) Jakarta Premium Outlet.
Live: https://jastippremium.netlify.app

## Struktur

- `index.html` — seluruh situs dalam satu file (CSS + JS inline, data produk di `allProducts`)

## Cara Update

1. Edit `index.html` (atau ganti dengan versi terbaru dari Netlify drag-and-drop).
2. Commit & push ke `main`:

   ```bash
   git add index.html
   git commit -m "update katalog"
   git push origin main
   ```

3. Netlify auto-deploy. Cek status di https://app.netlify.com/projects/jastippremium

## Catatan

- Foto produk dimuat dari URL eksternal (bukan file di repo ini).
- Tidak ada build step — Netlify publish langsung file di root.
- Repo lama `jastippremium` (scaffold Astro + Sanity) sengaja dibiarkan terpisah.
