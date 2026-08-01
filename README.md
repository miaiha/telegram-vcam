# Telegram Virtual Camera Mod

هذا المستودع يحتوي على ملفات معدلة لتطبيق تلغرام أندرويد لإضافة ميزة الكاميرا الافتراضية.

## المميزات
- **الكاميرا الافتراضية**: استبدال بث الكاميرا الحقيقي بفيديو من الاستوديو.
- **زر عائم**: يظهر داخل الكاميرا لاختيار الفيديو بسهولة.

## كيفية البناء
1. قم بعمل Clone لمستودع تلغرام الرسمي: `git clone https://github.com/DrKLO/Telegram.git`
2. استبدل الملفات التالية بالملفات الموجودة في هذا المستودع:
   - `TMessagesProj/src/main/java/org/telegram/messenger/camera/CameraView.java`
   - `TMessagesProj/src/main/java/org/telegram/ui/LaunchActivity.java`
3. قم ببناء التطبيق باستخدام Android Studio أو Gradle.

## ملاحظة حول APK
بسبب حجم تطبيق تلغرام الكبير، يفضل بناء APK محلياً أو استخدام GitHub Actions (يجب إضافة ملف `.github/workflows/build.yml` يدوياً إذا لم يكن موجوداً).
