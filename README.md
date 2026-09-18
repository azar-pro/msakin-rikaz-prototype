# مساكن ركاز للعقارات — React/Vite Prototype

Prototype عربي RTL مخصص لـ Msakin Rikaz Real Estate.

## ما يتضمنه
- Hero Search مع فلاتر وعداد نتائج مباشر بدون 0 flash.
- بطاقات عقارات للبيع والإيجار.
- صفحة تفاصيل عقار مع Smart Agent Routing ورسالة WhatsApp مجهزة تلقائيًا.
- قسم مشاريع مستقل وصفحة كاملة لمشروع الأرين F.
- أنواع الوحدات، المميزات، القرب من المعالم، المستندات والضمانات.
- Owner Lead Funnel متعدد الخطوات.
- Admin Dashboard.
- Property CRUD تجريبي + تعديل الحالة + Featured.
- Add/Edit Property form.
- معاينة رفع صورة محليًا.
- Agent Management.
- Project Management.
- localStorage persistence.
- Responsive RTL layout.

## تشغيل المشروع
```bash
npm install
npm run dev
```

ثم افتح رابط Vite المحلي.

## Build
```bash
npm run build
```

## ملاحظات البيانات
- الأسماء التجارية والهوية والصور المرسلة من مواد مساكن ركاز مستخدمة كمرجع.
- أسماء الموظفين والأرقام الموجودة داخل البروتوتايب Demo placeholders وليست بيانات فعلية.
- العقارات غير الموثقة بشكل صريح موسومة ضمنيًا كبيانات Demo.
- بيانات مشروع الأرين F مبنية على البرومبت المعتمد من المستخدم.

## Backend لاحقًا
البنية الحالية تعتمد localStorage ويمكن استبدال طبقة البيانات لاحقًا بـ Supabase أو API / MySQL بدون تغيير جوهري في الواجهة.
