# Khaznaty — Official Android Updates

مستودع التحديثات العام لتطبيق **خزنتي**، للملفات التنفيذية الموقعة وملاحظات الإصدارات فقط.

- أحدث إصدار: [GitHub Releases](https://github.com/Eslam-Salah/Khaznaty-Updates/releases/latest)
- تنبيهات التحديث داخل التطبيق تقرأ واجهة GitHub Releases الرسمية.
- مصدر التطبيق البرمجي محفوظ في مستودع خاص منفصل؛ لا تنشره هنا.
- لا ترفع أبدًا مفاتيح التوقيع `.jks` أو كلمات المرور أو نسخ الخزنة الاحتياطية.

## الإصدار الحالي

**Khaznaty v1.0.2**, versionCode **3**, package `com.khaznaty.vault`.

## طريقة نشر الإصدارات

ضع **APK الرسمي الموقّع** في المجلد `uploads/` بهذا الاسم:
`Khaznaty-1.0.2-Release-SIGNED.apk` للإصدار 1.0.2،
أو `Khaznaty-1.0.3-Release-SIGNED.apk` للإصدار التالي.

عند إضافة APK أو تغييره، ينشئ GitHub Actions إصدارًا عامًا بالوسم `v1.0.2` أو `v1.0.3` ويرفق ملف APK نفسه؛ كما يضيف ملاحظات الإصدار من `release-notes/vX.Y.Z.md` عند وجودها. تأكد أن APK موقّع بالمفتاح الرسمي نفسه وأن `versionCode` أعلى من السابق.

**لا ترفع APK تجريبيًا بتوقيع Debug.**
