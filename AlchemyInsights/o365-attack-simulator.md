---
title: 2681 סימולטור התקפה ב-Microsoft 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 3dae4768ca62757ce7f92dfc527078c963d72742
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506739"
---
# <a name="attack-simulator-in-microsoft-365"></a>סימולטור התקפה ב-Microsoft 365

- ? אתה מפספס את סימולטור התקיפה סימולטור **התקפה דורש office 365 הגנה מתקדמת איום תוכנית 2 (תוכנית ATP 2)** או **Office 365 הארגון E5**. סימולטור התקפה **אינו** נכלל בתוכנית הגנת האיום המתקדמת של office 365 1 (תוכנית ATP 1), Office 365 Enterprise E3, או כל מיקרוסופט 365 Apps עבור מנויים עסקיים.

- החשבון שאתה משתמש בו להפעלת התקפות מדומים דורש מנהל מערכת כללי או הרשאות מנהל אבטחה ואימות מרובה גורמים (משרד המרכז). לקבלת מידע נוסף על דרישות סימולטור התקפה, עיין [בנושא זה](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).

- דברים חשובים לדעת על סימולציות התקפה **באמצעות סיסמה בכח** :

  - אם לחשבון היעד מופעל משרד המשנה והסיסמה היתה מכוונת כראוי, החשבון לא יוצג כחשוד (מקדם האימות השני לא יהיה שלם).

  - קובץ הסיסמה אינו יכול להיות גדול מ-10 MB. השתמש בסיסמה אחת לכל שורה וכלול שורה ריקה (החזרת גררה) לאחר הסיסמה האחרונה ברשימה.

- חשוב לדעת אודות **החנית** הדמיות חיבור של דיוג:

  - באמצעות עיצוב, אין באפשרותך לספק ערך מותאם אישית עבור **כתובת URL של שרת ההתחברות לדיוג**.

  - אם נמען משתמש [בתוספת הפעלת הודעת דוח](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) כדי לדווח על ההודעה כדיוג, ייתכן שלא תקבל התראות עבור ההודעה (מכיוון שזוהי התקפה מדומה).

- דוחות: לאחר השלמת ההתקפה הדומה, באפשרותך ללחוץ על **פרטי התקפה** כדי לראות את הדוח.

- לקבלת הוראות מפורטות ותכונות חדשות ב סימולטור התקפה, ראה [סימולטור התקפה ב-Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).
