# AYUB PARFUM ERP (prototip)

Atir biznesi uchun boshqaruv tizimi prototipi: POS (butun flakon va razliv), ombor, filiallar,
mijozlar va qarzdorliklar, moliya, xodimlar (ish vaqti va bonus), hisobotlar, sozlamalar.

Bu **statik sayt**: bitta `index.html` fayl, build yoki server kerak emas.

## Mahalliy ishga tushirish
`index.html` ni brauzerda oching.

## Vercel'ga joylash
1. GitHub'da yangi repozitoriy yarating (masalan `ayub-parfum-erp`) va shu fayllarni yuklang.
2. https://vercel.com → **Add New → Project** → GitHub repozitoriyni tanlang.
3. Framework Preset: **Other**. Build Command va Output Directory bo'sh qoladi. **Deploy** bosing.
4. Har safar GitHub'ga yangi o'zgarish yuborsangiz (push), Vercel avtomatik yangilaydi.

## Muhim ogohlantirish (demo himoyasi)
- Ma'lumotlar (savdolar, xodimlar, davomat, PIN-kodlar) **har bir foydalanuvchining o'z brauzerida** saqlanadi.
  Bir qurilmadagi ma'lumot boshqasida ko'rinmaydi.
- Kirish PIN-kodi sahifa kodi ichida turadi, shuning uchun bu haqiqiy himoya emas.
  Boshlang'ich rahbar PIN-kodi: `888584`. Ommaga ochishdan oldin uni o'zgartiring.
- Haqiqiy ishlatish uchun server, ma'lumotlar bazasi va login kerak.
- Kompaniya telefonlari, manzillari, STIR va QR havolalari namunaviy.
