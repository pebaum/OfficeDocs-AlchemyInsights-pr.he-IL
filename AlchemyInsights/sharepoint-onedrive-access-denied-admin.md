---
title: פתרון בעיות בהודעות שנדחו על-ידי Access
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 9430b9786b35dda9fb2604fb6ae3c39c8c258d6e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505380"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>פתרון בעיות של הודעות שנדחו ב-Access במרכז ניהול Sharepoint/OneDrive

אם אתה מקבל הודעת גישה שנדחתה בעת ניסיון לגלוש אל מרכז ניהול Sharepoint/OneDrive, נא ודא שאתה [מקצה רשיון למשתמש](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users). אם למשתמש יש רשיון, עליך גם לוודא [שהוקצו לו תפקיד מנהל](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) שיכול לגשת למרכזי הניהול.

בעיה זו עשויה להתרחש גם כאשר משתמש נמחק ונוצר מחדש עם אותו שם ראשי של משתמש (UPN). החשבון החדש נוצר על-ידי שימוש בערך PUID (מזהה Passport ייחודי) אחר. כשהמשתמש מנסה לגשת לאוסף אתרים או ל-OneDrive שלהם, למשתמש יש PUID שגוי. תרחיש שני כולל סינכרון ספריות עם יחידה ארגונית של Active Directory (OU). אם משתמשים כבר החתימו ב-SharePoint ולאחר מכן מועברים ל-OU אחר ומסונכרנים מחדש עם SharePoint, הם עלולים להיתקל בבעיה זו.

כדי לפתור בעיה זו, עליך לשחזר את ה-UPN המקורי עם השלבים במאמר, [לשחזר משתמש ב-Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).

הערה: אם מרכז OneDrive או SharePoint Admin אינו זמין למשתמשים מרובים שהיו בעבר גישה, ייתכן שקיימת בעיית שירות זמנית.  [בדוק את לוח המחוונים של תקינות השירות](https://portal.office.com/adminportal/home#/servicehealth).


