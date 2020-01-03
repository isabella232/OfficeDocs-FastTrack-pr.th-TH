---
title: ภาคผนวก A - การโยกย้ายจาก IBM Domino ไปยัง Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 1/03/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'การโยกย้ายจาก IBM Domino เพื่อแลกเปลี่ยนแบบออนไลน์มีหลายด้านที่สำคัญรวมถึงสิ่งที่เกิดขึ้นในระหว่างขั้นตอนต่อไปนี้:'
ms.openlocfilehash: 17d7b6669dbd5f8647ee7dcf7218f898ddac59fc
ms.sourcegitcommit: d7f4c9eafe7855c6ae02c2bd0fe3b700c458007c
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 01/02/2020
ms.locfileid: "40929275"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="94c61-103">ภาคผนวก A - การโยกย้ายจาก IBM Domino ไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="94c61-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="94c61-104">การโยกย้ายจาก IBM Domino เพื่อแลกเปลี่ยนแบบออนไลน์มีหลายด้านที่สำคัญรวมถึงสิ่งที่เกิดขึ้นในระหว่างขั้นตอนต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="94c61-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="94c61-105">เริ่มต้นเฟส</span><span class="sxs-lookup"><span data-stu-id="94c61-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="94c61-106">ประเมินระยะ</span><span class="sxs-lookup"><span data-stu-id="94c61-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="94c61-107">ระยะแก้ไข</span><span class="sxs-lookup"><span data-stu-id="94c61-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="94c61-108">เปิดใช้งานเฟส</span><span class="sxs-lookup"><span data-stu-id="94c61-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="94c61-109">ย้ายระยะ</span><span class="sxs-lookup"><span data-stu-id="94c61-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="94c61-110">Identities</span><span class="sxs-lookup"><span data-stu-id="94c61-110">Identities</span></span>

<span data-ttu-id="94c61-111">คุณมีความรับผิดชอบในการสร้างและจัดการข้อมูลเฉพาะตัว (cloud เท่านั้นซิงโครไนส์หรือติดต่อกับภายนอกกับไดเรกทอรีที่ใช้งานอยู่ในสถานที่ของพวกเขา)</span><span class="sxs-lookup"><span data-stu-id="94c61-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="94c61-112">คุณต้องทำการแม็ปของข้อมูลเฉพาะตัว (ถ้าไม่มีอยู่แล้ว) ระหว่าง Domino และไดเรกทอรีที่ใช้งานอยู่ในสถานที่หรือ Azure ที่ใช้งานอยู่ในระหว่างขั้นตอนแรกของการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="94c61-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="94c61-113">อยู่ร่วมกัน</span><span class="sxs-lookup"><span data-stu-id="94c61-113">Coexistence</span></span>

<span data-ttu-id="94c61-114">ประโยชน์ของศูนย์ FastTrack สำหรับ Office ๓๖๕มีโฟลว์จดหมายแบบสองทิศทางระหว่างสภาพแวดล้อม Domino ในสถานที่และการแลกเปลี่ยนแบบออนไลน์กับลูกค้าทั้งหมด</span><span class="sxs-lookup"><span data-stu-id="94c61-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="94c61-115">โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="94c61-115">Migration</span></span>

<span data-ttu-id="94c61-116">กระบวนการศูนย์ FastTrack มาตรฐานสำหรับการโยกย้ายจาก Domino เพื่อแลกเปลี่ยนแบบออนไลน์เกี่ยวข้องกับข้อมูล Domino ที่จัดเตรียมไว้ล่วงหน้าเพื่อ Azure ก่อนการโยกย้ายไปยังกล่องจดหมาย Exchange แบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="94c61-116">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes.</span></span> <span data-ttu-id="94c61-117">การย้ายข้อมูล FastTrack ต้องการกิจกรรมที่จะดำเนินการในขั้นตอนต่างๆของการปฐมนิเทศโดยบุคลากรของศูนย์ FastTrack และคุณ</span><span class="sxs-lookup"><span data-stu-id="94c61-117">FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you.</span></span> <span data-ttu-id="94c61-118">เราครอบคลุมกิจกรรมเหล่านี้ในส่วนต่อไปนี้</span><span class="sxs-lookup"><span data-stu-id="94c61-118">We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="94c61-119">ข้อมูลที่ถูกโยกย้ายผ่านทางบริการ FastTrack อาจถูกถ่ายโอนไปเก็บและประมวลผลในสหรัฐอเมริกาหรือที่ใดก็ได้ที่ Microsoft รักษาสิ่งอำนวยความสะดวก</span><span class="sxs-lookup"><span data-stu-id="94c61-119">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities.</span></span> <span data-ttu-id="94c61-120">บริการของ FastTrack ไม่ได้รับการออกแบบหรือมีไว้สำหรับข้อมูลภายใต้ข้อกำหนดทางกฎหมายหรือกฎระเบียบพิเศษ</span><span class="sxs-lookup"><span data-stu-id="94c61-120">The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="94c61-121">เริ่มต้นเฟส</span><span class="sxs-lookup"><span data-stu-id="94c61-121">Initiate phase</span></span>

 <span data-ttu-id="94c61-122">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="94c61-122">**Key actions**</span></span>
  
- <span data-ttu-id="94c61-123">ระบุ Domino เป็นแพลตฟอร์มจดหมายต้นทาง</span><span class="sxs-lookup"><span data-stu-id="94c61-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="94c61-124">ตรวจสอบว่าศูนย์ FastTrack ดำเนินการย้ายข้อมูลหรือไม่</span><span class="sxs-lookup"><span data-stu-id="94c61-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="94c61-125">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="94c61-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="94c61-126">ให้ข้อมูลพื้นฐานเกี่ยวกับแพลตฟอร์มการส่งข้อความต้นฉบับและยืนยันความต้องการในการย้ายข้อมูลด้วยศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c61-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="94c61-127">เข้าร่วมในการฝึกปฏิบัติของกระบวนการสวัสดิการของศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c61-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="94c61-128">ลงชื่อในข้อตกลงการให้บริการของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c61-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="94c61-129">ประเมินระยะ</span><span class="sxs-lookup"><span data-stu-id="94c61-129">Assess phase</span></span>

 <span data-ttu-id="94c61-130">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="94c61-130">**Key actions**</span></span>
  
- <span data-ttu-id="94c61-131">ศูนย์ FastTrack ดำเนินการเวิร์กชอปบโอนย้ายข้อมูลกับลูกค้า</span><span class="sxs-lookup"><span data-stu-id="94c61-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="94c61-132">คุณทำข้อกำหนดเบื้องต้นในการโยกย้ายให้เสร็จสมบูรณ์เช่นแบบสอบถามการโยกย้ายและการจัดสรรเวิร์กสเตชันของผู้ดูแลระบบ</span><span class="sxs-lookup"><span data-stu-id="94c61-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="94c61-133">การประเมินการโยกย้ายสำหรับ Domino จะดำเนินการในสภาพแวดล้อมในสถานที่ของคุณ</span><span class="sxs-lookup"><span data-stu-id="94c61-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="94c61-134">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="94c61-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="94c61-135">เตรียมใช้งานเวิร์กสเตชันของผู้ดูแลที่ศูนย์การการจัดการและการย้ายข้อมูลเช่นการประเมินการสร้างแบบจำลองการตรวจสอบการตั้งค่าการส่งต่อระหว่างการโยกย้ายและอื่นๆ</span><span class="sxs-lookup"><span data-stu-id="94c61-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="94c61-136">การประเมินเป็นสิ่งสำคัญสำหรับการวางแผนและการดำเนินการย้ายข้อมูลความเร็วที่สำเร็จ</span><span class="sxs-lookup"><span data-stu-id="94c61-136">Assessment is critical for successful planning and execution of velocity migrations.</span></span> <span data-ttu-id="94c61-137">มันดำเนินการโดยสถาปนิกโยกย้ายที่ต้องการการเข้าถึงเฉพาะสภาพแวดล้อม Domino</span><span class="sxs-lookup"><span data-stu-id="94c61-137">It's performed by a migration architect who needs specific access to the Domino environment.</span></span> <span data-ttu-id="94c61-138">คอมโพเนนต์ของเวิร์กสเตชัน admin ที่จำเป็นรวมถึงไคลเอ็นต์ของ Notes ที่กำหนดค่าเพื่อเข้าถึงเซิร์ฟเวอร์เมล Domino แหล่งที่มาทั้งหมดและเซิร์ฟเวอร์การจัดเตรียมแบบจำลอง Azure Domino</span><span class="sxs-lookup"><span data-stu-id="94c61-138">Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="94c61-139">จัดให้มีการเข้าถึงระยะไกลของทีมโยกย้ายไปยังเวิร์กสเตชันของผู้ดูแลระบบบัญชีและสิทธิ์ในการดำเนินกิจกรรมการประเมินและการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-139">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities.</span></span> <span data-ttu-id="94c61-140">ซึ่งรวมถึงการเตรียมใช้งานหลายบัญชีในสถานที่และในการแลกเปลี่ยนแบบออนไลน์ด้วยสิทธิ์ระดับผู้ดูแลที่จำเป็นสำหรับการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="94c61-140">This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="94c61-141">เปิดพอร์ตของไฟร์วอลล์</span><span class="sxs-lookup"><span data-stu-id="94c61-141">Open firewall ports.</span></span> <span data-ttu-id="94c61-142">พอร์ตขาออกต้องถูกเปิดระหว่างเซิร์ฟเวอร์เมล Domino แหล่งที่มาและเซิร์ฟเวอร์การจัดเตรียม Azure</span><span class="sxs-lookup"><span data-stu-id="94c61-142">Outbound ports must be opened between the source Domino mail servers and the Azure staging server.</span></span> <span data-ttu-id="94c61-143">พอร์ตอื่นๆสำหรับการสื่อสาร (เช่นเวิร์กสเตชันของ admin เซิร์ฟเวอร์ Domino แหล่งที่มาและเซิร์ฟเวอร์ Exchange ในสถาน (ถ้ามี)) ต้องเปิดด้วย</span><span class="sxs-lookup"><span data-stu-id="94c61-143">Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="94c61-144">เปิดใช้งานการรับรองข้ามระหว่างสภาพแวดล้อม Domino ต้นทางและเซิร์ฟเวอร์ Azure Domino การจัดเตรียมเพื่ออำนวยความสะดวกในการจำลองแบบ</span><span class="sxs-lookup"><span data-stu-id="94c61-144">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication.</span></span> <span data-ttu-id="94c61-145">งานการรับรองข้ามมีการประสานกันระหว่างผู้ดูแล Domino ของลูกค้าและศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c61-145">Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="94c61-146">กรอกแบบสอบถามการโยกย้ายซึ่งจะรวบรวมข้อมูลที่จำเป็นในการกำหนดค่าสภาพแวดล้อมการโยกย้ายใน Azure (เช่นเครื่องมือสคริปต์และเซิร์ฟเวอร์การโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="94c61-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="94c61-147">ตรวจสอบให้แน่ใจว่ากล่องจดหมายเป้าหมายใน Office ๓๖๕มีโพรโทคอลอินเทอร์เฟซโปรแกรมประยุกต์การส่งข้อความ (MAPI) ที่เปิดใช้งาน</span><span class="sxs-lookup"><span data-stu-id="94c61-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="94c61-148">บางแผน Office ๓๖๕ไม่สนับสนุนโพรโทคอล MAPI</span><span class="sxs-lookup"><span data-stu-id="94c61-148">Some Office 365 plans don't support MAPI protocol.</span></span> <span data-ttu-id="94c61-149">ในการย้ายข้อมูลกล่องจดหมายจากแผนเหล่านี้จะต้องถูกแปลงเป็นแผนซึ่งสนับสนุน MAPI ก่อนเหตุการณ์การย้าย</span><span class="sxs-lookup"><span data-stu-id="94c61-149">In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event.</span></span> <span data-ttu-id="94c61-150">แผนเหล่านี้สามารถเปลี่ยนกลับได้</span><span class="sxs-lookup"><span data-stu-id="94c61-150">Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="94c61-151">ระยะแก้ไข</span><span class="sxs-lookup"><span data-stu-id="94c61-151">Remediate phase</span></span>

 <span data-ttu-id="94c61-152">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="94c61-152">**Key actions**</span></span>
  
- <span data-ttu-id="94c61-153">ศูนย์ FastTrack จะตรวจสอบรายงานการประเมินการย้ายข้อมูลและทดสอบรายละเอียดที่คุณจัดหาโดยใช้คำถาม</span><span class="sxs-lookup"><span data-stu-id="94c61-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="94c61-154">รายการแก้ไขที่แนะนำโดยศูนย์ FastTrack ต้องเสร็จสมบูรณ์โดยคุณ</span><span class="sxs-lookup"><span data-stu-id="94c61-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="94c61-155">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="94c61-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="94c61-156">แก้ไขสภาพแวดล้อม Domino ตามแนวทางที่ศูนย์ FastTrack มีให้ (ตัวอย่างเช่นการตั้งค่าสิทธิ์ที่จำเป็นใดๆที่ระบุว่าขาดหายไปในแฟ้มจดหมาย)</span><span class="sxs-lookup"><span data-stu-id="94c61-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="94c61-157">ตรวจสอบให้แน่ใจว่ากล่องจดหมาย Domino ต่ำกว่าขนาดสูงสุดที่อนุญาตผ่านการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="94c61-158">แม้ว่า FastTrack จะย้ายกล่องจดหมายถึง๘๕% ของขนาดเป้าหมายที่ยอมรับได้ทั้งหมด, พยายามย้ายกล่องจดหมายที่มีขนาดใหญ่กว่า 2 GB มีความเสี่ยงเพิ่มเติมเช่น:</span><span class="sxs-lookup"><span data-stu-id="94c61-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="94c61-159">ระยะเวลาการย้ายข้อมูลที่ยาวขึ้น</span><span class="sxs-lookup"><span data-stu-id="94c61-159">Lengthened duration of migrations.</span></span>    <br/> <span data-ttu-id="94c61-160">การใช้ทรัพยากรอย่างอื่นที่ใช้สำหรับการย้ายกล่องจดหมายอื่นๆ</span><span class="sxs-lookup"><span data-stu-id="94c61-160">Using resources otherwise used for migrating other mailboxes.</span></span>    <br/> <span data-ttu-id="94c61-161">มีอัตราข้อผิดพลาดเพิ่มขึ้นมาก</span><span class="sxs-lookup"><span data-stu-id="94c61-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="94c61-162">จัดเตรียมฐานข้อมูลจดหมายและรายการควบคุมการเข้าถึง (Acl) สำหรับการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-162">Prepare the mail-in databases and their access control lists (ACLs) for migration.</span></span> <span data-ttu-id="94c61-163">คุณต้องดำเนินการบางขั้นตอนเพื่อย้ายฐานข้อมูลจดหมายในและสิทธิ์ของพวกเขาไปยังกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์สำเร็จ</span><span class="sxs-lookup"><span data-stu-id="94c61-163">You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online.</span></span> <span data-ttu-id="94c61-164">บางส่วนของขั้นตอนเหล่านี้มีดังนี้:</span><span class="sxs-lookup"><span data-stu-id="94c61-164">A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="94c61-165">ลบรายการฐานข้อมูลจดหมายที่มีอยู่ในไดเรกทอรี Domino และสร้างเรกคอร์ดบุคคลใหม่</span><span class="sxs-lookup"><span data-stu-id="94c61-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="94c61-166">สร้างกลุ่มความปลอดภัยสากลที่เปิดใช้งานจดหมายในไดเรกทอรีที่ใช้งานอยู่ในสถานที่ที่มีการซิงโครไนส์กับ Office ๓๖๕ Azure ไดเรกทอรีที่ใช้งานอยู่และใช้เพื่อกำหนดค่าสิทธิ์บนกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="94c61-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="94c61-167">การทำเช่นนี้จะเป็นการโอนสิทธิ์ที่ตั้งค่าไว้บนฐานข้อมูลจดหมายไปยังกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="94c61-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="94c61-168">ความพร้อมของผู้ใช้และการฝึกอบรมสำหรับระบบการส่งข้อความใหม่และไคลเอ็นต์สามารถเริ่มต้นได้ในขณะนี้</span><span class="sxs-lookup"><span data-stu-id="94c61-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="94c61-169">เปิดใช้งานเฟส</span><span class="sxs-lookup"><span data-stu-id="94c61-169">Enable phase</span></span>

 <span data-ttu-id="94c61-170">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="94c61-170">**Key actions**</span></span>
  
- <span data-ttu-id="94c61-171">ศูนย์ FastTrack:</span><span class="sxs-lookup"><span data-stu-id="94c61-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="94c61-172">ตั้งค่าสภาพแวดล้อมการโยกย้ายใน Azure</span><span class="sxs-lookup"><span data-stu-id="94c61-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="94c61-173">กำหนดค่าเครื่องมือการย้ายบนเวิร์กสเตชันของผู้ดูแลในสถานที่</span><span class="sxs-lookup"><span data-stu-id="94c61-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="94c61-174">กำหนดคอนฟิกและสาธิตวิธีการใช้เครื่องมือการนำเข้าอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="94c61-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="94c61-175">ดำเนินการตรวจสอบคอมโพเนนต์การย้ายทั้งหมดและทำการย้ายข้อมูลการทดสอบ</span><span class="sxs-lookup"><span data-stu-id="94c61-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="94c61-176">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="94c61-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="94c61-177">บุคลากรของคุณในการดูแลการย้ายกล่องจดหมายที่จัดตารางเวลาต้องเข้าใจวิธีการใช้เครื่องมือการนำเข้าอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="94c61-177">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool.</span></span> <span data-ttu-id="94c61-178">คุณสามารถใช้เครื่องมือนี้เพื่อนำเข้าตารางเวลาการโยกย้ายไปยังฐานข้อมูลการจัดกำหนดการที่ศูนย์ FastTrack ใช้เพื่อดำเนินกิจกรรมก่อนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="94c61-178">You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="94c61-179">ดำเนินการกิจกรรมก่อนการย้ายข้อมูลเช่นการนำเข้ากำหนดการของผู้ใช้วิเคราะห์รายงานการตรวจสอบ remediating ปัญหาใดๆและการนำเข้าบัญชีผู้ใช้ใหม่ที่มีปัญหา</span><span class="sxs-lookup"><span data-stu-id="94c61-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="94c61-180">กิจกรรมก่อนการโยกย้ายจะมีการประสานงานระหว่างคุณกับศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="94c61-180">Pre-migration activities are coordinated between you and the FastTrack Center.</span></span> <span data-ttu-id="94c61-181">การจำลองแบบไปยัง Azure เริ่มต้นหลังจากที่มีการนำเข้าตารางเวลาการโยกย้ายผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="94c61-181">Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="94c61-182">เวลาที่จำเป็นในการจำลองแบบจะขึ้นอยู่กับจำนวนของข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-182">The time required to replicate depends on the amount of data.</span></span> <span data-ttu-id="94c61-183">ศูนย์ FastTrack จะดำเนินการตรวจสอบเพื่อกำหนดความพร้อมในการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-183">The FastTrack Center then performs auditing to determine migration readiness.</span></span> <span data-ttu-id="94c61-184">ผลการตรวจสอบจะมีให้กับคุณด้วยความเข้าใจว่าการแก้ไขที่ตามมาเป็นเรื่องปกติ</span><span class="sxs-lookup"><span data-stu-id="94c61-184">Audit results are provided to you with the understanding that subsequent remediation is normally required.</span></span> <span data-ttu-id="94c61-185">ขั้นตอนทั้งหมดเหล่านี้เรียกว่า "T-ลบ" กิจกรรมเนื่องจากพวกเขาต้องเริ่มต้นล่วงหน้าของผู้ใช้ที่กำหนดเวลาการย้ายถิ่น</span><span class="sxs-lookup"><span data-stu-id="94c61-185">All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="94c61-186">ย้ายระยะ</span><span class="sxs-lookup"><span data-stu-id="94c61-186">Migrate phase</span></span>

 <span data-ttu-id="94c61-187">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="94c61-187">**Key actions**</span></span>
  
- <span data-ttu-id="94c61-188">ศูนย์ FastTrack:</span><span class="sxs-lookup"><span data-stu-id="94c61-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="94c61-189">ดำเนินการย้ายข้อมูลของนักบินและความเร็ว</span><span class="sxs-lookup"><span data-stu-id="94c61-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="94c61-190">ดำเนินการเหตุการณ์การโยกย้ายและกิจกรรม T-ลบ</span><span class="sxs-lookup"><span data-stu-id="94c61-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="94c61-191">ให้ความช่วยเหลือหลังการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="94c61-192">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="94c61-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="94c61-193">ระบุและนำเข้ากำหนดการย้ายข้อมูล21วันก่อนการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="94c61-194">งานนี้มีความสำคัญเนื่องจากกิจกรรมก่อนการย้ายข้อมูลเกี่ยวข้องกับการแก้ไขและการพยายามสร้างแบบจำลองที่เป็นไปได้ในขั้นตอนต่างๆก่อนวันโยกย้ายจริง (T-0)</span><span class="sxs-lookup"><span data-stu-id="94c61-194">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0).</span></span> <span data-ttu-id="94c61-195">ในขณะที่กล่องจดหมายบางชนิดกำลังย้ายข้อมูลจะมีการดำเนินการกิจกรรม T ลบกับผู้อื่น</span><span class="sxs-lookup"><span data-stu-id="94c61-195">While some mailboxes are migrating, T-minus activities are being performed on others.</span></span> <span data-ttu-id="94c61-196">นี้จะทำให้การวางแผนและการประสานงานที่เหมาะสมต้อง.</span><span class="sxs-lookup"><span data-stu-id="94c61-196">This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="94c61-197">แก้ไขปัญหาที่ระบุในระหว่างการลบกิจกรรมที</span><span class="sxs-lookup"><span data-stu-id="94c61-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="94c61-198">ที่อยู่และแก้ไขปัญหาเซิร์ฟเวอร์ Domino ใดๆที่ส่งผลกระทบต่อกิจกรรมการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="94c61-199">ดำเนินการสื่อสารกับผู้ใช้ปลายทางเกี่ยวกับวันที่ย้ายข้อมูลที่กำลังจะเกิดขึ้น</span><span class="sxs-lookup"><span data-stu-id="94c61-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="94c61-200">ดำเนินการกิจกรรมความพร้อมของผู้ใช้และการฝึกอบรมสำหรับระบบการส่งข้อความใหม่และไคลเอนต์</span><span class="sxs-lookup"><span data-stu-id="94c61-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="94c61-201">ระบุและรายงานปัญหาหลังการย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="94c61-201">Identify and report post-migration issues.</span></span> <span data-ttu-id="94c61-202">ศูนย์ FastTrack มีความช่วยเหลือหลังการโยกย้ายจนกว่าจะถึง T + 5 วันหลังจากการโยกย้ายหลังจากที่มันจะกลายเป็นความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="94c61-202">The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility.</span></span> <span data-ttu-id="94c61-203">คุณสามารถเข้าสู่ระบบตั๋วหลังการย้ายข้อมูลสำหรับปัญหาต่างๆเช่นการหายไปของจดหมายรายการปฏิทินและที่ติดต่อหรือสำหรับรายการที่ซ้ำกันในกล่องเมล</span><span class="sxs-lookup"><span data-stu-id="94c61-203">You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="94c61-204">ศูนย์ FastTrack ไม่ครอบคลุมการปรับใช้ค่าธรรมเนียมใบอนุญาตหรือความช่วยเหลือที่เกี่ยวข้องกับการจัดเตรียมไดเรกทอรี (รวมถึงการซิงโครไนส์ไดเรกทอรีที่ใช้งานอยู่ไดเรกทอรีของ Domino), โปรแกรม add-on ของซอฟต์แวร์ร่วมกันสำหรับโปรแกรมประยุกต์ Notes การโอนย้ายบริการตนเองหรือการโอนย้ายที่เก็บถาวร</span><span class="sxs-lookup"><span data-stu-id="94c61-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

