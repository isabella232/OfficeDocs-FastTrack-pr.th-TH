---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยคุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมต้นทางของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ
ms.openlocfilehash: b02c7c863cdc689fab4a6545ac1acc84f6b03fc2
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416618"
---
# <a name="data-migration"></a><span data-ttu-id="56959-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-104">Data Migration</span></span>

<span data-ttu-id="56959-105">FastTrack สามารถช่วยคุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมต้นทางของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="56959-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="56959-106">ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="56959-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="56959-107">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 150-499** รายการ : FastTrack จะให้แนวทางการโยกย้ายเท่านั้น คุณมีหน้าที่รับผิดชอบในการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="56959-108">เราแนะแนวคุณผ่านเอกสารประกอบที่ช่วยให้คุณวางแผนและใช้เครื่องมือฟรีเพื่อโยกย้ายด้วยตนเอง</span><span class="sxs-lookup"><span data-stu-id="56959-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="56959-109">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 500 สิทธิ์** หรือมากกว่า : FastTrack มอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="56959-110">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและผู้เช่า Office 365 ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="56959-111">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-111">You create and schedule your migration events.</span></span> <span data-ttu-id="56959-112">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="56959-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="56959-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนวันที่ 1/9/2017 คุณต้องมีสิทธิ์การใช้งานเพียง 150 สิทธิ์จึงจะเข้าเกณฑ์ในบริการการโยกย้ายข้อมูลได้</span><span class="sxs-lookup"><span data-stu-id="56959-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="56959-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span><span class="sxs-lookup"><span data-stu-id="56959-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="56959-115">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="56959-115">Considerations</span></span>

  - <span data-ttu-id="56959-116">สภาพแวดล้อมต้นทางของคุณต้องตรงตามความต้องการเฉพาะเพื่อโยกย้ายข้อมูลไปยัง Office 365</span><span class="sxs-lookup"><span data-stu-id="56959-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="56959-117">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมต้นทางใน Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="56959-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="56959-118">เราต้องการการเข้าถึงและสิทธิ์ที่เหมาะสมต่อสภาพแวดล้อมต้นทางของคุณและผู้เช่า Office 365 เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="56959-119">บริการการโยกย้ายข้อมูลของเราไม่ได้ออกแบบมาและไม่มีไว้เพื่อใช้กับข้อมูลที่อยู่ภายใต้ข้อบังคับทางกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="56959-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="56959-120">เมื่อเราโยกย้ายข้อมูลของคุณ ข้อมูลนั้นอาจถูกถ่ายโอน จัดเก็บ และประมวลผลได้จากทุกที่ที่เราดูแลอยู่ (ยกเว้นในกรณีที่เป็นอย่างอื่นยกเว้นโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="56959-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="56959-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายจดหมายหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="56959-122">ปัญหาที่ไม่ได้คาดไว้ (เช่น ไม่สามารถอ่านได้ หรือรายการเสียหายในสภาพแวดล้อมต้นทาง) อาจป้องกันไม่ให้เราความสามารถในการโยกย้ายรายการข้อมูลของคุณบางส่วนได้</span><span class="sxs-lookup"><span data-stu-id="56959-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="56959-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่น การเปลี่ยนแปลงส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชัน (API)) ของบริษัทอื่นอาจส่งผลให้เกิดการเปลี่ยนแปลง ความล่าช้า หรือการระงับบริการการโยกย้ายข้อมูลของเรา</span><span class="sxs-lookup"><span data-stu-id="56959-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="56959-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-124">Migration service availability</span></span>

  - <span data-ttu-id="56959-125">**ลูกค้าเชิงพาณิชย์และลูกค้ารัฐบาลสหราชอาณาจักร:** เราให้บริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงทุกวัน (7) วันต่อสัปดาห์ (24 ชั่วโมง 7 วัน)</span><span class="sxs-lookup"><span data-stu-id="56959-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="56959-126">**For US Government/DOD customers:** เรามีบริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงต่อวัน 5 (5) วันธุรกิจต่อสัปดาห์ (24x5)</span><span class="sxs-lookup"><span data-stu-id="56959-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="56959-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="56959-127">Migration to Exchange Online</span></span>

<span data-ttu-id="56959-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เรามีแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="56959-129">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ Exchange Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="56959-130">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-130">You create and schedule your migration events.</span></span> <span data-ttu-id="56959-131">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="56959-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="56959-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้จดหมายจากกล่องจดหมายต้นทางที่เหมาะสมและกล่องจดหมายต้นทางที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="56959-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="56959-133">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="56959-133">Considerations</span></span>

  - <span data-ttu-id="56959-134">ก่อนการโยกย้าย คุณต้องออนบอร์ดหลัก FastTrack ให้เสร็จสมบูรณ์เพื่อ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="56959-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="56959-135">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="56959-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="56959-136">ดูรายละเอียด [ได้จากผลิตภัณฑ์](products-and-capabilities.md) และความสามารถ</span><span class="sxs-lookup"><span data-stu-id="56959-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="56959-137">FastTrack จะโยกย้ายไปยังกล่องจดหมาย Office 365 ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="56959-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="56959-138">คุณต้องเป็นไปตามข้อต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ในองค์กร</span><span class="sxs-lookup"><span data-stu-id="56959-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="56959-139">ดูรายละเอียด [ในเบื้องต้นเกี่ยวกับ](https://go.microsoft.com/fwlink/?LinkId=787528) การปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="56959-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="56959-140">สภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมต้องอยู่บน Service Pack (SP) ล่าสุด และระดับการอัปเดตสะสม (RU)/CUMULATIVE Update (CU) สําหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="56959-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="56959-141">รายชื่อการแจกจ่าย (*วัตถุ MailEnabledGroup)* และที่ติดต่อภายนอก (*วัตถุ MailEnabledContact)* ที่มีอยู่ใน Active Directory ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="56959-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="56959-142">อย่างไรก็ตาม คุณสามารถซิงโครไนซ์ได้โดยใช้ Azure Active Directory (Azure AD) Connect</span><span class="sxs-lookup"><span data-stu-id="56959-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="56959-143">สภาพแวดล้อมแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-143">Source environments</span></span>

<span data-ttu-id="56959-144">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="56959-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="56959-145">ฟอเรสต์ Active Directory เดียวหรือหลายฟอเรสต์ที่มีองค์กร Exchange เดียวหรือหลายองค์กร (ระบบจดหมาย Exchange แต่ละระบบต้องเป็น Exchange 2010 หรือใหม่กว่า)</span><span class="sxs-lookup"><span data-stu-id="56959-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="56959-146">สภาพแวดล้อมอีเมลแบบ IMAP แบบเดี่ยว</span><span class="sxs-lookup"><span data-stu-id="56959-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="56959-147">สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="56959-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="56959-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="56959-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="56959-149"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="56959-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="56959-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="56959-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="56959-151"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="56959-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="56959-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="56959-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="56959-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="56959-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="56959-154">
<strong>หมายเหตุ:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span><span class="sxs-lookup"><span data-stu-id="56959-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="56959-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="56959-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="56959-156">อีเมล</span><span class="sxs-lookup"><span data-stu-id="56959-156">Emails</span></span></li>
<li><span data-ttu-id="56959-157">กฎกล่องจดหมายฝั่งเซิร์ฟเวอร์</span><span class="sxs-lookup"><span data-stu-id="56959-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="56959-158">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="56959-158">Delegates</span></span></li>
<li><span data-ttu-id="56959-159">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="56959-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="56959-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="56959-160">Calendar</span></span> </li>
<li> <span data-ttu-id="56959-161">งาน</span><span class="sxs-lookup"><span data-stu-id="56959-161">Tasks</span></span> </li>
<li> <span data-ttu-id="56959-162">อีเมลที่จัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="56959-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="56959-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="56959-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="56959-164">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="56959-164">Signatures</span></span> </li>
<li> <span data-ttu-id="56959-165">การเก็บถาวรส่วนบุคคลถูกโยกย้ายไปพร้อมกับกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="56959-166">รายการที่กู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="56959-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="56959-167">Public folders</span></span> </li>
<li> <span data-ttu-id="56959-168">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="56959-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="56959-169">Journaling archive or any third-party archive solution</span><span class="sxs-lookup"><span data-stu-id="56959-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="56959-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-171">เก็บถาวรข้อมูลจากไฟล์ Personal Storage Table (PST)</span><span class="sxs-lookup"><span data-stu-id="56959-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="56959-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="56959-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="56959-174">กฎกล่องจดหมายที่ฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="56959-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="56959-175"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="56959-176">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณต้องตรงตามเงื่อนไขเบื้องต้นที่อธิบายไว้<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ในการโยกย้าย G Suite</a></span><span class="sxs-lookup"><span data-stu-id="56959-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="56959-177">แบบ Cutover หรือแบบระยะ</span><span class="sxs-lookup"><span data-stu-id="56959-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-178">อีเมล</span><span class="sxs-lookup"><span data-stu-id="56959-178">Emails</span></span> </li>
<li> <span data-ttu-id="56959-179">ที่ติดต่อในกล่องจดหมาย (ที่อยู่อีเมลสูงสุด 3 รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="56959-180">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="56959-180">Calendar</span></span> </li>
<li> <span data-ttu-id="56959-181">ป้ายชื่อ</span><span class="sxs-lookup"><span data-stu-id="56959-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-182">กฎ</span><span class="sxs-lookup"><span data-stu-id="56959-182">Rules</span></span> </li>
<li> <span data-ttu-id="56959-183">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="56959-183">Delegates</span></span> </li>
<li> <span data-ttu-id="56959-184">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="56959-184">Signatures</span></span> </li>
<li> <span data-ttu-id="56959-185">งาน</span><span class="sxs-lookup"><span data-stu-id="56959-185">Tasks</span></span> </li>
<li> <span data-ttu-id="56959-186">อีเมลหรือสิ่งที่แนบมาใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="56959-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="56959-187">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-188">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันการเก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="56959-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="56959-189">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="56959-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="56959-190">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="56959-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="56959-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="56959-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="56959-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="56959-193">กล่องจดหมายทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="56959-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="56959-194">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="56959-195">การตั้งค่าวันหยุดพักผ่อนและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="56959-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="56959-196">ปฏิทินที่แชร์ สิ่งที่แนบมาในระบบคลาวด์ ลิงก์ Google Hangout และสีเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="56959-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="56959-197">\*\*การสนทนาใน Hangout ที่บันทึกไว้เป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="56959-198"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="56959-199">การโยกย้ายโดยใช้เครื่องมือ IMAP4 ดั้งเดิม</span><span class="sxs-lookup"><span data-stu-id="56959-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="56959-200">อีเมล</span><span class="sxs-lookup"><span data-stu-id="56959-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="56959-201">กฎ</span><span class="sxs-lookup"><span data-stu-id="56959-201">Rules</span></span> </li>
<li> <span data-ttu-id="56959-202">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="56959-202">Delegates</span></span> </li>
<li> <span data-ttu-id="56959-203">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="56959-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="56959-204">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-204">External contacts</span></span> </li>
<li> <span data-ttu-id="56959-205">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="56959-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="56959-206">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-207">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="56959-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="56959-208">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="56959-208">Calendar</span></span> </li>
<li> <span data-ttu-id="56959-209">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="56959-209">Signatures</span></span> </li>
<li> <span data-ttu-id="56959-210">งาน</span><span class="sxs-lookup"><span data-stu-id="56959-210">Tasks</span></span> </li>
<li> <span data-ttu-id="56959-211">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="56959-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="56959-212">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-212">Archive data</span></span> </li>
<li> <span data-ttu-id="56959-213">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="56959-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="56959-214">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="56959-215">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="56959-216">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="56959-216">FastTrack responsibilities</span></span>

<span data-ttu-id="56959-217">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="56959-218">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="56959-219">ผู้เชี่ยวชาญด้าน FastTrack ของเรายังปฏิบัติกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="56959-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="56959-220">ให้แนวทางเพื่อช่วยให้คุณเปิดใช้งานการต่อสายจดหมาย SMTP ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="56959-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="56959-221">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-221">Your responsibilities</span></span>

<span data-ttu-id="56959-222">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="56959-223">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="56959-224">คุณยังสามารถปฏิบัติกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="56959-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="56959-225">การออนบอร์ดหลัก FastTrack ให้เสร็จสมบูรณ์ใน Exchange Online</span><span class="sxs-lookup"><span data-stu-id="56959-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="56959-226">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="56959-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="56959-227">ดูรายละเอียด [ได้จากผลิตภัณฑ์](products-and-capabilities.md) และความสามารถ</span><span class="sxs-lookup"><span data-stu-id="56959-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="56959-228">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางของ Office 365</span><span class="sxs-lookup"><span data-stu-id="56959-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="56959-229">ดูรายละเอียด [ได้จากสถานที่ทํางาน](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) ยุคใหม่</span><span class="sxs-lookup"><span data-stu-id="56959-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="56959-230">ตรงตามความต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ในองค์กร</span><span class="sxs-lookup"><span data-stu-id="56959-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="56959-231">ดูรายละเอียด [ในเบื้องต้นเกี่ยวกับ](https://go.microsoft.com/fwlink/?LinkId=787528) การปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="56959-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="56959-232">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมอยู่บน Service Pack (SP) ล่าสุด และระดับ Rollup (RU)/cumulative update (CU) ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="56959-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="56959-233">กําหนดค่าและตรวจสอบความถูกต้องของการกําหนดเส้นทางจดหมาย SMTP ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="56959-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="56959-234">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นทางของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="56959-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="56959-235">ขึ้นอยู่กับแพลตฟอร์มต้นทาง คุณอาจต้องจํากัดข้อมูลต้นฉบับของคุณไปที่ 85 เปอร์เซ็นต์ของโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="56959-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="56959-236">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="56959-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="56959-237">ซึ่งรวมถึงแต่ไม่จํากัดเฉพาะสมุดรายชื่อข้อมูลในไฟล์ PST ภายในเครื่อง กฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="56959-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="56959-238">ช่วยผู้ใช้ของคุณเกี่ยวกับการแก้ไขปัญหาการโยกย้ายด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="56959-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="56959-239">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="56959-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="56959-240">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เรามีแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="56959-241">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ SharePoint Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="56959-242">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-242">You create and schedule your migration events.</span></span> <span data-ttu-id="56959-243">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="56959-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="56959-244">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="56959-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="56959-245">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="56959-245">Considerations</span></span>

  - <span data-ttu-id="56959-246">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตาของ SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="56959-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="56959-247">อ้างอิงไปยัง [<span class="underline">SharePoint Online และ OneDrive for Business: ขอบเขตและขีดจํากัด</span>](https://go.microsoft.com/fwlink/?LinkId=698855) ของซอฟต์แวร์เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="56959-248">เราขอแนะนนะให้คุณจํากัดจํานวนรวมของการโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="56959-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="56959-249">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="56959-249">Source environment details</span></span>

<span data-ttu-id="56959-250">บริการการโยกย้ายข้อมูลของเราโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="56959-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="56959-251">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="56959-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="56959-252">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="56959-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="56959-253">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="56959-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="56959-254">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="56959-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="56959-255">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="56959-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="56959-256"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="56959-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="56959-257"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="56959-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="56959-258"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="56959-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="56959-259"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="56959-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="56959-260"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="56959-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="56959-261">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-262">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="56959-262">Documents</span></span> </li>
<li> <span data-ttu-id="56959-263">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-264">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="56959-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="56959-265">สิทธิ์ของไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="56959-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="56959-266">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-267">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-268">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-268">Created date</span></span> </li>
<li> <span data-ttu-id="56959-269">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-269">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-270">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-270">Created by</span></span> </li>
<li> <span data-ttu-id="56959-271">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="56959-272">\*การกําหนดค่าการซิงโครไนซ์ไดเรกทอรีที่ต้องใช้</span><span class="sxs-lookup"><span data-stu-id="56959-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="56959-273">เฉพาะสิทธิ์แบบ NTFS ที่ถูกแสดงใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="56959-274">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์ที่ใช้ไฟล์ร่วมกันจะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="56959-275">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-276">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="56959-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="56959-277">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-278">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="56959-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="56959-279">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียว และถูกซ่อนไว้)</span><span class="sxs-lookup"><span data-stu-id="56959-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="56959-280">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="56959-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="56959-281">สิทธิ์ปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาอยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="56959-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="56959-282">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="56959-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="56959-283">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="56959-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="56959-284">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-285">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="56959-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="56959-286">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="56959-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="56959-287">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="56959-288"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="56959-289">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-290">Google Docs, แผ่นงาน และสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน) รวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB</span><span class="sxs-lookup"><span data-stu-id="56959-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="56959-291">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-292">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-293">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-294">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-295">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-296">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-296">Created date</span></span> </li>
<li> <span data-ttu-id="56959-297">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-297">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-298">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-298">Created by</span></span> </li>
<li> <span data-ttu-id="56959-299">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="56959-300">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="56959-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="56959-301">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-302">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="56959-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="56959-303">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="56959-304">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-305">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-306">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="56959-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="56959-307">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="56959-308">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-309">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="56959-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="56959-310">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-311">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-312">Google Photos, Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="56959-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="56959-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="56959-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="56959-314">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="56959-315">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="56959-316">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="56959-317">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="56959-318">สิทธิ์ความเป็นสมาชิกของไดรฟ์<strong>ที่แชร์</strong>(หมายเหตุ: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="56959-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="56959-319">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="56959-320">ไฟล์ที่ถูกระบุว่าถูกห้ามหรือไม่สามารถคัดลอกได้</span><span class="sxs-lookup"><span data-stu-id="56959-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="56959-321">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="56959-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="56959-323">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-324">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="56959-324">Documents</span></span> </li>
<li> <span data-ttu-id="56959-325">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-326">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-327">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-328">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-329">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-330">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-330">Created date</span></span> </li>
<li> <span data-ttu-id="56959-331">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-331">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-332">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-332">Created by</span></span> </li>
<li> <span data-ttu-id="56959-333">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="56959-334">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="56959-335">บันทึกย่อแบบกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="56959-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-336">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="56959-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="56959-337">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="56959-338">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-339">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-340">แท็กกล่องและเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="56959-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="56959-341">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="56959-342">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-343">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="56959-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="56959-344">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-345">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-346">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="56959-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="56959-347">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="56959-348">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="56959-349">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="56959-350">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="56959-351"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="56959-352">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-353">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="56959-353">Documents</span></span> </li>
<li> <span data-ttu-id="56959-354">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-355">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-356">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-357">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-358">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-359">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-359">Created date</span></span> </li>
<li> <span data-ttu-id="56959-360">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-360">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-361">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-361">Created by</span></span> </li>
<li> <span data-ttu-id="56959-362">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="56959-363">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="56959-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="56959-364">เนื้อหาที่แชร์ซึ่งบัญชีผู้ใช้ Dropbox เป็นเจ้าของที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-365">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="56959-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="56959-366">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="56959-367">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-368">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-369">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="56959-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="56959-370">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="56959-371">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-372">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="56959-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="56959-373">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-374">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="56959-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="56959-375">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="56959-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="56959-376">กระดาษ Dropbox, ตู้แสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="56959-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="56959-377">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="56959-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="56959-378">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="56959-379">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="56959-380">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกใหม่หลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="56959-381">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="56959-382">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="56959-382">FastTrack responsibilities</span></span>

<span data-ttu-id="56959-383">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="56959-384">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลในกระบวนการ [และความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="56959-385">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-385">Your responsibilities</span></span>

<span data-ttu-id="56959-386">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="56959-387">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลในกระบวนการ [และความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="56959-388">คุณยังจะปฏิบัติกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="56959-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="56959-389">เตรียมใช้งานไซต์ทีม SharePoint ทั้งหมดเพื่อตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="56959-390">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="56959-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="56959-391">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เรามีแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="56959-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="56959-392">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ OneDrive for Business ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="56959-393">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-393">You create and schedule your migration events.</span></span> <span data-ttu-id="56959-394">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="56959-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="56959-395">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="56959-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="56959-396">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="56959-396">Considerations</span></span>

  - <span data-ttu-id="56959-397">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตาของ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="56959-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="56959-398">โปรดดู [<span class="underline">SharePoint Online และ OneDrive for Business: ขอบเขตและขีดจํากัดของ</span>](https://go.microsoft.com/fwlink/?LinkId=698855) ซอฟต์แวร์เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="56959-399">เราขอแนะนนะให้คุณจํากัดปริมาณข้อมูลโดยรวมที่คุณโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="56959-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="56959-400">FastTrack จะโยกย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="56959-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="56959-401">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="56959-401">Source environment details</span></span>

<span data-ttu-id="56959-402">บริการการโยกย้ายข้อมูลของเราโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="56959-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="56959-403">การแชร์ไฟล์ (การแชร์ไฟล์ SMB บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="56959-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="56959-404">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="56959-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="56959-405">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="56959-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="56959-406">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="56959-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="56959-407">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="56959-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="56959-408"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="56959-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="56959-409"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="56959-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="56959-410"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="56959-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="56959-411"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="56959-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="56959-412"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="56959-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="56959-413">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-414">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="56959-414">Documents</span></span> </li>
<li> <span data-ttu-id="56959-415">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-416">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="56959-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="56959-417">สิทธิ์ของไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="56959-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="56959-418">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-419">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-420">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-420">Created date</span></span> </li>
<li> <span data-ttu-id="56959-421">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-421">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-422">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-422">Created by</span></span> </li>
<li> <span data-ttu-id="56959-423">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="56959-424">\*การกําหนดค่าการซิงโครไนซ์ไดเรกทอรีที่ต้องใช้</span><span class="sxs-lookup"><span data-stu-id="56959-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="56959-425">เฉพาะสิทธิ์แบบ NTFS ที่ถูกแสดงใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="56959-426">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์ที่ใช้ไฟล์ร่วมกันจะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="56959-427">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="56959-428">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="56959-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="56959-429">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-430">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="56959-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="56959-431">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียว และถูกซ่อนไว้)</span><span class="sxs-lookup"><span data-stu-id="56959-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="56959-432">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="56959-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="56959-433">สิทธิ์ปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาอยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="56959-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="56959-434">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="56959-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="56959-435">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="56959-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="56959-436">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-437">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="56959-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="56959-438">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="56959-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="56959-439">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="56959-440"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="56959-441">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-442">Google Docs, Sheets และสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="56959-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="56959-443">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-444">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-445">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-446">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-447">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-448">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-448">Created date</span></span> </li>
<li> <span data-ttu-id="56959-449">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-449">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-450">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-450">Created by</span></span> </li>
<li> <span data-ttu-id="56959-451">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="56959-452">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="56959-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="56959-453">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-454">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="56959-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="56959-455">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="56959-456">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-457">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-458">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="56959-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="56959-459">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="56959-460">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-461">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="56959-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="56959-462">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-463">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-464">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="56959-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="56959-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="56959-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="56959-466">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="56959-467">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="56959-468">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="56959-469">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="56959-470">สิทธิ์สมาชิกไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="56959-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="56959-471">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="56959-472">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="56959-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="56959-474">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-475">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="56959-475">Documents</span></span> </li>
<li> <span data-ttu-id="56959-476">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-477">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-478">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-479">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-480">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-481">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-481">Created date</span></span> </li>
<li> <span data-ttu-id="56959-482">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-482">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-483">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-483">Created by</span></span> </li>
<li> <span data-ttu-id="56959-484">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="56959-485">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-486">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="56959-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="56959-487">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="56959-488">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-489">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-490">แท็กกล่องและเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="56959-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="56959-491">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="56959-492">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-493">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="56959-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="56959-494">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-495">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="56959-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="56959-496">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="56959-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="56959-497">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="56959-498">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="56959-499">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="56959-500">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="56959-501"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="56959-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="56959-502">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="56959-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="56959-503">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="56959-503">Documents</span></span> </li>
<li> <span data-ttu-id="56959-504">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="56959-505">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-506">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="56959-507">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="56959-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="56959-508">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="56959-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="56959-509">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="56959-509">Created date</span></span> </li>
<li> <span data-ttu-id="56959-510">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="56959-510">Modified date</span></span> </li>
<li> <span data-ttu-id="56959-511">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="56959-511">Created by</span></span> </li>
<li> <span data-ttu-id="56959-512">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="56959-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="56959-513">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="56959-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="56959-514">เนื้อหาที่แชร์ซึ่งบัญชีผู้ใช้ Dropbox เป็นเจ้าของที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="56959-515">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="56959-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="56959-516">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="56959-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="56959-517">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="56959-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-518">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="56959-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="56959-519">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="56959-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="56959-520">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="56959-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="56959-521">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="56959-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="56959-522">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="56959-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="56959-523">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="56959-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="56959-524">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="56959-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="56959-525">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="56959-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="56959-526">กระดาษ Dropbox, ตู้แสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="56959-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="56959-527">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="56959-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="56959-528">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="56959-529">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="56959-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="56959-530">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="56959-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="56959-531">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="56959-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="56959-532">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="56959-532">FastTrack responsibilities</span></span>

<span data-ttu-id="56959-533">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="56959-534">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="56959-535">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-535">Your responsibilities</span></span>

<span data-ttu-id="56959-536">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="56959-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="56959-537">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="56959-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="56959-538">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้เพื่อโยกย้าย OneDrive for Business โดยเฉพาะ:</span><span class="sxs-lookup"><span data-stu-id="56959-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="56959-539">เตรียมใช้งานไซต์ OneDrive for Business ทั้งหมดที่จะตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="56959-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
