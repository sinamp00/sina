# 🛡️ SinaVPN (اندروید) — فیلترشکن نسل نوین ضدتحریم

<div dir="rtl">

[![Release](https://img.shields.io/github/v/release/sinamp00/sina?color=00F5A0&label=Latest%20Version&style=for-the-badge)](https://github.com/sinamp00/sina/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-00F5FF?style=for-the-badge)](https://github.com/sinamp00/sina)
[![License Security](https://img.shields.io/badge/Security-ECDSA%20P--256-B388FF?style=for-the-badge)](https://github.com/sinamp00/sina)
[![Website](https://img.shields.io/badge/Website-Live%20Page-FFB300?style=for-the-badge)](https://sinamp00.github.io/sina/)

**SinaVPN** یک کلاینت فوق‌پیشرفته و بومی اندروید برای عبور نفوذناپذیر از اختلالات شدید اینترنت و سیستم‌های بازرسی عمیق بسته‌ها (DPI) در ایران می‌باشد. این اپلیکیشن با تلفیق هسته هیبریدی به زبان Go، رابط کاربری شیشه‌ای متریال دیزاین ۳، و رمزنگاری آفلاین طراحی شده است.

---

## 📥 لینک‌های مستقیم دانلود نسخه رسمی (v2.5.0)

| نسخه فایل | نوع معماری پردازنده | حجم فایل | لینک دانلود مستقیم |
| :--- | :--- | :--- | :--- |
| **Universal (پیشنهادی)** | تمامی مدل‌ها و پردازنده‌ها (All Archs) | ۲۶.۱ مگابایت | [📥 دانلود مستقیم نسخه Universal](https://github.com/sinamp00/sina/releases/download/v2.6.0/SinaVPN-Universal-Release.apk) |
| **arm64-v8a (فوق سبک)** | گوشی‌های جدید ۶۴ بیتی (Snapdragon, Tensor...) | ۱۰.۵ مگابایت | [📥 دانلود مستقیم نسخه arm64](https://github.com/sinamp00/sina/releases/download/v2.6.0/SinaVPN-arm64-Release.apk) |

> 🌐 **صفحه وب‌سایت لایو**: [https://sinamp00.github.io/sina/](https://sinamp00.github.io/sina/)  
> 🔄 **بروزرسانی درون‌برنامه‌ای**: این اپلیکیشن به فایل `version.json` همین مخزن متصل بوده و آپدیت‌ها را به صورت خودکار به شما اطلاع می‌دهد.

---

## ✨ ویژگی‌های کلیدی نسخه ۲.۶ (iOS-Grade Overhaul)

### ۱. ارتقای پروتکل‌ها و حذف بخش گیمینگ
- **🌐 تانل ماسک (MASQUE HTTP/2)**: ترانسپورت پیش‌فرض ماسک روی **H2 (TCP)** با فرگمنتیشن ریز بسته‌های TLS (`16-32 بافر`) و تاخیر میکروثانیه‌ای جهت عبور پایدار از سیستم‌های فیلترینگ بدون قطعی UDP.
- **✨ پروتکل سینا (Sina-Stealth)**: اسکن هوشمند پاک‌ترین رله‌ها و تانل بدون نشت.
- **⚡ وارپ پلاس (WARP+)**: اتصال به شبکه رله‌های اختصاصی کلودفلر با پینگ فوق‌العاده پایین.
- **🛡️ وایرگارد پرو (WireGuard Pro)**: تانل پایدار بدون نشتی DNS با بالاترین نرخ انتقال داده.
- **🚀 پاکسازی حالت گیمینگ**: حذف متغیرهای ناکارآمد و تمرکز کامل منابع سخت‌افزاری بر سرعت و پایداری شبکه.

### ۲. طراحی در سطح سیستم‌عامل iOS (iOS-Grade Design)
- **لغزنده کپسولی شناور (Sliding Pill Segmented Control)**: جابجایی نرم و انیمیشن فیزیکی زیر گزینه‌های انتخابی اسکن و پروتکل.
- **امواج و رادار ۳۶۰ درجه در دکمه اتصال**: چرخش شیدر سونار در اتصال و ۳ هاله امواج شیشه‌ای متحدالمرکز در اتصال پایدار.
- **نمودار زنده تلپاتی داده (Live Sparkline Waveform)**: ترسیم منحنی‌های نرم مکعبی بزیه متناسب با پالس مصرف داده.
- **شیت‌های مودال از پایین صفحه (iOS Bottom Sheet Modals)**: دیالوگ‌های حساب، لایسنس و تم با دستگیره کششی استاندارد و لغزش نرم.
- **هاله‌های محیطی داینامیک (Ambient Aurora Glow Orbs)**: تابش محو گرادیان شعاعی هماهنگ با تم انتخابی در پس‌زمینه.

### ۳. پالت رنگی ۹ گانه نئونی و رابط کاربری Liquid Glass
- سبز سایبر زمردی (`Cyber Emerald • #00F5A0`)
- نئون سایبر فیروزه‌ای (`Electric Cyan • #00F5FF`)
- آبی یاقوتی رویال (`Royal Sapphire • #0091EA`)
- بنفش آمیتیست (`Amethyst Violet • #B388FF`)
- رز نئونی سان‌ست (`Neon Rose • #FF2A85`)
- کهربایی گرم (`Solar Amber • #FFB300`)
- طلایی سلطنتی ۲۴ عیار (`Imperial Gold • #FFD700`)
- نئون لایم فسفری (`Toxic Lime • #A3E635`)
- قرمز تاکتیکال نظامی (`Crimson Stealth • #FF5252`)

### ۳. اسکنر هوشمند ۴ حالته (Symmetric Scan Bar)
- ⚡ **توربو (Turbo)**: اسکن سریع در کمترین زمان.
- ⚖️ **متعادل (Balanced)**: توازن میان سرعت کشف و دقت رله.
- 🕶️ **استتار (Stealth)**: فرگمنتیشن شدید برای شبکه‌های به شدت محدود.
- 🛡️ **نفوذناپذیر (Ironclad)**: کاوش عمیق پاک‌ترین Anycast IPهای فعال اپراتورهای ایران.

### ۴. امنیت لایسنسینگ آفلاین (Zero-Log ECDSA)
- بدون نیاز به ایمیل، شماره موبایل یا ثبت نام.
- اعتبارسنجی آفلاین کلیدها با رمزنگاری منحنی بیضوی **ECDSA NIST P-256**.
- گاوصندوق سخت‌افزاری شناسه دستگاه (**HWID Vault**) مقاوم در برابر پاک شدن داده‌ها.

---

## 🤖 ربات تلگرام و دریافت اشتراک

برای دریافت تست رایگان یا خرید لایسنس، به ربات تلگرام رسمی متصل شوید:
- **ربات تلگرام**: [@Sina_mp_VPNbot](https://t.me/Sina_mp_VPNbot)

---

## 🔒 اعتبارسنجی سلامت فایل‌ها (SHA-256 Checksums)

```text
e04883dc2a986f025a3083a8590f57064ca505dc07b9368ee515a83fbfe1e2ed  SinaVPN-arm64-Release.apk
d2c0bf0a07db62d6771f1da1099014ebf4c2fc228003a8e34336880751b7b1b1  SinaVPN-Universal-Release.apk
```

---

## 📄 راهنمای نصب

1. فایل نصبی `APK` مناسب گوشی خود را از جدول بالا دانلود کنید.
2. در صورتی که اخطار امنیتی نمایش داده شد، گزینه **Install from this source** یا **Install anyway** را انتخاب نمایید.
3. برنامه را باز کرده و دکمه اتصال مرکزی را لمس نمایید.

</div>
