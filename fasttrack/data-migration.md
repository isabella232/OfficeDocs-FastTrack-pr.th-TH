---
title: การโยกย้ายข้อมูล
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business) ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827663"
---
# <a name="data-migration"></a><span data-ttu-id="0f108-104">การโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-104">Data Migration</span></span>

<span data-ttu-id="0f108-105">FastTrack สามารถช่วยให้คุณโยกย้ายอีเมลและข้อมูลไฟล์ในสภาพแวดล้อมต้นฉบับของคุณไปยัง Office ๓๖๕ (Exchange Online, SharePoint Online และ OneDrive for Business)</span><span class="sxs-lookup"><span data-stu-id="0f108-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="0f108-106">ชนิดของความช่วยเหลือที่เราให้ขึ้นอยู่กับจำนวนสิทธิ์การใช้งาน Office ๓๖๕ของคุณ:</span><span class="sxs-lookup"><span data-stu-id="0f108-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="0f108-107">**สำหรับผู้เช่า Office ๓๖๕ที่มีสิทธิ์การใช้งาน 150-499** : FastTrack ให้คำแนะนำการโยกย้ายเท่านั้น คุณต้องรับผิดชอบในการดำเนินการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-107">**For Office 365 tenants with 150-499 licenses** : FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="0f108-108">เราจะแนะนำคุณเกี่ยวกับเอกสารที่จะช่วยคุณวางแผนและใช้เครื่องมือฟรีเพื่อดำเนินการโยกย้ายแบบบริการตนเอง</span><span class="sxs-lookup"><span data-stu-id="0f108-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="0f108-109">**สำหรับผู้เช่า Office ๓๖๕ที่มี๕๐๐หรือสิทธิ์การใช้งานเพิ่มเติม** ให้ทำดังนี้ FastTrack ให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-109">**For Office 365 tenants with 500 or more licenses** : FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="0f108-110">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="0f108-111">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-111">You create and schedule your migration events.</span></span> <span data-ttu-id="0f108-112">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="0f108-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="0f108-113">ถ้าคุณซื้อหรือต่ออายุแผนเชิงพาณิชย์ก่อนที่จะ9/1/2017 คุณจำเป็นต้องมีสิทธิ์การใช้งาน๑๕๐เท่านั้นที่จะมีคุณสมบัติสำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="0f108-114">สำหรับแผนการศึกษาเฉพาะผู้ที่ได้รับสิทธิ์การใช้งานคณาจารย์และเจ้าหน้าที่ของคุณเท่านั้นที่มีสิทธิ์สำหรับบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="0f108-115">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="0f108-115">Considerations</span></span>

  - <span data-ttu-id="0f108-116">สภาพแวดล้อมต้นฉบับของคุณต้องตรงตามความคาดหวังที่เฉพาะเจาะจงเพื่อโยกย้ายข้อมูลไปยัง Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="0f108-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="0f108-117">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) ของข้อมูลเพิ่มเติมเกี่ยวกับความคาดหวังของสภาพแวดล้อมแหล่งข้อมูลสำหรับ Exchange, SharePoint และ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="0f108-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="0f108-118">เราจำเป็นต้องมีสิทธิ์การเข้าถึงและสิทธิ์ที่เหมาะสมกับสภาพแวดล้อมต้นฉบับของคุณและผู้เช่า Office ๓๖๕เพื่อให้บริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="0f108-119">บริการการโยกย้ายข้อมูลของเราไม่ได้รับการออกแบบหรือไม่เหมาะสมสำหรับข้อมูลภายใต้ข้อกำหนดด้านกฎหมายหรือข้อบังคับพิเศษ</span><span class="sxs-lookup"><span data-stu-id="0f108-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="0f108-120">ในขณะที่เราโยกย้ายข้อมูลของคุณจะสามารถถ่ายโอนไปยังที่เก็บและการประมวลผลได้จากทุกที่ที่เรารักษาสิ่งอำนวยความสะดวก (ยกเว้นที่มีให้สำหรับโครงการการโยกย้าย FastTrack ของคุณ)</span><span class="sxs-lookup"><span data-stu-id="0f108-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="0f108-121">เราไม่สามารถรับประกันความเร็วของการโยกย้ายอีเมลหรือไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="0f108-122">ปัญหาที่ไม่คาดฝัน (เช่นรายการที่ไม่สามารถอ่านได้หรือข้อมูลที่เสียหายในสภาพแวดล้อมต้นฉบับ) อาจทำให้ความสามารถของเราในการโยกย้ายบางส่วนของรายการข้อมูลของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="0f108-123">ปัจจัยภายนอกที่อยู่นอกเหนือการควบคุมของเรา (เช่นการเปลี่ยนแปลงไปยังส่วนติดต่อการเขียนโปรแกรมแอปพลิเคชันของบริษัทอื่น (APIs)) อาจทำให้เกิดการเปลี่ยนแปลงความล่าช้าหรือการระงับการใช้บริการการโยกย้ายข้อมูลของเราได้</span><span class="sxs-lookup"><span data-stu-id="0f108-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="0f108-124">ความพร้อมใช้งานของบริการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-124">Migration service availability</span></span>

  - <span data-ttu-id="0f108-125">**สำหรับลูกค้าภาครัฐเชิงพาณิชย์และสหราชอาณาจักร:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง, 7 (7) วันต่อสัปดาห์ (24 ชั่วโมง)</span><span class="sxs-lookup"><span data-stu-id="0f108-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="0f108-126">**สำหรับลูกค้ารัฐบาล/DOD ของสหรัฐอเมริกา:** เรามีบริการการโอนข้อมูลบริการตลอด24ชั่วโมง5วันทำการ (5) วันทำการ (24x5)</span><span class="sxs-lookup"><span data-stu-id="0f108-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="0f108-127">การโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="0f108-127">Migration to Exchange Online</span></span>

<span data-ttu-id="0f108-128">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายอีเมลของคุณไปยัง Exchange Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0f108-129">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและการแลกเปลี่ยนแบบออนไลน์และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายกล่องจดหมายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="0f108-130">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-130">You create and schedule your migration events.</span></span> <span data-ttu-id="0f108-131">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="0f108-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0f108-132">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังจดหมายจากกล่องจดหมายที่จัดกำหนดการไว้อย่างเหมาะสมและที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณเพื่อที่จะถูกโยกย้ายไปยัง Exchange Online</span><span class="sxs-lookup"><span data-stu-id="0f108-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="0f108-133">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="0f108-133">Considerations</span></span>

  - <span data-ttu-id="0f108-134">ก่อนการโยกย้ายคุณจะต้องทำการ FastTrack core ปฐมนิเทศสำหรับ Exchange Online ให้เสร็จสมบูรณ์</span><span class="sxs-lookup"><span data-stu-id="0f108-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="0f108-135">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="0f108-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="0f108-136">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="0f108-137">FastTrack จะย้ายไปยังกล่องจดหมาย Office ๓๖๕ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="0f108-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="0f108-138">คุณต้องตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="0f108-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="0f108-139">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="0f108-140">สภาพแวดล้อมต้นฉบับแต่ละรายการต้องอยู่ในระดับ service pack (SP) ล่าสุดและ rollup (RU)/cumulative (CU) สำหรับผลิตภัณฑ์ที่เกี่ยวข้องในสภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="0f108-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="0f108-141">รายชื่อการแจกจ่าย (วัตถุ *MailEnabledGroup* ) และที่ติดต่อภายนอก (วัตถุ *MailEnabledContact* ) ที่มีอยู่ในไดเรกทอรีที่ใช้งานอยู่ภายในองค์กรของคุณไม่ได้เป็นส่วนหนึ่งของการโยกย้ายข้อมูลในกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="0f108-141">Distribution lists ( *MailEnabledGroup* objects) and external contacts ( *MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="0f108-142">อย่างไรก็ตามคุณสามารถซิงโครไนซ์ได้โดยใช้การเชื่อมต่อ Azure Active Directory (Azure AD)</span><span class="sxs-lookup"><span data-stu-id="0f108-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="0f108-143">สภาพแวดล้อมต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="0f108-143">Source environments</span></span>

<span data-ttu-id="0f108-144">บริการการโยกย้ายข้อมูลของเราจะย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="0f108-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="0f108-145">ฟอเรสต์ที่ใช้งานอยู่ของไดเรกทอรีเดียวหรือหลายฟอเรสต์ที่มี Exchange องค์กรเดียวหรือหลายองค์กร (แต่ละระบบจดหมาย Exchange จะต้องมี Exchange ๒๐๑๐หรือมากกว่า)</span><span class="sxs-lookup"><span data-stu-id="0f108-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="0f108-146">สภาพแวดล้อมอีเมลที่สามารถใช้งาน IMAP เดียวได้</span><span class="sxs-lookup"><span data-stu-id="0f108-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="0f108-147">ระบบ G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="0f108-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="0f108-148">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="0f108-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="0f108-149"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="0f108-150"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="0f108-151"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="0f108-152"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0f108-153"><strong>Exchange ๒๐๑๐, Exchange ๒๐๑๓, Exchange ๒๐๑๖, Exchange ๒๐๑๙</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="0f108-154">
<strong>หมายเหตุ:</strong> สำหรับการอ้างอิง Exchange ภายในองค์กรให้ดูที่<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด</span></a></span><span class="sxs-lookup"><span data-stu-id="0f108-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="0f108-155">การโยกย้ายด้วยการปรับใช้แบบไฮบริด</span><span class="sxs-lookup"><span data-stu-id="0f108-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="0f108-156">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="0f108-156">Emails</span></span></li>
<li><span data-ttu-id="0f108-157">กฎสำหรับกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="0f108-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="0f108-158">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="0f108-158">Delegates</span></span></li>
<li><span data-ttu-id="0f108-159">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="0f108-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="0f108-160">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="0f108-160">Calendar</span></span> </li>
<li> <span data-ttu-id="0f108-161">งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-161">Tasks</span></span> </li>
<li> <span data-ttu-id="0f108-162">อีเมลที่มีการจัดการสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="0f108-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="0f108-163">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="0f108-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="0f108-164">เซ็น</span><span class="sxs-lookup"><span data-stu-id="0f108-164">Signatures</span></span> </li>
<li> <span data-ttu-id="0f108-165">ที่เก็บถาวรส่วนบุคคลถูกโยกย้ายด้วยกล่องจดหมายของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="0f108-166">รายการที่สามารถกู้คืนได้</span><span class="sxs-lookup"><span data-stu-id="0f108-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-167">โฟลเดอร์สาธารณะ</span><span class="sxs-lookup"><span data-stu-id="0f108-167">Public folders</span></span> </li>
<li> <span data-ttu-id="0f108-168">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="0f108-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0f108-169">การบันทึกที่เก็บถาวรหรือโซลูชันที่เก็บถาวรของบริษัทอื่น</span><span class="sxs-lookup"><span data-stu-id="0f108-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="0f108-170">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-171">เก็บถาวรข้อมูลจากไฟล์ตารางที่เก็บข้อมูลส่วนบุคคล (PST)</span><span class="sxs-lookup"><span data-stu-id="0f108-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="0f108-172">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0f108-173">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0f108-174"><strong>สภาพแวดล้อม G Suite (Gmail, ที่ติดต่อและปฏิทินเท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="0f108-175">
<strong>หมายเหตุ:</strong> สภาพแวดล้อม G Suite ของคุณจะต้องตรงตามข้อกำหนดเบื้องต้นที่อธิบายไว้ในการ<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">ดำเนินการการโยกย้าย G suite</a></span><span class="sxs-lookup"><span data-stu-id="0f108-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="0f108-176">แบบเคลื่อนย้ายหรือแบบเป็นฉาก</span><span class="sxs-lookup"><span data-stu-id="0f108-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-177">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="0f108-177">Emails</span></span> </li>
<li> <span data-ttu-id="0f108-178">กล่องจดหมายที่ติดต่อ (ที่อยู่อีเมลที่ไม่เกิน3รายการต่อที่ติดต่อจะถูกโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="0f108-179">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="0f108-179">Calendar</span></span> </li>
<li> <span data-ttu-id="0f108-180">ป้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-181">กฎ</span><span class="sxs-lookup"><span data-stu-id="0f108-181">Rules</span></span> </li>
<li> <span data-ttu-id="0f108-182">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="0f108-182">Delegates</span></span> </li>
<li> <span data-ttu-id="0f108-183">เซ็น</span><span class="sxs-lookup"><span data-stu-id="0f108-183">Signatures</span></span> </li>
<li> <span data-ttu-id="0f108-184">งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-184">Tasks</span></span> </li>
<li> <span data-ttu-id="0f108-185">อีเมลหรือสิ่งที่แนบมาที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="0f108-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0f108-186">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-187">เก็บถาวรข้อมูลจากไฟล์ PST หรือโซลูชันที่เก็บถาวรของบริษัทอื่น (ตัวอย่างเช่น Google Vault)</span><span class="sxs-lookup"><span data-stu-id="0f108-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="0f108-188">สิทธิ์ที่มีการจัดการหรืออีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="0f108-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="0f108-189">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0f108-190">Google แฮงเอาท์ \*\*</span><span class="sxs-lookup"><span data-stu-id="0f108-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="0f108-191">กลุ่ม Google</span><span class="sxs-lookup"><span data-stu-id="0f108-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="0f108-192">กล่องจดหมายของทรัพยากร</span><span class="sxs-lookup"><span data-stu-id="0f108-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="0f108-193">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="0f108-194">การตั้งค่าวันหยุดและการตั้งค่าการตอบกลับอัตโนมัติ</span><span class="sxs-lookup"><span data-stu-id="0f108-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="0f108-195">ปฏิทินที่แชร์สิ่งที่แนบมาในระบบคลาวด์การเชื่อมโยง Google แฮงเอาท์และสีของเหตุการณ์</span><span class="sxs-lookup"><span data-stu-id="0f108-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="0f108-196">\*\* การสนทนาแฮงเอาท์ที่บันทึกเป็นป้ายชื่อจะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0f108-197"><strong>แหล่งข้อมูล IMAP4 (เช่น Domino, GroupWise หรือ Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="0f108-198">การโยกย้ายโดยใช้เครื่องมือ IMAP4 native</span><span class="sxs-lookup"><span data-stu-id="0f108-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="0f108-199">อีเมลที่</span><span class="sxs-lookup"><span data-stu-id="0f108-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="0f108-200">กฎ</span><span class="sxs-lookup"><span data-stu-id="0f108-200">Rules</span></span> </li>
<li> <span data-ttu-id="0f108-201">ผู้มอบสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="0f108-201">Delegates</span></span> </li>
<li> <span data-ttu-id="0f108-202">รายชื่อการแจกจ่าย</span><span class="sxs-lookup"><span data-stu-id="0f108-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="0f108-203">ที่ติดต่อภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-203">External contacts</span></span> </li>
<li> <span data-ttu-id="0f108-204">ผู้ใช้ที่เปิดใช้งานจดหมาย</span><span class="sxs-lookup"><span data-stu-id="0f108-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="0f108-205">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-206">ที่ติดต่อของกล่องจดหมาย</span><span class="sxs-lookup"><span data-stu-id="0f108-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="0f108-207">ปฏิทิน</span><span class="sxs-lookup"><span data-stu-id="0f108-207">Calendar</span></span> </li>
<li> <span data-ttu-id="0f108-208">เซ็น</span><span class="sxs-lookup"><span data-stu-id="0f108-208">Signatures</span></span> </li>
<li> <span data-ttu-id="0f108-209">งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-209">Tasks</span></span> </li>
<li> <span data-ttu-id="0f108-210">อีเมลใดๆที่เกินขีดจำกัดขนาดของข้อความ</span><span class="sxs-lookup"><span data-stu-id="0f108-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="0f108-211">เก็บถาวรข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-211">Archive data</span></span> </li>
<li> <span data-ttu-id="0f108-212">อีเมลที่เข้ารหัสลับ</span><span class="sxs-lookup"><span data-stu-id="0f108-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="0f108-213">รายการที่เสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="0f108-214">กล่องจดหมายที่ไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0f108-215">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="0f108-215">FastTrack responsibilities</span></span>

<span data-ttu-id="0f108-216">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0f108-217">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0f108-218">ผู้เชี่ยวชาญ FastTrack ของเรายังดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="0f108-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="0f108-219">ให้คำแนะนำในการช่วยให้คุณเปิดใช้งานการกำหนดเส้นทางจดหมาย SMTP ที่มีอยู่ร่วมกันระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="0f108-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0f108-220">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-220">Your responsibilities</span></span>

<span data-ttu-id="0f108-221">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0f108-222">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0f108-223">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะในการโยกย้าย Exchange ดังนี้</span><span class="sxs-lookup"><span data-stu-id="0f108-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="0f108-224">กรอกข้อมูล FastTrack core ปฐมนิเทศสำหรับ Exchange Online</span><span class="sxs-lookup"><span data-stu-id="0f108-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="0f108-225">ถ้าคุณดำเนินการปฐมนิเทศด้วยตัวคุณเองคุณต้องผ่านการตรวจสอบและข้อกำหนดเบื้องต้นที่จำเป็น</span><span class="sxs-lookup"><span data-stu-id="0f108-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="0f108-226">อ้างอิงถึง [ผลิตภัณฑ์และความสามารถ](products-and-capabilities.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="0f108-227">ติดตั้งซอฟต์แวร์ไคลเอ็นต์ระดับที่เหมาะสมตามแนวทางปฏิบัติของ Office ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="0f108-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="0f108-228">อ้างอิงไปยังที่ [ทำงานสมัยใหม่](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="0f108-229">ตอบสนองความต้องการที่เฉพาะเจาะจงถ้าคุณต้องการโยกย้ายจากสภาพแวดล้อม Exchange ภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="0f108-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="0f108-230">ดู [ข้อกำหนดเบื้องต้นของการปรับใช้แบบไฮบริด](https://go.microsoft.com/fwlink/?LinkId=787528) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="0f108-231">ตรวจสอบให้แน่ใจว่าสภาพแวดล้อมของแหล่งข้อมูลแต่ละรายการ (SP) และ rollup (RU)/cumulative update (CU) (CU) ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="0f108-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="0f108-232">กำหนดค่าและตรวจสอบความถูกต้องของการกำหนดเส้นทางจดหมาย SMTP ระหว่างสภาพแวดล้อมต้นฉบับของคุณและ Exchange Online ถ้าเกี่ยวข้อง</span><span class="sxs-lookup"><span data-stu-id="0f108-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="0f108-233">ตรวจสอบให้แน่ใจว่าขนาดกล่องจดหมายต้นฉบับของคุณไม่เกินโควตากล่องจดหมายเป้าหมาย</span><span class="sxs-lookup"><span data-stu-id="0f108-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="0f108-234">คุณอาจจำเป็นต้องจำกัดข้อมูลต้นฉบับของคุณไป๘๕ยังเปอร์เซ็นต์ของโควตาของกล่องจดหมายเป้าหมายทั้งนี้ขึ้นอยู่กับแพลตฟอร์มต้นฉบับ</span><span class="sxs-lookup"><span data-stu-id="0f108-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="0f108-235">โยกย้ายข้อมูลฝั่งไคลเอ็นต์ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="0f108-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="0f108-236">ซึ่งรวมถึงแต่ไม่จำกัดเฉพาะสมุดรายชื่อภายในเครื่องข้อมูลในไฟล์ PST ภายในเครื่องกฎ Outlook และการตั้งค่า Outlook ภายในเครื่อง</span><span class="sxs-lookup"><span data-stu-id="0f108-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="0f108-237">ช่วยให้ผู้ใช้ของคุณมีส่วนของปัญหาการโยกย้ายที่ด้านไคลเอ็นต์</span><span class="sxs-lookup"><span data-stu-id="0f108-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="0f108-238">การโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="0f108-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="0f108-239">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง SharePoint Online เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0f108-240">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับและ SharePoint Online และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="0f108-241">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-241">You create and schedule your migration events.</span></span> <span data-ttu-id="0f108-242">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="0f108-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0f108-243">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="0f108-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="0f108-244">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="0f108-244">Considerations</span></span>

  - <span data-ttu-id="0f108-245">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตา SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="0f108-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="0f108-246">อ้างอิงไปยัง [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="0f108-247">เราขอแนะนำให้คุณจำกัดจำนวนรวมของการโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="0f108-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="0f108-248">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-248">Source environment details</span></span>

<span data-ttu-id="0f108-249">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="0f108-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="0f108-250">ไฟล์ที่แชร์ (ไฟล์การบล็อกข้อความเซิร์ฟเวอร์ (SMB) บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="0f108-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="0f108-251">สภาพแวดล้อม G Suite เดียว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="0f108-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="0f108-252">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="0f108-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="0f108-253">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="0f108-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="0f108-254">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="0f108-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="0f108-255"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="0f108-256"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="0f108-257"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="0f108-258"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0f108-259"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="0f108-260">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-261">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="0f108-261">Documents</span></span> </li>
<li> <span data-ttu-id="0f108-262">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-263">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="0f108-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0f108-264">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="0f108-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0f108-265">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-266">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-267">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-267">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-268">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-268">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-269">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-269">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-270">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="0f108-271">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="0f108-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="0f108-272">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="0f108-273">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="0f108-274">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-275">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="0f108-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="0f108-276">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-277">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="0f108-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="0f108-278">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="0f108-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="0f108-279">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="0f108-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="0f108-280">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="0f108-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="0f108-281">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="0f108-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="0f108-282">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="0f108-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="0f108-283">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-284">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="0f108-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="0f108-285">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="0f108-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="0f108-286">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0f108-287"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="0f108-288">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-289">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่า) รวมถึงที่มีค่ามากกว่า10เมกะไบต์</span><span class="sxs-lookup"><span data-stu-id="0f108-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="0f108-290">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-291">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-292">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-293">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-294">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-295">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-295">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-296">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-296">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-297">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-297">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-298">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0f108-299">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="0f108-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="0f108-300">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-301">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="0f108-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0f108-302">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="0f108-303">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-304">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-305">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="0f108-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0f108-306">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0f108-307">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-308">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="0f108-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="0f108-309">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-310">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-311">Google รูปแบบฟอร์มแผนที่และแอปที่เชื่อมต่ออื่นๆ</span><span class="sxs-lookup"><span data-stu-id="0f108-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="0f108-312">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="0f108-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="0f108-313">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="0f108-314">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="0f108-315">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="0f108-316">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-317">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="0f108-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="0f108-318">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-319">ไฟล์ที่ถูกทำเครื่องหมายเป็นแบบจำกัดหรือไม่ copyable</span><span class="sxs-lookup"><span data-stu-id="0f108-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="0f108-320">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0f108-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="0f108-322">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-323">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="0f108-323">Documents</span></span> </li>
<li> <span data-ttu-id="0f108-324">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-325">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-326">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-327">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-328">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-329">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-329">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-330">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-330">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-331">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-331">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-332">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0f108-333">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-334">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="0f108-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0f108-335">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0f108-336">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-337">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-338">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="0f108-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="0f108-339">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0f108-340">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-341">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="0f108-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="0f108-342">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-343">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-344">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="0f108-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="0f108-345">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="0f108-346">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="0f108-347">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-348">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0f108-349"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="0f108-350">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-351">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="0f108-351">Documents</span></span> </li>
<li> <span data-ttu-id="0f108-352">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-353">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-354">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-355">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-356">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-357">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-357">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-358">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-358">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-359">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-359">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-360">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0f108-361">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="0f108-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="0f108-362">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-363">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="0f108-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0f108-364">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0f108-365">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-366">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-367">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="0f108-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0f108-368">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0f108-369">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-370">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="0f108-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="0f108-371">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-372">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="0f108-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="0f108-373">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="0f108-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="0f108-374">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="0f108-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="0f108-375">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="0f108-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="0f108-376">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="0f108-377">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="0f108-378">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="0f108-379">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0f108-380">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="0f108-380">FastTrack responsibilities</span></span>

<span data-ttu-id="0f108-381">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0f108-382">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0f108-383">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-383">Your responsibilities</span></span>

<span data-ttu-id="0f108-384">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0f108-385">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="0f108-386">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้เฉพาะกับการโยกย้าย SharePoint Online ได้ดังนี้</span><span class="sxs-lookup"><span data-stu-id="0f108-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="0f108-387">จัดเตรียมไซต์ทีม SharePoint ทั้งหมดที่จะกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="0f108-388">การโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="0f108-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="0f108-389">เมื่อคุณเลือกที่จะใช้ FastTrack เพื่อโยกย้ายไฟล์ของคุณไปยัง OneDrive for Business เราจะให้คำแนะนำการโยกย้ายและบริการการโยกย้ายข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="0f108-390">เรามีคำแนะนำที่จะช่วยให้คุณวางแผนการโยกย้ายของคุณกำหนดค่าสภาพแวดล้อมต้นฉบับของคุณและ OneDrive for Business และใช้ประโยชน์จากบริการการโยกย้ายข้อมูลของเราเพื่อโยกย้ายไฟล์ของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="0f108-391">คุณสร้างและจัดกำหนดการเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-391">You create and schedule your migration events.</span></span> <span data-ttu-id="0f108-392">เราเปิดใช้งานเหตุการณ์การโยกย้ายตามกำหนดการของคุณตรวจสอบความคืบหน้าของพวกเขาและแสดงรายงานสถานะ</span><span class="sxs-lookup"><span data-stu-id="0f108-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="0f108-393">เมื่อเหตุการณ์การโยกย้ายของคุณเสร็จสมบูรณ์คุณสามารถคาดหวังไฟล์จากแหล่งข้อมูลที่จัดกำหนดการไว้อย่างเหมาะสมและแหล่งข้อมูลที่มีสิทธิ์ของสภาพแวดล้อมต้นฉบับของคุณที่จะถูกโยกย้ายไปยัง OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="0f108-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="0f108-394">ข้อควรพิจารณา</span><span class="sxs-lookup"><span data-stu-id="0f108-394">Considerations</span></span>

  - <span data-ttu-id="0f108-395">การโยกย้ายทั้งหมดจะอยู่ภายใต้โควตาของ OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="0f108-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="0f108-396">โปรดดูที่ [<span class="underline">SharePoint Online และ OneDrive For Business: ขอบเขตและขีดจำกัดของซอฟต์แวร์</span>](https://go.microsoft.com/fwlink/?LinkId=698855) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="0f108-397">เราขอแนะนำให้คุณจำกัดจำนวนข้อมูลโดยรวมที่คุณโยกย้ายไปยัง๗๕เปอร์เซ็นต์ของโควตาที่เก็บข้อมูล SharePoint Online โดยรวมที่คุณมีสิทธิ์ (รวมถึงที่เก็บข้อมูลเพิ่มเติมที่คุณอาจซื้อแยกต่างหาก)</span><span class="sxs-lookup"><span data-stu-id="0f108-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="0f108-398">FastTrack จะย้ายไปยังไดรฟ์ OneDrive for Business ที่ใช้งานอยู่เท่านั้น</span><span class="sxs-lookup"><span data-stu-id="0f108-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="0f108-399">รายละเอียดของสภาพแวดล้อมของแหล่งข้อมูล</span><span class="sxs-lookup"><span data-stu-id="0f108-399">Source environment details</span></span>

<span data-ttu-id="0f108-400">บริการการโยกย้ายข้อมูลของเราจะโยกย้ายข้อมูลจากสภาพแวดล้อมแหล่งข้อมูลเหล่านี้:</span><span class="sxs-lookup"><span data-stu-id="0f108-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="0f108-401">ไฟล์ที่แชร์ (ไฟล์ SMB ที่แชร์บนอุปกรณ์สนับสนุน SMB ๒.๐เป็นต้นไป)</span><span class="sxs-lookup"><span data-stu-id="0f108-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="0f108-402">สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</span><span class="sxs-lookup"><span data-stu-id="0f108-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="0f108-403">Box (Starter, Business, Enterprise)</span><span class="sxs-lookup"><span data-stu-id="0f108-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="0f108-404">Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</span><span class="sxs-lookup"><span data-stu-id="0f108-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="0f108-405">ตารางต่อไปนี้แสดงรายละเอียดการโยกย้ายเฉพาะในสภาพแวดล้อมต้นฉบับแต่ละรายการ:</span><span class="sxs-lookup"><span data-stu-id="0f108-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="0f108-406"><strong>สภาพแวดล้อมต้นฉบับ</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="0f108-407"><strong>ชนิดของการโยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="0f108-408"><strong>สิ่งที่ย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="0f108-409"><strong>สิ่งที่ไม่โยกย้าย</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="0f108-410"><strong>อุปกรณ์แชร์ไฟล์ใดๆที่สนับสนุน SMB ๒.๐เป็นต้นไป</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="0f108-411">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-412">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="0f108-412">Documents</span></span> </li>
<li> <span data-ttu-id="0f108-413">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-414">สิทธิ์ของไฟล์และโฟลเดอร์ระดับผู้ใช้ \*</span><span class="sxs-lookup"><span data-stu-id="0f108-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0f108-415">สิทธิ์สำหรับไฟล์และโฟลเดอร์ระดับกลุ่ม \*</span><span class="sxs-lookup"><span data-stu-id="0f108-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="0f108-416">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-417">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-418">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-418">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-419">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-419">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-420">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-420">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-421">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="0f108-422">\* จำเป็นต้องมีการกำหนดค่าการซิงโครไนซ์ไดเรกทอรี</span><span class="sxs-lookup"><span data-stu-id="0f108-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="0f108-423">สิทธิ์การใช้งาน NTFS ที่เปิดใช้งานใน Windows File Explorer เท่านั้นที่จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="0f108-424">สิทธิ์ที่ได้รับการจัดการโดยตรงบนอุปกรณ์แชร์ไฟล์จะไม่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="0f108-425">ถ้าข้อมูลถูกเก็บไว้บนอุปกรณ์ SMB ๒.๐สิทธิ์ที่เทียบเท่ากับ NTFS ที่แสดงโดยโพรโทคอล SMB จะถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="0f108-426">ประวัติความเป็นเจ้าของและเวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="0f108-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="0f108-427">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-428">เวอร์ชันก่อนหน้า</span><span class="sxs-lookup"><span data-stu-id="0f108-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="0f108-429">แอตทริบิวต์ไฟล์และโฟลเดอร์ของ Windows (เช่นแบบอ่านอย่างเดียวและซ่อน)</span><span class="sxs-lookup"><span data-stu-id="0f108-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="0f108-430">ระบบไฟล์เทคโนโลยีใหม่ที่ไม่ใช่ Windows (NTFS) และการตั้งค่าพิเศษของ NTFS และการตั้งค่าพิเศษ:</span><span class="sxs-lookup"><span data-stu-id="0f108-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="0f108-431">สิทธิ์ปฏิเสธที่ชัดเจน (เอาออกหลังจากการโยกย้ายเนื้อหาภายใต้สิทธิ์หรือสิทธิ์แบบขนานบนโฟลเดอร์แม่)</span><span class="sxs-lookup"><span data-stu-id="0f108-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="0f108-432">การกำหนดค่าการตรวจสอบ NTFS</span><span class="sxs-lookup"><span data-stu-id="0f108-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="0f108-433">Metadata ของไฟล์เพิ่มเติมที่มีให้โดยโครงสร้างพื้นฐานของการจัดประเภทไฟล์ (FCI)</span><span class="sxs-lookup"><span data-stu-id="0f108-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="0f108-434">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-435">หุ้นที่ซ่อนอยู่</span><span class="sxs-lookup"><span data-stu-id="0f108-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="0f108-436">การแชร์ (เช่นสิทธิ์ที่มอบให้กับระดับการแชร์)</span><span class="sxs-lookup"><span data-stu-id="0f108-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="0f108-437">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0f108-438"><strong>สภาพแวดล้อม G Suite เดี่ยว (เฉพาะ Google Drive เท่านั้น)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="0f108-439">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-440">Google เอกสารชีตและสไลด์ (ไฟล์จะถูกแปลงเป็นรูปแบบ Office ที่เทียบเท่ากันรวมถึงที่มีค่ามากกว่า 10 MB)</span><span class="sxs-lookup"><span data-stu-id="0f108-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="0f108-441">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-442">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-443">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-444">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-445">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-446">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-446">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-447">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-447">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-448">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-448">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-449">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0f108-450">ไดรฟ์ที่แชร์ (โฟลเดอร์และไฟล์)</span><span class="sxs-lookup"><span data-stu-id="0f108-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="0f108-451">เนื้อหาที่แชร์ของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-452">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="0f108-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0f108-453">คำอธิบายไฟล์และโฟลเดอร์สีของโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="0f108-454">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-455">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-456">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="0f108-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0f108-457">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0f108-458">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-459">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="0f108-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="0f108-460">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-461">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-462">รูปแบบแผนที่และแอปที่เชื่อมต่ออื่นๆของ Google</span><span class="sxs-lookup"><span data-stu-id="0f108-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="0f108-463">Google รูปวาด</span><span class="sxs-lookup"><span data-stu-id="0f108-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="0f108-464">เนื้อหาที่แชร์ภายนอกองค์กรของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="0f108-465">เนื้อหาที่ไม่ได้เป็นของบัญชี Google Drive ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="0f108-466">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google Drive เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="0f108-467">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-468">สิทธิ์การเป็นสมาชิกของไดรฟ์ที่แชร์ (<strong>หมายเหตุ</strong>: ใช้รายงานผู้ดูแลระบบของ Google drive เพื่อระบุการเป็นสมาชิกของไดรฟ์ที่แชร์</span><span class="sxs-lookup"><span data-stu-id="0f108-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="0f108-469">แนะนำให้ผู้ใช้กำหนดค่าการตั้งค่าการเป็นสมาชิกเหล่านี้บนเป้าหมายก่อนการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-470">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="0f108-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="0f108-472">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-473">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="0f108-473">Documents</span></span> </li>
<li> <span data-ttu-id="0f108-474">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-475">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-476">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-477">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-478">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-479">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-479">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-480">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-480">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-481">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-481">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-482">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0f108-483">เนื้อหาที่แชร์ของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-484">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="0f108-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0f108-485">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0f108-486">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-487">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-488">แท็กกล่องและ metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="0f108-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="0f108-489">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0f108-490">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-491">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="0f108-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="0f108-492">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-493">ผู้ใช้ที่ถูกบล็อกหรือไม่ได้ใช้งาน</span><span class="sxs-lookup"><span data-stu-id="0f108-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="0f108-494">แอปกล่องบุ๊กมาร์กรายการโปรดและเวิร์กโฟลว์</span><span class="sxs-lookup"><span data-stu-id="0f108-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="0f108-495">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ของกล่องที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="0f108-496">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงานกล่องเพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="0f108-497">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-498">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="0f108-499"><strong>Dropbox สำหรับทีม (มาตรฐานและขั้นสูง)</strong></span><span class="sxs-lookup"><span data-stu-id="0f108-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="0f108-500">หนึ่งหรือหลายบัตร</span><span class="sxs-lookup"><span data-stu-id="0f108-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="0f108-501">เอกสาร</span><span class="sxs-lookup"><span data-stu-id="0f108-501">Documents</span></span> </li>
<li> <span data-ttu-id="0f108-502">โครงสร้างของไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="0f108-503">สิทธิ์ของโฟลเดอร์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-504">สิทธิ์ของโฟลเดอร์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="0f108-505">ไฟล์ที่อยู่ภายใต้ 15 GB</span><span class="sxs-lookup"><span data-stu-id="0f108-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="0f108-506">เอกสารพื้นฐานและ metadata ของโฟลเดอร์:</span><span class="sxs-lookup"><span data-stu-id="0f108-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="0f108-507">วันที่สร้างขึ้น</span><span class="sxs-lookup"><span data-stu-id="0f108-507">Created date</span></span> </li>
<li> <span data-ttu-id="0f108-508">วันที่ปรับเปลี่ยน</span><span class="sxs-lookup"><span data-stu-id="0f108-508">Modified date</span></span> </li>
<li> <span data-ttu-id="0f108-509">สร้างโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-509">Created by</span></span> </li>
<li> <span data-ttu-id="0f108-510">ปรับเปลี่ยนครั้งล่าสุดโดย</span><span class="sxs-lookup"><span data-stu-id="0f108-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="0f108-511">โฟลเดอร์และเนื้อหาของทีมที่แชร์</span><span class="sxs-lookup"><span data-stu-id="0f108-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="0f108-512">เนื้อหาที่แชร์ของบัญชีผู้ใช้ Dropbox ที่กำลังถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="0f108-513">ประวัติความเป็นเจ้าของเวอร์ชันก่อนหน้าและข้อคิดเห็น</span><span class="sxs-lookup"><span data-stu-id="0f108-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="0f108-514">คำอธิบายไฟล์และโฟลเดอร์</span><span class="sxs-lookup"><span data-stu-id="0f108-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="0f108-515">สิทธิ์ของไฟล์ระดับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="0f108-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-516">สิทธิ์ของไฟล์ระดับกลุ่ม</span><span class="sxs-lookup"><span data-stu-id="0f108-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="0f108-517">Metadata ขั้นสูง</span><span class="sxs-lookup"><span data-stu-id="0f108-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="0f108-518">แอตทริบิวต์การล็อกไฟล์</span><span class="sxs-lookup"><span data-stu-id="0f108-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="0f108-519">การแปลงของ Url ที่ฝังตัวในเนื้อหา</span><span class="sxs-lookup"><span data-stu-id="0f108-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="0f108-520">รายการที่ขยะ</span><span class="sxs-lookup"><span data-stu-id="0f108-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="0f108-521">เอกสารที่ไม่สามารถเข้าถึงหรือเสียหาย</span><span class="sxs-lookup"><span data-stu-id="0f108-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="0f108-522">โฟลเดอร์ Unmounted Dropbox</span><span class="sxs-lookup"><span data-stu-id="0f108-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="0f108-523">ผู้ใช้ที่ถูกลบหรือยกเลิกการเชื่อมต่อ</span><span class="sxs-lookup"><span data-stu-id="0f108-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="0f108-524">การแสดงผลงานของ Dropbox Paper และช่องว่าง</span><span class="sxs-lookup"><span data-stu-id="0f108-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="0f108-525">แอป Dropbox และรายการโปรด (หมุด/ดาว)</span><span class="sxs-lookup"><span data-stu-id="0f108-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="0f108-526">เนื้อหาที่ไม่ได้เป็นของบัญชีผู้ใช้ Dropbox ที่ถูกโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="0f108-527">สิทธิ์และ metadata พื้นฐานของผู้ใช้ภายนอก (<strong>หมายเหตุ</strong>: ใช้รายงาน Dropbox เพื่อระบุเนื้อหาที่แชร์กับผู้ใช้ภายนอก</span><span class="sxs-lookup"><span data-stu-id="0f108-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="0f108-528">แนะนำผู้ใช้ให้สิ้นสุดการ reshare เนื้อหากับผู้ใช้ภายนอกหลังจากการโยกย้าย)</span><span class="sxs-lookup"><span data-stu-id="0f108-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="0f108-529">ไฟล์หรือโฟลเดอร์ที่เกิน<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">ข้อจำกัดและข้อจำกัดของ SharePoint Online</span>ปัจจุบัน</a> </span><span class="sxs-lookup"><span data-stu-id="0f108-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="0f108-530">ความรับผิดชอบของ FastTrack</span><span class="sxs-lookup"><span data-stu-id="0f108-530">FastTrack responsibilities</span></span>

<span data-ttu-id="0f108-531">ผู้เชี่ยวชาญ FastTrack ของเราดำเนินกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="0f108-532">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="0f108-533">ความรับผิดชอบของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-533">Your responsibilities</span></span>

<span data-ttu-id="0f108-534">คุณทำกิจกรรมมาตรฐานระหว่างโครงการการโยกย้าย</span><span class="sxs-lookup"><span data-stu-id="0f108-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="0f108-535">อ้างอิงถึงข้อมูลความรับผิดชอบในการโยกย้ายข้อมูลใน [กระบวนการและความคาดหวัง](process-and-expectations.md) สำหรับรายละเอียด</span><span class="sxs-lookup"><span data-stu-id="0f108-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="0f108-536">นอกจากนี้คุณยังสามารถดำเนินการกิจกรรมต่อไปนี้โดยเฉพาะสำหรับการโยกย้าย OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="0f108-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="0f108-537">จัดเตรียมไซต์ OneDrive for Business ทั้งหมดที่จะได้รับการกำหนดเป้าหมายตามเหตุการณ์การโยกย้ายของคุณ</span><span class="sxs-lookup"><span data-stu-id="0f108-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
