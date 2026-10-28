# Kolloid Detektiv

Ochiq dars uchun vizual ta'limiy o'yin: **Kolloid eritmalarning koagullanishi** (jelatinani degidratlash yo'li bilan koagullash), 5-laboratoriya ishi.

**Onlayn:** https://hayitali21.github.io/kolloid-detektiv/

## Ishga tushirish

- `index.html` faylini ikki marta bosing — brauzerda ochiladi. Internet kerak emas.
- `F` — to'liq ekran (proyektor uchun 1366×768 ga moslangan).

## Bo'limlar (jami 22 daqiqa)

| № | Bo'lim | Vaqt |
|---|---|---|
| 1 | Sirli savol | 2 daq |
| 2 | Animatsiya va ikki qalqon | 5 daq |
| 3 | Qalqonni sina | 4 daq |
| 4 | Guruhlarga ajrat (asosiy o'yin) | 6 daq |
| 5 | Viktorina | 3 daq |
| 6 | Yakun | 2 daq |

Qo'shimcha: Asosiy menyudagi **⭐ Bonus** — "O'z probirkangni yasa".

## Klaviatura

| Tugma | Vazifa |
|---|---|
| `→` / `←` | Keyingi / oldingi bo'lim |
| `1`–`5` | Shu jamoaga +1 ball |
| `Shift` + `1`–`5` | Shu jamoadan −1 ball |
| `T` | Taymer start / pauza |
| `P` | Dars rejimi |
| `F` | To'liq ekran |
| `?` | Tugmalar ro'yxati |

## Sozlash

6-probirkaning pH qiymati kod boshidagi bitta o'zgaruvchidan olinadi:

```js
const TUBE6_PH = 4.1; // qo'llanma qiymati. Hisob bo'yicha ≈4.46 — o'qituvchi tasdiqlaydi
```

Jamoa nomlari, ballar va joriy bo'lim brauzerda (`localStorage`) saqlanadi.

> Animatsiyalar — jarayonning soddalashtirilgan ta'limiy modeli, haqiqiy o'lchov natijasi emas.
