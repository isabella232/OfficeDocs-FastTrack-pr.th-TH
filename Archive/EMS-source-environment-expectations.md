---
title: ความคาดหวังของสภาพแวดล้อมต้นทาง
description: ความต้องการของสภาพแวดล้อมต้นทางในการใช้สิทธิประโยชน์ของศูนย์ FastTrack for EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: None
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 285dee7b2372af0615673ecd330051fc50f49212
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283458"
---
# <a name="source-environment-expectations"></a>ข้อกำหนดของสภาพแวดล้อมต้นทาง
> [!CAUTION]
> เนื้อหานี้จะไม่ใช่เนื้อหาปัจจุบันอีกต่อไปและถูกจัดเวลาให้เอาออก ใช้สารบัญในการนําทางด้านซ้ายมือกับเนื้อหาปัจจุบัน

เมื่อคุณใช้สิทธิประโยชน์[ของศูนย์ FastTrack for Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md)เพื่อรับ Microsoft Azure Active Directory Premium, Microsoft Intune และ Azure Information Protection พร้อมให้ใช้งาน สภาพแวดล้อมของคุณจะต้องมีความคาดหมายตามที่อธิบายไว้ในส่วนต่อไปนี้

คุณอาจมี Active Directory ภายในองค์กรอยู่แล้วในองค์กรของคุณที่คุณต้องการรวมกับ Enterprise Mobility + Security (EMS) หรือบริการเฉพาะใดๆ ที่ใช้การจัดการข้อมูลเฉพาะตัวแบบสมบูรณ์จากคอนโซลเดียว สิทธิประโยชน์ของ FastTrack Center for Enterprise Mobility + Security (EMS) Azure Active Directoryรวมกับสภาพแวดล้อม Active Directory ภายในองค์กรของคุณ

ตารางต่อไปนี้แสดงความคาดหวังต่อสภาพแวดล้อมแหล่งข้อมูลที่มีอยู่ของคุณในการออนบอร์ด

|กิจกรรม|ความคาดหวังของสภาพแวดล้อมต้นทาง|
|------------|----------------------------------|
|การออนบอร์ดหลัก|Active Directory ฟอเรสต์ที่มีระดับฟอเรสต์ฟังก์ชันตั้งค่าWindows Server 2008 หรือสูงกว่า ด้วยการกําหนดค่าฟอเรสต์ต่อไปนี้:<br /><br />- ฟอเรสต์ Active Directory เดียว<br />- หลายฟอเรสต์ Active Directory </br></br>**หมายเหตุ**: การปรับใช้ Active Directory Federation Services (AD FS) อยู่นอกขอบเขตการกําหนดค่าฟอเรสต์ทั้งหมด สิทธิประโยชน์ของศูนย์ FastTrack|
|การPremiumการออนบอร์ดของ Azure AD|Active Directory ภายในองค์กรและสภาพแวดล้อมของ Azure AD ได้รับการเตรียมพร้อมPremium Azure AD Premium ซึ่งรวมถึงการแก้ไขปัญหาที่ระบุที่ป้องกันการรวมกับฟีเจอร์ Azure AD Premium Azure AD|
|Intuns on-boarding| ผู้ดูแลระบบ IT ต้องมีโครงสร้างพื้นฐานผู้ให้บริการออกใบรับรอง, WiFi และ VPN ที่ใช้งานได้ในสภาพแวดล้อมการผลิตอยู่แล้ว เมื่อวางแผนการปรับใช้โปรไฟล์ WiFi และ VPN กับ Intuny<br /><br /> **หมายเหตุ**: สิทธิประโยชน์ของบริการไม่มีความช่วยเหลือในการตั้งค่าหรือกําหนดค่าผู้ให้บริการออกใบรับรอง, WiFi, โครงสร้างพื้นฐาน VPN หรือใบรับรองแบบพุชของ Apple MDM  |
|ตัวจัดการการกําหนดค่าที่แนบบนระบบคลาวด์ด้วย Intun1|ด้วยการแนบระบบ Cloud ผู้ดูแลระบบ IT มีหน้าที่รับผิดชอบในการจัดเตรียมสภาพแวดล้อมภายในองค์กร ซึ่งอาจรวมถึงการแก้ไขปัญหาที่ป้องกันไม่ให้คุณแนบสภาพแวดล้อมตัวจัดการการกําหนดค่ากับ Intuns บนระบบคลาวด์<br /><br />**หมายเหตุ**: สิทธิประโยชน์ของบริการ FastTrack ไม่มีความช่วยเหลือในการตั้งค่าหรืออัปเกรดเซิร์ฟเวอร์ไซต์ตัวจัดการการกําหนดค่า หรือไคลเอ็นต์ตัวจัดการการกําหนดค่าเป็นความต้องการขั้นต่สุดที่ต้องใช้ในการสนับสนุนการแนบ Cloud |
|Intuned ที่รวมเข้ากับ Microsoft Defender Advanced Threat Protection (ATP)|**หมายเหตุ**: สิทธิประโยชน์ของบริการ FastTrack จะให้ความช่วยเหลือในการผนวกรวม Intun Microsoft Defender ATP และการสร้างนโยบายการปฏิบัติตามนโยบายอุปกรณ์โดยยึดตามWindows 10การประเมินระดับความเสี่ยง สิทธิประโยชน์ของบริการไม่มีความช่วยเหลือในการซื้อ การให้สิทธิ์การใช้งาน หรือการเปิดใช้งาน |
|Windows Autopilot|ผู้ดูแลระบบ IT มีหน้าที่ลงทะเบียนอุปกรณ์ของตนกับองค์กรโดยให้ผู้จัดซื้อฮาร์ดแวร์อัปโหลดรหัสฮาร์ดแวร์ในนามของพวกเขาหรือโดยการอัปโหลดลงในบริการ Windows Autopilot |
|ปรับใช้Outlookบน iOS และ Android อย่างปลอดภัยด้วย Intuned|<br /><br />- ข้อมูลเฉพาะตัวของผู้ใช้ที่เปิดใช้งานใน Azure AD Office 365<br />- Exchange Online หรือ ไฮบริด Exchangeกําหนดค่ากับสิทธิ์การใช้งานของผู้ใช้ที่กําหนด<br />|
|Azure Information Protection (P2 หรือ EMS E5)|<br /><br />ลูกค้าควรเป็นลูกค้าแล้ว: <br /> - ใช้ Azure AD<br />- ใช้ทั้ง Windows หรือ iOS (OS อื่นๆ อยู่นอกขอบเขต)<br /> - ใช้Officeที่ใหม่กว่า Office 2010 SP2 ที่ไม่ได้ใช้ Office เป็นไคลเอ็นต์หลัก <br /> - มีสถานที่แชร์ไฟล์หลักของพวกเขา  <br /> - อัปเกรดจาก บริการ Active Directory Rights Management (AD RMS) แล้ว <br /> - มีการจัดหมวดหมู่ที่ได้รับอนุมัติ <br /> - เข้าใจข้อจํากัดด้านข้อบังคับในการจัดการคีย์ที่ได้รับการป้องกัน <br />|
|ตัวสแกน Azure Information Protection|<br /><br /> ลูกค้าควรเป็นลูกค้าแล้ว: <br /> - ใช้Windows Server 2012 R2 หรือ Windows Server 2016<br /> - เชื่อมต่ออินเทอร์เน็ต <br /> - ให้ Microsoft SQL Server 2012 เป็นต้นไปในอินสแตนซ์ภายในเครื่องหรือระยะไกล  <br /> - มีบัญชีบริการที่สร้างขึ้นใน Active Directory ภายในองค์กรและซิงโครไนซ์กับ Azure AD  <br /> - ดาวน์โหลดAzInfoProtection.exeแล้ว <br /> - กําหนดค่าป้ายชื่อไว้เพื่อการจัดประเภท/การป้องกันโดยอัตโนมัติ<br />|

> [!NOTE]
> **ต้องการเรียนรู้เพิ่มเติมใช่ไหม** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>ขั้นตอนถัดไป

[สิทธิประโยชน์ของศูนย์ FastTrack เพื่อระยะการออนบอร์ดของ EMS](EMS-onboarding-phases.md)

