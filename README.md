# Sass-Sample

نمونه‌ی پروژه‌ی Sass با معماری 7-1 (متغیرها، میکسین‌ها، توابع، پلیس‌هولدرها و ماژول‌ها) به همراه صفحه‌ی دموی فارسی و راست‌به‌چپ.

## راهنما

### دستورات کامپایل

1. کامپایل خودکار با هر تغییر (حالت Watch):

   `npm run sass:watch`

2. خروجی فشرده برای انتشار (Production):

   `npm run sass:compressed`

### ساختار پروژه

```
├── index.html          # صفحه‌ی دموی فارسی و راست‌به‌چپ
├── package.json        # اسکریپت‌های کامپایل Sass
├── README.md
├── sass/
│   ├── style.scss          # فایل اصلی؛ تمام قوانین Sass
│   ├── _variables.scss     # متغیرها، هفت نوع داده، پرچم !default
│   ├── _mixins.scss        # میکسین‌ها: آرگومان، مقدار پیش‌فرض، ... و @content
│   ├── _functions.scss     # توابع سفارشی: @function و @return
│   ├── _placeholders.scss  # پلیس‌هولدرها (%) برای @extend
│   ├── _abstracts.scss     # @forward (بسته‌بندی ماژول‌ها)
│   └── _reset.scss         # ریست CSS (نمونه‌ی فایل پارشال)
└── css/
    ├── style.css           # خروجی کامپایل‌شده (این فایل را دستی ویرایش نکنید!)
    ├── style-compressed.css  # نسخه‌ی فشرده برای انتشار
    └── style.css.map       # سورس‌مپ برای دیباگ در مرورگر
```