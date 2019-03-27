---
title: שגיאת Winsock 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772443"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="1a670-102">שגיאת Winsock 10061</span><span class="sxs-lookup"><span data-stu-id="1a670-102">Winsock error 10061</span></span>

<span data-ttu-id="1a670-103">קוד שגיאה זו פירושה כי Office 365 לא היתה אפשרות ליצור שקע TCP (חיבור) עם מארח היעד.</span><span class="sxs-lookup"><span data-stu-id="1a670-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="1a670-104">הסיבה הסבירה ביותר לשגיאה זו היא בעיה בתצורת חומת האש שלך.</span><span class="sxs-lookup"><span data-stu-id="1a670-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="1a670-105">כדי לפתור את הבעיה, בדוק את הגדרות אלה:</span><span class="sxs-lookup"><span data-stu-id="1a670-105">To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="1a670-106">ודא את תצורת חומת האש שלך עם המידע ב- [Office 365 Url ואת טווחי כתובות IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="1a670-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="1a670-107">אם השגיאה הוא ספציפי כדי Exchange Online הגנה (EOP), יש קיבלת בעבר הודעה על שינוי [כתובות IP הגנה מקוונת של Exchange](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="1a670-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="1a670-108">ודא כי את ספק שירותי האינטרנט (ISP) אינה חוסמת את היציאה.</span><span class="sxs-lookup"><span data-stu-id="1a670-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="1a670-109">אמת את חכמה מארח והיעד הגדרות השרת במחברים שלך.</span><span class="sxs-lookup"><span data-stu-id="1a670-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="1a670-110">שים לב כי Office 365 לא תחסום חיבורים *נכנסים* באופן זה.</span><span class="sxs-lookup"><span data-stu-id="1a670-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  
