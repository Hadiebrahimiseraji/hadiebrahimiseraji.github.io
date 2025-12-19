# آهن آلات محسن محمدی - قائمشهر

وبسايت حرفه‌ای برای مركز فروش آهن‌آلات ساختمانی، تیرآهن، نبشی، وغيره.

## ويژگی‌ها

- بازطراحی راست‌رفته (RTL)
- توابع متقدمه: لينک واتساپ خودرفت و جابوجائين
- جدول قیمتهای به‌روز به‌روز
- راهنماا به مسیر (Google Maps, Balad, Neshan)
- ميانه سئو محلی
- دیزاين راست‌ابی با Tailwind CSS

## ساختار پروژه

```
hadiebrahimiseraji.github.io/
├─ index.html         # صفحه اصلي
├─ README.md          # اين فايل
├─ assets/
│  └─ images/
│     ├─ logo.png                   # لوگو (آپلود کنید)
│     ├─ storefront.jpg            # عكس فروشگاه (آپلود کنید)
│     └─ products/
│        ├─ milgerd.jpg            # عكس میلگرد
│        ├─ tirahan.jpg            # عكس تیرآهن
│        ├─ varagh.jpg             # عكس ورق
│        ├─ nabshi.jpg             # عكس نبشی
│        ├─ navdani.jpg            # عكس ناودانی
│        └─ ghoti.jpg              # عكس قوطی
```

## روزنه‌سازی قیمت‌ها

`priceData` آرایه در `index.html` را ویرایش کنید:

```javascript
const priceData = [
  { product: "میلگرد A3", sizes: "12, 14, 16", unit: "کيلو", price: "28,000" },
  // ...
];
```

## داده‌های تماس

`index.html` میں این مقدارات کو تبدیل کریں:

```javascript
const PHONE_LANDLINE = "09113286812";  // تلفن ثابت
const PHONE_MOBILE = "09113286812";    // موبائل/واتس اپ
const SHOP_ADDRESS = "...";
const SHOP_LAT = 36.4719;              // عرض جغرافیایی
const SHOP_LNG = 52.8620;              // طول جغرافیایی
```

## شروعه

1. تصاویر را در پوشه‌های صحیح قرار دهید
2. قیمت‌ها را به‌روز کنید
3. اطلاعات تماس را درج کنید
4. وب‌سایت به صورت خودکار در GitHub Pages منتشر می‌شود

## لینک

- **وب‌سایت**: https://hadiebrahimiseraji.github.io
- **Repository**: https://github.com/Hadiebrahimiseraji/hadiebrahimiseraji.github.io

---

**ساخته شده با ❤️ برای تجارت محلی**