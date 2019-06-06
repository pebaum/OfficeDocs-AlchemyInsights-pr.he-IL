---
title: צור אתר ב- SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 2097933dd20f326a7bda2151596d514c37d566ff
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: he-IL
ms.lasthandoff: 06/04/2019
ms.locfileid: "34717768"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="11073-102">צור אתרי SharePoint באמצעות תבניות</span><span class="sxs-lookup"><span data-stu-id="11073-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="11073-103">תבניות האתר של SharePoint הם הגדרות והאינטראקטיביות המיועד סביב צורך עסקי מסוים.</span><span class="sxs-lookup"><span data-stu-id="11073-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="11073-104">לקבלת מידע נוסף, ראה <a href="https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4">שימוש בתבניות כדי ליצור סוגים שונים של אתרי SharePoint.</a></span></span><span class="sxs-lookup"><span data-stu-id="11073-104">For more information, see <a href="https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4">Using templates to create different kinds of SharePoint sites.</a></span></span></span></p> <p><span data-ttu-id="11073-105"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">להלן מספר נפוצות בעיות/פתרונות לגבי שמירה אתר או רשימה כתבנית ב- Sharepoint Online.</span></span><span class="sxs-lookup"><span data-stu-id="11073-105"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online. </span></span></span></p> <p><span data-ttu-id="11073-106"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">לחצן תבנית הרשימה site/שמור אינו זמין או חסר.</span></u></strong></span><span class="sxs-lookup"><span data-stu-id="11073-106"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Save site/list template button is not available or missing. </span></u></strong></span></span></p> <ul> <li><span data-ttu-id="11073-107"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">מנהלים יהיה עליך לאפשר קובץ Script מותאם אישית כדי להפעיל את תכונות התבנית. לקבלת שלבים מפורטים, דוגמאות ושיקולים ראה </span> </span> <a style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">אפשר או מנע בקובץ script מותאם אישית</a>.</span><span class="sxs-lookup"><span data-stu-id="11073-107"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Administrators will need to Allow Custom Script to enable the template features. For detailed steps, examples and considerations see </span></span><a style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script">Allow or prevent custom script</a>.</span></span></li> <li><span data-ttu-id="11073-108"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">האתר שמור תבנית הפקודה אינה נתמכת ואת עלולה לגרום לבעיות באתרי משתמשים התשתית פרסום שרת SharePoint.</span></span><span class="sxs-lookup"><span data-stu-id="11073-108"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure. </span></span></span></li> </ul> <p><span data-ttu-id="11073-109"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">תבנית האתר אין אפשרות ליצור או אינו פועל כראוי</span></u></strong></span><span class="sxs-lookup"><span data-stu-id="11073-109"><strong style="mso-bidi-font-weight: normal;"><u><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The site template cannot be created or does not work correctly</span></u></strong></span></span></p> <ul> <li><span data-ttu-id="11073-110"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">התבנית חסרה <a href="https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx">תכונה</a> ואת זוכה&rsquo;להפעיל t. אם התכונה אינה זמינה להפעיל את אוסף האתרים הנוכחי, לא ניתן להשתמש תבנית האתר כדי ליצור אתר.</span></span><span class="sxs-lookup"><span data-stu-id="11073-110"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The template may be missing a <a href="https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx">feature</a> and won&rsquo;t activate. If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span></span></li> <li><span data-ttu-id="11073-111"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">בדוק אם כל הרשימות או הספריות לחרוג הפריטים <a href="https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59">סף מגבלה של תצוגת רשימה של</a> 5000 כפי זה יכול לחסום יצירה של תבנית אתר.</span></span><span class="sxs-lookup"><span data-stu-id="11073-111"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Check to see if any lists or libraries exceed the <a href="https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59">List View Limit Threshold of</a> 5000 items as this can block creation of a site template.</span></span></span></li> <li><span data-ttu-id="11073-112"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">האתר באמצעות משאבים רבים מדי, לכן תבנית האתר חורג ממגבלת 50 MB.</span></span><span class="sxs-lookup"><span data-stu-id="11073-112"><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span></span></li> <li>
<span data-ttu-id="11073-113">קיימות בעיות הצגת נתונים מתוך רשימה המשתמשת עמודה של בדיקת מידע.</span><span class="sxs-lookup"><span data-stu-id="11073-113">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="11073-114">לקבלת מידע נוסף, ראה </span> <span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"> <a style="box-sizing: border-box; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a"> <span style="color: #0067b8; text-decoration: none; text-underline: none;">שנוצר על-ידי תבנית רשימה&rsquo;t הצגת נתונים מרשימת בדיקת המידע הנכון ב- SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="11073-114">For more information, see </span><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"><a style="box-sizing: border-box; -webkit-text-stroke-width: 0px; word-spacing: 0px;" href="https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a"><span style="color: #0067b8; text-decoration: none; text-underline: none;">Template-generated list doesn&rsquo;t display data from the correct lookup list in SharePoint Online.</span></span>

<span data-ttu-id="11073-115">לקבלת מידע מפורט יותר אודות בעיות ופתרונות נפוצים, נא בדוק <a href="https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989">יצירה ושימוש של תבניות אתר.</span><span class="sxs-lookup"><span data-stu-id="11073-115">For more detailed information on common problems and solutions, please check <a href="https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989">Create and use site templates.</span></span>


