---
title: ภาพรวมสิทธิประโยชน์จากศูนย์ FastTrack
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: ด้วยสิทธิประโยชน์ของศูนย์ FastTrack Office 365 คุณจะได้รับการร่วมงานกับผู้เชี่ยวชาญด้าน FastTrack จากระยะไกลเพื่อเตรียมสภาพแวดล้อม Office 365 ของคุณให้พร้อมใช้งาน และวางแผนการเริ่มใช้งานและการใช้งานภายในองค์กรของคุณ เมื่อต้องการเรียนรู้เพิ่มเติมเกี่ยวกับสิทธิ์ ให้ดูที่ สิทธิประโยชน์ของศูนย์ FastTrack Office 365
ms.openlocfilehash: 039a1a409f35d12e61e25757e18f481c2b754571
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283501"
---
# <a name="fasttrack-center-benefit-overview"></a>ภาพรวมสิทธิประโยชน์จากศูนย์ FastTrack

> [!CAUTION]
> เนื้อหานี้จะไม่ใช่เนื้อหาปัจจุบันอีกต่อไปและถูกจัดเวลาให้เอาออก ใช้สารบัญในการนําทางด้านซ้ายมือกับเนื้อหาปัจจุบัน

ด้วยสิทธิประโยชน์ของศูนย์ FastTrack Office 365 คุณจะได้รับการร่วมงานกับผู้เชี่ยวชาญด้าน FastTrack จากระยะไกลเพื่อเตรียมสภาพแวดล้อม Office 365 ของคุณให้พร้อมใช้งาน และวางแผนการเริ่มใช้งานและการใช้งานภายในองค์กรของคุณ เมื่อต้องการเรียนรู้เพิ่มเติมเกี่ยวกับสิทธิ์ ให้ดูที่ สิทธิประโยชน์ของ[ศูนย์ FastTrack Office 365](O365-fasttrack-benefit-for-office-365.md)
  
เราครอบคลุมหัวข้อต่อไปนี้:
- [กระบวนการ FastTrack](O365-fasttrack-process.md) 
- [ข้อกำหนดของสภาพแวดล้อมต้นทาง](O365-source-environment-expectations.md)
- [ขั้นตอนการออนบอร์ดและการโยกย้าย](O365-onboarding-and-migration.md)
- [การโยกย้ายข้อมูล](O365-data-migration.md)
- [ความรับผิดชอบของ FastTrack](O365-fasttrack-responsibilities.md)
- [ความรับผิดชอบของคุณ](O365-your-responsibilities.md) 
- [ภาคผนวก A - สิทธิประโยชน์เพิ่มเติมจากศูนย์ FastTrack](O365-fasttrack-additional-benefits.md)
- [ภาคผนวก B - ข้อตกลง HIPAA Business Associate ของศูนย์ FastTrack](O365-hipaa-business-associate-agreement.md)
- [ภาคผนวก C - ภาพรวมสิทธิประโยชน์จากศูนย์ FastTrack สำหรับ Office 365 US Government](US-Gov-appendix-overview.md)
    
ผู้Office 365ของคุณจะถูกสร้างขึ้นเมื่อออนบอร์ดเสร็จสมบูรณ์ ผู้ใช้ที่มีสิทธิ์การใช้งานสามารถเข้าถึงOffice 365ได้โดยใช้หนึ่งในตัวเลือกข้อมูลเฉพาะตัวต่อไปนี้:
- ข้อมูลเฉพาะตัวบนระบบคลาวด์ด้วยOffice 365เฉพาะ
- ข้อมูลเฉพาะตัวที่ซิงโครไนซ์Office 365บัญชีที่ซิงโครไนซ์จาก Active Directory ภายในองค์กรของคุณกับ Azure Active Directory เชื่อมต่อ (การซิงค์แฮชรหัสผ่าน หรือการรับรองความถูกต้องแบบพาส-ตลอด) รายการเหล่านี้มีให้ลูกค้าที่มี:
  - สภาพแวดล้อม Active Directory ฟอเรสต์เดียว
  - โทโพโลยี Active Directory แบบหลายฟอเรสต์ที่สนับสนุน For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
- ข้อมูลเฉพาะตัวภายนอกOffice 365บัญชีต่อไปนี้:
  - ซิงโครไนซ์จาก Active Directory ด้วยเครื่องมือAzure Active Directory เชื่อมต่อข้อมูลของลูกค้าด้วย
      - Active Directory ฟอเรสต์การกําหนดค่าเดียว
      - Active Directory บัญชีผู้ใช้ฟอเรสต์เดียว (หรือที่เรียกว่า "Logon Forest") และการกําหนดค่าฟอเรสต์ของทรัพยากร Active Directory เดียว
  - กําหนดค่าด้วยโครงสร้างพื้นฐาน Active Directory Federation Services (AD FS) ภายในองค์กร ซึ่งได้แก่
      - ภายนอกด้วยบทบาท Windows Server 2012 R2 บน AD FS จาก Active Directory ภายในองค์กรของคุณ
      - เมื่อต้องระบุ บทบาท Windows Server 2012 R2 เป็นต้นไป Windows Application Proxy (WAP) ที่ใช้ในการประกาศโครงสร้างพื้นฐาน AD FS ภายในองค์กรของคุณไปยังอินเทอร์เน็ต
    > [!NOTE]
    > การปรับใช้และการกําหนดค่า AD FS และ WAP เสร็จสิ้นโดยใช้ตัวช่วยสร้าง[เชื่อมต่อกําหนด](https://go.microsoft.com/fwlink/?linkid=844794)ค่า Azure AD จากสภาพแวดล้อมภายในองค์กรของคุณ 
  
- ผู้ใช้ที่มีสิทธิ์การใช้งานสามารถเข้าถึง [บริการและแผนที่มีสิทธิ์](M365-eligible-services-and-plans.md)ได้แล้วในขณะนี้

