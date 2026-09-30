# Leotube PWA

هذه الحزمة جاهزة للرفع إلى GitHub Pages ثم إدخال رابط الموقع في PWABuilder.

## الملفات
- `index.html` الصفحة الرئيسية مع إصلاح Screen Wake Lock.
- `manifest.json` مانيفيست PWA كامل.
- `sw.js` Service Worker.
- `icons/` أيقونات 192 و512، عادية وMaskable.

## GitHub Pages
1. ارفع كل محتويات هذا المجلد إلى جذر repository.
2. يجب أن يكون `index.html` في جذر الفرع المنشور.
3. Settings > Pages > Deploy from a branch > `main` > `/ (root)`.
4. افتح رابط GitHub Pages وتأكد أن الصفحة تعمل.
5. ضع رابط GitHub Pages في PWABuilder واختر Android.

ملاحظة: الروابط داخل الصفحة والـmanifest نسبية وليست `/...` حتى تعمل بشكل صحيح داخل GitHub Pages project site مثل `/leotube/`.
