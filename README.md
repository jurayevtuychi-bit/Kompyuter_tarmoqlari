# Kompyuter Tarmoqlari — Interaktiv Mobil Ilova (Android APK)

Ushbu repozitoriy "Kompyuter tarmoqlari" fanining barcha 12 ta nazariy mavzusi, 12 ta amaliy mashg'uloti va 8 ta Cisco Packet Tracer laboratoriya topshiriqlarini o'z ichiga oluvchi to'liq avtonom mobil ilovadir.

## Ilovaning asosiy imkoniyatlari:
- **Ochiq havorang zamonaviy dizayn** (ko'zni charchatmaydigan, yengil interfeys).
- **12 ta nazariy mavzu va 120 ta test savoli** (har bir mavzuda 10 tadan savol).
- **Variantlarning tasodifiy almashinuvi (Dynamic Shuffle)** — har safar test topshirilganda A, B, C, D variantlari yangicha ketma-ketlikda chiqadi.
- **Bosqichma-bosqich qat'iy o'tish (100% Gating)** — 1-mavzu testini 100% bajarmaguncha 2-mavzu ochilmaydi (... va shu tartibda 12-mavzugacha).
- **25 ta savoldan iborat Yakuniy Nazorat Testi**.
- **Foydalanuvchi shaxsiy kabineti** va kurs yakunida beriladigan **QR-kodli rasmiy Sertifikat**.

---

## GitHub Actions orqali APK faylni avtomatik yuklab olish:

1. **GitHub da yangi repozitoriy oching**:
   - `github.com` ga kiring va **New repository** tugmasini bosing (masalan, `kompyuter-tarmoqlari-app`).
   - Repozitoriyni **Public** qilib tanlang va **Create repository** ni bosing.

2. **Fayllarni yuklang**:
   - Ushbu `.zip` arxiv ichidagi barcha fayl va papkalarni (`.github`, `www`, `package.json`, `capacitor.config.json`, `README.md`) yangi repozitoriyingizga yuklang (`git push` yoki to'g'ridan-to'g'ri veb-brauzer orqali `Upload files`).

3. **APK ni yuklab oling**:
   - Repozitoriyingizdagi **Actions** bo'limiga o'ting.
   - **Build Android APK** jarayoni avtomatik boshlanadi (2-4 daqiqa davom etadi).
   - Jarayon yashil belgi bilan tugagach, sahifa pastidagi **Artifacts** bo'limidan **KompyuterTarmoqlari-APK** arxivini bosing.
   - Yuklab olingan arxiv ichidagi `app-debug.apk` faylini Android smartfoningizga o'rnating!
