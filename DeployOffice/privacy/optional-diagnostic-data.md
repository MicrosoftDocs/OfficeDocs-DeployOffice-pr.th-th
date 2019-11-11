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
ms.openlocfilehash: ab40e68df1ed91b1aff7510383d47967e8f13ccb
ms.sourcegitcommit: acb22296532bbfdfcad4dc1e7162f812997fbdd1
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 11/08/2019
ms.locfileid: "38067121"
---
# <a name="optional-diagnostic-data-for-office"></a><span data-ttu-id="d514a-103">ข้อมูลการวินิจฉัยเพิ่มเติมสำหรับ Office</span><span class="sxs-lookup"><span data-stu-id="d514a-103">Optional diagnostic data for Office</span></span>

> [!IMPORTANT]
> <span data-ttu-id="d514a-104">ข้อมูลในบทความนี้ใช้กับเวอร์ชัน 1904 ขึ้นไปของซอฟต์แวร์ไคลเอ็นต์ Office ต่อไปนี้ที่ติดตั้งบนคอมพิวเตอร์ที่ใช้ Windows:</span><span class="sxs-lookup"><span data-stu-id="d514a-104">The information in this article applies to Version 1904 or later of the following Office client software installed on a computer running Windows:</span></span>
> - <span data-ttu-id="d514a-105">Office 365 ProPlus และ Office 365 Business</span><span class="sxs-lookup"><span data-stu-id="d514a-105">Office 365 ProPlus and Office 365 Business</span></span>
> - <span data-ttu-id="d514a-106">Office 365 Personal, Office 365 Home หรือ Office เวอร์ชันอื่นที่เป็นส่วนหนึ่งของการสมัครใช้งาน Office 365</span><span class="sxs-lookup"><span data-stu-id="d514a-106">Office 365 Personal, Office 365 Home, or other versions of Office that are part of an Office 365 subscription.</span></span>
> - <span data-ttu-id="d514a-107">Project และ Visio ที่มีแผนการสมัครใช้งาน เช่น แผน Project Online Professional หรือ Visio Online Plan 2</span><span class="sxs-lookup"><span data-stu-id="d514a-107">Project and Visio that come with some subscription plans, such as the Project Online Professional plan or Visio Online Plan 2.</span></span>
>
> <span data-ttu-id="d514a-108">ข้อมูลยังใช้กับเวอร์ชัน 16.28 หรือใหม่กว่าของแอปพลิเคชัน Office for Mac ดังต่อไปนี้: Excel, Outlook, OneNote, PowerPoint และ Word</span><span class="sxs-lookup"><span data-stu-id="d514a-108">The information also applies to Version 16.28 or later of the following Office for Mac applications: Excel, Outlook, OneNote, PowerPoint, and Word.</span></span>

<span data-ttu-id="d514a-109">ข้อมูลการวินิจฉัยมีไว้เพื่อรักษาความปลอดภัย อัปเดต ตรวจหา วินิจฉัย และแก้ไขปัญหาใน Office รวมถึงการปรับปรุงผลิตภัณฑ์ด้วย</span><span class="sxs-lookup"><span data-stu-id="d514a-109">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and fix problems, and also make product improvements.</span></span> <span data-ttu-id="d514a-110">ข้อมูลนี้จะไม่มีชื่อหรือที่อยู่อีเมลของผู้ใช้ เนื้อหาไฟล์ของผู้ใช้ หรือข้อมูลเกี่ยวกับแอปที่ไม่เกี่ยวข้องกับ Office</span><span class="sxs-lookup"><span data-stu-id="d514a-110">This data does not include a user’s name or email address, the content of the user’s files, or information about apps unrelated to Office.</span></span>

<span data-ttu-id="d514a-111">ข้อมูลการวินิจฉัยนี้จะรวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ทำงานบนคอมพิวเตอร์ที่ใช้ Windows</span><span class="sxs-lookup"><span data-stu-id="d514a-111">This diagnostic data is collected and sent to Microsoft about Office client software being used on computers running Windows.</span></span> <span data-ttu-id="d514a-112">จำเป็นต้องระบุข้อมูลการวินิจฉัยบางอย่าง ขณะที่ข้อมูลการวินิจฉัยบางอย่างสามารถระบุหรือไม่ก็ได้</span><span class="sxs-lookup"><span data-stu-id="d514a-112">Some diagnostic data is required, while some diagnostic data is optional.</span></span> <span data-ttu-id="d514a-113">เราให้ความสามารถในการเลือกว่าจะส่งข้อมูลการวินิจฉัยที่จำเป็นหรือเพิ่มเติมให้เราผ่านการใช้การควบคุมความเป็นส่วนตัวหรือไม่ เช่น การตั้งค่านโยบายสำหรับองค์กร</span><span class="sxs-lookup"><span data-stu-id="d514a-113">We give you the ability to choose whether to send us required or optional diagnostic data through the use of privacy controls, such as policy settings for organizations.</span></span> <span data-ttu-id="d514a-114">คุณสามารถดูข้อมูลการวินิจฉัยที่ส่งถึงเราโดยใช้ตัวแสดงข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="d514a-114">You can see the diagnostic data being sent to us by using the Diagnostic Data Viewer.</span></span>

<span data-ttu-id="d514a-115">***ข้อมูลการวินิจฉัยเพิ่มเติม*** เป็นข้อมูลเพิ่มเติมที่ช่วยให้พวกเราสามารถปรับปรุงผลิตภัณฑ์และให้ข้อมูลที่ผ่านการเพิ่มประสิทธิภาพเพื่อช่วยให้เราตรวจหา วินิจฉัย และแก้ไขปัญหาได้</span><span class="sxs-lookup"><span data-stu-id="d514a-115">***Optional diagnostic data*** is additional data that helps us make product improvements and provides enhanced information to help us detect, diagnose, and fix issues.</span></span>

<span data-ttu-id="d514a-116">ถ้าคุณเลือกส่งข้อมูลการวินิจฉัยเพิ่มเติมถึงเรา จะมีข้อมูลการวินิจฉัยที่จำเป็นรวมอยู่ด้วย</span><span class="sxs-lookup"><span data-stu-id="d514a-116">If you choose to send us optional diagnostic data, required diagnostic data is also included.</span></span>

<span data-ttu-id="d514a-117">ตัวอย่างของข้อมูลการวินิจฉัยเพิ่มเติมมีข้อมูลที่เรารวบรวมเกี่ยวกับรูปร่างที่ผู้ใช้แทรกลงในเอกสาร Word เพื่อให้เราสามารถให้ตัวเลือกที่ดียิ่งขึ้น และข้อมูลที่เรารวบรวมเกี่ยวกับเวลาที่ใช้ในการแสดงสไลด์ PowerPoint บนหน้าจอของคุณเพื่อให้เราสามารถปรับปรุงประสบการณ์ใช้งานได้ถ้าทำงานช้า</span><span class="sxs-lookup"><span data-stu-id="d514a-117">Examples of optional diagnostic data include data we collect about the shapes users insert into Word documents so we can provide better options, and data we collect about the time it takes for a PowerPoint slide to appear on your screen so we can improve the experience if it’s slow.</span></span>

<span data-ttu-id="d514a-118">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัย ให้ดูที่หัวข้อต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-118">For more information about diagnostic data, see the following:</span></span>

- [<span data-ttu-id="d514a-119">ข้อมูลการวินิจฉัยที่จำเป็นสำหรับ Office</span><span class="sxs-lookup"><span data-stu-id="d514a-119">Required diagnostic data for Office</span></span>](required-diagnostic-data.md)
- [<span data-ttu-id="d514a-120">การใช้ตัวแสดงข้อมูลการวินิจฉัยกับ Office</span><span class="sxs-lookup"><span data-stu-id="d514a-120">Using the Diagnostic Data Viewer with Office</span></span>](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

<span data-ttu-id="d514a-121">ถ้าคุณเป็นผู้ดูแลระบบสำหรับองค์กรของคุณ คุณอาจสนใจหัวข้อต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-121">If you’re the admin for your organization, you might also be interested in the following:</span></span>

- [<span data-ttu-id="d514a-122">ภาพรวมของการควบคุมความเป็นส่วนตัวของ Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="d514a-122">Overview of privacy controls for Office 365 ProPlus</span></span>](overview-privacy-controls.md)
- [<span data-ttu-id="d514a-123">ใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวของ Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="d514a-123">Use policy settings to manage privacy controls for Office 365 ProPlus</span></span>](manage-privacy-controls.md)
- [<span data-ttu-id="d514a-124">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office for Mac</span><span class="sxs-lookup"><span data-stu-id="d514a-124">Use preferences to manage privacy controls for Office for Mac</span></span>](mac-privacy-preferences.md)
- [<span data-ttu-id="d514a-125">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ iOS</span><span class="sxs-lookup"><span data-stu-id="d514a-125">Use preferences to manage privacy controls for Office on iOS devices</span></span>](ios-privacy-preferences.md)
- [<span data-ttu-id="d514a-126">ใช้การตั้งค่านโยบายเพื่อจัดการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ Android</span><span class="sxs-lookup"><span data-stu-id="d514a-126">Use preferences to manage privacy controls for Office on iOS devices</span></span>](android-privacy-controls.md)

## <a name="categories-of-optional-diagnostic-data"></a><span data-ttu-id="d514a-127">ประเภทของข้อมูลการวินิจฉัยเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="d514a-127">Categories of optional diagnostic data</span></span>

<span data-ttu-id="d514a-128">ข้อมูลการวินิจฉัยเพิ่มเติมจัดแบ่งเป็นประเภทต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-128">Optional diagnostic data is organized into the following categories:</span></span>

- <span data-ttu-id="d514a-129">การตั้งค่าซอฟต์แวร์และสินค้าคงคลัง</span><span class="sxs-lookup"><span data-stu-id="d514a-129">Software setup and inventory</span></span>
- <span data-ttu-id="d514a-130">การใช้งานบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="d514a-130">Product and service usage</span></span>
- <span data-ttu-id="d514a-131">ประสิทธิภาพของบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="d514a-131">Product and service performance</span></span>
- <span data-ttu-id="d514a-132">การเชื่อมต่อและการกำหนดค่าของอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="d514a-132">Device connectivity and configuration</span></span>

<span data-ttu-id="d514a-133">ประเภทเหล่านี้จะแสดงอยู่ในตัวแสดงข้อมูลการวินิจฉัย และเป็นประเภทเดียวกันกับที่ใช้กับข้อมูลการวินิจฉัยที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="d514a-133">These categories are shown in the Diagnostic Data Viewer and are the same categories used with required diagnostic data.</span></span>

<span data-ttu-id="d514a-134">ส่วนต่อไปนี้มีคำอธิบายของแต่ละประเภทและตัวอย่างของเหตุการณ์สำหรับแต่ละประเภท</span><span class="sxs-lookup"><span data-stu-id="d514a-134">The following sections provide a description of each category and examples of events for each category.</span></span>

## <a name="software-setup-and-inventory-events"></a><span data-ttu-id="d514a-135">เหตุการณ์ของการตั้งค่าซอฟต์แวร์และสินค้าคงคลัง</span><span class="sxs-lookup"><span data-stu-id="d514a-135">Software setup and inventory events</span></span>

<span data-ttu-id="d514a-136">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-136">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="d514a-137">ผลิตภัณฑ์และเวอร์ชันที่ติดตั้งและสถานะการติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="d514a-137">Installed product and version and the installation status</span></span>
- <span data-ttu-id="d514a-138">Add-in ของซอฟต์แวร์และการตั้งค่า</span><span class="sxs-lookup"><span data-stu-id="d514a-138">Software add-ins and their settings.</span></span>
- <span data-ttu-id="d514a-139">เงื่อนไขของข้อผิดพลาดสำหรับเอกสาร ฟีเจอร์ และ Add-in ที่อาจลดการรักษาความปลอดภัยลง รวมถึงความพร้อมในการอัปเดตผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="d514a-139">Document, feature, and add-in error conditions that may compromise security, including product update readiness.</span></span>

<span data-ttu-id="d514a-140">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="d514a-140">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="d514a-141">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-141">**Event name**</span></span>   | <span data-ttu-id="d514a-142">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-142">**Event description**</span></span>  |
| ---- | ---- |
| <span data-ttu-id="d514a-143">Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId</span><span class="sxs-lookup"><span data-stu-id="d514a-143">Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId</span></span> | <span data-ttu-id="d514a-144">เหตุการณ์นี้ระบุว่า Word อัปเดต Ribbon ในส่วนติดต่อผู้ใช้ของ Word ได้สำเร็จหรือไม่เมื่อผู้ใช้เปลี่ยนแปลงข้อมูลประจำตัวของตน</span><span class="sxs-lookup"><span data-stu-id="d514a-144">This event indicates whether Word successfully updates the Ribbon in the Word User Interface when the user changes their identity.</span></span> <span data-ttu-id="d514a-145">เราใช้เหตุการณ์นี้เพื่อตรวจสอบการตั้งค่าที่ไม่ถูกต้องและปัญหาอื่นๆ ที่อาจส่งผลต่อส่วนติดต่อผู้ใช้ของ Office</span><span class="sxs-lookup"><span data-stu-id="d514a-145">We use this event to detect incorrect setup and other issues that would affect the Office user interface.</span></span> |
| <span data-ttu-id="d514a-146">Office.Extensibility.AppCommands.AppCmdInstall</span><span class="sxs-lookup"><span data-stu-id="d514a-146">Office.Extensibility.AppCommands.AppCmdInstall</span></span>   | <span data-ttu-id="d514a-147">เหตุการณ์นี้มีข้อมูลเกี่ยวกับ Add-in ของ Office ที่ผู้ใช้ติดตั้ง รวมถึง ID แอป รุ่นและเวอร์ชันของระบบปฏิบัติการ ความสำเร็จของการติดตั้ง และระยะเวลาของการติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="d514a-147">This event provides information about the Office add-in that the user has installed, including app ID, operating system build and version, success of installation, and duration of install.</span></span>  |

## <a name="product-and-service-usage-events"></a><span data-ttu-id="d514a-148">เหตุการณ์ของการใช้งานบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="d514a-148">Product and service usage events</span></span>

<span data-ttu-id="d514a-149">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-149">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="d514a-150">ความสำเร็จของฟังก์ชันการทำงานของแอปพลิเคชัน</span><span class="sxs-lookup"><span data-stu-id="d514a-150">Success of application functionality.</span></span> <span data-ttu-id="d514a-151">จำกัดเฉพาะการเปิดและปิดแอปพลิเคชันและเอกสาร การแก้ไขไฟล์ และการแชร์ไฟล์ (การทำงานร่วมกัน)</span><span class="sxs-lookup"><span data-stu-id="d514a-151">Limited to opening and closing of the application and documents, file editing, and file sharing (collaboration).</span></span>
- <span data-ttu-id="d514a-152">การกำหนดว่าเหตุการณ์ของฟีเจอร์เฉพาะเกิดขึ้นหรือไม่ เช่น เริ่มหรือหยุด และฟีเจอร์กำลังทำงานอยู่หรือไม่</span><span class="sxs-lookup"><span data-stu-id="d514a-152">Determination if specific feature events have occurred, such as start or stop, and if feature is running.</span></span>
- <span data-ttu-id="d514a-153">ฟีเจอร์การช่วยสำหรับการเข้าถึง Office</span><span class="sxs-lookup"><span data-stu-id="d514a-153">Office accessibility features</span></span>

<span data-ttu-id="d514a-154">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="d514a-154">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="d514a-155">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-155">**Event name**</span></span>   | <span data-ttu-id="d514a-156">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-156">**Event description**</span></span>  |
| ------ | ------- |
| <span data-ttu-id="d514a-157">Office.Word.Commanding.Highlight</span><span class="sxs-lookup"><span data-stu-id="d514a-157">Office.Word.Commanding.Highlight</span></span>  | <span data-ttu-id="d514a-158">เหตุการณ์นี้ระบุว่า Word ได้ดำเนินการคำสั่งเพื่อเน้นข้อความ</span><span class="sxs-lookup"><span data-stu-id="d514a-158">This event indicates Word has executed the command to highlight text.</span></span> <span data-ttu-id="d514a-159">เราใช้เหตุการณ์นี้เพื่อตรวจสอบข้อผิดพลาดในคำสั่งการเน้นข้อความ</span><span class="sxs-lookup"><span data-stu-id="d514a-159">We use this event to detect errors in the text-highlight command.</span></span>  |
| <span data-ttu-id="d514a-160">Office.Translator.AddInLoaded</span><span class="sxs-lookup"><span data-stu-id="d514a-160">Office.Translator.AddInLoaded</span></span>   | <span data-ttu-id="d514a-161">ฮาร์ทบีทเพื่อระบุว่าฟีเจอร์ตัวแปลภาษาถูกโหลด และแสดงผลสำเร็จแล้ว</span><span class="sxs-lookup"><span data-stu-id="d514a-161">A heartbeat to indicate that the translator feature has been loaded and rendered successfully.</span></span>  |
| <span data-ttu-id="d514a-162">Office.Graphics.GVizInsertShape</span><span class="sxs-lookup"><span data-stu-id="d514a-162">Office.Graphics.GVizInsertShape</span></span> |<span data-ttu-id="d514a-163">ติดตามการใช้งานฟีเจอร์แทรกรูปร่างใน Word และยังรายงานรายละเอียดเกี่ยวกับชนิดของรูปร่างที่แทรกและแหล่งที่มา</span><span class="sxs-lookup"><span data-stu-id="d514a-163">Tracks the usage of the Insert Shape feature in Word and also reports details of types of shapes inserted and from which source.</span></span>| 
| <span data-ttu-id="d514a-164">Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule</span><span class="sxs-lookup"><span data-stu-id="d514a-164">Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule</span></span>   | <span data-ttu-id="d514a-165">เหตุการณ์นี้กำหนดว่ามีส่วนใดส่วนหนึ่งแสดงอยู่ในเอกสารเมื่อผู้ใช้แทรกการซูมสรุปหรือไม่ และผู้ใช้เลือกที่จะลบส่วนที่มีอยู่หรือไม่</span><span class="sxs-lookup"><span data-stu-id="d514a-165">This event determines if there are any sections present in a document when the user is inserting Summary Zoom and if the user chooses to delete existing sections.</span></span> |
| <span data-ttu-id="d514a-166">Office.Security.SecureReaderHost.ProtectedViewValidation</span><span class="sxs-lookup"><span data-stu-id="d514a-166">Office.Security.SecureReaderHost.ProtectedViewValidation</span></span> | <span data-ttu-id="d514a-167">ติดตามเวลาและสาเหตุที่มีการเปิดไฟล์ในมุมมองที่ได้รับการป้องกัน</span><span class="sxs-lookup"><span data-stu-id="d514a-167">Tracks when and why a file is opened in Protected View.</span></span> <span data-ttu-id="d514a-168">ใช้กับเงื่อนไขการวินิจฉัยที่มุมมองที่ได้รับการป้องกันอาจทริกเกอร์ไม่ถูกต้องเพื่อให้แน่ใจว่าฟีเจอร์ทำงานอย่างถูกต้อง</span><span class="sxs-lookup"><span data-stu-id="d514a-168">Used to diagnose conditions where Protected View may not be correctly triggered to ensure the feature is working properly.</span></span> |

## <a name="product-and-service-performance-events"></a><span data-ttu-id="d514a-169">เหตุการณ์ของประสิทธิภาพของบริการและผลิตภัณฑ์</span><span class="sxs-lookup"><span data-stu-id="d514a-169">Product and service performance events</span></span>

<span data-ttu-id="d514a-170">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-170">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="d514a-171">แอปพลิเคชันจบการทำงานโดยไม่คาดคิด (การหยุดทำงาน) และสถานะของแอปพลิเคชันเมื่อเกิดเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="d514a-171">Unexpected application exits (crashes) and the state of the application when that happens.</span></span>
- <span data-ttu-id="d514a-172">เวลาตอบสนองหรือประสิทธิภาพการทำงานต่ำสำหรับสถานการณ์ เช่น การเริ่มต้นแอปพลิเคชัน หรือการเปิดไฟล์</span><span class="sxs-lookup"><span data-stu-id="d514a-172">Poor response time or performance for scenarios such as application start up or opening a file.</span></span>
- <span data-ttu-id="d514a-173">ข้อผิดพลาดในฟังก์ชันการทำงานของฟีเจอร์หรือประสบการณ์ใช้งานของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d514a-173">Errors in functionality of a feature or user experience.</span></span>

<span data-ttu-id="d514a-174">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="d514a-174">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="d514a-175">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-175">**Event name**</span></span>    | <span data-ttu-id="d514a-176">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-176">**Event description**</span></span>   |
| --------------- | -------------- |
| <span data-ttu-id="d514a-177">Office.Word.Word.CoreSaveTime100ns</span><span class="sxs-lookup"><span data-stu-id="d514a-177">Office.Word.Word.CoreSaveTime100ns</span></span>     | <span data-ttu-id="d514a-178">เหตุการณ์นี้บันทึกประสิทธิภาพการทำงานของกิจกรรมการบันทึกเอกสารโดย Word</span><span class="sxs-lookup"><span data-stu-id="d514a-178">This event logs the performance of a document save activity by Word.</span></span> <span data-ttu-id="d514a-179">เราใช้เหตุการณ์นี้เพื่อตรวจสอบข้อผิดพลาดและปัญหาประสิทธิภาพการทำงานในกิจกรรมการบันทึกเอกสารของ Word</span><span class="sxs-lookup"><span data-stu-id="d514a-179">We use this event to detect errors and performance issues in the Word save document activity.</span></span>|
| <span data-ttu-id="d514a-180">Office.Identity.SignInForWamAccountAad</span><span class="sxs-lookup"><span data-stu-id="d514a-180">Office.Identity.SignInForWamAccountAad</span></span>  | <span data-ttu-id="d514a-181">เหตุการณ์นี้จะถูกส่งเมื่อผู้ใช้ลงชื่อเข้าใช้บัญชี Azure Active Directory ที่มีไลบรารีระบบจัดการบัญชีบนเว็บ (WAM)</span><span class="sxs-lookup"><span data-stu-id="d514a-181">This event is sent when a user is signed in to an Azure Active Directory account with Web Account Manager (WAM) library.</span></span> <span data-ttu-id="d514a-182">เหตุการณ์นี้จะส่งเมตาดาต้า เช่น AppName, AppVersion และ ErrorCode ถ้าเหตุการณ์ล้มเหลว</span><span class="sxs-lookup"><span data-stu-id="d514a-182">This event sends metadata such as AppName, AppVersion, and ErrorCode if the event failed.</span></span> |
| <span data-ttu-id="d514a-183">Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime</span><span class="sxs-lookup"><span data-stu-id="d514a-183">Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime</span></span> | <span data-ttu-id="d514a-184">เหตุการณ์นี้รวบรวมระยะเวลาที่ใช้ในการแสดงรูปขนาดย่อต้นแบบของสไลด์แรกใน PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d514a-184">This event collects the length of time it takes to render the first slide master thumbnail in PowerPoint.</span></span>  |
| <span data-ttu-id="d514a-185">Office.Extensibility.Diagnostics</span><span class="sxs-lookup"><span data-stu-id="d514a-185">Office.Extensibility.Diagnostics</span></span>   | <span data-ttu-id="d514a-186">เหตุการณ์นี้มีข้อมูลการวินิจฉัยทั่วไปสำหรับ Add-in ของ Office เช่น รายงานการหยุดทำงานสำหรับการแก้จุดบกพร่อง</span><span class="sxs-lookup"><span data-stu-id="d514a-186">This event provides general diagnostic information for Office add-ins, such as crash reports for debugging.</span></span>|

## <a name="device-connectivity-and-configuration-events"></a><span data-ttu-id="d514a-187">เหตุการณ์ของการเชื่อมต่อและการกำหนดค่าของอุปกรณ์</span><span class="sxs-lookup"><span data-stu-id="d514a-187">Device connectivity and configuration events</span></span>

<span data-ttu-id="d514a-188">ประเภทนี้มีเหตุการณ์ที่อาจครอบคลุมพื้นที่ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d514a-188">This category includes events that may cover the following areas:</span></span>

- <span data-ttu-id="d514a-189">สถานการเชื่อมต่อเครือข่ายและการตั้งค่าอุปกรณ์ เช่น หน่วยความจำ</span><span class="sxs-lookup"><span data-stu-id="d514a-189">Network connection state and device settings, such as memory.</span></span>

<span data-ttu-id="d514a-190">ตารางต่อไปนี้แสดงตัวอย่างของเหตุการณ์ในประเภทนี้และคำอธิบายของเหตุการณ์เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="d514a-190">The following table provides examples of events in this category and a description of those events.</span></span>

| <span data-ttu-id="d514a-191">**ชื่อเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-191">**Event name**</span></span>                    | <span data-ttu-id="d514a-192">**คำอธิบายเหตุการณ์**</span><span class="sxs-lookup"><span data-stu-id="d514a-192">**Event description**</span></span>                                                                                                                                                     |
| ------ | ----- |
| <span data-ttu-id="d514a-193">Office.Graphics.ArtViewValidate</span><span class="sxs-lookup"><span data-stu-id="d514a-193">Office.Graphics.ArtViewValidate</span></span> | <span data-ttu-id="d514a-194">เหตุการณ์นี้บันทึกการตรวจสอบผลลัพธ์ของมุมมองกราฟิกที่สนับสนุนส่วนติดต่อผู้ใช้ของกราฟิก</span><span class="sxs-lookup"><span data-stu-id="d514a-194">This event logs validation the results of Graphics View that supports Graphics User Interface.</span></span> <span data-ttu-id="d514a-195">เราใช้เหตุการณ์เพื่อรวบรวมข้อมูลการใช้งานและข้อผิดพลาดเกี่ยวกับการแสดงผลกราฟิก</span><span class="sxs-lookup"><span data-stu-id="d514a-195">We use the event to collect usage and error data about graphics rendering.</span></span> |
| <span data-ttu-id="d514a-196">Office.Graphics.ARCExceptionScope</span><span class="sxs-lookup"><span data-stu-id="d514a-196">Office.Graphics.ARCExceptionScope</span></span> | <span data-ttu-id="d514a-197">เหตุการณ์นี้ติดตามความล้มเหลวในการแสดงผลที่มาจากโปรแกรมการแสดงผล</span><span class="sxs-lookup"><span data-stu-id="d514a-197">This event tracks rendering failures coming from the rendering engine.</span></span> |
| <span data-ttu-id="d514a-198">Office.Extensibility.ODPLatency</span><span class="sxs-lookup"><span data-stu-id="d514a-198">Office.Extensibility.ODPLatency</span></span>   | <span data-ttu-id="d514a-199">เหตุการณ์นี้มีข้อมูลเกี่ยวกับการเชื่อมต่อเครือข่ายและความเร็วของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d514a-199">This event provides information about the user’s network connection and speed.</span></span>     |
