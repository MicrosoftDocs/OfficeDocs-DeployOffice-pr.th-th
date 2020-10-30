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
ms.openlocfilehash: ed24ac934625bba61eac25e764a892d48365c005
ms.sourcegitcommit: 596a0a60394011aafe1119f353ac76f27e1a4d1b
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 10/29/2020
ms.locfileid: "48794676"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="9e8e1-103">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ iOS</span><span class="sxs-lookup"><span data-stu-id="9e8e1-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="9e8e1-104">สำหรับรายการผลิตภัณฑ์ Office ที่ครอบคลุมโดยข้อมูลความเป็นส่วนตัวนี้ โปรดดู[การควบคุมความเป็นส่วนตัวที่พร้อมใช้งานสำหรับผลิตภัณฑ์ Office](products-versions-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="9e8e1-105">มีการตั้งค่าการกำหนดลักษณะแบบใหม่สำหรับ Office บนอุปกรณ์ iOS ที่ให้คุณควบคุมการตั้งค่าที่เกี่ยวข้องกับสิ่งต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="9e8e1-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="9e8e1-106">\***ข้อมูลการวินิจฉัย** _ ที่รวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ใช้อยู่</span><span class="sxs-lookup"><span data-stu-id="9e8e1-106">\***Diagnostic data** _ that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="9e8e1-107">_\*_ประสบการณ์ใช้งานที่เชื่อมต่อ_\*_ ที่ใช้ฟังก์ชันการทำงานบนระบบ Cloud เพื่อมอบฟีเจอร์ Office ที่ได้รับการปรับปรุงให้กับคุณและผู้ใช้ของคุณ</span><span class="sxs-lookup"><span data-stu-id="9e8e1-107">_*_Connected experiences_*_ that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="9e8e1-108">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัยและประสบการณ์การใช้งานที่เชื่อมต่อ ให้ดู[ภาพรวมของการควบคุมความเป็นส่วนตัว](overview-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="9e8e1-109">สำหรับข้อมูลเกี่ยวกับการตั้งค่าที่คล้ายกันสำหรับ Office บนคอมพิวเตอร์ที่ใช้ macOS ให้ดู [ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office for Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="9e8e1-110">การตั้งค่าการกำหนดลักษณะอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="9e8e1-110">Setting device preferences</span></span>
<span data-ttu-id="9e8e1-111">เมื่อติดตั้งแอปพลิเคชัน Office ไว้ เซิร์ฟเวอร์การจัดการอุปกรณ์เคลื่อนที่ (MDM) จะสามารถตั้งค่าการกำหนดลักษณะใหม่ๆ เหล่านี้ที่ระดับอุปกรณ์ได้</span><span class="sxs-lookup"><span data-stu-id="9e8e1-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="9e8e1-112">หลายเซิร์ฟเวอร์ MDM อนุญาตให้ผู้ดูแลระบบ IT สามารถเพิ่มพจนานุกรมการกำหนดค่าเพิ่มเติมได้เมื่อเซิร์ฟเวอร์ส่งคำสั่ง MDM `InstallApplication` ถึงอุปกรณ์ iOS</span><span class="sxs-lookup"><span data-stu-id="9e8e1-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="9e8e1-113">โปรดดูรายละเอียดเพิ่มเติมที่คู่มือของเซิร์ฟเวอร์ MDM ของคุณ</span><span class="sxs-lookup"><span data-stu-id="9e8e1-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="9e8e1-114">พจนานุกรมจะแสดงเป็นชุดคีย์/ค่าที่จับคู่กันในรูปแบบ XML</span><span class="sxs-lookup"><span data-stu-id="9e8e1-114">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="9e8e1-115">ตัวอย่างเช่น:</span><span class="sxs-lookup"><span data-stu-id="9e8e1-115">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="9e8e1-116">เมื่อส่งถึงอุปกรณ์แล้ว พจนานุกรมการกำหนดค่าจะอยู่ภายใต้คีย์ `com.apple.managed.configuration` ซึ่งจะอ่านเมื่อเปิดใช้แอปพลิเคชัน Office</span><span class="sxs-lookup"><span data-stu-id="9e8e1-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="9e8e1-117">นอกจากนี้คุณยังสามารถใช้บริการนโยบายระบบคลาวด์ของ Office และการตั้งค่านโยบายทั้ง 4 รูปแบบดังต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="9e8e1-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="9e8e1-118">กำหนดค่าระดับข้อมูลการวินิจฉัยซอฟต์แวร์ไคลเอ็นต์ที่ส่งจาก Office ถึง Microsoft</span><span class="sxs-lookup"><span data-stu-id="9e8e1-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="9e8e1-119">อนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office ที่วิเคราะห์เนื้อหา</span><span class="sxs-lookup"><span data-stu-id="9e8e1-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="9e8e1-120">อนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office ที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="9e8e1-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="9e8e1-121">อนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมใน Office</span><span class="sxs-lookup"><span data-stu-id="9e8e1-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="9e8e1-122">คุณสามารถกำหนดการตั้งค่าความเป็นส่วนตัวสำหรับ Outlook สำหรับ iOS และ OneDrive สำหรับ iOS โดยใช้บริการนโยบายคลาวด์ของ Office เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="9e8e1-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="9e8e1-123">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับการใช้บริการนโยบายระบบคลาวด์ของ Office ให้ดู [ภาพรวมของบริการนโยบายระบบคลาวด์ของ Office](../overview-office-cloud-policy-service.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="9e8e1-124">การตั้งค่าการกำหนดลักษณะสำหรับข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="9e8e1-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="9e8e1-125">ข้อมูลการวินิจฉัยมีไว้เพื่อรักษาความปลอดภัย อัปเดต ตรวจหา วินิจฉัย และแก้ไขปัญหาใน Office รวมถึงการปรับปรุงผลิตภัณฑ์ด้วย</span><span class="sxs-lookup"><span data-stu-id="9e8e1-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="9e8e1-126">สำหรับข้อมูลเพิ่มเติม ให้ดู [ข้อมูลการวินิจฉัยที่ส่งจาก Microsoft 365 Apps for enterprise ไปยัง Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9e8e1-127">_ *คีย์*\*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-127">_ *Key*\*</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="9e8e1-128">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-128">**Data Type**</span></span>  | <span data-ttu-id="9e8e1-129">สตริง</span><span class="sxs-lookup"><span data-stu-id="9e8e1-129">String</span></span> |
|<span data-ttu-id="9e8e1-130">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-130">**Possible values**</span></span>  | <span data-ttu-id="9e8e1-131">`BasicDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น จำเป็น)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-131">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="9e8e1-132">`FullDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น ไม่จำเป็น)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-132">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="9e8e1-133">`ZeroDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น ไม่ใช่ทั้งสองอย่าง)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-133">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="9e8e1-134">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ระบบจะส่งเฉพาะข้อมูลการวินิจฉัยที่จำเป็นถึง Microsoft หากผู้ใช้ที่มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) ลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-134">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="9e8e1-135">นอกจากนี้ ผู้ใช้เหล่านี้จะไม่สามารถเปลี่ยนระดับของข้อมูลการวินิจฉัยได้ ไม่ว่าคุณจะตั้งค่าการกำหนดลักษณะนี้ไว้อย่างไร</span><span class="sxs-lookup"><span data-stu-id="9e8e1-135">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="9e8e1-136">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) ระบบจะส่งข้อมูลการวินิจฉัยที่ต้องใช้เท่านั้น เว้นแต่ว่าผู้ใช้เลือกที่จะส่งข้อมูลการวินิจฉัยเพิ่มเติม โดยไปที่ **การตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-136">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings** .</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="9e8e1-137">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณ</span><span class="sxs-lookup"><span data-stu-id="9e8e1-137">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="9e8e1-138">ประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณเป็นประสบการณ์ที่ใช้เนื้อหา Office ของคุณเพื่อให้คำแนะนำการออกแบบ คำแนะนำการแก้ไข ข้อมูลเชิงลึก และฟีเจอร์การทำงานที่คล้ายกัน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-138">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="9e8e1-139">ตัวอย่างเช่น แนวคิดการออกแบบใน PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9e8e1-139">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="9e8e1-140">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่อเหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-140">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9e8e1-141">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-141">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="9e8e1-142">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-142">**Data Type**</span></span>  | <span data-ttu-id="9e8e1-143">บูลีน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-143">Boolean</span></span> |
|<span data-ttu-id="9e8e1-144">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-144">**Possible values**</span></span>  | <span data-ttu-id="9e8e1-145">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-145">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="9e8e1-146">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-146">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="9e8e1-147">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ผู้ใช้จะสามารถใช้ประสบการณ์ใช้งานที่เชื่อมต่อซึ่งวิเคราะห์เนื้อหาได้</span><span class="sxs-lookup"><span data-stu-id="9e8e1-147">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="9e8e1-148">หากผู้ใช้มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน ผู้ใช้จะไม่สามารถปิดประสบการณ์ใช้งานที่เชื่อมต่อซึ่งวิเคราะห์เนื้อหาได้</span><span class="sxs-lookup"><span data-stu-id="9e8e1-148">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="9e8e1-149">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) ผู้ใช้สามารถเลือกที่จะปิดประสบการณ์ใช้งานที่เชื่อมต่อซึ่งวิเคราะห์เนื้อหาได้โดยไปที่ **การตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-149">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="9e8e1-150">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="9e8e1-150">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="9e8e1-151">ประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์คือประสบการณ์ที่ช่วยให้คุณสามารถค้นหาและดาวน์โหลดเนื้อหาแบบออนไลน์ที่รวมถึงเทมเพลต รูปภาพ วิดีโอ และเอกสารอ้างอิงเพื่อเพิ่มขีดความสามารถให้เอกสารของคุณ</span><span class="sxs-lookup"><span data-stu-id="9e8e1-151">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="9e8e1-152">ตัวอย่างเช่น เทมเพลต Office หรือการแทรกไอคอนออนไลน์</span><span class="sxs-lookup"><span data-stu-id="9e8e1-152">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="9e8e1-153">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่อเหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-153">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9e8e1-154">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-154">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="9e8e1-155">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-155">**Data Type**</span></span>  | <span data-ttu-id="9e8e1-156">บูลีน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-156">Boolean</span></span> |
|<span data-ttu-id="9e8e1-157">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-157">**Possible values**</span></span>  | <span data-ttu-id="9e8e1-158">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-158">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="9e8e1-159">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-159">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="9e8e1-160">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ผู้ใช้จะสามารถใช้ประสบการณ์ใช้งานที่เชื่อมต่อซึ่งดาวน์โหลดเนื้อหาแบบออนไลน์ได้</span><span class="sxs-lookup"><span data-stu-id="9e8e1-160">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="9e8e1-161">หากผู้ใช้มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน ผู้ใช้จะไม่สามารถปิดประสบการณ์ใช้งานที่เชื่อมต่อซึ่งดาวน์โหลดเนื้อหาแบบออนไลน์ได้</span><span class="sxs-lookup"><span data-stu-id="9e8e1-161">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="9e8e1-162">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) ผู้ใช้สามารถเลือกที่จะปิดประสบการณ์ใช้งานที่เชื่อมต่อซึ่งดาวน์โหลดเนื้อหาแบบออนไลน์ได้โดยไปที่ **การตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-162">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings** .</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="9e8e1-163">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="9e8e1-163">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="9e8e1-164">นอกเหนือจากประสบการณ์ใช้งานที่เชื่อมต่อที่กล่าวถึงข้างต้นแล้ว ยังมีประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมบางส่วน ซึ่งคุณสามารถเลือกอนุญาตให้ผู้ใช้เข้าถึงด้วยบัญชีขององค์กรได้ โดยในบางครั้งอาจอ้างอิงว่าเป็นบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-164">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="9e8e1-165">ตัวอย่างเช่น Add-in ของ Office ที่ดาวน์โหลดผ่าน Office Store ไปยังอุปกรณ์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="9e8e1-165">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="9e8e1-166">หากต้องการดูตัวอย่างเพิ่มเติม ให้ดู [ภาพรวมของประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมใน Office](optional-connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="9e8e1-166">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9e8e1-167">**คีย์**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-167">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="9e8e1-168">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-168">**Data Type**</span></span>  | <span data-ttu-id="9e8e1-169">บูลีน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-169">Boolean</span></span> |
|<span data-ttu-id="9e8e1-170">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-170">**Possible values**</span></span>  | <span data-ttu-id="9e8e1-171">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-171">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="9e8e1-172">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="9e8e1-172">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="9e8e1-173">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ประสบการณ์ใช้งานที่เชื่อมต่อเพิ่มเติมจะมีให้บริการแก่ผู้ใช้ที่มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) ที่ได้ลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="9e8e1-173">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="9e8e1-174">เว้นแต่ว่าคุณได้ตั้งค่าการกำหนดลักษณะนี้เป็น FALSE ผู้ใช้เหล่านี้สามารถเลือกที่จะปิดประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมได้โดยไปที่ **ตั้งค่า** > **การตั้งค่าความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="9e8e1-174">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings** .</span></span>

<span data-ttu-id="9e8e1-175">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 (หรือ Microsoft 365) จะไม่มีตัวเลือกในการปิดใช้งานประสบการณ์ใช้งานที่เชื่อมต่อเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="9e8e1-175">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>