---
title: שיתוף עם משתמשים חיצוניים אינו פועל
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 305b3891e6c83e27b5c55c13757640e6e9d51a81
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 01/15/2019
ms.locfileid: "28292509"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="d88b8-102">פתור בעיות שיתוף תוכן SharePoint עם משתמשים חיצוניים</span><span class="sxs-lookup"><span data-stu-id="d88b8-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="d88b8-103">ודא כי שיתוף חיצוני מופעלת עבור הארגון שלך:</span><span class="sxs-lookup"><span data-stu-id="d88b8-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="d88b8-104">עבור אל [שירותי &amp; דף תוספות במרכז הניהול של Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), לחץ על **אתרים**.</span><span class="sxs-lookup"><span data-stu-id="d88b8-104">Go to the [Services &amp; add-ins page in the Office 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="d88b8-p101">ודא כי ההגדרה מופעלת כדי "On". אם נבחר "רק קיימים משתמשים חיצוניים", ודא שמופיע משתמש חיצוני במרכז הניהול של Office 365.</span><span class="sxs-lookup"><span data-stu-id="d88b8-p101">Make sure the setting is turned to "On." If "Only existing external users" is selected, make sure the external user is listed in the Office 365 admin center.</span></span>
    
<span data-ttu-id="d88b8-p102">ודא חיצוני שיתופו מופעלת עבור האתר. עבור אוסף אתרים קלאסי:</span><span class="sxs-lookup"><span data-stu-id="d88b8-p102">Make sure external sharing it turned on for the site. For a classic site collection:</span></span>
  
1. <span data-ttu-id="d88b8-109">במרכז הניהול של SharePoint קלאסי, בחלונית הימנית, לחץ על **אוספי אתרים**.</span><span class="sxs-lookup"><span data-stu-id="d88b8-109">In the classic SharePoint admin center, in the left pane, click **site collections**.</span></span>
    
2. <span data-ttu-id="d88b8-110">בחר אתר או אתרים ולאחר ברצועת הכלים, לחץ על **שיתוף**.</span><span class="sxs-lookup"><span data-stu-id="d88b8-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="d88b8-111">עבור אתר של צוות השייך לקבוצת Office 365, או אתר תקשורת:</span><span class="sxs-lookup"><span data-stu-id="d88b8-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="d88b8-p103">סוגים אלה של האתר החדש יש את אותו שיתוף הגדרת כהגדרה ברחבי הארגון שלך, אלא אם כן הגדרת ארגוני מאפשרת שיתוף קבצים באמצעות קישורים שאינן דורשות הכניסה. במקרה זה, האתרים אפשר שיתוף עם משתמשים חיצוניים חדשים וקיימים להיכנס. כדי לשנות את ההגדרה עבור אתרים מסוימים, השתמש מרכז הניהול החדש של SharePoint (תצוגה מקדימה) או PowerShell. [פרטים נוספים](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="d88b8-p103">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in. In this case, the sites allow sharing with new and existing external users who sign in. To change the setting for specific sites, use the new SharePoint admin center (preview) or PowerShell. [Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="d88b8-116">ההגדרה שיתוף חיצוני עבור כל אתר יכול להיות מגבילות יותר את הגדרת הארגון כולו, אך ולקוד לא יותר מההגדרה של הארגון כולו.</span><span class="sxs-lookup"><span data-stu-id="d88b8-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  
