---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมแหล่งข้อมูลของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ
ms.openlocfilehash: 7b9e48d802e0c33f72165f77b23680915c9c61eb
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994942"
---
# <a name="data-migration"></a><span data-ttu-id="6aee9-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-104">Data Migration</span></span>

<span data-ttu-id="6aee9-105">FastTrack สามารถช่วยให้คุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมแหล่งข้อมูลของคุณไปยัง Office 365 (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="6aee9-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="6aee9-106">ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนสิทธิ์การใช้งาน Office 365 ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="6aee9-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="6aee9-107">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 150-499 สิทธิ์**: FastTrack ให้แนวทางการโยกย้ายเท่านั้น คุณมีหน้าที่รับผิดชอบในการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="6aee9-108">เราแนะแนวคุณผ่านเอกสารประกอบที่จะช่วยให้คุณวางแผนและใช้เครื่องมือฟรีเพื่อโยกย้ายด้วยตนเอง</span><span class="sxs-lookup"><span data-stu-id="6aee9-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="6aee9-109">**สําหรับผู้เช่า Office 365 ที่มีสิทธิ์การใช้งาน 500 สิทธิ์หรือมากกว่า**: FastTrack มอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="6aee9-110">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางของคุณ และผู้เช่า Office 365 และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="6aee9-111">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-111">You create and schedule your migration events.</span></span> <span data-ttu-id="6aee9-112">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="6aee9-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนวันที่ 1/9/2017 คุณมีสิทธิการใช้งานเพียง 150 สิทธิ์จึงจะมีสิทธิ์รับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="6aee9-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span><span class="sxs-lookup"><span data-stu-id="6aee9-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="6aee9-115">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="6aee9-115">Considerations</span></span>

  - <span data-ttu-id="6aee9-116">สภาพแวดล้อมต้นทางของคุณต้องตรงตามความต้องการเฉพาะเพื่อโยกย้ายข้อมูลไปยัง Office 365</span><span class="sxs-lookup"><span data-stu-id="6aee9-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="6aee9-117">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมต้นทางใน Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="6aee9-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="6aee9-118">เราต้องการการเข้าถึงและสิทธิ์ที่เหมาะสมต่อสภาพแวดล้อมต้นทางของคุณและผู้เช่า Office 365 เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="6aee9-119">บริการการโยกย้ายข้อมูลของเราไม่ได้ออกแบบหรือมีไว้เพื่อข้อมูลที่อยู่ภายใต้ข้อบังคับทางกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="6aee9-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="6aee9-120">เมื่อเราโยกย้ายข้อมูลของคุณ ข้อมูลนั้นจะสามารถถ่ายโอน จัดเก็บ และประมวลผลได้จากทุกที่ที่เราบงรักษาสิ่งอสะดวก (ยกเว้นเป็นอย่างอื่นที่มีให้ในโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="6aee9-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="6aee9-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายจดหมายหรือไฟล์ได้</span><span class="sxs-lookup"><span data-stu-id="6aee9-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="6aee9-122">ปัญหาที่ไม่ได้คาดไว้ (เช่น รายการไม่สามารถอ่านได้ หรือเสียหายในสภาพแวดล้อมของแหล่งข้อมูล) อาจป้องกันความสามารถในการโยกย้ายรายการข้อมูลบางอย่างของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="6aee9-123">ปัจจัยภายนอกที่อยู่นอกการควบคุมของเรา (เช่น การเปลี่ยนแปลงส่วนติดต่อการเขียนโปรแกรมในแอปพลิเคชัน (API)) ของบริษัทอื่น อาจส่งผลให้เกิดการเปลี่ยนแปลง ความล่าช้า หรือระงับบริการการโยกย้ายข้อมูลของเรา</span><span class="sxs-lookup"><span data-stu-id="6aee9-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="6aee9-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-124">Migration service availability</span></span>

  - <span data-ttu-id="6aee9-125">**For Commercial and UK Government customers:** เรามีบริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงทุกวัน ทุกวัน (24 ชั่วโมง 7) วันต่อสัปดาห์ (24x7 วัน)</span><span class="sxs-lookup"><span data-stu-id="6aee9-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="6aee9-126">**For US Government/DOD customers:** เรามีบริการการโยกย้ายข้อมูล 24 ชั่วโมงต่อวัน ห้า (5) วันธุรกิจต่อสัปดาห์ (24x5)</span><span class="sxs-lookup"><span data-stu-id="6aee9-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="6aee9-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-127">Migration to Exchange Online</span></span>

<span data-ttu-id="6aee9-128">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="6aee9-129">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและ Exchange Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="6aee9-130">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-130">You create and schedule your migration events.</span></span> <span data-ttu-id="6aee9-131">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="6aee9-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดเวลาไว้อย่างเหมาะสมและกล่องจดหมายต้นทางที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="6aee9-133">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="6aee9-133">Considerations</span></span>

  - <span data-ttu-id="6aee9-134">ก่อนการโยกย้าย คุณต้องออนบอร์ดหลัก FastTrack for Exchange Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="6aee9-135">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="6aee9-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="6aee9-136">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="6aee9-137">FastTrack จะโยกย้ายไปยังกล่องจดหมาย Office 365 ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="6aee9-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="6aee9-138">คุณต้องเป็นไปตามข้อต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="6aee9-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="6aee9-139">ดู ข้อมูล [เบื้องต้นเกี่ยวกับการปรับใช้แบบ](https://go.microsoft.com/fwlink/?LinkId=787528) ไฮบริด</span><span class="sxs-lookup"><span data-stu-id="6aee9-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="6aee9-140">สภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมต้องอยู่ในระดับ Service Pack (SP) และ Rollup (RU)/cumulative Update (CU) ล่าสุดสําหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="6aee9-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="6aee9-141">รายชื่อการแจกจ่าย (วัตถุ *MailEnabledGroup)* และที่ติดต่อภายนอก (*วัตถุ MailEnabledContact)* ที่มีอยู่ใน Active Directory ภายในองค์กรของคุณไม่ใช่ส่วนหนึ่งของการโยกย้ายข้อมูลกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="6aee9-142">อย่างไรก็ตาม คุณสามารถซิงโครไนซ์ได้โดยใช้ Azure Active Directory (Azure AD) Connect</span><span class="sxs-lookup"><span data-stu-id="6aee9-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="6aee9-143">สภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="6aee9-143">Source environments</span></span>

<span data-ttu-id="6aee9-144">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="6aee9-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="6aee9-145">ฟอเรสต์ Active Directory เดียวหรือหลายฟอเรสต์ที่มีองค์กร Exchange เดียวหรือหลายองค์กร (ระบบจดหมาย Exchange แต่ละระบบต้องเป็น Exchange 2010 หรือใหม่กว่า)</span><span class="sxs-lookup"><span data-stu-id="6aee9-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="6aee9-146">สภาพแวดล้อมอีเมลแบบ IMAP แบบเดี่ยว</span><span class="sxs-lookup"><span data-stu-id="6aee9-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="6aee9-147">สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="6aee9-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="6aee9-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="6aee9-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6aee9-149"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="6aee9-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="6aee9-151"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="6aee9-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6aee9-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="6aee9-154">
<strong>หมายเหตุ:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span><span class="sxs-lookup"><span data-stu-id="6aee9-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="6aee9-155">การโยกย้ายที่มีการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="6aee9-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="6aee9-156">อีเมล</span><span class="sxs-lookup"><span data-stu-id="6aee9-156">Emails</span></span></li>
<li><span data-ttu-id="6aee9-157">กฎกล่องจดหมายฝั่งเซิร์ฟเวอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="6aee9-158">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="6aee9-158">Delegates</span></span></li>
<li><span data-ttu-id="6aee9-159">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="6aee9-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="6aee9-160">Calendar</span></span> </li>
<li> <span data-ttu-id="6aee9-161">งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-161">Tasks</span></span> </li>
<li> <span data-ttu-id="6aee9-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="6aee9-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="6aee9-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="6aee9-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="6aee9-164">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-164">Signatures</span></span> </li>
<li> <span data-ttu-id="6aee9-165">การเก็บถาวรส่วนบุคคลถูกโยกย้ายพร้อมกับกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="6aee9-166">รายการที่กู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="6aee9-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-167">Public folders</span></span> </li>
<li> <span data-ttu-id="6aee9-168">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="6aee9-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="6aee9-169">Journaling archive หรือโซลูชันการเก็บถาวรของบริษัทอื่นใดๆ</span><span class="sxs-lookup"><span data-stu-id="6aee9-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="6aee9-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-171">เก็บถาวรข้อมูลจากไฟล์ Personal Storage Table (PST)</span><span class="sxs-lookup"><span data-stu-id="6aee9-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="6aee9-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="6aee9-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="6aee9-174">กฎกล่องจดหมายฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="6aee9-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-175"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="6aee9-176">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณต้องตรงตามเงื่อนไขเบื้องต้นที่อธิบายไว้<a href="/exchange/mailbox-migration/perform-g-suite-migration">ใน การโยกย้าย G Suite</a></span><span class="sxs-lookup"><span data-stu-id="6aee9-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="/exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="6aee9-177">แบบ Cutover หรือแบบระยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-178">อีเมล</span><span class="sxs-lookup"><span data-stu-id="6aee9-178">Emails</span></span> </li>
<li> <span data-ttu-id="6aee9-179">ที่ติดต่อในกล่องจดหมาย (โยกย้ายที่อยู่อีเมลได้สูงสุด 3 ที่อยู่ต่อหนึ่งที่ติดต่อ)</span><span class="sxs-lookup"><span data-stu-id="6aee9-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="6aee9-180">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="6aee9-180">Calendar</span></span> </li>
<li> <span data-ttu-id="6aee9-181">ป้ายชื่อ</span><span class="sxs-lookup"><span data-stu-id="6aee9-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-182">กฎ</span><span class="sxs-lookup"><span data-stu-id="6aee9-182">Rules</span></span> </li>
<li> <span data-ttu-id="6aee9-183">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="6aee9-183">Delegates</span></span> </li>
<li> <span data-ttu-id="6aee9-184">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-184">Signatures</span></span> </li>
<li> <span data-ttu-id="6aee9-185">งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-185">Tasks</span></span> </li>
<li> <span data-ttu-id="6aee9-186">อีเมลหรือสิ่งที่แนบมาใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="6aee9-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="6aee9-187">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-188">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันการเก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="6aee9-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="6aee9-189">สิทธิ์ที่ได้รับการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="6aee9-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="6aee9-190">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="6aee9-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="6aee9-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="6aee9-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="6aee9-193">กล่องจดหมายทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="6aee9-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="6aee9-194">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="6aee9-195">การตั้งค่าวันหยุดพักผ่อนและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="6aee9-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="6aee9-196">ปฏิทินที่แชร์ สิ่งที่แนบมาในระบบคลาวด์ ลิงก์ Google Hangout และสีเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="6aee9-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="6aee9-197">\*\*การสนทนาใน Hangout ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6aee9-198"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="6aee9-199">การโยกย้ายโดยใช้เครื่องมือ IMAP4 ดั้งเดิม</span><span class="sxs-lookup"><span data-stu-id="6aee9-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="6aee9-200">อีเมล</span><span class="sxs-lookup"><span data-stu-id="6aee9-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="6aee9-201">กฎ</span><span class="sxs-lookup"><span data-stu-id="6aee9-201">Rules</span></span> </li>
<li> <span data-ttu-id="6aee9-202">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="6aee9-202">Delegates</span></span> </li>
<li> <span data-ttu-id="6aee9-203">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="6aee9-204">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-204">External contacts</span></span> </li>
<li> <span data-ttu-id="6aee9-205">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="6aee9-206">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-207">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="6aee9-208">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="6aee9-208">Calendar</span></span> </li>
<li> <span data-ttu-id="6aee9-209">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-209">Signatures</span></span> </li>
<li> <span data-ttu-id="6aee9-210">งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-210">Tasks</span></span> </li>
<li> <span data-ttu-id="6aee9-211">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="6aee9-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="6aee9-212">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-212">Archive data</span></span> </li>
<li> <span data-ttu-id="6aee9-213">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="6aee9-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="6aee9-214">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="6aee9-215">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="6aee9-216">ความรับผิดชอบของ FastTrack ในการโยกย้าย Exchange Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="6aee9-217">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-218">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="6aee9-219">ผู้เชี่ยวชาญด้าน FastTrack ของเรายังจัดกิจกรรมต่อไปนี้ เฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="6aee9-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="6aee9-220">ให้แนวทางเพื่อช่วยให้คุณเปิดใช้งานการต่อสายจดหมาย SMTP ที่อยู่ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="6aee9-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="6aee9-221">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-221">Your responsibilities</span></span>

<span data-ttu-id="6aee9-222">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-223">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="6aee9-224">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้าย Exchange:</span><span class="sxs-lookup"><span data-stu-id="6aee9-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="6aee9-225">การออนบอร์ดหลัก FastTrack ที่สมบูรณ์ของ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="6aee9-226">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="6aee9-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="6aee9-227">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="6aee9-228">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ในระดับที่เหมาะสมตามแนวทางของ Office 365</span><span class="sxs-lookup"><span data-stu-id="6aee9-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="6aee9-229">โปรดดู [สถานที่ทํางานยุค](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) ใหม่ เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="6aee9-230">ตรงตามความต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="6aee9-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="6aee9-231">ดู ข้อมูล [เบื้องต้นเกี่ยวกับการปรับใช้แบบ](https://go.microsoft.com/fwlink/?LinkId=787528) ไฮบริด</span><span class="sxs-lookup"><span data-stu-id="6aee9-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="6aee9-232">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมอยู่บนระดับ Service Pack (SP) ล่าสุด และสะสม (RU)/Cumulative Update (CU) ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="6aee9-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="6aee9-233">กําหนดค่าและตรวจสอบความถูกต้องของการกําหนดเส้นทางจดหมาย SMTP ที่อยู่ร่วมกันระหว่างสภาพแวดล้อมต้นทางของคุณและ Exchange Online ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="6aee9-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="6aee9-234">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นทางของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="6aee9-235">ขึ้นอยู่กับแพลตฟอร์มต้นทาง คุณอาจต้องจํากัดแหล่งข้อมูลของคุณถึง 85 เปอร์เซ็นต์ของโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="6aee9-236">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="6aee9-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="6aee9-237">ซึ่งรวมถึงแต่ไม่จํากัดเฉพาะสมุดรายชื่อ ภายในเครื่อง ข้อมูลในไฟล์ PST ภายในเครื่อง กฎของ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="6aee9-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="6aee9-238">ช่วยเหลือผู้ใช้ของคุณเกี่ยวกับการแก้ไขปัญหาการโยกย้ายที่ฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="6aee9-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="6aee9-239">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="6aee9-240">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="6aee9-241">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและ SharePoint Online ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="6aee9-242">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-242">You create and schedule your migration events.</span></span> <span data-ttu-id="6aee9-243">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="6aee9-244">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="6aee9-245">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="6aee9-245">Considerations</span></span>

 - <span data-ttu-id="6aee9-246">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="6aee9-247">ดูข้อ <a href="https://go.microsoft.com/fwlink/?LinkId=698855">จํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="6aee9-248">เราขอแนะให้ คุณ จํากัด จํานวนรวมของโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="6aee9-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="6aee9-249">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="6aee9-249">Source environment details</span></span>

<span data-ttu-id="6aee9-250">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="6aee9-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="6aee9-251">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="6aee9-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="6aee9-252">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="6aee9-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="6aee9-253">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="6aee9-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="6aee9-254">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="6aee9-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="6aee9-255">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="6aee9-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="6aee9-256"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="6aee9-257"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="6aee9-258"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="6aee9-259"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6aee9-260"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="6aee9-261">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-262">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-262">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-263">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-264">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-265">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-266">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-267">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-268">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-268">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-269">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-269">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-270">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-270">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-271">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="6aee9-272">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="6aee9-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="6aee9-273">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงใน File Explorer ของ Windows เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="6aee9-274">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="6aee9-275">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-276">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="6aee9-277">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-278">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="6aee9-279">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="6aee9-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="6aee9-280">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="6aee9-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="6aee9-281">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="6aee9-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="6aee9-282">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="6aee9-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="6aee9-283">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="6aee9-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="6aee9-284">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-285">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="6aee9-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="6aee9-286">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="6aee9-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="6aee9-287">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-288"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="6aee9-289">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-290">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน) รวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB</span><span class="sxs-lookup"><span data-stu-id="6aee9-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="6aee9-291">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-292">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-293">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-294">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-295">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-296">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-296">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-297">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-297">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-298">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-298">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-299">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-300">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="6aee9-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="6aee9-301">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-302">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-303">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="6aee9-304">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-305">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-306">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-307">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-308">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-309">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-310">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-311">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-312">Google Photos, Forms, Maps และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="6aee9-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="6aee9-313">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="6aee9-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="6aee9-314">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="6aee9-315">เนื้อหาที่บัญชี Google Drive ไม่ได้เป็นเจ้าของที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="6aee9-316">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-317">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-318">สิทธิ์การเป็นสมาชิกของไดรฟ์<strong>ที่แชร์</strong>(หมายเหตุ : ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="6aee9-319">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-320">ไฟล์ที่ถูกระบุว่าถูกห้ามหรือไม่สามารถคัดลอกได้</span><span class="sxs-lookup"><span data-stu-id="6aee9-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="6aee9-321">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6aee9-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="6aee9-323">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-324">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-324">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-325">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-326">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-327">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-328">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-329">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-330">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-330">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-331">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-331">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-332">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-332">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-333">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-334">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="6aee9-335">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="6aee9-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-336">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-337">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="6aee9-338">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-339">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-340">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-341">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-342">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-343">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-344">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-345">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-346">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="6aee9-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="6aee9-347">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="6aee9-348">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-349">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-350">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-351"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="6aee9-352">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-353">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-353">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-354">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-355">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-356">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-357">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-358">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-359">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-359">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-360">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-360">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-361">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-361">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-362">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-363">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="6aee9-364">เนื้อหาที่แชร์ที่บัญชีผู้ใช้ Dropbox ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-365">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-366">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="6aee9-367">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-368">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-369">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-370">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-371">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-372">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-373">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-374">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="6aee9-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="6aee9-375">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="6aee9-376">กระดาษ Dropbox, การแสดงภาพ และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="6aee9-377">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="6aee9-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="6aee9-378">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="6aee9-379">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-380">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกใหม่หลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="6aee9-381">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="6aee9-382">ความรับผิดชอบของ FastTrack ในการโยกย้าย SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="6aee9-383">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-384">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="6aee9-385">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-385">Your responsibilities</span></span>

<span data-ttu-id="6aee9-386">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-387">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="6aee9-388">คุณยังสามารถกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="6aee9-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="6aee9-389">เตรียมใช้งานทีมไซต์ SharePoint ทั้งหมดเพื่อตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="6aee9-390">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="6aee9-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="6aee9-391">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="6aee9-392">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="6aee9-393">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-393">You create and schedule your migration events.</span></span> <span data-ttu-id="6aee9-394">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="6aee9-395">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="6aee9-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="6aee9-396">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="6aee9-396">Considerations</span></span>

  - <span data-ttu-id="6aee9-397">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="6aee9-398">ดูข้อ <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> จํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="6aee9-399">เราขอแนะให้ คุณจํากัดปริมาณข้อมูลโดยรวมที่คุณโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="6aee9-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="6aee9-400">FastTrack จะโยกย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="6aee9-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="6aee9-401">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="6aee9-401">Source environment details</span></span>

<span data-ttu-id="6aee9-402">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="6aee9-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="6aee9-403">การแชร์ไฟล์ (การแชร์ไฟล์ SMB บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="6aee9-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="6aee9-404">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="6aee9-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="6aee9-405">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="6aee9-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="6aee9-406">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="6aee9-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="6aee9-407">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="6aee9-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="6aee9-408"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="6aee9-409"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="6aee9-410"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="6aee9-411"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6aee9-412"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="6aee9-413">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-414">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-414">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-415">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-416">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-417">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-418">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-419">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-420">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-420">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-421">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-421">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-422">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-422">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-423">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="6aee9-424">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="6aee9-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="6aee9-425">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงใน File Explorer ของ Windows เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="6aee9-426">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="6aee9-427">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="6aee9-428">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="6aee9-429">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-430">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="6aee9-431">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="6aee9-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="6aee9-432">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="6aee9-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="6aee9-433">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="6aee9-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="6aee9-434">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="6aee9-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="6aee9-435">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="6aee9-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="6aee9-436">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-437">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="6aee9-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="6aee9-438">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="6aee9-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="6aee9-439">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-440"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="6aee9-441">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-442">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="6aee9-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="6aee9-443">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-444">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-445">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-446">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-447">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-448">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-448">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-449">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-449">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-450">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-450">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-451">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-452">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="6aee9-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="6aee9-453">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-454">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-455">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="6aee9-456">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-457">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-458">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-459">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-460">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-461">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-462">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-463">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-464">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="6aee9-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="6aee9-465">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="6aee9-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="6aee9-466">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="6aee9-467">เนื้อหาที่บัญชี Google Drive ไม่ได้เป็นเจ้าของที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="6aee9-468">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-469">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-470">สิทธิ์สมาชิกไดรฟ์ที่<strong>แชร์ (หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="6aee9-471">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-472">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6aee9-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="6aee9-474">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-475">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-475">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-476">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-477">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-478">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-479">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-480">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-481">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-481">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-482">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-482">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-483">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-483">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-484">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-485">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-486">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-487">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="6aee9-488">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-489">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-490">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-491">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-492">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-493">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-494">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-495">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-496">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="6aee9-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="6aee9-497">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="6aee9-498">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-499">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-500">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-501"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="6aee9-502">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-503">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-503">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-504">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-505">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-506">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-507">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-508">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-509">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-509">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-510">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-510">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-511">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-511">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-512">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-513">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="6aee9-514">เนื้อหาที่แชร์ที่บัญชีผู้ใช้ Dropbox ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="6aee9-515">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-516">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="6aee9-517">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-518">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-519">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-520">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-521">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-522">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-523">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-524">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="6aee9-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="6aee9-525">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="6aee9-526">กระดาษ Dropbox, การแสดงภาพ และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="6aee9-527">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="6aee9-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="6aee9-528">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="6aee9-529">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-530">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-531">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="6aee9-532">ความรับผิดชอบของ FastTrack ในการโยกย้าย OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="6aee9-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="6aee9-533">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-534">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="6aee9-535">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-535">Your responsibilities</span></span>

<span data-ttu-id="6aee9-536">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-537">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="6aee9-538">คุณยังสามารถกิจกรรมต่อไปนี้โดยเฉพาะการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="6aee9-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="6aee9-539">เตรียมใช้งานไซต์ OneDrive for Business ทั้งหมดที่จะตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="6aee9-540">การโยกย้ายไปยัง Microsoft Teams และกลุ่ม Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="6aee9-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="6aee9-541">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง Microsoft Teams และกลุ่ม Microsoft 365 เราจะให้แนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="6aee9-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="6aee9-542">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้าย กําหนดค่าสภาพแวดล้อมต้นทางและ Teams และ Microsoft 365 Groups และใช้ประโยชน์บริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="6aee9-543">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-543">You create and schedule your migration events.</span></span> <span data-ttu-id="6aee9-544">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="6aee9-545">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของคุณถูกโยกย้ายไปยัง Teams และ Microsoft 365 Groups</span><span class="sxs-lookup"><span data-stu-id="6aee9-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="6aee9-546">ช่องทางของทีมและกลุ่ม Microsoft 365 จะต้องได้รับการจัดเตรียมไว้ล่วงหน้าโดยลูกค้าก่อน จึงจะสามารถโยกย้ายข้อมูลไปยังประเภทปลายทางเหล่านี้ได้</span><span class="sxs-lookup"><span data-stu-id="6aee9-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="6aee9-547">Teams และ Microsoft 365 Groups จะส่งผลต่อสิทธิ์ของคุณต่อสถานที่ตั้งปลายทางของไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="6aee9-548">Teams และ Microsoft 365 Groups ถูกสร้างขึ้นเพื่อให้สามารถร่วมมือกันได้</span><span class="sxs-lookup"><span data-stu-id="6aee9-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="6aee9-549">แชนเนล Teams หรือกลุ่ม Microsoft 365 จะระบุบุคคลที่สามารถเข้าถึงไฟล์เหล่านั้นเมื่อโยกย้ายไปยังปลายทางเหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="6aee9-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="6aee9-550">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนเนล Teams ใดๆ หรือสิทธิ์กลุ่ม Microsoft 365 ระหว่างการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="6aee9-551">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="6aee9-551">Considerations</span></span>

- <span data-ttu-id="6aee9-552">การโยกย้ายทั้งหมดขึ้นอยู่กับโควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6aee9-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="6aee9-553">ดูข้อ <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> จํากัดของ SharePoint</a> เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="6aee9-554">เราขอแนะให้ คุณ จํากัด จํานวนรวมของโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="6aee9-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="6aee9-555">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="6aee9-555">Source environment details</span></span>

<span data-ttu-id="6aee9-556">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="6aee9-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="6aee9-557">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="6aee9-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="6aee9-558">สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="6aee9-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="6aee9-559">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="6aee9-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="6aee9-560">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="6aee9-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="6aee9-561">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="6aee9-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="6aee9-562"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="6aee9-563"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="6aee9-564"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="6aee9-565"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="6aee9-566"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="6aee9-567">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-568">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-568">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-569">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-570">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-571">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-572">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-573">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-574">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-574">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-575">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-575">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-576">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-576">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-577">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="6aee9-578">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="6aee9-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="6aee9-579">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงใน File Explorer ของ Windows เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="6aee9-580">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="6aee9-581">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="6aee9-582">สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="6aee9-583">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="6aee9-584">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-585">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="6aee9-586">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-587">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="6aee9-588">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="6aee9-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="6aee9-589">สิทธิ์ขั้นสูงและการตั้งค่าพิเศษต่างๆ ของ Non-Windows New Technology File System (NTFS) และ NTFS:</span><span class="sxs-lookup"><span data-stu-id="6aee9-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="6aee9-590">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="6aee9-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="6aee9-591">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="6aee9-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="6aee9-592">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="6aee9-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="6aee9-593">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-594">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="6aee9-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="6aee9-595">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="6aee9-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="6aee9-596">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-597"><strong>สภาพแวดล้อม G Suite เดียว (Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="6aee9-598">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-599">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="6aee9-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="6aee9-600">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-601">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-602">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-603">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-604">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-605">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-605">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-606">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-606">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-607">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-607">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-608">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-609">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="6aee9-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="6aee9-610">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Google Drive ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="6aee9-611">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="6aee9-612">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="6aee9-613">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="6aee9-614">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-615">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="6aee9-616">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-617">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-618">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-619">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-620">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-621">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-622">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-623">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-624">Google Photos Forms, Maps และแอปอื่นๆ ที่เชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="6aee9-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="6aee9-625">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="6aee9-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="6aee9-626">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="6aee9-627">เนื้อหาที่บัญชี Google Drive ไม่ได้เป็นเจ้าของที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="6aee9-628">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-629">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-630">สิทธิ์สมาชิกไดรฟ์ที่<strong>แชร์ (หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="6aee9-631">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-632">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="6aee9-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="6aee9-634">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-635">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-635">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-636">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-637">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-638">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-639">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-640">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-641">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-641">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-642">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-642">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-643">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-643">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-644">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-645">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="6aee9-646">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="6aee9-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="6aee9-647">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="6aee9-648">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="6aee9-649">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="6aee9-650">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-651">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="6aee9-652">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-653">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-654">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-655">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-656">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-657">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-658">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-659">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="6aee9-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="6aee9-660">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="6aee9-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="6aee9-661">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="6aee9-662">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-663">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-664">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="6aee9-665"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="6aee9-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="6aee9-666">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="6aee9-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="6aee9-667">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="6aee9-667">Documents</span></span> </li>
<li> <span data-ttu-id="6aee9-668">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="6aee9-669">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-670">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="6aee9-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="6aee9-671">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="6aee9-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="6aee9-672">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="6aee9-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="6aee9-673">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-673">Created date</span></span> </li>
<li> <span data-ttu-id="6aee9-674">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="6aee9-674">Modified date</span></span> </li>
<li> <span data-ttu-id="6aee9-675">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-675">Created by</span></span> </li>
<li> <span data-ttu-id="6aee9-676">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="6aee9-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="6aee9-677">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="6aee9-678">เนื้อหาที่แชร์ที่บัญชีผู้ใช้ Dropbox ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="6aee9-679">\*สิทธิ์ได้รับผลกระทบจากกลุ่ม Microsoft 365 และ/หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="6aee9-680">ถ้าปลายทางคือกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams กลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="6aee9-681">เราไม่แนะให้โยกย้ายสิทธิ์ในไฟล์การโยกย้ายไปยังกลุ่ม Microsoft 365 หรือแชนเนล Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="6aee9-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="6aee9-682">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="6aee9-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="6aee9-683">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="6aee9-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="6aee9-684">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-685">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="6aee9-686">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="6aee9-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="6aee9-687">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="6aee9-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="6aee9-688">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="6aee9-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="6aee9-689">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="6aee9-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="6aee9-690">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="6aee9-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="6aee9-691">โฟลเดอร์ Dropbox ที่ไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="6aee9-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="6aee9-692">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6aee9-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="6aee9-693">กระดาษ Dropbox, การแสดงภาพ และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="6aee9-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="6aee9-694">แอป Dropbox และรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="6aee9-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="6aee9-695">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="6aee9-696">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="6aee9-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="6aee9-697">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="6aee9-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="6aee9-698">ไฟล์หรือโฟลเดอร์ที่เกินข้อ <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">จํากัดและข้อจํากัดของ SharePoint Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="6aee9-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="6aee9-699">ความรับผิดชอบของ FastTrack ในการโยกย้าย Microsoft Teams และ Microsoft 365 Groups</span><span class="sxs-lookup"><span data-stu-id="6aee9-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="6aee9-700">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-701">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="6aee9-702">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-702">Your responsibilities</span></span> 

<span data-ttu-id="6aee9-703">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="6aee9-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="6aee9-704">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="6aee9-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="6aee9-705">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้ายกลุ่มMicrosoft Teams Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="6aee9-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="6aee9-706">เตรียมใช้งานแชMicrosoft Teamsเนลทั้งหมดMicrosoft 365 Groups ตามเป้าหมายของเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="6aee9-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="6aee9-707">FastTrackแชนเนลหรือกลุ่มMicrosoft Teams Microsoft 365ล่วงหน้า</span><span class="sxs-lookup"><span data-stu-id="6aee9-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="6aee9-708">FastTrackเพิ่มผู้ใช้หรือกลุ่มลงในแชนMicrosoft TeamsเนลMicrosoft 365กลุ่ม</span><span class="sxs-lookup"><span data-stu-id="6aee9-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="6aee9-709">คุณต้องเพิ่มผู้ใช้หรือกลุ่มของคุณลงในแชนMicrosoft Teamsเนลและกลุ่ม Microsoft 365 ทั้งหมดก่อนที่คุณจะโยกย้ายข้อมูลไปยังปลายทางเหล่านั้น เพื่อให้ผู้ใช้เหล่านั้นมีสิทธิ์เข้าถึงเอกสารที่เพิ่งโยกย้ายเหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="6aee9-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>