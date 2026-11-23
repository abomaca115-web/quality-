BRCGS Issue 9 - PWA
====================
الملفات:
  index.html   التطبيق نفسه (نفس ملفك + تسجيل الـ service worker)
  manifest.json بيانات التطبيق (الاسم، الأيقونات، الوضع standalone)
  sw.js        التخزين المؤقت للعمل أوفلاين
  icons/       الأيقونات

التشغيل:
  لازم يتفتح من رابط HTTPS (أو localhost) عشان التثبيت والأوفلاين يشتغلوا.
  لو فتحته بالضغط المزدوج على الملف (file://) هيشتغل كصفحة عادية بس بدون تثبيت.

  1) ارفع المجلد كله على: Netlify Drop (app.netlify.com/drop) أو GitHub Pages أو Cloudflare Pages
  2) افتح الرابط من الموبايل مرة واحدة وإنت أونلاين
  3) أندرويد (Chrome): القائمة > Install app / إضافة إلى الشاشة الرئيسية
     آيفون (Safari): مشاركة > Add to Home Screen

لتحويله APK لأندرويد:
  ادخل pwabuilder.com، حط رابط التطبيق بعد الرفع، واختار Android.
