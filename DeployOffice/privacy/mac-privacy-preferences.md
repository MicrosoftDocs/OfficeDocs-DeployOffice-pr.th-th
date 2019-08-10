---
title: ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office for Mac
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
description: มอบข้อมูลเกี่ยวกับวิธีการจัดการการควบคุมความเป็นส่วนตัวใน Office for Mac ให้กับผู้ดูแลระบบ Office
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246330"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="46114-103">ใช้การกำหนดลักษณะเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office for Mac</span><span class="sxs-lookup"><span data-stu-id="46114-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="46114-104">ตั้งแต่ Office for Mac เวอร์ชัน 16.28 เป็นต้นไป มีการตั้งค่าการกำหนดลักษณะแบบใหม่ที่ช่วยให้คุณสามารถควบคุมการตั้งค่าที่เกี่ยวข้องกับสิ่งต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="46114-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="46114-105">***ข้อมูลการวินิจฉัย*** ที่รวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ใช้อยู่</span><span class="sxs-lookup"><span data-stu-id="46114-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="46114-106">***ประสบการณ์ใช้งานที่เชื่อมต่อ*** ที่ใช้ฟังก์ชันการทำงานบนระบบ Cloud เพื่อมอบฟีเจอร์ Office ที่ได้รับการปรับปรุงให้กับคุณและผู้ใช้ของคุณ</span><span class="sxs-lookup"><span data-stu-id="46114-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="46114-107">นอกจากนี้ยังมีการตั้งค่าการกำหนดลักษณะใหม่ที่เกี่ยวข้องกับกล่องโต้ตอบ**การแจ้งเตือนข้อมูลที่จำเป็น**สำหรับ Microsoft AutoUpdate (MAU)</span><span class="sxs-lookup"><span data-stu-id="46114-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="46114-108">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัยและประสบการณ์การใช้งานที่เชื่อมต่อ ให้ดู[ภาพรวมของการควบคุมความเป็นส่วนตัว](overview-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="46114-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="46114-109">สำหรับข้อมูลเพิ่มเติมเกี่ยวกับการตั้งค่าที่คล้ายกันสำหรับโปรแกรม Officer บนคอมพิวเตอร์ที่ใช้ Windows ให้ดูที่ [ใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office 365 ProPlus](manage-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="46114-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="46114-110">การตั้งค่าการกำหนดลักษณะ</span><span class="sxs-lookup"><span data-stu-id="46114-110">Setting preferences</span></span>

<span data-ttu-id="46114-111">การตั้งค่าการกำหนดลักษณะใหม่เหล่านี้คือ CFPreferences API ที่ใช้งานร่วมกันได้ และสามารถตั้งค่าได้โดยใช้คำสั่ง `defaults` ในเทอร์มินัล หรือใช้ผ่านเซิร์ฟเวอร์โปรไฟล์การกำหนดค่าหรือการจัดการอุปกรณ์เคลื่อนที่ (MDM)</span><span class="sxs-lookup"><span data-stu-id="46114-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="46114-112">เมื่อมีการบังคับใช้การกำหนดลักษณะ ผู้ใช้จะไม่สามารถเปลี่ยนค่าได้และตัวควบคุมภายในแอปจะถูกปิดใช้งาน</span><span class="sxs-lookup"><span data-stu-id="46114-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="46114-113">การตั้งค่าการกำหนดลักษณะสำหรับข้อมูลการวินิจฉัย</span><span class="sxs-lookup"><span data-stu-id="46114-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="46114-114">ข้อมูลการวินิจฉัยมีไว้เพื่อรักษาความปลอดภัย อัปเดต ตรวจหา วินิจฉัย และแก้ไขปัญหาใน Office รวมถึงการปรับปรุงผลิตภัณฑ์ด้วย</span><span class="sxs-lookup"><span data-stu-id="46114-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="46114-115">สำหรับข้อมูลเพิ่มเติม ดูที่ [ข้อมูลการวินิจฉัยที่ส่งจาก Office 365 ProPlus ไปยัง Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft)</span><span class="sxs-lookup"><span data-stu-id="46114-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="46114-116">**โดเมนการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="46114-117">**แป้น**</span><span class="sxs-lookup"><span data-stu-id="46114-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="46114-118">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="46114-118">**Data Type**</span></span>  | <span data-ttu-id="46114-119">สตริง</span><span class="sxs-lookup"><span data-stu-id="46114-119">String</span></span> |
|<span data-ttu-id="46114-120">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="46114-120">**Possible values**</span></span>  | <span data-ttu-id="46114-121">`BasicDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น จำเป็น)*</span><span class="sxs-lookup"><span data-stu-id="46114-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="46114-122">`FullDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น ไม่จำเป็น)*</span><span class="sxs-lookup"><span data-stu-id="46114-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="46114-123">`ZeroDiagnosticData` *(ซึ่งจะตั้งค่าระดับเป็น ไม่ใช่ทั้งสองอย่าง)*</span><span class="sxs-lookup"><span data-stu-id="46114-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="46114-124">**ความพร้อมใช้งาน**</span><span class="sxs-lookup"><span data-stu-id="46114-124">**Availability**</span></span> |<span data-ttu-id="46114-125">16.28 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="46114-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="46114-126">หากคุณตั้งค่าการกำหนดลักษณะนี้ จะมีการนำค่าดังกล่าวไปใช้กับผลิตภัณฑ์ต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="46114-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="46114-127">เวอร์ชัน 1.00.217856 และเวอร์ชันที่ใหม่กว่าของ Teams for Mac</span><span class="sxs-lookup"><span data-stu-id="46114-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="46114-128">เวอร์ชัน 16.28 และเวอร์ชันที่ใหม่กว่าของ Skype for Business for Mac</span><span class="sxs-lookup"><span data-stu-id="46114-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="46114-129">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ทั้งข้อมูลการวินิจฉัยที่ไม่จำเป็นและจำเป็นจะถูกส่งไปยัง Microsoft หากผู้ใช้ที่มีการสมัครใช้งาน Office 365 ได้ลงชื่อเข้าใช้ด้วยบัญชีของที่ทำงานหรือที่โรงเรียน หรือหากผู้ใช้มี Office 2019 for Mac เวอร์ชันที่ได้รับสิทธิ์การใช้งาน</span><span class="sxs-lookup"><span data-stu-id="46114-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="46114-130">นอกจากนี้ ผู้ใช้เหล่านี้จะไม่สามารถเปลี่ยนระดับของข้อมูลการวินิจฉัยได้ โดยไม่คำนึงถึงวิธีที่คุณตั้งค่าการกำหนดลักษณะนี้</span><span class="sxs-lookup"><span data-stu-id="46114-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="46114-131">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 จะมีการส่งข้อมูลการวินิจฉัยเพียงอย่างเดียว เว้นแต่ว่าผู้ใช้จะเลือกที่จะส่งข้อมูลการวินิจฉัยเพิ่มเติม โดยไปที่**นโยบาย** > **ความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="46114-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="46114-132">การตั้งค่าการกำหนดลักษณะสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณ</span><span class="sxs-lookup"><span data-stu-id="46114-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="46114-133">ประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณเป็นประสบการณ์ที่ใช้เนื้อหา Office ของคุณเพื่อให้คำแนะนำการออกแบบ คำแนะนำการแก้ไข ข้อมูลเชิงลึก และฟีเจอร์การทำงานที่คล้ายกัน</span><span class="sxs-lookup"><span data-stu-id="46114-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="46114-134">ตัวอย่างเช่น PowerPoint Designer หรือเครื่องมือค้นคว้าใน Word</span><span class="sxs-lookup"><span data-stu-id="46114-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="46114-135">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่อเหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="46114-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="46114-136">**โดเมนการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="46114-137">**แป้น**</span><span class="sxs-lookup"><span data-stu-id="46114-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="46114-138">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="46114-138">**Data Type**</span></span>  | <span data-ttu-id="46114-139">บูลีน</span><span class="sxs-lookup"><span data-stu-id="46114-139">Boolean</span></span> |
|<span data-ttu-id="46114-140">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="46114-140">**Possible values**</span></span>  | <span data-ttu-id="46114-141">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="46114-142">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="46114-143">**ความพร้อมใช้งาน**</span><span class="sxs-lookup"><span data-stu-id="46114-143">**Availability**</span></span> |<span data-ttu-id="46114-144">16.28 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="46114-144">16.28 and later</span></span> |

<span data-ttu-id="46114-145">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ผู้ใช้จะสามารถใช้งานที่เชื่อมต่อซึ่งทำการวิเคราะห์เนื้อหาได้</span><span class="sxs-lookup"><span data-stu-id="46114-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="46114-146">หากผู้ใช้มีการสมัครใช้งาน Office 365 และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือที่โรงเรียน หรือหากผู้ใช้มี Office 2019 for Mac เวอร์ชันที่ได้รับสิทธิ์การใช้งาน ผู้ใช้จะไม่สามารถปิดการใช้งานที่เชื่อมต่อกับการวิเคราะห์เนื้อหาได้</span><span class="sxs-lookup"><span data-stu-id="46114-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="46114-147">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 ผู้ใช้สามารถเลือกที่จะปิดการใช้งานการเชื่อมต่อที่วิเคราะห์เนื้อหาได้โดยไปที่**นโยบาย** > **ความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="46114-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="46114-148">การตั้งค่าการกำหนดลักษณธสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="46114-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="46114-149">ประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์คือประสบการณ์ที่ช่วยให้คุณสามารถค้นหาและดาวน์โหลดเนื้อหาแบบออนไลน์ที่รวมถึงเทมเพลต, รูปภาพ, โมเดล 3D, วิดีโอ และเอกสารอ้างอิงเพื่อเพิ่มขีดความสามารถให้เอกสารของคุณ</span><span class="sxs-lookup"><span data-stu-id="46114-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="46114-150">ตัวอย่างเช่น เทมเพลต Office หรือเครื่องมือเริ่มต้นด่วนของ PowerPoint</span><span class="sxs-lookup"><span data-stu-id="46114-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="46114-151">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่อเหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="46114-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="46114-152">**โดเมนการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="46114-153">**แป้น**</span><span class="sxs-lookup"><span data-stu-id="46114-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="46114-154">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="46114-154">**Data Type**</span></span>  | <span data-ttu-id="46114-155">บูลีน</span><span class="sxs-lookup"><span data-stu-id="46114-155">Boolean</span></span> |
|<span data-ttu-id="46114-156">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="46114-156">**Possible values**</span></span>  | <span data-ttu-id="46114-157">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="46114-158">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="46114-159">**ความพร้อมใช้งาน**</span><span class="sxs-lookup"><span data-stu-id="46114-159">**Availability**</span></span> |<span data-ttu-id="46114-160">16.28 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="46114-160">16.28 and later</span></span> |

<span data-ttu-id="46114-161">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ผู้ใช้จะสามารถใช้งานที่เชื่อมต่อซึ่งดาวน์โหลดเนื้อหาแบบออนไลน์ได้</span><span class="sxs-lookup"><span data-stu-id="46114-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="46114-162">หากผู้ใช้มีการสมัครใช้งาน Office 365 และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือที่โรงเรียน หรือหากผู้ใช้มี Office 2019 for Mac เวอร์ชันที่ได้รับสิทธิ์การใช้งาน ผู้ใช้จะไม่สามารถปิดการใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์ได้</span><span class="sxs-lookup"><span data-stu-id="46114-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="46114-163">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 ผู้ใช้สามารถเลือกที่จะปิดการใช้งานการเชื่อมต่อที่ดาวน์โหลดเนื้อหาออนไลน์ได้โดยไปที่**นโยบาย** > **ความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="46114-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="46114-164">การตั้งค่าการกำหนดลักษณธสำหรับประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="46114-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="46114-165">นอกเหนือจากประสบการณ์ใช้งานที่เชื่อมต่อที่กล่าวถึงข้างต้นแล้ว ยังมีประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมบางส่วน ซึ่งคุณสามารถเลือกอนุญาตให้ผู้ใช้เข้าถึงด้วยบัญชีขององค์กรได้ โดยในบางครั้งอาจอ้างอิงว่าเป็นบัญชีของที่ทำงานหรือโรงเรียน</span><span class="sxs-lookup"><span data-stu-id="46114-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="46114-166">ตัวอย่างเช่น ฟีเจอร์ LinkedIn ของตัวช่วยร่างประวัติย่อใน Word หรือแถบสภาพอากาศใน Outlook ที่ใช้ใน MSN Weather</span><span class="sxs-lookup"><span data-stu-id="46114-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="46114-167">หากต้องการดูตัวอย่างเพิ่มเติม ให้ดู [ภาพรวมของประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติมใน Office](optional-connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="46114-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="46114-168">**โดเมนการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="46114-169">**แป้น**</span><span class="sxs-lookup"><span data-stu-id="46114-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="46114-170">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="46114-170">**Data Type**</span></span>  | <span data-ttu-id="46114-171">บูลีน</span><span class="sxs-lookup"><span data-stu-id="46114-171">Boolean</span></span> |
|<span data-ttu-id="46114-172">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="46114-172">**Possible values**</span></span>  | <span data-ttu-id="46114-173">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="46114-174">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="46114-175">**ความพร้อมใช้งาน**</span><span class="sxs-lookup"><span data-stu-id="46114-175">**Availability**</span></span> |<span data-ttu-id="46114-176">16.28 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="46114-176">16.28 and later</span></span> |

<span data-ttu-id="46114-177">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ ประสบการณ์ใช้งานที่เชื่อมต่อที่เพิ่มเติมเข้าจะมีให้บริการแก่ผู้ใช้ที่มีการสมัครใช้งาน Office 365 ที่ได้ลงชื่อเข้าใช้ด้วยบัญชีของที่ทำงานหรือที่โรงเรียน หรือหากผู้ใช้มี Office 2019 for Mac เวอร์ชันที่ได้รับสิทธิ์การใช้งาน</span><span class="sxs-lookup"><span data-stu-id="46114-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="46114-178">เว้นแต่ว่าคุณได้ตั้งค่าการกำหนดลักษณะนี้ให้ `FALSE` ผู้ใช้เหล่านี้สามารถเลือกที่จะปิดใช้งานการเชื่อมต่อเพิ่มเติมได้โดยไปที่**ความเป็นส่วนตัว** > **ของการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="46114-179">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 จะไม่มีตัวเลือกในการปิดใช้งานการเชื่อมต่อที่ไม่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="46114-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="46114-180">การตั้งค่าการกำหนดลักษณะสำหรับการใช้งานที่เชื่อมต่อส่วนใหญ่</span><span class="sxs-lookup"><span data-stu-id="46114-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="46114-181">คุณสามารถใช้การกำหนดลักษณะนี้เพื่อควบคุมว่าจะให้ผู้ใช้ของคุณมีประสบการณ์การใช้งานที่เชื่อมต่อกันมากที่สุดหรือไม่</span><span class="sxs-lookup"><span data-stu-id="46114-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="46114-182">**โดเมนการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="46114-183">**แป้น**</span><span class="sxs-lookup"><span data-stu-id="46114-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="46114-184">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="46114-184">**Data Type**</span></span>  | <span data-ttu-id="46114-185">บูลีน</span><span class="sxs-lookup"><span data-stu-id="46114-185">Boolean</span></span> |
|<span data-ttu-id="46114-186">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="46114-186">**Possible values**</span></span>  | <span data-ttu-id="46114-187">`TRUE` *(เปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="46114-188">`FALSE` *(ปิดใช้งาน)*</span><span class="sxs-lookup"><span data-stu-id="46114-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="46114-189">**ความพร้อมใช้งาน**</span><span class="sxs-lookup"><span data-stu-id="46114-189">**Availability**</span></span> |<span data-ttu-id="46114-190">16.28 และใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="46114-190">16.28 and later</span></span> |

<span data-ttu-id="46114-191">หากคุณไม่ได้ตั้งค่าการกำหนดลักษณะนี้ การใช้งานที่เชื่อมต่อทั้งหมดจะพร้อมใช้งานสำหรับผู้ใช้ของคุณ เว้นแต่ว่าคุณได้ตั้งค่าการกำหนดลักษณะอื่นๆ สำหรับการเชื่อมต่อที่ได้รับการติดตั้งไว้ก่อนหน้านี้ เช่น `OfficeExperiencesAnalyzingContentPreference`</span><span class="sxs-lookup"><span data-stu-id="46114-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="46114-192">ตัวอย่างเช่น หากคุณตั้งค่าการกำหนดลักษณะนี้เป็น `FALSE` ผู้ใช้จะไม่สามารถใช้งานที่เชื่อมต่อต่อไปนี้ได้:</span><span class="sxs-lookup"><span data-stu-id="46114-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="46114-193">ประสบการณ์ที่วิเคราะห์เนื้อหาของคุณ</span><span class="sxs-lookup"><span data-stu-id="46114-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="46114-194">ประสบการณ์ที่ดาวน์โหลดเนื้อหาแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="46114-194">Experiences that download online content</span></span>
- <span data-ttu-id="46114-195">ประสบการณ์ใช้งานที่เชื่อมต่อสำหรับเลือกเพิ่มเติม</span><span class="sxs-lookup"><span data-stu-id="46114-195">Optional connected experiences</span></span>

<span data-ttu-id="46114-196">นอกจากนี หากคุณตั้งค่าการกำหนดลักษณะนี้เป็น `FALSE` การใช้งานที่เชื่อมต่ออื่นๆ ส่วนใหญ่จะถูกปิดด้วยเช่นกัน เช่น การเขียนร่วมและที่เก็บไฟล์ออนไลน์ </span><span class="sxs-lookup"><span data-stu-id="46114-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="46114-197">สำหรับรายการประสบการณ์ใช้งานที่เชื่อมต่ออื่นๆ เหล่านี้ ให้ดู [ประสบการณ์ใช้งานที่เชื่อมต่อใน Office](connected-experiences.md)</span><span class="sxs-lookup"><span data-stu-id="46114-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="46114-198">แม้ว่าคุณจะตั้งค่าการกำหนดลักษณะนี้เป็น `FALSE` แต่ฟังก์ชันของ Office บางส่วน เช่น การซิงค์กล่องจดหมายใน Outlook และ Teams และ Skype for Business จะยังคงสามารถใช้งานได้</span><span class="sxs-lookup"><span data-stu-id="46114-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="46114-199">[บริการหลัก](essential-services.md) เช่น บริการให้สิทธิ์การใช้งานที่ยืนยันว่าคุณได้รับสิทธิ์การใช้งาน Office อย่างถูกต้อง จะยังคงสามารถใช้งานได้</span><span class="sxs-lookup"><span data-stu-id="46114-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="46114-200">หากผู้ใช้มีการสมัครใช้งาน Office 365 และลงชื่อเข้าใช้ด้วยบัญชีที่ทำงานหรือที่โรงเรียน หรือหากผู้ใช้มี Office 2019 for Mac เวอร์ชันที่ได้รับสิทธิ์การใช้งาน ผู้ใช้จะไม่สามารถปิดการใช้งานที่เชื่อมต่อส่วนใหญ่ได้</span><span class="sxs-lookup"><span data-stu-id="46114-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="46114-201">สำหรับผู้ใช้อื่นๆ เช่น ผู้ใช้งานที่บ้านที่มีการสมัครใช้งาน Office 365 ผู้ใช้สามารถเลือกที่จะปิดการใช้งานการเชื่อมต่อส่วนใหญ่ได้โดยไปที่**นโยบาย** > **ความเป็นส่วนตัว**</span><span class="sxs-lookup"><span data-stu-id="46114-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="46114-202">การตั้งค่าการกำหนดลักษณะสำหรับกล่องโต้ตอบการแจ้งเตือนข้อมูลที่จำเป็นสำหรับ Microsoft AutoUpdate</span><span class="sxs-lookup"><span data-stu-id="46114-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="46114-203">ครั้งแรกที่มีการเปิดใช้งานเวอร์ชัน 4.12 หรือเวอร์ชันที่ใหม่กว่าของ Microsoft AutoUpdate (MAU) ผู้ใช้จะเห็นกล่องโต้ตอบ**การแจ้งเตือนข้อมูลที่จำเป็น**ที่มีข้อมูลว่ามีการส่งข้อมูลใดจาก MAU ไปยัง Microsoft</span><span class="sxs-lookup"><span data-stu-id="46114-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="46114-204">หากคุณไม่ต้องการให้ผู้ใช้ของคุณเห็นกล่องโต้ตอบ**การแจ้งเตือนข้อมูลที่จำเป็น**สำหรับ Microsoft AutoUpdate คุณสามารถตั้งค่าการกำหนดลักษณะต่อไปนี้</span><span class="sxs-lookup"><span data-stu-id="46114-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="46114-205">ไม่ว่าคุณจะตั้งค่าใด กล่องโต้ตอบจะไม่แสดงแก่ผู้ใช้ของคุณ</span><span class="sxs-lookup"><span data-stu-id="46114-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="46114-206">**โดเมนการกำหนดลักษณะ**</span><span class="sxs-lookup"><span data-stu-id="46114-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="46114-207">**แป้น**</span><span class="sxs-lookup"><span data-stu-id="46114-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="46114-208">**ชนิดข้อมูล**</span><span class="sxs-lookup"><span data-stu-id="46114-208">**Data Type**</span></span>  | <span data-ttu-id="46114-209">สตริง</span><span class="sxs-lookup"><span data-stu-id="46114-209">String</span></span> |
|<span data-ttu-id="46114-210">**ค่าที่เป็นไปได้**</span><span class="sxs-lookup"><span data-stu-id="46114-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="46114-211">**ความพร้อมใช้งาน**</span><span class="sxs-lookup"><span data-stu-id="46114-211">**Availability**</span></span> |<span data-ttu-id="46114-212">4.12 และเวอร์ชันที่ใหม่กว่า</span><span class="sxs-lookup"><span data-stu-id="46114-212">4.12 and later</span></span> |

<span data-ttu-id="46114-213">หากคุณอนุญาตให้ผู้ใช้ของคุณเห็นกล่องโต้ตอบนี้แล้ว เมื่อผู้ใช้เลือก **ตกลง** ค่า `RequiredDataOnly` จะถูกเขียนไปยัง `AcknowledgedDataCollectionPolicy` และกล่องโต้ตอบจะไม่แสดงแก่ผู้ใช้อีกครั้ง</span><span class="sxs-lookup"><span data-stu-id="46114-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="46114-214">หัวข้อที่เกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="46114-214">Related topics</span></span>

- [<span data-ttu-id="46114-215">การอ้างอิงโปรไฟล์การกำหนดค่า (เอกสารประกอบของนักพัฒนา Apple)</span><span class="sxs-lookup"><span data-stu-id="46114-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="46114-216">การปรับใช้การกำหนดลักษณะสำหรับ Office for Mac</span><span class="sxs-lookup"><span data-stu-id="46114-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="46114-217">การตั้งค่าความเป็นส่วนตัวของบัญชี</span><span class="sxs-lookup"><span data-stu-id="46114-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
