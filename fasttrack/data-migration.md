---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมแหล่งข้อมูลของคุณOffice 365 (Exchange Online SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนของOffice 365การใช้งานของคุณ
ms.openlocfilehash: 437da2c12375bfc2d9614c452b0685f18ad3d188
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592432"
---
# <a name="data-migration"></a><span data-ttu-id="996ed-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-104">Data Migration</span></span>

<span data-ttu-id="996ed-105">FastTrack สามารถช่วยให้คุณโยกย้ายจดหมายและไฟล์ข้อมูลในสภาพแวดล้อมแหล่งข้อมูลของคุณOffice 365 (Exchange Online SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="996ed-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="996ed-106">ชนิดของความช่วยเหลือที่เรามีจะขึ้นอยู่กับจํานวนของOffice 365ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="996ed-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="996ed-107">**สําหรับOffice 365เช่าที่มีสิทธิ์การใช้งาน 150-499 สิทธิ์**: FastTrack ให้แนวทางการโยกย้ายเท่านั้น คุณมีหน้าที่รับผิดชอบในการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="996ed-108">เราแนะแนวคุณผ่านเอกสารประกอบที่จะช่วยให้คุณวางแผนและใช้เครื่องมือฟรีเพื่อโยกย้ายด้วยตนเอง</span><span class="sxs-lookup"><span data-stu-id="996ed-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="996ed-109">**สําหรับOffice 365เช่าที่มี 500 สิทธิ์** หรือมากกว่า : FastTrack มอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="996ed-110">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายของคุณ กําหนดค่าสภาพแวดล้อมต้นทางและผู้Office 365ของคุณ และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="996ed-111">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-111">You create and schedule your migration events.</span></span> <span data-ttu-id="996ed-112">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="996ed-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="996ed-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนวันที่ 1/9/2017 คุณมีสิทธิการใช้งานเพียง 150 สิทธิ์จึงจะมีสิทธิ์รับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="996ed-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span><span class="sxs-lookup"><span data-stu-id="996ed-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="996ed-115">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="996ed-115">Considerations</span></span>

  - <span data-ttu-id="996ed-116">สภาพแวดล้อมต้นทางของคุณต้องตรงตามความต้องการเฉพาะเพื่อโยกย้ายข้อมูลOffice 365ข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="996ed-117">ดู[ผลิตภัณฑ์และความสามารถ เพื่อดู](products-and-capabilities.md)ข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมExchangeแหล่งข้อมูล SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="996ed-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="996ed-118">เราต้องการการเข้าถึงและสิทธิ์ที่เหมาะสมต่อสภาพแวดล้อมต้นทางของคุณ และผู้Office 365เช่าเพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="996ed-119">บริการการโยกย้ายข้อมูลของเราไม่ได้ออกแบบหรือมีไว้เพื่อข้อมูลที่อยู่ภายใต้ข้อบังคับทางกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="996ed-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="996ed-120">เมื่อเราโยกย้ายข้อมูลของคุณ ข้อมูลนั้นจะสามารถถ่ายโอน จัดเก็บ และประมวลผลได้จากทุกที่ที่เราบงรักษาสิ่งอสะดวก (ยกเว้นเป็นอย่างอื่นที่มีให้ในโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="996ed-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="996ed-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายจดหมายหรือไฟล์ได้</span><span class="sxs-lookup"><span data-stu-id="996ed-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="996ed-122">ปัญหาที่ไม่ได้คาดไว้ (เช่น รายการไม่สามารถอ่านได้ หรือเสียหายในสภาพแวดล้อมของแหล่งข้อมูล) อาจป้องกันความสามารถในการโยกย้ายรายการข้อมูลบางอย่างของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="996ed-123">ปัจจัยภายนอกที่อยู่นอกการควบคุมของเรา (เช่น การเปลี่ยนแปลงส่วนติดต่อการเขียนโปรแกรมในแอปพลิเคชัน (API)) ของบริษัทอื่น อาจส่งผลให้เกิดการเปลี่ยนแปลง ความล่าช้า หรือระงับบริการการโยกย้ายข้อมูลของเรา</span><span class="sxs-lookup"><span data-stu-id="996ed-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="996ed-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-124">Migration service availability</span></span>

  - <span data-ttu-id="996ed-125">**For Commercial and UK Government customers:** เรามีบริการการโยกย้ายข้อมูลตลอด 24 ชั่วโมงทุกวัน ทุกวัน (24 ชั่วโมง 7) วันต่อสัปดาห์ (24x7 วัน)</span><span class="sxs-lookup"><span data-stu-id="996ed-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="996ed-126">**For US Government/DOD customers:** เรามีบริการการโยกย้ายข้อมูล 24 ชั่วโมงต่อวัน ห้า (5) วันธุรกิจต่อสัปดาห์ (24x5)</span><span class="sxs-lookup"><span data-stu-id="996ed-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="996ed-127">การโยกย้ายExchange Online</span><span class="sxs-lookup"><span data-stu-id="996ed-127">Migration to Exchange Online</span></span>

<span data-ttu-id="996ed-128">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยังบัญชี Exchange Online เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="996ed-129">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้าย กําหนดค่าสภาพแวดล้อมต้นทางและExchange Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="996ed-130">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-130">You create and schedule your migration events.</span></span> <span data-ttu-id="996ed-131">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="996ed-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="996ed-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้จดหมายจากกล่องจดหมายที่จัดเวลาไว้อย่างเหมาะสมและกล่องจดหมายต้นทางที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณExchange Onlineกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="996ed-133">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="996ed-133">Considerations</span></span>

  - <span data-ttu-id="996ed-134">ก่อนการโยกย้าย คุณต้องออนบอร์ดหลัก FastTrack Exchange Onlineให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="996ed-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="996ed-135">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="996ed-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="996ed-136">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="996ed-137">FastTrack จะโยกย้ายไปยังกล่องจดหมายOffice 365เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="996ed-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="996ed-138">คุณต้องเป็นไปตามข้อต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อมExchangeภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="996ed-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="996ed-139">ดู ข้อมูล [เบื้องต้นเกี่ยวกับการปรับใช้แบบ](https://go.microsoft.com/fwlink/?LinkId=787528) ไฮบริด</span><span class="sxs-lookup"><span data-stu-id="996ed-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="996ed-140">สภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมต้องอยู่ในระดับ Service Pack (SP) และ Rollup (RU)/cumulative Update (CU) ล่าสุดสําหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="996ed-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="996ed-141">รายชื่อการแจกจ่าย (วัตถุ *MailEnabledGroup)* และที่ติดต่อภายนอก (*วัตถุ MailEnabledContact)* ที่มีอยู่ใน Active Directory ภายในองค์กรของคุณไม่ใช่ส่วนหนึ่งของการโยกย้ายข้อมูลกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="996ed-142">อย่างไรก็ตาม คุณสามารถซิงโครไนซ์โดยใช้การตั้งค่าAzure Active Directory (Azure AD) เชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="996ed-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="996ed-143">สภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="996ed-143">Source environments</span></span>

<span data-ttu-id="996ed-144">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="996ed-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="996ed-145">ฟอเรสต์ Active Directory เดียวหรือหลายฟอเรสต์ที่มีองค์กร ExchangeเดียวหรือหลายExchange (แต่ละExchangeจดหมายจะต้องExchange 2010 หรือใหม่กว่า)</span><span class="sxs-lookup"><span data-stu-id="996ed-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="996ed-146">สภาพแวดล้อมอีเมลแบบ IMAP แบบเดี่ยว</span><span class="sxs-lookup"><span data-stu-id="996ed-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="996ed-147">สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="996ed-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="996ed-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="996ed-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="996ed-149"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="996ed-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="996ed-151"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="996ed-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="996ed-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="996ed-154">
<strong>หมายเหตุ:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span><span class="sxs-lookup"><span data-stu-id="996ed-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="996ed-155">การโยกย้ายที่มีการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="996ed-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="996ed-156">อีเมล</span><span class="sxs-lookup"><span data-stu-id="996ed-156">Emails</span></span></li>
<li><span data-ttu-id="996ed-157">กฎกล่องจดหมายฝั่งเซิร์ฟเวอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="996ed-158">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="996ed-158">Delegates</span></span></li>
<li><span data-ttu-id="996ed-159">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="996ed-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="996ed-160">Calendar</span></span> </li>
<li> <span data-ttu-id="996ed-161">งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-161">Tasks</span></span> </li>
<li> <span data-ttu-id="996ed-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="996ed-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="996ed-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="996ed-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="996ed-164">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="996ed-164">Signatures</span></span> </li>
<li> <span data-ttu-id="996ed-165">การเก็บถาวรส่วนบุคคลถูกโยกย้ายพร้อมกับกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="996ed-166">รายการที่กู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="996ed-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="996ed-167">Public folders</span></span> </li>
<li> <span data-ttu-id="996ed-168">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="996ed-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="996ed-169">Journaling archive หรือโซลูชันการเก็บถาวรของบริษัทอื่นใดๆ</span><span class="sxs-lookup"><span data-stu-id="996ed-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="996ed-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-171">เก็บถาวรข้อมูลจากไฟล์ Personal Storage Table (PST)</span><span class="sxs-lookup"><span data-stu-id="996ed-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="996ed-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="996ed-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="996ed-174">กฎกล่องจดหมายฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="996ed-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-175"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อ และปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="996ed-176">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณต้องตรงตามเงื่อนไขเบื้องต้นที่อธิบายไว้[ใน การโยกย้าย G Suite](/Exchange/mailbox-migration/perform-g-suite-migration)</span><span class="sxs-lookup"><span data-stu-id="996ed-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in [Perform a G Suite migration](/Exchange/mailbox-migration/perform-g-suite-migration).</span></span></td>
<td><span data-ttu-id="996ed-177">แบบ Cutover หรือแบบระยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-178">อีเมล</span><span class="sxs-lookup"><span data-stu-id="996ed-178">Emails</span></span> </li>
<li> <span data-ttu-id="996ed-179">ที่ติดต่อในกล่องจดหมาย (โยกย้ายที่อยู่อีเมลได้สูงสุด 3 ที่อยู่ต่อหนึ่งที่ติดต่อ)</span><span class="sxs-lookup"><span data-stu-id="996ed-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="996ed-180">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="996ed-180">Calendar</span></span> </li>
<li> <span data-ttu-id="996ed-181">ป้ายชื่อ</span><span class="sxs-lookup"><span data-stu-id="996ed-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-182">กฎ</span><span class="sxs-lookup"><span data-stu-id="996ed-182">Rules</span></span> </li>
<li> <span data-ttu-id="996ed-183">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="996ed-183">Delegates</span></span> </li>
<li> <span data-ttu-id="996ed-184">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="996ed-184">Signatures</span></span> </li>
<li> <span data-ttu-id="996ed-185">งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-185">Tasks</span></span> </li>
<li> <span data-ttu-id="996ed-186">อีเมลหรือสิ่งที่แนบมาใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="996ed-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="996ed-187">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-188">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันการเก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="996ed-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="996ed-189">สิทธิ์ที่ได้รับการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="996ed-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="996ed-190">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="996ed-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="996ed-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="996ed-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="996ed-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="996ed-193">กล่องจดหมายทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="996ed-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="996ed-194">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="996ed-195">การตั้งค่าวันหยุดพักผ่อนและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="996ed-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="996ed-196">ปฏิทินที่แชร์ สิ่งที่แนบมาในระบบคลาวด์ ลิงก์ Google Hangout และสีเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="996ed-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="996ed-197">\*\*การสนทนาใน Hangout ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="996ed-198"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="996ed-199">การโยกย้ายโดยใช้เครื่องมือ IMAP4 ดั้งเดิม</span><span class="sxs-lookup"><span data-stu-id="996ed-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="996ed-200">อีเมล</span><span class="sxs-lookup"><span data-stu-id="996ed-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="996ed-201">กฎ</span><span class="sxs-lookup"><span data-stu-id="996ed-201">Rules</span></span> </li>
<li> <span data-ttu-id="996ed-202">ผู้รับมอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="996ed-202">Delegates</span></span> </li>
<li> <span data-ttu-id="996ed-203">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="996ed-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="996ed-204">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-204">External contacts</span></span> </li>
<li> <span data-ttu-id="996ed-205">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="996ed-206">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-207">ที่ติดต่อในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="996ed-208">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="996ed-208">Calendar</span></span> </li>
<li> <span data-ttu-id="996ed-209">ลายเซ็น</span><span class="sxs-lookup"><span data-stu-id="996ed-209">Signatures</span></span> </li>
<li> <span data-ttu-id="996ed-210">งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-210">Tasks</span></span> </li>
<li> <span data-ttu-id="996ed-211">อีเมลใดๆ ที่มีขนาดเกินขีดจํากัดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="996ed-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="996ed-212">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-212">Archive data</span></span> </li>
<li> <span data-ttu-id="996ed-213">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="996ed-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="996ed-214">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="996ed-215">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="996ed-216">ความรับผิดชอบของ FastTrack Exchange Onlineการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="996ed-217">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-218">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="996ed-219">ผู้เชี่ยวชาญด้าน FastTrack ของเรายังจัดกิจกรรมต่อไปนี้ เฉพาะการโยกย้ายExchange:</span><span class="sxs-lookup"><span data-stu-id="996ed-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="996ed-220">ให้แนวทางเพื่อช่วยให้คุณเปิดใช้งานการต่อสายจดหมาย SMTP ที่อยู่ร่วมกันระหว่างสภาพแวดล้อมต้นทางExchange Onlineการเชื่อมต่อ ของคุณ ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="996ed-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="996ed-221">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-221">Your responsibilities</span></span>

<span data-ttu-id="996ed-222">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-223">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="996ed-224">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้ายExchange:</span><span class="sxs-lookup"><span data-stu-id="996ed-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="996ed-225">การออนบอร์ดหลัก FastTrack ที่สมบูรณ์Exchange Onlineดาวน์โหลด</span><span class="sxs-lookup"><span data-stu-id="996ed-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="996ed-226">ถ้าคุณเริ่มการออนบอร์ดด้วยตนเอง คุณต้องผ่านการตรวจสอบที่ต้องมีและโปรแกรมเบื้องต้น</span><span class="sxs-lookup"><span data-stu-id="996ed-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="996ed-227">ดู [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="996ed-228">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ในระดับที่เหมาะสมตามOffice 365การใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="996ed-229">โปรดดู [สถานที่ทํางานยุค](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) ใหม่ เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="996ed-230">เป็นไปตามข้อต้องการเฉพาะถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อมExchangeภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="996ed-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="996ed-231">ดู ข้อมูล [เบื้องต้นเกี่ยวกับการปรับใช้แบบ](https://go.microsoft.com/fwlink/?LinkId=787528) ไฮบริด</span><span class="sxs-lookup"><span data-stu-id="996ed-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="996ed-232">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อมอยู่บนระดับ Service Pack (SP) ล่าสุด และสะสม (RU)/Cumulative Update (CU) ถ้ามี</span><span class="sxs-lookup"><span data-stu-id="996ed-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="996ed-233">กําหนดค่าและตรวจสอบความถูกต้องของการกําหนดเส้นทางจดหมาย SMTP ที่อยู่ร่วมกันระหว่างสภาพแวดล้อมต้นทางExchange Onlineตรวจสอบความถูกต้อง ถ้าสามารถใช้งานได้</span><span class="sxs-lookup"><span data-stu-id="996ed-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="996ed-234">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นทางของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="996ed-235">ขึ้นอยู่กับแพลตฟอร์มต้นทาง คุณอาจต้องจํากัดแหล่งข้อมูลของคุณถึง 85 เปอร์เซ็นต์ของโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="996ed-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="996ed-236">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="996ed-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="996ed-237">ซึ่งรวมถึงแต่จะไม่จํากัดเฉพาะสมุดรายชื่อภายในเครื่อง ข้อมูลในไฟล์ PST ภายในเครื่อง Outlookกฎพื้นฐาน และการตั้งค่าบัญชีOutlookภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="996ed-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="996ed-238">ช่วยเหลือผู้ใช้ของคุณเกี่ยวกับการแก้ไขปัญหาการโยกย้ายที่ฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="996ed-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="996ed-239">การโยกย้ายSharePointออนไลน์</span><span class="sxs-lookup"><span data-stu-id="996ed-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="996ed-240">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะมอบแนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="996ed-241">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและ SharePoint Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="996ed-242">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-242">You create and schedule your migration events.</span></span> <span data-ttu-id="996ed-243">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="996ed-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="996ed-244">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณSharePoint Online</span><span class="sxs-lookup"><span data-stu-id="996ed-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="996ed-245">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="996ed-245">Considerations</span></span>

 - <span data-ttu-id="996ed-246">การโยกย้ายทั้งหมดขึ้นอยู่กับSharePointโควตาออนไลน์</span><span class="sxs-lookup"><span data-stu-id="996ed-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="996ed-247">โปรดดู<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePointจํากัด</a>เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="996ed-248">เราขอแนะSharePointให้คุณจํากัดจํานวนโดยรวมของการโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint แบบออนไลน์ ทั้งหมดที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="996ed-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="996ed-249">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="996ed-249">Source environment details</span></span>

<span data-ttu-id="996ed-250">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="996ed-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="996ed-251">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="996ed-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="996ed-252">สภาพแวดล้อม G Suite เดียว (Google ไดรฟ์เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="996ed-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="996ed-253">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="996ed-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="996ed-254">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="996ed-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="996ed-255">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="996ed-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="996ed-256"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="996ed-257"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="996ed-258"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="996ed-259"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="996ed-260"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="996ed-261">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-262">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-262">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-263">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-264">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="996ed-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-265">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="996ed-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-266">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-267">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-268">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-268">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-269">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-269">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-270">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-270">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-271">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="996ed-272">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="996ed-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="996ed-273">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงWindows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="996ed-274">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="996ed-275">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-276">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="996ed-277">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-278">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="996ed-279">Windowsแอตทริบิวต์ของไฟล์และโฟลเดอร์ (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="996ed-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="996ed-280">สิทธิ์ขั้นสูงWindowsแบบ NTFS และ NTFS และการตั้งค่าพิเศษที่ไม่ใช่แบบใหม่:</span><span class="sxs-lookup"><span data-stu-id="996ed-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="996ed-281">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="996ed-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="996ed-282">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="996ed-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="996ed-283">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="996ed-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="996ed-284">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-285">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="996ed-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="996ed-286">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="996ed-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="996ed-287">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-288"><strong>สภาพแวดล้อมของ G Suite เดียว (Google ไดรฟ์เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="996ed-289">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-290">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบ Officeที่เทียบเท่ากัน) รวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB</span><span class="sxs-lookup"><span data-stu-id="996ed-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="996ed-291">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-292">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-293">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-294">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-295">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-296">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-296">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-297">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-297">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-298">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-298">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-299">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-300">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="996ed-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="996ed-301">เนื้อหาที่แชร์เป็นเจ้าของโดยGoogle ไดรฟ์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-302">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-303">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="996ed-304">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-305">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-306">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-307">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-308">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-309">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-310">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-311">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-312">Google Photos, Forms, แผนที่ และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="996ed-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="996ed-313">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="996ed-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="996ed-314">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="996ed-315">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยGoogle ไดรฟ์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="996ed-316">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้Google ไดรฟ์ของผู้ดูแลระบบเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-317">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-318">สิทธิ์การเป็นสมาชิกของไดรฟ์<strong>ที่แชร์</strong>(หมายเหตุ : ใช้Google ไดรฟ์ของผู้ดูแลระบบเพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="996ed-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="996ed-319">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-320">ไฟล์ที่ถูกระบุว่าถูกห้ามหรือไม่สามารถคัดลอกได้</span><span class="sxs-lookup"><span data-stu-id="996ed-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="996ed-321">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="996ed-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="996ed-323">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-324">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-324">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-325">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-326">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-327">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-328">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-329">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-330">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-330">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-331">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-331">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-332">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-332">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-333">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-334">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="996ed-335">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="996ed-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-336">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-337">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="996ed-338">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-339">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-340">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-341">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-342">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-343">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-344">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-345">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-346">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="996ed-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="996ed-347">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="996ed-348">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-349">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-350">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-351"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="996ed-352">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-353">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-353">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-354">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-355">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-356">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-357">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-358">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-359">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-359">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-360">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-360">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-361">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-361">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-362">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-363">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="996ed-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="996ed-364">เนื้อหาที่แชร์เป็นเจ้าของโดยDropboxที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-365">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-366">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="996ed-367">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-368">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-369">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-370">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-371">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-372">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-373">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-374">โฟลเดอร์ที่Dropboxไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="996ed-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="996ed-375">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="996ed-376">Dropbox กระดาษ การแสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="996ed-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="996ed-377">Dropbox แอปและรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="996ed-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="996ed-378">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีDropboxโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="996ed-379">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: Dropboxรายงานเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-380">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกใหม่หลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="996ed-381">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="996ed-382">ความรับผิดชอบของ FastTrack SharePointการโยกย้าย Online</span><span class="sxs-lookup"><span data-stu-id="996ed-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="996ed-383">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-384">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="996ed-385">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-385">Your responsibilities</span></span>

<span data-ttu-id="996ed-386">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-387">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="996ed-388">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้ายSharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="996ed-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="996ed-389">เตรียมใช้งานทีมSharePointไซต์ทีมทั้งหมดให้ถูกตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="996ed-390">การโยกย้ายOneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="996ed-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="996ed-391">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยังบัญชี OneDrive for Business เราจะให้แนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="996ed-392">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้ายกําหนดค่าสภาพแวดล้อมต้นทางและOneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="996ed-393">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-393">You create and schedule your migration events.</span></span> <span data-ttu-id="996ed-394">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="996ed-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="996ed-395">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดเวลาไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณOneDrive for Businessแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="996ed-396">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="996ed-396">Considerations</span></span>

  - <span data-ttu-id="996ed-397">การโยกย้ายทั้งหมดขึ้นอยู่กับSharePointโควตาออนไลน์</span><span class="sxs-lookup"><span data-stu-id="996ed-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="996ed-398">โปรดดู<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePointจํากัด</a>เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="996ed-399">เราขอแนะSharePointให้คุณจํากัดปริมาณข้อมูลโดยรวมที่คุณโยกย้ายไปที่ 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="996ed-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="996ed-400">FastTrack จะโยกย้ายไปยังไดรฟ์OneDrive for Businessที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="996ed-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="996ed-401">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="996ed-401">Source environment details</span></span>

<span data-ttu-id="996ed-402">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="996ed-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="996ed-403">การแชร์ไฟล์ (การแชร์ไฟล์ SMB บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="996ed-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="996ed-404">สภาพแวดล้อม G Suite เดียว (Google ไดรฟ์เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="996ed-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="996ed-405">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="996ed-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="996ed-406">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="996ed-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="996ed-407">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="996ed-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="996ed-408"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="996ed-409"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="996ed-410"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="996ed-411"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="996ed-412"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="996ed-413">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-414">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-414">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-415">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-416">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="996ed-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-417">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="996ed-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-418">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-419">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-420">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-420">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-421">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-421">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-422">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-422">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-423">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="996ed-424">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="996ed-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="996ed-425">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงWindows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="996ed-426">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="996ed-427">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="996ed-428">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="996ed-429">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-430">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="996ed-431">Windowsแอตทริบิวต์ของไฟล์และโฟลเดอร์ (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="996ed-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="996ed-432">สิทธิ์ขั้นสูงWindowsแบบ NTFS และ NTFS และการตั้งค่าพิเศษที่ไม่ใช่แบบใหม่:</span><span class="sxs-lookup"><span data-stu-id="996ed-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="996ed-433">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="996ed-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="996ed-434">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="996ed-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="996ed-435">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="996ed-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="996ed-436">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-437">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="996ed-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="996ed-438">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="996ed-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="996ed-439">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-440"><strong>สภาพแวดล้อมของ G Suite เดียว (Google ไดรฟ์เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="996ed-441">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-442">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบOfficeที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="996ed-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="996ed-443">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-444">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-445">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-446">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-447">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-448">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-448">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-449">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-449">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-450">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-450">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-451">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-452">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="996ed-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="996ed-453">เนื้อหาที่แชร์เป็นเจ้าของโดยGoogle ไดรฟ์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-454">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-455">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="996ed-456">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-457">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-458">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-459">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-460">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-461">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-462">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-463">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-464">Google Photos Forms, แผนที่ และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="996ed-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="996ed-465">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="996ed-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="996ed-466">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="996ed-467">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยGoogle ไดรฟ์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="996ed-468">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้Google ไดรฟ์ของผู้ดูแลระบบเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-469">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-470">สิทธิ์สมาชิกไดรฟ์ที่<strong>แชร์ (หมายเหตุ</strong>: ใช้Google ไดรฟ์ของผู้ดูแลระบบเพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="996ed-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="996ed-471">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-472">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="996ed-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="996ed-474">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-475">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-475">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-476">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-477">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-478">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-479">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-480">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-481">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-481">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-482">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-482">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-483">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-483">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-484">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-485">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-486">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-487">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="996ed-488">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-489">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-490">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-491">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-492">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-493">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-494">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-495">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-496">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="996ed-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="996ed-497">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="996ed-498">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-499">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-500">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-501"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="996ed-502">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-503">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-503">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-504">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-505">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-506">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="996ed-507">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-508">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-509">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-509">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-510">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-510">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-511">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-511">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-512">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-513">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="996ed-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="996ed-514">เนื้อหาที่แชร์เป็นเจ้าของโดยDropboxที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="996ed-515">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-516">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="996ed-517">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-518">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-519">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-520">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-521">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-522">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-523">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-524">โฟลเดอร์ที่Dropboxไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="996ed-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="996ed-525">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="996ed-526">Dropbox กระดาษ การแสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="996ed-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="996ed-527">Dropbox แอปและรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="996ed-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="996ed-528">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีDropboxโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="996ed-529">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: Dropboxรายงานเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-530">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-531">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="996ed-532">ความรับผิดชอบของ FastTrack OneDrive for Businessการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="996ed-533">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-534">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="996ed-535">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-535">Your responsibilities</span></span>

<span data-ttu-id="996ed-536">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-537">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="996ed-538">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้ายOneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="996ed-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="996ed-539">เตรียมใช้งานOneDrive for Businessทั้งหมดที่จะตั้งเป้าหมายโดยเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="996ed-540">การโยกย้ายMicrosoft Teams Microsoft 365กลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="996ed-541">เมื่อคุณเลือกใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยังกลุ่ม Microsoft Teams Microsoft 365 เราจะให้แนวทางการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="996ed-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="996ed-542">เรามีแนวทางเพื่อช่วยให้คุณวางแผนการโยกย้าย กําหนดค่าสภาพแวดล้อมต้นทางและกลุ่ม Teams และ Microsoft 365 และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="996ed-543">คุณสร้างและจัดเวลาเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-543">You create and schedule your migration events.</span></span> <span data-ttu-id="996ed-544">เราจะเปิดใช้เหตุการณ์การโยกย้ายตามกําหนดการของคุณ ตรวจสอบความคืบหน้าของเหตุการณ์และรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="996ed-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="996ed-545">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์ คุณสามารถคาดหวังให้ไฟล์จากแหล่งข้อมูลที่เหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นทางของคุณถูกโยกย้ายTeamsและMicrosoft 365กลุ่มของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="996ed-546">TeamsและMicrosoft 365กลุ่มเหล่านี้ต้องได้รับการเตรียมใช้งานไว้ล่วงหน้าโดยลูกค้าก่อน จึงจะสามารถโยกย้ายข้อมูลไปยังชนิดปลายทางเหล่านี้ได้</span><span class="sxs-lookup"><span data-stu-id="996ed-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="996ed-547">Teamsกลุ่มMicrosoft 365กลุ่มจะส่งผลต่อสิทธิ์ของคุณบนที่ตั้งปลายทางของไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="996ed-548">TeamsและMicrosoft 365แบบกลุ่มถูกสร้างขึ้นเพื่อให้สามารถร่วมมือกันได้</span><span class="sxs-lookup"><span data-stu-id="996ed-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="996ed-549">แชTeamsเนลMicrosoft 365กลุ่มจะระบุบุคคลที่สามารถเข้าถึงไฟล์เหล่านั้นเมื่อโยกย้ายไปยังปลายทางเหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="996ed-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="996ed-550">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนTeamsเนลMicrosoft 365สิทธิ์ กลุ่ม ระหว่างการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="996ed-551">ข้อพิจารณา</span><span class="sxs-lookup"><span data-stu-id="996ed-551">Considerations</span></span>

- <span data-ttu-id="996ed-552">การโยกย้ายทั้งหมดขึ้นอยู่กับSharePointโควตาออนไลน์</span><span class="sxs-lookup"><span data-stu-id="996ed-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="996ed-553">โปรดดู<a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePointจํากัด</a>เพื่อดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="996ed-554">เราขอแนะSharePointให้คุณจํากัดจํานวนโดยรวมของการโยกย้ายเป็น 75 เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint แบบออนไลน์ ทั้งหมดที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="996ed-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="996ed-555">รายละเอียดของสภาพแวดล้อมต้นทาง</span><span class="sxs-lookup"><span data-stu-id="996ed-555">Source environment details</span></span>

<span data-ttu-id="996ed-556">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="996ed-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="996ed-557">การแชร์ไฟล์ (การแชร์ไฟล์ Server Message Block (SMB) บนอุปกรณ์ที่สนับสนุน SMB 2.0 เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="996ed-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="996ed-558">สภาพแวดล้อม G Suite เดียว (Google ไดรฟ์เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="996ed-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="996ed-559">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="996ed-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="996ed-560">Dropbox for Teams (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="996ed-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="996ed-561">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะกับสภาพแวดล้อมต้นทางแต่ละสภาพแวดล้อม:</span><span class="sxs-lookup"><span data-stu-id="996ed-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="996ed-562"><strong>สภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="996ed-563"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="996ed-564"><strong>การโยกย้ายคืออะไร</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="996ed-565"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="996ed-566"><strong>อุปกรณ์ที่ใช้ไฟล์ร่วมกันที่สนับสนุน SMB 2.0 เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="996ed-567">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-568">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-568">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-569">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-570">สิทธิ์ไฟล์และโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="996ed-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-571">สิทธิ์ไฟล์และโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="996ed-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-572">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-573">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-574">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-574">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-575">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-575">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-576">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-576">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-577">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="996ed-578">\*ต้องกําหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="996ed-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="996ed-579">เฉพาะสิทธิ์ NTFS ที่ถูกแสดงWindows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="996ed-580">สิทธิ์ที่จัดการโดยตรงบนอุปกรณ์การแชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="996ed-581">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB 2.0 สิทธิ์เทียบเท่า NTFS ที่ถูกแสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="996ed-582">สิทธิ์จะได้รับผลกระทบจากแชMicrosoft 365และ/หรือแชMicrosoft Teamsเนลกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="996ed-583">ถ้าปลายทางคือกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนลกลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="996ed-584">เราไม่แนะMicrosoft Teamsสิทธิ์การโยกย้ายไฟล์ไปยังกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนล</span><span class="sxs-lookup"><span data-stu-id="996ed-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-585">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="996ed-586">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-587">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="996ed-588">Windowsแอตทริบิวต์ของไฟล์และโฟลเดอร์ (เช่น อ่านอย่างเดียวและถูกซ่อน)</span><span class="sxs-lookup"><span data-stu-id="996ed-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="996ed-589">สิทธิ์ขั้นสูงWindowsแบบ NTFS และ NTFS และการตั้งค่าพิเศษที่ไม่ใช่แบบใหม่:</span><span class="sxs-lookup"><span data-stu-id="996ed-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="996ed-590">สิทธิ์การปฏิเสธอย่างชัดแจ้ง (ถูกเอาออกหลังการโยกย้าย เนื้อหาที่อยู่ภายใต้สิทธิ์แบบขนานหรือสิทธิ์บนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="996ed-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="996ed-591">การกําหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="996ed-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="996ed-592">เมตาดาต้าของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="996ed-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="996ed-593">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-594">การแชร์ที่ซ่อน</span><span class="sxs-lookup"><span data-stu-id="996ed-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="996ed-595">การแชร์ (เช่น สิทธิ์ที่ได้รับในระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="996ed-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="996ed-596">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-597"><strong>สภาพแวดล้อมของ G Suite เดียว (Google ไดรฟ์เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="996ed-598">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-599">Google Docs, Sheets และ Slides (ไฟล์จะถูกแปลงเป็นรูปแบบOfficeที่เทียบเท่ากัน ซึ่งรวมถึงไฟล์ที่มีขนาดมากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="996ed-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="996ed-600">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-601">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="996ed-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-602">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="996ed-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-603">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-604">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-605">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-605">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-606">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-606">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-607">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-607">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-608">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-609">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="996ed-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="996ed-610">เนื้อหาที่แชร์เป็นเจ้าของโดยGoogle ไดรฟ์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="996ed-611">\*สิทธิ์ได้รับผลกระทบจากแชนMicrosoft 365และ/หรือแชนMicrosoft Teamsเนลเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="996ed-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="996ed-612">ถ้าปลายทางคือกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนลกลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="996ed-613">เราไม่แนะMicrosoft Teamsสิทธิ์การโยกย้ายไฟล์ไปยังกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนล</span><span class="sxs-lookup"><span data-stu-id="996ed-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="996ed-614">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-615">รายละเอียดไฟล์และโฟลเดอร์ สีโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="996ed-616">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-617">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-618">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-619">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-620">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-621">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-622">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-623">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-624">Google Photos Forms, แผนที่ และแอปอื่นๆ ที่เชื่อมต่ออยู่</span><span class="sxs-lookup"><span data-stu-id="996ed-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="996ed-625">รูปวาด Google</span><span class="sxs-lookup"><span data-stu-id="996ed-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="996ed-626">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="996ed-627">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยGoogle ไดรฟ์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="996ed-628">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้Google ไดรฟ์ของผู้ดูแลระบบเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-629">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-630">สิทธิ์สมาชิกไดรฟ์ที่<strong>แชร์ (หมายเหตุ</strong>: ใช้Google ไดรฟ์ของผู้ดูแลระบบเพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="996ed-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="996ed-631">สั่งให้ผู้ใช้กําหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-632">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="996ed-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="996ed-634">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-635">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-635">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-636">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-637">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="996ed-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-638">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="996ed-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-639">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-640">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-641">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-641">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-642">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-642">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-643">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-643">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-644">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-645">เนื้อหาที่แชร์เป็นเจ้าของโดยบัญชี Box ที่โยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="996ed-646">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="996ed-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="996ed-647">\*สิทธิ์ได้รับผลกระทบจากแชนMicrosoft 365และ/หรือแชนMicrosoft Teamsเนลเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="996ed-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="996ed-648">ถ้าปลายทางคือกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนลกลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="996ed-649">เราไม่แนะMicrosoft Teamsสิทธิ์การโยกย้ายไฟล์ไปยังกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนล</span><span class="sxs-lookup"><span data-stu-id="996ed-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="996ed-650">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-651">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="996ed-652">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-653">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-654">แท็ก Box และเมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-655">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-656">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-657">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-658">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-659">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="996ed-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="996ed-660">แอป Box บุ๊กมาร์ก รายการโปรด และเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="996ed-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="996ed-661">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีผู้ใช้ Box ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="996ed-662">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Box เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-663">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-664">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="996ed-665"><strong>Dropbox for Teams (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="996ed-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="996ed-666">Single หรือ Multi-pass</span><span class="sxs-lookup"><span data-stu-id="996ed-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="996ed-667">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="996ed-667">Documents</span></span> </li>
<li> <span data-ttu-id="996ed-668">โครงสร้างไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="996ed-669">สิทธิ์ในการเข้าถึงโฟลเดอร์ระดับผู้ใช้\*</span><span class="sxs-lookup"><span data-stu-id="996ed-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-670">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม\*</span><span class="sxs-lookup"><span data-stu-id="996ed-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="996ed-671">ไฟล์ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="996ed-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="996ed-672">เอกสารพื้นฐานและเมตาดาต้าของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="996ed-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="996ed-673">วันที่สร้าง</span><span class="sxs-lookup"><span data-stu-id="996ed-673">Created date</span></span> </li>
<li> <span data-ttu-id="996ed-674">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="996ed-674">Modified date</span></span> </li>
<li> <span data-ttu-id="996ed-675">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-675">Created by</span></span> </li>
<li> <span data-ttu-id="996ed-676">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="996ed-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="996ed-677">โฟลเดอร์และเนื้อหาทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="996ed-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="996ed-678">เนื้อหาที่แชร์เป็นเจ้าของโดยDropboxที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="996ed-679">\*สิทธิ์ได้รับผลกระทบจากแชนMicrosoft 365และ/หรือแชนMicrosoft Teamsเนลเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="996ed-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="996ed-680">ถ้าปลายทางคือกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนลกลุ่มหรือแชนเนลจะระบุโปรไฟล์สิทธิ์สุดท้ายในไฟล์ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="996ed-681">เราไม่แนะMicrosoft Teamsสิทธิ์การโยกย้ายไฟล์ไปยังกลุ่มMicrosoft 365หรือแชMicrosoft Teamsเนล</span><span class="sxs-lookup"><span data-stu-id="996ed-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="996ed-682">ประวัติความเป็นเจ้าของ เวอร์ชันก่อนหน้า และข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="996ed-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="996ed-683">รายละเอียดไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="996ed-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="996ed-684">สิทธิ์ไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-685">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="996ed-686">เมตาดาต้าขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="996ed-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="996ed-687">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="996ed-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="996ed-688">การแปลง URL ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="996ed-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="996ed-689">รายการที่ถังขยะ</span><span class="sxs-lookup"><span data-stu-id="996ed-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="996ed-690">เอกสารที่ไม่สามารถเข้าถึงได้หรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="996ed-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="996ed-691">โฟลเดอร์ที่Dropboxไม่ได้ติดตั้ง</span><span class="sxs-lookup"><span data-stu-id="996ed-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="996ed-692">ลบหรือยกเลิกการเชื่อมต่อผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="996ed-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="996ed-693">Dropbox กระดาษ การแสดงภาพ และพื้นที่</span><span class="sxs-lookup"><span data-stu-id="996ed-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="996ed-694">Dropbox แอปและรายการโปรด (ปักหมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="996ed-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="996ed-695">เนื้อหาที่ไม่ได้เป็นเจ้าของโดยบัญชีDropboxโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="996ed-696">สิทธิ์และเมตาดาต้าพื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: Dropboxรายงานเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="996ed-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="996ed-697">สั่งให้ผู้ใช้แชร์เนื้อหากับผู้ใช้ภายนอกอีกครั้งหลังการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="996ed-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="996ed-698">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อSharePointและข้อจํากัดของ Online ปัจจุบัน</span></a> </span><span class="sxs-lookup"><span data-stu-id="996ed-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="996ed-699">ความรับผิดชอบของ FastTrack Microsoft TeamsและการMicrosoft 365กลุ่มต่างๆ</span><span class="sxs-lookup"><span data-stu-id="996ed-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="996ed-700">ผู้เชี่ยวชาญด้าน FastTrack ของเราจะปฏิบัติกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-701">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="996ed-702">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-702">Your responsibilities</span></span> 

<span data-ttu-id="996ed-703">คุณกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="996ed-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="996ed-704">ให้ดูข้อมูลที่รับผิดชอบการโยกย้ายข้อมูล [ในกระบวนการและความคาดหวัง](process-and-expectations.md) ดูรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="996ed-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="996ed-705">นอกจากนี้ คุณยังสามารถกิจกรรมต่อไปนี้ โดยเฉพาะการโยกย้ายกลุ่มMicrosoft Teams Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="996ed-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="996ed-706">เตรียมใช้งานแชMicrosoft Teamsเนลทั้งหมดMicrosoft 365 Groups ตามเป้าหมายของเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="996ed-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="996ed-707">FastTrack จะไม่เตรียมใช้งานแชนเนลMicrosoft Teamsหรือกลุ่มMicrosoft 365ไว้ล่วงหน้า</span><span class="sxs-lookup"><span data-stu-id="996ed-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="996ed-708">FastTrack จะไม่เพิ่มผู้ใช้หรือกลุ่มลงในแชนMicrosoft TeamsเนลMicrosoft 365กลุ่ม</span><span class="sxs-lookup"><span data-stu-id="996ed-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="996ed-709">คุณต้องเพิ่มผู้ใช้หรือกลุ่มของคุณลงในแชนMicrosoft Teamsเนลและกลุ่ม Microsoft 365 ทั้งหมดก่อนที่คุณจะโยกย้ายข้อมูลไปยังปลายทางเหล่านั้น เพื่อให้ผู้ใช้เหล่านั้นมีสิทธิ์เข้าถึงเอกสารที่เพิ่งโยกย้ายเหล่านั้น</span><span class="sxs-lookup"><span data-stu-id="996ed-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>