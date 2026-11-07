## راهنما

### دستورات کامپایل

1. کامپایل خودکار با هر تغییر (حالت Watch):

   `npm run sass:watch`

2. خروجی فشرده برای انتشار (Production):

   `npm run sass:compressed`

### ساختار پروژه

```
sass/
├── style.scss          # فایل اصلی؛ تمام قوانین Sass
├── _variables.scss     # متغیرها، هفت نوع داده، پرچم !default
├── _mixins.scss        # میکسین‌ها: آرگومان، مقدار پیش‌فرض، ... و @content
├── _functions.scss     # توابع سفارشی: @function و @return
├── _placeholders.scss  # پلیس‌هولدرها (%) برای @extend
├── _abstracts.scss     # @forward (بسته‌بندی ماژول‌ها)
├── _reset.scss         # ریست CSS (نمونه‌ی فایل پارشال)
│
├── index.html          # صفحه‌ی دموی فارسی و راست‌به‌چپ
└── css/
    └── style.css       # خروجی کامپایل‌شده (این فایل را دستی ویرایش نکنید!)
```