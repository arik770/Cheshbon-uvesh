# חשבון עו"ש 💳

ניהול חשבון עו"ש אישי — PWA, עמוד אחד, ללא שרתים, ללא חיבורים חיצוניים.

## העלאה לגיטהב + GitHub Pages

### שלב 1 — העלה לגיטהב
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/cheshbon-uvesh.git
git push -u origin main
```

### שלב 2 — הפעל GitHub Pages
1. כנס להגדרות הריפו: **Settings → Pages**
2. תחת **Source** בחר: **Deploy from a branch**
3. בחר branch: **main** ותיקייה: **/ (root)**
4. לחץ **Save**
5. אחרי כדקה תקבל קישור: `https://YOUR-USERNAME.github.io/cheshbon-uvesh`

### שלב 3 — הוסף לדף הבית של הטלפון (PWA)
- **אנדרואיד Chrome**: תפריט ⋮ → "הוסף למסך הבית"
- **iPhone Safari**: שיתוף 📤 → "הוסף למסך הבית"

## קבצים
```
cheshbon-uvesh/
├── index.html       ← כל האתר
├── manifest.json    ← הגדרות PWA
├── sw.js            ← Service Worker (אופליין)
├── icon-192.png     ← אייקון
├── icon-512.png     ← אייקון גדול
└── README.md
```

## פיצ'רים
- יתרה נוכחית חכמה עם נקודת ייחוס
- עסקאות עתידיות + תחזית
- אמצעי תשלום, תדירות חוזרת, ספירת תשלומים
- תקופת חיוב גמישה (1–31)
- קטגוריות ניתנות לעריכה
- עובד אופליין אחרי ביקור ראשון
- נתונים נשמרים ב-localStorage — לא יוצא שום דבר לשום שרת
