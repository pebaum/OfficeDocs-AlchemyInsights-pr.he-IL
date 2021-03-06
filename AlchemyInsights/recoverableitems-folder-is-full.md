---
title: 1336 התיקיה ' פריטים להתאוששות ' מלאה
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 4f0cba480fcc05114abd8f370b84e9a37e5f2804
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510753"
---
# <a name="the-recoverable-items-folder-is-full"></a>התיקיה ' פריטים הניתנים לשחזור ' מלאה

עבור תיבות דואר של Exchange Online, מגבלת האחסון המהווה ברירת מחדל עבור התיקיה ' פריטים הניתנים לשחזור ' היא 30 GB. מגבלת האחסון עבור התיקיה ' פריטים הניתנים לשחזור ' מוגברת באופן אוטומטי ל-100 GB אם תיבת הדואר ממוקמת בחסימה משפטית, החזקת eDiscovery, או מוקצית למדיניות שמירה.

כאשר התיקיה ' פריטים הניתנים לשחזור ' מגיעה למגבלת האחסון, פונקציונליות תיבת הדואר מושפעת מהדרכים הבאות:

- למשתמש אין אפשרות למחוק פריטים מתיבת הדואר.

- למסייע התיקיות המנוהלות אין אפשרות למחוק פריטים לפי תגית שמירה או הגדרות של תיקיות מנוהלות.

- עבור תיבות דואר שבהן שחזור פריט יחיד מאופשר או ממוקמות בהמתנה, תהליך ההגנה על עמוד ההעתקה מפני כתיבה אינו יכול לשמור על גירסאות של פריטים שנערכו על-ידי המשתמש.

- עבור תיבות דואר שבהן מופעל רישום ביקורת של תיבת דואר, לא ניתן לשמור ערכי יומן רישום של ביקורת דואר בתיקיית המשנה ' ביקורת ' בתיקיה ' פריטים הניתנים לשחזור '.

עבור תיבות דואר שאינן נמצאות בהמתנה, למנהלים יש אפשרות להשתמש `Search-Mailbox -SearchDumpsterOnly -DeleteContent` בפקודה ב-Exchange Online PowerShell כדי למחוק פריטים בתיקיה ' פריטים הניתנים לשחזור '. כדי לקבל מידע נוסף עיין בנושאים הבאים:

- [חיפוש ומחיקה של הודעות](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [חיפוש-תיבת דואר](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

עבור תיבות דואר הנמצאות בהמתנה, למנהלים יש להסיר את החסימה לפני שהם יכולים למחוק פריטים מהתיקיה ' פריטים הניתנים לשחזור '. לקבלת מידע נוסף, ראה [מחיקת פריטים בתיקיה ' פריטים הניתנים לשחזור ' של תיבות דואר המבוססות על ענן צמתים בהמתנה](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

כדי לסייע במניעת הגדלת התיקיה ' פריטים הניתנים לשחזור ', מנהלים יכולים להגדיל את מגבלת האחסון של התיקיה ' פריטים הניתנים לשחזור ' עבור תיבות דואר בהמתנה ולהגדיר מדיניות שמירה של תיבת דואר המעביר פריטים מהתיקיה ' פריטים הניתנים לשחזור ' לתיבת הדואר של המשתמש בארכיון. ראה [הגדלת המיכסה של ' פריטים הניתנים לשחזור ' עבור תיבות דואר בהמתנה](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
