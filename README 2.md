
AI Affiliate - גרסה מוכנה לפריסה (סטטי)
---------------------------------------

מה נוסף בגרסה זו (מוכן עכשיו):
- config.json עם שדות להחלפה: affiliate_id, mailchimp_form_action, google_analytics_id
- SVG לדוגמה בתיקיית assets (ניתן להחליף בתמונות מוצר אמיתיות)
- Netlify example function (/functions/ping.js) כדוגמת webhook פשוטה
- netlify.toml עבור פריסה מהירה ל-Netlify
- דפי HTML בעיצוב RTL ומבנה פשוט לפריסה מיידית

הוראות מהירות לפריסה (Netlify / Vercel / GitHub Pages):
1) הורידי את הקובץ ZIP המצורף ופרסי אותו במחשבך.
2) פתחי את config.json והכניסי את המזהה שותף שלך ב-"affiliate_id".
   - אם יש לך חשבון Mailchimp: הכנסי את ה-"mailchimp_form_action" (את ה-POST URL של הטופס).
   - הוסיפי את מזהה Google Analytics ב-"google_analytics_id" אם יש.
3) העלי את התיקייה לשירות פריסה סטטי (Netlify/Vercel/GitHub Pages):
   - Netlify: גרור ושחרר את התיקייה לדשבורד או קישור ל-GitHub. אם תרצי להשתמש בפונקציה, חברי לפרויקט Netlify Functions.
   - Vercel: ייבא את הפרויקט מ-GitHub והפרסו.
   - GitHub Pages: העלי לקבוצת repo והפעלי Pages.

החלפת קישורי שותפים בדפים:
- הקישורים בדפי /posts/*.html מסומנים עם attribute data-affiliate="affiliate".
- כשאת מעלה את האתר, עדכני את config.json עם affiliate_id — הסקריפט בצד הלקוח יעדכן את הלחיצות להוסיף פרמטרים.

אם תרצי — אני יכול:
- להחליף את affiliate_id עבורך (רק תכתבי לי את המזהה) וליצור גרסה מעודכנת.
- להעלות את האתר ל-GitHub ולספק הוראות פריסה ספציפיות; לשם כך אני צריך גישה ל-GitHub או שתחברי את חשבונך.
- לעצב דף נחיתה ממיר למוצר ספציפי (כולל כותרת מכירתית, חבילת תמונות וטקסט CTA).

בהצלחה — תני לי לדעת אם את רוצה שאעדכן את config.json עם המזהה שלך עכשיו.
