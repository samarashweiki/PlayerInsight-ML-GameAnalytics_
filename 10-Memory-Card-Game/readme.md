# 🎮 Player Insight: ML-Powered Game Analytics

## 🧠 نظرة عامة على المشروع

هذا المشروع يهدف إلى تحليل سلوك اللاعبين باستخدام تقنيات تعلم الآلة. قمنا باستخدام لعبة جاهزة (لعبة ذاكرة) وقمنا بتعديلها لإضافة ميزة جمع بيانات اللاعبين، وتحليل هذه البيانات باستخدام خوارزميات التعلم الآلي، وتقديم توصيات تلقائية لتصميم اللعبة.

## 🛠️ التقنيات المستخدمة

- محرك اللعبة: **JavaScript + HTML** (لعبة ذاكرة جاهزة)
- البرمجة الخلفية والتحليل: **Python**
- مكتبات تعلم الآلة:  
  - `pandas`  
  - `scikit-learn`  
  - `numpy`
- عرض البيانات والتوصيات:  
  - لوحة تحكم باستخدام HTML + JavaScript

## 🧩 كيفية تثبيت المشروع وتشغيله

1. افتح مجلد المشروع باستخدام Visual Studio Code.
2. شغل اللعبة في متصفح من خلال فتح ملف `index.html`.
3. اجمع بيانات اللعب تلقائيًا من خلال التعديلات البرمجية.
4. شغّل كود تحليل البيانات و ML (باستخدام Python).
5. افتح ملف `dashboard.html` لرؤية لوحة البيانات والتحليلات.

## 🧪 جمع البيانات

- تم تسجيل:
  - عدد الحركات لكل لاعب.
  - الوقت المستغرق.
  - حالة النجاح أو الفشل.
  - وقت الجلسة.
- يتم تخزين البيانات باستخدام `localStorage` وتُصدّر كملف JSON.

## 🤖 شرح تعلم الآلة

- استخدمنا خوارزمية **K-Means** لتجميع اللاعبين حسب أدائهم.
- يتم التنبؤ إذا كان اللاعب سيحقق نجاحًا أم لا بناءً على:
  - عدد الحركات.
  - الزمن.
- تظهر التوقعات في لوحة البيانات باللون الأخضر أو الأحمر حسب النتيجة.

## 📊 مميزات لوحة التحكم

- جدول تفصيلي لكل لاعب.
- حساب المتوسطات العامة.
- تقسيم اللاعبين إلى مجموعتين (سريع وبطيء).
- عرض توصيات آلية حسب نتائج التحليل.

## 📁 ملفات المشروع

