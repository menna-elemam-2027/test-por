# منة الله مصطفي السيد علي السعيد — Portfolio شخصي

موقع Portfolio عربي متجاوب مبني باستخدام HTML وCSS وJavaScript مع Bootstrap RTL.

## التشغيل محليًا

يمكن فتح `index.html` مباشرة في المتصفح، أو تشغيل خادم محلي من داخل مجلد المشروع:

```bash
python3 -m http.server 3000 --bind 0.0.0.0
```

ثم افتح `http://localhost:3000`.

## التخصيص قبل التسليم

ابحث في `index.html` عن الاسم **منة الله مصطفي السيد علي السعيد** واستبدله باسمك، ثم حدّث:

- التخصص والمدينة والنبذة الشخصية.
- بيانات الدراسة والخبرات.
- أسماء المشاريع ووصفها والتقنيات المستخدمة.
- البريد الإلكتروني وروابط GitHub وLinkedIn.
- نسب المهارات في `styles.css` إذا رغبت.

## رفع المشروع إلى GitHub

```bash
git init
git add .
git commit -m "Create Arabic personal portfolio"
git branch -M main
git remote add origin https://github.com/USERNAME/portfolio.git
git push -u origin main
```

بعد الرفع فعّل **GitHub Pages** من إعدادات المستودع، واختر الفرع `main` ومجلد `/root`، ثم انسخ رابط الموقع أو رابط المستودع إلى نموذج التسليم.

## بنية الملفات

- `index.html` — محتوى الموقع وأقسامه.
- `styles.css` — الهوية البصرية والتجاوب.
- `script.js` — التنقل، مؤشر التمرير، وإظهار العناصر أثناء النزول.