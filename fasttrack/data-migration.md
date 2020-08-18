---
title: การโยกย้ายข้อมูล
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/17/2020
ms.locfileid: "46777228"
---
# <a name="data-migration"></a><span data-ttu-id="88860-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-104">Data Migration</span></span>

<span data-ttu-id="88860-105">FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="88860-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="88860-106">ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="88860-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="88860-107">**สำหรับผู้เช่า Office ๓๖๕ที่มีสิทธิ์การใช้งาน 150-499**: FastTrack ให้คำแนะนำการโยกย้ายเท่านั้น คุณต้องรับผิดชอบในการดำเนินการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="88860-108">เราจะแนะนำคุณเกี่ยวกับเอกสารที่จะช่วยคุณวางแผนและใช้เครื่องมือฟรีเพื่อดำเนินการโยกย้ายแบบบริการตนเอง</span><span class="sxs-lookup"><span data-stu-id="88860-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="88860-109">**สำหรับผู้เช่า Office ๓๖๕ที่มี๕๐๐หรือสิทธิ์การใช้งานเพิ่มเติม**ให้ทำดังนี้ FastTrack ให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="88860-110">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="88860-111">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-111">You create and schedule your migration events.</span></span> <span data-ttu-id="88860-112">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="88860-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="88860-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนที่จะ9/1/2017 คุณจำเป็นต้องมีสิทธิ์การใช้งาน๑๕๐เท่านั้นที่จะมีคุณสมบัติสำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="88860-114">สำหรับแผนการศึกษาเฉพาะผู้ที่ได้รับสิทธิ์การใช้งานคณาจารย์และเจ้าหน้าที่ของคุณเท่านั้นที่มีสิทธิ์สำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="88860-115">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="88860-115">Considerations</span></span>

  - <span data-ttu-id="88860-116">สภาพแวดล้อมต้นฉบับของคุณต้องตรงตามความคาดหวังที่เฉพาะเจาะจงเพื่อโยกย้ายข้อมูลไปยัง Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="88860-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="88860-117">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) ของข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมแหล่งข้อมูลสำหรับ Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="88860-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="88860-118">เราจำเป็นต้องมีสิทธิ์การเข้าถึงและสิทธิ์ที่เหมาะสมกับสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="88860-119">บริการการโยกย้ายข้อมูลของเราไม่ได้รับการออกแบบหรือไม่เหมาะสมสำหรับข้อมูลภายใต้ข้อกำหนดด้านกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="88860-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="88860-120">ในขณะที่เราโยกย้ายข้อมูลของคุณจะสามารถถ่ายโอนไปยังที่เก็บและการประมวลผลได้จากทุกที่ที่เรารักษาสิ่งอำนวยความสะดวก (ยกเว้นที่มีให้สำหรับโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="88860-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="88860-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายอีเมลหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="88860-122">ปัญหาที่ไม่คาดฝัน (เช่นรายการที่ไม่สามารถอ่านได้หรือข้อมูลที่เสียหายในสภาพแวดล้อมต้นฉบับ) อาจทำให้ความสามารถของเราในการโยกย้ายบางส่วนของรายการข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="88860-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่นการเปลี่ยนแปลงไปยังส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชันของบริษัทอื่น (APIs)) อาจทำให้เกิดการเปลี่ยนแปลงความล่าช้าหรือการระงับการใช้บริการการโยกย้ายข้อมูลของเราได้</span><span class="sxs-lookup"><span data-stu-id="88860-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="88860-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-124">Migration service availability</span></span>

  - <span data-ttu-id="88860-125">**สำหรับลูกค้าภาครัฐเชิงพาณิชย์และสหราชอาณาจักร:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง, 7 (7) วันต่อสัปดาห์ (24 ชั่วโมง)</span><span class="sxs-lookup"><span data-stu-id="88860-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="88860-126">**สำหรับลูกค้ารัฐบาล/DOD ของสหรัฐอเมริกา:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง5วันทำการ (5) วันทำการ (24x5)</span><span class="sxs-lookup"><span data-stu-id="88860-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="88860-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="88860-127">Migration to Exchange Online</span></span>

<span data-ttu-id="88860-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="88860-129">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและการแลกเปลี่ยนแบบออนไลน์และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="88860-130">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-130">You create and schedule your migration events.</span></span> <span data-ttu-id="88860-131">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="88860-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="88860-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดกำหนดการไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณเพื่อที่จะถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="88860-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="88860-133">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="88860-133">Considerations</span></span>

  - <span data-ttu-id="88860-134">ก่อนการโยกย้ายคุณจะต้องทำการ FastTrack core ปฐมนิเทศสำหรับ Exchange Online ให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="88860-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="88860-135">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="88860-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="88860-136">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="88860-137">FastTrack จะย้ายไปยังกล่องจดหมาย Office ๓๖๕ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="88860-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="88860-138">คุณต้องตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="88860-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="88860-139">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="88860-140">สภาพแวดล้อมต้นฉบับแต่ละรายการต้องอยู่ในระดับ service pack (SP) ล่าสุดและ rollup (RU)/cumulative (CU) สำหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="88860-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="88860-141">รายชื่อการแจกจ่าย (วัตถุ*MailEnabledGroup* ) และที่ติดต่อภายนอก (วัตถุ*MailEnabledContact* ) ที่มีอยู่ในไดเรกทอรีที่ใช้งานอยู่ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="88860-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="88860-142">อย่างไรก็ตามคุณสามารถซิงโครไนซ์ได้โดยใช้การเชื่อมต่อ Azure Active Directory (Azure AD)</span><span class="sxs-lookup"><span data-stu-id="88860-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="88860-143">สภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="88860-143">Source environments</span></span>

<span data-ttu-id="88860-144">บริการการโยกย้ายข้อมูลของเราจะย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="88860-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="88860-145">ฟอเรสต์ที่ใช้งานอยู่ของไดเรกทอรีเดียวหรือหลายฟอเรสต์ที่มี Exchange องค์กรเดียวหรือหลายองค์กร (แต่ละระบบจดหมาย Exchange จะต้องมี Exchange ๒๐๑๐หรือมากกว่า)</span><span class="sxs-lookup"><span data-stu-id="88860-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="88860-146">สภาพแวดล้อมอีเมลที่สามารถใช้งาน IMAP เดียวได้</span><span class="sxs-lookup"><span data-stu-id="88860-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="88860-147">ระบบ G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="88860-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="88860-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="88860-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88860-149"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="88860-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="88860-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="88860-151"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="88860-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88860-153"><strong>Exchange ๒๐๑๐, Exchange ๒๐๑๓, Exchange ๒๐๑๖, Exchange ๒๐๑๙</strong></span><span class="sxs-lookup"><span data-stu-id="88860-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="88860-154">
<strong>หมายเหตุ:</strong>   สำหรับการอ้างอิง Exchange ภายในองค์กรให้ดูที่ <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด</span></a></span><span class="sxs-lookup"><span data-stu-id="88860-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="88860-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="88860-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="88860-156">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="88860-156">Emails</span></span></li>
<li><span data-ttu-id="88860-157">กฎสำหรับกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="88860-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="88860-158">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="88860-158">Delegates</span></span></li>
<li><span data-ttu-id="88860-159">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="88860-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="88860-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="88860-160">Calendar</span></span> </li>
<li> <span data-ttu-id="88860-161">งาน</span><span class="sxs-lookup"><span data-stu-id="88860-161">Tasks</span></span> </li>
<li> <span data-ttu-id="88860-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="88860-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="88860-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="88860-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="88860-164">เซ็น</span><span class="sxs-lookup"><span data-stu-id="88860-164">Signatures</span></span> </li>
<li> <span data-ttu-id="88860-165">ที่เก็บถาวรส่วนบุคคลถูกโยกย้ายด้วยกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="88860-166">รายการที่สามารถกู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="88860-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="88860-167">Public folders</span></span> </li>
<li> <span data-ttu-id="88860-168">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="88860-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="88860-169">การบันทึกที่เก็บถาวรหรือโซลูชันที่เก็บถาวรของบริษัทอื่น</span><span class="sxs-lookup"><span data-stu-id="88860-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="88860-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-171">เก็บถาวรข้อมูลจากไฟล์ตารางที่เก็บข้อมูลส่วนบุคคล (PST)</span><span class="sxs-lookup"><span data-stu-id="88860-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="88860-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="88860-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88860-174"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="88860-175">
<strong>หมายเหตุ:</strong>   สภาพแวดล้อม G Suite ของคุณจะต้องตรงตามข้อกำหนดเบื้องต้นที่อธิบายไว้ในการ<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ดำเนินการการโยกย้าย G suite</a></span><span class="sxs-lookup"><span data-stu-id="88860-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="88860-176">แบบเคลื่อนย้ายหรือแบบเป็นฉาก</span><span class="sxs-lookup"><span data-stu-id="88860-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-177">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="88860-177">Emails</span></span> </li>
<li> <span data-ttu-id="88860-178">กล่องจดหมายที่ติดต่อ (ที่อยู่อีเมลที่ไม่เกิน3รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="88860-179">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="88860-179">Calendar</span></span> </li>
<li> <span data-ttu-id="88860-180">ป้าย</span><span class="sxs-lookup"><span data-stu-id="88860-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-181">กฎ</span><span class="sxs-lookup"><span data-stu-id="88860-181">Rules</span></span> </li>
<li> <span data-ttu-id="88860-182">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="88860-182">Delegates</span></span> </li>
<li> <span data-ttu-id="88860-183">เซ็น</span><span class="sxs-lookup"><span data-stu-id="88860-183">Signatures</span></span> </li>
<li> <span data-ttu-id="88860-184">งาน</span><span class="sxs-lookup"><span data-stu-id="88860-184">Tasks</span></span> </li>
<li> <span data-ttu-id="88860-185">อีเมลหรือสิ่งที่แนบมาที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="88860-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="88860-186">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-187">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันที่เก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="88860-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="88860-188">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="88860-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="88860-189">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="88860-190">Google แฮงเอาท์ \*\*</span><span class="sxs-lookup"><span data-stu-id="88860-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="88860-191">กลุ่ม Google</span><span class="sxs-lookup"><span data-stu-id="88860-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="88860-192">กล่องจดหมายของทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="88860-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="88860-193">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="88860-194">การตั้งค่าวันหยุดและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="88860-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="88860-195">ปฏิทินที่แชร์สิ่งที่แนบมาในระบบคลาวด์การเชื่อมโยง Google แฮงเอาท์และสีของเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="88860-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="88860-196">\*\* การสนทนาแฮงเอาท์ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88860-197"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="88860-198">การโยกย้ายโดยใช้เครื่องมือ IMAP4 native</span><span class="sxs-lookup"><span data-stu-id="88860-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="88860-199">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="88860-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="88860-200">กฎ</span><span class="sxs-lookup"><span data-stu-id="88860-200">Rules</span></span> </li>
<li> <span data-ttu-id="88860-201">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="88860-201">Delegates</span></span> </li>
<li> <span data-ttu-id="88860-202">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="88860-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="88860-203">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-203">External contacts</span></span> </li>
<li> <span data-ttu-id="88860-204">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="88860-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="88860-205">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-206">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="88860-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="88860-207">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="88860-207">Calendar</span></span> </li>
<li> <span data-ttu-id="88860-208">เซ็น</span><span class="sxs-lookup"><span data-stu-id="88860-208">Signatures</span></span> </li>
<li> <span data-ttu-id="88860-209">งาน</span><span class="sxs-lookup"><span data-stu-id="88860-209">Tasks</span></span> </li>
<li> <span data-ttu-id="88860-210">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="88860-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="88860-211">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-211">Archive data</span></span> </li>
<li> <span data-ttu-id="88860-212">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="88860-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="88860-213">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="88860-214">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="88860-215">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="88860-215">FastTrack responsibilities</span></span>

<span data-ttu-id="88860-216">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="88860-217">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="88860-218">ผู้เชี่ยวชาญ FastTrack ของเรายังดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="88860-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="88860-219">ให้คำแนะนำในการช่วยให้คุณเปิดใช้งานการกำหนดเส้นทางจดหมาย SMTP ที่มีอยู่ร่วมกันระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="88860-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="88860-220">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-220">Your responsibilities</span></span>

<span data-ttu-id="88860-221">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="88860-222">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="88860-223">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะในการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="88860-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="88860-224">กรอกข้อมูล FastTrack core ปฐมนิเทศสำหรับ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="88860-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="88860-225">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="88860-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="88860-226">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="88860-227">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางปฏิบัติของ Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="88860-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="88860-228">อ้างอิงไปยังที่ [ทำงานสมัยใหม่](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="88860-229">ตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="88860-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="88860-230">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="88860-231">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของแหล่งข้อมูลแต่ละรายการ (SP) และ rollup (RU)/cumulative update (CU) (CU) ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="88860-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="88860-232">กำหนดค่าและตรวจสอบความถูกต้องของการกำหนดเส้นทางจดหมาย SMTP ระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="88860-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="88860-233">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นฉบับของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="88860-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="88860-234">คุณอาจจำเป็นต้องจำกัดข้อมูลต้นฉบับของคุณไป๘๕ยังเปอร์เซ็นต์ของโควตาของกล่องจดหมายเป้าหมายทั้งนี้ขึ้นอยู่กับแพลตฟอร์มต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="88860-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="88860-235">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="88860-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="88860-236">ซึ่งรวมถึงแต่ไม่จำกัดเฉพาะสมุดรายชื่อภายในเครื่องข้อมูลในไฟล์ PST ภายในเครื่องกฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="88860-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="88860-237">ช่วยให้ผู้ใช้ของคุณมีส่วนของปัญหาการโยกย้ายที่ด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="88860-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="88860-238">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="88860-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="88860-239">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="88860-240">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและ SharePoint Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="88860-241">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-241">You create and schedule your migration events.</span></span> <span data-ttu-id="88860-242">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="88860-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="88860-243">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="88860-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="88860-244">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="88860-244">Considerations</span></span>

  - <span data-ttu-id="88860-245">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="88860-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="88860-246">อ้างอิงไปยัง [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="88860-247">เราขอแนะนำให้คุณจำกัดจำนวนรวมของการโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="88860-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="88860-248">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-248">Source environment details</span></span>

<span data-ttu-id="88860-249">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="88860-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="88860-250">ไฟล์ที่แชร์ (ไฟล์การบล็อกข้อความเซิร์ฟเวอร์ (SMB) บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="88860-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="88860-251">สภาพแวดล้อม G Suite เดียว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="88860-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="88860-252">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="88860-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="88860-253">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="88860-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="88860-254">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="88860-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="88860-255"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="88860-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="88860-256"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="88860-257"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="88860-258"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88860-259"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="88860-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="88860-260">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-261">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="88860-261">Documents</span></span> </li>
<li> <span data-ttu-id="88860-262">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-263">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="88860-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="88860-264">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="88860-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="88860-265">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-266">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-267">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-267">Created date</span></span> </li>
<li> <span data-ttu-id="88860-268">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-268">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-269">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-269">Created by</span></span> </li>
<li> <span data-ttu-id="88860-270">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="88860-271">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="88860-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="88860-272">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="88860-273">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="88860-274">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-275">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="88860-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="88860-276">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-277">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="88860-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="88860-278">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="88860-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="88860-279">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="88860-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="88860-280">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="88860-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="88860-281">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="88860-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="88860-282">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="88860-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="88860-283">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-284">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="88860-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="88860-285">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="88860-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="88860-286">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88860-287"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="88860-288">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-289">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่า) รวมถึงที่มีค่ามากกว่า10เมกะไบต์</span><span class="sxs-lookup"><span data-stu-id="88860-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="88860-290">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-291">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-292">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-293">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-294">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-295">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-295">Created date</span></span> </li>
<li> <span data-ttu-id="88860-296">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-296">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-297">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-297">Created by</span></span> </li>
<li> <span data-ttu-id="88860-298">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="88860-299">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="88860-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="88860-300">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-301">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="88860-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="88860-302">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="88860-303">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-304">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-305">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="88860-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="88860-306">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="88860-307">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-308">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="88860-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="88860-309">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-310">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-311">Google รูปแบบฟอร์มแผนที่และแอปที่เชื่อมต่ออื่นๆ</span><span class="sxs-lookup"><span data-stu-id="88860-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="88860-312">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="88860-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="88860-313">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="88860-314">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="88860-315">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="88860-316">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="88860-317">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="88860-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="88860-318">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="88860-319">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88860-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="88860-321">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-322">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="88860-322">Documents</span></span> </li>
<li> <span data-ttu-id="88860-323">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-324">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-325">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-326">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-327">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-328">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-328">Created date</span></span> </li>
<li> <span data-ttu-id="88860-329">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-329">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-330">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-330">Created by</span></span> </li>
<li> <span data-ttu-id="88860-331">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="88860-332">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-333">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="88860-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="88860-334">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="88860-335">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-336">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-337">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="88860-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="88860-338">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="88860-339">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-340">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="88860-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="88860-341">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-342">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-343">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="88860-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="88860-344">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="88860-345">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="88860-346">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="88860-347">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88860-348"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="88860-349">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-350">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="88860-350">Documents</span></span> </li>
<li> <span data-ttu-id="88860-351">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-352">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-353">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-354">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-355">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-356">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-356">Created date</span></span> </li>
<li> <span data-ttu-id="88860-357">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-357">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-358">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-358">Created by</span></span> </li>
<li> <span data-ttu-id="88860-359">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="88860-360">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="88860-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="88860-361">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-362">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="88860-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="88860-363">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="88860-364">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-365">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-366">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="88860-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="88860-367">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="88860-368">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-369">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="88860-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="88860-370">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-371">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="88860-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="88860-372">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="88860-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="88860-373">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="88860-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="88860-374">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="88860-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="88860-375">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="88860-376">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="88860-377">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="88860-378">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="88860-379">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="88860-379">FastTrack responsibilities</span></span>

<span data-ttu-id="88860-380">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="88860-381">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="88860-382">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-382">Your responsibilities</span></span>

<span data-ttu-id="88860-383">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="88860-384">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="88860-385">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้เฉพาะกับการโยกย้าย SharePoint Online ได้ดังนี้</span><span class="sxs-lookup"><span data-stu-id="88860-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="88860-386">จัดเตรียมไซต์ทีม SharePoint ทั้งหมดที่จะกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="88860-387">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="88860-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="88860-388">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="88860-389">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="88860-390">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-390">You create and schedule your migration events.</span></span> <span data-ttu-id="88860-391">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="88860-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="88860-392">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="88860-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="88860-393">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="88860-393">Considerations</span></span>

  - <span data-ttu-id="88860-394">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตาของ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="88860-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="88860-395">โปรดดูที่ [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="88860-396">เราขอแนะนำให้คุณจำกัดจำนวนข้อมูลโดยรวมที่คุณโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="88860-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="88860-397">FastTrack จะย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="88860-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="88860-398">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="88860-398">Source environment details</span></span>

<span data-ttu-id="88860-399">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="88860-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="88860-400">ไฟล์ที่แชร์ (ไฟล์ SMB ที่แชร์บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="88860-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="88860-401">สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="88860-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="88860-402">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="88860-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="88860-403">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="88860-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="88860-404">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="88860-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="88860-405"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="88860-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="88860-406"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="88860-407"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="88860-408"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="88860-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="88860-409"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="88860-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="88860-410">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-411">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="88860-411">Documents</span></span> </li>
<li> <span data-ttu-id="88860-412">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-413">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="88860-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="88860-414">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="88860-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="88860-415">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-416">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-417">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-417">Created date</span></span> </li>
<li> <span data-ttu-id="88860-418">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-418">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-419">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-419">Created by</span></span> </li>
<li> <span data-ttu-id="88860-420">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="88860-421">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="88860-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="88860-422">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="88860-423">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="88860-424">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="88860-425">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="88860-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="88860-426">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-427">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="88860-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="88860-428">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="88860-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="88860-429">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="88860-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="88860-430">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="88860-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="88860-431">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="88860-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="88860-432">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="88860-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="88860-433">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-434">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="88860-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="88860-435">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="88860-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="88860-436">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88860-437"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="88860-438">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-439">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากันรวมถึงที่มีค่ามากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="88860-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="88860-440">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-441">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-442">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-443">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-444">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-445">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-445">Created date</span></span> </li>
<li> <span data-ttu-id="88860-446">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-446">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-447">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-447">Created by</span></span> </li>
<li> <span data-ttu-id="88860-448">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="88860-449">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="88860-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="88860-450">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-451">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="88860-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="88860-452">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="88860-453">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-454">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-455">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="88860-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="88860-456">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="88860-457">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-458">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="88860-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="88860-459">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-460">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-461">รูปแบบแผนที่และแอปที่เชื่อมต่ออื่นๆของ Google</span><span class="sxs-lookup"><span data-stu-id="88860-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="88860-462">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="88860-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="88860-463">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="88860-464">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="88860-465">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="88860-466">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="88860-467">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="88860-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="88860-468">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="88860-469">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="88860-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="88860-471">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-472">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="88860-472">Documents</span></span> </li>
<li> <span data-ttu-id="88860-473">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-474">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-475">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-476">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-477">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-478">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-478">Created date</span></span> </li>
<li> <span data-ttu-id="88860-479">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-479">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-480">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-480">Created by</span></span> </li>
<li> <span data-ttu-id="88860-481">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="88860-482">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-483">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="88860-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="88860-484">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="88860-485">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-486">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-487">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="88860-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="88860-488">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="88860-489">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-490">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="88860-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="88860-491">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-492">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="88860-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="88860-493">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="88860-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="88860-494">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="88860-495">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="88860-496">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="88860-497">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="88860-498"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="88860-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="88860-499">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="88860-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="88860-500">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="88860-500">Documents</span></span> </li>
<li> <span data-ttu-id="88860-501">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="88860-502">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-503">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="88860-504">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="88860-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="88860-505">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="88860-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="88860-506">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="88860-506">Created date</span></span> </li>
<li> <span data-ttu-id="88860-507">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="88860-507">Modified date</span></span> </li>
<li> <span data-ttu-id="88860-508">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="88860-508">Created by</span></span> </li>
<li> <span data-ttu-id="88860-509">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="88860-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="88860-510">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="88860-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="88860-511">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="88860-512">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="88860-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="88860-513">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="88860-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="88860-514">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="88860-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-515">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="88860-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="88860-516">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="88860-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="88860-517">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="88860-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="88860-518">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="88860-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="88860-519">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="88860-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="88860-520">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="88860-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="88860-521">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="88860-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="88860-522">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="88860-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="88860-523">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="88860-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="88860-524">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="88860-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="88860-525">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="88860-526">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="88860-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="88860-527">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="88860-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="88860-528">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="88860-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="88860-529">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="88860-529">FastTrack responsibilities</span></span>

<span data-ttu-id="88860-530">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="88860-531">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="88860-532">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-532">Your responsibilities</span></span>

<span data-ttu-id="88860-533">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="88860-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="88860-534">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="88860-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="88860-535">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="88860-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="88860-536">จัดเตรียมไซต์ OneDrive for Business ทั้งหมดที่จะได้รับการกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="88860-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
