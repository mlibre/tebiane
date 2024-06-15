# تبیان قران

این برنامه یک ربات تلگرام است، برای جستجوی آیات قرآن کریم به همراه تعدادی از ترجمه ها و تفسیر های(به زودی) فارسی. شما می‌توانند کلمه یا جمله مورد نظر رو جستجو کنید و نتایج مرتبط رو ببینید.

این برنامه در حال حاضر فقط به شکل ربات تلگرام در دسترس قرار داره. برای شروع به یکی از آدرس های زیر برین

* Link: <https://t.me/TebianeBot>
* Telegram Usernmae: @TebianeBot

![Tebiane](./image.png)

## ویژگی‌ها

* جستجوی نسبی (فازی) در آیات - به این معنی که لازم نیست کلمات به ظور دقیق یا کامل وارد بشن
* نمایش ترجمه‌های مختلف - شامل ترجمه ی اقای مکارم شیرازی، فولادوند و ...ا
* نمایش تفسیر آیات(به زودی)
* گردش بین آیات و نتایج جستجو

## نصب و راه‌اندازی

اگه میخواید این ربات رو به صورت شخصی استفاده کنین یا تغییری روش بدین مراحل زیر رو دنبال کنین

### پیش‌نیازها

برای اجرای این پروژه به موارد زیر نیاز دارید:

* Node.js (نسخه 18 یا بالاتر)
* ربات تلگرام و توکن دسترسی

### کلن و اجرا

مخزن را کلن کنید و پکیج های مربوط رو نصب کنید:

```bash
git clone https://github.com/mlibre/Tebiane
cd Tebiane
npm install
```

### پیکربندی تنظیمات ربات

فایل `.env.example` رو به نام `.env` تغییر دهید:

برنامه هنگام شروع شدن این فایل رو میخونه و توکن ربات شما و تنظیمات پروکسی رو برای اجرای ربات استفاده میکنه. نمونه محتویات این فایل به این شکله:

```env
TELEGRAM_BOT_TOKEN=توکن-ربات-شما
PROXY=http://127.0.0.1:2081
```

### اجرای پروژه

برای اجرای پروژه، دستور زیر را وارد کنید:

```bash
npm start

# یا به صورت مستقیم فایل اصلی رو اجرا کنید
node src/main.js
```

<!-- * **search** - هر چه دوست دارید بنویسید
* **resources** - نمایش منابع -->