---
title: การใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ Android
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: โดยมีผู้ดูแลระบบ Office ซึ่งมีข้อมูลเกี่ยวกับวิธีจัดการการตั้งค่าความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ Android
hideEdit: true
ms.openlocfilehash: 38d68df0d3a12e6858568906a60973bad9d76709
ms.sourcegitcommit: f441b1a5f8853c0941b3e23c7781c89abf0be641
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 07/09/2020
ms.locfileid: "45087902"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a><span data-ttu-id="5d669-103">การใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-103">Use policy settings to manage privacy controls for Office on Android devices</span></span>

<span data-ttu-id="5d669-104">การตั้งค่านโยบายสำหรับ Office บนอุปกรณ์ Android จะทำให้คุณสามารถควบคุมการตั้งค่าที่เกี่ยวข้องกับเรื่องดังต่อไปนี้ได้:</span><span class="sxs-lookup"><span data-stu-id="5d669-104">There are policy settings for Office on Android devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="5d669-105">***ข้อมูลการวินิจฉัย***ที่รวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ใช้อยู่</span><span class="sxs-lookup"><span data-stu-id="5d669-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="5d669-106">***ประสบการณ์ใช้งานที่เชื่อมต่อ*** ที่ใช้ฟังก์ชันการทำงานบนระบบ Cloud เพื่อมอบฟีเจอร์ Office ที่ได้รับการปรับปรุงให้กับคุณและผู้ใช้ของคุณ</span><span class="sxs-lookup"><span data-stu-id="5d669-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="5d669-107">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัยและประสบการณ์การใช้งานที่เชื่อมต่อ ให้ดู[ภาพรวมของการควบคุมความเป็นส่วนตัว](overview-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="5d669-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="5d669-108">การตั้งค่านโยบายเหล่านี้จะนำไปใช้กับแอปพลิเคชันต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="5d669-108">These policy settings apply to the following applications:</span></span>
- <span data-ttu-id="5d669-109">เวอร์ชัน16.0.12228.20260 และเวอร์ชันที่ใหม่กว่าของ Word สำหรับ Android Excel สำหรับ Android และ PowerPoint สำหรับ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-109">Version 16.0.12228.20260 and later of Word for Android, Excel for Android, and PowerPoint for Android.</span></span>
- <span data-ttu-id="5d669-110">Outlook สำหรับ Android เวอร์ชัน 4.1.71 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="5d669-110">Version 4.1.71 and later of Outlook for Android.</span></span>
- <span data-ttu-id="5d669-111">เวอร์ชัน16.0.12228.20004 และเวอร์ชันต่อมาของ OneNote for Android</span><span class="sxs-lookup"><span data-stu-id="5d669-111">Version 16.0.12228.20004 and later of OneNote for Android.</span></span>
- <span data-ttu-id="5d669-112">OneDrive สำหรับ Android เวอร์ชัน 5.47 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="5d669-112">Version 5.47 and later of OneDrive for Android.</span></span>

> [!NOTE]
>- <span data-ttu-id="5d669-113">การตั้งค่านโยบายเหล่านี้จะนำไปใช้กับเวอร์ชัน 16.0.12130.20272 และเวอร์ชันต่อมาของตัวอย่างสำหรับสาธารณะใน [แอป Office สำหรับอุปกรณ์เคลื่อนที่](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172) ของ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-113">These policy settings also apply to Version 16.0.12130.20272 and later of the public preview of the [Office Mobile app](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172) for Android.</span></span>
>- <span data-ttu-id="5d669-114">การใช้ตัวอย่างสำหรับสาธารณะของแอป Office สำหรับอุปกรณ์เคลื่อนที่ของ Android จะรวบรวมรายการบันทึกการหยุดทำงานซึ่งในบางครั้งอาจมีเนื้อหาอยู่</span><span class="sxs-lookup"><span data-stu-id="5d669-114">Use of the public preview of the Office Mobile app for Android will collect crash logs which may in some circumstances contain content.</span></span>
>- <span data-ttu-id="5d669-115">ถ้าคุณกังวลเกี่ยวกับการรวบรวมข้อมูลจากตัวอย่างสำหรับสาธารณะของแอป Office สำหรับ Android คุณควรแจ้งผู้ใช้ของคุณไม่ให้เข้าสู่แอปพลิเคชันด้วยบัญชีที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="5d669-115">If you're concerned about the collection of data from the public preview of the Office Mobile app for Android, you should inform your users not to log into the application with their work or school accounts.</span></span>

## <a name="policy-settings-available-for-office-on-android-devices"></a><span data-ttu-id="5d669-116">การตั้งค่านโยบายที่พร้อมใช้งานสำหรับ Office บนอุปกรณ์ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-116">Policy settings available for Office on Android devices</span></span>

<span data-ttu-id="5d669-117">ตารางต่อไปนี้แสดงการตั้งค่านโยบายที่สามารถใช้งานได้สำหรับ Office บนอุปกรณ์ Android และลิงก์ไปยังข้อมูลเพิ่มเติมเกี่ยวกับการตั้งค่านโยบายแต่ละรายการ</span><span class="sxs-lookup"><span data-stu-id="5d669-117">The following table lists which policy settings are available for Office on Android devices and a link to additional information about each policy setting.</span></span>

> [!NOTE]
>- <span data-ttu-id="5d669-118">ข้อมูลเพิ่มเติมนี้ครอบคลุมถึงการตั้งค่านโยบายสำหรับ Office บนอุปกรณ์ที่ใช้บน Windows</span><span class="sxs-lookup"><span data-stu-id="5d669-118">The additional information provided covers the policy settings for Office on devices running Windows.</span></span> <span data-ttu-id="5d669-119">แต่ข้อมูลเดียวกันนี้จะถูกนำไปใช้กับ Office บนอุปกรณ์ Android เนื่องจากเป็นการตั้งค่านโยบายแบบเดียวกัน</span><span class="sxs-lookup"><span data-stu-id="5d669-119">But the same information applies to Office on Android devices because they are the same policy settings.</span></span>
>- <span data-ttu-id="5d669-120">การตั้งค่านโยบายที่ *อนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office* ซึ่งพร้อมใช้งานสำหรับ Office บนอุปกรณ์ที่ใช้ Windows แต่ไม่สามารถใช้งานได้กับ Office บนอุปกรณ์ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-120">The *Allow the use of connected experiences in Office* policy setting that's available for Office on devices running Windows does not apply to Office on Android devices.</span></span> 


|<span data-ttu-id="5d669-121">ชื่อของการตั้งค่านโยบาย</span><span class="sxs-lookup"><span data-stu-id="5d669-121">Name of policy setting</span></span>  |<span data-ttu-id="5d669-122">ข้อมูลเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="5d669-122">Additional information</span></span> |
|---------|---------|
|<span data-ttu-id="5d669-123">การกำหนดค่าระดับของข้อมูลการวินิจฉัยซอฟต์แวร์ไคลเอ็นต์ที่ส่งโดย Office ไปยัง Microsoft</span><span class="sxs-lookup"><span data-stu-id="5d669-123">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>|[<span data-ttu-id="5d669-124">การตั้งค่านโยบายสำหรับข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="5d669-124">Policy setting for diagnostic data</span></span>](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|<span data-ttu-id="5d669-125">การอนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office ที่วิเคราะห์เนื้อหา</span><span class="sxs-lookup"><span data-stu-id="5d669-125">Allow the use of connected experiences in Office that analyze content</span></span>| [<span data-ttu-id="5d669-126">การตั้งค่านโยบายสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณ</span><span class="sxs-lookup"><span data-stu-id="5d669-126">Policy setting for connected experiences that analyze your content</span></span>](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|<span data-ttu-id="5d669-127">การอนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office ที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="5d669-127">Allow the use of connected experiences in Office that download online content</span></span> |[<span data-ttu-id="5d669-128">การตั้งค่านโยบายสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="5d669-128">Policy setting for connected experiences that download online content</span></span>](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|<span data-ttu-id="5d669-129">การอนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อแบบทางเลือกเพิ่มเติมใน Office</span><span class="sxs-lookup"><span data-stu-id="5d669-129">Allow the use of additional optional connected experiences in Office</span></span> |[<span data-ttu-id="5d669-130">การตั้งค่านโยบายสำหรับประสบการณ์ใช้งานที่เชื่อมต่อแบบทางเลือก</span><span class="sxs-lookup"><span data-stu-id="5d669-130">Policy setting for optional connected experiences</span></span>](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a><span data-ttu-id="5d669-131">การใช้บริการนโยบายระบบคลาวด์ของ Office เพื่อนำการตั้งค่านโยบายไปใช้</span><span class="sxs-lookup"><span data-stu-id="5d669-131">Use Office cloud policy service to apply policy settings</span></span>

<span data-ttu-id="5d669-132">เมื่อต้องการนำการตั้งค่านโยบายทั้ง 4 เหล่านี้ไปใช้กับ Office บนอุปกรณ์ Android คุณต้องใช้บริการนโยบายระบบคลาวด์ของ Office</span><span class="sxs-lookup"><span data-stu-id="5d669-132">To apply any of these 4 policy settings for Office on Android devices, you need to use the Office cloud policy service.</span></span> <span data-ttu-id="5d669-133">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับการใช้บริการนโยบายระบบคลาวด์ของ Office ให้ดู [ภาพรวมของบริการนโยบายระบบคลาวด์ของ Office](../overview-office-cloud-policy-service.md)</span><span class="sxs-lookup"><span data-stu-id="5d669-133">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

> [!NOTE]
> <span data-ttu-id="5d669-134">ถ้าก่อนหน้านี้คุณใช้บริการนโยบายระบบคลาวด์ของ Office เพื่อกำหนดค่าการตั้งค่านโยบายเหล่านี้สำหรับ Office บนอุปกรณ์ที่ใช้ Windows การตั้งค่าเดียวกันนั้นจะถูกนำไปใช้กับ Office บนอุปกรณ์ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-134">If you previously used Office cloud policy service to configure these policy settings for Office on devices running Windows, those same settings will apply to Office on Android devices.</span></span> <span data-ttu-id="5d669-135">สำหรับการแก้ไขปัญหาที่เกิดขึ้น คุณเพียงแค่ต้องลงชื่อเข้าใช้บริการนโยบายระบบคลาวด์ของ Office และบริการจะนำการตั้งค่าโดยอัตโนมัตินี้ไปใช้ใน Office บนอุปกรณ์ Android</span><span class="sxs-lookup"><span data-stu-id="5d669-135">For that to happen, you just need to sign in to the Office cloud policy service and the service will apply the settings automatically to Office on Android devices.</span></span>
