---
title: הנחיות לייצוא נתוני מחזור חיים
description: הנחיות לייצוא מידע אודות מחזור-חיים של מוצר
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: he-IL
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546800"
---
# <a name="lifecycle-data-export-guidance"></a>הנחיות לייצוא נתוני מחזור חיים
מסמך זה מתאר כיצד להשתמש בקובץ ייצוא המוצר.

## <a name="query-information"></a>מידע על שאילתות
במסמך Excel זה קיימים שדות כדי לסייע בזיהוי הנתונים המאוכלסים בטבלת המוצרים.

### <a name="end-of-support"></a>סיום התמיכה
ערך סיום התמיכה יסנן מוצרים לפי תאריך סיום התמיכה של המוצר או תאריכי סיום ההפצה שלו.

ערכים אפשריים: הכל (לא הוחל מסנן), שנה וטווח.

### <a name="family"></a>משפחה
ערך המשפחה מסנן מוצרים לפי רמת האב שלו בתוך ההיררכיה המכונה המשפחה.

ערכים אפשריים: הכל (לא הוחל מסנן), שם משפחה

### <a name="group"></a>קבוצה
ערך הקבוצה מסנן מוצרים ברמת האב שלה (משפחה) לקבוצה ספציפית.

ערכים אפשריים: הכל (לא הוחל מסנן), שם קבוצה

## <a name="table-columns"></a>עמודות טבלה
טבלת המוצרים מורכבת מעמודות המגדירות את המוצר, המהדורות, ההפצות ותאריכים תואמים של התמיכה.

> [!NOTE]
> תהיה שורה עבור כל מוצר, מהדורה, ושילוב הפצה.

### <a name="product"></a>מוצר
שם המוצר.

### <a name="edition"></a>גירסה
עמודת המהדורה תאוכלס כאשר המוצר מכיל מהדורות. כאשר אין מהדורת מוצר, שדה זה יהיה ריק.

### <a name="release"></a>הפצה
עמודת המהדורה תאוכלס כאשר המוצר מכיל מהדורות מרובות.
כאשר למוצר יש רק מהדורה אחת, שדה זה יהיה ריק.

### <a name="support-policy"></a>מדיניות תמיכה
שדה זה מגדיר תחת איזו מדיניות תמיכה המוצר פועל.

ערכים אפשריים: [קבוע](/lifecycle/policies/fixed), [מודרני](/lifecycle/policies/modern), רכיב

### <a name="start-date"></a>תאריך התחלה
תאריך תחילת התמיכה במוצר.

### <a name="mainstream-date"></a>תאריך רגיל
כאשר מדיניות התמיכה היא **קבועה** או **רכיב**, זהו התאריך של תאריך הסיום הרגיל של המוצר.
  
כאשר מדיניות התמיכה **מודרנית,** שדה זה יהיה ריק.

### <a name="extended-end-date"></a>תאריך סיום מורחב
כאשר מדיניות התמיכה היא **קבועה** או **רכיב**, זהו התאריך של תאריך הסיום המורחב של המוצר.

כאשר מדיניות התמיכה **מודרנית,** שדה זה יהיה ריק.

### <a name="retirement-date"></a>תאריך פרישה
כאשר מדיניות התמיכה היא **קבועה** או **רכיב**, שדה זה יהיה ריקה.

כאשר מדיניות התמיכה **מודרנית**, זהו תאריך הפרישה של המוצר.

### <a name="release-start-date"></a>תאריך תחילת ההפצה
התאריך בו התחילה התמיכה בהפצה. כאשר למוצר יש רק מהדורה אחת, שדה זה יהיה ריק.
 
### <a name="release-end-date"></a>תאריך סיום ההפצה
התאריך בו הסתיימה התמיכה בהפצה.
כאשר למוצר יש רק מהדורה אחת, שדה זה יהיה ריק.

### <a name="docs-url"></a>Docs Url
כתובת URL לתיעוד מורחב.