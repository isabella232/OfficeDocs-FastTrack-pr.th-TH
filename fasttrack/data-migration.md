---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมแหล่งข้อมูลของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ
ms.openlocfilehash: 07165233711d4d4931f8adac4809b56138078f5a
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927003"
---
# <a name="data-migration"></a><span data-ttu-id="09015-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-104">Data Migration</span></span>

<span data-ttu-id="09015-105">FastTrack สามารถช่วยให้คุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมแหล่งข้อมูลของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="09015-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="09015-106">ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="09015-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="09015-107">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 150-499 สิทธิ์**: FastTrack ให้แนวทางการโยกย้ายเท่านั้น คุณมีหน้าที่รับผิดชอบในการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="09015-108">เราแนะแนวคุณผ่านเอกสารประกอบที่จะช่วยให้คุณวางแผนและใช้เครื่องมือฟรีเพื่อโยกย้ายด้วยตนเอง</span><span class="sxs-lookup"><span data-stu-id="09015-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="09015-109">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 500 สิทธิ์หรือมากกว่า**: FastTrack มอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="09015-110">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางของคุณ และผู้เช่า Office 365 และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="09015-111">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-111">You create and schedule your migration events.</span></span> <span data-ttu-id="09015-112">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="09015-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="09015-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนวันที่ 1/9/2017 คุณมีสิทธิการใช้งานเพียง 150 สิทธิ์จึงจะมีสิทธิ์รับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="09015-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span><span class="sxs-lookup"><span data-stu-id="09015-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="09015-115">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="09015-115">Considerations</span></span>

  - <span data-ttu-id="09015-116">สภาพแวดล้อมต้นทางของคุณต้องตรงตามความต้องการเฉพาะเพื่อโยกย้ายข้อมูลไปยัง Office 365</span><span class="sxs-lookup"><span data-stu-id="09015-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="09015-117">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมต้นทางใน Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="09015-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="09015-118">เราต้องการการเข้าถึงและสิทธิ์ที่เหมาะสมต่อสภาพแวดล้อมต้นทางของคุณและผู้เช่า Office 365 เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="09015-119">บริการการโยกย้ายข้อมูลของเราไม่ได้ออกแบบหรือมีไว้เพื่อข้อมูลที่อยู่ภายใต้ข้อบังคับทางกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="09015-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="09015-120">เมื่อเราโยกย้ายข้อมูลของคุณ ข้อมูลนั้นจะสามารถถ่ายโอน จัดเก็บ และประมวลผลได้จากทุกที่ที่เราบงรักษาสิ่งอสะดวก (ยกเว้นเป็นอย่างอื่นที่มีให้ในโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="09015-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="09015-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายจดหมายหรือไฟล์ได้</span><span class="sxs-lookup"><span data-stu-id="09015-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="09015-122">ปัญหาที่ไม่ได้คาดไว้ (เช่น รายการไม่สามารถอ่านได้ หรือเสียหายในสภาพแวดล้อมของแหล่งข้อมูล) อาจป้องกันความสามารถในการโยกย้ายรายการข้อมูลบางอย่างของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="09015-123">ปัจจัยภายนอกที่อยู่นอกการควบคุมของเรา (เช่น การเปลี่ยนแปลงส่วนติดต่อการเขียนโปรแกรมในแอปพลิเคชัน (API)) ของบริษัทอื่น อาจส่งผลให้เกิดการเปลี่ยนแปลง ความล่าช้า หรือระงับบริการการโยกย้ายข้อมูลของเรา</span><span class="sxs-lookup"><span data-stu-id="09015-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="09015-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-124">Migration service availability</span></span>

  - <span data-ttu-id="09015-125">**For Commercial and UK Government customers:** เรามีบริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงทุกวัน ทุกวัน (24 ชั่วโมง 7) วันต่อสัปดาห์ (24x7 วัน)</span><span class="sxs-lookup"><span data-stu-id="09015-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="09015-126">**For US Government/DOD customers:** เรามีบริการการโยกย้ายข้อมูล 24 ชั่วโมงต่อวัน ห้า (5) วันธุรกิจต่อสัปดาห์ (24x5)</span><span class="sxs-lookup"><span data-stu-id="09015-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="09015-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="09015-127">Migration to Exchange Online</span></span>

<span data-ttu-id="09015-128">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="09015-129">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและ Exchange Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="09015-130">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-130">You create and schedule your migration events.</span></span> <span data-ttu-id="09015-131">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="09015-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="09015-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดเวลาไว้อย่างเหมาะสมและกล่องจดหมายต้นทางที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="09015-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="09015-133">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="09015-133">Considerations</span></span>

  - <span data-ttu-id="09015-134">ก่อนการโยกย้าย คุณต้องออนบอร์ดหลัก FastTrack for Exchange Online</span><span class="sxs-lookup"><span data-stu-id="09015-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="09015-135">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="09015-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="09015-136">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="09015-137">FastTrack จะโยกย้ายไปยังกล่องจดหมาย Office 365 ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="09015-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="09015-138">คุณต้องเป็นไปตามข้อต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="09015-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="09015-139">ดู ข้อมูล [เบื้องต้นเกี่ยวกับการปรับใช้แบบ](https://go.microsoft.com/fwlink/?LinkId=787528) ไฮบริด</span><span class="sxs-lookup"><span data-stu-id="09015-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="09015-140">สภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมต้องอยู่ในระดับ Service Pack (SP) และ Rollup (RU)/cumulative Update (CU) ล่าสุดสําหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="09015-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="09015-141">รายชื่อการแจกจ่าย (วัตถุ *MailEnabledGroup)* และที่ติดต่อภายนอก (*วัตถุ MailEnabledContact)* ที่มีอยู่ใน Active Directory ภายในองค์กรของคุณไม่ใช่ส่วนหนึ่งของการโยกย้ายข้อมูลกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="09015-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="09015-142">อย่างไรก็ตาม คุณสามารถซิงโครไนซ์ได้โดยใช้ Azure Active Directory (Azure AD) Connect</span><span class="sxs-lookup"><span data-stu-id="09015-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="09015-143">สภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="09015-143">Source environments</span></span>

<span data-ttu-id="09015-144">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="09015-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="09015-145">ฟอเรสต์ Active Directory เดียวหรือหลายฟอเรสต์ที่มีองค์กร Exchange เดียวหรือหลายองค์กร (ระบบจดหมาย Exchange แต่ละระบบต้องเป็น Exchange 2010 หรือใหม่กว่า)</span><span class="sxs-lookup"><span data-stu-id="09015-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="09015-146">สภาพแวดล้อมอีเมลแบบ IMAP แบบเดี่ยว</span><span class="sxs-lookup"><span data-stu-id="09015-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="09015-147">สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="09015-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="09015-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="09015-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09015-149"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="09015-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="09015-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="09015-151"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="09015-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="09015-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09015-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="09015-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="09015-154">
<strong>หมายเหตุ:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span><span class="sxs-lookup"><span data-stu-id="09015-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="09015-155">การโยกย้ายที่มีการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="09015-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="09015-156">อีเมล</span><span class="sxs-lookup"><span data-stu-id="09015-156">Emails</span></span></li>
<li><span data-ttu-id="09015-157">กฎกล่องจดหมายฝั่งเซิร์ฟเวอร์</span><span class="sxs-lookup"><span data-stu-id="09015-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="09015-158">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="09015-158">Delegates</span></span></li>
<li><span data-ttu-id="09015-159">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="09015-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="09015-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="09015-160">Calendar</span></span> </li>
<li> <span data-ttu-id="09015-161">งาน</span><span class="sxs-lookup"><span data-stu-id="09015-161">Tasks</span></span> </li>
<li> <span data-ttu-id="09015-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="09015-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="09015-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="09015-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="09015-164">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="09015-164">Signatures</span></span> </li>
<li> <span data-ttu-id="09015-165">การเก็บถาวรส่วนบุคคลถูกโยกย้ายพร้อมกับกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="09015-166">รายการที่กู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="09015-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="09015-167">Public folders</span></span> </li>
<li> <span data-ttu-id="09015-168">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="09015-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="09015-169">Journaling archive หรือโซลูชันการเก็บถาวรของบริษัทอื่นใดๆ</span><span class="sxs-lookup"><span data-stu-id="09015-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="09015-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-171">เก็บถาวรข้อมูลจากไฟล์ Personal Storage Table (PST)</span><span class="sxs-lookup"><span data-stu-id="09015-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="09015-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="09015-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="09015-174">กฎกล่องจดหมายฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="09015-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-175"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="09015-176">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณต้องตรงตามเงื่อนไขเบื้องต้นที่อธิบายไว้<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ใน การโยกย้าย G Suite</a></span><span class="sxs-lookup"><span data-stu-id="09015-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="09015-177">แบบ Cutover หรือแบบระยะ</span><span class="sxs-lookup"><span data-stu-id="09015-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-178">อีเมล</span><span class="sxs-lookup"><span data-stu-id="09015-178">Emails</span></span> </li>
<li> <span data-ttu-id="09015-179">ที่ติดต่อในกล่องจดหมาย (โยกย้ายที่อยู่อีเมลได้สูงสุด 3 ที่อยู่ต่อหนึ่งที่ติดต่อ)</span><span class="sxs-lookup"><span data-stu-id="09015-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="09015-180">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="09015-180">Calendar</span></span> </li>
<li> <span data-ttu-id="09015-181">ป้ายชื่อ</span><span class="sxs-lookup"><span data-stu-id="09015-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-182">กฎ</span><span class="sxs-lookup"><span data-stu-id="09015-182">Rules</span></span> </li>
<li> <span data-ttu-id="09015-183">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="09015-183">Delegates</span></span> </li>
<li> <span data-ttu-id="09015-184">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="09015-184">Signatures</span></span> </li>
<li> <span data-ttu-id="09015-185">งาน</span><span class="sxs-lookup"><span data-stu-id="09015-185">Tasks</span></span> </li>
<li> <span data-ttu-id="09015-186">อีเมลหรือสิ่งที่แนบมาใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="09015-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="09015-187">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-188">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันการเก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="09015-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="09015-189">สิทธิ์ที่ได้รับการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="09015-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="09015-190">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="09015-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="09015-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="09015-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="09015-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="09015-193">กล่องจดหมายทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="09015-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="09015-194">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="09015-195">การตั้งค่าวันหยุดพักผ่อนและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="09015-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="09015-196">ปฏิทินที่แชร์ สิ่งที่แนบมาในระบบคลาวด์ ลิงก์ Google Hangout และสีเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="09015-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="09015-197">\*\*การสนทนาใน Hangout ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09015-198"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="09015-199">การโยกย้ายโดยใช้เครื่องมือ IMAP4 ดั้งเดิม</span><span class="sxs-lookup"><span data-stu-id="09015-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="09015-200">อีเมล</span><span class="sxs-lookup"><span data-stu-id="09015-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="09015-201">กฎ</span><span class="sxs-lookup"><span data-stu-id="09015-201">Rules</span></span> </li>
<li> <span data-ttu-id="09015-202">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="09015-202">Delegates</span></span> </li>
<li> <span data-ttu-id="09015-203">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="09015-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="09015-204">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-204">External contacts</span></span> </li>
<li> <span data-ttu-id="09015-205">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="09015-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="09015-206">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-207">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="09015-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="09015-208">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="09015-208">Calendar</span></span> </li>
<li> <span data-ttu-id="09015-209">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="09015-209">Signatures</span></span> </li>
<li> <span data-ttu-id="09015-210">งาน</span><span class="sxs-lookup"><span data-stu-id="09015-210">Tasks</span></span> </li>
<li> <span data-ttu-id="09015-211">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="09015-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="09015-212">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-212">Archive data</span></span> </li>
<li> <span data-ttu-id="09015-213">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="09015-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="09015-214">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="09015-215">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="09015-216">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="09015-216">FastTrack responsibilities</span></span>

<span data-ttu-id="09015-217">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-218">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="09015-219">ผู้เชี่ยวชาญด้าน FastTrack ของเรายังจัดกิจกรรมต่อไปนี้ เฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="09015-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="09015-220">ให้แนวทางเพื่อช่วยให้คุณเปิดใช้งานการต่อสายจดหมาย SMTP ที่อยู่ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="09015-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="09015-221">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-221">Your responsibilities</span></span>

<span data-ttu-id="09015-222">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-223">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="09015-224">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="09015-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="09015-225">การออนบอร์ดหลัก FastTrack ที่สมบูรณ์ของ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="09015-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="09015-226">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="09015-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="09015-227">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="09015-228">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ในระดับที่เหมาะสมตามแนวทางของ Office 365</span><span class="sxs-lookup"><span data-stu-id="09015-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="09015-229">โปรดดู [สถานที่ทํางานยุค](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) ใหม่ เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="09015-230">ตรงตามความต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="09015-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="09015-231">ดู ข้อมูล [เบื้องต้นเกี่ยวกับการปรับใช้แบบ](https://go.microsoft.com/fwlink/?LinkId=787528) ไฮบริด</span><span class="sxs-lookup"><span data-stu-id="09015-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="09015-232">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมอยู่บนระดับ Service Pack (SP) ล่าสุด และสะสม (RU)/Cumulative Update (CU) ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="09015-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="09015-233">กําหนดค่าและตรวจสอบความถูกต้องของการกําหนดเส้นทางจดหมาย SMTP ที่อยู่ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="09015-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="09015-234">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นทางของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="09015-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="09015-235">ขึ้นอยู่กับแพลตฟอร์มต้นทาง คุณอาจต้องจํากัดแหล่งข้อมูลของคุณถึง 85 เปอร์เซ็นต์ของโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="09015-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="09015-236">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="09015-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="09015-237">ซึ่งรวมถึงแต่ไม่จํากัดเฉพาะสมุดรายชื่อ ภายในเครื่อง ข้อมูลในไฟล์ PST ภายในเครื่อง กฎของ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="09015-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="09015-238">ช่วยเหลือผู้ใช้ของคุณเกี่ยวกับการแก้ไขปัญหาการโยกย้ายที่ฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="09015-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="09015-239">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="09015-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="09015-240">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="09015-241">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและ SharePoint Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="09015-242">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-242">You create and schedule your migration events.</span></span> <span data-ttu-id="09015-243">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="09015-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="09015-244">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="09015-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="09015-245">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="09015-245">Considerations</span></span>

 - <span data-ttu-id="09015-246">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="09015-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="09015-247">ดูข้อ <a href="https://go.microsoft.com/fwlink/?LinkId=698855">จํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="09015-248">เราขอแนะให้ คุณ จํากัด จํานวนรวมของโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="09015-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="09015-249">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="09015-249">Source environment details</span></span>

<span data-ttu-id="09015-250">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="09015-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="09015-251">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="09015-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="09015-252">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="09015-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="09015-253">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="09015-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="09015-254">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="09015-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="09015-255">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="09015-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="09015-256"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="09015-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="09015-257"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="09015-258"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="09015-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="09015-259"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09015-260"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="09015-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="09015-261">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-262">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-262">Documents</span></span> </li>
<li> <span data-ttu-id="09015-263">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-264">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="09015-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-265">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="09015-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-266">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-267">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-268">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-268">Created date</span></span> </li>
<li> <span data-ttu-id="09015-269">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-269">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-270">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-270">Created by</span></span> </li>
<li> <span data-ttu-id="09015-271">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="09015-272">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="09015-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="09015-273">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงใน File Explorer ของ Windows เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="09015-274">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="09015-275">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-276">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="09015-277">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-278">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="09015-279">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="09015-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="09015-280">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="09015-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="09015-281">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="09015-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="09015-282">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="09015-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="09015-283">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="09015-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="09015-284">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-285">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="09015-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="09015-286">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="09015-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="09015-287">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-288"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="09015-289">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-290">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน) รวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB</span><span class="sxs-lookup"><span data-stu-id="09015-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="09015-291">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-292">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-293">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-294">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-295">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-296">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-296">Created date</span></span> </li>
<li> <span data-ttu-id="09015-297">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-297">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-298">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-298">Created by</span></span> </li>
<li> <span data-ttu-id="09015-299">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-300">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="09015-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="09015-301">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-302">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-303">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="09015-304">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-305">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-306">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-307">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-308">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-309">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-310">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-311">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-312">Google Photos, Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="09015-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="09015-313">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="09015-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="09015-314">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="09015-315">เนื้อหาที่บัญชี Google Drive ไม่ได้เป็นเจ้าของที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="09015-316">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-317">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-318">สิทธิ์การเป็นสมาชิกของไดรฟ์<strong>ที่แชร์</strong>(หมายเหตุ : ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="09015-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="09015-319">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="09015-320">ไฟล์ที่ถูกระบุว่าถูกห้ามหรือไม่สามารถคัดลอกได้</span><span class="sxs-lookup"><span data-stu-id="09015-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="09015-321">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09015-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="09015-323">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-324">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-324">Documents</span></span> </li>
<li> <span data-ttu-id="09015-325">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-326">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-327">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-328">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-329">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-330">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-330">Created date</span></span> </li>
<li> <span data-ttu-id="09015-331">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-331">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-332">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-332">Created by</span></span> </li>
<li> <span data-ttu-id="09015-333">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-334">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="09015-335">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="09015-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-336">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-337">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="09015-338">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-339">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-340">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-341">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-342">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-343">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-344">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-345">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-346">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="09015-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="09015-347">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="09015-348">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-349">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-350">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-351"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="09015-352">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-353">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-353">Documents</span></span> </li>
<li> <span data-ttu-id="09015-354">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-355">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-356">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-357">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-358">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-359">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-359">Created date</span></span> </li>
<li> <span data-ttu-id="09015-360">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-360">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-361">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-361">Created by</span></span> </li>
<li> <span data-ttu-id="09015-362">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-363">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="09015-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="09015-364">เนื้อหาที่แชร์ที่บัญชีผู้ใช้ Dropbox ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-365">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-366">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="09015-367">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-368">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-369">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-370">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-371">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-372">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-373">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-374">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="09015-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="09015-375">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="09015-376">กระดาษ Dropbox, การแสดงภาพ และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="09015-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="09015-377">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="09015-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="09015-378">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="09015-379">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-380">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกใหม่หลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="09015-381">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="09015-382">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="09015-382">FastTrack responsibilities</span></span>

<span data-ttu-id="09015-383">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-384">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="09015-385">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-385">Your responsibilities</span></span>

<span data-ttu-id="09015-386">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-387">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="09015-388">คุณยังสามารถกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="09015-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="09015-389">เตรียมใช้งานทีมไซต์ SharePoint ทั้งหมดเพื่อตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="09015-390">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="09015-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="09015-391">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="09015-392">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="09015-393">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-393">You create and schedule your migration events.</span></span> <span data-ttu-id="09015-394">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="09015-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="09015-395">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="09015-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="09015-396">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="09015-396">Considerations</span></span>

  - <span data-ttu-id="09015-397">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="09015-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="09015-398">ดูข้อ <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> จํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="09015-399">เราขอแนะให้ คุณจํากัดปริมาณข้อมูลโดยรวมที่คุณโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="09015-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="09015-400">FastTrack จะโยกย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="09015-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="09015-401">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="09015-401">Source environment details</span></span>

<span data-ttu-id="09015-402">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="09015-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="09015-403">การแชร์ไฟล์ (การแชร์ไฟล์ SMB บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="09015-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="09015-404">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="09015-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="09015-405">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="09015-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="09015-406">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="09015-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="09015-407">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="09015-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="09015-408"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="09015-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="09015-409"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="09015-410"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="09015-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="09015-411"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09015-412"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="09015-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="09015-413">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-414">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-414">Documents</span></span> </li>
<li> <span data-ttu-id="09015-415">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-416">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="09015-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-417">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="09015-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-418">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-419">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-420">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-420">Created date</span></span> </li>
<li> <span data-ttu-id="09015-421">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-421">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-422">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-422">Created by</span></span> </li>
<li> <span data-ttu-id="09015-423">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="09015-424">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="09015-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="09015-425">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงใน File Explorer ของ Windows เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="09015-426">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="09015-427">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="09015-428">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="09015-429">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-430">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="09015-431">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="09015-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="09015-432">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="09015-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="09015-433">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="09015-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="09015-434">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="09015-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="09015-435">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="09015-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="09015-436">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-437">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="09015-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="09015-438">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="09015-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="09015-439">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-440"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="09015-441">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-442">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="09015-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="09015-443">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-444">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-445">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-446">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-447">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-448">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-448">Created date</span></span> </li>
<li> <span data-ttu-id="09015-449">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-449">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-450">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-450">Created by</span></span> </li>
<li> <span data-ttu-id="09015-451">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-452">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="09015-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="09015-453">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-454">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-455">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="09015-456">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-457">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-458">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-459">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-460">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-461">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-462">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-463">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-464">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="09015-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="09015-465">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="09015-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="09015-466">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="09015-467">เนื้อหาที่บัญชี Google Drive ไม่ได้เป็นเจ้าของที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="09015-468">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-469">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-470">สิทธิ์สมาชิกไดรฟ์ที่<strong>แชร์ (หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="09015-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="09015-471">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="09015-472">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09015-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="09015-474">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-475">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-475">Documents</span></span> </li>
<li> <span data-ttu-id="09015-476">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-477">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-478">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-479">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-480">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-481">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-481">Created date</span></span> </li>
<li> <span data-ttu-id="09015-482">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-482">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-483">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-483">Created by</span></span> </li>
<li> <span data-ttu-id="09015-484">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-485">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-486">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-487">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="09015-488">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-489">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-490">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-491">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-492">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-493">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-494">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-495">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-496">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="09015-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="09015-497">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="09015-498">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-499">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-500">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-501"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="09015-502">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-503">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-503">Documents</span></span> </li>
<li> <span data-ttu-id="09015-504">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-505">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-506">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="09015-507">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-508">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-509">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-509">Created date</span></span> </li>
<li> <span data-ttu-id="09015-510">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-510">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-511">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-511">Created by</span></span> </li>
<li> <span data-ttu-id="09015-512">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-513">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="09015-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="09015-514">เนื้อหาที่แชร์ที่บัญชีผู้ใช้ Dropbox ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="09015-515">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-516">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="09015-517">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-518">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-519">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-520">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-521">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-522">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-523">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-524">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="09015-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="09015-525">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="09015-526">กระดาษ Dropbox, การแสดงภาพ และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="09015-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="09015-527">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="09015-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="09015-528">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="09015-529">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-530">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-531">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="09015-532">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="09015-532">FastTrack responsibilities</span></span>

<span data-ttu-id="09015-533">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-534">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="09015-535">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-535">Your responsibilities</span></span>

<span data-ttu-id="09015-536">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-537">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="09015-538">คุณยังสามารถกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="09015-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="09015-539">เตรียมใช้งานไซต์ OneDrive for Business ทั้งหมดที่จะตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="09015-540">การโยกย้ายไปยัง Microsoft Teams และกลุ่ม Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="09015-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="09015-541">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง Microsoft Teams และกลุ่ม Microsoft 365 เราจะให้แนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="09015-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="09015-542">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้าย กําหนดค่าสภาพแวดล้อมต้นทางและ Teams และ Microsoft 365 Groups และใช้ประโยชน์บริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="09015-543">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-543">You create and schedule your migration events.</span></span> <span data-ttu-id="09015-544">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="09015-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="09015-545">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของคุณถูกโยกย้ายไปยัง Teams และ Microsoft 365 Groups</span><span class="sxs-lookup"><span data-stu-id="09015-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="09015-546">ช่องทางของทีมและกลุ่ม Microsoft 365 จะต้องได้รับการจัดเตรียมไว้ล่วงหน้าโดยลูกค้าก่อน จึงจะสามารถโยกย้ายข้อมูลไปยังประเภทปลายทางเหล่านี้ได้</span><span class="sxs-lookup"><span data-stu-id="09015-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="09015-547">Teams และ Microsoft 365 Groups จะส่งผลต่อสิทธิ์ของคุณต่อสถานที่ตั้งปลายทางของไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="09015-548">Teams และ Microsoft 365 Groups ถูกสร้างขึ้นเพื่อให้สามารถร่วมมือกันได้</span><span class="sxs-lookup"><span data-stu-id="09015-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="09015-549">แชนเนล Teams หรือกลุ่ม Microsoft 365 จะระบุบุคคลที่สามารถเข้าถึงไฟล์เหล่านั้นเมื่อโยกย้ายไปยังปลายทางเหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="09015-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="09015-550">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนเนล Teams ใดๆ หรือสิทธิ์กลุ่ม Microsoft 365 ระหว่างการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="09015-551">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="09015-551">Considerations</span></span>

- <span data-ttu-id="09015-552">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="09015-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="09015-553">ดูข้อ <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> จํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="09015-554">เราขอแนะให้ คุณ จํากัด จํานวนรวมของโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="09015-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="09015-555">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="09015-555">Source environment details</span></span>

<span data-ttu-id="09015-556">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="09015-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="09015-557">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="09015-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="09015-558">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="09015-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="09015-559">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="09015-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="09015-560">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="09015-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="09015-561">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="09015-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="09015-562"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="09015-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="09015-563"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="09015-564"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="09015-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="09015-565"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="09015-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="09015-566"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="09015-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="09015-567">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-568">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-568">Documents</span></span> </li>
<li> <span data-ttu-id="09015-569">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-570">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="09015-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-571">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="09015-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-572">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-573">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-574">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-574">Created date</span></span> </li>
<li> <span data-ttu-id="09015-575">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-575">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-576">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-576">Created by</span></span> </li>
<li> <span data-ttu-id="09015-577">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="09015-578">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="09015-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="09015-579">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงใน File Explorer ของ Windows เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="09015-580">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="09015-581">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="09015-582">สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="09015-583">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="09015-584">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-585">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="09015-586">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-587">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="09015-588">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="09015-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="09015-589">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="09015-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="09015-590">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="09015-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="09015-591">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="09015-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="09015-592">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="09015-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="09015-593">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-594">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="09015-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="09015-595">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="09015-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="09015-596">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-597"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="09015-598">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-599">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="09015-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="09015-600">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-601">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="09015-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-602">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="09015-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-603">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-604">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-605">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-605">Created date</span></span> </li>
<li> <span data-ttu-id="09015-606">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-606">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-607">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-607">Created by</span></span> </li>
<li> <span data-ttu-id="09015-608">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-609">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="09015-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="09015-610">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="09015-611">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="09015-612">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="09015-613">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="09015-614">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-615">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="09015-616">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-617">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-618">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-619">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-620">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-621">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-622">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-623">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-624">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="09015-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="09015-625">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="09015-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="09015-626">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="09015-627">เนื้อหาที่บัญชี Google Drive ไม่ได้เป็นเจ้าของที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="09015-628">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-629">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-630">สิทธิ์สมาชิกไดรฟ์ที่<strong>แชร์ (หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="09015-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="09015-631">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="09015-632">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="09015-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="09015-634">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-635">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-635">Documents</span></span> </li>
<li> <span data-ttu-id="09015-636">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-637">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="09015-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-638">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="09015-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-639">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-640">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-641">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-641">Created date</span></span> </li>
<li> <span data-ttu-id="09015-642">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-642">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-643">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-643">Created by</span></span> </li>
<li> <span data-ttu-id="09015-644">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-645">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="09015-646">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="09015-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="09015-647">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="09015-648">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="09015-649">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="09015-650">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-651">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="09015-652">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-653">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-654">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-655">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-656">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-657">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-658">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-659">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="09015-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="09015-660">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="09015-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="09015-661">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="09015-662">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-663">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-664">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="09015-665"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="09015-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="09015-666">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="09015-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="09015-667">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="09015-667">Documents</span></span> </li>
<li> <span data-ttu-id="09015-668">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="09015-669">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="09015-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-670">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="09015-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="09015-671">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="09015-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="09015-672">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="09015-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="09015-673">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="09015-673">Created date</span></span> </li>
<li> <span data-ttu-id="09015-674">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="09015-674">Modified date</span></span> </li>
<li> <span data-ttu-id="09015-675">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="09015-675">Created by</span></span> </li>
<li> <span data-ttu-id="09015-676">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="09015-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="09015-677">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="09015-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="09015-678">เนื้อหาที่แชร์ที่บัญชีผู้ใช้ Dropbox ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="09015-679">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="09015-680">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="09015-681">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="09015-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="09015-682">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="09015-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="09015-683">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="09015-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="09015-684">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-685">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="09015-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="09015-686">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="09015-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="09015-687">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="09015-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="09015-688">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="09015-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="09015-689">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="09015-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="09015-690">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="09015-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="09015-691">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="09015-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="09015-692">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="09015-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="09015-693">กระดาษ Dropbox, การแสดงภาพ และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="09015-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="09015-694">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="09015-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="09015-695">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="09015-696">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="09015-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="09015-697">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="09015-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="09015-698">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="09015-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="09015-699">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="09015-699">FastTrack responsibilities</span></span>

<span data-ttu-id="09015-700">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-701">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="09015-702">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-702">Your responsibilities</span></span> 

<span data-ttu-id="09015-703">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="09015-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="09015-704">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="09015-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="09015-705">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้าย Microsoft Teams และ Microsoft 365 Groups:</span><span class="sxs-lookup"><span data-stu-id="09015-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="09015-706">เตรียมใช้งานแชนเนล Microsoft Teams และกลุ่ม Microsoft 365 ทั้งหมดตามเป้าหมายของเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="09015-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="09015-707">FastTrack ไม่ได้เตรียมแชนเนล Microsoft Teams หรือกลุ่ม Microsoft 365 ไว้ล่วงหน้า</span><span class="sxs-lookup"><span data-stu-id="09015-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="09015-708">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนเนล Microsoft Teams หรือกลุ่ม Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="09015-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="09015-709">คุณต้องเพิ่มผู้ใช้หรือกลุ่มของคุณไปยังแชนเนล Microsoft Teams และกลุ่ม Microsoft 365 ทั้งหมดก่อนที่คุณจะโยกย้ายข้อมูลไปยังปลายทางเหล่านั้น เพื่อให้ผู้ใช้เหล่านั้นมีสิทธิ์เข้าถึงเอกสารที่โยกย้ายใหม่เหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="09015-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>