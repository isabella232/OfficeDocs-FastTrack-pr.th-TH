---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750048"
---
# <a name="data-migration"></a><span data-ttu-id="3c677-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-104">Data Migration</span></span>

<span data-ttu-id="3c677-105">FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="3c677-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="3c677-106">ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="3c677-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="3c677-107">**สำหรับผู้เช่า Office ๓๖๕ที่มีสิทธิ์การใช้งาน 150-499**: FastTrack ให้คำแนะนำการโยกย้ายเท่านั้น คุณต้องรับผิดชอบในการดำเนินการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="3c677-108">เราจะแนะนำคุณเกี่ยวกับเอกสารที่จะช่วยคุณวางแผนและใช้เครื่องมือฟรีเพื่อดำเนินการโยกย้ายแบบบริการตนเอง</span><span class="sxs-lookup"><span data-stu-id="3c677-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="3c677-109">**สำหรับผู้เช่า Office ๓๖๕ที่มี๕๐๐หรือสิทธิ์การใช้งานเพิ่มเติม** ให้ทำดังนี้ FastTrack ให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="3c677-110">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="3c677-111">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-111">You create and schedule your migration events.</span></span> <span data-ttu-id="3c677-112">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="3c677-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="3c677-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนที่จะ9/1/2017 คุณจำเป็นต้องมีสิทธิ์การใช้งาน๑๕๐เท่านั้นที่จะมีคุณสมบัติสำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="3c677-114">สำหรับแผนการศึกษาเฉพาะผู้ที่ได้รับสิทธิ์การใช้งานคณาจารย์และเจ้าหน้าที่ของคุณเท่านั้นที่มีสิทธิ์สำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="3c677-115">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="3c677-115">Considerations</span></span>

  - <span data-ttu-id="3c677-116">สภาพแวดล้อมต้นฉบับของคุณต้องตรงตามความคาดหวังที่เฉพาะเจาะจงเพื่อโยกย้ายข้อมูลไปยัง Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="3c677-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="3c677-117">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) ของข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมแหล่งข้อมูลสำหรับ Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="3c677-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="3c677-118">เราจำเป็นต้องมีสิทธิ์การเข้าถึงและสิทธิ์ที่เหมาะสมกับสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="3c677-119">บริการการโยกย้ายข้อมูลของเราไม่ได้รับการออกแบบหรือไม่เหมาะสมสำหรับข้อมูลภายใต้ข้อกำหนดด้านกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="3c677-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="3c677-120">ในขณะที่เราโยกย้ายข้อมูลของคุณจะสามารถถ่ายโอนไปยังที่เก็บและการประมวลผลได้จากทุกที่ที่เรารักษาสิ่งอำนวยความสะดวก (ยกเว้นที่มีให้สำหรับโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="3c677-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="3c677-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายอีเมลหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="3c677-122">ปัญหาที่ไม่คาดฝัน (เช่นรายการที่ไม่สามารถอ่านได้หรือข้อมูลที่เสียหายในสภาพแวดล้อมต้นฉบับ) อาจทำให้ความสามารถของเราในการโยกย้ายบางส่วนของรายการข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="3c677-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่นการเปลี่ยนแปลงไปยังส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชันของบริษัทอื่น (APIs)) อาจทำให้เกิดการเปลี่ยนแปลงความล่าช้าหรือการระงับการใช้บริการการโยกย้ายข้อมูลของเราได้</span><span class="sxs-lookup"><span data-stu-id="3c677-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="3c677-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-124">Migration service availability</span></span>

  - <span data-ttu-id="3c677-125">**สำหรับลูกค้าภาครัฐเชิงพาณิชย์และสหราชอาณาจักร:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง, 7 (7) วันต่อสัปดาห์ (24 ชั่วโมง)</span><span class="sxs-lookup"><span data-stu-id="3c677-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="3c677-126">**สำหรับลูกค้ารัฐบาล/DOD ของสหรัฐอเมริกา:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง5วันทำการ (5) วันทำการ (24x5)</span><span class="sxs-lookup"><span data-stu-id="3c677-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="3c677-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3c677-127">Migration to Exchange Online</span></span>

<span data-ttu-id="3c677-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3c677-129">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและการแลกเปลี่ยนแบบออนไลน์และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="3c677-130">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-130">You create and schedule your migration events.</span></span> <span data-ttu-id="3c677-131">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="3c677-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3c677-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดกำหนดการไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณเพื่อที่จะถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3c677-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="3c677-133">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="3c677-133">Considerations</span></span>

  - <span data-ttu-id="3c677-134">ก่อนการโยกย้ายคุณจะต้องทำการ FastTrack core ปฐมนิเทศสำหรับ Exchange Online ให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="3c677-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="3c677-135">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="3c677-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3c677-136">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="3c677-137">FastTrack จะย้ายไปยังกล่องจดหมาย Office ๓๖๕ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="3c677-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="3c677-138">คุณต้องตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="3c677-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3c677-139">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="3c677-140">สภาพแวดล้อมต้นฉบับแต่ละรายการต้องอยู่ในระดับ service pack (SP) ล่าสุดและ rollup (RU)/cumulative (CU) สำหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="3c677-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="3c677-141">รายชื่อการแจกจ่าย (วัตถุ *MailEnabledGroup* ) และที่ติดต่อภายนอก (วัตถุ *MailEnabledContact* ) ที่มีอยู่ในไดเรกทอรีที่ใช้งานอยู่ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="3c677-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="3c677-142">อย่างไรก็ตามคุณสามารถซิงโครไนซ์ได้โดยใช้การเชื่อมต่อ Azure Active Directory (Azure AD)</span><span class="sxs-lookup"><span data-stu-id="3c677-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="3c677-143">สภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="3c677-143">Source environments</span></span>

<span data-ttu-id="3c677-144">บริการการโยกย้ายข้อมูลของเราจะย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="3c677-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="3c677-145">ฟอเรสต์ที่ใช้งานอยู่ของไดเรกทอรีเดียวหรือหลายฟอเรสต์ที่มี Exchange องค์กรเดียวหรือหลายองค์กร (แต่ละระบบจดหมาย Exchange จะต้องมี Exchange ๒๐๑๐หรือมากกว่า)</span><span class="sxs-lookup"><span data-stu-id="3c677-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="3c677-146">สภาพแวดล้อมอีเมลที่สามารถใช้งาน IMAP เดียวได้</span><span class="sxs-lookup"><span data-stu-id="3c677-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="3c677-147">ระบบ G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="3c677-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="3c677-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="3c677-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3c677-149"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3c677-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3c677-151"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="3c677-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3c677-153"><strong>Exchange ๒๐๑๐, Exchange ๒๐๑๓, Exchange ๒๐๑๖, Exchange ๒๐๑๙</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="3c677-154">
<strong>หมายเหตุ:</strong> สำหรับการอ้างอิง Exchange ภายในองค์กรให้ดูที่<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด</span></a></span><span class="sxs-lookup"><span data-stu-id="3c677-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="3c677-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="3c677-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="3c677-156">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="3c677-156">Emails</span></span></li>
<li><span data-ttu-id="3c677-157">กฎสำหรับกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="3c677-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="3c677-158">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="3c677-158">Delegates</span></span></li>
<li><span data-ttu-id="3c677-159">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="3c677-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3c677-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="3c677-160">Calendar</span></span> </li>
<li> <span data-ttu-id="3c677-161">งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-161">Tasks</span></span> </li>
<li> <span data-ttu-id="3c677-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="3c677-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="3c677-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="3c677-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="3c677-164">เซ็น</span><span class="sxs-lookup"><span data-stu-id="3c677-164">Signatures</span></span> </li>
<li> <span data-ttu-id="3c677-165">ที่เก็บถาวรส่วนบุคคลถูกโยกย้ายด้วยกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="3c677-166">รายการที่สามารถกู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="3c677-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="3c677-167">Public folders</span></span> </li>
<li> <span data-ttu-id="3c677-168">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="3c677-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3c677-169">การบันทึกที่เก็บถาวรหรือโซลูชันที่เก็บถาวรของบริษัทอื่น</span><span class="sxs-lookup"><span data-stu-id="3c677-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="3c677-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-171">เก็บถาวรข้อมูลจากไฟล์ตารางที่เก็บข้อมูลส่วนบุคคล (PST)</span><span class="sxs-lookup"><span data-stu-id="3c677-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="3c677-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3c677-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c677-174"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="3c677-175">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณจะต้องตรงตามข้อกำหนดเบื้องต้นที่อธิบายไว้ในการ<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ดำเนินการการโยกย้าย G suite</a></span><span class="sxs-lookup"><span data-stu-id="3c677-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="3c677-176">แบบเคลื่อนย้ายหรือแบบเป็นฉาก</span><span class="sxs-lookup"><span data-stu-id="3c677-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-177">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="3c677-177">Emails</span></span> </li>
<li> <span data-ttu-id="3c677-178">กล่องจดหมายที่ติดต่อ (ที่อยู่อีเมลที่ไม่เกิน3รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="3c677-179">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="3c677-179">Calendar</span></span> </li>
<li> <span data-ttu-id="3c677-180">ป้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-181">กฎ</span><span class="sxs-lookup"><span data-stu-id="3c677-181">Rules</span></span> </li>
<li> <span data-ttu-id="3c677-182">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="3c677-182">Delegates</span></span> </li>
<li> <span data-ttu-id="3c677-183">เซ็น</span><span class="sxs-lookup"><span data-stu-id="3c677-183">Signatures</span></span> </li>
<li> <span data-ttu-id="3c677-184">งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-184">Tasks</span></span> </li>
<li> <span data-ttu-id="3c677-185">อีเมลหรือสิ่งที่แนบมาที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="3c677-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3c677-186">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-187">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันที่เก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="3c677-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="3c677-188">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="3c677-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="3c677-189">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3c677-190">Google แฮงเอาท์ \*\*</span><span class="sxs-lookup"><span data-stu-id="3c677-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="3c677-191">กลุ่ม Google</span><span class="sxs-lookup"><span data-stu-id="3c677-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="3c677-192">กล่องจดหมายของทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="3c677-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="3c677-193">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3c677-194">การตั้งค่าวันหยุดและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="3c677-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="3c677-195">ปฏิทินที่แชร์สิ่งที่แนบมาในระบบคลาวด์การเชื่อมโยง Google แฮงเอาท์และสีของเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="3c677-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="3c677-196">\*\* การสนทนาแฮงเอาท์ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3c677-197"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="3c677-198">การโยกย้ายโดยใช้เครื่องมือ IMAP4 native</span><span class="sxs-lookup"><span data-stu-id="3c677-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="3c677-199">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="3c677-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="3c677-200">กฎ</span><span class="sxs-lookup"><span data-stu-id="3c677-200">Rules</span></span> </li>
<li> <span data-ttu-id="3c677-201">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="3c677-201">Delegates</span></span> </li>
<li> <span data-ttu-id="3c677-202">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="3c677-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="3c677-203">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-203">External contacts</span></span> </li>
<li> <span data-ttu-id="3c677-204">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="3c677-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="3c677-205">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-206">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="3c677-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3c677-207">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="3c677-207">Calendar</span></span> </li>
<li> <span data-ttu-id="3c677-208">เซ็น</span><span class="sxs-lookup"><span data-stu-id="3c677-208">Signatures</span></span> </li>
<li> <span data-ttu-id="3c677-209">งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-209">Tasks</span></span> </li>
<li> <span data-ttu-id="3c677-210">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="3c677-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3c677-211">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-211">Archive data</span></span> </li>
<li> <span data-ttu-id="3c677-212">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="3c677-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="3c677-213">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3c677-214">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3c677-215">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="3c677-215">FastTrack responsibilities</span></span>

<span data-ttu-id="3c677-216">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3c677-217">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3c677-218">ผู้เชี่ยวชาญ FastTrack ของเรายังดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="3c677-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="3c677-219">ให้คำแนะนำในการช่วยให้คุณเปิดใช้งานการกำหนดเส้นทางจดหมาย SMTP ที่มีอยู่ร่วมกันระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="3c677-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3c677-220">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-220">Your responsibilities</span></span>

<span data-ttu-id="3c677-221">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3c677-222">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3c677-223">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะในการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="3c677-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="3c677-224">กรอกข้อมูล FastTrack core ปฐมนิเทศสำหรับ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3c677-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="3c677-225">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="3c677-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3c677-226">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="3c677-227">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางปฏิบัติของ Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="3c677-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="3c677-228">อ้างอิงไปยังที่ [ทำงานสมัยใหม่](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="3c677-229">ตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="3c677-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3c677-230">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="3c677-231">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของแหล่งข้อมูลแต่ละรายการ (SP) และ rollup (RU)/cumulative update (CU) (CU) ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="3c677-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="3c677-232">กำหนดค่าและตรวจสอบความถูกต้องของการกำหนดเส้นทางจดหมาย SMTP ระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="3c677-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="3c677-233">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นฉบับของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="3c677-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="3c677-234">คุณอาจจำเป็นต้องจำกัดข้อมูลต้นฉบับของคุณไป๘๕ยังเปอร์เซ็นต์ของโควตาของกล่องจดหมายเป้าหมายทั้งนี้ขึ้นอยู่กับแพลตฟอร์มต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="3c677-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="3c677-235">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="3c677-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="3c677-236">ซึ่งรวมถึงแต่ไม่จำกัดเฉพาะสมุดรายชื่อภายในเครื่องข้อมูลในไฟล์ PST ภายในเครื่องกฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="3c677-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="3c677-237">ช่วยให้ผู้ใช้ของคุณมีส่วนของปัญหาการโยกย้ายที่ด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="3c677-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="3c677-238">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3c677-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="3c677-239">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3c677-240">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและ SharePoint Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3c677-241">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-241">You create and schedule your migration events.</span></span> <span data-ttu-id="3c677-242">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="3c677-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3c677-243">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3c677-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="3c677-244">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="3c677-244">Considerations</span></span>

  - <span data-ttu-id="3c677-245">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3c677-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3c677-246">อ้างอิงไปยัง [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="3c677-247">เราขอแนะนำให้คุณจำกัดจำนวนรวมของการโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="3c677-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3c677-248">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-248">Source environment details</span></span>

<span data-ttu-id="3c677-249">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="3c677-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3c677-250">ไฟล์ที่แชร์ (ไฟล์การบล็อกข้อความเซิร์ฟเวอร์ (SMB) บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="3c677-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3c677-251">สภาพแวดล้อม G Suite เดียว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="3c677-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3c677-252">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="3c677-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3c677-253">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="3c677-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3c677-254">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="3c677-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3c677-255"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3c677-256"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3c677-257"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3c677-258"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3c677-259"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3c677-260">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-261">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="3c677-261">Documents</span></span> </li>
<li> <span data-ttu-id="3c677-262">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-263">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="3c677-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c677-264">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="3c677-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c677-265">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-266">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-267">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-267">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-268">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-268">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-269">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-269">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-270">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="3c677-271">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="3c677-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3c677-272">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3c677-273">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3c677-274">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-275">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="3c677-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3c677-276">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-277">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="3c677-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="3c677-278">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="3c677-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3c677-279">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="3c677-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3c677-280">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="3c677-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3c677-281">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="3c677-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3c677-282">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="3c677-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3c677-283">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-284">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="3c677-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3c677-285">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="3c677-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3c677-286">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c677-287"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3c677-288">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-289">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่า) รวมถึงที่มีค่ามากกว่า10เมกะไบต์</span><span class="sxs-lookup"><span data-stu-id="3c677-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="3c677-290">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-291">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-292">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-293">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-294">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-295">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-295">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-296">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-296">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-297">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-297">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-298">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c677-299">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="3c677-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3c677-300">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-301">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="3c677-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c677-302">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3c677-303">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-304">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-305">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="3c677-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c677-306">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c677-307">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-308">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="3c677-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c677-309">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-310">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-311">Google รูปแบบฟอร์มแผนที่และแอปที่เชื่อมต่ออื่นๆ</span><span class="sxs-lookup"><span data-stu-id="3c677-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3c677-312">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="3c677-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3c677-313">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3c677-314">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3c677-315">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3c677-316">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-317">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="3c677-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3c677-318">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-319">ไฟล์ที่ถูกทำเครื่องหมายเป็นแบบจำกัดหรือไม่ copyable</span><span class="sxs-lookup"><span data-stu-id="3c677-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="3c677-320">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3c677-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3c677-322">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-323">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="3c677-323">Documents</span></span> </li>
<li> <span data-ttu-id="3c677-324">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-325">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-326">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-327">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-328">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-329">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-329">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-330">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-330">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-331">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-331">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-332">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c677-333">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3c677-334">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="3c677-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-335">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="3c677-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c677-336">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c677-337">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-338">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-339">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="3c677-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c677-340">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c677-341">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-342">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="3c677-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c677-343">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-344">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-345">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="3c677-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3c677-346">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3c677-347">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3c677-348">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-349">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c677-350"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3c677-351">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-352">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="3c677-352">Documents</span></span> </li>
<li> <span data-ttu-id="3c677-353">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-354">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-355">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-356">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-357">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-358">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-358">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-359">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-359">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-360">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-360">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-361">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c677-362">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="3c677-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3c677-363">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-364">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="3c677-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c677-365">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c677-366">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-367">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-368">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="3c677-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c677-369">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c677-370">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-371">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="3c677-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c677-372">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-373">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="3c677-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3c677-374">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="3c677-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3c677-375">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="3c677-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3c677-376">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="3c677-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3c677-377">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3c677-378">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3c677-379">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="3c677-380">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3c677-381">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="3c677-381">FastTrack responsibilities</span></span>

<span data-ttu-id="3c677-382">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3c677-383">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3c677-384">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-384">Your responsibilities</span></span>

<span data-ttu-id="3c677-385">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3c677-386">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="3c677-387">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้เฉพาะกับการโยกย้าย SharePoint Online ได้ดังนี้</span><span class="sxs-lookup"><span data-stu-id="3c677-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="3c677-388">จัดเตรียมไซต์ทีม SharePoint ทั้งหมดที่จะกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="3c677-389">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="3c677-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="3c677-390">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3c677-391">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3c677-392">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-392">You create and schedule your migration events.</span></span> <span data-ttu-id="3c677-393">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="3c677-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3c677-394">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="3c677-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="3c677-395">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="3c677-395">Considerations</span></span>

  - <span data-ttu-id="3c677-396">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตาของ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="3c677-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="3c677-397">โปรดดูที่ [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="3c677-398">เราขอแนะนำให้คุณจำกัดจำนวนข้อมูลโดยรวมที่คุณโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="3c677-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="3c677-399">FastTrack จะย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="3c677-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="3c677-400">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="3c677-400">Source environment details</span></span>

<span data-ttu-id="3c677-401">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="3c677-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3c677-402">ไฟล์ที่แชร์ (ไฟล์ SMB ที่แชร์บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="3c677-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3c677-403">สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="3c677-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3c677-404">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="3c677-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3c677-405">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="3c677-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3c677-406">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="3c677-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3c677-407"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3c677-408"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3c677-409"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3c677-410"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3c677-411"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3c677-412">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-413">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="3c677-413">Documents</span></span> </li>
<li> <span data-ttu-id="3c677-414">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-415">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="3c677-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c677-416">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="3c677-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3c677-417">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-418">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-419">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-419">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-420">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-420">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-421">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-421">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-422">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3c677-423">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="3c677-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3c677-424">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3c677-425">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3c677-426">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3c677-427">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="3c677-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3c677-428">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-429">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="3c677-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="3c677-430">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="3c677-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3c677-431">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="3c677-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3c677-432">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="3c677-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3c677-433">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="3c677-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3c677-434">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="3c677-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3c677-435">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-436">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="3c677-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3c677-437">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="3c677-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3c677-438">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c677-439"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3c677-440">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-441">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากันรวมถึงที่มีค่ามากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="3c677-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3c677-442">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-443">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-444">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-445">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-446">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-447">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-447">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-448">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-448">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-449">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-449">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-450">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c677-451">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="3c677-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3c677-452">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-453">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="3c677-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c677-454">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3c677-455">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-456">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-457">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="3c677-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c677-458">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c677-459">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-460">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="3c677-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c677-461">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-462">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-463">รูปแบบแผนที่และแอปที่เชื่อมต่ออื่นๆของ Google</span><span class="sxs-lookup"><span data-stu-id="3c677-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3c677-464">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="3c677-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3c677-465">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3c677-466">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3c677-467">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3c677-468">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-469">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="3c677-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3c677-470">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-471">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3c677-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3c677-473">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-474">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="3c677-474">Documents</span></span> </li>
<li> <span data-ttu-id="3c677-475">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-476">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-477">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-478">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-479">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-480">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-480">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-481">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-481">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-482">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-482">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-483">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c677-484">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-485">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="3c677-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c677-486">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c677-487">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-488">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-489">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="3c677-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c677-490">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c677-491">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-492">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="3c677-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c677-493">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-494">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="3c677-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3c677-495">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="3c677-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3c677-496">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3c677-497">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3c677-498">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-499">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3c677-500"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="3c677-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3c677-501">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="3c677-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3c677-502">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="3c677-502">Documents</span></span> </li>
<li> <span data-ttu-id="3c677-503">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3c677-504">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-505">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3c677-506">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="3c677-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3c677-507">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="3c677-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3c677-508">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="3c677-508">Created date</span></span> </li>
<li> <span data-ttu-id="3c677-509">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="3c677-509">Modified date</span></span> </li>
<li> <span data-ttu-id="3c677-510">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-510">Created by</span></span> </li>
<li> <span data-ttu-id="3c677-511">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="3c677-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3c677-512">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="3c677-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3c677-513">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3c677-514">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="3c677-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3c677-515">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="3c677-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3c677-516">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="3c677-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-517">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="3c677-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3c677-518">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="3c677-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3c677-519">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="3c677-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3c677-520">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="3c677-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3c677-521">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="3c677-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="3c677-522">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="3c677-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3c677-523">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="3c677-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3c677-524">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="3c677-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3c677-525">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="3c677-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3c677-526">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="3c677-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3c677-527">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3c677-528">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="3c677-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3c677-529">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="3c677-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3c677-530">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="3c677-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="3c677-531">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="3c677-531">FastTrack responsibilities</span></span>

<span data-ttu-id="3c677-532">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3c677-533">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="3c677-534">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-534">Your responsibilities</span></span>

<span data-ttu-id="3c677-535">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="3c677-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3c677-536">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="3c677-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3c677-537">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="3c677-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="3c677-538">จัดเตรียมไซต์ OneDrive for Business ทั้งหมดที่จะได้รับการกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="3c677-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
