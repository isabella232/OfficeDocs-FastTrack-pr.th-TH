---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 3/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยคุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมต้นทางของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ
ms.openlocfilehash: f518e8dbda9200318022bad2cc12d1ba68263df8
ms.sourcegitcommit: 31d2c36fd00f47330dc2c90a646f8ce8a9687e1d
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 03/24/2021
ms.locfileid: "51188033"
---
# <a name="data-migration"></a><span data-ttu-id="991f5-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-104">Data Migration</span></span>

<span data-ttu-id="991f5-105">FastTrack สามารถช่วยคุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมต้นทางของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="991f5-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="991f5-106">ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="991f5-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="991f5-107">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 150-499** รายการ : FastTrack จะให้แนวทางการโยกย้ายเท่านั้น คุณมีหน้าที่รับผิดชอบในการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="991f5-108">เราแนะแนวคุณผ่านเอกสารประกอบที่ช่วยให้คุณวางแผนและใช้เครื่องมือฟรีเพื่อโยกย้ายด้วยตนเอง</span><span class="sxs-lookup"><span data-stu-id="991f5-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="991f5-109">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 500 สิทธิ์หรือมากกว่า**: FastTrack มอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="991f5-110">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและผู้เช่า Office 365 ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="991f5-111">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-111">You create and schedule your migration events.</span></span> <span data-ttu-id="991f5-112">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="991f5-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="991f5-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนวันที่ 1/9/2017 คุณต้องมีสิทธิ์การใช้งานเพียง 150 สิทธิ์จึงจะเข้าเกณฑ์ในบริการการโยกย้ายข้อมูลได้</span><span class="sxs-lookup"><span data-stu-id="991f5-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="991f5-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span><span class="sxs-lookup"><span data-stu-id="991f5-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="991f5-115">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="991f5-115">Considerations</span></span>

  - <span data-ttu-id="991f5-116">สภาพแวดล้อมต้นทางของคุณต้องตรงตามความต้องการเฉพาะเพื่อโยกย้ายข้อมูลไปยัง Office 365</span><span class="sxs-lookup"><span data-stu-id="991f5-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="991f5-117">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมต้นทางใน Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="991f5-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="991f5-118">เราต้องการการเข้าถึงและสิทธิ์ที่เหมาะสมต่อสภาพแวดล้อมต้นทางของคุณและผู้เช่า Office 365 เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="991f5-119">บริการการโยกย้ายข้อมูลของเราไม่ได้ออกแบบมาหรือมีไว้เพื่อข้อมูลภายใต้ข้อกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="991f5-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="991f5-120">เมื่อเราโยกย้ายข้อมูลของคุณ ข้อมูลนั้นอาจถูกถ่ายโอน จัดเก็บ และประมวลผลได้จากทุกที่ที่เราดูแลอยู่ (ยกเว้นในกรณีที่เป็นอย่างอื่นยกเว้นโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="991f5-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="991f5-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายจดหมายหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="991f5-122">ปัญหาที่ไม่ได้คาดไว้ (เช่น ไม่สามารถอ่านได้ หรือรายการเสียหายในสภาพแวดล้อมต้นทาง) อาจป้องกันไม่ให้เราความสามารถในการโยกย้ายรายการข้อมูลของคุณบางส่วนได้</span><span class="sxs-lookup"><span data-stu-id="991f5-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="991f5-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่น การเปลี่ยนแปลงส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชัน (API)) ของบริษัทอื่นอาจส่งผลให้เกิดการเปลี่ยนแปลง ความล่าช้า หรือการระงับบริการการโยกย้ายข้อมูลของเรา</span><span class="sxs-lookup"><span data-stu-id="991f5-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="991f5-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-124">Migration service availability</span></span>

  - <span data-ttu-id="991f5-125">**ลูกค้าเชิงพาณิชย์และลูกค้ารัฐบาลสหราชอาณาจักร:** เราให้บริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงทุกวัน (7) วันต่อสัปดาห์ (24 ชั่วโมง 7 วัน)</span><span class="sxs-lookup"><span data-stu-id="991f5-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="991f5-126">**For US Government/DOD customers:** เราให้บริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงต่อวัน 5 (5) วันธุรกิจต่อสัปดาห์ (24x5)</span><span class="sxs-lookup"><span data-stu-id="991f5-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="991f5-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="991f5-127">Migration to Exchange Online</span></span>

<span data-ttu-id="991f5-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เรามีแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="991f5-129">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ Exchange Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="991f5-130">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-130">You create and schedule your migration events.</span></span> <span data-ttu-id="991f5-131">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="991f5-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="991f5-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้จดหมายจากกล่องจดหมายต้นทางที่เหมาะสมและกล่องจดหมายต้นทางที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="991f5-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="991f5-133">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="991f5-133">Considerations</span></span>

  - <span data-ttu-id="991f5-134">ก่อนการโยกย้าย คุณต้องออนบอร์ดหลัก FastTrack ให้เสร็จสมบูรณ์เพื่อ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="991f5-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="991f5-135">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="991f5-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="991f5-136">ดูรายละเอียด [ได้จากผลิตภัณฑ์](products-and-capabilities.md) และความสามารถ</span><span class="sxs-lookup"><span data-stu-id="991f5-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="991f5-137">FastTrack จะโยกย้ายไปยังกล่องจดหมาย Office 365 ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="991f5-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="991f5-138">คุณต้องตรงตามความต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="991f5-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="991f5-139">ดูรายละเอียด [ในเบื้องต้นเกี่ยวกับ](https://go.microsoft.com/fwlink/?LinkId=787528) การปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="991f5-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="991f5-140">สภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมต้องอยู่บน Service Pack (SP) ล่าสุด และระดับการอัปเดตสะสม (RU)/CUMULATIVE Update (CU) สําหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="991f5-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="991f5-141">รายชื่อการแจกจ่าย (*วัตถุ MailEnabledGroup)* และที่ติดต่อภายนอก (วัตถุ *MailEnabledContact)* ที่มีอยู่ใน Active Directory ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="991f5-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="991f5-142">อย่างไรก็ตาม คุณสามารถซิงโครไนซ์ได้โดยใช้ Azure Active Directory (Azure AD) Connect</span><span class="sxs-lookup"><span data-stu-id="991f5-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="991f5-143">สภาพแวดล้อมแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-143">Source environments</span></span>

<span data-ttu-id="991f5-144">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="991f5-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="991f5-145">ฟอเรสต์ Active Directory เดียวหรือหลายฟอเรสต์ที่มี Exchange องค์กรเดียวหรือหลายองค์กร (ระบบจดหมาย Exchange แต่ละระบบต้องเป็น Exchange 2010 หรือใหม่กว่า)</span><span class="sxs-lookup"><span data-stu-id="991f5-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="991f5-146">สภาพแวดล้อมอีเมลแบบ IMAP แบบเดี่ยว</span><span class="sxs-lookup"><span data-stu-id="991f5-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="991f5-147">สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="991f5-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="991f5-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="991f5-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="991f5-149"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="991f5-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="991f5-151"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="991f5-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="991f5-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="991f5-154">
<strong>หมายเหตุ:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span><span class="sxs-lookup"><span data-stu-id="991f5-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="991f5-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="991f5-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="991f5-156">อีเมล</span><span class="sxs-lookup"><span data-stu-id="991f5-156">Emails</span></span></li>
<li><span data-ttu-id="991f5-157">กฎกล่องจดหมายฝั่งเซิร์ฟเวอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="991f5-158">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="991f5-158">Delegates</span></span></li>
<li><span data-ttu-id="991f5-159">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="991f5-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="991f5-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="991f5-160">Calendar</span></span> </li>
<li> <span data-ttu-id="991f5-161">งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-161">Tasks</span></span> </li>
<li> <span data-ttu-id="991f5-162">อีเมลที่จัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="991f5-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="991f5-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="991f5-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="991f5-164">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="991f5-164">Signatures</span></span> </li>
<li> <span data-ttu-id="991f5-165">การเก็บถาวรส่วนบุคคลถูกโยกย้ายไปพร้อมกับกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="991f5-166">รายการที่กู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="991f5-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="991f5-167">Public folders</span></span> </li>
<li> <span data-ttu-id="991f5-168">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="991f5-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="991f5-169">Journaling archive or any third-party archive solution</span><span class="sxs-lookup"><span data-stu-id="991f5-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="991f5-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-171">เก็บถาวรข้อมูลจากไฟล์ Personal Storage Table (PST)</span><span class="sxs-lookup"><span data-stu-id="991f5-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="991f5-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="991f5-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="991f5-174">กฎกล่องจดหมายที่ฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="991f5-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-175"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="991f5-176">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณต้องตรงตามเงื่อนไขเบื้องต้นที่อธิบายไว้<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ในการโยกย้าย G Suite</a></span><span class="sxs-lookup"><span data-stu-id="991f5-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="991f5-177">แบบ Cutover หรือแบบระยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-178">อีเมล</span><span class="sxs-lookup"><span data-stu-id="991f5-178">Emails</span></span> </li>
<li> <span data-ttu-id="991f5-179">ที่ติดต่อในกล่องจดหมาย (ที่อยู่อีเมลสูงสุด 3 รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="991f5-180">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="991f5-180">Calendar</span></span> </li>
<li> <span data-ttu-id="991f5-181">ป้ายชื่อ</span><span class="sxs-lookup"><span data-stu-id="991f5-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-182">กฎ</span><span class="sxs-lookup"><span data-stu-id="991f5-182">Rules</span></span> </li>
<li> <span data-ttu-id="991f5-183">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="991f5-183">Delegates</span></span> </li>
<li> <span data-ttu-id="991f5-184">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="991f5-184">Signatures</span></span> </li>
<li> <span data-ttu-id="991f5-185">งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-185">Tasks</span></span> </li>
<li> <span data-ttu-id="991f5-186">อีเมลหรือสิ่งที่แนบมาใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="991f5-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="991f5-187">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-188">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันการเก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="991f5-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="991f5-189">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="991f5-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="991f5-190">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="991f5-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="991f5-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="991f5-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="991f5-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="991f5-193">กล่องจดหมายทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="991f5-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="991f5-194">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="991f5-195">การตั้งค่าวันหยุดพักผ่อนและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="991f5-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="991f5-196">ปฏิทินที่แชร์ สิ่งที่แนบมาในระบบคลาวด์ ลิงก์ Google Hangout และสีเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="991f5-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="991f5-197">\*\*การสนทนาใน Hangout ที่บันทึกไว้เป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="991f5-198"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="991f5-199">การโยกย้ายโดยใช้เครื่องมือ IMAP4 ดั้งเดิม</span><span class="sxs-lookup"><span data-stu-id="991f5-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="991f5-200">อีเมล</span><span class="sxs-lookup"><span data-stu-id="991f5-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="991f5-201">กฎ</span><span class="sxs-lookup"><span data-stu-id="991f5-201">Rules</span></span> </li>
<li> <span data-ttu-id="991f5-202">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="991f5-202">Delegates</span></span> </li>
<li> <span data-ttu-id="991f5-203">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="991f5-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="991f5-204">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-204">External contacts</span></span> </li>
<li> <span data-ttu-id="991f5-205">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="991f5-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="991f5-206">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-207">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="991f5-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="991f5-208">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="991f5-208">Calendar</span></span> </li>
<li> <span data-ttu-id="991f5-209">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="991f5-209">Signatures</span></span> </li>
<li> <span data-ttu-id="991f5-210">งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-210">Tasks</span></span> </li>
<li> <span data-ttu-id="991f5-211">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="991f5-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="991f5-212">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-212">Archive data</span></span> </li>
<li> <span data-ttu-id="991f5-213">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="991f5-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="991f5-214">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="991f5-215">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="991f5-216">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="991f5-216">FastTrack responsibilities</span></span>

<span data-ttu-id="991f5-217">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-218">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="991f5-219">ผู้เชี่ยวชาญด้าน FastTrack ของเรายังปฏิบัติกิจกรรมต่อไปนี้เฉพาะการโยกย้าย Exchange โดยเฉพาะ:</span><span class="sxs-lookup"><span data-stu-id="991f5-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="991f5-220">ให้แนวทางเพื่อช่วยให้คุณเปิดใช้งานการต่อสายจดหมาย SMTP ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="991f5-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="991f5-221">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-221">Your responsibilities</span></span>

<span data-ttu-id="991f5-222">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-223">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="991f5-224">คุณยังสามารถปฏิบัติกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="991f5-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="991f5-225">การออนบอร์ดหลัก FastTrack ให้เสร็จสมบูรณ์ใน Exchange Online</span><span class="sxs-lookup"><span data-stu-id="991f5-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="991f5-226">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="991f5-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="991f5-227">ดูรายละเอียด [ได้จากผลิตภัณฑ์](products-and-capabilities.md) และความสามารถ</span><span class="sxs-lookup"><span data-stu-id="991f5-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="991f5-228">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางของ Office 365</span><span class="sxs-lookup"><span data-stu-id="991f5-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="991f5-229">ดูรายละเอียด [ได้จากสถานที่ทํางาน](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) ยุคใหม่</span><span class="sxs-lookup"><span data-stu-id="991f5-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="991f5-230">ตรงตามความต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ในองค์กร</span><span class="sxs-lookup"><span data-stu-id="991f5-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="991f5-231">ดูรายละเอียด [ในเบื้องต้นเกี่ยวกับ](https://go.microsoft.com/fwlink/?LinkId=787528) การปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="991f5-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="991f5-232">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมอยู่บน Service Pack (SP) ล่าสุด และระดับ Rollup (RU)/cumulative update (CU) ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="991f5-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="991f5-233">กําหนดค่าและตรวจสอบความถูกต้องของการกําหนดเส้นทางจดหมาย SMTP ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="991f5-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="991f5-234">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นทางของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="991f5-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="991f5-235">ขึ้นอยู่กับแพลตฟอร์มต้นทาง คุณอาจต้องจํากัดข้อมูลต้นฉบับของคุณไปที่ 85 เปอร์เซ็นต์ของโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="991f5-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="991f5-236">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ได้ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="991f5-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="991f5-237">ซึ่งรวมถึงแต่ไม่จํากัดเฉพาะสมุดรายชื่อข้อมูลในไฟล์ PST ภายในเครื่อง กฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="991f5-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="991f5-238">ช่วยผู้ใช้ของคุณเกี่ยวกับการแก้ไขปัญหาการโยกย้ายด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="991f5-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="991f5-239">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="991f5-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="991f5-240">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เรามีแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="991f5-241">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ SharePoint Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="991f5-242">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-242">You create and schedule your migration events.</span></span> <span data-ttu-id="991f5-243">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="991f5-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="991f5-244">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="991f5-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="991f5-245">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="991f5-245">Considerations</span></span>

 - <span data-ttu-id="991f5-246">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตาของ SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="991f5-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="991f5-247">อ้างอิงไปยัง <a href="https://go.microsoft.com/fwlink/?LinkId=698855">ขีดจํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="991f5-248">เราขอแนะนนะให้คุณจํากัดจํานวนรวมของการโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="991f5-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="991f5-249">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="991f5-249">Source environment details</span></span>

<span data-ttu-id="991f5-250">บริการการโยกย้ายข้อมูลของเราโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="991f5-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="991f5-251">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="991f5-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="991f5-252">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="991f5-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="991f5-253">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="991f5-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="991f5-254">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="991f5-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="991f5-255">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="991f5-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="991f5-256"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="991f5-257"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="991f5-258"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="991f5-259"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="991f5-260"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="991f5-261">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-262">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-262">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-263">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-264">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="991f5-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-265">สิทธิ์ของไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="991f5-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-266">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-267">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-268">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-268">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-269">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-269">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-270">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-270">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-271">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="991f5-272">\*การกําหนดค่าการซิงโครไนซ์ไดเรกทอรีที่ต้องใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="991f5-273">เฉพาะสิทธิ์แบบ NTFS ที่ถูกแสดงใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="991f5-274">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์ที่ใช้ไฟล์ร่วมกันจะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="991f5-275">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-276">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="991f5-277">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-278">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="991f5-279">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียว และถูกซ่อนไว้)</span><span class="sxs-lookup"><span data-stu-id="991f5-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="991f5-280">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="991f5-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="991f5-281">สิทธิ์ปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาอยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="991f5-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="991f5-282">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="991f5-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="991f5-283">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="991f5-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="991f5-284">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-285">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="991f5-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="991f5-286">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="991f5-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="991f5-287">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-288"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="991f5-289">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-290">Google Docs, Sheets และสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน) รวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB</span><span class="sxs-lookup"><span data-stu-id="991f5-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="991f5-291">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-292">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-293">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-294">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-295">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-296">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-296">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-297">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-297">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-298">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-298">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-299">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-300">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="991f5-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="991f5-301">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-302">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-303">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="991f5-304">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-305">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-306">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-307">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-308">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-309">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-310">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-311">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-312">Google Photos, Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="991f5-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="991f5-313">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="991f5-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="991f5-314">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="991f5-315">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="991f5-316">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-317">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-318">สิทธิ์ความเป็นสมาชิกของไดรฟ์<strong>ที่แชร์</strong>(หมายเหตุ: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="991f5-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="991f5-319">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-320">ไฟล์ที่ถูกระบุว่าถูกห้ามหรือไม่สามารถคัดลอกได้</span><span class="sxs-lookup"><span data-stu-id="991f5-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="991f5-321">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="991f5-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="991f5-323">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-324">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-324">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-325">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-326">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-327">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-328">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-329">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-330">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-330">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-331">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-331">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-332">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-332">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-333">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-334">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="991f5-335">บันทึกย่อแบบกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="991f5-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-336">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-337">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="991f5-338">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-339">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-340">แท็กกล่องและเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-341">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-342">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-343">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-344">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-345">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-346">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="991f5-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="991f5-347">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="991f5-348">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-349">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-350">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-351"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="991f5-352">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-353">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-353">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-354">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-355">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-356">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-357">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-358">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-359">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-359">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-360">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-360">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-361">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-361">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-362">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-363">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="991f5-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="991f5-364">เนื้อหาที่แชร์ซึ่งบัญชีผู้ใช้ Dropbox เป็นเจ้าของที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-365">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-366">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="991f5-367">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-368">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-369">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-370">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-371">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-372">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-373">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-374">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="991f5-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="991f5-375">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="991f5-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="991f5-376">กระดาษ Dropbox, ตู้แสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="991f5-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="991f5-377">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="991f5-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="991f5-378">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="991f5-379">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-380">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกใหม่หลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="991f5-381">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="991f5-382">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="991f5-382">FastTrack responsibilities</span></span>

<span data-ttu-id="991f5-383">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-384">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลในกระบวนการ [และความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="991f5-385">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-385">Your responsibilities</span></span>

<span data-ttu-id="991f5-386">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-387">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลในกระบวนการ [และความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="991f5-388">คุณยังจะปฏิบัติกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="991f5-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="991f5-389">เตรียมใช้งานไซต์ทีม SharePoint ทั้งหมดเพื่อตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="991f5-390">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="991f5-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="991f5-391">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เรามีแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="991f5-392">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ OneDrive for Business ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="991f5-393">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-393">You create and schedule your migration events.</span></span> <span data-ttu-id="991f5-394">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="991f5-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="991f5-395">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="991f5-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="991f5-396">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="991f5-396">Considerations</span></span>

  - <span data-ttu-id="991f5-397">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตาของ SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="991f5-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="991f5-398">อ้างอิงไปยัง <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> ขีดจํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="991f5-399">เราขอแนะนนะให้คุณจํากัดปริมาณข้อมูลโดยรวมที่คุณโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="991f5-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="991f5-400">FastTrack จะโยกย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="991f5-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="991f5-401">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="991f5-401">Source environment details</span></span>

<span data-ttu-id="991f5-402">บริการการโยกย้ายข้อมูลของเราโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="991f5-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="991f5-403">การแชร์ไฟล์ (การแชร์ไฟล์ SMB บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="991f5-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="991f5-404">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="991f5-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="991f5-405">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="991f5-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="991f5-406">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="991f5-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="991f5-407">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="991f5-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="991f5-408"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="991f5-409"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="991f5-410"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="991f5-411"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="991f5-412"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="991f5-413">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-414">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-414">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-415">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-416">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="991f5-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-417">สิทธิ์ของไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="991f5-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-418">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-419">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-420">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-420">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-421">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-421">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-422">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-422">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-423">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="991f5-424">\*การกําหนดค่าการซิงโครไนซ์ไดเรกทอรีที่ต้องใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="991f5-425">เฉพาะสิทธิ์แบบ NTFS ที่ถูกแสดงใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="991f5-426">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์ที่ใช้ไฟล์ร่วมกันจะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="991f5-427">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="991f5-428">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="991f5-429">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-430">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="991f5-431">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียว และถูกซ่อนไว้)</span><span class="sxs-lookup"><span data-stu-id="991f5-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="991f5-432">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="991f5-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="991f5-433">สิทธิ์ปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาอยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="991f5-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="991f5-434">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="991f5-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="991f5-435">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="991f5-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="991f5-436">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-437">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="991f5-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="991f5-438">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="991f5-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="991f5-439">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-440"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="991f5-441">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-442">Google Docs, Sheets และสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="991f5-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="991f5-443">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-444">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-445">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-446">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-447">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-448">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-448">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-449">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-449">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-450">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-450">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-451">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-452">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="991f5-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="991f5-453">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-454">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-455">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="991f5-456">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-457">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-458">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-459">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-460">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-461">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-462">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-463">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-464">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="991f5-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="991f5-465">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="991f5-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="991f5-466">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="991f5-467">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="991f5-468">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-469">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-470">สิทธิ์สมาชิกไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="991f5-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="991f5-471">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-472">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="991f5-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="991f5-474">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-475">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-475">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-476">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-477">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-478">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-479">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-480">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-481">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-481">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-482">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-482">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-483">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-483">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-484">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-485">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-486">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-487">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="991f5-488">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-489">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-490">แท็กกล่องและเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-491">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-492">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-493">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-494">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-495">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-496">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="991f5-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="991f5-497">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="991f5-498">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-499">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-500">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-501"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="991f5-502">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-503">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-503">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-504">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-505">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-506">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="991f5-507">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-508">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-509">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-509">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-510">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-510">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-511">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-511">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-512">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-513">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="991f5-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="991f5-514">เนื้อหาที่แชร์ซึ่งบัญชีผู้ใช้ Dropbox เป็นเจ้าของที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="991f5-515">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-516">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="991f5-517">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-518">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-519">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-520">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-521">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-522">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-523">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-524">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="991f5-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="991f5-525">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="991f5-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="991f5-526">กระดาษ Dropbox, ตู้แสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="991f5-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="991f5-527">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="991f5-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="991f5-528">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="991f5-529">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-530">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-531">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="991f5-532">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="991f5-532">FastTrack responsibilities</span></span>

<span data-ttu-id="991f5-533">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-534">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="991f5-535">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-535">Your responsibilities</span></span>

<span data-ttu-id="991f5-536">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-537">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="991f5-538">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้เพื่อโยกย้าย OneDrive for Business โดยเฉพาะ:</span><span class="sxs-lookup"><span data-stu-id="991f5-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="991f5-539">เตรียมใช้งานไซต์ OneDrive for Business ทั้งหมดที่จะตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="991f5-540">การโยกย้ายไปยัง Microsoft Teams และกลุ่ม Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="991f5-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="991f5-541">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง Microsoft Teams และ Microsoft 365 Groups เราจะให้แนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="991f5-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="991f5-542">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้าย กําหนดค่าสภาพแวดล้อมต้นทางและ Teams และกลุ่ม Microsoft 365 ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="991f5-543">คุณสร้างและจัดตารางเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-543">You create and schedule your migration events.</span></span> <span data-ttu-id="991f5-544">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="991f5-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="991f5-545">เมื่อกิจกรรมการโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและทรัพยากรที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง Teams และ Microsoft 365 Groups</span><span class="sxs-lookup"><span data-stu-id="991f5-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="991f5-546">ทีมแชนเนลและกลุ่ม Microsoft 365 ต้องได้รับการจัดเตรียมไว้ล่วงหน้าโดยลูกค้าก่อนที่จะสามารถโยกย้ายข้อมูลไปยังปลายทางประเภทนี้ได้</span><span class="sxs-lookup"><span data-stu-id="991f5-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="991f5-547">Teams และ Microsoft 365 Groups ส่งผลกระทบต่อสิทธิ์ของคุณบนปลายทางของไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="991f5-548">Teams และ Microsoft 365 Groups ถูกสร้างขึ้นเพื่อให้การร่วมมือกัน</span><span class="sxs-lookup"><span data-stu-id="991f5-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="991f5-549">แชนเนล Teams หรือกลุ่ม Microsoft 365 จะระบุว่าใครมีสิทธิ์เข้าถึงไฟล์เหล่านั้นเมื่อโยกย้ายไปยังปลายทางเหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="991f5-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="991f5-550">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนเนล Teams ใดๆ หรือสิทธิ์กลุ่ม Microsoft 365 ระหว่างการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="991f5-551">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="991f5-551">Considerations</span></span>

- <span data-ttu-id="991f5-552">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตาของ SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="991f5-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="991f5-553">อ้างอิงไปยัง <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> ขีดจํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="991f5-554">เราขอแนะนนะให้คุณจํากัดจํานวนรวมของการโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="991f5-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="991f5-555">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="991f5-555">Source environment details</span></span>

<span data-ttu-id="991f5-556">บริการการโยกย้ายข้อมูลของเราโยกย้ายข้อมูลจากสภาพแวดล้อมต้นทางเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="991f5-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="991f5-557">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="991f5-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="991f5-558">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="991f5-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="991f5-559">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="991f5-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="991f5-560">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="991f5-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="991f5-561">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="991f5-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="991f5-562"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="991f5-563"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="991f5-564"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="991f5-565"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="991f5-566"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="991f5-567">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-568">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-568">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-569">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-570">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="991f5-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-571">สิทธิ์ของไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="991f5-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-572">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-573">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-574">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-574">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-575">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-575">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-576">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-576">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-577">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="991f5-578">\*การกําหนดค่าการซิงโครไนซ์ไดเรกทอรีที่ต้องใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="991f5-579">เฉพาะสิทธิ์แบบ NTFS ที่ถูกแสดงใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="991f5-580">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์ที่ใช้ไฟล์ร่วมกันจะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="991f5-581">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="991f5-582">สิทธิ์จะได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="991f5-583">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="991f5-584">เราไม่แนะให้โยกย้ายสิทธิ์ในการโยกย้ายไฟล์ไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-585">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="991f5-586">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-587">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="991f5-588">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียว และถูกซ่อนไว้)</span><span class="sxs-lookup"><span data-stu-id="991f5-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="991f5-589">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="991f5-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="991f5-590">สิทธิ์ปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาอยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="991f5-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="991f5-591">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="991f5-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="991f5-592">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="991f5-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="991f5-593">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-594">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="991f5-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="991f5-595">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="991f5-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="991f5-596">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-597"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="991f5-598">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-599">Google Docs, Sheets และสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="991f5-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="991f5-600">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-601">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="991f5-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-602">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="991f5-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-603">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-604">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-605">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-605">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-606">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-606">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-607">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-607">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-608">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-609">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="991f5-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="991f5-610">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="991f5-611">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="991f5-612">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="991f5-613">เราไม่แนะให้โยกย้ายสิทธิ์ในการโยกย้ายไฟล์ไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="991f5-614">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-615">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="991f5-616">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-617">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-618">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-619">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-620">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-621">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-622">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-623">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-624">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="991f5-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="991f5-625">Google Drawings</span><span class="sxs-lookup"><span data-stu-id="991f5-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="991f5-626">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="991f5-627">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="991f5-628">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-629">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-630">สิทธิ์สมาชิกไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="991f5-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="991f5-631">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-632">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="991f5-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="991f5-634">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-635">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-635">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-636">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-637">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="991f5-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-638">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="991f5-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-639">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-640">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-641">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-641">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-642">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-642">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-643">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-643">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-644">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-645">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="991f5-646">บันทึกย่อแบบกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="991f5-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="991f5-647">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="991f5-648">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="991f5-649">เราไม่แนะให้โยกย้ายสิทธิ์ในการโยกย้ายไฟล์ไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="991f5-650">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-651">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="991f5-652">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-653">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-654">แท็กกล่องและเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-655">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-656">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-657">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-658">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-659">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="991f5-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="991f5-660">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="991f5-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="991f5-661">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชี Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="991f5-662">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-663">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-664">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="991f5-665"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="991f5-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="991f5-666">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="991f5-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="991f5-667">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="991f5-667">Documents</span></span> </li>
<li> <span data-ttu-id="991f5-668">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="991f5-669">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="991f5-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-670">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="991f5-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="991f5-671">ไฟล์ที่มีขนาดไม่เกิน 15 GB</span><span class="sxs-lookup"><span data-stu-id="991f5-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="991f5-672">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="991f5-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="991f5-673">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="991f5-673">Created date</span></span> </li>
<li> <span data-ttu-id="991f5-674">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="991f5-674">Modified date</span></span> </li>
<li> <span data-ttu-id="991f5-675">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-675">Created by</span></span> </li>
<li> <span data-ttu-id="991f5-676">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="991f5-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="991f5-677">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="991f5-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="991f5-678">เนื้อหาที่แชร์ซึ่งบัญชีผู้ใช้ Dropbox เป็นเจ้าของที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="991f5-679">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="991f5-680">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="991f5-681">เราไม่แนะให้โยกย้ายสิทธิ์ในการโยกย้ายไฟล์ไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="991f5-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="991f5-682">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="991f5-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="991f5-683">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="991f5-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="991f5-684">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="991f5-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-685">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="991f5-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="991f5-686">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="991f5-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="991f5-687">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="991f5-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="991f5-688">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="991f5-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="991f5-689">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="991f5-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="991f5-690">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="991f5-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="991f5-691">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="991f5-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="991f5-692">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="991f5-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="991f5-693">กระดาษ Dropbox, ตู้แสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="991f5-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="991f5-694">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="991f5-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="991f5-695">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="991f5-696">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="991f5-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="991f5-697">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="991f5-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="991f5-698">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="991f5-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="991f5-699">ความรับผิดชอบ FastTrack</span><span class="sxs-lookup"><span data-stu-id="991f5-699">FastTrack responsibilities</span></span>

<span data-ttu-id="991f5-700">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะจัดกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-701">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="991f5-702">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-702">Your responsibilities</span></span> 

<span data-ttu-id="991f5-703">คุณปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="991f5-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="991f5-704">อ้างอิงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ของรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="991f5-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="991f5-705">นอกจากนี้ คุณยังจะปฏิบัติกิจกรรมต่อไปนี้โดยเฉพาะในการโยกย้าย Microsoft Teams และ Microsoft 365 Groups:</span><span class="sxs-lookup"><span data-stu-id="991f5-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="991f5-706">เตรียมใช้งานแชนเนล Microsoft Teams และกลุ่ม Microsoft 365 ทั้งหมดตามเป้าหมายของเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="991f5-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="991f5-707">FastTrack ไม่ได้เตรียมใช้งาน Microsoft Teams Channels หรือ Microsoft 365 Groups ไว้ล่วงหน้า</span><span class="sxs-lookup"><span data-stu-id="991f5-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="991f5-708">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนเนล Microsoft Teams หรือกลุ่ม Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="991f5-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="991f5-709">คุณต้องเพิ่มผู้ใช้หรือกลุ่มของคุณลงในแชนเนล Microsoft Teams และกลุ่ม Microsoft 365 ทั้งหมดก่อนที่คุณจะโยกย้ายข้อมูลไปยังปลายทางเหล่านั้น เพื่อให้ผู้ใช้เหล่านั้นสามารถเข้าถึงเอกสารที่เพิ่งโยกย้ายได้</span><span class="sxs-lookup"><span data-stu-id="991f5-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>