العمدة — النسخة المصححة
- مبنية على index(4).html الأصلي.
- لا يتم تحميل Supabase قبل اكتمال الصفحة.
- IndexedDB هو التخزين المحلي.
- Supabase هو التخزين المشترك.
- Sync عند بدء التشغيل/عودة الإنترنت/كل 20 ثانية.
- Realtime عند تعديل app_state من جهاز آخر.
- PWA Service Worker.
- يلزم تشغيل SQL النهائي في Supabase.
- يلزم ربط حسابات المستخدمين بـ Supabase Auth وworkspace_members لاستكمال الصلاحيات السحابية الحقيقية.
