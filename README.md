# نظام إدارة حلقات تحفيظ القرآن الكريم

## 🎯 نظرة عامة
نظام شامل لإدارة حلقات تحفيظ القرآن الكريم مع دعم الحلقات المنفصلة للرجال والنساء.

## 📊 قواعد البيانات المدعومة

### 🗄️ قاعدة البيانات المحلية (افتراضية)
- تعمل تلقائياً بدون إعداد
- مناسبة للتجربة والتطوير
- البيانات مؤقتة (تُحذف عند إعادة التشغيل)

### ☁️ Supabase (موصى بها للإنتاج)
- قاعدة بيانات سحابية دائمة
- نسخ احتياطية تلقائية
- أداء متقدم وأمان عالي

## 🚀 كيفية التبديل إلى Supabase

### الطريقة السريعة:
1. اتبع التعليمات في `QUICK_SUPABASE_GUIDE.md`
2. أضف `DATABASE_URL` في Secrets
3. شغل: `tsx scripts/setup-supabase.ts`

### الطريقة التفصيلية:
راجع `SUPABASE_SETUP.md` للتعليمات الكاملة.

## 👥 بيانات تسجيل الدخول
جميع بيانات المعلمين متوفرة في `CREDENTIALS.md`

## 🎨 الثيمات والتصميم
- **حلقات الرجال:** ثيم أخضر وبيج 
- **حلقات النساء:** ثيم وردي وبيج
- **واجهة عربية كاملة** مع دعم RTL
- **تصميم متجاوب** للجوال والحاسوب

## 🔧 التشغيل

```bash
# تشغيل النظام
npm run dev

# تحديث قاعدة البيانات
npm run db:push

# إعداد Supabase (بعد إضافة DATABASE_URL)
tsx scripts/setup-supabase.ts
```

## 📱 الميزات الرئيسية

- ✅ نظام تسجيل دخول آمن للمعلمين
- ✅ إدارة الطلاب (إضافة، تعديل، حذف)
- ✅ تسجيل اليوميات الشامل
- ✅ عارض القرآن التفاعلي مع تمييز الأخطاء
- ✅ تتبع الأخطاء والمراجعات
- ✅ تقارير التقدم
- ✅ دعم التاريخ الهجري

## 🔄 كيفية العودة للقاعدة المحلية
ببساطة احذف `DATABASE_URL` من Secrets وأعد تشغيل النظام.

---
**المطور:** نظام حلقات القرآن  
**النسخة:** 1.0.0  
**التحديث الأخير:** 2025# friendly-fiesta
