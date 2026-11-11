# فروشگاه لوازم جانبی الیاس

سایت ثابت (بدون سرور). سفارش‌ها به واتساپ فرستاده می‌شن.

## پنل مدیریت
آدرس: `/admin.html` (مثلاً amire201515-coder.github.io/elias-shop/admin.html)

با توکن گیتهاب وارد می‌شی. با پنل می‌تونی کالا اضافه، ویرایش و حذف کنی، عکس بذاری، قیمت و تخفیف بدی، کالا رو ناموجود کنی، دسته‌ها و اطلاعات فروشگاه (نام، شماره‌ی واتساپ، بنر) رو عوض کنی.

### ساختن توکن
1. گیتهاب ← github.com/settings/personal-access-tokens/new
2. Repository access: Only select repositories ← elias-shop
3. Repository permissions ← Contents: Read and write
4. Generate token و کپی توکن. توکن رو به هیچ‌کس نده.

## فایل‌ها
- `data/products.json` : کالاها
- `data/config.json` : تنظیمات فروشگاه و دسته‌ها
- `img/` : عکس‌ها
