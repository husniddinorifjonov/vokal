# ROYAL music school — Vokal kursi lendingi

Andijondagi ROYAL music school vokal kursi uchun bir sahifali sayt. Bitta `index.html` fayl: CSS, JS va rasmlar ichida, tashqi bog'liqlik faqat Google Fonts (Inter).

- Tillar: UZ / RU (yuqori o'ngdagi tugma)
- Qorong'i va yorug' rejim
- Hero'da mikrofon orqali ovoz tahlili (HTTPS va mikrofon ruxsati kerak; bo'lmasa pianino varianti chiqadi)
- Yozilish formalari Google Apps Script web-ilovasiga (`LEAD_URL`, `/exec`) JSON yuboradi: `{name, phone, course, plan, form, lang, page}`. Skript arizani Telegram'dagi RoyalMusicBot'ga jo'natadi. Bot tokeni sahifada yo'q — u skriptning Script properties (`TG_TOKEN`) ichida turadi.

Joylash: GitHub Pages (Settings → Pages → Deploy from a branch → main / root).
