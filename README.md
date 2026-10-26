# ROYAL music school — Vokal kursi lendingi

Andijondagi ROYAL music school vokal kursi uchun bir sahifali sayt. Bitta `index.html` fayl: CSS, JS va rasmlar ichida, tashqi bog'liqlik faqat Google Fonts (Inter).

- Tillar: UZ / RU (yuqori o'ngdagi tugma)
- Qorong'i va yorug' rejim
- Hero'da mikrofon orqali ovoz tahlili (HTTPS va mikrofon ruxsati kerak; bo'lmasa pianino varianti chiqadi)
- Yozilish formalari `POST /api/lead` ga JSON yuboradi: `{name, phone, course, plan, source, lang}` — bu manzil serverda bo'lishi kerak (GitHub Pages'da forma ishlamaydi, telefon raqami ko'rsatiladi)

Joylash: `index.html` ni istalgan statik hostingga qo'ying yoki GitHub Pages'ni yoqing (Settings → Pages → Deploy from a branch → main / root).
