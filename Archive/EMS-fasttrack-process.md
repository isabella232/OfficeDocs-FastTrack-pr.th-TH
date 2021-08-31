---
title: กระบวนการFastTrackข้อมูล
description: ภาพรวมของกระบวนการออนFastTrackบอร์ดของศูนย์สิทธิประโยชน์
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
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 067eb95cd920848da63de0222867d6e1583b3c08
ms.sourcegitcommit: 3d086ab6c4743afbedebed55a3ddb65f05422a1b
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/30/2021
ms.locfileid: "58710446"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>กระบวนการสิทธิประโยชน์จากศูนย์ FastTrack สำหรับ Enterprise Mobility + Security (EMS)

> [!CAUTION]
> เนื้อหานี้จะไม่ใช่เนื้อหาปัจจุบันอีกต่อไปและถูกจัดเวลาให้เอาออก ใช้สารบัญในการนําทางด้านซ้ายมือกับเนื้อหาปัจจุบัน

ถ้าองค์กรของคุณมีสิทธิ์รับสิทธิประโยชน์ของ FastTrack Center for EMS คุณสามารถติดต่อผู้เชี่ยวชาญของ FastTrack จากระยะไกลเพื่อขอรับ Microsoft Azure Active Directory Premium, Microsoft Intune และ Azure Information Protection พร้อมให้ใช้งาน คุณยังสามารถขอความช่วยเหลือผ่านไซต์FastTrack [Azure](https://www.microsoft.com/fasttrack/microsoft-365/ems) Information Protection และMicrosoft Cloud App Securityได้ เมื่อต้องการเรียนรู้ว่าองค์กรของคุณมีสิทธิ์หรือไม่ ให้ดูที่[บริการและแผนที่มีสิทธิ์](M365-eligible-services-and-plans.md)


ต่อไปนี้คือสิ่งที่เราครอบคลุมเกี่ยวกับกระบวนการออนบอร์ด:

-   [ภาพรวมของกระบวนการออนบอร์ด](EMS-fasttrack-benefit-overview.md)

-   [ความคาดหวังต่อสภาพแวดล้อมต้นทางของคุณ](EMS-source-environment-expectations.md)

-   [ขั้นตอนต่างๆ ของกระบวนการออนบอร์ด](EMS-onboarding-phases.md)

-   [FastTrackความรับผิดชอบ](EMS-fasttrack-responsibilities.md)ในแต่ละขั้นตอน

-   [ความรับผิดชอบของลูกค้า](EMS-your-responsibilities.md) ในแต่ละขั้นตอน

นี่คือสิ่งที่คุณสามารถคาดหวังได้เมื่อการออนบอร์ดเสร็จสมบูรณ์:

-   ผู้เช่า EMS ของคุณสร้างขึ้นจากบริการที่คุณเลือก

-   ผู้ใช้ที่มีสิทธิ์การใช้งานสามารถเข้าถึงบริการ EMS โดยใช้หนึ่งในตัวเลือกข้อมูลเฉพาะตัวต่อไปนี้:

    -   ข้อมูลเฉพาะตัวบนระบบคลาวด์ (บัญชี EMS ที่ไม่ซ้")

    -   ข้อมูลเฉพาะตัวที่ซิงโครไนซ์: บัญชี EMS ที่ซิงโครไนซ์จาก Active Directory ภายในองค์กรของคุณโดยใช้เครื่องมือ Azure Active Directory เชื่อมต่อ (การซิงค์แฮชรหัสผ่าน หรือ การรับรองความถูกต้องแบบพาส-ผ่าน) ตัวเลือกนี้มีไว้ของลูกค้าที่มีฟอเรสต์เดียวหรือหลายฟอเรสต์ Active Directory

    -   ข้อมูลเฉพาะตัวภายนอก -- กับบัญชี Microsoft EMS ที่:

        -   ซิงโครไนซ์จาก Active Directory ด้วยเครื่องมือการเชื่อมต่อ Azure AD ตัวเลือกนี้มีไว้ของลูกค้าที่ใช้การกําหนดค่าฟอเรสต์ของ Active Directory เดียว

        -   ติดต่อกับภายนอกด้วย Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 หรือใหม่กว่าจาก Active Directory ภายในองค์กรของคุณ

        -   ความสามารถในการจัดประเภทและปกป้องข้อมูลโดยอัตโนมัติทั้งในที่ที่เหลือและระหว่างการขนส่งด้วย Azure Information Protection 

        -   ความสามารถในการค้นพบข้อมูลภายในการแชร์ไฟล์ภายในองค์กรSharePointเซิร์ฟเวอร์ด้วยตัวสแกน Azure Information Protection 

        -   ความสามารถในการจัดการคีย์ผู้เช่า Azure Information Protection ของคุณภายใน Azure Key Vault 

