---
title: ข้อมูลการวินิจฉัยเพิ่มเติมสำหรับ Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: ให้ข้อมูลแก่ผู้ดูแลระบบ Office เกี่ยวกับข้อมูลการวินิจฉัยเพิ่มเติมใน Office รวมถึงตัวอย่างเหตุการณ์บางอย่าง
hideEdit: true
ms.openlocfilehash: d772a649a78a88112a270e839834cbe48141217f
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510189"
---
# <a name="optional-diagnostic-data-for-office"></a><span data-ttu-id="2df9f-103">ข้อมูลการวินิจฉัยเพิ่มเติมสำหรับ Office</span><span class="sxs-lookup"><span data-stu-id="2df9f-103">Optional diagnostic data for Office</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2df9f-104">ข้อมูลในบทความนี้ใช้กับเวอร์ชัน 1904 ขึ้นไปของซอฟต์แวร์ไคลเอ็นต์ Office ต่อไปนี้ที่ติดตั้งบนคอมพิวเตอร์ที่ใช้ Windows:</span><span class="sxs-lookup"><span data-stu-id="2df9f-104">The information in this article applies to Version 1904 or later of the following Office client software installed on a computer running Windows:</span></span>
> - <span data-ttu-id="2df9f-105">Office 365 ProPlus และ Office 365 Business</span><span class="sxs-lookup"><span data-stu-id="2df9f-105">Office 365 ProPlus and Office 365 Business</span></span>
> - <span data-ttu-id="2df9f-106">Office 365 Personal, Office 365 Home หรือ Office เวอร์ชันอื่นที่เป็นส่วนหนึ่งของการสมัครใช้งาน Office 365</span><span class="sxs-lookup"><span data-stu-id="2df9f-106">Office 365 Personal, Office 365 Home, or other versions of Office that are part of an Office 365 subscription.</span></span>
> - <span data-ttu-id="2df9f-107">Project และ Visio ที่มีแผนการสมัครใช้งาน เช่น แผน Project Online Professional หรือ Visio Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="2df9f-107">Project and Visio that come with some subscription plans, such as the Project Online Professional plan or Visio Online Plan 2.</span></span>
>
> <span data-ttu-id="2df9f-108">ข้อมูลยังใช้กับเวอร์ชัน 16.28 หรือใหม่กว่าของแอปพลิเคชัน Office for Mac ดังต่อไปนี้: Excel, Outlook, OneNote, PowerPoint และ Word</span><span class="sxs-lookup"><span data-stu-id="2df9f-108">The information also applies to Version 16.28 or later of the following Office for Mac applications: Excel, Outlook, OneNote, PowerPoint, and Word.</span></span>

<span data-ttu-id="2df9f-109">ข้อมูลการวินิจฉัยมีไว้เพื่อรักษาความปลอดภัย อัปเดต ตรวจหา วินิจฉัย และแก้ไขปัญหาใน Office รวมถึงการปรับปรุงผลิตภัณฑ์ด้วย</span><span class="sxs-lookup"><span data-stu-id="2df9f-109">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and fix problems, and also make product improvements.</span></span> <span data-ttu-id="2df9f-110">ข้อมูลนี้จะไม่มีชื่อหรือที่อยู่อีเมลของผู้ใช้ เนื้อหาไฟล์ของผู้ใช้ หรือข้อมูลเกี่ยวกับแอปที่ไม่เกี่ยวข้องกับ Office</span><span class="sxs-lookup"><span data-stu-id="2df9f-110">This data does not include a user’s name or email address, the content of the user’s files, or information about apps unrelated to Office.</span></span>

<span data-ttu-id="2df9f-111">ข้อมูลการวินิจฉัยนี้จะรวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ทำงานบนคอมพิวเตอร์ที่ใช้ Windows</span><span class="sxs-lookup"><span data-stu-id="2df9f-111">This diagnostic data is collected and sent to Microsoft about Office client software being used on computers running Windows.</span></span> <span data-ttu-id="2df9f-112">จำเป็นต้องระบุข้อมูลการวินิจฉัยบางอย่าง ขณะที่ข้อมูลการวินิจฉัยบางอย่างสามารถระบุหรือไม่ก็ได้</span><span class="sxs-lookup"><span data-stu-id="2df9f-112">Some diagnostic data is required, while some diagnostic data is optional.</span></span> <span data-ttu-id="2df9f-113">เราให้ความสามารถในการเลือกว่าจะส่งข้อมูลการวินิจฉัยที่จำเป็นหรือเพิ่มเติมให้เราผ่านการใช้การควบคุมความเป็นส่วนตัวหรือไม่ เช่น การตั้งค่านโยบายสำหรับองค์กร</span><span class="sxs-lookup"><span data-stu-id="2df9f-113">We give you the ability to choose whether to send us required or optional diagnostic data through the use of privacy controls, such as policy settings for organizations.</span></span> <span data-ttu-id="2df9f-114">คุณสามารถดูข้อมูลการวินิจฉัยที่ส่งถึงเราโดยใช้ตัวแสดงข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="2df9f-114">You can see the diagnostic data being sent to us by using the Diagnostic Data Viewer.</span></span>

<span data-ttu-id="2df9f-115">***ข้อมูลการวินิจฉัยเพิ่มเติม*** เป็นข้อมูลเพิ่มเติมที่ช่วยให้พวกเราสามารถปรับปรุงผลิตภัณฑ์และให้ข้อมูลที่ผ่านการเพิ่มประสิทธิภาพเพื่อช่วยให้เราตรวจหา วินิจฉัย และแก้ไขปัญหาได้</span><span class="sxs-lookup"><span data-stu-id="2df9f-115">***Optional diagnostic data*** is additional data that helps us make product improvements and provides enhanced information to help us detect, diagnose, and fix issues.</span></span>

<span data-ttu-id="2df9f-116">ถ้าคุณเลือกส่งข้อมูลการวินิจฉัยเพิ่มเติมถึงเรา จะมีข้อมูลการวินิจฉัยที่จำเป็นรวมอยู่ด้วย</span><span class="sxs-lookup"><span data-stu-id="2df9f-116">If you choose to send us optional diagnostic data, required diagnostic data is also included.</span></span>

<span data-ttu-id="2df9f-117">ตัวอย่างของข้อมูลการวินิจฉัยเพิ่มเติมมีข้อมูลที่เรารวบรวมเกี่ยวกับรูปร่างที่ผู้ใช้แทรกลงในเอกสาร Word เพื่อให้เราสามารถให้ตัวเลือกที่ดียิ่งขึ้น และข้อมูลที่เรารวบรวมเกี่ยวกับเวลาที่ใช้ในการแสดงสไลด์ PowerPoint บนหน้าจอของคุณเพื่อให้เราสามารถปรับปรุงประสบการณ์ใช้งานได้ถ้าทำงานช้า</span><span class="sxs-lookup"><span data-stu-id="2df9f-117">Examples of optional diagnostic data include data we collect about the pictures users insert into Word documents so we can provide better image options, and data we collect about the time it takes for a PowerPoint slide to appear on your screen so we can improve the experience if it’s slow.</span></span>

<span data-ttu-id="2df9f-118">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัย ให้ดูที่หัวข้อต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-118">For more information about diagnostic data, see the following:</span></span>

- [<span data-ttu-id="2df9f-119">ข้อมูลการวินิจฉัยที่จำเป็นสำหรับ Office</span><span class="sxs-lookup"><span data-stu-id="2df9f-119">Required diagnostic data for Office</span></span>](required-diagnostic-data.md)
- [<span data-ttu-id="2df9f-120">การใช้ตัวแสดงข้อมูลการวินิจฉัยกับ Office</span><span class="sxs-lookup"><span data-stu-id="2df9f-120">Using the Diagnostic Data Viewer with Office</span></span>](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

<span data-ttu-id="2df9f-121">ถ้าคุณเป็นผู้ดูแลระบบสำหรับองค์กรของคุณ คุณอาจสนใจหัวข้อต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-121">If you’re the admin for your organization, you might also be interested in the following:</span></span>

- [<span data-ttu-id="2df9f-122">ภาพรวมของการควบคุมความเป็นส่วนตัวของ Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="2df9f-122">Overview of privacy controls for Office 365 ProPlus</span></span>](overview-privacy-controls.md)
- [<span data-ttu-id="2df9f-123">ใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวของ Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="2df9f-123">Use policy settings to manage privacy controls for Office 365 ProPlus</span></span>](manage-privacy-controls.md)
- [<span data-ttu-id="2df9f-124">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office for Mac</span><span class="sxs-lookup"><span data-stu-id="2df9f-124">Use preferences to manage privacy controls for Office for Mac</span></span>](mac-privacy-preferences.md)
- [<span data-ttu-id="2df9f-125">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ iOS</span><span class="sxs-lookup"><span data-stu-id="2df9f-125">Use preferences to manage privacy controls for Office for Mac</span></span>](ios-privacy-preferences.md)

## <a name="categories-of-optional-diagnostic-data"></a><span data-ttu-id="2df9f-126">ประเภทของข้อมูลการวินิจฉัยเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="2df9f-126">Categories of optional diagnostic data</span></span>

<span data-ttu-id="2df9f-127">ข้อมูลการวินิจฉัยเพิ่มเติมจัดแบ่งเป็นประเภทต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-127">Optional diagnostic data is organized into the following categories:</span></span>

- <span data-ttu-id="2df9f-128">การตั้งค่าซอฟต์แวร์และสินค้าคงคลัง</span><span class="sxs-lookup"><span data-stu-id="2df9f-128">Software setup and inventory</span></span>
- <span data-ttu-id="2df9f-129">การใช้งานบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-129">Product and service usage</span></span>
- <span data-ttu-id="2df9f-130">ประสิทธิภาพของบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-130">Product and service performance</span></span>
- <span data-ttu-id="2df9f-131">การเชื่อมต่อและการกำหนดค่าของอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-131">Device connectivity and configuration</span></span>

<span data-ttu-id="2df9f-132">ประเภทเหล่านี้จะแสดงอยู่ในตัวแสดงข้อมูลการวินิจฉัย และเป็นประเภทเดียวกันกับที่ใช้กับข้อมูลการวินิจฉัยที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="2df9f-132">These categories are shown in the Diagnostic Data Viewer and are the same categories used with required diagnostic data.</span></span>

<span data-ttu-id="2df9f-133">ส่วนต่อไปนี้มีคำอธิบายของแต่ละประเภทและตัวอย่างของเหตุการณ์สำหรับแต่ละประเภท</span><span class="sxs-lookup"><span data-stu-id="2df9f-133">The following sections provide a description of each category and examples of events for each category.</span></span>

## <a name="software-setup-and-inventory-events"></a><span data-ttu-id="2df9f-134">เหตุการณ์ของการตั้งค่าซอฟต์แวร์และสินค้าคงคลัง</span><span class="sxs-lookup"><span data-stu-id="2df9f-134">Software setup and inventory events</span></span>

<span data-ttu-id="2df9f-135">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-135">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="2df9f-136">ผลิตภัณฑ์และเวอร์ชันที่ติดตั้งและสถานะการติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="2df9f-136">Installed product and version and the installation status</span></span>
- <span data-ttu-id="2df9f-137">Add-in ของซอฟต์แวร์และการตั้งค่า</span><span class="sxs-lookup"><span data-stu-id="2df9f-137">Software add-ins and their settings.</span></span>
- <span data-ttu-id="2df9f-138">เงื่อนไขของข้อผิดพลาดสำหรับเอกสาร ฟีเจอร์ และ Add-in ที่อาจลดการรักษาความปลอดภัยลง รวมถึงความพร้อมในการอัปเดตผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-138">Document, feature, and add-in error conditions that may compromise security, including product update readiness.</span></span>

<span data-ttu-id="2df9f-139">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="2df9f-139">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="2df9f-140">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-140">**Event name**</span></span>   | <span data-ttu-id="2df9f-141">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-141">**Event description**</span></span>  |
| ---- | ---- |
| <span data-ttu-id="2df9f-142">Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId</span><span class="sxs-lookup"><span data-stu-id="2df9f-142">OfficeExtensibilityAppCommandsGetRibbonUpdatesForUserId</span></span> | <span data-ttu-id="2df9f-143">เหตุการณ์นี้ระบุว่า Word อัปเดต Ribbon ในส่วนติดต่อผู้ใช้ของ Word ได้สำเร็จหรือไม่เมื่อผู้ใช้เปลี่ยนแปลงข้อมูลประจำตัวของตน</span><span class="sxs-lookup"><span data-stu-id="2df9f-143">This event indicates whether Word successfully updates the Ribbon in the Word User Interface when the user changes their identity.</span></span> <span data-ttu-id="2df9f-144">เราใช้เหตุการณ์นี้เพื่อตรวจสอบการตั้งค่าที่ไม่ถูกต้องและปัญหาอื่นๆ ที่อาจส่งผลต่อส่วนติดต่อผู้ใช้ของ Office</span><span class="sxs-lookup"><span data-stu-id="2df9f-144">We use this event to detect incorrect setup and other issues that would affect the Office user interface.</span></span> |
| <span data-ttu-id="2df9f-145">Office.Extensibility.AppCommands.AppCmdInstall</span><span class="sxs-lookup"><span data-stu-id="2df9f-145">Office.Extensibility.AppCommands.AppCmdInstall</span></span>   | <span data-ttu-id="2df9f-146">เหตุการณ์นี้มีข้อมูลเกี่ยวกับ Add-in ของ Office ที่ผู้ใช้ติดตั้ง รวมถึง ID แอป รุ่นและเวอร์ชันของระบบปฏิบัติการ ความสำเร็จของการติดตั้ง และระยะเวลาของการติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="2df9f-146">This event provides information about the Office add-in that the user has installed, including app ID, operating system build and version, success of installation, and duration of install.</span></span>  |

## <a name="product-and-service-usage-events"></a><span data-ttu-id="2df9f-147">เหตุการณ์ของการใช้งานบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-147">Product and service usage events</span></span>

<span data-ttu-id="2df9f-148">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-148">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="2df9f-149">ความสำเร็จของฟังก์ชันการทำงานของแอปพลิเคชัน</span><span class="sxs-lookup"><span data-stu-id="2df9f-149">Success of application functionality.</span></span> <span data-ttu-id="2df9f-150">จำกัดเฉพาะการเปิดและปิดแอปพลิเคชันและเอกสาร การแก้ไขไฟล์ และการแชร์ไฟล์ (การทำงานร่วมกัน)</span><span class="sxs-lookup"><span data-stu-id="2df9f-150">Limited to opening and closing of the application and documents, file editing, and file sharing (collaboration).</span></span>
- <span data-ttu-id="2df9f-151">การกำหนดว่าเหตุการณ์ของฟีเจอร์เฉพาะเกิดขึ้นหรือไม่ เช่น เริ่มหรือหยุด และฟีเจอร์กำลังทำงานอยู่หรือไม่</span><span class="sxs-lookup"><span data-stu-id="2df9f-151">Determination if specific feature events have occurred, such as start or stop, and if feature is running.</span></span>
- <span data-ttu-id="2df9f-152">ฟีเจอร์การช่วยสำหรับการเข้าถึง Office</span><span class="sxs-lookup"><span data-stu-id="2df9f-152">Office accessibility features</span></span>

<span data-ttu-id="2df9f-153">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="2df9f-153">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="2df9f-154">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-154">**Event name**</span></span>   | <span data-ttu-id="2df9f-155">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-155">**Event description**</span></span>  |
| ------ | ------- |
| <span data-ttu-id="2df9f-156">Office.Word.Commanding.Highlight</span><span class="sxs-lookup"><span data-stu-id="2df9f-156">Office.Word.Commanding.Highlight</span></span>  | <span data-ttu-id="2df9f-157">เหตุการณ์นี้ระบุว่า Word ได้ดำเนินการคำสั่งเพื่อเน้นข้อความ</span><span class="sxs-lookup"><span data-stu-id="2df9f-157">This event indicates Word has executed the command to highlight text.</span></span> <span data-ttu-id="2df9f-158">เราใช้เหตุการณ์นี้เพื่อตรวจสอบข้อผิดพลาดในคำสั่งการเน้นข้อความ</span><span class="sxs-lookup"><span data-stu-id="2df9f-158">We use this event to detect errors in the text-highlight command.</span></span>  |
| <span data-ttu-id="2df9f-159">Office.Translator.AddInLoaded</span><span class="sxs-lookup"><span data-stu-id="2df9f-159">Office.Translator.AddInLoaded</span></span>   | <span data-ttu-id="2df9f-160">ฮาร์ทบีทเพื่อระบุว่าฟีเจอร์ตัวแปลภาษาถูกโหลด และแสดงผลสำเร็จแล้ว</span><span class="sxs-lookup"><span data-stu-id="2df9f-160">A heartbeat to indicate that the translator feature has been loaded and rendered successfully.</span></span>  |
| <span data-ttu-id="2df9f-161">Office.Graphics.GVizInsertShape</span><span class="sxs-lookup"><span data-stu-id="2df9f-161">Office.Graphics.GVizInsertShape</span></span> |<span data-ttu-id="2df9f-162">ติดตามการใช้งานฟีเจอร์แทรกรูปร่างใน Word และยังรายงานรายละเอียดเกี่ยวกับชนิดของรูปร่างที่แทรกและแหล่งที่มา</span><span class="sxs-lookup"><span data-stu-id="2df9f-162">Tracks the success or failure of the Insert Picture feature, and also reports details of types of pictures inserted and from which source.</span></span>| 
| <span data-ttu-id="2df9f-163">Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule</span><span class="sxs-lookup"><span data-stu-id="2df9f-163">Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule</span></span>   | <span data-ttu-id="2df9f-164">เหตุการณ์นี้กำหนดว่ามีส่วนใดส่วนหนึ่งแสดงอยู่ในเอกสารเมื่อผู้ใช้แทรกการซูมสรุปหรือไม่ และผู้ใช้เลือกที่จะลบส่วนที่มีอยู่หรือไม่</span><span class="sxs-lookup"><span data-stu-id="2df9f-164">This event determines if there are any sections present in a document when the user is inserting Summary Zoom and if the user chooses to delete existing sections.</span></span> |
| <span data-ttu-id="2df9f-165">Office.Security.SecureReaderHost.ProtectedViewValidation</span><span class="sxs-lookup"><span data-stu-id="2df9f-165">Office.Security.SecureReaderHost.ProtectedViewValidation</span></span> | <span data-ttu-id="2df9f-166">ติดตามเวลาและสาเหตุที่มีการเปิดไฟล์ในมุมมองที่ได้รับการป้องกัน</span><span class="sxs-lookup"><span data-stu-id="2df9f-166">Tracks when and why a file is opened in Protected View.</span></span> <span data-ttu-id="2df9f-167">ใช้กับเงื่อนไขการวินิจฉัยที่มุมมองที่ได้รับการป้องกันอาจทริกเกอร์ไม่ถูกต้องเพื่อให้แน่ใจว่าฟีเจอร์ทำงานอย่างถูกต้อง</span><span class="sxs-lookup"><span data-stu-id="2df9f-167">Used to diagnose conditions where Protected View may not be correctly triggered to ensure the feature is working properly.</span></span> |

## <a name="product-and-service-performance-events"></a><span data-ttu-id="2df9f-168">เหตุการณ์ของประสิทธิภาพของบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-168">Product and service performance events</span></span>

<span data-ttu-id="2df9f-169">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-169">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="2df9f-170">แอปพลิเคชันจบการทำงานโดยไม่คาดคิด (การหยุดทำงาน) และสถานะของแอปพลิเคชันเมื่อเกิดเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-170">Unexpected application exits (crashes) and the state of the application when that happens.</span></span>
- <span data-ttu-id="2df9f-171">เวลาตอบสนองหรือประสิทธิภาพการทำงานต่ำสำหรับสถานการณ์ เช่น การเริ่มต้นแอปพลิเคชัน หรือการเปิดไฟล์</span><span class="sxs-lookup"><span data-stu-id="2df9f-171">Poor response time or performance for scenarios such as application start up or opening a file.</span></span>
- <span data-ttu-id="2df9f-172">ข้อผิดพลาดในฟังก์ชันการทำงานของฟีเจอร์หรือประสบการณ์ใช้งานของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="2df9f-172">Errors in functionality of a feature or user experience.</span></span>

<span data-ttu-id="2df9f-173">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="2df9f-173">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="2df9f-174">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-174">**Event name**</span></span>    | <span data-ttu-id="2df9f-175">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-175">**Event description**</span></span>   |
| --------------- | -------------- |
| <span data-ttu-id="2df9f-176">Office.Word.Word.CoreSaveTime100ns</span><span class="sxs-lookup"><span data-stu-id="2df9f-176">OfficeWordWordCoreSaveTime100ns</span></span>     | <span data-ttu-id="2df9f-177">เหตุการณ์นี้บันทึกประสิทธิภาพการทำงานของกิจกรรมการบันทึกเอกสารโดย Word</span><span class="sxs-lookup"><span data-stu-id="2df9f-177">This event logs the performance of a document save activity by Word.</span></span> <span data-ttu-id="2df9f-178">เราใช้เหตุการณ์นี้เพื่อตรวจสอบข้อผิดพลาดและปัญหาประสิทธิภาพการทำงานในกิจกรรมการบันทึกเอกสารของ Word</span><span class="sxs-lookup"><span data-stu-id="2df9f-178">We use this event to detect errors and performance issues in the Word save document activity.</span></span>|
| <span data-ttu-id="2df9f-179">Office.Identity.SignInForWamAccountAad</span><span class="sxs-lookup"><span data-stu-id="2df9f-179">Office.Identity.SignInForWamAccountAad</span></span>  | <span data-ttu-id="2df9f-180">เหตุการณ์นี้จะถูกส่งเมื่อผู้ใช้ลงชื่อเข้าใช้บัญชี Azure Active Directory ที่มีไลบรารีระบบจัดการบัญชีบนเว็บ (WAM)</span><span class="sxs-lookup"><span data-stu-id="2df9f-180">This event is sent when a user is signed in to an Azure Active Directory account with Web Account Manager (WAM) library.</span></span> <span data-ttu-id="2df9f-181">เหตุการณ์นี้จะส่งเมตาดาต้า เช่น AppName, AppVersion และ ErrorCode ถ้าเหตุการณ์ล้มเหลว</span><span class="sxs-lookup"><span data-stu-id="2df9f-181">This event sends metadata such as AppName, AppVersion, and ErrorCode if the event failed.</span></span> |
| <span data-ttu-id="2df9f-182">Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime</span><span class="sxs-lookup"><span data-stu-id="2df9f-182">Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime</span></span> | <span data-ttu-id="2df9f-183">เหตุการณ์นี้รวบรวมระยะเวลาที่ใช้ในการแสดงรูปขนาดย่อต้นแบบของสไลด์แรกใน PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2df9f-183">This event collects the length of time it takes to render the first slide master thumbnail in PowerPoint.</span></span>  |
| <span data-ttu-id="2df9f-184">Office.Extensibility.Diagnostics</span><span class="sxs-lookup"><span data-stu-id="2df9f-184">Office.Extensibility.Diagnostics</span></span>   | <span data-ttu-id="2df9f-185">เหตุการณ์นี้มีข้อมูลการวินิจฉัยทั่วไปสำหรับ Add-in ของ Office เช่น รายงานการหยุดทำงานสำหรับการแก้จุดบกพร่อง</span><span class="sxs-lookup"><span data-stu-id="2df9f-185">This event provides general diagnostic information for Office add-ins, such as crash reports for debugging.</span></span>|

## <a name="device-connectivity-and-configuration-events"></a><span data-ttu-id="2df9f-186">เหตุการณ์ของการเชื่อมต่อและการกำหนดค่าของอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="2df9f-186">Device connectivity and configuration events</span></span>

<span data-ttu-id="2df9f-187">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="2df9f-187">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="2df9f-188">สถานการเชื่อมต่อเครือข่ายและการตั้งค่าอุปกรณ์ เช่น หน่วยความจำ</span><span class="sxs-lookup"><span data-stu-id="2df9f-188">Network connection state and device settings, such as memory.</span></span>

<span data-ttu-id="2df9f-189">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="2df9f-189">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="2df9f-190">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-190">**Event name**</span></span>                    | <span data-ttu-id="2df9f-191">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="2df9f-191">**Event description**</span></span>                                                                                                                                                     |
| ------ | ----- |
| <span data-ttu-id="2df9f-192">Office.Graphics.ArtViewValidate</span><span class="sxs-lookup"><span data-stu-id="2df9f-192">OfficeGraphicsArtViewValidate</span></span> | <span data-ttu-id="2df9f-193">เหตุการณ์นี้บันทึกการตรวจสอบผลลัพธ์ของมุมมองกราฟิกที่สนับสนุนส่วนติดต่อผู้ใช้ของกราฟิก</span><span class="sxs-lookup"><span data-stu-id="2df9f-193">This event logs validation the results of Graphics View that supports Graphics User Interface.</span></span> <span data-ttu-id="2df9f-194">เราใช้เหตุการณ์เพื่อรวบรวมข้อมูลการใช้งานและข้อผิดพลาดเกี่ยวกับการแสดงผลกราฟิก</span><span class="sxs-lookup"><span data-stu-id="2df9f-194">We use the event to collect usage and error data about graphics rendering.</span></span> |
| <span data-ttu-id="2df9f-195">Office.Graphics.ARCExceptionScope</span><span class="sxs-lookup"><span data-stu-id="2df9f-195">Office.Graphics.ARCExceptionScope</span></span> | <span data-ttu-id="2df9f-196">เหตุการณ์นี้ติดตามความล้มเหลวในการแสดงผลที่มาจากโปรแกรมการแสดงผล</span><span class="sxs-lookup"><span data-stu-id="2df9f-196">This event tracks rendering failures coming from the rendering engine.</span></span> |
| <span data-ttu-id="2df9f-197">Office.Extensibility.ODPLatency</span><span class="sxs-lookup"><span data-stu-id="2df9f-197">Office.Extensibility.ODPLatency</span></span>   | <span data-ttu-id="2df9f-198">เหตุการณ์นี้มีข้อมูลเกี่ยวกับการเชื่อมต่อเครือข่ายและความเร็วของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="2df9f-198">This event provides information about the user’s network connection and speed.</span></span>     |
