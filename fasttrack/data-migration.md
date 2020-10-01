---
title: การโยกย้ายข้อมูล
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319953"
---
# <a name="data-migration"></a><span data-ttu-id="c82e5-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-104">Data Migration</span></span>

<span data-ttu-id="c82e5-105">FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="c82e5-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="c82e5-106">ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="c82e5-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="c82e5-107">**สำหรับผู้เช่า Office ๓๖๕ที่มีสิทธิ์การใช้งาน 150-499**: FastTrack ให้คำแนะนำการโยกย้ายเท่านั้น คุณต้องรับผิดชอบในการดำเนินการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="c82e5-108">เราจะแนะนำคุณเกี่ยวกับเอกสารที่จะช่วยคุณวางแผนและใช้เครื่องมือฟรีเพื่อดำเนินการโยกย้ายแบบบริการตนเอง</span><span class="sxs-lookup"><span data-stu-id="c82e5-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="c82e5-109">**สำหรับผู้เช่า Office ๓๖๕ที่มี๕๐๐หรือสิทธิ์การใช้งานเพิ่มเติม**ให้ทำดังนี้ FastTrack ให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="c82e5-110">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="c82e5-111">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-111">You create and schedule your migration events.</span></span> <span data-ttu-id="c82e5-112">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="c82e5-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนที่จะ9/1/2017 คุณจำเป็นต้องมีสิทธิ์การใช้งาน๑๕๐เท่านั้นที่จะมีคุณสมบัติสำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="c82e5-114">สำหรับแผนการศึกษาเฉพาะผู้ที่ได้รับสิทธิ์การใช้งานคณาจารย์และเจ้าหน้าที่ของคุณเท่านั้นที่มีสิทธิ์สำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="c82e5-115">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="c82e5-115">Considerations</span></span>

  - <span data-ttu-id="c82e5-116">สภาพแวดล้อมต้นฉบับของคุณต้องตรงตามความคาดหวังที่เฉพาะเจาะจงเพื่อโยกย้ายข้อมูลไปยัง Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="c82e5-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="c82e5-117">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) ของข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมแหล่งข้อมูลสำหรับ Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="c82e5-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="c82e5-118">เราจำเป็นต้องมีสิทธิ์การเข้าถึงและสิทธิ์ที่เหมาะสมกับสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="c82e5-119">บริการการโยกย้ายข้อมูลของเราไม่ได้รับการออกแบบหรือไม่เหมาะสมสำหรับข้อมูลภายใต้ข้อกำหนดด้านกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="c82e5-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="c82e5-120">ในขณะที่เราโยกย้ายข้อมูลของคุณจะสามารถถ่ายโอนไปยังที่เก็บและการประมวลผลได้จากทุกที่ที่เรารักษาสิ่งอำนวยความสะดวก (ยกเว้นที่มีให้สำหรับโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="c82e5-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="c82e5-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายอีเมลหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="c82e5-122">ปัญหาที่ไม่คาดฝัน (เช่นรายการที่ไม่สามารถอ่านได้หรือข้อมูลที่เสียหายในสภาพแวดล้อมต้นฉบับ) อาจทำให้ความสามารถของเราในการโยกย้ายบางส่วนของรายการข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="c82e5-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่นการเปลี่ยนแปลงไปยังส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชันของบริษัทอื่น (APIs)) อาจทำให้เกิดการเปลี่ยนแปลงความล่าช้าหรือการระงับการใช้บริการการโยกย้ายข้อมูลของเราได้</span><span class="sxs-lookup"><span data-stu-id="c82e5-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="c82e5-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-124">Migration service availability</span></span>

  - <span data-ttu-id="c82e5-125">**สำหรับลูกค้าภาครัฐเชิงพาณิชย์และสหราชอาณาจักร:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง, 7 (7) วันต่อสัปดาห์ (24 ชั่วโมง)</span><span class="sxs-lookup"><span data-stu-id="c82e5-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="c82e5-126">**สำหรับลูกค้ารัฐบาล/DOD ของสหรัฐอเมริกา:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง5วันทำการ (5) วันทำการ (24x5)</span><span class="sxs-lookup"><span data-stu-id="c82e5-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="c82e5-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c82e5-127">Migration to Exchange Online</span></span>

<span data-ttu-id="c82e5-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c82e5-129">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและการแลกเปลี่ยนแบบออนไลน์และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="c82e5-130">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-130">You create and schedule your migration events.</span></span> <span data-ttu-id="c82e5-131">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c82e5-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดกำหนดการไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณเพื่อที่จะถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c82e5-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="c82e5-133">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="c82e5-133">Considerations</span></span>

  - <span data-ttu-id="c82e5-134">ก่อนการโยกย้ายคุณจะต้องทำการ FastTrack core ปฐมนิเทศสำหรับ Exchange Online ให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="c82e5-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="c82e5-135">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c82e5-136">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="c82e5-137">FastTrack จะย้ายไปยังกล่องจดหมาย Office ๓๖๕ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="c82e5-138">คุณต้องตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="c82e5-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c82e5-139">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="c82e5-140">สภาพแวดล้อมต้นฉบับแต่ละรายการต้องอยู่ในระดับ service pack (SP) ล่าสุดและ rollup (RU)/cumulative (CU) สำหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="c82e5-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="c82e5-141">รายชื่อการแจกจ่าย (วัตถุ*MailEnabledGroup* ) และที่ติดต่อภายนอก (วัตถุ*MailEnabledContact* ) ที่มีอยู่ในไดเรกทอรีที่ใช้งานอยู่ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="c82e5-142">อย่างไรก็ตามคุณสามารถซิงโครไนซ์ได้โดยใช้การเชื่อมต่อ Azure Active Directory (Azure AD)</span><span class="sxs-lookup"><span data-stu-id="c82e5-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="c82e5-143">สภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="c82e5-143">Source environments</span></span>

<span data-ttu-id="c82e5-144">บริการการโยกย้ายข้อมูลของเราจะย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="c82e5-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="c82e5-145">ฟอเรสต์ที่ใช้งานอยู่ของไดเรกทอรีเดียวหรือหลายฟอเรสต์ที่มี Exchange องค์กรเดียวหรือหลายองค์กร (แต่ละระบบจดหมาย Exchange จะต้องมี Exchange ๒๐๑๐หรือมากกว่า)</span><span class="sxs-lookup"><span data-stu-id="c82e5-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="c82e5-146">สภาพแวดล้อมอีเมลที่สามารถใช้งาน IMAP เดียวได้</span><span class="sxs-lookup"><span data-stu-id="c82e5-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="c82e5-147">ระบบ G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="c82e5-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="c82e5-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="c82e5-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c82e5-149"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c82e5-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c82e5-151"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="c82e5-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c82e5-153"><strong>Exchange ๒๐๑๐, Exchange ๒๐๑๓, Exchange ๒๐๑๖, Exchange ๒๐๑๙</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="c82e5-154">
<strong>หมายเหตุ:</strong>   สำหรับการอ้างอิง Exchange ภายในองค์กรให้ดูที่ <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด</span></a></span><span class="sxs-lookup"><span data-stu-id="c82e5-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="c82e5-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="c82e5-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="c82e5-156">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="c82e5-156">Emails</span></span></li>
<li><span data-ttu-id="c82e5-157">กฎสำหรับกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="c82e5-158">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="c82e5-158">Delegates</span></span></li>
<li><span data-ttu-id="c82e5-159">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c82e5-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="c82e5-160">Calendar</span></span> </li>
<li> <span data-ttu-id="c82e5-161">งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-161">Tasks</span></span> </li>
<li> <span data-ttu-id="c82e5-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="c82e5-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="c82e5-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="c82e5-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="c82e5-164">เซ็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-164">Signatures</span></span> </li>
<li> <span data-ttu-id="c82e5-165">ที่เก็บถาวรส่วนบุคคลถูกโยกย้ายด้วยกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="c82e5-166">รายการที่สามารถกู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="c82e5-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-167">Public folders</span></span> </li>
<li> <span data-ttu-id="c82e5-168">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="c82e5-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c82e5-169">การบันทึกที่เก็บถาวรหรือโซลูชันที่เก็บถาวรของบริษัทอื่น</span><span class="sxs-lookup"><span data-stu-id="c82e5-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="c82e5-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-171">เก็บถาวรข้อมูลจากไฟล์ตารางที่เก็บข้อมูลส่วนบุคคล (PST)</span><span class="sxs-lookup"><span data-stu-id="c82e5-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="c82e5-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c82e5-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c82e5-174"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="c82e5-175">
<strong>หมายเหตุ:</strong>   สภาพแวดล้อม G Suite ของคุณจะต้องตรงตามข้อกำหนดเบื้องต้นที่อธิบายไว้ในการ<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ดำเนินการการโยกย้าย G suite</a></span><span class="sxs-lookup"><span data-stu-id="c82e5-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="c82e5-176">แบบเคลื่อนย้ายหรือแบบเป็นฉาก</span><span class="sxs-lookup"><span data-stu-id="c82e5-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-177">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="c82e5-177">Emails</span></span> </li>
<li> <span data-ttu-id="c82e5-178">กล่องจดหมายที่ติดต่อ (ที่อยู่อีเมลที่ไม่เกิน3รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="c82e5-179">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="c82e5-179">Calendar</span></span> </li>
<li> <span data-ttu-id="c82e5-180">ป้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-181">กฎ</span><span class="sxs-lookup"><span data-stu-id="c82e5-181">Rules</span></span> </li>
<li> <span data-ttu-id="c82e5-182">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="c82e5-182">Delegates</span></span> </li>
<li> <span data-ttu-id="c82e5-183">เซ็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-183">Signatures</span></span> </li>
<li> <span data-ttu-id="c82e5-184">งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-184">Tasks</span></span> </li>
<li> <span data-ttu-id="c82e5-185">อีเมลหรือสิ่งที่แนบมาที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="c82e5-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c82e5-186">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-187">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันที่เก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="c82e5-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="c82e5-188">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="c82e5-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="c82e5-189">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c82e5-190">Google แฮงเอาท์ \*\*</span><span class="sxs-lookup"><span data-stu-id="c82e5-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="c82e5-191">กลุ่ม Google</span><span class="sxs-lookup"><span data-stu-id="c82e5-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="c82e5-192">กล่องจดหมายของทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="c82e5-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="c82e5-193">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="c82e5-194">การตั้งค่าวันหยุดและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="c82e5-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="c82e5-195">ปฏิทินที่แชร์สิ่งที่แนบมาในระบบคลาวด์การเชื่อมโยง Google แฮงเอาท์และสีของเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="c82e5-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="c82e5-196">\*\* การสนทนาแฮงเอาท์ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c82e5-197"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="c82e5-198">การโยกย้ายโดยใช้เครื่องมือ IMAP4 native</span><span class="sxs-lookup"><span data-stu-id="c82e5-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="c82e5-199">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="c82e5-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="c82e5-200">กฎ</span><span class="sxs-lookup"><span data-stu-id="c82e5-200">Rules</span></span> </li>
<li> <span data-ttu-id="c82e5-201">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="c82e5-201">Delegates</span></span> </li>
<li> <span data-ttu-id="c82e5-202">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="c82e5-203">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-203">External contacts</span></span> </li>
<li> <span data-ttu-id="c82e5-204">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="c82e5-205">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-206">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c82e5-207">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="c82e5-207">Calendar</span></span> </li>
<li> <span data-ttu-id="c82e5-208">เซ็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-208">Signatures</span></span> </li>
<li> <span data-ttu-id="c82e5-209">งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-209">Tasks</span></span> </li>
<li> <span data-ttu-id="c82e5-210">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="c82e5-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c82e5-211">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-211">Archive data</span></span> </li>
<li> <span data-ttu-id="c82e5-212">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="c82e5-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="c82e5-213">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c82e5-214">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c82e5-215">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="c82e5-215">FastTrack responsibilities</span></span>

<span data-ttu-id="c82e5-216">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c82e5-217">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c82e5-218">ผู้เชี่ยวชาญ FastTrack ของเรายังดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="c82e5-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="c82e5-219">ให้คำแนะนำในการช่วยให้คุณเปิดใช้งานการกำหนดเส้นทางจดหมาย SMTP ที่มีอยู่ร่วมกันระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="c82e5-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c82e5-220">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-220">Your responsibilities</span></span>

<span data-ttu-id="c82e5-221">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c82e5-222">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c82e5-223">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะในการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="c82e5-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="c82e5-224">กรอกข้อมูล FastTrack core ปฐมนิเทศสำหรับ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c82e5-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="c82e5-225">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c82e5-226">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="c82e5-227">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางปฏิบัติของ Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="c82e5-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="c82e5-228">อ้างอิงไปยังที่ [ทำงานสมัยใหม่](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="c82e5-229">ตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="c82e5-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c82e5-230">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="c82e5-231">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของแหล่งข้อมูลแต่ละรายการ (SP) และ rollup (RU)/cumulative update (CU) (CU) ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="c82e5-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="c82e5-232">กำหนดค่าและตรวจสอบความถูกต้องของการกำหนดเส้นทางจดหมาย SMTP ระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="c82e5-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="c82e5-233">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นฉบับของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="c82e5-234">คุณอาจจำเป็นต้องจำกัดข้อมูลต้นฉบับของคุณไป๘๕ยังเปอร์เซ็นต์ของโควตาของกล่องจดหมายเป้าหมายทั้งนี้ขึ้นอยู่กับแพลตฟอร์มต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="c82e5-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="c82e5-235">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="c82e5-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="c82e5-236">ซึ่งรวมถึงแต่ไม่จำกัดเฉพาะสมุดรายชื่อภายในเครื่องข้อมูลในไฟล์ PST ภายในเครื่องกฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="c82e5-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="c82e5-237">ช่วยให้ผู้ใช้ของคุณมีส่วนของปัญหาการโยกย้ายที่ด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="c82e5-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="c82e5-238">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c82e5-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="c82e5-239">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c82e5-240">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและ SharePoint Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c82e5-241">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-241">You create and schedule your migration events.</span></span> <span data-ttu-id="c82e5-242">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c82e5-243">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c82e5-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="c82e5-244">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="c82e5-244">Considerations</span></span>

  - <span data-ttu-id="c82e5-245">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c82e5-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c82e5-246">อ้างอิงไปยัง [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c82e5-247">เราขอแนะนำให้คุณจำกัดจำนวนรวมของการโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="c82e5-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c82e5-248">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-248">Source environment details</span></span>

<span data-ttu-id="c82e5-249">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="c82e5-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c82e5-250">ไฟล์ที่แชร์ (ไฟล์การบล็อกข้อความเซิร์ฟเวอร์ (SMB) บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="c82e5-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c82e5-251">สภาพแวดล้อม G Suite เดียว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="c82e5-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c82e5-252">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="c82e5-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c82e5-253">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="c82e5-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c82e5-254">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="c82e5-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c82e5-255"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c82e5-256"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c82e5-257"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c82e5-258"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c82e5-259"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c82e5-260">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-261">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="c82e5-261">Documents</span></span> </li>
<li> <span data-ttu-id="c82e5-262">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-263">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="c82e5-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c82e5-264">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="c82e5-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c82e5-265">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-266">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-267">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-267">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-268">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-268">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-269">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-269">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-270">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="c82e5-271">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="c82e5-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c82e5-272">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c82e5-273">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c82e5-274">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-275">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="c82e5-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c82e5-276">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-277">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="c82e5-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="c82e5-278">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="c82e5-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c82e5-279">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="c82e5-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c82e5-280">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="c82e5-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c82e5-281">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="c82e5-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c82e5-282">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="c82e5-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c82e5-283">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-284">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="c82e5-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c82e5-285">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="c82e5-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c82e5-286">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c82e5-287"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c82e5-288">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-289">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่า) รวมถึงที่มีค่ามากกว่า10เมกะไบต์</span><span class="sxs-lookup"><span data-stu-id="c82e5-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="c82e5-290">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-291">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-292">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-293">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-294">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-295">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-295">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-296">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-296">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-297">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-297">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-298">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c82e5-299">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="c82e5-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c82e5-300">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-301">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c82e5-302">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c82e5-303">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-304">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-305">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="c82e5-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c82e5-306">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c82e5-307">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-308">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="c82e5-309">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-310">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-311">Google รูปแบบฟอร์มแผนที่และแอปที่เชื่อมต่ออื่นๆ</span><span class="sxs-lookup"><span data-stu-id="c82e5-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c82e5-312">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="c82e5-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c82e5-313">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c82e5-314">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c82e5-315">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c82e5-316">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-317">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c82e5-318">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-319">ไฟล์ที่ถูกทำเครื่องหมายเป็นแบบจำกัดหรือไม่ copyable</span><span class="sxs-lookup"><span data-stu-id="c82e5-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="c82e5-320">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c82e5-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c82e5-322">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-323">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="c82e5-323">Documents</span></span> </li>
<li> <span data-ttu-id="c82e5-324">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-325">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-326">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-327">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-328">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-329">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-329">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-330">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-330">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-331">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-331">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-332">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c82e5-333">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-334">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c82e5-335">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c82e5-336">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-337">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-338">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="c82e5-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c82e5-339">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c82e5-340">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-341">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="c82e5-342">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-343">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-344">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="c82e5-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c82e5-345">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c82e5-346">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c82e5-347">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-348">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c82e5-349"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c82e5-350">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-351">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="c82e5-351">Documents</span></span> </li>
<li> <span data-ttu-id="c82e5-352">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-353">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-354">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-355">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-356">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-357">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-357">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-358">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-358">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-359">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-359">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-360">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c82e5-361">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c82e5-362">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-363">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c82e5-364">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c82e5-365">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-366">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-367">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="c82e5-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c82e5-368">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c82e5-369">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-370">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="c82e5-371">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-372">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="c82e5-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c82e5-373">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="c82e5-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c82e5-374">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="c82e5-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c82e5-375">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="c82e5-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c82e5-376">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c82e5-377">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c82e5-378">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="c82e5-379">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c82e5-380">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="c82e5-380">FastTrack responsibilities</span></span>

<span data-ttu-id="c82e5-381">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c82e5-382">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c82e5-383">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-383">Your responsibilities</span></span>

<span data-ttu-id="c82e5-384">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c82e5-385">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="c82e5-386">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้เฉพาะกับการโยกย้าย SharePoint Online ได้ดังนี้</span><span class="sxs-lookup"><span data-stu-id="c82e5-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="c82e5-387">จัดเตรียมไซต์ทีม SharePoint ทั้งหมดที่จะกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="c82e5-388">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="c82e5-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="c82e5-389">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c82e5-390">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c82e5-391">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-391">You create and schedule your migration events.</span></span> <span data-ttu-id="c82e5-392">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c82e5-393">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="c82e5-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="c82e5-394">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="c82e5-394">Considerations</span></span>

  - <span data-ttu-id="c82e5-395">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตาของ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="c82e5-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="c82e5-396">โปรดดูที่ [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="c82e5-397">เราขอแนะนำให้คุณจำกัดจำนวนข้อมูลโดยรวมที่คุณโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="c82e5-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="c82e5-398">FastTrack จะย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c82e5-399">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="c82e5-399">Source environment details</span></span>

<span data-ttu-id="c82e5-400">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="c82e5-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c82e5-401">ไฟล์ที่แชร์ (ไฟล์ SMB ที่แชร์บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="c82e5-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c82e5-402">สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="c82e5-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c82e5-403">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="c82e5-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c82e5-404">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="c82e5-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c82e5-405">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="c82e5-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="c82e5-406"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="c82e5-407"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="c82e5-408"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c82e5-409"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c82e5-410"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c82e5-411">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-412">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="c82e5-412">Documents</span></span> </li>
<li> <span data-ttu-id="c82e5-413">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-414">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="c82e5-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c82e5-415">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="c82e5-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c82e5-416">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-417">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-418">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-418">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-419">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-419">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-420">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-420">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-421">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="c82e5-422">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="c82e5-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c82e5-423">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c82e5-424">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c82e5-425">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="c82e5-426">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="c82e5-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c82e5-427">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-428">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="c82e5-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="c82e5-429">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="c82e5-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c82e5-430">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="c82e5-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c82e5-431">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="c82e5-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c82e5-432">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="c82e5-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c82e5-433">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="c82e5-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c82e5-434">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-435">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="c82e5-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c82e5-436">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="c82e5-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c82e5-437">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c82e5-438"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c82e5-439">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-440">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากันรวมถึงที่มีค่ามากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="c82e5-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="c82e5-441">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-442">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-443">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-444">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-445">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-446">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-446">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-447">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-447">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-448">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-448">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-449">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c82e5-450">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="c82e5-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c82e5-451">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-452">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c82e5-453">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c82e5-454">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-455">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-456">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="c82e5-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c82e5-457">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c82e5-458">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-459">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="c82e5-460">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-461">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-462">รูปแบบแผนที่และแอปที่เชื่อมต่ออื่นๆของ Google</span><span class="sxs-lookup"><span data-stu-id="c82e5-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c82e5-463">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="c82e5-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c82e5-464">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c82e5-465">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c82e5-466">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c82e5-467">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-468">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c82e5-469">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-470">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c82e5-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c82e5-472">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-473">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="c82e5-473">Documents</span></span> </li>
<li> <span data-ttu-id="c82e5-474">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-475">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-476">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-477">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-478">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-479">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-479">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-480">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-480">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-481">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-481">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-482">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c82e5-483">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-484">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c82e5-485">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c82e5-486">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-487">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-488">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="c82e5-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c82e5-489">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c82e5-490">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-491">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="c82e5-492">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-493">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="c82e5-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c82e5-494">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="c82e5-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c82e5-495">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c82e5-496">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c82e5-497">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-498">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c82e5-499"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="c82e5-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c82e5-500">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="c82e5-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c82e5-501">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="c82e5-501">Documents</span></span> </li>
<li> <span data-ttu-id="c82e5-502">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c82e5-503">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-504">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-505">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="c82e5-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c82e5-506">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="c82e5-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c82e5-507">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="c82e5-507">Created date</span></span> </li>
<li> <span data-ttu-id="c82e5-508">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="c82e5-508">Modified date</span></span> </li>
<li> <span data-ttu-id="c82e5-509">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-509">Created by</span></span> </li>
<li> <span data-ttu-id="c82e5-510">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="c82e5-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c82e5-511">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c82e5-512">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c82e5-513">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="c82e5-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c82e5-514">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="c82e5-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c82e5-515">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="c82e5-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-516">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="c82e5-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c82e5-517">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="c82e5-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c82e5-518">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="c82e5-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c82e5-519">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="c82e5-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c82e5-520">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="c82e5-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="c82e5-521">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="c82e5-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c82e5-522">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="c82e5-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c82e5-523">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="c82e5-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c82e5-524">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="c82e5-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c82e5-525">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="c82e5-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c82e5-526">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c82e5-527">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="c82e5-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c82e5-528">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="c82e5-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c82e5-529">ไฟล์หรือโฟลเดอร์ที่เกิน <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="c82e5-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c82e5-530">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="c82e5-530">FastTrack responsibilities</span></span>

<span data-ttu-id="c82e5-531">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c82e5-532">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c82e5-533">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-533">Your responsibilities</span></span>

<span data-ttu-id="c82e5-534">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="c82e5-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c82e5-535">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="c82e5-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c82e5-536">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="c82e5-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="c82e5-537">จัดเตรียมไซต์ OneDrive for Business ทั้งหมดที่จะได้รับการกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="c82e5-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
