---
title: 1491-search-not-returning-expected-results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 1491
ms.assetid: ''
ms.openlocfilehash: 517d9b75fc3aef09c0c2d5870aa695cc0ab10f06
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776083"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="523f4-102">חיפוש תוכן שלא להחזיר את התוצאות הצפויות</span><span class="sxs-lookup"><span data-stu-id="523f4-102">Content Search not returning expected results</span></span>

<span data-ttu-id="523f4-103">בעת הפעלת תוכן חיפושים מ & האבטחה של Office 365 מרכז תאימות, ייתכן שתקבל תוצאות החיפוש לא צפויה.</span><span class="sxs-lookup"><span data-stu-id="523f4-103">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="523f4-104">עליך לשקול את הדברים הבאים שיכולים להשפיע על תוצאות החיפוש שלך:</span><span class="sxs-lookup"><span data-stu-id="523f4-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="523f4-105">**מיקומי תוכן ואת תנאי חיפוש**: ודא שבחרת את מיקומי תוכן המתאים ואת תנאי חיפוש.</span><span class="sxs-lookup"><span data-stu-id="523f4-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="523f4-106">אם הפעלת חיפוש גדולים (עם מיקומים רבים), שתשקול לפצל אותו לתוך חיפושים מרובים.</span><span class="sxs-lookup"><span data-stu-id="523f4-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="523f4-107">**פריטים כלולים באינדקס חלקית**: [פריטים כלולים באינדקס באופן חלקי](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) מתיבות נכללים בתוצאות החיפוש משוער.</span><span class="sxs-lookup"><span data-stu-id="523f4-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="523f4-108">עם זאת, פריטי אינדקס חלקית מאתרי SharePoint ואת OneDrive שאינם נכללים במרכז ההערכה החיפוש.</span><span class="sxs-lookup"><span data-stu-id="523f4-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="523f4-109">**כשלים החיפוש**: בעת חיפוש מספר גדול של תיבות דואר (מעל ל- 100,000 תיבות דואר), אתה מקבל שגיאות החיפוש, עם קודי שגיאה כגון CS008-009 ו- CS012-002).</span><span class="sxs-lookup"><span data-stu-id="523f4-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="523f4-110">במקרה זה, נסה שנית את החיפוש רק עבור מיקומי תוכן נכשלה.</span><span class="sxs-lookup"><span data-stu-id="523f4-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="523f4-111">עיין [במאמר זה](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) לקבלת מידע נוסף.</span><span class="sxs-lookup"><span data-stu-id="523f4-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>