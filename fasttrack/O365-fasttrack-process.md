---
title: กระบวนการ FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/02/2019
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: กระบวนการ FastTrack ให้บริการการเตรียมพร้อมและการรับผู้ใช้
ms.openlocfilehash: 445202e667abe77a12428d86b60e31e1910f7004
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921525"
---
# <a name="the-fasttrack-process"></a><span data-ttu-id="a0852-103">กระบวนการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="a0852-103">The FastTrack Process</span></span>

<span data-ttu-id="a0852-104">กระบวนการ FastTrack ให้บริการการเตรียมพร้อมและการรับผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="a0852-104">The FastTrack process provides onboarding and user adoption services.</span></span> 
  
<span data-ttu-id="a0852-105">การเตรียมการประกอบด้วย:</span><span class="sxs-lookup"><span data-stu-id="a0852-105">Onboarding consists of:</span></span>
  
- <span data-ttu-id="a0852-106">การ*ปฐมนิเทศหลัก*—เหล่านี้เป็นงานที่จำเป็นสำหรับการกำหนดค่าผู้เช่าและการรวมกับ Azure ที่ใช้งานอยู่ไดเรกทอรี (azure AD) ถ้าจำเป็น</span><span class="sxs-lookup"><span data-stu-id="a0852-106">*Core onboarding* — These are tasks required for tenant configuration and integration with Azure Active Directory (Azure AD) if needed.</span></span> <span data-ttu-id="a0852-107">การเตรียมการหลักยังมีพื้นฐานสำหรับการเตรียมการบริการที่มีสิทธิ์อื่นๆอีกด้วย</span><span class="sxs-lookup"><span data-stu-id="a0852-107">Core onboarding also provides the baseline for onboarding other eligible services.</span></span> 
- <span data-ttu-id="a0852-108">การ*เตรียมการและการย้ายบริการ*—งานปฐมนิเทศบริการเปิดใช้งานสถานการณ์จำลองในผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="a0852-108">*Service onboarding and migration* — Service onboarding tasks enable scenarios in your tenant.</span></span> <span data-ttu-id="a0852-109">การย้ายข้อมูล (รวมถึงเมลและไฟล์) จะถูกครอบคลุมในการ[ย้ายข้อมูล](O365-data-migration.md)</span><span class="sxs-lookup"><span data-stu-id="a0852-109">Data migration (including email and files) is covered in [Data Migration](O365-data-migration.md).</span></span> 
    
<span data-ttu-id="a0852-110">บริการการรับผู้ใช้จะประกอบด้วยงานที่ให้คำแนะนำสำหรับคุณเพื่อให้แน่ใจว่าผู้ใช้ของคุณทราบถึงบริการที่มีสิทธิ์และสามารถใช้เพื่อขับเคลื่อนคุณค่าทางธุรกิจ</span><span class="sxs-lookup"><span data-stu-id="a0852-110">User adoption services are comprised of tasks that provide guidance for you to ensure your users are aware of the eligible services and can use them to drive business value.</span></span> <span data-ttu-id="a0852-111">ความช่วยเหลือนี้เกิดขึ้นควบคู่ไปกับกิจกรรมการเตรียมพร้อม</span><span class="sxs-lookup"><span data-stu-id="a0852-111">This assistance occurs in parallel to onboarding activities.</span></span>
  
> [!NOTE]
> <span data-ttu-id="a0852-112">ให้คำแนะนำและแนวทางปฏิบัติที่ดีที่สุดในการออกแบบเพื่อให้ได้ผลลัพธ์ที่รวดเร็วและคาดการณ์ได้</span><span class="sxs-lookup"><span data-stu-id="a0852-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="a0852-113">หากคุณเลือกที่จะปรับใช้นอกเหนือจากคำแนะนำนี้คุณจะได้รับประสบการณ์และการใช้บริการที่มีผลกระทบ</span><span class="sxs-lookup"><span data-stu-id="a0852-113">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="a0852-114">คำแนะนำถูกกำหนดให้เป็นการรวมกันของความช่วยเหลือทางวาจาและเป็นลายลักษณ์อักษร</span><span class="sxs-lookup"><span data-stu-id="a0852-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="a0852-115">เมื่อผู้เชี่ยวชาญ FastTrack ให้คำแนะนำเจ้าหน้าที่ FastTrack ไม่สามารถดำเนินการในนามของคุณได้</span><span class="sxs-lookup"><span data-stu-id="a0852-115">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="a0852-116">คุณสามารถใช้บริการ FastTrack เพื่อบนเครื่องบินและนำปริมาณงานของผลิตภัณฑ์ที่มีคุณสมบัติใดๆออกมาได้ตราบใดที่การสมัครใช้งานของคุณเป็นปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="a0852-116">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span> 
  
## <a name="the-onboarding-process"></a><span data-ttu-id="a0852-117">กระบวนการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="a0852-117">The onboarding process</span></span>

<span data-ttu-id="a0852-118">แผนภาพต่อไปนี้แสดงกระบวนการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="a0852-118">The following diagram illustrates the onboarding process.</span></span>
  
![เส้นเวลาสำหรับการใช้สวัสดิการการปฐมนิเทศ](media/O365-Onboarding-Timeline.png)
  
<span data-ttu-id="a0852-120">คุณสามารถขอรับความช่วยเหลือผ่าน[ศูนย์ดูแลของ Microsoft ๓๖๕](https://go.microsoft.com/fwlink/?linkid=2032704)หรือ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="a0852-120">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 

<span data-ttu-id="a0852-121">หากต้องการรับความช่วยเหลือผ่าน[ศูนย์กลางการดูแลระบบ Microsoft ๓๖๕](https://go.microsoft.com/fwlink/?linkid=2032704)ผู้ดูแลของคุณลงชื่อเข้าใช้ศูนย์กลางการดูแลระบบแล้วคลิก "**ต้องการความช่วยเหลือ**" วิดเจ็ต</span><span class="sxs-lookup"><span data-stu-id="a0852-121">To get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704), your admin signs into the admin center and then clicks the **Need help?** widget.</span></span> 

<span data-ttu-id="a0852-122">เพื่อขอความช่วยเหลือผ่าน[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698):</span><span class="sxs-lookup"><span data-stu-id="a0852-122">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.  <span data-ttu-id="a0852-123">เข้าสู่ระบบ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="a0852-123">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="a0852-124">เลือก**บริการ**</span><span class="sxs-lookup"><span data-stu-id="a0852-124">Select **Services**.</span></span>
3.  <span data-ttu-id="a0852-125">ทำการ**ร้องขอความช่วยเหลือด้วยแบบฟอร์ม Microsoft ๓๖๕**</span><span class="sxs-lookup"><span data-stu-id="a0852-125">Complete the **Request for Assistance with Microsoft 365** form.</span></span> 
  
 <span data-ttu-id="a0852-126">นอกจากนี้คุณยังสามารถขอความช่วยเหลือจากศูนย์ FastTrack จาก[ไซต์ fasttrack](https://go.microsoft.com/fwlink/?linkid=780698)ในรายการของบริการที่พร้อมใช้งานสำหรับผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="a0852-126">You can also ask for FastTrack Center help from the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) in the list of available services for your tenant.</span></span> 
    
 <span data-ttu-id="a0852-127">เมื่อเริ่มต้นความช่วยเหลือการปฐมนิเทศเราตั้งค่าตารางการประชุมแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="a0852-127">Once onboarding assistance starts, we set up a schedule of online meetings.</span></span>
    
<span data-ttu-id="a0852-128">นอกจากนี้พาร์ทเนอร์ยังสามารถรับความช่วยเหลือผ่าน[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในนามของลูกค้าได้อีกด้วย</span><span class="sxs-lookup"><span data-stu-id="a0852-128">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="a0852-129">การทำเช่นนั้น:</span><span class="sxs-lookup"><span data-stu-id="a0852-129">To do so:</span></span>
1.  <span data-ttu-id="a0852-130">เข้าสู่ระบบ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="a0852-130">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="a0852-131">เลือก**ลูกค้าของฉัน**</span><span class="sxs-lookup"><span data-stu-id="a0852-131">Select **My Customers**.</span></span>
3.  <span data-ttu-id="a0852-132">ค้นหาลูกค้าของคุณหรือเลือกจากรายชื่อลูกค้าของคุณ</span><span class="sxs-lookup"><span data-stu-id="a0852-132">Search for your customer or select them from your customer list.</span></span>
4.  <span data-ttu-id="a0852-133">เลือก**บริการ**</span><span class="sxs-lookup"><span data-stu-id="a0852-133">Select **Services**.</span></span>
5.  <span data-ttu-id="a0852-134">ทำการ**ร้องขอความช่วยเหลือด้วยแบบฟอร์ม Microsoft ๓๖๕**</span><span class="sxs-lookup"><span data-stu-id="a0852-134">Complete the **Request for Assistance with Microsoft 365** form.</span></span> 

<span data-ttu-id="a0852-135">ตารางต่อไปนี้แสดงรายการบทบาทและความรับผิดชอบสำหรับกระบวนการ</span><span class="sxs-lookup"><span data-stu-id="a0852-135">The following table lists roles and responsibilities for the process.</span></span>
    
|||
|:-----|:-----|
|<span data-ttu-id="a0852-136">**บทบาท**</span><span class="sxs-lookup"><span data-stu-id="a0852-136">**Role**</span></span> <br/> |<span data-ttu-id="a0852-137">**รับผิดชอบ**</span><span class="sxs-lookup"><span data-stu-id="a0852-137">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="a0852-138">**ผู้เชี่ยวชาญ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="a0852-138">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="a0852-139">ให้บริการการเตรียมการย้ายข้อมูลและการนำผู้ใช้ทั้งหมดจากระยะไกล</span><span class="sxs-lookup"><span data-stu-id="a0852-139">Provides all onboarding, migration, and user adoption services remotely.</span></span>  <br/> <span data-ttu-id="a0852-140">ช่วยเหลือคุณจากระยะไกลโดยใช้เครื่องมือและเอกสารที่เผยแพร่ร่วมกัน</span><span class="sxs-lookup"><span data-stu-id="a0852-140">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="a0852-141">ทำงานโดยตรงกับคุณหรือตัวแทนของคุณ</span><span class="sxs-lookup"><span data-stu-id="a0852-141">Works directly with you or your representative.</span></span> <br/> <span data-ttu-id="a0852-142">ให้คำแนะนำในการย้ายข้อมูลทางเมล</span><span class="sxs-lookup"><span data-stu-id="a0852-142">Provides email and data migration guidance.</span></span>|
|<span data-ttu-id="a0852-143">**ศูนย์ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="a0852-143">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="a0852-144">ให้คำแนะนำเกี่ยวกับการปฐมนิเทศหลักและบริการและการวางแผนการใช้บริการที่มีสิทธิ์ที่ประสบความสำเร็จ</span><span class="sxs-lookup"><span data-stu-id="a0852-144">Provides guidance with core and service onboarding and planning successful adoption of eligible services.</span></span>  <br/> <span data-ttu-id="a0852-145">ให้ความช่วยเหลือและมีให้บริการในช่วงเวลาทำการปกติสำหรับภูมิภาคที่กำหนด</span><span class="sxs-lookup"><span data-stu-id="a0852-145">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="a0852-146">ให้ความช่วยเหลือในภาษาจีนดั้งเดิมและจีน (ทรัพยากรที่พูดภาษาจีนกลางเท่านั้น), อังกฤษ, ฝรั่งเศส, เยอรมัน, อิตาลี, ญี่ปุ่น, เกาหลี, โปรตุเกส (บราซิล), สเปน, ไทยและเวียดนาม</span><span class="sxs-lookup"><span data-stu-id="a0852-146">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|


  

