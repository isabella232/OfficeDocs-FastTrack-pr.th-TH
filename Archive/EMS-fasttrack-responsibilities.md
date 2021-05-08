---
title: ความรับผิดชอบของ FastTrack
description: ความรับผิดชอบของ FastTrack เมื่อลูกค้าใช้สิทธิประโยชน์ของศูนย์ FastTrack กับ EMS
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
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 46d059e97dc2eae307fed2596cd339be11062ad2
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283464"
---
# <a name="fasttrack-responsibilities"></a>ความรับผิดชอบของ FastTrack

> [!CAUTION]
> เนื้อหานี้จะไม่ใช่เนื้อหาปัจจุบันอีกต่อไปและถูกจัดเวลาให้เอาออก ใช้สารบัญในการนําทางด้านซ้ายมือกับเนื้อหาปัจจุบัน

FastTrack มีหน้าที่รับผิดชอบต่อไปนี้ระหว่างการออนบอร์ด

## <a name="general"></a>ทั่วไป

-   ให้ความช่วยเหลือสนับสนุนระยะไกลแก่คุณเพื่อรับกิจกรรมการกําหนดค่าที่กําหนดค่าตามที่ระบุไว้ในรายละเอียดรายละเอียดเกี่ยวกับขั้นตอน

-   มีเอกสารประกอบ เครื่องมือซอฟต์แวร์ และคอนโซลผู้ดูแลระบบที่พร้อมใช้งานเพื่อช่วยให้คุณลดหรือขจัดงานการกําหนดค่า

## <a name="initiate-phase"></a>เริ่มขั้นตอน

-   ใช้งานร่วมกับคุณเพื่อเริ่มการออนบอร์ด

-   กําหนดบริการที่มีสิทธิ์ที่คุณต้องการออนบอร์ด

## <a name="assess-phase"></a>ประเมินระยะ

-   ให้ภาพรวมการดูแลระบบ

-   ให้แนวทางเกี่ยวกับ:

    -   ความต้องการ DNS เครือข่าย และโครงสร้างพื้นฐาน

    -   ความต้องการของไคลเอ็นต์ (เบราว์เซอร์อินเทอร์เน็ต ระบบปฏิบัติการของไคลเอ็นต์ และความต้องการของบริการ)

    -   ข้อมูลเฉพาะตัวของผู้ใช้และการเตรียมใช้งาน

    -   การเปิดใช้งานบริการที่มีสิทธิ์ที่ซื้อและกําหนดให้เป็นส่วนหนึ่งของการออนบอร์ด

-   สร้างไทม์ไลน์เพื่อแก้ไขกิจกรรม

-   ระบุรายการตรวจสอบการแก้ไขของทั้ง Intuned และ Azure AD Premium

## <a name="remediate-phase"></a>แก้ไขขั้นตอน

-   พักสายการประชุมพร้อมกับคุณตามเวลาที่ตกลงไว้เพื่อทบทวนความคืบหน้าของกิจกรรมการแก้ไข เช่น แนะนะคุณผ่านการติดตั้งข้อกวมก่อนการออนบอร์ดบริการระบบคลาวด์ของ Microsoft

## <a name="enable-phase"></a>เปิดใช้งานระยะ
ให้แนวทางเกี่ยวกับ:

-   การเปิดใช้งานผู้เช่าหรือการสมัครใช้งานบริการออนไลน์ของ Microsoft ของคุณ

-   การกําหนดค่าโพรโทคอล TCP/IP และพอร์ตไฟร์วอลล์

-   การกําหนดค่า DNS ของบริการที่มีสิทธิ์

-   การตรวจสอบความถูกต้องของการเชื่อมต่อกับบริการออนไลน์ของ Microsoft

-   For a single-forest environment:

    -   การติดตั้งเซิร์ฟเวอร์การซิงโครไนซ์ไดเรกทอรีระหว่าง Active Directory Domain Services (AD DS) และบริการออนไลน์ของ Microsoft ที่มีสิทธิ์ (ถ้าต้องระบุเท่านั้น)

    -   การกําหนดค่าการรับรองความถูกต้องที่มีการจัดการ (การซิงค์แฮชรหัสผ่านหรือการรับรองความถูกต้องแบบพาสAzure Active Directory เชื่อมต่อ) ด้วยเครื่องมือการAzure Active Directory เชื่อมต่อรหัสผ่าน (เฉพาะแนวทางถ้าต้องระบุ)

        > [!NOTE]
        > การพัฒนาและการปรับใช้ส่วนขยายกฎแบบเองอยู่นอกขอบเขต

-   For a single forest when the target is federrated identities: Installing and configuring Active Directory Federation Services (AD FS) for local domain authentication with Intuned intuned intuned in a single-site, fault-todex configuration, if required.

    > [!NOTE]
    > การกําหนดค่าฟอเรสต์หลายการกําหนดค่าทั้งหมด การปรับใช้ AD FS อยู่นอกขอบเขต

-   ทดสอบฟังก์ชันการลงชื่อเข้าระบบครั้งเดียว (SSO) ถ้ามีการปรับใช้

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>เปิดใช้งานระยะ - Microsoft Azure Active Directory Premium

ให้แนวทางเกี่ยวกับ:

- การเปิดใช้งานผู้เช่า Azure AD Premiumของคุณ

- การกําหนดค่าพอร์ตไฟร์วอลล์

- การกําหนดค่า DNS ของบริการที่มีสิทธิ์

- การตรวจสอบความถูกต้องของการเชื่อมต่อไปยังบริการPremium Azure AD

- For a single-forest environment:

  -   การติดตั้งการซิงโครไนซ์ไดเรกทอรีระหว่าง Active Directory Domain Services (AD DS) และ Azure AD เชื่อมต่อ ของคุณ ถ้าต้องใช้

  -   การกําหนดค่าวิธีการรับรองความถูกต้อง (การซิงค์แฮชรหัสผ่านPass-Throughการรับรองความถูกต้อง) ด้วยเครื่องมือเชื่อมต่อ Azure AD

- For a multiple-forest environment:

  -   การติดตั้งการซิงโครไนซ์เชื่อมต่อ Azure AD ให้ตั้งค่าสถานการณ์สมมติแบบหลายฟอเรสต์
- For single- and multiple-forest environments:
  - การAzure Active Directoryผ่านการรับรองความถูกต้อง ถ้าต้องใช้
  - การAzure Active Directoryการกําหนดค่าSign-Onแบบเดี่ยวอย่างราบรื่น (SSO) ถ้าต้องใช้
    > [!NOTE]
    > Azure Active Directory การรับรองความถูกต้องแบบพาส-ทะลุผ่านสรีรวลแบบหลายฟอเรสต์ได้รับการสนับสนุนถ้ามีความเชื่อถือฟอเรสต์ระหว่างฟอเรสต์ Active Directory ของคุณ และถ้าการกําหนดเส้นทางส่วนต่อท้ายชื่อถูกกําหนดค่าอย่างถูกต้อง คุณสามารถติดตั้งตัวแทนเพิ่มเติมได้บนเซิร์ฟเวอร์ภายในองค์กรหลายเซิร์ฟเวอร์เพื่อให้มีความพร้อมใช้งานสูงในการร้องขอการลงชื่อเข้าใช้

  - For more information, see [Azure Active Directory Pass-through Authentication: Quick start](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) and Azure Active Directory Seamless Single [Sign-on: Quick start](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - For more information about pass-through authentication limits, see [Azure Active Directory Pass-through Authentication: Current limitations](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - For more information about Seamless SSO issues, see [Troubleshoot Azure Active Directory Seamless Single Sign-on](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > การซิงค์แฮชรหัสผ่านและ Writeback รหัสผ่านสนับสนุนฟอเรสต์หลายฟอเรสต์ อย่างไรก็ตาม สถานการณ์การเขียนกลับอื่นๆ ไม่ได้รับการสนับสนุน

  - การกําหนดค่าการซิงโครไนซ์ระหว่างฟอเรสต์ Active Directory ภายในองค์กรMicrosoft Azure Active Directory Premiumไดเรกทอรี (Azure Active Directory)

    > [!NOTE]
    > การพัฒนาและการปรับใช้ส่วนขยายกฎแบบเองอยู่นอกขอบเขต

- For a single forest when the target is federrated identities:

  -   การติดตั้งและการกําหนดค่า AD FS ของการรับรองความถูกต้องโดเมนภายในด้วย Azure AD Premium ในไซต์เดียว การกําหนดค่า fault-tooid (ถ้าต้องใช้)

  > [!NOTE]
  > การกําหนดค่าฟอเรสต์หลายการกําหนดค่าทั้งหมด การปรับใช้ AD FS อยู่นอกขอบเขต

- ทดสอบฟังก์ชันการใช้ฟังก์ชัน SSO (ถ้ามีการปรับใช้)

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>เปิดใช้งานระยะ - Azure AD Premium - ที่มี Azure AD เชื่อมต่อและ AD FS

ให้แนวทางเกี่ยวกับการตั้งค่า:

- การเตรียมใช้งานผู้ใช้ รวมถึงการให้สิทธิ์การใช้งาน

- การซิงค์ไดเรกทอรีเชื่อมต่อ Azure AD (ที่มีการซิงค์แฮชรหัสผ่านและแฮชของรหัสผ่าน)

  - Azure Active Directory ตั้งค่ารหัสผ่านใหม่แบบบริการตนเอง (SSPR)

  - การรับรองความถูกต้องโดยใช้หลายปัจจัยของ Azure

  - การรวมซอฟต์แวร์เป็นแอปพลิเคชันบริการ (SaaS) อย่างน้อยสาม (3) รายการกับ Sign-On (SSO) เดียวจาก[Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/)

  - การเตรียมใช้งานผู้ใช้โดยอัตโนมัติกับแอปพลิเคชัน SaaS ที่รวมไว้ล่วงหน้าตามที่ระบุไว้ในรายการบทช่วย [สอน](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list)การรวมแอป จํากัดเฉพาะการเตรียมใช้งานขาออกเท่านั้น

  - หน้าจอการเข้าสู่ระบบแบบปรับแต่งเอง รวมถึงโลโก้ ข้อความ และรูป

  - Self-Serviceและกลุ่มแบบไดนามิก (กลุ่ม)

  - Azure Active Directory พร็อกซีแอปพลิเคชัน

  - Azure Active Directory เชื่อมต่อสุขภาพของคุณ

  - Azure Active Directory การเข้าถึงตามเงื่อนไข

  - Azure Active Directory ข้อตกลงการใช้งาน

  - Azure Active Directory การป้องกันข้อมูลเฉพาะตัว

  - Azure Active Directory Privileged Identity Management

  - Azure Active Directory Access Reviews.

  -   Azure Active Directory การป้องกันด้วยรหัสผ่าน

  -   Azure Active Directory B2B.

### <a name="enable-phase---intune"></a>เปิดใช้งานระยะ - Intun1

> [!IMPORTANT]
> FastTrack ไม่สนับสนุนการจัดการWindows 10แบบคลาสสิกด้วย Intunk FastTrack สนับสนุนเฉพาะWindows 10ผ่านการจัดการอุปกรณ์เคลื่อนที่ Intuned (MDM)

ให้แนวทางเกี่ยวกับ:

-   การกําหนดค่าข้อมูลเฉพาะตัวที่จะใช้โดย Intuner โดยการใช้ประโยชน์จาก Active Directory ภายในองค์กรของคุณหรือข้อมูลเฉพาะตัวบนระบบคลาวด์ (Azure Active Directory)

-   การให้สิทธิ์การใช้งานแก่ผู้ใช้ของคุณ

-   การเพิ่มผู้ใช้ลงในการสมัครใช้งาน Intun1 ของคุณ การนิยามบทบาทผู้ดูแลระบบ IT และการสร้างผู้ใช้และกลุ่มอุปกรณ์

-   การกําหนดค่าผู้ให้บริการ MDM การจัดการอุปกรณ์เคลื่อนที่ของคุณ โดยยึดตามความต้องการด้านการจัดการของคุณ รวมถึง:

    -   การตั้งค่า Intuny เป็นอํานาจ MDM ของคุณ

    -   การกําหนดค่ากลุ่มการทดสอบที่จะใช้เพื่อตรวจสอบนโยบายการจัดการ MDM

    -   นําทางพอร์ทัลผู้ดูแลระบบ Intun1 เพื่อค้นหาข้อมูลผู้ใช้และอุปกรณ์

    -   การตั้งค่าบทบาท Intun1 (ผู้ให้บริการเจ้าหน้าที่ให้ความช่วยเหลือ ผู้ดูแลระบบ เป็นต้น)

    -   การกําหนดค่านโยบายและบริการการจัดการ MDM เช่น:

        -   การปรับใช้แอปของแต่ละแพลตฟอร์มที่ได้รับการสนับสนุนผ่านลิงก์เว็บ MSI และ/หรือลิงก์ลึก

        -   การปรับใช้Office ProPlus Windows 10อุปกรณ์อื่นๆ

        -   โปรแกรมการซื้อปริมาณมากเพื่อการปรับใช้แอป รวมถึง VPP ของ Apple, Windows Store for Business และ Google's Play for Work Store

        -   การปรับใช้อีเมล เครือข่ายไร้สาย และโปรไฟล์ VPN ถ้าคุณมีผู้ให้บริการออกใบรับรองที่มีอยู่ Wi-Fiโครงสร้างพื้นฐาน VPN ในองค์กรของคุณ

        -   การตั้งค่าตัวเชื่อมต่อMicrosoft Intune Exchangeตัวเชื่อมต่อ (ถ้ามี)

        -   โปรไฟล์การกําหนดค่าอุปกรณ์ของแพลตฟอร์มอุปกรณ์ที่สนับสนุน

    -   การตั้งค่านโยบายการเข้าถึงตามเงื่อนไข

    -   การกําหนดค่าและการปรับใช้นโยบายการป้องกันแอป Intuned ของแต่ละแพลตฟอร์มที่ได้รับการสนับสนุน

    -   การเตรียมแอปในสายงานธุรกิจ (LOB) สําหรับนโยบายการป้องกันแอป Intun <2> พร้อมแนวทางเกี่ยวกับตัวเลือกที่พร้อมใช้งาน

    -   การลงทะเบียนอุปกรณ์ของแพลตฟอร์มที่รองรับแต่ละแพลตฟอร์มกับ Intuned หรือตัวจัดการการกําหนดค่าMicrosoft Intuneบริการของคุณ

    -   การเชื่อมต่อไปยังคลังสินค้าของข้อมูล Intun1

    -   การรวม Intun1 กับ:
        -   ตัวแสดงทีมเพื่อขอรับความช่วยเหลือระยะไกล (ต้องมีการสมัครใช้งาน Team Viewer)

        -   โซลูชันคู่ค้า Mobile Threat Defense (ต้องมีการสมัครใช้งานโซลูชันของคู่ค้า Mobile Threat Defense)

        -   Telecom expense management solutions (Telecom expense management solution subscription is required).

        -   Microsoft Defender Advanced Threat Protection (Windows E5 หรือ Microsoft 365 E5ใบอนุญาต)

    -   การกําหนดค่าการอัปเดตซอฟต์แวร์ของแพลตฟอร์มที่รองรับ

    -   ทรัพยากรในการวางแผนการนํามาใช้ของผู้ใช้

- การตั้งค่าการWindows Autopilot:

    - กําหนดค่าและMicrosoft Intuneการตั้งค่าWindows Autopilot

    - กําหนดค่ากลุ่มแบบไดนามิกของ Azure AD

    - เพิ่มแบรนด์บริษัทของคุณลงใน Azure AD

    - สร้างและกําหนดอุปกรณ์Windowsโปรไฟล์ Autopilot (เช่น โปรไฟล์ Windows Autopilot ที่จํากัดการสร้างบัญชีผู้ดูแลระบบภายใน)

    - ปรับแต่ง ประสบการณ์แบบไม่อยู่ในกล่อง (OOBE) เพื่อให้สอดคล้องกับความต้องการขององค์กร

    - การกําหนดค่าการลงทะเบียน MDM อัตโนมัติใน Azure AD และ Intuned

    > [!NOTE]
    > การตั้งค่าWindows Autopilot ภายนอก Intunt อยู่นอกขอบเขตรับสิทธิประโยชน์ FastTrack

### <a name="enable-phase---cloud-attach"></a>เปิดใช้งานระยะ - การแนบ Cloud

ให้แนวทางเกี่ยวกับ:

-   การให้สิทธิ์การใช้งานแก่ผู้ใช้ของคุณ

-   การปรับใช้การแนบ Cloud ในคอนโซลตัวจัดการการกําหนดค่า

-   การเพิ่มผู้ใช้ลงในการสมัครใช้งาน Intun1 ของคุณ การนิยามบทบาทผู้ดูแลระบบ IT และการสร้างกลุ่มผู้ใช้และอุปกรณ์ (ถ้าไม่ได้ติดตั้ง Intun1)

-   การตั้งค่าการรวมแบบAzure Active Directoryแบบไฮบริด

-   การตั้งค่าAzure Active Directoryการลงทะเบียน MDM โดยอัตโนมัติ

-   การตั้งค่า Cloud Management Gateway

-   การเพิ่มผู้ใช้ลงในการสมัครใช้งาน Intun1 ของคุณ การนิยามบทบาทผู้ดูแลระบบ IT และการสร้างผู้ใช้และกลุ่มอุปกรณ์

-   การเตรียมบริการ Intun1 ในการจัดการอุปกรณ์

-   การตั้งค่าผู้ให้บริการการจัดการอุปกรณ์เคลื่อนที่ (MDM) เป็น Intuny

-   การกําหนดค่ากลุ่มการทดสอบที่จะใช้เพื่อตรวจสอบนโยบายการจัดการ MDM

-   นําทางพอร์ทัลผู้ดูแลระบบ Intun1 เพื่อค้นหาข้อมูลผู้ใช้และอุปกรณ์

-   การตั้งค่าบทบาท Intun1 (ผู้ให้บริการเจ้าหน้าที่ให้ความช่วยเหลือ ผู้ดูแลระบบ และอื่นๆ)

-   การลงทะเบียนWindows 10ไปยัง Intuned

-   การสลับปริมาณงานของการจัดการโดย Intuned ตามต้องการ

### <a name="enable-phase--azure-information-protection"></a>เปิดใช้งานระยะ - Azure Information Protection

ให้แนวทางเกี่ยวกับ: 

- การเปิดใช้งานและการกําหนดค่าผู้เช่าของลูกค้า

- การสร้างและการตั้งค่าป้ายชื่อและนโยบาย

- การใช้ตัวกรองป้องกันข้อมูลกับเอกสาร 

- จัดประเภทและติดป้ายข้อมูลในแอป Office โดยอัตโนมัติ (เช่น Word, PowerPoint, Excel และ Outlook) ที่เรียกใช้บน Windows และใช้ไคลเอ็นต์ Azure Information Protection

- การใช้ไฟล์ที่อยู่กับเครื่องสแกน Azure Information Protection

- การตรวจสอบอีเมลในระหว่างการขนส่งโดยใช้กฎExchange OnlineลExchange Onlineจดหมายของคุณ

นอกจากนี้ ยังมีแนวทางสําหรับลูกค้าที่ต้องการใช้การป้องกันโดยใช้ Microsoft Azure Rights Management Services (Azure RMS), การเข้ารหัสลับข้อความของ Office 365 (OME) และการป้องกันการสูญหายของข้อมูล (DLP)

> [!NOTE]
> **ต้องการเรียนรู้เพิ่มเติมใช่ไหม** ดู [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>ขั้นตอนถัดไป

[สิทธิประโยชน์ FastTrack ของ EMS - ความรับผิดชอบของคุณ](EMS-your-responsibilities.md)

