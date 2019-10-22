---
title: ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ iOS
ms.author: danbrown
author: pbowden-msft
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
- Ent_Office_Mac
description: มอบข้อมูลเกี่ยวกับวิธีการจัดการการตั้งค่าความเป็นส่วนตัวบนอุปกรณ์ iOS ให้กับผู้ดูแลระบบ Office
hideEdit: true
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604302"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="89761-103">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ iOS</span><span class="sxs-lookup"><span data-stu-id="89761-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="89761-104">มีการตั้งค่าการกำหนดลักษณะแบบใหม่สำหรับ Office บนอุปกรณ์ iOS ที่ให้คุณควบคุมการตั้งค่าที่เกี่ยวข้องกับสิ่งต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="89761-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="89761-105">***ข้อมูลการวินิจฉัย***ที่รวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ใช้อยู่</span><span class="sxs-lookup"><span data-stu-id="89761-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="89761-106">***ประสบการณ์ใช้งานที่เชื่อมต่อ*** ที่ใช้ฟังก์ชันการทำงานบนระบบ Cloud เพื่อมอบฟีเจอร์ Office ที่ได้รับการปรับปรุงให้กับคุณและผู้ใช้ของคุณ</span><span class="sxs-lookup"><span data-stu-id="89761-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="89761-107">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัยและประสบการณ์การใช้งานที่เชื่อมต่อ ให้ดู[ภาพรวมของการควบคุมความเป็นส่วนตัว](overview-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="89761-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="89761-108">การตั้งค่าการกำหนดลักษณะจะนำมาใช้กับแอปพลิเคชันดังต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="89761-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="89761-109">Word for iOS, Excel for iOS และ PowerPoint for iOS เวอร์ชัน 2.30 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="89761-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="89761-110">OneNote for iOS เวอร์ชัน 16.30 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="89761-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="89761-111">Visio Viewer for iOS เวอร์ชัน 1.17 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="89761-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="89761-112">สำหรับข้อมูลเกี่ยวกับการตั้งค่าที่คล้ายกันสำหรับ Office บนคอมพิวเตอร์ที่ใช้ macOS ให้ดู [ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office for Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="89761-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="89761-113">การตั้งค่าการกำหนดลักษณะอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="89761-113">Setting device preferences</span></span>
<span data-ttu-id="89761-114">เมื่อติดตั้งแอปพลิเคชัน Office ไว้ เซิร์ฟเวอร์การจัดการอุปกรณ์เคลื่อนที่ (MDM) จะสามารถตั้งค่าการกำหนดลักษณะใหม่ๆ เหล่านี้ที่ระดับอุปกรณ์ได้</span><span class="sxs-lookup"><span data-stu-id="89761-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="89761-115">หลายเซิร์ฟเวอร์ MDM อนุญาตให้ผู้ดูแลระบบ IT สามารถเพิ่มพจนานุกรมการกำหนดค่าเพิ่มเติมได้เมื่อเซิร์ฟเวอร์ส่งคำสั่ง MDM `InstallApplication` ถึงอุปกรณ์ iOS</span><span class="sxs-lookup"><span data-stu-id="89761-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="89761-116">โปรดดูรายละเอียดเพิ่มเติมที่คู่มือของเซิร์ฟเวอร์ MDM ของคุณ</span><span class="sxs-lookup"><span data-stu-id="89761-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="89761-117">พจนานุกรมจะแสดงเป็นชุดคีย์/ค่าที่จับคู่กันในรูปแบบ XML</span><span class="sxs-lookup"><span data-stu-id="89761-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="89761-118">ตัวอย่างเช่น:</span><span class="sxs-lookup"><span data-stu-id="89761-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="89761-119">เมื่อส่งถึงอุปกรณ์แล้ว พจนานุกรมการกำหนดค่าจะอยู่ภายใต้คีย์ `com.apple.managed.configuration` ซึ่งจะอ่านเมื่อเปิดใช้แอปพลิเคชัน Office</span><span class="sxs-lookup"><span data-stu-id="89761-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="89761-120">การตั้งค่าการกำหนดลักษณะสำหรับข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="89761-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="89761-121">ข้อมูลการวินิจฉัยมีไว้เพื่อรักษาความปลอดภัย อัปเดต ตรวจหา วินิจฉัย และแก้ไขปัญหาใน Office รวมถึงการปรับปรุงผลิตภัณฑ์ด้วย</span><span class="sxs-lookup"><span data-stu-id="89761-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="89761-122">สำหรับข้อมูลเพิ่มเติม ดูที่ [ข้อมูลการวินิจฉัยที่ส่งจาก Office 365 ProPlus ไปยัง Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft)</span><span class="sxs-lookup"><span data-stu-id="89761-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="89761-123">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="89761-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="89761-124">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="89761-124">**Data Type**</span></span>  | <span data-ttu-id="89761-125">สตริง</span><span class="sxs-lookup"><span data-stu-id="89761-125">String</span></span> |
|<span data-ttu-id="89761-126">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="89761-126">**Possible values**</span></span>  | <span data-ttu-id="89761-127">`BasicDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น จำเป็น)*</span><span class="sxs-lookup"><span data-stu-id="89761-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="89761-128">`FullDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น ไม่จำเป็น)*</span><span class="sxs-lookup"><span data-stu-id="89761-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="89761-129">`ZeroDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น ไม่ใช่ทั้งสองอย่าง)*</span><span class="sxs-lookup"><span data-stu-id="89761-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="89761-130">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ระบบจะส่งเฉพาะข้อมูลการวินิจฉัยที่จำเป็นถึง Microsoft หากผู้ใช้ที่มีการสมัครใช้งาน Office 365 ลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="89761-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="89761-131">นอกจากนี้ ผู้ใช้เหล่านี้จะไม่สามารถเปลี่ยนระดับของข้อมูลการวินิจฉัยได้ ไม่ว่าคุณจะตั้งค่าการกำหนดลักษณะนี้ไว้อย่างไร</span><span class="sxs-lookup"><span data-stu-id="89761-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="89761-132">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 ระบบจะส่งข้อมูลการวินิจฉัยที่ต้องใช้เท่านั้น เว้นแต่ว่าผู้ใช้เลือกที่จะส่งข้อมูลการวินิจฉัยเพิ่มเติม โดยไปที่ **ตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="89761-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="89761-133">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณ</span><span class="sxs-lookup"><span data-stu-id="89761-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="89761-134">ประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณเป็นประสบการณ์ที่ใช้เนื้อหา Office ของคุณเพื่อให้คำแนะนำการออกแบบ คำแนะนำการแก้ไข ข้อมูลเชิงลึก และฟีเจอร์การทำงานที่คล้ายกัน</span><span class="sxs-lookup"><span data-stu-id="89761-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="89761-135">ตัวอย่างเช่น แนวคิดการออกแบบใน PowerPoint</span><span class="sxs-lookup"><span data-stu-id="89761-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="89761-136">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่อเหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="89761-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="89761-137">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="89761-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="89761-138">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="89761-138">**Data Type**</span></span>  | <span data-ttu-id="89761-139">บูลีน</span><span class="sxs-lookup"><span data-stu-id="89761-139">Boolean</span></span> |
|<span data-ttu-id="89761-140">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="89761-140">**Possible values**</span></span>  | <span data-ttu-id="89761-141">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="89761-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="89761-142">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="89761-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="89761-143">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ผู้ใช้จะสามารถใช้ประสบการณ์ใช้งานที่เชื่อมต่อซึ่งวิเคราะห์เนื้อหาได้</span><span class="sxs-lookup"><span data-stu-id="89761-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="89761-144">หากผู้ใช้มีการสมัครใช้งาน Office 365 และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน ผู้ใช้จะไม่สามารถปิดประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาได้</span><span class="sxs-lookup"><span data-stu-id="89761-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="89761-145">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 ผู้ใช้สามารถเลือกที่จะปิดประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาได้โดยไปที่ **ตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="89761-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="89761-146">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="89761-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="89761-147">ประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์คือประสบการณ์ที่ช่วยให้คุณสามารถค้นหาและดาวน์โหลดเนื้อหาแบบออนไลน์ที่รวมถึงเทมเพลต รูปภาพ วิดีโอ และเอกสารอ้างอิงเพื่อเพิ่มขีดความสามารถให้เอกสารของคุณ</span><span class="sxs-lookup"><span data-stu-id="89761-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="89761-148">ตัวอย่างเช่น เทมเพลต Office หรือการแทรกไอคอนออนไลน์</span><span class="sxs-lookup"><span data-stu-id="89761-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="89761-149">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่อเหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="89761-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="89761-150">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="89761-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="89761-151">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="89761-151">**Data Type**</span></span>  | <span data-ttu-id="89761-152">บูลีน</span><span class="sxs-lookup"><span data-stu-id="89761-152">Boolean</span></span> |
|<span data-ttu-id="89761-153">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="89761-153">**Possible values**</span></span>  | <span data-ttu-id="89761-154">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="89761-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="89761-155">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="89761-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="89761-156">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ผู้ใช้จะสามารถใช้ประสบการณ์ใช้งานที่เชื่อมต่อซึ่งดาวน์โหลดเนื้อหาแบบออนไลน์ได้</span><span class="sxs-lookup"><span data-stu-id="89761-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="89761-157">หากผู้ใช้มีการสมัครใช้งาน Office 365 และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน ผู้ใช้จะไม่สามารถปิดประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาออนไลน์ได้</span><span class="sxs-lookup"><span data-stu-id="89761-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="89761-158">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 ผู้ใช้สามารถเลือกที่จะปิดประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาออนไลน์ได้โดยไปที่ **ตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="89761-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="89761-159">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="89761-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="89761-160">นอกเหนือจากประสบการณ์ใช้งานที่เชื่อมต่อที่กล่าวถึงข้างต้นแล้ว ยังมีประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมบางส่วน ซึ่งคุณสามารถเลือกอนุญาตให้ผู้ใช้เข้าถึงด้วยบัญชีขององค์กรได้ โดยในบางครั้งอาจอ้างอิงว่าเป็นบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="89761-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="89761-161">ตัวอย่างเช่น Add-in ของ Office ที่ดาวน์โหลดผ่าน Office Store ไปยังอุปกรณ์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="89761-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="89761-162">หากต้องการดูตัวอย่างเพิ่มเติม ให้ดู [ภาพรวมของประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมใน Office](optional-connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="89761-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="89761-163">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="89761-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="89761-164">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="89761-164">**Data Type**</span></span>  | <span data-ttu-id="89761-165">บูลีน</span><span class="sxs-lookup"><span data-stu-id="89761-165">Boolean</span></span> |
|<span data-ttu-id="89761-166">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="89761-166">**Possible values**</span></span>  | <span data-ttu-id="89761-167">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="89761-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="89761-168">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="89761-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="89761-169">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมจะมีให้บริการแก่ผู้ใช้ที่มีการสมัครใช้งาน Office 365 ที่ได้ลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="89761-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="89761-170">เว้นแต่ว่าคุณได้ตั้งค่าการกำหนดลักษณะนี้เป็น FALSE ผู้ใช้เหล่านี้สามารถเลือกที่จะปิดประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมได้โดยไปที่ **ตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="89761-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="89761-171">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 จะไม่มีตัวเลือกในการปิดประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="89761-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>