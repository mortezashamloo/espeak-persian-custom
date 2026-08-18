# eSpeak Persian Custom

پچ و بیلد شخصی‌سازی‌شده برای استفاده بهتر از eSpeak / eSpeak NG با زبان فارسی.

## بیلد ۳۲بیتی eSpeak NG 1.51 (با پچ fa → en-us)

این ریپو یک GitHub Actions دارد که نسخهٔ ۳۲بیتی eSpeak NG 1.51 را با پچ زیر می‌سازد:

- وقتی زبان فعلی فارسی باشد، کلمات انگلیسی با لهجهٔ **آمریکایی (en-us)** خوانده می‌شوند (به جای بریتیش).

### نحوه اجرا

1. برو به تب **Actions** در همین ریپو:
   https://github.com/mortezashamloo/espeak-persian-custom/actions

2. workflow به نام **Build eSpeak NG 32-bit (fa → en-us)** را انتخاب کن.

3. روی **Run workflow** کلیک کن.

4. بعد از اتمام بیلد، در بخش **Artifacts** فایل `espeak-ng-32bit-fa-en-us-1.51` را دانلود کن.

5. فایل `espeak.dll` داخل آن را در مسیر زیر کپی کن:
   ```
   C:\Program Files (x86)\NVDA\synthDrivers\espeak.dll
   ```

### پچ

فایل پچ در مسیر `patches/fa-en-us-1.51.patch` قرار دارد.

---

## نسخهٔ کلاسیک eSpeak 1.48.15 (قبلی)

این ریپو در ابتدا برای نسخهٔ کلاسیک eSpeak 1.48.15 با بهبودهای فارسی ساخته شده بود.
