# مسار — التحديثات / Masar — Updates

هذا المستودع يستضيف ملفات التحديث داخل التطبيق لبرنامج **مسار** (المعرّف الداخلي `thabat`).

This repository hosts the in-app update files for the **Masar** app (internal id `thabat`).

- `latest.json` — أحدث إصدار متاح (يُقرأ من داخل التطبيق).
- ملفات APK مرفقة بكل إصدار (release assets).

التطبيق يقرأ `latest.json` من أحدث إصدار (release) هنا، وينزّل ملف الـAPK المطابق لنوع الجهاز، مع الحفاظ على كل بيانات المستخدم.

> مفتاح التوقيع الخاص (release key) لا يُنشر هنا أبداً.
