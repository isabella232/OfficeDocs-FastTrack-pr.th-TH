---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack ให้คำแนะนำในการปรับใช้ Windows 10 เพื่อช่วยคุณในการอัปเกรดจาก Windows 7 Professional และ Windows ๘.๑ Professional เป็น Windows 10 Enterprise
ms.openlocfilehash: 0b19ada41624d8c8fa8d3ab5e85a14b42edd53f3
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817142"
---
# <a name="windows-10"></a><span data-ttu-id="157db-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="157db-103">Windows 10</span></span>

> [!CAUTION]
> <span data-ttu-id="157db-104">เนื้อหานี้ไม่ได้อยู่ในปัจจุบันอีกต่อไปและมีการจัดกำหนดการสำหรับการเอาออก</span><span class="sxs-lookup"><span data-stu-id="157db-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="157db-105">ใช้สารบัญในการนำทางด้านซ้ายสำหรับเนื้อหาปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="157db-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="157db-106">FastTrack ให้คำแนะนำในการปรับใช้ Windows 10 เพื่อช่วยคุณในการอัปเกรดจาก Windows 7 Professional และ Windows ๘.๑ Professional เป็น Windows 10 Enterprise</span><span class="sxs-lookup"><span data-stu-id="157db-106">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="157db-107">คุณทำงานกับผู้เชี่ยวชาญ FastTrack เพื่อ:</span><span class="sxs-lookup"><span data-stu-id="157db-107">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="157db-108">ปรับใช้ Windows 10 Enterprise โดยใช้ตัวจัดการการกำหนดค่า Microsoft จุดสิ้นสุดหรือ Microsoft ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="157db-108">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="157db-109">ปรับใช้แอป Microsoft ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="157db-109">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="157db-110">อัปเดต Windows 10 Enterprise และ Microsoft ๓๖๕ Apps โดยใช้ตัวจัดการการกำหนดค่า Microsoft จุดสิ้นสุดหรือ Microsoft ๓๖๕</span><span class="sxs-lookup"><span data-stu-id="157db-110">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="157db-111">ตัวจัดการการกำหนดค่าของ cloud ที่แนบมากับ Microsoft Intune หรือปรับใช้ Intune เป็นโซลูชันการจัดการระบบคลาวด์เพียงอย่างเดียว</span><span class="sxs-lookup"><span data-stu-id="157db-111">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="157db-112">FastTrack ให้ลูกค้าที่มีวิธีการแนะนำคำแนะนำและแนวทางปฏิบัติที่ดีที่สุดที่ออกแบบมาเพื่อส่งผลลัพธ์ที่รวดเร็วและคาดเดาได้</span><span class="sxs-lookup"><span data-stu-id="157db-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="157db-113">ถ้าคุณเลือกที่จะปรับใช้ภายนอกคำแนะนำนี้ประสบการณ์การใช้งานของคุณอาจได้รับผลกระทบ</span><span class="sxs-lookup"><span data-stu-id="157db-113">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="157db-114">คำแนะนำจะถูกกำหนดให้เป็นการรวมกันของความช่วยเหลือทางวาจาและการเขียน</span><span class="sxs-lookup"><span data-stu-id="157db-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="157db-115">เมื่อผู้เชี่ยวชาญด้าน FastTrack ให้คำแนะนำเจ้าหน้าที่ FastTrack ไม่สามารถดำเนินการในนามของคุณได้</span><span class="sxs-lookup"><span data-stu-id="157db-115">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="157db-116">คุณสามารถใช้ FastTrack services สำหรับแผนการคัดเลือกตราบใดที่การสมัครใช้งานของคุณเป็นปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="157db-116">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="157db-117">ตารางต่อไปนี้แสดงบทบาทและความรับผิดชอบสำหรับกระบวนการ</span><span class="sxs-lookup"><span data-stu-id="157db-117">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="157db-118">**บทบาท**</span><span class="sxs-lookup"><span data-stu-id="157db-118">**Role**</span></span> <br/> |<span data-ttu-id="157db-119">**ชอบ**</span><span class="sxs-lookup"><span data-stu-id="157db-119">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="157db-120">**ผู้เชี่ยวชาญ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="157db-120">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="157db-121">มีการปรับใช้และการปรับปรุงบริการทั้งหมดจากระยะไกล</span><span class="sxs-lookup"><span data-stu-id="157db-121">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="157db-122">ช่วยเหลือคุณจากระยะไกลโดยใช้เครื่องมือการรวมกันและเอกสารที่เผยแพร่</span><span class="sxs-lookup"><span data-stu-id="157db-122">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="157db-123">ทำงานร่วมกับคุณหรือตัวแทนของคุณได้โดยตรง</span><span class="sxs-lookup"><span data-stu-id="157db-123">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="157db-124">**ศูนย์ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="157db-124">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="157db-125">ให้คำแนะนำในการวางแผนและปรับใช้ Windows 10 Enterprise</span><span class="sxs-lookup"><span data-stu-id="157db-125">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="157db-126">ให้ความช่วยเหลือและพร้อมใช้งานในช่วงเวลาทำการปกติสำหรับภูมิภาคที่กำหนด</span><span class="sxs-lookup"><span data-stu-id="157db-126">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="157db-127">ให้ความช่วยเหลือในภาษาจีนแบบดั้งเดิมและภาษาจีนประยุกต์ (แหล่งข้อมูลพูดภาษาจีนกลางเท่านั้น), อังกฤษ, ฝรั่งเศส, เยอรมัน, อิตาลี, ญี่ปุ่น, เกาหลี, โปรตุเกส (บราซิล), ภาษาสเปน, ภาษาไทยและภาษาเวียดนาม</span><span class="sxs-lookup"><span data-stu-id="157db-127">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="157db-128">คุณสามารถรับความช่วยเหลือผ่าน[ศูนย์การจัดการ Microsoft ๓๖๕](https://go.microsoft.com/fwlink/?linkid=2032704)หรือ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="157db-128">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="157db-129">เมื่อต้องการลงชื่อเข้าใช้คุณจะต้องมีบัญชีผู้ใช้ที่ทำงานหรือที่โรงเรียน (ID ขององค์กรหรือ active Directory ID) บนผู้เช่าที่ใช้งานอยู่</span><span class="sxs-lookup"><span data-stu-id="157db-129">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="157db-130">เมื่อต้องการรับความช่วยเหลือผ่าน [ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ให้ทำดังนี้</span><span class="sxs-lookup"><span data-stu-id="157db-130">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="157db-131">ลงชื่อเข้าใช้[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="157db-131">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="157db-132">เลือก **ร้องขอความช่วยเหลือเกี่ยวกับ Microsoft ๓๖๕** จากการ **ดำเนินการด่วน** ที่ด้านบนของหน้า landing page ของคุณ</span><span class="sxs-lookup"><span data-stu-id="157db-132">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="157db-133">ทำการ **ร้องขอความช่วยเหลือให้เสร็จสมบูรณ์ด้วย Microsoft ๓๖๕** ฟอร์ม</span><span class="sxs-lookup"><span data-stu-id="157db-133">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="157db-134">คู่ค้ายังสามารถรับความช่วยเหลือผ่าน [ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) ในนามของลูกค้าได้อีกด้วย</span><span class="sxs-lookup"><span data-stu-id="157db-134">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="157db-135">เมื่อต้องการทำเช่นนี้ให้ทำดังนี้</span><span class="sxs-lookup"><span data-stu-id="157db-135">To do so:</span></span>
1.    <span data-ttu-id="157db-136">ลงชื่อเข้าใช้[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="157db-136">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="157db-137">เลือก **ร้องขอความช่วยเหลือเกี่ยวกับ Microsoft ๓๖๕** จากการ **ดำเนินการด่วน** ที่ด้านบนของหน้า landing page ของคุณ</span><span class="sxs-lookup"><span data-stu-id="157db-137">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="157db-138">ค้นหาลูกค้าของคุณโดยการใส่ชื่อลูกค้าโดเมนหรือ TPID</span><span class="sxs-lookup"><span data-stu-id="157db-138">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="157db-139">เลือกลูกค้าจากผลลัพธ์การค้นหา</span><span class="sxs-lookup"><span data-stu-id="157db-139">Select customer from the search results.</span></span>
5.    <span data-ttu-id="157db-140">ทำการ **ร้องขอความช่วยเหลือให้เสร็จสมบูรณ์ด้วย Microsoft ๓๖๕** ฟอร์ม</span><span class="sxs-lookup"><span data-stu-id="157db-140">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
