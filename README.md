# نظام نتائج الطالبات — الإصدار النهائي

نسخة PWA عربية RTL، Mobile-First، قابلة للنشر على GitHub Pages والتثبيت على Android كـ PWA مستقلة.

## الملفات
- index.html: التطبيق الرئيسي
- standalone.html: نسخة HTML مستقلة داخل المشروع
- manifest.webmanifest: تعريف PWA
- sw.js: العمل دون اتصال
- assets/: الشعار وأيقونات التطبيق

## GitHub Pages
ارفع محتويات هذا المجلد إلى مستودع GitHub ثم فعّل GitHub Pages من إعدادات المستودع.
بعد فتح الموقع عبر HTTPS، يمكن تثبيته من Chrome كـ تطبيق مستقل.

## APK
لإنشاء APK Android حقيقي من نفس PWA باستخدام Trusted Web Activity، يلزم ربط التطبيق بعنوان HTTPS النهائي وإضافة Digital Asset Links إلى .well-known/assetlinks.json. لا يتم تضمين توقيع APK عشوائي في هذه الحزمة.
