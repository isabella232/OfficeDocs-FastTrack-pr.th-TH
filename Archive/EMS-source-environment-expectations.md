---
title: ความคาดหวังของสภาพแวดล้อมต้นทาง
description: แหล่งข้อมูลข้องของสภาพแวดล้อมในการใช้สิทธิประโยชน์FastTrack Center For EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.localizationpriority: ''
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 8ad6cbdfdd39764b0b63b2910b792f51480a32b4
ms.sourcegitcommit: 3d086ab6c4743afbedebed55a3ddb65f05422a1b
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/30/2021
ms.locfileid: "58710311"
---
# <a name="source-environment-expectations"></a>ข้อกำหนดของสภาพแวดล้อมต้นทาง
> [!CAUTION]
> เนื้อหานี้จะไม่ใช่เนื้อหาปัจจุบันอีกต่อไปและถูกจัดเวลาให้เอาออก ใช้สารบัญในการนําทางด้านซ้ายมือกับเนื้อหาปัจจุบัน

เมื่อคุณใช้สิทธิประโยชน์ของศูนย์ FastTrack Enterprise [Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md)เพื่อรับ Microsoft Azure Active Directory Premium, Microsoft Intune และ Azure Information Protection พร้อมให้ใช้งาน สภาพแวดล้อมของคุณต้องเป็นไปตามความคาดหวังที่อธิบายไว้ในส่วนต่อไปนี้

คุณอาจมี Active Directory ภายในองค์กรอยู่แล้วในองค์กรของคุณที่คุณต้องการรวมกับ Enterprise Mobility + Security (EMS) หรือบริการแต่ละรายการใดๆ ที่ใช้การจัดการข้อมูลเฉพาะตัวแบบสมบูรณ์จากคอนโซลเดียว สิทธิประโยชน์ของ FastTrack Center for Enterprise Mobility + Security (EMS) รวมถึงการช่วยให้คุณAzure Active Directoryกับสภาพแวดล้อม Active Directory ภายในองค์กรที่มีอยู่ของคุณ

ตารางต่อไปนี้แสดงความคาดหวังต่อสภาพแวดล้อมแหล่งข้อมูลที่มีอยู่ของคุณในการออนบอร์ด

|กิจกรรม|ความคาดหวังของสภาพแวดล้อมต้นทาง|
|------------|----------------------------------|
|การออนบอร์ดหลัก|Active Directory ฟอเรสต์ที่ตั้งค่าระดับฟอเรสต์ฟังก์ชันWindows Server 2008 หรือสูงกว่า ด้วยการกําหนดค่าฟอเรสต์ต่อไปนี้:<br /><br />- ฟอเรสต์ Active Directory เดียว<br />- หลายฟอเรสต์ Active Directory </br></br>**หมายเหตุ**: การปรับใช้ Active Directory Federation Services (AD FS) อยู่นอกขอบเขตการกําหนดค่าฟอเรสต์ทั้งหมด สิทธิประโยชน์ของศูนย์การติดต่อกับภายนอกของ FastTrack|
|การPremium Azure AD|Active Directory ภายในองค์กรและสภาพแวดล้อมของ Azure AD ได้รับการเตรียมพร้อมPremium Azure AD ซึ่งรวมถึงการแก้ไขปัญหาที่ระบุที่ป้องกันการรวมกับฟีเจอร์ Azure AD Premium Azure AD|
|Intuns on-boarding| ผู้ดูแลระบบ IT ต้องมีโครงสร้างพื้นฐานผู้ให้บริการออกใบรับรอง, WiFi และ VPN ที่ใช้งานได้ในสภาพแวดล้อมการผลิตอยู่แล้ว เมื่อวางแผนการปรับใช้โปรไฟล์ WiFi และ VPN กับ Intuny<br /><br /> **หมายเหตุ**: สิทธิประโยชน์ของบริการไม่มีความช่วยเหลือในการตั้งค่าหรือกําหนดค่าผู้ให้บริการออกใบรับรอง, WiFi, โครงสร้างพื้นฐาน VPN หรือใบรับรองแบบพุชของ Apple MDM  |
|ตัวจัดการการกําหนดค่าที่แนบบนระบบคลาวด์ด้วย Intun1|ด้วยการแนบระบบ Cloud ผู้ดูแลระบบ IT มีหน้าที่รับผิดชอบในการจัดเตรียมสภาพแวดล้อมภายในองค์กร ซึ่งอาจรวมถึงการแก้ไขปัญหาที่ป้องกันไม่ให้คุณแนบสภาพแวดล้อมตัวจัดการการกําหนดค่ากับ Intun<br /><br />**หมายเหตุ**: สิทธิประโยชน์ของFastTrackการกําหนดค่าไม่มีความช่วยเหลือในการตั้งค่าหรืออัปเกรดเซิร์ฟเวอร์ไซต์ตัวจัดการการกําหนดค่าหรือไคลเอ็นต์ตัวจัดการการกําหนดค่าเป็นความต้องการขั้นต่สุดที่ต้องใช้เพื่อสนับสนุนการแนบ Cloud |
|Intuns ที่รวมเข้ากับ Microsoft Defender Advanced Threat Protection (ATP)|**หมายเหตุ**: สิทธิประโยชน์FastTrackบริการของคุณมอบความช่วยเหลือในการรวม Intuned กับ Microsoft Defender ATP และสร้างนโยบายการปฏิบัติตามนโยบายWindows 10การประเมินระดับความเสี่ยง สิทธิประโยชน์ของบริการไม่มีความช่วยเหลือในการซื้อ การให้สิทธิ์การใช้งาน หรือการเปิดใช้งาน |
|Windows Autopilot|ผู้ดูแลระบบ IT มีหน้าที่ลงทะเบียนอุปกรณ์ของตนกับองค์กรโดยให้ผู้จัดซื้อฮาร์ดแวร์อัปโหลดรหัสฮาร์ดแวร์ในนามของพวกเขาหรือโดยการอัปโหลดลงในบริการ Windows Autopilot |
|ปรับใช้Outlookบน iOS และ Android อย่างปลอดภัยด้วย Intuned|<br /><br />- ข้อมูลเฉพาะตัวของผู้ใช้ที่เปิดใช้งานใน Azure AD Office 365<br />- Exchange Online หรือ ไฮบริด Exchangeกําหนดค่ากับสิทธิ์การใช้งานของผู้ใช้ที่กําหนด<br />|
|Azure Information Protection (P2 หรือ EMS E5)|<br /><br />ลูกค้าควรเป็นลูกค้าแล้ว: <br /> - ใช้ Azure AD<br />- ใช้การWindowsหรือ iOS (OS อื่นๆ อยู่นอกขอบเขต)<br /> - ใช้Officeที่ใหม่กว่า Office 2010 SP2 ที่ไม่ได้ใช้Officeเป็นไคลเอ็นต์หลัก <br /> - มีสถานที่แชร์ไฟล์หลักของพวกเขา  <br /> - อัปเกรดจาก บริการ Active Directory Rights Management (AD RMS) แล้ว <br /> - มีการจัดหมวดหมู่ที่ได้รับอนุมัติ <br /> - เข้าใจข้อจํากัดด้านข้อบังคับในการจัดการคีย์ที่ได้รับการป้องกัน <br />|
|ตัวสแกน Azure Information Protection|<br /><br /> ลูกค้าควรเป็นลูกค้าแล้ว: <br /> - ใช้Windows Server 2012 R2 หรือ Windows Server 2016<br /> - เชื่อมต่ออินเทอร์เน็ต <br /> - ให้ Microsoft SQL Server 2012 เป็นต้นไปในอินสแตนซ์ภายในเครื่องหรือระยะไกล  <br /> - มีบัญชีบริการที่สร้างขึ้นใน Active Directory ภายในองค์กรและซิงโครไนซ์กับ Azure AD  <br /> - ดาวน์โหลดAzInfoProtection.exeแล้ว <br /> - กําหนดค่าป้ายชื่อไว้เพื่อการจัดประเภท/การป้องกันโดยอัตโนมัติ<br />|

> [!NOTE]
> **ต้องการเรียนรู้เพิ่มเติมใช่ไหม** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>ขั้นตอนถัดไป

[FastTrack สิทธิประโยชน์ของศูนย์เพื่อขั้นตอนการออนบอร์ดของ EMS](EMS-onboarding-phases.md)

