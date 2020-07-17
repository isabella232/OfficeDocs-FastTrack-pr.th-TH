---
title: กระบวนการ FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: กระบวนการ FastTrack ให้บริการการเตรียมพร้อมและการยอมรับผู้ใช้
ms.openlocfilehash: 271a78c8d203c90e2bb49a7569283a748b66f443
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011375"
---
# <a name="the-fasttrack-process"></a><span data-ttu-id="6ce46-103">กระบวนการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="6ce46-103">The FastTrack Process</span></span>

<span data-ttu-id="6ce46-104">กระบวนการ FastTrack ให้บริการการเตรียมพร้อมและการยอมรับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="6ce46-104">The FastTrack process provides onboarding and user adoption services.</span></span> 
  
<span data-ttu-id="6ce46-105">การเตรียมพร้อมประกอบด้วย:</span><span class="sxs-lookup"><span data-stu-id="6ce46-105">Onboarding consists of:</span></span>
  
- <span data-ttu-id="6ce46-106">*หลัก onboarding* — งานเหล่านี้จําเป็นสําหรับการตั้งค่าคอนฟิกผู้เช่าและรวมกับ Azure Active Directory (Azure AD) ถ้าจําเป็น</span><span class="sxs-lookup"><span data-stu-id="6ce46-106">*Core onboarding* — These are tasks required for tenant configuration and integration with Azure Active Directory (Azure AD) if needed.</span></span> <span data-ttu-id="6ce46-107">นอกจากนี้ Core onboarding ยังให้พื้นฐานสําหรับการให้บริการที่มีสิทธิ์อื่น ๆ</span><span class="sxs-lookup"><span data-stu-id="6ce46-107">Core onboarding also provides the baseline for onboarding other eligible services.</span></span> 
- <span data-ttu-id="6ce46-108">*การเริ่มใช้งานและการโยกย้ายบริการ*— งานการเตรียมพร้อมของบริการจะเปิดใช้งานสถานการณ์จําลองในผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="6ce46-108">*Service onboarding and migration* — Service onboarding tasks enable scenarios in your tenant.</span></span> <span data-ttu-id="6ce46-109">การย้ายข้อมูล (รวมถึงอีเมลและไฟล์) จะครอบคลุมอยู่ใน[การย้ายข้อมูล](O365-data-migration.md)</span><span class="sxs-lookup"><span data-stu-id="6ce46-109">Data migration (including email and files) is covered in [Data Migration](O365-data-migration.md).</span></span> 
    
<span data-ttu-id="6ce46-110">บริการการนําผู้ใช้มาใช้เป็นงานต่างๆ ที่ให้คําแนะนําแก่คุณเพื่อให้แน่ใจว่าผู้ใช้ของคุณทราบถึงบริการที่มีสิทธิ์และสามารถใช้บริการเหล่านั้นเพื่อกระตุ้นมูลค่าทางธุรกิจได้</span><span class="sxs-lookup"><span data-stu-id="6ce46-110">User adoption services are comprised of tasks that provide guidance for you to ensure your users are aware of the eligible services and can use them to drive business value.</span></span> <span data-ttu-id="6ce46-111">ความช่วยเหลือนี้เกิดขึ้นควบคู่ไปกับกิจกรรมออนบอร์ด</span><span class="sxs-lookup"><span data-stu-id="6ce46-111">This assistance occurs in parallel to onboarding activities.</span></span>
  
> [!NOTE]
> <span data-ttu-id="6ce46-112">FastTrack ให้แนวทางแนะนํา คําแนะนํา และแนวทางปฏิบัติที่ดีที่สุดที่ออกแบบมาเพื่อมอบผลลัพธ์ที่รวดเร็วและคาดการณ์ได้</span><span class="sxs-lookup"><span data-stu-id="6ce46-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="6ce46-113">หากคุณเลือกที่จะปรับใช้นอกคําแนะนํานี้ ประสบการณ์การใช้งานและการใช้งานของบริการอาจได้รับผลกระทบ</span><span class="sxs-lookup"><span data-stu-id="6ce46-113">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="6ce46-114">คําแนะนําถูกกําหนดเป็นการรวมกันของความช่วยเหลือทางวาจาและเขียน</span><span class="sxs-lookup"><span data-stu-id="6ce46-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="6ce46-115">เมื่อผู้เชี่ยวชาญ FastTrack ให้คําแนะนําบุคลากร FastTrack ไม่สามารถดําเนินการในนามของคุณ</span><span class="sxs-lookup"><span data-stu-id="6ce46-115">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="6ce46-116">คุณสามารถใช้บริการ FastTrack เพื่อขึ้นเครื่องและนําปริมาณงานของผลิตภัณฑ์ที่มีคุณสมบัติเหมาะสมได้ตราบใดที่การสมัครใช้งานของคุณเป็นปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="6ce46-116">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span> 
  
## <a name="the-onboarding-process"></a><span data-ttu-id="6ce46-117">กระบวนการเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="6ce46-117">The onboarding process</span></span>

<span data-ttu-id="6ce46-118">แผนภาพต่อไปนี้แสดงกระบวนการเริ่มต้น</span><span class="sxs-lookup"><span data-stu-id="6ce46-118">The following diagram illustrates the onboarding process.</span></span>
  
![ไทม์ไลน์สําหรับการใช้ประโยชน์บนเครื่องบิน](media/o365-onboarding-timeline-m365-apps.png)
  
<span data-ttu-id="6ce46-120">คุณสามารถขอความช่วยเหลือผ่าน[ศูนย์การจัดการ Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704)หรือ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="6ce46-120">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 

<span data-ttu-id="6ce46-121">เมื่อต้องการขอความช่วยเหลือผ่าน[ศูนย์การจัดการ Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704)ผู้ดูแลระบบของคุณลงชื่อเข้าใช้ศูนย์การจัดการ แล้วคลิกวิดเจ็ต**ต้องการความช่วยเหลือ**</span><span class="sxs-lookup"><span data-stu-id="6ce46-121">To get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704), your admin signs into the admin center and then clicks the **Need help?** widget.</span></span> 

<span data-ttu-id="6ce46-122">เพื่อขอความช่วยเหลือผ่านเว็บไซต์[FastTrack](https://go.microsoft.com/fwlink/?linkid=780698):</span><span class="sxs-lookup"><span data-stu-id="6ce46-122">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="6ce46-123">ลงชื่อเข้าใช้[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="6ce46-123">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="6ce46-124">เลือก**ขอความช่วยเหลือสําหรับ Microsoft 365**จาก**การดําเนินการด่วน**ที่ด้านบนของหน้า Landing Page ของคุณ หรือโดยการเลือก**ขอความช่วยเหลือสําหรับ Microsoft 365**บนการ์ดการปรับใช้</span><span class="sxs-lookup"><span data-stu-id="6ce46-124">Select **Request assistance for Microsoft 365** from the **quick actions** on the top of your landing page or by selecting **Request assistance for Microsoft 365** on the deploy card.</span></span>
3.    <span data-ttu-id="6ce46-125">กรอกแบบฟอร์ม**ขอความช่วยเหลือสําหรับ Microsoft 365**</span><span class="sxs-lookup"><span data-stu-id="6ce46-125">Complete the **Request Assistance for Microsoft 365** form.</span></span> 
  
 <span data-ttu-id="6ce46-126">นอกจากนี้ คุณยังสามารถขอความช่วยเหลือจาก FastTrack Center ได้จาก[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในรายการบริการที่พร้อมใช้งานสําหรับผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="6ce46-126">You can also ask for FastTrack Center help from the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) in the list of available services for your tenant.</span></span> 
    
 <span data-ttu-id="6ce46-127">เมื่อความช่วยเหลือเริ่มต้นขึ้นเราจะตั้งตารางเวลาการประชุมออนไลน์</span><span class="sxs-lookup"><span data-stu-id="6ce46-127">Once onboarding assistance starts, we set up a schedule of online meetings.</span></span>
    
<span data-ttu-id="6ce46-128">พาร์ทเนอร์ยังสามารถขอความช่วยเหลือผ่าน[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในนามของลูกค้าได้</span><span class="sxs-lookup"><span data-stu-id="6ce46-128">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="6ce46-129">เมื่อต้องการทําเช่นนั้น:</span><span class="sxs-lookup"><span data-stu-id="6ce46-129">To do so:</span></span>
1.    <span data-ttu-id="6ce46-130">ลงชื่อเข้าใช้[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="6ce46-130">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="6ce46-131">เลือก**ลูกค้าของฉัน**</span><span class="sxs-lookup"><span data-stu-id="6ce46-131">Select **My Customers**.</span></span>
3.    <span data-ttu-id="6ce46-132">ค้นหาลูกค้าของคุณหรือเลือกจากรายชื่อลูกค้าของคุณ</span><span class="sxs-lookup"><span data-stu-id="6ce46-132">Search for your customer or select them from your customer list.</span></span>
4.    <span data-ttu-id="6ce46-133">เลือก**บริการ**</span><span class="sxs-lookup"><span data-stu-id="6ce46-133">Select **Services**.</span></span>
5.    <span data-ttu-id="6ce46-134">กรอกแบบฟอร์ม**ขอความช่วยเหลือสําหรับ Microsoft 365**</span><span class="sxs-lookup"><span data-stu-id="6ce46-134">Complete the **Request Assistance for Microsoft 365** form.</span></span> 

<span data-ttu-id="6ce46-135">ตารางต่อไปนี้แสดงรายการบทบาทและความรับผิดชอบสําหรับกระบวนการ</span><span class="sxs-lookup"><span data-stu-id="6ce46-135">The following table lists roles and responsibilities for the process.</span></span>
    
|||
|:-----|:-----|
|<span data-ttu-id="6ce46-136">**บทบาท**</span><span class="sxs-lookup"><span data-stu-id="6ce46-136">**Role**</span></span> <br/> |<span data-ttu-id="6ce46-137">**ความรับผิดชอบ**</span><span class="sxs-lookup"><span data-stu-id="6ce46-137">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="6ce46-138">**ผู้เชี่ยวชาญ**</span><span class="sxs-lookup"><span data-stu-id="6ce46-138">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="6ce46-139">ให้บริการการเตรียมพร้อม, การย้ายข้อมูล และการรับใช้งานของผู้ใช้จากระยะไกล</span><span class="sxs-lookup"><span data-stu-id="6ce46-139">Provides all onboarding, migration, and user adoption services remotely.</span></span>  <br/> <span data-ttu-id="6ce46-140">ช่วยให้คุณจากระยะไกลโดยใช้การรวมกันของเครื่องมือและเอกสารที่เผยแพร่</span><span class="sxs-lookup"><span data-stu-id="6ce46-140">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="6ce46-141">ทํางานร่วมกับคุณหรือตัวแทนของคุณโดยตรง</span><span class="sxs-lookup"><span data-stu-id="6ce46-141">Works directly with you or your representative.</span></span> <br/> <span data-ttu-id="6ce46-142">ให้คําแนะนําในการย้ายข้อมูลและอีเมล</span><span class="sxs-lookup"><span data-stu-id="6ce46-142">Provides email and data migration guidance.</span></span>|
|<span data-ttu-id="6ce46-143">**ศูนย์ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="6ce46-143">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="6ce46-144">ให้คําแนะนํากับหลักและบริการบนเรือและการวางแผนการยอมรับที่ประสบความสําเร็จในการให้บริการที่มีสิทธิ์</span><span class="sxs-lookup"><span data-stu-id="6ce46-144">Provides guidance with core and service onboarding and planning successful adoption of eligible services.</span></span>  <br/> <span data-ttu-id="6ce46-145">ให้ความช่วยเหลือและพร้อมให้บริการในเวลาทําการปกติสําหรับภูมิภาคที่กําหนด</span><span class="sxs-lookup"><span data-stu-id="6ce46-145">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="6ce46-146">ให้ความช่วยเหลือในภาษาจีนแบบดั้งเดิมและภาษาจีนตัวย่อ (ทรัพยากรที่พูดภาษาจีนกลางเท่านั้น) ภาษาอังกฤษฝรั่งเศสเยอรมันอิตาลีญี่ปุ่นเกาหลีโปรตุเกส (บราซิล) สเปนไทยและเวียดนาม</span><span class="sxs-lookup"><span data-stu-id="6ce46-146">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
