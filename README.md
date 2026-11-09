# جمعية Jam3iya

برنامج ويب لإدارة الجمعية: جدول الجمعية، الإيصالات والدفع، الإعدادات، القرعة، الإشعارات، وحسابات الأدمن والأعضاء.
الصفحة كلها في ملف واحد `index.html` ولا تحتاج أي خادم.

## الرفع على GitHub (من المتصفح)
1. أنشئ حسابًا على https://github.com ثم اضغط **New repository**.
2. اكتب اسمًا مثل `jam3iya` واختر **Public** (أو Private لو خطتك تدعم Pages للمستودعات الخاصة)، ثم **Create repository**.
3. اضغط **uploading an existing file** وارفع الملفات: `index.html` و `README.md` و `.nojekyll`، ثم **Commit changes**.
4. من **Settings → Pages**: في Source اختر **Deploy from a branch**، ثم Branch: `main` والمجلد `/ (root)`، ثم **Save**.
5. بعد دقيقة يظهر الرابط: `https://اسم-المستخدم.github.io/jam3iya/`

## الرفع من الكمبيوتر (Git)
```
git init
git add .
git commit -m "Jam3iya"
git branch -M main
git remote add origin https://github.com/اسم-المستخدم/jam3iya.git
git push -u origin main
```

## ملاحظات مهمة
- على GitHub Pages تُحفظ البيانات داخل متصفح كل جهاز (بدون قاعدة بيانات مشتركة). خذ نسخة احتياطية دورية من الإعدادات بزر "نسخة احتياطية" ويمكن استردادها بزر "استرداد".
- حساب الأدمن الافتراضي مخزّن داخل الملف مشفّرًا. غيّر اسمه وكلمة مروره من الإعدادات بعد أول دخول، ولا تضع بيانات حقيقية حساسة في مستودع عام.
- الحماية داخل المتصفح فقط وليست حماية خادم.
