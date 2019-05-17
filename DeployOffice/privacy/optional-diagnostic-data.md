---
title: ข้อมูลการวินิจฉัยเพิ่มเติมสำหรับ Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: ให้ข้อมูลแก่ผู้ดูแลระบบ Office เกี่ยวกับข้อมูลการวินิจฉัยเพิ่มเติมใน Office รวมถึงตัวอย่างเหตุการณ์บางอย่าง
hideEdit: true
ms.openlocfilehash: 1df576e8f5f1b3ed9fff11651ff4dd2b28d47229
ms.sourcegitcommit: b3fd057154853fc588d0e83b4d632b6e9a051a3c
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 04/23/2019
ms.locfileid: "32435878"
---
# <a name="optional-diagnostic-data-for-office"></a><span data-ttu-id="22a0e-103">ข้อมูลการวินิจฉัยเพิ่มเติมสำหรับ Office</span><span class="sxs-lookup"><span data-stu-id="22a0e-103">Optional diagnostic data for Office</span></span>

> [!IMPORTANT]
> <span data-ttu-id="22a0e-104">ข้อมูลในบทความนี้ใช้กับเวอร์ชัน 1904 ขึ้นไปของซอฟต์แวร์ไคลเอ็นต์ Office ต่อไปนี้ที่ติดตั้งบนคอมพิวเตอร์ที่ใช้ Windows:</span><span class="sxs-lookup"><span data-stu-id="22a0e-104">The information in this article applies to Version 1904 or later of the following Office client software installed on a computer running Windows:</span></span>
> - <span data-ttu-id="22a0e-105">Office 365 ProPlus และ Office 365 Business</span><span class="sxs-lookup"><span data-stu-id="22a0e-105">Office 365 ProPlus and Office 365 Business</span></span>
> - <span data-ttu-id="22a0e-106">Office 365 Personal, Office 365 Home หรือ Office เวอร์ชันอื่นที่เป็นส่วนหนึ่งของการสมัครใช้งาน Office 365</span><span class="sxs-lookup"><span data-stu-id="22a0e-106">Office 365 Personal, Office 365 Home, or other versions of Office that are part of an Office 365 subscription.</span></span>
> - <span data-ttu-id="22a0e-107">Project และ Visio ที่มีแผนการสมัครใช้งาน เช่น แผน Project Online Professional หรือ Visio Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="22a0e-107">Project and Visio that come with some subscription plans, such as the Project Online Professional plan or Visio Online Plan 2.</span></span>

<span data-ttu-id="22a0e-108">ข้อมูลการวินิจฉัยมีไว้เพื่อรักษาความปลอดภัย อัปเดต ตรวจหา วินิจฉัย และแก้ไขปัญหาใน Office รวมถึงการปรับปรุงผลิตภัณฑ์ด้วย</span><span class="sxs-lookup"><span data-stu-id="22a0e-108">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and fix problems, and also make product improvements.</span></span> <span data-ttu-id="22a0e-109">ข้อมูลนี้จะไม่มีชื่อหรือที่อยู่อีเมลของผู้ใช้ เนื้อหาไฟล์ของผู้ใช้ หรือข้อมูลเกี่ยวกับแอปที่ไม่เกี่ยวข้องกับ Office</span><span class="sxs-lookup"><span data-stu-id="22a0e-109">This data does not include a user’s name or email address, the content of the user’s files, or information about apps unrelated to Office.</span></span>

<span data-ttu-id="22a0e-110">ข้อมูลการวินิจฉัยนี้จะรวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ทำงานบนคอมพิวเตอร์ที่ใช้ Windows</span><span class="sxs-lookup"><span data-stu-id="22a0e-110">This diagnostic data is collected and sent to Microsoft about Office client software being used on computers running Windows.</span></span> <span data-ttu-id="22a0e-111">จำเป็นต้องระบุข้อมูลการวินิจฉัยบางอย่าง ขณะที่ข้อมูลการวินิจฉัยบางอย่างสามารถระบุหรือไม่ก็ได้</span><span class="sxs-lookup"><span data-stu-id="22a0e-111">Some diagnostic data is required, while some diagnostic data is optional.</span></span> <span data-ttu-id="22a0e-112">เราให้ความสามารถในการเลือกว่าจะส่งข้อมูลการวินิจฉัยที่จำเป็นหรือเพิ่มเติมให้เราผ่านการใช้การควบคุมความเป็นส่วนตัวหรือไม่ เช่น การตั้งค่านโยบายสำหรับองค์กร</span><span class="sxs-lookup"><span data-stu-id="22a0e-112">We give you the ability to choose whether to send us required or optional diagnostic data through the use of privacy controls, such as policy settings for organizations.</span></span> <span data-ttu-id="22a0e-113">คุณสามารถดูข้อมูลการวินิจฉัยที่ส่งถึงเราโดยใช้ตัวแสดงข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="22a0e-113">You can see the diagnostic data being sent to us by using the Diagnostic Data Viewer.</span></span>

<span data-ttu-id="22a0e-114">***ข้อมูลการวินิจฉัยเพิ่มเติม*** เป็นข้อมูลเพิ่มเติมที่ช่วยให้พวกเราสามารถปรับปรุงผลิตภัณฑ์และให้ข้อมูลที่ผ่านการเพิ่มประสิทธิภาพเพื่อช่วยให้เราตรวจหา วินิจฉัย และแก้ไขปัญหาได้</span><span class="sxs-lookup"><span data-stu-id="22a0e-114">***Optional diagnostic data*** is additional data that helps us make product improvements and provides enhanced information to help us detect, diagnose, and fix issues.</span></span>

<span data-ttu-id="22a0e-115">ถ้าคุณเลือกส่งข้อมูลการวินิจฉัยเพิ่มเติมถึงเรา จะมีข้อมูลการวินิจฉัยที่จำเป็นรวมอยู่ด้วย</span><span class="sxs-lookup"><span data-stu-id="22a0e-115">If you choose to send us optional diagnostic data, required diagnostic data is also included.</span></span>

<span data-ttu-id="22a0e-116">ตัวอย่างของข้อมูลการวินิจฉัยเพิ่มเติมมีข้อมูลที่เรารวบรวมเกี่ยวกับรูปภาพที่ผู้ใช้แทรกลงในเอกสาร Word เพื่อให้เราสามารถมอบตัวเลือกรูปที่ดีขึ้น และข้อมูลที่เรารวบรวมเกี่ยวกับเวลาที่ใช้ในการแสดงสไลด์ PowerPoint บนหน้าจอของคุณเพื่อให้เราสามารถปรับปรุงประสบการณ์ใช้งานได้ถ้าทำงานช้า</span><span class="sxs-lookup"><span data-stu-id="22a0e-116">Examples of optional diagnostic data include data we collect about the pictures users insert into Word documents so we can provide better image options, and data we collect about the time it takes for a PowerPoint slide to appear on your screen so we can improve the experience if it’s slow.</span></span>

<span data-ttu-id="22a0e-117">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัย ให้ดูที่หัวข้อต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-117">For more information about diagnostic data, see the following:</span></span>

- [<span data-ttu-id="22a0e-118">ข้อมูลการวินิจฉัยที่จำเป็นสำหรับ Office</span><span class="sxs-lookup"><span data-stu-id="22a0e-118">Required diagnostic data for Office</span></span>](required-diagnostic-data.md)
- [<span data-ttu-id="22a0e-119">การใช้ตัวแสดงข้อมูลการวินิจฉัยกับ Office</span><span class="sxs-lookup"><span data-stu-id="22a0e-119">Using the Diagnostic Data Viewer with Office</span></span>](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

<span data-ttu-id="22a0e-120">ถ้าคุณเป็นผู้ดูแลระบบสำหรับองค์กรของคุณ คุณอาจสนใจหัวข้อต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-120">If you’re the admin for your organization, you might also be interested in the following:</span></span>

- [<span data-ttu-id="22a0e-121">ภาพรวมของการควบคุมความเป็นส่วนตัวของ Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="22a0e-121">Overview of privacy controls for Office 365 ProPlus</span></span>](overview-privacy-controls.md)
- [<span data-ttu-id="22a0e-122">ใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวของ Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="22a0e-122">Use policy settings to manage privacy controls for Office 365 ProPlus</span></span>](manage-privacy-controls.md)

## <a name="categories-of-optional-diagnostic-data"></a><span data-ttu-id="22a0e-123">ประเภทของข้อมูลการวินิจฉัยเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="22a0e-123">Categories of optional diagnostic data</span></span>

<span data-ttu-id="22a0e-124">ข้อมูลการวินิจฉัยเพิ่มเติมจัดแบ่งเป็นประเภทต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-124">Optional diagnostic data is organized into the following categories:</span></span>

- <span data-ttu-id="22a0e-125">การตั้งค่าซอฟต์แวร์และสินค้าคงคลัง</span><span class="sxs-lookup"><span data-stu-id="22a0e-125">Software setup and inventory</span></span>
- <span data-ttu-id="22a0e-126">การใช้งานบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-126">Product and service usage</span></span>
- <span data-ttu-id="22a0e-127">ประสิทธิภาพของบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-127">Product and service performance</span></span>
- <span data-ttu-id="22a0e-128">การเชื่อมต่อและการกำหนดค่าของอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-128">Device connectivity and configuration</span></span>

<span data-ttu-id="22a0e-129">ประเภทเหล่านี้จะแสดงอยู่ในตัวแสดงข้อมูลการวินิจฉัย และเป็นประเภทเดียวกันกับที่ใช้กับข้อมูลการวินิจฉัยที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="22a0e-129">These categories are shown in the Diagnostic Data Viewer and are the same categories used with required diagnostic data.</span></span>

<span data-ttu-id="22a0e-130">ส่วนต่อไปนี้มีคำอธิบายของแต่ละประเภทและตัวอย่างของเหตุการณ์สำหรับแต่ละประเภท</span><span class="sxs-lookup"><span data-stu-id="22a0e-130">The following sections provide a description of each category and examples of events for each category.</span></span>

## <a name="software-setup-and-inventory-events"></a><span data-ttu-id="22a0e-131">เหตุการณ์ของการตั้งค่าซอฟต์แวร์และสินค้าคงคลัง</span><span class="sxs-lookup"><span data-stu-id="22a0e-131">Software setup and inventory events</span></span>

<span data-ttu-id="22a0e-132">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-132">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="22a0e-133">ผลิตภัณฑ์และเวอร์ชันที่ติดตั้งและสถานะการติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="22a0e-133">Installed product and version and the installation status</span></span>
- <span data-ttu-id="22a0e-134">Add-in ของซอฟต์แวร์และการตั้งค่า</span><span class="sxs-lookup"><span data-stu-id="22a0e-134">Software add-ins and their settings.</span></span>
- <span data-ttu-id="22a0e-135">เงื่อนไขของข้อผิดพลาดสำหรับเอกสาร ฟีเจอร์ และ Add-in ที่อาจลดการรักษาความปลอดภัยลง รวมถึงความพร้อมในการอัปเดตผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-135">Document, feature, and add-in error conditions that may compromise security, including product update readiness.</span></span>

<span data-ttu-id="22a0e-136">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="22a0e-136">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="22a0e-137">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-137">**Event name**</span></span>   | <span data-ttu-id="22a0e-138">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-138">**Event description**</span></span>  |
| ---- | ---- |
| <span data-ttu-id="22a0e-139">Office\_Extensibility\_AppCommands\_GetRibbonUpdatesForUserId</span><span class="sxs-lookup"><span data-stu-id="22a0e-139">Office\_Extensibility\_AppCommands\_GetRibbonUpdatesForUserId</span></span> | <span data-ttu-id="22a0e-140">เหตุการณ์นี้ระบุว่า Word อัปเดต Ribbon ในส่วนติดต่อผู้ใช้ของ Word ได้สำเร็จหรือไม่เมื่อผู้ใช้เปลี่ยนแปลงข้อมูลประจำตัวของตน</span><span class="sxs-lookup"><span data-stu-id="22a0e-140">This event indicates whether Word successfully updates the Ribbon in the Word User Interface when the user changes their identity.</span></span> <span data-ttu-id="22a0e-141">เราใช้เหตุการณ์นี้เพื่อตรวจสอบการตั้งค่าที่ไม่ถูกต้องและปัญหาอื่นๆ ที่อาจส่งผลต่อส่วนติดต่อผู้ใช้ของ Office</span><span class="sxs-lookup"><span data-stu-id="22a0e-141">We use this event to detect incorrect setup and other issues that would affect the Office user interface.</span></span> |
| <span data-ttu-id="22a0e-142">Office.Extensibility.AppCommands.AppCmdInstall</span><span class="sxs-lookup"><span data-stu-id="22a0e-142">Office.Extensibility.AppCommands.AppCmdInstall</span></span>   | <span data-ttu-id="22a0e-143">เหตุการณ์นี้มีข้อมูลเกี่ยวกับ Add-in ของ Office ที่ผู้ใช้ติดตั้ง รวมถึง ID แอป รุ่นและเวอร์ชันของระบบปฏิบัติการ ความสำเร็จของการติดตั้ง และระยะเวลาของการติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="22a0e-143">This event provides information about the Office add-in that the user has installed, including app ID, operating system build and version, success of installation, and duration of install.</span></span>  |

## <a name="product-and-service-usage-events"></a><span data-ttu-id="22a0e-144">เหตุการณ์ของการใช้งานบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-144">Product and service usage events</span></span>

<span data-ttu-id="22a0e-145">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-145">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="22a0e-146">ความสำเร็จของฟังก์ชันการทำงานของแอปพลิเคชัน</span><span class="sxs-lookup"><span data-stu-id="22a0e-146">Success of application functionality.</span></span> <span data-ttu-id="22a0e-147">จำกัดเฉพาะการเปิดและปิดแอปพลิเคชันและเอกสาร การแก้ไขไฟล์ และการแชร์ไฟล์ (การทำงานร่วมกัน)</span><span class="sxs-lookup"><span data-stu-id="22a0e-147">Limited to opening and closing of the application and documents, file editing, and file sharing (collaboration).</span></span>
- <span data-ttu-id="22a0e-148">การกำหนดว่าเหตุการณ์ของฟีเจอร์เฉพาะเกิดขึ้นหรือไม่ เช่น เริ่มหรือหยุด และฟีเจอร์กำลังทำงานอยู่หรือไม่</span><span class="sxs-lookup"><span data-stu-id="22a0e-148">Determination if specific feature events have occurred, such as start or stop, and if feature is running.</span></span>
- <span data-ttu-id="22a0e-149">ฟีเจอร์การช่วยสำหรับการเข้าถึง Office</span><span class="sxs-lookup"><span data-stu-id="22a0e-149">Office accessibility features</span></span>

<span data-ttu-id="22a0e-150">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="22a0e-150">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="22a0e-151">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-151">**Event name**</span></span>   | <span data-ttu-id="22a0e-152">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-152">**Event description**</span></span>  |
| ------ | ------- |
| <span data-ttu-id="22a0e-153">Office.Word.Commanding.Highlight</span><span class="sxs-lookup"><span data-stu-id="22a0e-153">Office.Word.Commanding.Highlight</span></span>  | <span data-ttu-id="22a0e-154">เหตุการณ์นี้ระบุว่า Word ได้ดำเนินการคำสั่งเพื่อเน้นข้อความ</span><span class="sxs-lookup"><span data-stu-id="22a0e-154">This event indicates Word has executed the command to highlight text.</span></span> <span data-ttu-id="22a0e-155">เราใช้เหตุการณ์นี้เพื่อตรวจสอบข้อผิดพลาดในคำสั่งการเน้นข้อความ</span><span class="sxs-lookup"><span data-stu-id="22a0e-155">We use this event to detect errors in the text-highlight command.</span></span>  |
| <span data-ttu-id="22a0e-156">Office.Translator.AddInLoaded</span><span class="sxs-lookup"><span data-stu-id="22a0e-156">Office.Translator.AddInLoaded</span></span>   | <span data-ttu-id="22a0e-157">ฮาร์ทบีทเพื่อระบุว่าฟีเจอร์ตัวแปลภาษาถูกโหลด และแสดงผลสำเร็จแล้ว</span><span class="sxs-lookup"><span data-stu-id="22a0e-157">A heartbeat to indicate that the translator feature has been loaded and rendered successfully.</span></span>  |
| <span data-ttu-id="22a0e-158">Office.Graphics.InsertPictureCommandActivity</span><span class="sxs-lookup"><span data-stu-id="22a0e-158">Office.Graphics.InsertPictureCommandActivity</span></span>  | <span data-ttu-id="22a0e-159">ติดตามความสำเร็จหรือความล้มเหลวของฟีเจอร์แทรกรูปภาพ และยังรายงานรายละเอียดเกี่ยวกับชนิดของรูปภาพที่แทรกและแหล่งที่มา</span><span class="sxs-lookup"><span data-stu-id="22a0e-159">Tracks the success or failure of the Insert Picture feature, and also reports details of types of pictures inserted and from which source.</span></span>|
| <span data-ttu-id="22a0e-160">Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule</span><span class="sxs-lookup"><span data-stu-id="22a0e-160">Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule</span></span>   | <span data-ttu-id="22a0e-161">เหตุการณ์นี้กำหนดว่ามีส่วนใดส่วนหนึ่งแสดงอยู่ในเอกสารเมื่อผู้ใช้แทรกการซูมสรุปหรือไม่ และผู้ใช้เลือกที่จะลบส่วนที่มีอยู่หรือไม่</span><span class="sxs-lookup"><span data-stu-id="22a0e-161">This event determines if there are any sections present in a document when the user is inserting Summary Zoom and if the user chooses to delete existing sections.</span></span> |
| <span data-ttu-id="22a0e-162">Office.Security.SecureReaderHost.ProtectedViewValidation</span><span class="sxs-lookup"><span data-stu-id="22a0e-162">Office.Security.SecureReaderHost.ProtectedViewValidation</span></span> | <span data-ttu-id="22a0e-163">ติดตามเวลาและสาเหตุที่มีการเปิดไฟล์ในมุมมองที่ได้รับการป้องกัน</span><span class="sxs-lookup"><span data-stu-id="22a0e-163">Tracks when and why a file is opened in Protected View.</span></span> <span data-ttu-id="22a0e-164">ใช้กับเงื่อนไขการวินิจฉัยที่มุมมองที่ได้รับการป้องกันอาจทริกเกอร์ไม่ถูกต้องเพื่อให้แน่ใจว่าฟีเจอร์ทำงานอย่างถูกต้อง</span><span class="sxs-lookup"><span data-stu-id="22a0e-164">Used to diagnose conditions where Protected View may not be correctly triggered to ensure the feature is working properly.</span></span> |

## <a name="product-and-service-performance-events"></a><span data-ttu-id="22a0e-165">เหตุการณ์ของประสิทธิภาพของบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-165">Product and service performance events</span></span>

<span data-ttu-id="22a0e-166">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-166">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="22a0e-167">แอปพลิเคชันจบการทำงานโดยไม่คาดคิด (การหยุดทำงาน) และสถานะของแอปพลิเคชันเมื่อเกิดเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-167">Unexpected application exits (crashes) and the state of the application when that happens.</span></span>
- <span data-ttu-id="22a0e-168">เวลาตอบสนองหรือประสิทธิภาพการทำงานต่ำสำหรับสถานการณ์ เช่น การเริ่มต้นแอปพลิเคชัน หรือการเปิดไฟล์</span><span class="sxs-lookup"><span data-stu-id="22a0e-168">Poor response time or performance for scenarios such as application start up or opening a file.</span></span>
- <span data-ttu-id="22a0e-169">ข้อผิดพลาดในฟังก์ชันการทำงานของฟีเจอร์หรือประสบการณ์ใช้งานของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="22a0e-169">Errors in functionality of a feature or user experience.</span></span>

<span data-ttu-id="22a0e-170">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="22a0e-170">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="22a0e-171">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-171">**Event name**</span></span>    | <span data-ttu-id="22a0e-172">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-172">**Event description**</span></span>   |
| --------------- | -------------- |
| <span data-ttu-id="22a0e-173">Office\_Word\_Word\_CoreSaveTime100ns</span><span class="sxs-lookup"><span data-stu-id="22a0e-173">Office\_Word\_Word\_CoreSaveTime100ns</span></span>     | <span data-ttu-id="22a0e-174">เหตุการณ์นี้บันทึกประสิทธิภาพการทำงานของกิจกรรมการบันทึกเอกสารโดย Word</span><span class="sxs-lookup"><span data-stu-id="22a0e-174">This event logs the performance of a document save activity by Word.</span></span> <span data-ttu-id="22a0e-175">เราใช้เหตุการณ์นี้เพื่อตรวจสอบข้อผิดพลาดและปัญหาประสิทธิภาพการทำงานในกิจกรรมการบันทึกเอกสารของ Word</span><span class="sxs-lookup"><span data-stu-id="22a0e-175">We use this event to detect errors and performance issues in the Word save document activity.</span></span>|
| <span data-ttu-id="22a0e-176">Office.Identity.SignInForWamAccountAad</span><span class="sxs-lookup"><span data-stu-id="22a0e-176">Office.Identity.SignInForWamAccountAad</span></span>  | <span data-ttu-id="22a0e-177">เหตุการณ์นี้จะถูกส่งเมื่อผู้ใช้ลงชื่อเข้าใช้บัญชี Azure Active Directory ที่มีไลบรารีระบบจัดการบัญชีบนเว็บ (WAM)</span><span class="sxs-lookup"><span data-stu-id="22a0e-177">This event is sent when a user is signed in to an Azure Active Directory account with Web Account Manager (WAM) library.</span></span> <span data-ttu-id="22a0e-178">เหตุการณ์นี้จะส่งเมตาดาต้า เช่น AppName, AppVersion และ ErrorCode ถ้าเหตุการณ์ล้มเหลว</span><span class="sxs-lookup"><span data-stu-id="22a0e-178">This event sends metadata such as AppName, AppVersion, and ErrorCode if the event failed.</span></span> |
| <span data-ttu-id="22a0e-179">Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime</span><span class="sxs-lookup"><span data-stu-id="22a0e-179">Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime</span></span> | <span data-ttu-id="22a0e-180">เหตุการณ์นี้รวบรวมระยะเวลาที่ใช้ในการแสดงรูปขนาดย่อต้นแบบของสไลด์แรกใน PowerPoint</span><span class="sxs-lookup"><span data-stu-id="22a0e-180">This event collects the length of time it takes to render the first slide master thumbnail in PowerPoint.</span></span>  |
| <span data-ttu-id="22a0e-181">Office.Extensibility.Diagnostics</span><span class="sxs-lookup"><span data-stu-id="22a0e-181">Office.Extensibility.Diagnostics</span></span>   | <span data-ttu-id="22a0e-182">เหตุการณ์นี้มีข้อมูลการวินิจฉัยทั่วไปสำหรับ Add-in ของ Office เช่น รายงานการหยุดทำงานสำหรับการแก้จุดบกพร่อง</span><span class="sxs-lookup"><span data-stu-id="22a0e-182">This event provides general diagnostic information for Office add-ins, such as crash reports for debugging.</span></span>|

## <a name="device-connectivity-and-configuration-events"></a><span data-ttu-id="22a0e-183">เหตุการณ์ของการเชื่อมต่อและการกำหนดค่าของอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="22a0e-183">Device connectivity and configuration events</span></span>

<span data-ttu-id="22a0e-184">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="22a0e-184">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="22a0e-185">สถานการเชื่อมต่อเครือข่ายและการตั้งค่าอุปกรณ์ เช่น หน่วยความจำ</span><span class="sxs-lookup"><span data-stu-id="22a0e-185">Network connection state and device settings, such as memory.</span></span>

<span data-ttu-id="22a0e-186">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="22a0e-186">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="22a0e-187">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-187">**Event name**</span></span>                    | <span data-ttu-id="22a0e-188">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="22a0e-188">**Event description**</span></span>                                                                                                                                                     |
| ------ | ----- |
| <span data-ttu-id="22a0e-189">Office\_Graphics\_ArtViewValidate</span><span class="sxs-lookup"><span data-stu-id="22a0e-189">Office\_Graphics\_ArtViewValidate</span></span> | <span data-ttu-id="22a0e-190">เหตุการณ์นี้บันทึกการตรวจสอบผลลัพธ์ของมุมมองกราฟิกที่สนับสนุนส่วนติดต่อผู้ใช้ของกราฟิก</span><span class="sxs-lookup"><span data-stu-id="22a0e-190">This event logs validation the results of Graphics View that supports Graphics User Interface.</span></span> <span data-ttu-id="22a0e-191">เราใช้เหตุการณ์เพื่อรวบรวมข้อมูลการใช้งานและข้อผิดพลาดเกี่ยวกับการแสดงผลกราฟิก</span><span class="sxs-lookup"><span data-stu-id="22a0e-191">We use the event to collect usage and error data about graphics rendering.</span></span> |
| <span data-ttu-id="22a0e-192">Office.Graphics.ARCExceptionScope</span><span class="sxs-lookup"><span data-stu-id="22a0e-192">Office.Graphics.ARCExceptionScope</span></span> | <span data-ttu-id="22a0e-193">เหตุการณ์นี้ติดตามความล้มเหลวในการแสดงผลที่มาจากโปรแกรมการแสดงผล</span><span class="sxs-lookup"><span data-stu-id="22a0e-193">This event tracks rendering failures coming from the rendering engine.</span></span> |
| <span data-ttu-id="22a0e-194">Office.Extensibility.ODPLatency</span><span class="sxs-lookup"><span data-stu-id="22a0e-194">Office.Extensibility.ODPLatency</span></span>   | <span data-ttu-id="22a0e-195">เหตุการณ์นี้มีข้อมูลเกี่ยวกับการเชื่อมต่อเครือข่ายและความเร็วของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="22a0e-195">This event provides information about the user’s network connection and speed.</span></span>     |
