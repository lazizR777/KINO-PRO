# 🎬 KINO PRO — Ko'p Sahifali Premium Kinoteatr va IMAX Chipta Kassasi

**KINO PRO** — zamonaviy animatsiyalar, 3D kartochkalar, AI kayfiyat tavsiyachisi, IMAX zalidan jonli o'rindiq bronlash tizimi, sharhlar va ko'p sahifali arxitekturaga ega to'liq veb-loyiha.

## 📂 Loyiha Tuzilmasi
- `index.html` — Asosiy sahifa (Hero slayder, AI tavsiyachi, Trendlar, Katalog, IMAX kassa, Aktyorlar, Premyera taymeri, Obuna va FAQ).
- `pages/catalog.html` — To'liq filmlar, seriallar va animelar katalogi sahifasi.
- `pages/series.html` — Seriallar va Anime uchun maxsus sahifa.
- `pages/tickets.html` — Kinoteatr IMAX zalidan o'rindiq band qilish sahifasi.
- `css/style.css` — 3D perspektiva, Glassmorphism, neon effektlar va barcha animatsiyalar.
- `js/movies.js` — 16 ta film, serial va anime hamda mashhur aktyorlar ma'lumotlar bazasi.
- `js/app.js` — Barcha interaktiv mexanizmlar, `localStorage` watchlist, sharhlar va chipta hisob-kitobi.
- `.github/workflows/deploy.yml` — GitHub'ga yuklaganda avtomatik **GitHub Pages** deploy qilish fayli.
- `vercel.json` va `netlify.toml` — Vercel va Netlify uchun tayyor sozlamalar.

## 🚀 GitHub va Deploy Qilish
1. GitHub'da `kino-pro` nomli yangi repository yarating.
2. Loyiha fayllarini yuklang:
   ```bash
   git init
   git add .
   git commit -m "Deploy KINO PRO full project"
   git branch -M main
   git remote add origin https://github.com/USERNAME/kino-pro.git
   git push -u origin main
   ```
3. **GitHub Pages** avtomatik ishga tushishi uchun Repository → **Settings → Pages → Source: GitHub Actions** ni tanlang.
4. Yoki **Vercel** / **Netlify** orqali repository'ni tanlab 1 tugma bilan deploy qiling.
# KINO-PRO
