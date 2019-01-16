---
title: העברת הודעות דואר אלקטרוני בתיבת הדואר של ארכיון
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 41d6825b568263fb7b09066b65235aa348415bae
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 01/15/2019
ms.locfileid: "28292868"
---
<span data-ttu-id="f5a41-p101">בעיות אחסון בארכיון של פריטים בתיבת הדואר של ארכיון. ודא שביצעת את השלבים הבאים:</span><span class="sxs-lookup"><span data-stu-id="f5a41-p101">Having problems archiving items to the Archive mailbox. Make sure you have performed the following steps:</span></span>
  
1. <span data-ttu-id="f5a41-p102">ודא כי **לאחסן בארכיון דואר** הפכה לזמינה. אם לא, בצע את הפעולות במאמר [זה](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) כדי להפעיל את תיבת הדואר של ארכיון.</span><span class="sxs-lookup"><span data-stu-id="f5a41-p102">Confirm that an **Archive mailbox** has been enabled. If not, use steps in [this article](https://docs.microsoft.com/en-us/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span> 
    
2. <span data-ttu-id="f5a41-106">במרכז הניהול של Exchange, בחר **תגיות השמירה** תחת **ניהול תאימות**, ליצור **תגית שמירה** עם פעולת **העבר לארכיון** המכיל את **גיל השמירה**הרצויה.</span><span class="sxs-lookup"><span data-stu-id="f5a41-106">In the Exchange Admin Center, select **Retention Tags** under **Compliance Management**, create a **Retention tag** with the **Move to Archive** action containing the desired **Retention Age**.</span></span>
    
3. <span data-ttu-id="f5a41-107">במרכז הניהול של Exchange, בחר **מדיניות שמירה**, ליצור **מדיניות שמירה** ולהוסיף תגית השמירה שלך **להעביר לארכיון** מדיניות זו.</span><span class="sxs-lookup"><span data-stu-id="f5a41-107">In the Exchange Admin Center, select **Retention Policies**, create a **Retention Policy** and add your **Move to Archive** retention tag to that policy.</span></span> 
    
4. <span data-ttu-id="f5a41-p103">[הקצאת מדיניות השמירה](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) תיבת דואר של משתמש מסוים. באותה המדיניות יוחלו על **ראשי** וגם את תיבת הדואר של **ארכיון** .</span><span class="sxs-lookup"><span data-stu-id="f5a41-p103">[Assign the Retention Policy](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox. The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span> 
    
<span data-ttu-id="f5a41-p104">תיבת הדואר של המשתמש אמורה להיות מדיניות ארכיון כדי להעביר פריטים בתיבת הדואר של ארכיון. ייתכן שיהיה עליך לכפות את מנוהל תיקיה המסייע (MFA) כדי להפעיל, להחיל את ההגדרות החדשות לתיבת הדואר של המשתמש. הפעל את הפקודה הבאה בעת [מחובר EXO PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) כדי להפעיל את ניהול מסייע התיקיות עבור תיבת דואר מסוימת:</span><span class="sxs-lookup"><span data-stu-id="f5a41-p104">The user's mailbox should now have an Archive policy to move items to the Archive mailbox. It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox. Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span> 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

<span data-ttu-id="f5a41-113">מעוניין במידע נוסף אודות הגדרת מדיניות אחסון בארכיון, ראה [הגדרת מדיניות ארכיון ומחיקה של תיבות דואר](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="f5a41-113">Want more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/en-us/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  
