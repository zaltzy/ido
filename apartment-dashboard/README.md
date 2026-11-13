# מוכרים את הדירה

דשבורד למעקב אחרי פרסומי הדירה (יד2, פייסבוק, אינסטגרם) ולניהול פניות.

- `docs/index.html` (בשורש הריפו): הגרסה העצמאית שמוגשת ב-GitHub Pages. נתונים ב-Firebase Firestore, כניסה עם Google. את `FIREBASE_CONFIG` מדביקים בראש הסקריפט.
- `firestore.rules` (בשורש הריפו): כללי הגישה. רק שתי הכתובות שמוגדרות שם יכולות לקרוא ולכתוב.
- `apartment-dashboard/index.html`: הגרסה המקורית שרצה כ-Artifact ב-claude.ai.
- אוספים: `config/main` (פרטי דירה, טקסטים, נמענים), `channels` (מקומות פרסום וקצב חידוש), `leads` (פניות).
