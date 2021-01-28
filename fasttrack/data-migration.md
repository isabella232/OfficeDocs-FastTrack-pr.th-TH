---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016477"
---
# <a name="data-migration"></a><span data-ttu-id="d34ef-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-104">Data Migration</span></span>

<span data-ttu-id="d34ef-105">FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="d34ef-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="d34ef-106">ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="d34ef-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="d34ef-107">**สำหรับผู้เช่า Office ๓๖๕ที่มีสิทธิ์การใช้งาน 150-499**: FastTrack ให้คำแนะนำการโยกย้ายเท่านั้น คุณต้องรับผิดชอบในการดำเนินการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="d34ef-108">เราจะแนะนำคุณเกี่ยวกับเอกสารที่จะช่วยคุณวางแผนและใช้เครื่องมือฟรีเพื่อดำเนินการโยกย้ายแบบบริการตนเอง</span><span class="sxs-lookup"><span data-stu-id="d34ef-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="d34ef-109">**สำหรับผู้เช่า Office ๓๖๕ที่มี๕๐๐หรือสิทธิ์การใช้งานเพิ่มเติม** ให้ทำดังนี้ FastTrack ให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="d34ef-110">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="d34ef-111">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-111">You create and schedule your migration events.</span></span> <span data-ttu-id="d34ef-112">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="d34ef-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนที่จะ9/1/2017 คุณจำเป็นต้องมีสิทธิ์การใช้งาน๑๕๐เท่านั้นที่จะมีคุณสมบัติสำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="d34ef-114">สำหรับแผนการศึกษาเฉพาะผู้ที่ได้รับสิทธิ์การใช้งานคณาจารย์และเจ้าหน้าที่ของคุณเท่านั้นที่มีสิทธิ์สำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="d34ef-115">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="d34ef-115">Considerations</span></span>

  - <span data-ttu-id="d34ef-116">สภาพแวดล้อมต้นฉบับของคุณต้องตรงตามความคาดหวังที่เฉพาะเจาะจงเพื่อโยกย้ายข้อมูลไปยัง Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="d34ef-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="d34ef-117">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) ของข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมแหล่งข้อมูลสำหรับ Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="d34ef-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="d34ef-118">เราจำเป็นต้องมีสิทธิ์การเข้าถึงและสิทธิ์ที่เหมาะสมกับสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="d34ef-119">บริการการโยกย้ายข้อมูลของเราไม่ได้รับการออกแบบหรือไม่เหมาะสมสำหรับข้อมูลภายใต้ข้อกำหนดด้านกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="d34ef-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="d34ef-120">ในขณะที่เราโยกย้ายข้อมูลของคุณจะสามารถถ่ายโอนไปยังที่เก็บและการประมวลผลได้จากทุกที่ที่เรารักษาสิ่งอำนวยความสะดวก (ยกเว้นที่มีให้สำหรับโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="d34ef-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="d34ef-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายอีเมลหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="d34ef-122">ปัญหาที่ไม่คาดฝัน (เช่นรายการที่ไม่สามารถอ่านได้หรือข้อมูลที่เสียหายในสภาพแวดล้อมต้นฉบับ) อาจทำให้ความสามารถของเราในการโยกย้ายบางส่วนของรายการข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="d34ef-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่นการเปลี่ยนแปลงไปยังส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชันของบริษัทอื่น (APIs)) อาจทำให้เกิดการเปลี่ยนแปลงความล่าช้าหรือการระงับการใช้บริการการโยกย้ายข้อมูลของเราได้</span><span class="sxs-lookup"><span data-stu-id="d34ef-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="d34ef-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-124">Migration service availability</span></span>

  - <span data-ttu-id="d34ef-125">**สำหรับลูกค้าภาครัฐเชิงพาณิชย์และสหราชอาณาจักร:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง, 7 (7) วันต่อสัปดาห์ (24 ชั่วโมง)</span><span class="sxs-lookup"><span data-stu-id="d34ef-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="d34ef-126">**สำหรับลูกค้ารัฐบาล/DOD ของสหรัฐอเมริกา:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง5วันทำการ (5) วันทำการ (24x5)</span><span class="sxs-lookup"><span data-stu-id="d34ef-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="d34ef-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d34ef-127">Migration to Exchange Online</span></span>

<span data-ttu-id="d34ef-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="d34ef-129">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและการแลกเปลี่ยนแบบออนไลน์และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="d34ef-130">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-130">You create and schedule your migration events.</span></span> <span data-ttu-id="d34ef-131">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="d34ef-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดกำหนดการไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณเพื่อที่จะถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d34ef-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="d34ef-133">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="d34ef-133">Considerations</span></span>

  - <span data-ttu-id="d34ef-134">ก่อนการโยกย้ายคุณจะต้องทำการ FastTrack core ปฐมนิเทศสำหรับ Exchange Online ให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="d34ef-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="d34ef-135">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="d34ef-136">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="d34ef-137">FastTrack จะย้ายไปยังกล่องจดหมาย Office ๓๖๕ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="d34ef-138">คุณต้องตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="d34ef-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="d34ef-139">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="d34ef-140">สภาพแวดล้อมต้นฉบับแต่ละรายการต้องอยู่ในระดับ service pack (SP) ล่าสุดและ rollup (RU)/cumulative (CU) สำหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="d34ef-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="d34ef-141">รายชื่อการแจกจ่าย (วัตถุ *MailEnabledGroup* ) และที่ติดต่อภายนอก (วัตถุ *MailEnabledContact* ) ที่มีอยู่ในไดเรกทอรีที่ใช้งานอยู่ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="d34ef-142">อย่างไรก็ตามคุณสามารถซิงโครไนซ์ได้โดยใช้การเชื่อมต่อ Azure Active Directory (Azure AD)</span><span class="sxs-lookup"><span data-stu-id="d34ef-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="d34ef-143">สภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="d34ef-143">Source environments</span></span>

<span data-ttu-id="d34ef-144">บริการการโยกย้ายข้อมูลของเราจะย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="d34ef-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="d34ef-145">ฟอเรสต์ที่ใช้งานอยู่ของไดเรกทอรีเดียวหรือหลายฟอเรสต์ที่มี Exchange องค์กรเดียวหรือหลายองค์กร (แต่ละระบบจดหมาย Exchange จะต้องมี Exchange ๒๐๑๐หรือมากกว่า)</span><span class="sxs-lookup"><span data-stu-id="d34ef-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="d34ef-146">สภาพแวดล้อมอีเมลที่สามารถใช้งาน IMAP เดียวได้</span><span class="sxs-lookup"><span data-stu-id="d34ef-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="d34ef-147">ระบบ G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="d34ef-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="d34ef-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="d34ef-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d34ef-149"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="d34ef-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="d34ef-151"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="d34ef-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d34ef-153"><strong>Exchange ๒๐๑๐, Exchange ๒๐๑๓, Exchange ๒๐๑๖, Exchange ๒๐๑๙</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="d34ef-154">
<strong>หมายเหตุ:</strong> สำหรับการอ้างอิง Exchange ภายในองค์กรให้ดูที่<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด</span></a></span><span class="sxs-lookup"><span data-stu-id="d34ef-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="d34ef-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="d34ef-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="d34ef-156">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="d34ef-156">Emails</span></span></li>
<li><span data-ttu-id="d34ef-157">กฎสำหรับกล่องจดหมายฝั่งเซิร์ฟเวอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="d34ef-158">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="d34ef-158">Delegates</span></span></li>
<li><span data-ttu-id="d34ef-159">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="d34ef-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="d34ef-160">Calendar</span></span> </li>
<li> <span data-ttu-id="d34ef-161">งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-161">Tasks</span></span> </li>
<li> <span data-ttu-id="d34ef-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="d34ef-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="d34ef-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="d34ef-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="d34ef-164">เซ็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-164">Signatures</span></span> </li>
<li> <span data-ttu-id="d34ef-165">ที่เก็บถาวรส่วนบุคคลถูกโยกย้ายด้วยกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="d34ef-166">รายการที่สามารถกู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="d34ef-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-167">Public folders</span></span> </li>
<li> <span data-ttu-id="d34ef-168">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="d34ef-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="d34ef-169">การบันทึกที่เก็บถาวรหรือโซลูชันที่เก็บถาวรของบริษัทอื่น</span><span class="sxs-lookup"><span data-stu-id="d34ef-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="d34ef-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-171">เก็บถาวรข้อมูลจากไฟล์ตารางที่เก็บข้อมูลส่วนบุคคล (PST)</span><span class="sxs-lookup"><span data-stu-id="d34ef-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="d34ef-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="d34ef-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="d34ef-174">กฎสำหรับกล่องจดหมายฝั่งไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="d34ef-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d34ef-175"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="d34ef-176">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณจะต้องตรงตามข้อกำหนดเบื้องต้นที่อธิบายไว้ในการ<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ดำเนินการการโยกย้าย G suite</a></span><span class="sxs-lookup"><span data-stu-id="d34ef-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="d34ef-177">แบบเคลื่อนย้ายหรือแบบเป็นฉาก</span><span class="sxs-lookup"><span data-stu-id="d34ef-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-178">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="d34ef-178">Emails</span></span> </li>
<li> <span data-ttu-id="d34ef-179">กล่องจดหมายที่ติดต่อ (ที่อยู่อีเมลที่ไม่เกิน3รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="d34ef-180">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="d34ef-180">Calendar</span></span> </li>
<li> <span data-ttu-id="d34ef-181">ป้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-182">กฎ</span><span class="sxs-lookup"><span data-stu-id="d34ef-182">Rules</span></span> </li>
<li> <span data-ttu-id="d34ef-183">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="d34ef-183">Delegates</span></span> </li>
<li> <span data-ttu-id="d34ef-184">เซ็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-184">Signatures</span></span> </li>
<li> <span data-ttu-id="d34ef-185">งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-185">Tasks</span></span> </li>
<li> <span data-ttu-id="d34ef-186">อีเมลหรือสิ่งที่แนบมาที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="d34ef-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="d34ef-187">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-188">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันที่เก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="d34ef-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="d34ef-189">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="d34ef-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="d34ef-190">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="d34ef-191">Google แฮงเอาท์ \*\*</span><span class="sxs-lookup"><span data-stu-id="d34ef-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="d34ef-192">กลุ่ม Google</span><span class="sxs-lookup"><span data-stu-id="d34ef-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="d34ef-193">กล่องจดหมายของทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="d34ef-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="d34ef-194">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="d34ef-195">การตั้งค่าวันหยุดและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="d34ef-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="d34ef-196">ปฏิทินที่แชร์สิ่งที่แนบมาในระบบคลาวด์การเชื่อมโยง Google แฮงเอาท์และสีของเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="d34ef-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="d34ef-197">\*\* การสนทนาแฮงเอาท์ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d34ef-198"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="d34ef-199">การโยกย้ายโดยใช้เครื่องมือ IMAP4 native</span><span class="sxs-lookup"><span data-stu-id="d34ef-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="d34ef-200">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="d34ef-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="d34ef-201">กฎ</span><span class="sxs-lookup"><span data-stu-id="d34ef-201">Rules</span></span> </li>
<li> <span data-ttu-id="d34ef-202">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="d34ef-202">Delegates</span></span> </li>
<li> <span data-ttu-id="d34ef-203">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="d34ef-204">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-204">External contacts</span></span> </li>
<li> <span data-ttu-id="d34ef-205">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="d34ef-206">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-207">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="d34ef-208">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="d34ef-208">Calendar</span></span> </li>
<li> <span data-ttu-id="d34ef-209">เซ็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-209">Signatures</span></span> </li>
<li> <span data-ttu-id="d34ef-210">งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-210">Tasks</span></span> </li>
<li> <span data-ttu-id="d34ef-211">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="d34ef-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="d34ef-212">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-212">Archive data</span></span> </li>
<li> <span data-ttu-id="d34ef-213">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="d34ef-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="d34ef-214">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="d34ef-215">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="d34ef-216">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d34ef-216">FastTrack responsibilities</span></span>

<span data-ttu-id="d34ef-217">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="d34ef-218">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="d34ef-219">ผู้เชี่ยวชาญ FastTrack ของเรายังดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="d34ef-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="d34ef-220">ให้คำแนะนำในการช่วยให้คุณเปิดใช้งานการกำหนดเส้นทางจดหมาย SMTP ที่มีอยู่ร่วมกันระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="d34ef-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="d34ef-221">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-221">Your responsibilities</span></span>

<span data-ttu-id="d34ef-222">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="d34ef-223">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="d34ef-224">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะในการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="d34ef-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="d34ef-225">กรอกข้อมูล FastTrack core ปฐมนิเทศสำหรับ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="d34ef-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="d34ef-226">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="d34ef-227">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="d34ef-228">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางปฏิบัติของ Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="d34ef-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="d34ef-229">อ้างอิงไปยังที่ [ทำงานสมัยใหม่](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="d34ef-230">ตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="d34ef-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="d34ef-231">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="d34ef-232">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของแหล่งข้อมูลแต่ละรายการ (SP) และ rollup (RU)/cumulative update (CU) (CU) ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="d34ef-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="d34ef-233">กำหนดค่าและตรวจสอบความถูกต้องของการกำหนดเส้นทางจดหมาย SMTP ระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="d34ef-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="d34ef-234">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นฉบับของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="d34ef-235">คุณอาจจำเป็นต้องจำกัดข้อมูลต้นฉบับของคุณไป๘๕ยังเปอร์เซ็นต์ของโควตาของกล่องจดหมายเป้าหมายทั้งนี้ขึ้นอยู่กับแพลตฟอร์มต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="d34ef-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="d34ef-236">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="d34ef-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="d34ef-237">ซึ่งรวมถึงแต่ไม่จำกัดเฉพาะสมุดรายชื่อภายในเครื่องข้อมูลในไฟล์ PST ภายในเครื่องกฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="d34ef-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="d34ef-238">ช่วยให้ผู้ใช้ของคุณมีส่วนของปัญหาการโยกย้ายที่ด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="d34ef-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="d34ef-239">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="d34ef-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="d34ef-240">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="d34ef-241">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและ SharePoint Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="d34ef-242">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-242">You create and schedule your migration events.</span></span> <span data-ttu-id="d34ef-243">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="d34ef-244">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="d34ef-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="d34ef-245">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="d34ef-245">Considerations</span></span>

  - <span data-ttu-id="d34ef-246">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="d34ef-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="d34ef-247">อ้างอิงไปยัง [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="d34ef-248">เราขอแนะนำให้คุณจำกัดจำนวนรวมของการโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="d34ef-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="d34ef-249">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-249">Source environment details</span></span>

<span data-ttu-id="d34ef-250">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="d34ef-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="d34ef-251">ไฟล์ที่แชร์ (ไฟล์การบล็อกข้อความเซิร์ฟเวอร์ (SMB) บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="d34ef-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="d34ef-252">สภาพแวดล้อม G Suite เดียว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="d34ef-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="d34ef-253">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="d34ef-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="d34ef-254">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="d34ef-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="d34ef-255">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="d34ef-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="d34ef-256"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="d34ef-257"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="d34ef-258"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="d34ef-259"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d34ef-260"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="d34ef-261">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-262">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="d34ef-262">Documents</span></span> </li>
<li> <span data-ttu-id="d34ef-263">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-264">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="d34ef-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d34ef-265">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="d34ef-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d34ef-266">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-267">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-268">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-268">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-269">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-269">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-270">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-270">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-271">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="d34ef-272">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="d34ef-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="d34ef-273">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="d34ef-274">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="d34ef-275">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-276">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="d34ef-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="d34ef-277">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-278">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="d34ef-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="d34ef-279">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="d34ef-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="d34ef-280">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="d34ef-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="d34ef-281">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="d34ef-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="d34ef-282">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="d34ef-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="d34ef-283">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="d34ef-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="d34ef-284">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-285">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="d34ef-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="d34ef-286">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="d34ef-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="d34ef-287">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d34ef-288"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="d34ef-289">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-290">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่า) รวมถึงที่มีค่ามากกว่า10เมกะไบต์</span><span class="sxs-lookup"><span data-stu-id="d34ef-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="d34ef-291">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-292">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-293">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-294">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-295">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-296">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-296">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-297">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-297">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-298">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-298">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-299">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d34ef-300">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="d34ef-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="d34ef-301">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-302">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d34ef-303">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="d34ef-304">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-305">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-306">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="d34ef-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d34ef-307">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d34ef-308">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-309">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="d34ef-310">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-311">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-312">Google รูปแบบฟอร์มแผนที่และแอปที่เชื่อมต่ออื่นๆ</span><span class="sxs-lookup"><span data-stu-id="d34ef-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="d34ef-313">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="d34ef-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="d34ef-314">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="d34ef-315">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="d34ef-316">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="d34ef-317">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-318">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="d34ef-319">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-320">ไฟล์ที่ถูกทำเครื่องหมายเป็นแบบจำกัดหรือไม่ copyable</span><span class="sxs-lookup"><span data-stu-id="d34ef-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="d34ef-321">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d34ef-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="d34ef-323">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-324">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="d34ef-324">Documents</span></span> </li>
<li> <span data-ttu-id="d34ef-325">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-326">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-327">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-328">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-329">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-330">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-330">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-331">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-331">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-332">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-332">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-333">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d34ef-334">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="d34ef-335">บันทึกย่อของกล่อง (แปลงเป็นรูปแบบเอกสาร Word)</span><span class="sxs-lookup"><span data-stu-id="d34ef-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-336">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d34ef-337">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d34ef-338">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-339">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-340">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="d34ef-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="d34ef-341">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d34ef-342">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-343">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="d34ef-344">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-345">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-346">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="d34ef-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="d34ef-347">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="d34ef-348">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="d34ef-349">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-350">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d34ef-351"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="d34ef-352">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-353">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="d34ef-353">Documents</span></span> </li>
<li> <span data-ttu-id="d34ef-354">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-355">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-356">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-357">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-358">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-359">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-359">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-360">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-360">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-361">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-361">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-362">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d34ef-363">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="d34ef-364">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-365">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d34ef-366">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d34ef-367">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-368">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-369">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="d34ef-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d34ef-370">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d34ef-371">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-372">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="d34ef-373">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-374">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="d34ef-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="d34ef-375">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="d34ef-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="d34ef-376">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="d34ef-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="d34ef-377">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="d34ef-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="d34ef-378">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="d34ef-379">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="d34ef-380">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="d34ef-381">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="d34ef-382">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d34ef-382">FastTrack responsibilities</span></span>

<span data-ttu-id="d34ef-383">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="d34ef-384">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="d34ef-385">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-385">Your responsibilities</span></span>

<span data-ttu-id="d34ef-386">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="d34ef-387">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="d34ef-388">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้เฉพาะกับการโยกย้าย SharePoint Online ได้ดังนี้</span><span class="sxs-lookup"><span data-stu-id="d34ef-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="d34ef-389">จัดเตรียมไซต์ทีม SharePoint ทั้งหมดที่จะกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="d34ef-390">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="d34ef-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="d34ef-391">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="d34ef-392">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="d34ef-393">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-393">You create and schedule your migration events.</span></span> <span data-ttu-id="d34ef-394">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="d34ef-395">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="d34ef-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="d34ef-396">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="d34ef-396">Considerations</span></span>

  - <span data-ttu-id="d34ef-397">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตาของ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="d34ef-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="d34ef-398">โปรดดูที่ [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="d34ef-399">เราขอแนะนำให้คุณจำกัดจำนวนข้อมูลโดยรวมที่คุณโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="d34ef-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="d34ef-400">FastTrack จะย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="d34ef-401">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d34ef-401">Source environment details</span></span>

<span data-ttu-id="d34ef-402">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="d34ef-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="d34ef-403">ไฟล์ที่แชร์ (ไฟล์ SMB ที่แชร์บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="d34ef-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="d34ef-404">สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="d34ef-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="d34ef-405">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="d34ef-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="d34ef-406">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="d34ef-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="d34ef-407">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="d34ef-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="d34ef-408"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="d34ef-409"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="d34ef-410"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="d34ef-411"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="d34ef-412"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="d34ef-413">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-414">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="d34ef-414">Documents</span></span> </li>
<li> <span data-ttu-id="d34ef-415">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-416">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="d34ef-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d34ef-417">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="d34ef-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="d34ef-418">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-419">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-420">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-420">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-421">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-421">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-422">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-422">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-423">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="d34ef-424">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="d34ef-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="d34ef-425">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="d34ef-426">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="d34ef-427">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="d34ef-428">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="d34ef-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="d34ef-429">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-430">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="d34ef-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="d34ef-431">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="d34ef-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="d34ef-432">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="d34ef-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="d34ef-433">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="d34ef-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="d34ef-434">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="d34ef-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="d34ef-435">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="d34ef-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="d34ef-436">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-437">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="d34ef-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="d34ef-438">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="d34ef-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="d34ef-439">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d34ef-440"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="d34ef-441">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-442">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากันรวมถึงที่มีค่ามากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="d34ef-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="d34ef-443">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-444">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-445">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-446">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-447">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-448">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-448">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-449">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-449">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-450">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-450">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-451">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d34ef-452">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="d34ef-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="d34ef-453">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-454">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d34ef-455">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="d34ef-456">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-457">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-458">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="d34ef-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d34ef-459">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d34ef-460">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-461">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="d34ef-462">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-463">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-464">รูปแบบแผนที่และแอปที่เชื่อมต่ออื่นๆของ Google</span><span class="sxs-lookup"><span data-stu-id="d34ef-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="d34ef-465">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="d34ef-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="d34ef-466">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="d34ef-467">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="d34ef-468">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="d34ef-469">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-470">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="d34ef-471">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-472">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="d34ef-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="d34ef-474">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-475">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="d34ef-475">Documents</span></span> </li>
<li> <span data-ttu-id="d34ef-476">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-477">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-478">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-479">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-480">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-481">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-481">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-482">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-482">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-483">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-483">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-484">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d34ef-485">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-486">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d34ef-487">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d34ef-488">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-489">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-490">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="d34ef-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="d34ef-491">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d34ef-492">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-493">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="d34ef-494">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-495">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="d34ef-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="d34ef-496">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="d34ef-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="d34ef-497">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="d34ef-498">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="d34ef-499">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-500">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="d34ef-501"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="d34ef-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="d34ef-502">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="d34ef-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="d34ef-503">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="d34ef-503">Documents</span></span> </li>
<li> <span data-ttu-id="d34ef-504">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="d34ef-505">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-506">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-507">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="d34ef-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="d34ef-508">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="d34ef-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="d34ef-509">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="d34ef-509">Created date</span></span> </li>
<li> <span data-ttu-id="d34ef-510">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="d34ef-510">Modified date</span></span> </li>
<li> <span data-ttu-id="d34ef-511">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-511">Created by</span></span> </li>
<li> <span data-ttu-id="d34ef-512">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="d34ef-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="d34ef-513">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="d34ef-514">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="d34ef-515">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="d34ef-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="d34ef-516">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="d34ef-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="d34ef-517">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d34ef-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-518">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="d34ef-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="d34ef-519">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="d34ef-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="d34ef-520">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="d34ef-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="d34ef-521">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="d34ef-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="d34ef-522">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="d34ef-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="d34ef-523">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="d34ef-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="d34ef-524">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="d34ef-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="d34ef-525">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="d34ef-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="d34ef-526">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="d34ef-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="d34ef-527">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="d34ef-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="d34ef-528">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="d34ef-529">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="d34ef-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="d34ef-530">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="d34ef-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="d34ef-531">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="d34ef-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="d34ef-532">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d34ef-532">FastTrack responsibilities</span></span>

<span data-ttu-id="d34ef-533">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="d34ef-534">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="d34ef-535">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-535">Your responsibilities</span></span>

<span data-ttu-id="d34ef-536">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="d34ef-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="d34ef-537">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="d34ef-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="d34ef-538">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="d34ef-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="d34ef-539">จัดเตรียมไซต์ OneDrive for Business ทั้งหมดที่จะได้รับการกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="d34ef-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
