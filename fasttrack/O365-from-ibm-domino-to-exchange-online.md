---
title: ภาคผนวก A - การโยกย้ายจาก IBM Domino ไปยัง Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 3/03/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'การโยกย้ายจาก IBM Domino แลกเปลี่ยนแบบออนไลน์รวมถึงด้านที่สำคัญหลายประการรวมทั้งสิ่งที่เกิดขึ้นในระหว่างขั้นตอนต่อไปนี้:'
ms.openlocfilehash: ac945137e7beee0d0813ce171fc7292d683e9cd9
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347581"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="d5521-103">ภาคผนวก A - การโยกย้ายจาก IBM Domino ไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d5521-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="d5521-104">การโยกย้ายจาก IBM Domino แลกเปลี่ยนแบบออนไลน์รวมถึงด้านที่สำคัญหลายประการรวมทั้งสิ่งที่เกิดขึ้นในระหว่างขั้นตอนต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="d5521-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="d5521-105">ขั้นตอนการเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="d5521-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="d5521-106">ประเมินระยะ</span><span class="sxs-lookup"><span data-stu-id="d5521-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="d5521-107">Remediate เฟส</span><span class="sxs-lookup"><span data-stu-id="d5521-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="d5521-108">เปิดใช้งานเฟส</span><span class="sxs-lookup"><span data-stu-id="d5521-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="d5521-109">ขั้นตอนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="d5521-110">Identities</span><span class="sxs-lookup"><span data-stu-id="d5521-110">Identities</span></span>

<span data-ttu-id="d5521-111">คุณต้องรับผิดชอบในการสร้างและจัดการข้อมูลเฉพาะตัว (cloud เท่านั้นซิงโครไนส์หรือติดต่อกับภายนอกกับไดเรกทอรีที่ใช้งานอยู่ในสถานที่ของตน)</span><span class="sxs-lookup"><span data-stu-id="d5521-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="d5521-112">คุณต้องทำการแมปของข้อมูลเฉพาะตัว (ถ้าไม่มีอยู่) ระหว่าง Domino และไดเรกทอรีที่ใช้งานอยู่ในสถานที่หรือไดเรกทอรีที่ใช้งานอยู่ Azure ในระหว่างขั้นตอนแรกของปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="d5521-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="d5521-113">ร่วม</span><span class="sxs-lookup"><span data-stu-id="d5521-113">Coexistence</span></span>

<span data-ttu-id="d5521-114">FastTrack ศูนย์ประโยชน์สำหรับ Office ๓๖๕ให้การไหลของจดหมายแบบสองทิศทางระหว่างสภาพแวดล้อมโดมิโนในสถานที่และการแลกเปลี่ยนแบบออนไลน์กับลูกค้าทั้งหมด</span><span class="sxs-lookup"><span data-stu-id="d5521-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="d5521-115">โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-115">Migration</span></span>

<span data-ttu-id="d5521-116">ขั้นตอนการ FastTrack มาตรฐานสำหรับการโยกย้ายจาก Domino เพื่อแลกเปลี่ยนแบบออนไลน์เกี่ยวข้องกับข้อมูล Domino ก่อนการเตรียมใช้งาน Azure ก่อนที่จะย้ายไปยังกล่องจดหมาย Exchange แบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="d5521-116">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes.</span></span> <span data-ttu-id="d5521-117">การโยกย้าย FastTrack ต้องมีกิจกรรมที่จะดำเนินการในระยะที่แตกต่างกันของปฐมนิเทศโดยเจ้าหน้าที่ศูนย์ FastTrack และคุณ</span><span class="sxs-lookup"><span data-stu-id="d5521-117">FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you.</span></span> <span data-ttu-id="d5521-118">เราครอบคลุมกิจกรรมเหล่านี้ในส่วนต่อไปนี้</span><span class="sxs-lookup"><span data-stu-id="d5521-118">We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="d5521-119">ข้อมูลที่ย้ายผ่านทางบริการ FastTrack อาจถูกถ่ายโอนไปยังที่เก็บและประมวลผลในสหรัฐอเมริกาหรือที่ใดก็ตามที่ Microsoft เก็บรักษาสิ่งอำนวยความสะดวก</span><span class="sxs-lookup"><span data-stu-id="d5521-119">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities.</span></span> <span data-ttu-id="d5521-120">บริการ FastTrack ไม่ได้ออกแบบมาหรือมีไว้สำหรับข้อมูลภายใต้ข้อกำหนดทางกฎหมายหรือกฎระเบียบพิเศษ</span><span class="sxs-lookup"><span data-stu-id="d5521-120">The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="d5521-121">ขั้นตอนการเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="d5521-121">Initiate phase</span></span>

 <span data-ttu-id="d5521-122">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="d5521-122">**Key actions**</span></span>
  
- <span data-ttu-id="d5521-123">ระบุ Domino เป็นแพลตฟอร์มจดหมายต้นทาง</span><span class="sxs-lookup"><span data-stu-id="d5521-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="d5521-124">ตรวจสอบว่าศูนย์ FastTrack ดำเนินการย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="d5521-125">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="d5521-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="d5521-126">ให้ข้อมูลพื้นฐานเกี่ยวกับแพลตฟอร์มการส่งข้อความต้นทางและยืนยันการย้ายที่มีความตั้งใจกับศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5521-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="d5521-127">มีส่วนร่วมในการฝึกปฏิบัติของกระบวนการสวัสดิการศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5521-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="d5521-128">ลงนามในข้อตกลงการให้บริการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5521-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="d5521-129">ประเมินระยะ</span><span class="sxs-lookup"><span data-stu-id="d5521-129">Assess phase</span></span>

 <span data-ttu-id="d5521-130">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="d5521-130">**Key actions**</span></span>
  
- <span data-ttu-id="d5521-131">ศูนย์ FastTrack จะดำเนินการย้ายเวิร์กชอปกับลูกค้า</span><span class="sxs-lookup"><span data-stu-id="d5521-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="d5521-132">คุณดำเนินการข้อกำหนดเบื้องต้นในการโยกย้ายเช่นแบบสอบถามการโยกย้ายและการจัดเตรียมของเวิร์กสเตชันของผู้ดูแลระบบ</span><span class="sxs-lookup"><span data-stu-id="d5521-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="d5521-133">การประเมินการโยกย้ายสำหรับ Domino จะดำเนินการในสภาพแวดล้อมในสถานที่ของคุณ</span><span class="sxs-lookup"><span data-stu-id="d5521-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="d5521-134">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="d5521-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="d5521-135">สำรองข้อมูลผู้ดูแลเวิร์กสเตชันที่ศูนย์ FastTrack ใช้ในการจัดการงานปฐมนิเทศและการย้ายเช่นการประเมินการสร้างแบบจำลองการตรวจสอบการตั้งค่าการส่งต่อในระหว่างการย้ายและอื่นๆ</span><span class="sxs-lookup"><span data-stu-id="d5521-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="d5521-136">การประเมินเป็นสิ่งสำคัญสำหรับการวางแผนและการดำเนินการโยกย้ายความเร็ว</span><span class="sxs-lookup"><span data-stu-id="d5521-136">Assessment is critical for successful planning and execution of velocity migrations.</span></span> <span data-ttu-id="d5521-137">มันดำเนินการโดยสถาปนิกการโยกย้ายที่ต้องการการเข้าถึงที่เฉพาะเจาะจงไปยังสภาพแวดล้อมโดมิโน</span><span class="sxs-lookup"><span data-stu-id="d5521-137">It's performed by a migration architect who needs specific access to the Domino environment.</span></span> <span data-ttu-id="d5521-138">คอมโพเนนต์ของเวิร์กสเตชันของผู้ดูแลระบบที่จำเป็นรวมถึงไคลเอนต์บันทึกการกำหนดค่าการเข้าถึงเซิร์ฟเวอร์จดหมายทั้งหมดที่ต้นทาง Domino และเซิร์ฟเวอร์การจัดเตรียมแบบจำลอง Azure Domino</span><span class="sxs-lookup"><span data-stu-id="d5521-138">Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="d5521-139">ให้การเข้าถึงระยะไกลของทีมการโยกย้ายไปยังเวิร์กสเตชันของผู้ดูแลระบบบัญชีและสิทธิ์สำหรับการดำเนินการประเมินและการย้ายกิจกรรม</span><span class="sxs-lookup"><span data-stu-id="d5521-139">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities.</span></span> <span data-ttu-id="d5521-140">ซึ่งรวมถึงการจัดเตรียมหลายบัญชีในสถานที่และในการแลกเปลี่ยนแบบออนไลน์ที่มีสิทธิ์ระดับผู้ดูแลที่จำเป็นสำหรับการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-140">This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="d5521-141">เปิดพอร์ตไฟร์วอลล์</span><span class="sxs-lookup"><span data-stu-id="d5521-141">Open firewall ports.</span></span> <span data-ttu-id="d5521-142">พอร์ตขาออกต้องถูกเปิดระหว่างเซิร์ฟเวอร์จดหมายโดมิโนต้นทางและเซิร์ฟเวอร์การจัดเตรียม Azure</span><span class="sxs-lookup"><span data-stu-id="d5521-142">Outbound ports must be opened between the source Domino mail servers and the Azure staging server.</span></span> <span data-ttu-id="d5521-143">พอร์ตอื่นๆสำหรับการสื่อสาร (เช่นเวิร์กสเตชัน admin เซิร์ฟเวอร์โดมิโนต้นทางและเซิร์ฟเวอร์ Exchange ในสถานที่ (ถ้ามี))) ต้องถูกเปิด</span><span class="sxs-lookup"><span data-stu-id="d5521-143">Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="d5521-144">เปิดใช้งานการรับรองข้ามระหว่างสภาพแวดล้อมโดมิโนแหล่งที่มาและเซิร์ฟเวอร์การจัดเตรียม Azure Domino เพื่ออำนวยความสะดวกในการจำลองแบบ</span><span class="sxs-lookup"><span data-stu-id="d5521-144">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication.</span></span> <span data-ttu-id="d5521-145">งานการรับรองแบบไขว้จะประสานระหว่างผู้ดูแลโดมิโนของลูกค้าและศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5521-145">Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="d5521-146">กรอกแบบสอบถามการโยกย้ายซึ่งจับข้อมูลที่จำเป็นในการกำหนดค่าสภาพแวดล้อมการโยกย้ายใน Azure (เช่นเครื่องมือสคริปต์และเซิร์ฟเวอร์การย้าย)</span><span class="sxs-lookup"><span data-stu-id="d5521-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="d5521-147">ให้แน่ใจว่ากล่องจดหมายเป้าหมายใน Office ๓๖๕มีการส่งข้อความแอพลิเคชันโปรแกรมอินเทอร์เฟซ (MAPI) โพรโทคอลที่เปิดใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d5521-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="d5521-148">บางแผน Office ๓๖๕ไม่สนับสนุนโพรโทคอล MAPI</span><span class="sxs-lookup"><span data-stu-id="d5521-148">Some Office 365 plans don't support MAPI protocol.</span></span> <span data-ttu-id="d5521-149">เมื่อต้องการย้ายข้อมูลกล่องจดหมายจากแผนเหล่านี้จำเป็นต้องถูกแปลงเป็นแผนที่สนับสนุน MAPI ก่อนหน้าของเหตุการณ์การโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-149">In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event.</span></span> <span data-ttu-id="d5521-150">การย้ายต่อไปนี้แผนเหล่านี้สามารถเปลี่ยนกลับ</span><span class="sxs-lookup"><span data-stu-id="d5521-150">Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="d5521-151">Remediate เฟส</span><span class="sxs-lookup"><span data-stu-id="d5521-151">Remediate phase</span></span>

 <span data-ttu-id="d5521-152">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="d5521-152">**Key actions**</span></span>
  
- <span data-ttu-id="d5521-153">FastTrack ศูนย์ความคิดเห็นรายงานการประเมินการย้ายและทดสอบรายละเอียดที่คุณจัดหาโดยใช้แบบสอบถาม</span><span class="sxs-lookup"><span data-stu-id="d5521-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="d5521-154">ไอเท็มที่แนะนำโดยศูนย์ FastTrack ต้องดำเนินการให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="d5521-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="d5521-155">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="d5521-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="d5521-156">Remediate สภาพแวดล้อมโดมิโนตามแนวทางที่ศูนย์ FastTrack ให้ (ตัวอย่างเช่นการตั้งค่าสิทธิ์ที่จำเป็นใดๆที่ระบุว่าขาดหายไปในแฟ้มจดหมาย)</span><span class="sxs-lookup"><span data-stu-id="d5521-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="d5521-157">ตรวจสอบให้แน่ใจว่ากล่องจดหมายโดมิโนต่ำกว่าขนาดสูงสุดที่อนุญาตผ่านการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="d5521-158">ถึงแม้ว่า FastTrack ย้ายกล่องจดหมายได้ถึง๘๕% ของขนาดปลายทางรวมที่อนุญาตพยายามที่จะย้ายกล่องจดหมายที่มีขนาดใหญ่กว่า2กิกะไบต์ทำความเสี่ยงเพิ่มเติมเช่น:</span><span class="sxs-lookup"><span data-stu-id="d5521-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="d5521-159">ระยะเวลาขยายของการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-159">Lengthened duration of migrations.</span></span>    <br/> <span data-ttu-id="d5521-160">การใช้ทรัพยากรอื่นที่ใช้สำหรับการโยกย้ายกล่องจดหมายอื่น</span><span class="sxs-lookup"><span data-stu-id="d5521-160">Using resources otherwise used for migrating other mailboxes.</span></span>    <br/> <span data-ttu-id="d5521-161">เพิ่มขึ้นมากในอัตราข้อผิดพลาด</span><span class="sxs-lookup"><span data-stu-id="d5521-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="d5521-162">เตรียมการจดหมายในฐานข้อมูลและรายการควบคุมการเข้าถึง (Acl) สำหรับการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-162">Prepare the mail-in databases and their access control lists (ACLs) for migration.</span></span> <span data-ttu-id="d5521-163">คุณต้องทำขั้นตอนบางอย่างเพื่อโยกย้ายจดหมายในฐานข้อมูลและสิทธิ์ของพวกเขาไปยังกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์เสร็จเรียบร้อยแล้ว</span><span class="sxs-lookup"><span data-stu-id="d5521-163">You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online.</span></span> <span data-ttu-id="d5521-164">ขั้นตอนเหล่านี้บางอย่างจะเป็นดังนี้:</span><span class="sxs-lookup"><span data-stu-id="d5521-164">A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="d5521-165">เอาจดหมายที่มีอยู่ในรายการฐานข้อมูลในไดเรกทอรี Domino และสร้างเรกคอร์ดบุคคลใหม่</span><span class="sxs-lookup"><span data-stu-id="d5521-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="d5521-166">สร้างกลุ่มความปลอดภัยสากลที่เปิดใช้งานจดหมายในไดเรกทอรีที่ใช้งานอยู่ในสถานที่ที่มีการซิงโครไนส์กับ Office ๓๖๕ Azure ไดเรกทอรีที่ใช้งานอยู่และใช้การกำหนดค่าสิทธิ์ในกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="d5521-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="d5521-167">การโอนย้ายสิทธิ์ที่ตั้งค่าบนฐานข้อมูลจดหมายในไปยังกล่องจดหมายที่ใช้ร่วมกันในการแลกเปลี่ยนแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="d5521-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="d5521-168">การเตรียมพร้อมสำหรับผู้ใช้และการฝึกอบรมสำหรับระบบการส่งข้อความใหม่และลูกค้าสามารถเริ่มต้นได้ในขณะนี้</span><span class="sxs-lookup"><span data-stu-id="d5521-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="d5521-169">เปิดใช้งานเฟส</span><span class="sxs-lookup"><span data-stu-id="d5521-169">Enable phase</span></span>

 <span data-ttu-id="d5521-170">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="d5521-170">**Key actions**</span></span>
  
- <span data-ttu-id="d5521-171">เดอะ FastTrack เซ็นเตอร์:</span><span class="sxs-lookup"><span data-stu-id="d5521-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="d5521-172">ตั้งค่าสภาพแวดล้อมการโยกย้ายใน Azure</span><span class="sxs-lookup"><span data-stu-id="d5521-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="d5521-173">กำหนดค่าเครื่องมือการโยกย้ายบนเวิร์กสเตชันของผู้ดูแลในสถานที่</span><span class="sxs-lookup"><span data-stu-id="d5521-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="d5521-174">กำหนดค่าและอธิบายวิธีการใช้เครื่องมือนำเข้าอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="d5521-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="d5521-175">ดำเนินการตรวจสอบคอมโพเนนต์การโยกย้ายทั้งหมดและทำการโยกย้ายการทดสอบ</span><span class="sxs-lookup"><span data-stu-id="d5521-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="d5521-176">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="d5521-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="d5521-177">บุคลากรของคุณในการย้ายเก็บกล่องจดหมายการจัดกำหนดการต้องเข้าใจวิธีการใช้เครื่องมือการนำเข้าอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="d5521-177">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool.</span></span> <span data-ttu-id="d5521-178">คุณใช้เครื่องมือนี้เพื่อนำเข้ากำหนดการโยกย้ายลงในฐานข้อมูลการจัดกำหนดการซึ่งศูนย์ FastTrack ใช้ในการดำเนินการกิจกรรมก่อนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-178">You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="d5521-179">ดำเนินการกิจกรรมก่อนการโยกย้ายเช่นการนำเข้าตารางเวลาของผู้ใช้การวิเคราะห์รายงานการตรวจสอบ remediating ปัญหาใดๆและบัญชีผู้ใช้ลองที่มีปัญหา</span><span class="sxs-lookup"><span data-stu-id="d5521-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="d5521-180">กิจกรรมก่อนการโยกย้ายจะมีการประสานงานระหว่างคุณกับศูนย์ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d5521-180">Pre-migration activities are coordinated between you and the FastTrack Center.</span></span> <span data-ttu-id="d5521-181">การจำลองแบบ Azure เริ่มต้นหลังจากที่มีการนำเข้ากำหนดการโยกย้ายผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d5521-181">Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="d5521-182">เวลาที่จำเป็นต้องทำซ้ำขึ้นอยู่กับจำนวนข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d5521-182">The time required to replicate depends on the amount of data.</span></span> <span data-ttu-id="d5521-183">ศูนย์ FastTrack ทำการตรวจสอบเพื่อกำหนดความพร้อมในการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-183">The FastTrack Center then performs auditing to determine migration readiness.</span></span> <span data-ttu-id="d5521-184">โดยปกติแล้วผลการตรวจสอบจะเป็นไปตามที่กำหนดไว้</span><span class="sxs-lookup"><span data-stu-id="d5521-184">Audit results are provided to you with the understanding that subsequent remediation is normally required.</span></span> <span data-ttu-id="d5521-185">ขั้นตอนเหล่านี้ทั้งหมดจะเรียกว่า "T-ลบ" กิจกรรมเนื่องจากพวกเขาต้องเริ่มต้นล่วงหน้าของการโยกย้ายที่กำหนดเวลาของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d5521-185">All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="d5521-186">ขั้นตอนการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-186">Migrate phase</span></span>

 <span data-ttu-id="d5521-187">**การดำเนินการที่สำคัญ**</span><span class="sxs-lookup"><span data-stu-id="d5521-187">**Key actions**</span></span>
  
- <span data-ttu-id="d5521-188">เดอะ FastTrack เซ็นเตอร์:</span><span class="sxs-lookup"><span data-stu-id="d5521-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="d5521-189">ดำเนินการนำร่องและความเร็วในการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="d5521-190">ดำเนินการเหตุการณ์การโยกย้ายและกิจกรรม T-ลบ</span><span class="sxs-lookup"><span data-stu-id="d5521-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="d5521-191">ให้ความช่วยเหลือหลังการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="d5521-192">**ความรับผิดชอบของลูกค้า**</span><span class="sxs-lookup"><span data-stu-id="d5521-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="d5521-193">ระบุและนำเข้าตารางเวลาการโยกย้าย21วันก่อนการย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="d5521-194">งานนี้เป็นสิ่งสำคัญเนื่องจากกิจกรรมก่อนการโยกย้ายที่เกี่ยวข้องกับด้านและการลองใหม่ที่เป็นไปได้ของการสร้างแบบจำลองในระยะที่แตกต่างกันก่อนวันโยกย้ายที่แท้จริง (T-0)</span><span class="sxs-lookup"><span data-stu-id="d5521-194">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0).</span></span> <span data-ttu-id="d5521-195">ในขณะที่กล่องจดหมายบางอย่างจะถูกย้ายกิจกรรม T-ลบจะถูกดำเนินการกับผู้อื่น</span><span class="sxs-lookup"><span data-stu-id="d5521-195">While some mailboxes are migrating, T-minus activities are being performed on others.</span></span> <span data-ttu-id="d5521-196">ซึ่งทำให้การวางแผนและการประสานงานที่เหมาะสมต้อง</span><span class="sxs-lookup"><span data-stu-id="d5521-196">This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="d5521-197">แก้ไขปัญหาที่ระบุในระหว่างกิจกรรม T-ลบ</span><span class="sxs-lookup"><span data-stu-id="d5521-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="d5521-198">ที่อยู่และแก้ไขปัญหาใดๆของเซิร์ฟเวอร์ Domino ที่มีผลกระทบต่อกิจกรรมการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="d5521-199">การดำเนินการสื่อสารของผู้ใช้ปลายทางเกี่ยวกับวันโยกย้ายที่จะเกิดขึ้น</span><span class="sxs-lookup"><span data-stu-id="d5521-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="d5521-200">ทำกิจกรรมการเตรียมพร้อมสำหรับผู้ใช้และฝึกอบรมสำหรับระบบการส่งข้อความใหม่และลูกค้า</span><span class="sxs-lookup"><span data-stu-id="d5521-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="d5521-201">ระบุและรายงานปัญหาหลังการย้าย</span><span class="sxs-lookup"><span data-stu-id="d5521-201">Identify and report post-migration issues.</span></span> <span data-ttu-id="d5521-202">ศูนย์ FastTrack ให้ความช่วยเหลือหลังการโยกย้ายจนถึง T + 5 วันหลังจากการโยกย้ายหลังจากที่จะกลายเป็นความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="d5521-202">The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility.</span></span> <span data-ttu-id="d5521-203">คุณสามารถเข้าสู่ระบบตั๋วหลังการย้ายสำหรับปัญหาเช่นอีเมลรายการปฏิทินและที่ติดต่อหรือสำหรับการซ้ำในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="d5521-203">You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="d5521-204">FastTrack Center ไม่ครอบคลุมการปรับใช้ค่าธรรมเนียมสิทธิ์การใช้งานหรือความช่วยเหลือที่เกี่ยวข้องกับการเตรียมไดเรกทอรี (รวมถึงการซิงโครไนส์ของไดเรกทอรี Domino ไปใช้งานอยู่), โปรแกรม add-on ของซอฟต์แวร์ที่มีอยู่ร่วมกันสำหรับบันทึกย่อแอพลิเคชัน การโยกย้ายแบบบริการตนเองหรือการย้ายเก็บถาวร</span><span class="sxs-lookup"><span data-stu-id="d5521-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

