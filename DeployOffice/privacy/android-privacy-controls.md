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
ms.openlocfilehash: 36ae9878d03845c24e3717dfac970b2b961279dc
ms.sourcegitcommit: acb22296532bbfdfcad4dc1e7162f812997fbdd1
ms.translationtype: HT
ms.contentlocale: th-TH
ms.lasthandoff: 11/08/2019
ms.locfileid: "38068454"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a>การใช้การตั้งค่านโยบายเพื่อจัดการการควบคุมความเป็นส่วนตัวสำหรับ Office บนอุปกรณ์ Android

การตั้งค่านโยบายสำหรับ Office บนอุปกรณ์ Android จะทำให้คุณสามารถควบคุมการตั้งค่าที่เกี่ยวข้องกับเรื่องดังต่อไปนี้ได้:

- ***ข้อมูลการวินิจฉัย***ที่รวบรวมและส่งถึง Microsoft เกี่ยวกับซอฟต์แวร์ไคลเอ็นต์ Office ที่ใช้อยู่

- ***ประสบการณ์ใช้งานที่เชื่อมต่อ*** ที่ใช้ฟังก์ชันการทำงานบนระบบ Cloud เพื่อมอบฟีเจอร์ Office ที่ได้รับการปรับปรุงให้กับคุณและผู้ใช้ของคุณ

สำหรับข้อมูลเพิ่มเติมเกี่ยวกับข้อมูลการวินิจฉัยและประสบการณ์การใช้งานที่เชื่อมต่อ ให้ดู[ภาพรวมของการควบคุมความเป็นส่วนตัว](overview-privacy-controls.md)

การตั้งค่านโยบายเหล่านี้จะนำไปใช้กับแอปพลิเคชันต่อไปนี้:
- เวอร์ชัน 16.0.12226.10000 และเวอร์ชันต่อมาของ Word for Android, Excel for Android และ PowerPoint for Android 
- เวอร์ชัน16.0.12228.20004 และเวอร์ชันต่อมาของ OneNote for Android

> [!NOTE]
>- การตั้งค่านโยบายเหล่านี้จะนำไปใช้กับเวอร์ชัน 16.0.12130.20272 และเวอร์ชันต่อมาของตัวอย่างสำหรับสาธารณะใน [แอป Office สำหรับอุปกรณ์เคลื่อนที่](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172) ของ Android
>- การใช้ตัวอย่างสำหรับสาธารณะของแอป Office สำหรับอุปกรณ์เคลื่อนที่ของ Android จะรวบรวมรายการบันทึกการหยุดทำงานซึ่งในบางครั้งอาจมีเนื้อหาอยู่
>- ถ้าคุณกังวลเกี่ยวกับการรวบรวมข้อมูลจากตัวอย่างสำหรับสาธารณะของแอป Office สำหรับ Android คุณควรแจ้งผู้ใช้ของคุณไม่ให้เข้าสู่แอปพลิเคชันด้วยบัญชีที่ทำงานหรือโรงเรียน

## <a name="policy-settings-available-for-office-on-android-devices"></a>การตั้งค่านโยบายที่พร้อมใช้งานสำหรับ Office บนอุปกรณ์ Android

ตารางต่อไปนี้แสดงการตั้งค่านโยบายที่สามารถใช้งานได้สำหรับ Office บนอุปกรณ์ Android และลิงก์ไปยังข้อมูลเพิ่มเติมเกี่ยวกับการตั้งค่านโยบายแต่ละรายการ

> [!NOTE]
>- ข้อมูลเพิ่มเติมนี้ครอบคลุมถึงการตั้งค่านโยบายสำหรับ Office บนอุปกรณ์ที่ใช้บน Windows แต่ข้อมูลเดียวกันนี้จะถูกนำไปใช้กับ Office บนอุปกรณ์ Android เนื่องจากเป็นการตั้งค่านโยบายแบบเดียวกัน
>- การตั้งค่านโยบายที่ *อนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office* ซึ่งพร้อมใช้งานสำหรับ Office บนอุปกรณ์ที่ใช้ Windows แต่ไม่สามารถใช้งานได้กับ Office บนอุปกรณ์ Android 


|ชื่อของการตั้งค่านโยบาย  |ข้อมูลเพิ่มเติม |
|---------|---------|
|การกำหนดค่าระดับของข้อมูลการวินิจฉัยซอฟต์แวร์ไคลเอ็นต์ที่ส่งโดย Office ไปยัง Microsoft|[การตั้งค่านโยบายสำหรับข้อมูลการวินิจฉัย](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|การอนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office ที่วิเคราะห์เนื้อหา| [การตั้งค่านโยบายสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่วิเคราะห์เนื้อหาของคุณ](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|การอนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อใน Office ที่ดาวน์โหลดเนื้อหาแบบออนไลน์ |[การตั้งค่านโยบายสำหรับประสบการณ์ใช้งานที่เชื่อมต่อที่ดาวน์โหลดเนื้อหาแบบออนไลน์](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|การอนุญาตให้ใช้ประสบการณ์ใช้งานที่เชื่อมต่อแบบทางเลือกเพิ่มเติมใน Office |[การตั้งค่านโยบายสำหรับประสบการณ์ใช้งานที่เชื่อมต่อแบบทางเลือก](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a>การใช้บริการนโยบายระบบคลาวด์ของ Office เพื่อนำการตั้งค่านโยบายไปใช้

เมื่อต้องการนำการตั้งค่านโยบายทั้ง 4 เหล่านี้ไปใช้กับ Office บนอุปกรณ์ Android คุณต้องใช้บริการนโยบายระบบคลาวด์ของ Office สำหรับข้อมูลเพิ่มเติมเกี่ยวกับการใช้บริการนโยบายระบบคลาวด์ของ Office ให้ดู [ภาพรวมของบริการนโยบายระบบคลาวด์ของ Office](../overview-office-cloud-policy-service.md)

> [!NOTE]
> ถ้าก่อนหน้านี้คุณใช้บริการนโยบายระบบคลาวด์ของ Office เพื่อกำหนดค่าการตั้งค่านโยบายเหล่านี้สำหรับ Office บนอุปกรณ์ที่ใช้ Windows การตั้งค่าเดียวกันนั้นจะถูกนำไปใช้กับ Office บนอุปกรณ์ Android สำหรับการแก้ไขปัญหาที่เกิดขึ้น คุณเพียงแค่ต้องลงชื่อเข้าใช้บริการนโยบายระบบคลาวด์ของ Office และบริการจะนำการตั้งค่าโดยอัตโนมัตินี้ไปใช้ใน Office บนอุปกรณ์ Android
