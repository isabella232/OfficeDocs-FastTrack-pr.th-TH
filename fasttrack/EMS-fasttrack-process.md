---
title: กระบวนการ FastTrack
description: ภาพรวมของกระบวนการปฐมนิเทศสิทธิประโยชน์ของ FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 380ccc613301c1b85d59b232ec10194111f6c63b
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800493"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>กระบวนการสิทธิประโยชน์จากศูนย์ FastTrack สำหรับ Enterprise Mobility + Security (EMS)

> [!CAUTION]
> เนื้อหานี้ไม่ได้อยู่ในปัจจุบันอีกต่อไปและมีการจัดกำหนดการสำหรับการเอาออก ใช้สารบัญในการนำทางด้านซ้ายสำหรับเนื้อหาปัจจุบัน

ถ้าองค์กรของคุณมีสิทธิ์ได้รับสิทธิประโยชน์สำหรับ EMS FastTrack คุณสามารถทำงานได้จากระยะไกลกับผู้เชี่ยวชาญ FastTrack เพื่อรับ Microsoft Azure Active Directory Premium, Microsoft Intune และการป้องกันข้อมูล Azure พร้อมใช้งาน นอกจากนี้คุณยังสามารถขอความช่วยเหลือผ่าน [ไซต์ FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) สำหรับการป้องกันข้อมูล Azure และการรักษาความปลอดภัยของแอป Microsoft Cloud เมื่อต้องการเรียนรู้ว่าองค์กรของคุณมีสิทธิ์หรือไม่ให้ดูที่ [บริการและแผน](M365-eligible-services-and-plans.md)ที่มีสิทธิ์การใช้งาน


ต่อไปนี้คือสิ่งที่เราครอบคลุมเกี่ยวกับกระบวนการปฐมนิเทศ:

-   [ภาพรวมของกระบวนการปฐมนิเทศ](EMS-fasttrack-benefit-overview.md)

-   [ความคาดหวังสำหรับสภาพแวดล้อมต้นฉบับของคุณ](EMS-source-environment-expectations.md)

-   [ขั้นตอนของกระบวนการปฐมนิเทศ](EMS-onboarding-phases.md)

-   ความ[รับผิดชอบของ FastTrack](EMS-fasttrack-responsibilities.md)สำหรับแต่ละขั้นตอน

-   ความ[รับผิดชอบของลูกค้า](EMS-your-responsibilities.md)สำหรับแต่ละขั้นตอน

ต่อไปนี้คือสิ่งที่คุณสามารถคาดหวังเมื่อปฐมนิเทศเสร็จสมบูรณ์:

-   ผู้เช่า EMS ของคุณสำหรับบริการที่คุณเลือกจะถูกสร้างขึ้น

-   ผู้ใช้ที่ได้รับสิทธิ์การใช้งานสามารถเข้าถึงบริการ EMS ได้โดยใช้หนึ่งในตัวเลือกข้อมูลประจำตัวต่อไปนี้:

    -   ข้อมูลเฉพาะตัวของระบบคลาวด์ (บัญชีผู้ใช้ EMS ที่ไม่ซ้ำกัน)

    -   ข้อมูลประจำตัวที่ซิงโครไนซ์: บัญชีผู้ใช้ EMS ที่ซิงโครไนซ์จาก active Directory ภายในองค์กรของคุณโดยใช้เครื่องมือการเชื่อมต่อ Azure Active Directory (รหัสผ่านการซิงค์หรือการรับรองความถูกต้องแบบพาส-ทรู) ตัวเลือกนี้มีไว้สำหรับลูกค้าที่มีฟอเรสต์เดี่ยวหรือฟอเรสต์ไดเรกทอรีที่ใช้งานอยู่หลายรายการ

    -   ข้อมูลประจำตัวที่ติดต่อกับภายนอก--ด้วยบัญชีผู้ใช้ Microsoft EMS ที่มีดังต่อไปนี้

        -   ซิงโครไนซ์จาก Active Directory กับเครื่องมือการเชื่อมต่อ AD Azure ตัวเลือกนี้มีไว้สำหรับลูกค้าที่มีการกำหนดค่าฟอเรสต์ของไดเรกทอรีที่ใช้งานอยู่เดียว

        -   ที่ติดต่อกับภายนอกด้วย Windows Server ๒๐๑๒ R2 บริการสหพันธรัฐไดเรกทอรีที่ใช้งานอยู่ (AD FS) ๒.๐หรือใหม่กว่าจากไดเรกทอรีที่ใช้งานอยู่ภายในองค์กรของคุณ

        -   ความสามารถในการจัดประเภทโดยอัตโนมัติและการปกป้องข้อมูลทั้งในส่วนที่เหลือและการส่งต่อด้วยการป้องกันข้อมูล Azure 

        -   ความสามารถในการค้นหาข้อมูลภายในการแชร์ไฟล์ภายในองค์กรและเซิร์ฟเวอร์ SharePoint ด้วยสแกนเนอร์การป้องกันข้อมูลของ Azure 

        -   ความสามารถในการจัดการคีย์ผู้เช่าที่ปกป้องข้อมูล Azure ของคุณภายในระบบป้องกันคีย์ Azure 

