---
title: פתרון בעיות סינכרון סיסמאות
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: c71fce8621057093d23891c26f7b0285fdc8b9ed
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 01/15/2019
ms.locfileid: "28292537"
---
# <a name="troubleshoot-password-synchronization"></a><span data-ttu-id="f6030-102">פתרון בעיות סינכרון סיסמאות</span><span class="sxs-lookup"><span data-stu-id="f6030-102">Troubleshoot password synchronization</span></span>

<span data-ttu-id="f6030-103">כדי לפתור בעיות שבהן הם סיסמאות לא מסונכרן עם חיבור AD תכלת הרקיע גירסה 1.1.614.0 או גירסה מתקדמת יותר:</span><span class="sxs-lookup"><span data-stu-id="f6030-103">To troubleshoot issues where no passwords are synchronized with Azure AD Connect version 1.1.614.0 or later:</span></span>
  
1. <span data-ttu-id="f6030-104">פתח את הפעלת Windows PowerShell חדשה בשרת שלך חיבור AD תכלת הרקיע עם האפשרות **הפעל כמנהל** .</span><span class="sxs-lookup"><span data-stu-id="f6030-104">Open a new Windows PowerShell session on your Azure AD Connect server with the **Run as Administrator** option.</span></span> 
    
2. <span data-ttu-id="f6030-105">הפעל **RemoteSigned ExecutionPolicy ערכה** או **ערכת-ExecutionPolicy בלתי מוגבלת**.</span><span class="sxs-lookup"><span data-stu-id="f6030-105">Run **Set-ExecutionPolicy RemoteSigned** or **Set-ExecutionPolicy Unrestricted**.</span></span> 
    
3. <span data-ttu-id="f6030-106">הפעל את אשף ' התחבר AD תכלת הרקיע.</span><span class="sxs-lookup"><span data-stu-id="f6030-106">Start the Azure AD Connect wizard.</span></span>
    
4. <span data-ttu-id="f6030-107">נווט \* \* פעילויות נוספות \* \* דף, בחר \* \* פתרון \* \*, ולחץ על **הבא**.</span><span class="sxs-lookup"><span data-stu-id="f6030-107">Navigate to the \*\* Additional Tasks \*\* page, select \*\* Troubleshoot \*\*, and click **Next**.</span></span> 
    
5. <span data-ttu-id="f6030-108">בדף ' פתרון בעיות ', לחץ על תפריט **הפעלה כדי להפעיל את פתרון הבעיות** ב- PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f6030-108">On the Troubleshooting page, click **Launch to start the troubleshooting** menu in PowerShell.</span></span> 
    
6. <span data-ttu-id="f6030-109">בתפריט הראשי, בחר **לפתור בעיות סינכרון סיסמאות**.</span><span class="sxs-lookup"><span data-stu-id="f6030-109">In the main menu, select **Troubleshoot Password Synchronization**.</span></span> 
    
7. <span data-ttu-id="f6030-110">בתפריט המשנה, בחר **סינכרון סיסמאות אינו פועל כלל**.</span><span class="sxs-lookup"><span data-stu-id="f6030-110">In the sub menu, select **Password Synchronization does not work at all**.</span></span> 
    
 <span data-ttu-id="f6030-111">**להבין את התוצאות של הפעילות לפתרון בעיות**</span><span class="sxs-lookup"><span data-stu-id="f6030-111">**Understand the results of the troubleshooting task**</span></span>
  
<span data-ttu-id="f6030-112">המשימה לפתרון בעיות מבצע את הבדיקות הבאות:</span><span class="sxs-lookup"><span data-stu-id="f6030-112">The troubleshooting task performs the following checks:</span></span>
  
- <span data-ttu-id="f6030-113">מאמת כי תכונת הסינכרון של סיסמאות זמינה עבור דיירים תכלת הרקיע הפרסומת שלך.</span><span class="sxs-lookup"><span data-stu-id="f6030-113">Validates that the password synchronization feature is enabled for your Azure AD tenant.</span></span>
    
- <span data-ttu-id="f6030-114">מאמת שרת התחבר AD תכלת הרקיע אינו נמצא במצב אחסון זמני.</span><span class="sxs-lookup"><span data-stu-id="f6030-114">Validates that the Azure AD Connect server is not in staging mode.</span></span>
    
- <span data-ttu-id="f6030-115">עבור כל קיים המקומית Active Directory מחבר (התואם יער של Active Directory קיים):</span><span class="sxs-lookup"><span data-stu-id="f6030-115">For each existing on-premises Active Directory connector (which corresponds to an existing Active Directory forest):</span></span>
    
- 
  - <span data-ttu-id="f6030-116">מאמת את תכונת הסינכרון של סיסמאות מופעלת.</span><span class="sxs-lookup"><span data-stu-id="f6030-116">Validates that the password synchronization feature is enabled.</span></span>
    
  - <span data-ttu-id="f6030-117">חיפוש אירועים של פעימות הסינכרון סיסמה ביומני האירועים של היישום Windows.</span><span class="sxs-lookup"><span data-stu-id="f6030-117">Searches for password synchronization heartbeat events in the Windows Application Event logs.</span></span>
    
  - <span data-ttu-id="f6030-118">עבור כל תחום Active Directory תחת המחבר Active Directory מקומי:</span><span class="sxs-lookup"><span data-stu-id="f6030-118">For each Active Directory domain under the on-premises Active Directory connector:</span></span>
    
  - <span data-ttu-id="f6030-119">מאמת התחום הוא אפשרות לגשת מהשרת התחבר AD תכלת הרקיע.</span><span class="sxs-lookup"><span data-stu-id="f6030-119">Validates that the domain is reachable from the Azure AD Connect server.</span></span>
    
  - <span data-ttu-id="f6030-120">מאמת חשבונות ה-Active Directory Domain Services (AD DS) בשימוש על-ידי המחבר Active Directory מקומי בעל שם משתמש וסיסמה נכונים, סיסמה והרשאות הנדרש עבור סינכרון סיסמאות.</span><span class="sxs-lookup"><span data-stu-id="f6030-120">Validates that the Active Directory Domain Services (AD DS) accounts used by the on-premises Active Directory connector has the correct username, password, and permissions required for password synchronization.</span></span>
    
<span data-ttu-id="f6030-121">לקבלת עזרה נוספת לפתרון בעיות סינכרון סיסמה, ראה [פתרון בעיות סינכרון סיסמאות עם סינכרון התחבר AD תכלת הרקיע](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span><span class="sxs-lookup"><span data-stu-id="f6030-121">For more help troubleshooting password sync, see [Troubleshoot password synchronization with Azure AD Connect sync](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).</span></span>
  
