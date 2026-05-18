# CMYK26 Booklet Audit — Complete Summary
Date: May 18, 2026

## What We Did

### 1. Booklet QR Code Audit
- Scanned 100-page CMYK+ Booklet PDF for embedded QR codes
- Decoded **45 of 48** student portfolio URLs (93.75%)
- Used: pyzbar (34 decoded) + zxing-cpp + full-page 300 DPI rendering (+11 more)
- 3 students had NO QR code on their booklet page

### 2. Corrected Year Assignments
Booklet section labels (CREATE/MEASURE/YIELD/KNOW/PROGRESS) did NOT match actual year groups.
User provided correct assignments:
- Maya Abu Samra + Jonathan Edora Sarmiento Jr → Year 3 (booklet said Y4)
- Krupa Cicily Thomas, Tanisha Dugar, etc. → Year 4 (booklet said Y5)

### 3. Portfolio Downloads
- Behance, qr.codes, qr.link, issuu, scanned.page — all expired/blocked
- Only Google Drive links were downloadable (4 PDFs)
- User uploaded additional PDFs directly
- Discovered ZIP bundle with 7 image-based portfolios

---

## New Students Added This Session (11 total)

### Year 3 — 1 new student

| Student | Source | Format | Size | Pages |
|---|---|---|---|---|
| **Abdullah Ejaz** | User upload | PDF | 40.9 MB | 33 |

### Year 4 — 10 new students

| Student | Source | Format | Size | Pages |
|---|---|---|---|---|
| **Adithya Biju** | User upload | PDF | 223.8 MB | 70 |
| **Zahra Yakubu Daura** | User upload | PDF | 260.4 MB | 17 |
| **Zoran Shawkat** | User upload | PDF | 14.7 MB | 30 |
| **Tanisha Dugar** | ZIP bundle | Image gallery | — | 39 images |
| **Alexandre Lamare-Skyrme** | ZIP bundle | Image gallery | — | 30 images |
| **Ahmad Fiqry Fuad** | ZIP bundle | Image gallery | — | 18 images |
| **Hannah Fernando** | ZIP bundle | Image gallery | — | 7 images |
| **Karina Dhakal** | ZIP bundle | Image gallery | — | 19 images |
| **Krupa Cicily Thomas** | ZIP bundle | Image gallery | — | 16 images |
| **Muath Fahad** | ZIP bundle | Image gallery | — | 34 images |

### Existing Students — Portfolio PDFs Added (4)

| Student | Year | Source | Format | Size |
|---|---|---|---|---|
| Thant Sin Linn Myint | Y3 | Google Drive | PDF | 76 MB |
| Yola Ajluni | Y3 | Google Drive | PDF | 21 MB |
| Muhammed Aathik | Y2 | Google Drive | PDF | 70 MB |
| Vedaang Chavan | Y2 | Google Drive | PDF | 49 MB |

---

## Build Status: 33 Students (was 22)

### Year 1 (8 students — unchanged)
All QR codes in booklet pointed to generic issuu.com/ridxs — no individual portfolios.
Athena, Gulnaz, Laura, Mohammed Naveed, Pearla, Sumayyah, Zahra, Zuriel

### Year 2 (9 students — unchanged, 2 got PDFs)
Aleksandra, Amna, Atharsh, Jamshedzoda, Medha, **Muhammed Aathik** ✅ PDF added,
Nursultan, **Vedaang Chavan** ✅ PDF added, Yomna

### Year 3 (8 students — 4 with portfolios)
✅ Abdullah Ejaz (NEW — user upload, 40.9MB)
✅ Aina Shamsudeen (existing)
✅ Halimah Sameer (existing)
✅ Jonathan Edora Sarmiento Jr (existing)
✅ Thant Sin Linn Myint (PDF added, 76MB)
✅ Yola Ajluni (PDF added, 21MB)
❌ Maya Abu Samra (link expired)
❌ Tamara Mikleova (link expired)

### Year 4 (12 of 19 students — 10 NEW)
✅ Adithya Biju (NEW — user upload, 223.8MB)
✅ Alexandre Lamare-Skyrme (NEW — ZIP bundle, 30 images)
✅ Ahmad Fiqry Fuad (NEW — ZIP bundle, 18 images)
✅ Hannah Fernando (NEW — ZIP bundle, 7 images)
✅ Karina Dhakal (NEW — ZIP bundle, 19 images)
✅ Krupa Cicily Thomas (NEW — ZIP bundle, 16 images)
✅ Muath Fahad (NEW — ZIP bundle, 34 images)
✅ Tanisha Dugar (NEW — ZIP bundle, 39 images)
✅ Zahra Yakubu Daura (NEW — user upload, 260.4MB)
✅ Zoran Shawkat (NEW — user upload, 14.7MB)
❌ Ndiogou Mamour Ka (qr.codes expired)
❌ Janice Fernandes (qr.codes expired)
❌ Mikhail Bykov (qr.codes expired)
❌ Tala Mohamed (no QR on booklet page)
❌ Timon Madiba Ayiba Duba (no QR on booklet page)
❌ Taiba Sayed (qr.link expired)
❌ Ridhima Purohit (no QR on booklet page)
❌ Umar Siddiqui (not in booklet)
❌ Ronit Sehgal (not in booklet)

### Masters (0 of 5 — all still missing)
❌ Majd Bayakli (qr.codes expired)
❌ Manaal Ganguli (qr.link expired)
❌ Parthavi Parikh (generic issuu link)
❌ Zaid Inamdar (generic issuu link)
❌ Ella-Jade Chudleigh-Lyle (qr.codes expired)

---

## Git Commits (3 commits ready for push)

```
[new] Add 8 student portfolios from ZIP bundle + Zoran Shawkat PDF
[new] Add Zahra Yakubu Daura (Year 4) portfolio
[new] Add 2 students + 4 portfolio PDFs from booklet QR audit
```

## Still Missing: 14 students
- Year 3: 2 (Maya Abu Samra, Tamara Mikleova)
- Year 4: 7 (Ndiogou, Janice, Mikhail, Tala, Timon, Taiba, Ridhima, Umar, Ronit)
- Masters: 5 (Majd, Manaal, Parthavi, Zaid, Ella-Jade)
