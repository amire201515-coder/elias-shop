# فروشگاه لوازم جانبی الیاس

سایت ثابت (بدون سرور). سفارش‌ها به واتساپ فرستاده می‌شن.

## تغییر کالاها
فایل `data/products.json` رو ویرایش کن. هر کالا:
`{"id":"p24","name":"اسم کالا","cat":"case","sub":"قاب گوشی","price":200000,"img":"img/p24.jpg"}`

- `cat` یکی از: case, cable, audio, power, other
- `price` به تومان
- `img` اختیاری است
- برای ناموجود شدن کالا: `"avail": false`

## افزودن عکس
عکس رو توی پوشه‌ی `img` با نام کالا (مثلاً `p01.jpg`) بارگذاری کن و در `products.json` برای همان کالا `"img":"img/p01.jpg"` بنویس.

## انتشار
Settings ← Pages ← Source: Deploy from a branch ← Branch: main و پوشه‌ی root ← Save.
