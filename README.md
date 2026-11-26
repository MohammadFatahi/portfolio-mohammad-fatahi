# وب‌سایت شخصی من

من محمد فتاحی هستم. این سایت را برای معرفی خودم و جمع کردن تمرین‌های دورهٔ بک‌اند پایتون ساخته‌ام.

[دیدن سایت](https://mohammadfatahi.github.io/portfolio-mohammad-fatahi/)

## صفحه‌ها

- `index.html`: معرفی کوتاه و عکس پروفایل
- `about.html`: دربارهٔ من و مسیر یادگیری
- `skills.html`: مهارت‌هایی که تمرین کرده‌ام
- `projects.html`: سه پروژهٔ پایتون، خروجی نمونه و لینک کدها
- `contact.html`: راه‌های ارتباط از طریق GitHub و ORCID

استایل مشترک در `css/style.css` است و منوی موبایل و دکمهٔ بازگشت به بالا در `js/script.js` نوشته شده‌اند.
سایت با HTML، CSS و کمی JavaScript ساخته شده و ابزار build یا کتابخانهٔ جانبی ندارد.

## اجرای محلی

می‌شود `index.html` را مستقیم در مرورگر باز کرد. برای اجرای سرور محلی هم:

```console
python -m http.server 8000
```

بعد آدرس `http://localhost:8000` را باز کنید.

## پروژه‌های معرفی‌شده

1. [Password Checker](https://github.com/MohammadFatahi/python-password-checker)
2. [Mini Store](https://github.com/MohammadFatahi/python-mini-store)
3. [Pet Shelter](https://github.com/MohammadFatahi/python-pet-shelter)

عکس پروفایل از حساب گیت‌هاب خودم گرفته شده است. تصاویر پروژه‌ها، خروجی اجرای نمونهٔ همان برنامه‌ها هستند؛ ورودی‌های آن‌ها آزمایشی‌اند.
در موبایل منو باز و بسته می‌شود. صفحه‌ها بدون JavaScript هم قابل استفاده‌اند.

## انتشار

در تنظیمات مخزن، بخش Pages، منبع انتشار `Deploy from a branch` و شاخهٔ `main` با پوشهٔ `/ (root)` انتخاب شده است.
