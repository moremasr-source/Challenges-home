# بيت المغامرين – المرحلة 1 (مجانية بالكامل)
GitHub (الكود + الاستضافة) + Supabase Free (الحسابات + قاعدة البيانات).

## الإعداد
1. **GitHub:** أنشئ مستودعًا جديدًا (Public)، وارفع كل هذه الملفات إليه.
2. **Supabase:** أنشئ مشروعًا مجانيًا، ثم SQL Editor ← الصق محتوى `supabase/schema.sql` ← Run.
3. **التسجيل:** Authentication ← Providers ← Email. أثناء التجربة عطّل "Confirm email" لتسهيل الدخول.
4. **المفاتيح:** Project Settings ← API. انسخ `Project URL` والمفتاح العام (anon/publishable) إلى `config.js`. لا تضع مفتاح service_role أبدًا.
5. **الاستضافة:** GitHub ← Settings ← Pages ← Deploy from branch ← main / root. ستحصل على رابط الموقع.
6. **رابط الموقع:** Supabase ← Authentication ← URL Configuration ← ضع رابط GitHub Pages في Site URL.
7. **منع إيقاف المشروع بسبب الخمول:** GitHub ← Settings ← Secrets and variables ← Actions ← أضف `SUPABASE_URL` و`SUPABASE_ANON_KEY`. ثم Actions ← keepalive ← Run workflow للتجربة.

## اختبار القبول (اجرِه بالترتيب)
- [ ] حساب جديد ثم دخول  - [ ] إنشاء عائلة  - [ ] إضافة ابنين
- [ ] إضافة مهمة، ثم "خلصت" ثم "اعتماد": تزيد نقاط الابن
- [ ] أنشئ حسابًا ثانيًا في متصفح آخر: لا يرى أي بيانات من الحساب الأول (اختبار الأمان الأهم)

## القادم
المتجر وطلباته (الجداول جاهزة)، ثم الشارات، ثم القوائم الخاصة/العامة، ثم التحديات بين العائلات.
