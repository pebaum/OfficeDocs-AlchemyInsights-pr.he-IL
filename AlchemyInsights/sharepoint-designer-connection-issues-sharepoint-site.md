---
title: בעיות חיבור של מעצב SharePoint
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511545"
---
# <a name="sharepoint-designer-connection-issues"></a>בעיות חיבור של מעצב SharePoint 

אם SharePoint Designer נתקל בבעיות חיבור לאתרי SharePoint, נא נסה את הפתרונות הנפוצים הבאים.

שלב 1: ודא ש-SharePoint Designer 2013 מתעדכן באמצעות [sharepoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) ו [-2 באוגוסט, 2016 עדכון עבור sharepoint designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



שלב 2: ניקוי קבצי המטמון המקומי:

1. סגור את SharePoint Designer 2013.

2. במחשב המקומי, הסר את כל הקבצים שנמצאו בכל אחת מהתיקיות הבאות.

    - % Appנתוניםהארכה/הרחבה של שרת אינטרנט \ זיכרון מטמון
    - % שגיאת מערכת/מטמון
    - % משתמשים ברשת הקבצים האחרים

3. פתח את SharePoint Designer 2013 והזן שוב את החשבון כדי לראות אם הוא פועל.

שלב 3: [הפעלת אימות מודרני עבור Office 2013 בהתקני Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).

שלב 4: מנהלי מערכת יצטרכו **לאפשר Script מותאם אישית** בהגדרות מרכז הניהול של sharepoint כדי לאפשר חיבור של מעצב sharepoint. ראה [התרה או מניעה של קובץ script מותאם אישית](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) לקבלת מידע נוסף.


