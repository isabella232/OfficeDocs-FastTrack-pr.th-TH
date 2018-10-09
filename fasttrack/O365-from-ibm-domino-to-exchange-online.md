---
title: ภาคผนวก A - โยกย้ายจาก IBM Domino การแลกเปลี่ยนแบบออนไลน์
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/01/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: 'โยกย้ายจาก IBM Domino การแลกเปลี่ยนแบบออนไลน์มีความสำคัญด้านต่าง ๆ รวมถึงสิ่งที่เกิดขึ้นในระหว่างระยะต่อไปนี้:'
ms.openlocfilehash: 4097903eeffa998a4f4c10b6b3abb7df0d0677c6
ms.sourcegitcommit: a754d02f1dea1a2147f716a2cbebda7b68141777
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 10/01/2018
ms.locfileid: "25445178"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="51c85-103">ภาคผนวก A - โยกย้ายจาก IBM Domino การแลกเปลี่ยนแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="51c85-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="51c85-104">โยกย้ายจาก IBM Domino การแลกเปลี่ยนแบบออนไลน์มีความสำคัญด้านต่าง ๆ รวมถึงสิ่งที่เกิดขึ้นในระหว่างระยะต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="51c85-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="51c85-105">ขั้นตอนการเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="51c85-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="51c85-106">ขั้นตอนประเมิน</span><span class="sxs-lookup"><span data-stu-id="51c85-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="51c85-107">Remediate ขั้นตอน</span><span class="sxs-lookup"><span data-stu-id="51c85-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="51c85-108">ขั้นตอนการเปิดใช้งาน</span><span class="sxs-lookup"><span data-stu-id="51c85-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="51c85-109">ย้ายขั้นตอน</span><span class="sxs-lookup"><span data-stu-id="51c85-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="51c85-110">ข้อมูลเฉพาะตัว</span><span class="sxs-lookup"><span data-stu-id="51c85-110">Identities</span></span>

<span data-ttu-id="51c85-p101">คุณเป็นผู้รับผิดชอบสำหรับการสร้าง และการจัดการรหัสประจำตัว (cloud เท่านั้น การซิงโครไนส์ หรือติดต่อกับภายนอกกับไดเรกทอรีที่ใช้งานอยู่ในสถานของพวกเขา) คุณต้องทำการแม็ปผู้ใช้อีเมล (ถ้า ไม่มีแสดงอยู่แล้ว) ระหว่าง Domino และไดเรก ทอรีที่ใช้งานอยู่ในสถาน หรือโฆษณา Azure ในระหว่างขั้นตอนแรก ๆ ของการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="51c85-p101">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory). You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure AD during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="51c85-113">มีอยู่ร่วมกัน</span><span class="sxs-lookup"><span data-stu-id="51c85-113">Coexistence</span></span>

<span data-ttu-id="51c85-114">สวัสดิการศูนย์ FastTrack สำหรับ Office 365 ให้การรับส่งจดหมายแบบสองทิศทางระหว่างสภาพแวดล้อมของ Domino ในสถานที่และการแลกเปลี่ยนแบบออนไลน์กับลูกค้าทั้งหมด</span><span class="sxs-lookup"><span data-stu-id="51c85-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="51c85-115">การโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-115">Migration</span></span>

<span data-ttu-id="51c85-p102">กระบวนการ FastTrack ศูนย์มาตรฐานสำหรับการโยกย้ายจาก Domino ในการแลกเปลี่ยนแบบออนไลน์เกี่ยวข้องกับการจัดเตรียมข้อมูล Domino ไป Azure ก่อนที่จะย้ายระบบไปยังกล่องจดหมาย Exchange แบบออนไลน์ล่วงหน้า FastTrack migrations จำเป็นต้องมีกิจกรรมที่จะดำเนินการในขั้นตอนที่แตกต่างกันของการปฐมนิเทศ โดยบุคลากรศูนย์ FastTrack และคุณ เราครอบคลุมกิจกรรมเหล่านี้ในส่วนต่อไปนี้</span><span class="sxs-lookup"><span data-stu-id="51c85-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="51c85-p103">โยกย้ายข้อมูลผ่าน FastTrack การบริการอาจจะถูกโอนย้ายไป จัดเก็บ และประมวลผล ในสหรัฐอเมริกา หรือที่ใดก็ได้ที่ Microsoft รักษาสิ่งอำนวยความสะดวก บริการ FastTrack ไม่ได้รับการออกแบบ หรือไว้สำหรับข้อมูลขึ้นอยู่กับความต้องการพิเศษตามกฎหมาย หรือตามข้อบังคับ</span><span class="sxs-lookup"><span data-stu-id="51c85-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="51c85-121">ขั้นตอนการเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="51c85-121">Initiate phase</span></span>

 <span data-ttu-id="51c85-122">**การดำเนินการหลัก**</span><span class="sxs-lookup"><span data-stu-id="51c85-122">**Key actions**</span></span>
  
- <span data-ttu-id="51c85-123">ระบุ Domino เป็นแพลตฟอร์มจดหมายของแหล่งที่มา</span><span class="sxs-lookup"><span data-stu-id="51c85-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="51c85-124">กำหนดว่า ศูนย์ FastTrack ทำการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="51c85-125">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="51c85-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="51c85-126">แสดงข้อมูลพื้นฐานเกี่ยวกับแพลตฟอร์มส่งข้อความต้นฉบับ และยืนยันเจตนาโยกย้ายกับศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="51c85-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="51c85-127">มีส่วนร่วมในการฝึกปฏิบัติกระบวนการ FastTrack ศูนย์สวัสดิการ</span><span class="sxs-lookup"><span data-stu-id="51c85-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="51c85-128">ลงทะเบียนข้อตกลงบริการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="51c85-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="51c85-129">ขั้นตอนประเมิน</span><span class="sxs-lookup"><span data-stu-id="51c85-129">Assess phase</span></span>

 <span data-ttu-id="51c85-130">**การดำเนินการหลัก**</span><span class="sxs-lookup"><span data-stu-id="51c85-130">**Key actions**</span></span>
  
- <span data-ttu-id="51c85-131">ศูนย์กลาง FastTrack ดำเนินการทำเวิร์คโยกย้ายกับลูกค้า</span><span class="sxs-lookup"><span data-stu-id="51c85-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="51c85-132">การโยกย้ายข้อกำหนดเบื้องต้น เช่นแบบสอบถามการย้ายและการจัดเตรียมเวิร์กสเตชันของผู้ดูแลให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="51c85-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="51c85-133">มีดำเนินการโยกย้ายประเมินสำหรับ Domino ในสภาพแวดล้อมในสถานที่ของคุณ</span><span class="sxs-lookup"><span data-stu-id="51c85-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="51c85-134">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="51c85-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="51c85-135">การเตรียมใช้งานเวิร์กสเตชันของผู้ดูแลที่ศูนย์ FastTrack ใช้ในการจัดการปฐมนิเทศและโยกย้ายงาน เช่นเดียวกับการประเมิน การสร้างแบบจำลอง ตรวจสอบ การตั้งค่าการส่งต่อระหว่างการย้ายระบบ และอื่น ๆ</span><span class="sxs-lookup"><span data-stu-id="51c85-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="51c85-p104">ประเมินมีความสำคัญต่อการวางแผนเสร็จเรียบร้อยแล้วและการดำเนินการของความเร็ว migrations จะดำเนินการ โดยสถาปนิกการโยกย้ายที่ต้องการเข้าใช้งานกับสภาพแวดล้อมแบบ Domino คอมโพเนนต์ของเวิร์กสเตชันผู้ดูแลจำเป็นต้องรวมไคลเอนต์หมายเหตุการตั้งค่าคอนฟิกการเข้าถึงเซิร์ฟเวอร์จดหมาย Domino ต้นฉบับทั้งหมดและเซิร์ฟเวอร์การจำลองแบบจำลอง Azure Domino</span><span class="sxs-lookup"><span data-stu-id="51c85-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="51c85-p105">ให้การโยกย้ายทีมเข้าถึงระยะไกลไปยังเวิร์กสเตชันของผู้ดูแล บัญชี และสิทธิ์สำหรับการดำเนินการประเมินและการย้ายกิจกรรม ซึ่งรวมถึงการเตรียมใช้งานหลายบัญชีในสถานและ ในการแลกเปลี่ยนแบบออนไลน์ด้วยสิทธิ์ระดับผู้ดูแลที่จำเป็นสำหรับการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="51c85-p106">เปิดพอร์ตในไฟร์วอลล์ จะต้องเปิดพอร์ตขาออกระหว่างเซิร์ฟเวอร์จดหมาย Domino ต้นทางและเซิร์ฟเวอร์กำลังเตรียม Azure พอร์ตอื่น ๆ สำหรับการสื่อสาร (เช่นเดียวกับเวิร์กสเตชันของผู้ดูแล เซิร์ฟเวอร์ Domino ของแหล่งที่มา และ Exchange เซิร์ฟเวอร์ในสถาน (ถ้ามี)) ต้องยังต้องสามารถเปิด</span><span class="sxs-lookup"><span data-stu-id="51c85-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="51c85-p107">เปิดใช้งานใบรับรองข้ามระหว่างสภาพแวดล้อมการ Domino ต้นทางและเซิร์ฟเวอร์ Azure Domino จัดเตรียมเพื่อให้ง่ายต่อการจำลองแบบ รับรองข้ามงานกำลังใช้ร่วมกันระหว่าง admin Domino ของลูกค้าและศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="51c85-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="51c85-146">การโยกย้ายแบบสอบถาม ซึ่งรวบรวมข้อมูลที่จำเป็นในการกำหนดค่าสภาพแวดล้อมการโยกย้ายใน Azure (เช่นเครื่องมือ สคริปต์ และการย้ายเซิร์ฟเวอร์) ให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="51c85-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="51c85-147">ให้แน่ใจว่า กล่องจดหมายเป้าหมายใน Office 365 มีโพรโทคอลการส่งข้อความแอพลิเคชันโปรแกรมอินเทอร์เฟซ (MAPI) ที่เปิดใช้งาน</span><span class="sxs-lookup"><span data-stu-id="51c85-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="51c85-p108">แผน Office 365 บางอย่างไม่สนับสนุนโพรโทคอล MAPI เมื่อต้องการย้ายข้อมูล กล่องจดหมายจากแผนเหล่านี้ต้องถูกแปลงเป็นแผนที่สนับสนุน MAPI อยู่ก่อนหน้าเหตุการณ์การโยกย้าย ต่อไปนี้โยกย้าย แผนเหล่านี้สามารถเปลี่ยนกลับ</span><span class="sxs-lookup"><span data-stu-id="51c85-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="51c85-151">Remediate ขั้นตอน</span><span class="sxs-lookup"><span data-stu-id="51c85-151">Remediate phase</span></span>

 <span data-ttu-id="51c85-152">**การดำเนินการหลัก**</span><span class="sxs-lookup"><span data-stu-id="51c85-152">**Key actions**</span></span>
  
- <span data-ttu-id="51c85-153">ศูนย์กลาง FastTrack ตรวจทานรายงานการประเมินการโยกย้าย และรายละเอียดที่คุณป้อนโดยใช้แบบสอบถามทดสอบ</span><span class="sxs-lookup"><span data-stu-id="51c85-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="51c85-154">ต้องดำเนินการด้านสินค้าที่แนะนำ โดยศูนย์ FastTrack โดยคุณ</span><span class="sxs-lookup"><span data-stu-id="51c85-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="51c85-155">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="51c85-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="51c85-156">Remediate Domino สภาพแวดล้อมตามคำแนะนำที่ให้ศูนย์กลางการ FastTrack (ตัวอย่างเช่น การตั้งค่าสิทธิ์ที่จำเป็นใด ๆ ที่ระบุไว้เป็นขาดหายไปในแฟ้มจดหมาย)</span><span class="sxs-lookup"><span data-stu-id="51c85-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="51c85-157">ให้แน่ใจว่า กล่องจดหมาย Domino อยู่ต่ำกว่าขนาดสูงสุดที่ได้รับอนุญาตผ่านการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="51c85-158">ถึงแม้ว่า FastTrack ย้ายกล่องจดหมายได้ถึง 85% ของผลรวมที่ได้รับอนุญาตเป้าหมายขนาด พยายามที่จะย้ายกล่องจดหมายที่มีขนาดใหญ่กว่า 2 กิกะไบต์ทำการเพิ่มเติมความเสี่ยงเช่นเดียวกับ:</span><span class="sxs-lookup"><span data-stu-id="51c85-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="51c85-p109">ระยะเวลาที่ lengthened ของ migrations</span><span class="sxs-lookup"><span data-stu-id="51c85-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="51c85-p110">โดยใช้ทรัพยากรที่มีใช้สำหรับการโยกย้ายกล่องจดหมายอื่น</span><span class="sxs-lookup"><span data-stu-id="51c85-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="51c85-161">การเพิ่มขึ้นที่ใหญ่ในอัตราข้อผิดพลาด</span><span class="sxs-lookup"><span data-stu-id="51c85-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="51c85-p111">เตรียมจดหมายในฐานข้อมูล และควบคุมการเข้าถึงรายการ (Acl) สำหรับการโยกย้าย คุณต้องดำเนินการตามขั้นตอนบางอย่างด้านการโยกย้ายจดหมายในฐานข้อมูลและสิทธิ์ไปยังกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์เสร็จเรียบร้อยแล้ว สองสามขั้นตอนเหล่านี้มีดังนี้:</span><span class="sxs-lookup"><span data-stu-id="51c85-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="51c85-165">เอารายการจดหมายในฐานข้อมูลที่มีอยู่ในไดเรกทอรี Domino และสร้างเรกคอร์ดใหม่ของบุคคล</span><span class="sxs-lookup"><span data-stu-id="51c85-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="51c85-p112">สร้างกลุ่มการรักษาความปลอดภัยสากลที่เปิดใช้งานจดหมายในไดเรกทอรีที่ใช้งานอยู่การในสถานที่มีการซิงโครไนส์กับ Office 365 โฆษณา Azure และใช้ในการกำหนดค่าสิทธิ์ในกล่องจดหมายที่ใช้ร่วมกันใน Exchange แบบออนไลน์ การโอนย้ายนี้สิทธิ์ที่ตั้งบนจดหมายในฐานข้อมูลไปยังกล่องจดหมายที่ใช้ร่วมกันใน Exchange แบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="51c85-p112">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure AD and used to configure permissions on the shared mailbox in Exchange Online. This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="51c85-168">ความพร้อมของผู้ใช้และการฝึกอบรมสำหรับระบบการส่งข้อความใหม่และไคลเอนต์จะสามารถเริ่มต้นในขณะนี้</span><span class="sxs-lookup"><span data-stu-id="51c85-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="51c85-169">ขั้นตอนการเปิดใช้งาน</span><span class="sxs-lookup"><span data-stu-id="51c85-169">Enable phase</span></span>

 <span data-ttu-id="51c85-170">**การดำเนินการหลัก**</span><span class="sxs-lookup"><span data-stu-id="51c85-170">**Key actions**</span></span>
  
- <span data-ttu-id="51c85-171">ศูนย์ FastTrack:</span><span class="sxs-lookup"><span data-stu-id="51c85-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="51c85-172">ตั้งค่าสภาพแวดล้อมการโยกย้ายใน Azure</span><span class="sxs-lookup"><span data-stu-id="51c85-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="51c85-173">เครื่องมือการโยกย้ายการตั้งค่าคอนฟิกบนเวิร์กสเตชันการดูแลในสถาน</span><span class="sxs-lookup"><span data-stu-id="51c85-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="51c85-174">คุณสามารถกำหนดค่า และสาธิตวิธีการใช้เครื่องมือการนำเข้าอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="51c85-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="51c85-175">ดำเนินการตรวจสอบคอมโพเนนต์การโยกย้ายทั้งหมด และทำการทดสอบ migrations</span><span class="sxs-lookup"><span data-stu-id="51c85-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="51c85-176">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="51c85-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="51c85-p113">บุคลากรของคุณรับผิดชอบการวางแผนการย้ายกล่องจดหมายต้องเข้าใจวิธีการใช้เครื่องมือการนำเข้าอัตโนมัติ คุณสามารถใช้เครื่องมือนี้เพื่อนำเข้ากำหนดการโยกย้ายไปยังฐานข้อมูลการจัดกำหนดการซึ่งศูนย์ FastTrack ใช้เพื่อทำกิจกรรมก่อนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="51c85-179">ทำกิจกรรมต่าง ๆ เช่นการนำเข้าผู้ใช้กำหนดการ การวิเคราะห์รายงานการตรวจสอบ remediating ปัญหาต่าง ๆ และ reimporting บัญชีผู้ใช้ที่ มีปัญหาก่อนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="51c85-p114">กิจกรรมก่อนการโยกย้ายถูกใช้ร่วมกันระหว่างคุณและศูนย์ FastTrack จำลองการ Azure เริ่มต้นหลังจากที่มีการนำเข้าในกำหนดการการโยกย้ายผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="51c85-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="51c85-p115">เวลาต้องใช้ในการจำลองขึ้นอยู่กับจำนวนของข้อมูล กึ่งกลาง FastTrack แล้วทำการตรวจสอบเพื่อตรวจสอบความพร้อมในการโยกย้าย ผลลัพธ์การตรวจสอบหากคุณ มีความเข้าใจโดยปกติจำเป็นด้านที่ตามมา ขั้นตอนเหล่านี้ทั้งหมดจะเรียกว่า "เครื่อง T" กิจกรรมได้เนื่องจากต้องเริ่มต้นล่วงหน้าก่อนการโยกย้ายการจัดกำหนดการของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="51c85-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="51c85-186">ย้ายขั้นตอน</span><span class="sxs-lookup"><span data-stu-id="51c85-186">Migrate phase</span></span>

 <span data-ttu-id="51c85-187">**การดำเนินการหลัก**</span><span class="sxs-lookup"><span data-stu-id="51c85-187">**Key actions**</span></span>
  
- <span data-ttu-id="51c85-188">ศูนย์ FastTrack:</span><span class="sxs-lookup"><span data-stu-id="51c85-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="51c85-189">ดำเนินการ migrations ผู้นำร่องและอัตราเร็ว</span><span class="sxs-lookup"><span data-stu-id="51c85-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="51c85-190">ดำเนินการเหตุการณ์การโยกย้ายและกิจกรรมเครื่อง T</span><span class="sxs-lookup"><span data-stu-id="51c85-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="51c85-191">ให้ความช่วยเหลือหลังการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="51c85-192">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="51c85-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="51c85-193">ระบุ และนำเข้าตารางเวลาโยกย้าย 21 วันก่อนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="51c85-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="51c85-p116">งานนี้มีความสำคัญเนื่องจากกิจกรรมการโยกย้ายก่อนที่เกี่ยวข้องกับด้านและลองใหม่ที่เป็นไปได้ของการสร้างแบบจำลองในขั้นตอนต่าง ๆ ก่อนที่จะโยกย้ายจริงประจำวัน (T-0) ในขณะที่กำลังย้ายกล่องจดหมายบาง กิจกรรม T เครื่องกำลังดำเนินการอื่น ซึ่งทำให้การวางแผนและต้องประสานกันเหมาะสมจะต้อง</span><span class="sxs-lookup"><span data-stu-id="51c85-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="51c85-197">แก้ไขปัญหาที่ระบุในระหว่างกิจกรรมเครื่อง T</span><span class="sxs-lookup"><span data-stu-id="51c85-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="51c85-198">ที่อยู่ และแก้ไขปัญหาของเซิร์ฟเวอร์ที่มีผลกระทบต่อกิจกรรมการโยกย้าย Domino ใด ๆ</span><span class="sxs-lookup"><span data-stu-id="51c85-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="51c85-199">ทำการติดต่อสื่อสารสำหรับผู้ใช้เกี่ยวกับการโยกย้ายที่กำลังมาถึงวัน</span><span class="sxs-lookup"><span data-stu-id="51c85-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="51c85-200">ดำเนินการกิจกรรมความพร้อมของผู้ใช้และการฝึกอบรมสำหรับระบบการส่งข้อความใหม่และไคลเอนต์</span><span class="sxs-lookup"><span data-stu-id="51c85-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="51c85-p117">ระบุ และรายงานปัญหาหลังการโยกย้าย ศูนย์ FastTrack ให้ความช่วยเหลือหลังการโยกย้ายจนถึง T + 5 วันหลังจากโยกย้าย ซึ่งจะกลายเป็นความรับผิดชอบของคุณ คุณสามารถเข้าสู่ตั๋วหลังการย้าย สำหรับการตัดสินค้าจากคลังเช่นอีเมล รายการปฏิทิน และที่ติดต่อที่ขาดหายไป หรือ สำหรับรายการที่ซ้ำกันในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="51c85-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="51c85-204">ศูนย์ FastTrack ไม่ครอบคลุมปรับใช้ ค่าธรรมเนียมสิทธิ์การใช้งาน หรือขอความช่วยเหลือที่เกี่ยวข้องกับการจัดเตรียมของไดเรกทอรี (รวมถึงการซิงโครไนส์ไดเรกทอรี Domino เพื่อใช้งานไดเรกทอรี), โปรแกรม add-on ซอฟต์แวร์มีอยู่ร่วมกันสำหรับบันทึกย่อโปรแกรมประยุกต์ทำงานร่วมกัน การย้ายด้วยตนเอง หรือการย้ายเก็บ</span><span class="sxs-lookup"><span data-stu-id="51c85-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

