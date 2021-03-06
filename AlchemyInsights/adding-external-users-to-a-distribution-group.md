---
title: הוספת משתמשים חיצוניים לקבוצת תפוצה
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 7dbc69bced9ca800d3f95081b77dda5e49662579
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 04/27/2020
ms.locfileid: "43910933"
---
# <a name="add-external-users-to-a-distribution-group"></a>הוספת משתמשים חיצוניים לקבוצת תפוצה

הוספת איש קשר חיצוני לקבוצת תפוצה (DG) היא תהליך בן שני שלבים:
  
1. צור איש קשר של דואר עבור המשתמש החיצוני:
    
    1. במרכז הניהול, עבור אל דף **Users** > [אנשי הקשר](https://admin.microsoft.com/adminportal/home#/Contact) של Users. 
    
    2. בחר **בהוסף איש קשר**.
    
    3. הקלד את המידע עבור איש הקשר שלך ובחר **ב'הוספה**.
    
2. הוסף את איש הקשר לדואר ל-DG שלך:
    
    1. במרכז הניהול, עבור לדף קבוצות **קבוצות** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) . 
    
    2. חפש את ה-DG שאליה ברצונך להוסיף את המשתמש החיצוני ובחר בו כדי לפתוח את תיבת הדו של העריכה.
    
    3. בכרטיסיה **חברים** , בחר **באפשרות הצג הכל ונהל את החברים**. 
    
    4. בחר באפשרות ' **הוסף חברים**'.
    
    5. בחר את איש הקשר של הדואר שיצרת בשלב הקודם ולאחר מכן בחר **בשמור**.
    
אם לאחר ביצוע שלבים אלה המשתמשים החיצוניים שלך לא יכולים לשלוח מיילים ל-DG או לא לקבל מיילים ממנו, זה יכול להיות כי DG מסומנת רק לאפשר מיילים ממשתמשים פנימיים. באפשרותך לבדוק תצורה זו ולתקן אותה לאחר ההנחיות [כאן](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).
  
 **הערה:** הוראות אלה אינן חלות אם סוג הקבוצה שלך הוא "Microsoft 365 group" במקום "קבוצת תפוצה". אם זהו המצב, באפשרותך להוסיף את המשתמש החיצוני ישירות לקבוצה מ-Outlook. מידע מפורט על מיקרוסופט 365 קבוצות אורחים, כמו גם הוראות להוספת אורחים חיצוניים ניתן למצוא [במאמר זה](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).
  