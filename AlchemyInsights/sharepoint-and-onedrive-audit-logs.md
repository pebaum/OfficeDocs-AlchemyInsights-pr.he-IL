---
title: דוחות יומן ביקורת קלאסיים של SharePoint
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 0aedb549f11db54d3cd480671fb0767c60680ad3
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509601"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>יומני ביקורת של SharePoint ו-OneDrive

## <a name="sharepoint-classic-audit-logs"></a>יומני ביקורת קלאסיים של SharePoint

ביקורת מדור קודם של SPO הועברה ליומן ביקורת אחיד (רע מ). כל דוחות הביקורת מהדור הקודם של SPO יהיו מופעל באמצעות רע מ, ואותות הביקורת הישנים הועברו ל-רע מ.

שינויי מפתח:

* זמירה אינו זמין כיכולת.
* בחירת אירועים ספציפיים לביקורת אינה זמינה. עיין [במסמך זה](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance) לקבלת רשימה מלאה של אירועים מבוקרים הזמינים כברירת מחדל.
* אפשרות **המיקום** תחת **דוחות מותאמים אישית** אינה זמינה.
* האפשרות **פתיחה או הורדה של אירועי מסמכים** אינה זמינה.

[קביעת תצורה של הגדרות ביקורת עבור אוסף אתרים](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>SharePoint ו-OneDrive מודרני יומני ביקורת מאוחד מציות

* [הפעלה/ביטול של רישום ביקורת אחיד](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off) 

אין צורך בקביעת תצורה נוספת בתוך SharePoint או OneDrive.

השתמש בחיפוש ביומן ביקורת כדי לבדוק את הפעילות של הקבצים, התיקיות, המשתמשים, ההרשאות:

* [פעילויות קובץ ועמוד](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* [פעילויות תיקיה](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [שיתוף וגישה לפעילויות בקשה](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [פעילויות סנכרון](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [פעילויות ניהול האתר](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

לקבלת מידע נוסף אודות אחזור אירועים אלה, ראה [חיפוש ביומן הביקורת](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
