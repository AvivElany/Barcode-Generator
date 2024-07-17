# מחולל ברקודים

### במסגרת קורס פולסטאק במכללת האקריו בניתי פרויקט אישי זה ובעזרת שימוש בסיפרייה קיימת
- הפרויקט כתוב ב-HTML, CSS ו-JavaScript
- נעשה שימוש בסיפרייה בשם JsBarcode

barcode.html
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jsbarcode/3.11.0/JsBarcode.all.min.js"></script> <!-- ספרייה אוטומטית כתובה ליצירת ברקודים -->
```

## עיצוב
העיצוב הינו בסיסי, ממורכז במרכז המסך, צבוע בצבעי בסיס - שחור ולבן אך מאוד אינטואטיבי למטרת האפליקציה
<BR>

## פונקציונליות 
הדרישה מהמשתמש הינה לכתוב בשורת הכתיבה מחרוזת כלשהי מכל תו שקיים, לבחור צבע לברקוד עצמו וצבע לרקע וכפתור מחולל
<BR>
לאחר מכן תוצג תמונה המכילה את הברקוד לפי המחרוזת, מתחת לברקוד המחרוזת ויוצג מעל כפתור להורדת התמונה בפורמט SVG
<BR>
מצד מפתח הפרונט בניתי את העיצוב, וקראתי נכון לפונקציה הבנויה שמייצרת את הברקוד ואת יצירת התמונה