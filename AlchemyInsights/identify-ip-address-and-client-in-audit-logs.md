---
title: זהה את כתובת ה-IP ואת לקוח ביומני ביקורת
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909283"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="13f79-102">זהה את כתובת ה-IP ואת לקוח ביומני ביקורת</span><span class="sxs-lookup"><span data-stu-id="13f79-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="13f79-103">כתובת ה-IP המתאים לפעילות על-ידי משתמש או מנהל מוצג יומני ביקורת.</span><span class="sxs-lookup"><span data-stu-id="13f79-103">The IP address that corresponds to an activity by a user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="13f79-104">פרטי לקוח גם נרשם.</span><span class="sxs-lookup"><span data-stu-id="13f79-104">The client information is also logged.</span></span> <span data-ttu-id="13f79-105">להלן השלבים כדי לזהות מידע כזה</span><span class="sxs-lookup"><span data-stu-id="13f79-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="13f79-106">היכנס אל [מרכז התאימות של Office 365 אבטחה &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="13f79-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="13f79-107">לחץ על **חיפוש ויצירת החקירה** ובחר באפשרות **החיפוש יומן ביקורת**.</span><span class="sxs-lookup"><span data-stu-id="13f79-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

   <span data-ttu-id="13f79-108">אם אתה מתעניין פעילות מסוימת, בחר אותו מתוך רשימת **הפעילויות** .</span><span class="sxs-lookup"><span data-stu-id="13f79-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="13f79-109">אם לא, כל הפעילויות יוחזר עבור המשתמש הנבחר (הגדרת ברירת המחדל).</span><span class="sxs-lookup"><span data-stu-id="13f79-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="13f79-110">**הערה**: ייתכן פעילויות מסוימות לא יהיו זמינות בתפריט **פעילויות** ; עם זאת, ביקורת אלה פריטים יוחזר אם הוא **הצגת תוצאות עבור כל הפעילויות** שנבחרו (הגדרת ברירת המחדל).</span><span class="sxs-lookup"><span data-stu-id="13f79-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="13f79-111">ציין את שם המשתמש בשדה **המשתמשים** , בחר את טווח התאריכים המתאימים עבור הפעילות ולאחר מכן לחץ על **חיפוש**.</span><span class="sxs-lookup"><span data-stu-id="13f79-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="13f79-112">בתוצאות, באפשרותך לראות את כתובת ה-IP עבור פעילות זו בחלונית התוצאות.</span><span class="sxs-lookup"><span data-stu-id="13f79-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="13f79-113">בחר את הרשומה ביקורת כדי לראות מידע מפורט תפריט נשלף של **פרטים** (לדוגמה, לקוח, משתמש לבצע פעולה, וכו ').</span><span class="sxs-lookup"><span data-stu-id="13f79-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="13f79-114">לקבלת מידע נוסף, ראה [איתור כתובת ה-IP של המחשב המשמש כדי לגשת לחשבון פרוץ](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="13f79-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>