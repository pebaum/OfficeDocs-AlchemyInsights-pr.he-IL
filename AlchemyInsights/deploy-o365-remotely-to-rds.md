---
title: פריסת מיקרוסופט 365 Apps עבור הארגון לשימוש משותף ב-RDS, שרת מסופים או VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: fe051cd1dac899dc9bb19d275c352ec6585b6a93
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507587"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>פריסת מיקרוסופט 365 Apps עבור הארגון לשימוש משותף ב-RDS, שרת מסופים או VDI

כדי לפרוס את Microsoft 365 Apps עבור ארגון באמצעות שירותי שולחן עבודה מרוחק (RDS), שנקרא בעבר שירותי מסוף:
- עליך להיות בעל 365 של Microsoft עבור תוכנית עסקית או תוכנית Office 365 הכוללת את Microsoft 365 Apps עבור הארגון, כגון Office 365 E3 או הארגון E5.
   > [!NOTE] 
   > התוכניות של Microsoft 365 לעסקים ו-Microsoft 365 Business Premium פרימיום לא כוללות את Microsoft 365 Apps עבור הארגון.
- עליך להפוך [הפעלת מחשב משותפת](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation)לזמינה.

> [!NOTE]
> באפשרותך גם להוריד ולהפעיל את [מסייע התמיכה והשחזור של microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) כדי להתקין את Microsoft 365 Apps עבור ארגון במצב הפעלה משותף של המחשב.

לקבלת מידע נוסף אודות דרישות מוקדמות, הוראות התקנה והנחיות בנוגע להתקנות מותאמות אישית באמצעות כלי הפריסה של Office, ראה [פריסה של Microsoft 365 Apps עבור ארגון באמצעות שירותי שולחן עבודה מרוחק](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).

כדי לתקן שגיאות הקשורות להפעלת מחשב משותף:
- ראה [פתרון בעיות בהפעלת מחשב משותף עבור Microsoft 365 Apps עבור הארגון](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
- ראה [איפוס יישומי Microsoft 365 עבור מצב הפעלה ארגונית](https://go.microsoft.com/fwlink/?linkid=2109218).

אם ברצונך להתקין את Microsoft 365 Apps עבור ארגון ב-RDS ממרכז הניהול של Microsoft 365, ***המשתמש בהגדרות ברירת המחדל של ההתקנה***, השתמש בשלבים הבאים:

1.    בדוק איזה מנוי יש לך. [למד כיצד לעשות זאת](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have).
2.    במידת הצורך, עבור למנוי אחר. [למד כיצד לעשות זאת](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan).
3.    אם Office כבר מותקן בשרת ה-RDS באמצעות כל מנוי אחר של Microsoft, הסר את התקנתה. לדוגמה, על-ידי הולך **ללוח**  >  **הבקרה הסר תוכנית**. הסר [התקנה באמצעות מסייע התמיכה והשחזור של Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) אם אתה נתקל בבעיות.
4.    בשרת RDS, היכנס למרכז הניהול של Microsoft 365 עם חשבון מנהל המערכת שלך [והתקן את microsoft 365 Apps עבור הארגון](https://portal.office.com/OLS/MySoftware.aspx).
5.    לאחר התקנת Office, ***אל תפתח או תיכנס*** ליישומי office כלשהם.
6.    בשרת RDS, הפעל הפעלה משותפת של המחשב על-ידי עריכת הרישום על-ידי ביצוע השלבים הבאים:
   1. לחץ לחיצה ימנית על לחצן Windows בפינה השמאלית התחתונה של המסך ובחר באפשרות **הפעלה**. בתיבה פתח את, הקלד **regedit**ולאחר מכן בחר **באפשרות אישור**.
   2. בחר **כן** כאשר תתבקש לאפשר לעורך הרישום לבצע שינויים במכשיר.
   3. בעורך הרישום, הוסף ערך מחרוזת של **רישוי שיתופיות** עם הגדרה של 1 תחת HKEY_LOCAL_MACHINE \software\microsoft \Office\ClickToRun\Configuration.
   4. בשרת RDS, ***היכנס כמשתמש קצה*** [וודא שהפעלת מחשב משותף מאופשרת עבור יישומי Microsoft 365 עבור הארגון](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

