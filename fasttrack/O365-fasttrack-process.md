---
title: กระบวนการ FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 2/04/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: กระบวนการ FastTrack ให้บริการปฐมนิเทศและผู้ใช้
ms.openlocfilehash: a1c67af6c9bb19c967afcd32ba46ebc550068fd7
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 02/03/2020
ms.locfileid: "41677085"
---
# <a name="the-fasttrack-process"></a><span data-ttu-id="7d119-103">กระบวนการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="7d119-103">The FastTrack Process</span></span>

<span data-ttu-id="7d119-104">กระบวนการ FastTrack ให้บริการปฐมนิเทศและผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="7d119-104">The FastTrack process provides onboarding and user adoption services.</span></span> 
  
<span data-ttu-id="7d119-105">ปฐมนิเทศประกอบด้วย:</span><span class="sxs-lookup"><span data-stu-id="7d119-105">Onboarding consists of:</span></span>
  
- <span data-ttu-id="7d119-106">*หลักปฐมนิเทศ*—เหล่านี้เป็นงานที่จำเป็นสำหรับการกำหนดค่าผู้เช่าและการรวมกับ Azure ใช้งานไดเรกทอรี (azure AD) ถ้าจำเป็น</span><span class="sxs-lookup"><span data-stu-id="7d119-106">*Core onboarding* — These are tasks required for tenant configuration and integration with Azure Active Directory (Azure AD) if needed.</span></span> <span data-ttu-id="7d119-107">หลักปฐมนิเทศยังให้ข้อมูลพื้นฐานสำหรับการปฐมนิเทศบริการที่มีสิทธิ์อื่นๆ</span><span class="sxs-lookup"><span data-stu-id="7d119-107">Core onboarding also provides the baseline for onboarding other eligible services.</span></span> 
- <span data-ttu-id="7d119-108">*บริการปฐมนิเทศและการโยกย้าย*—งานปฐมนิเทศบริการเปิดใช้งานสถานการณ์ในผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="7d119-108">*Service onboarding and migration* — Service onboarding tasks enable scenarios in your tenant.</span></span> <span data-ttu-id="7d119-109">การย้ายข้อมูล (รวมถึงอีเมลและไฟล์) จะครอบคลุมในการ[ย้ายข้อมูล](O365-data-migration.md)</span><span class="sxs-lookup"><span data-stu-id="7d119-109">Data migration (including email and files) is covered in [Data Migration](O365-data-migration.md).</span></span> 
    
<span data-ttu-id="7d119-110">บริการการยอมรับผู้ใช้จะประกอบด้วยงานที่ให้คำแนะนำแก่คุณเพื่อให้ผู้ใช้ทราบถึงบริการที่มีสิทธิ์และสามารถใช้พวกเขาในการขับค่าทางธุรกิจ</span><span class="sxs-lookup"><span data-stu-id="7d119-110">User adoption services are comprised of tasks that provide guidance for you to ensure your users are aware of the eligible services and can use them to drive business value.</span></span> <span data-ttu-id="7d119-111">ความช่วยเหลือนี้จะเกิดขึ้นควบคู่ไปกับกิจกรรมปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="7d119-111">This assistance occurs in parallel to onboarding activities.</span></span>
  
> [!NOTE]
> <span data-ttu-id="7d119-112">FastTrack ให้ลูกค้าด้วยวิธีการที่แนะนำคำแนะนำและแนวทางปฏิบัติที่ดีที่สุดที่ออกแบบมาเพื่อให้ผลลัพธ์ที่รวดเร็วและคาดเดาได้</span><span class="sxs-lookup"><span data-stu-id="7d119-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="7d119-113">ถ้าคุณเลือกที่จะปรับใช้ภายนอกของคำแนะนำนี้, ประสบการณ์ปฐมนิเทศของคุณและการใช้งานของบริการอาจได้รับผลกระทบ.</span><span class="sxs-lookup"><span data-stu-id="7d119-113">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="7d119-114">คำแนะนำถูกกำหนดเป็นการรวมกันของการให้ความช่วยเหลือทางวาจาและเป็นลายลักษณ์อักษร</span><span class="sxs-lookup"><span data-stu-id="7d119-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="7d119-115">เมื่อผู้เชี่ยวชาญ FastTrack ให้คำแนะนำ, เจ้าหน้าที่ FastTrack ไม่สามารถดำเนินการในนามของคุณ.</span><span class="sxs-lookup"><span data-stu-id="7d119-115">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="7d119-116">คุณสามารถใช้บริการ FastTrack กับออนบอร์ดและนำค่าปริมาณของผลิตภัณฑ์ที่มีคุณสมบัติเหมาะสมตราบใดที่การสมัครใช้งานของคุณเป็นปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="7d119-116">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span> 
  
## <a name="the-onboarding-process"></a><span data-ttu-id="7d119-117">กระบวนการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="7d119-117">The onboarding process</span></span>

<span data-ttu-id="7d119-118">แผนภาพต่อไปนี้แสดงให้เห็นถึงกระบวนการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="7d119-118">The following diagram illustrates the onboarding process.</span></span>
  
![ระยะเวลาในการใช้ประโยชน์ปฐมนิเทศ](media/O365-Onboarding-Timeline.png)
  
<span data-ttu-id="7d119-120">คุณสามารถขอรับความช่วยเหลือผ่านทาง[Microsoft ๓๖๕ admin ศูนย์](https://go.microsoft.com/fwlink/?linkid=2032704)หรือ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="7d119-120">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 

<span data-ttu-id="7d119-121">หากต้องการรับความช่วยเหลือผ่าน[ศูนย์การดูแล Microsoft ๓๖๕](https://go.microsoft.com/fwlink/?linkid=2032704)ผู้ดูแลของคุณจะลงชื่อเข้าใช้ศูนย์การดูแลจากนั้นคลิก**ต้องการความช่วยเหลือ**วิดเจ็ต</span><span class="sxs-lookup"><span data-stu-id="7d119-121">To get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704), your admin signs into the admin center and then clicks the **Need help?** widget.</span></span> 

<span data-ttu-id="7d119-122">เมื่อต้องการรับความช่วยเหลือผ่าน[เว็บไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698):</span><span class="sxs-lookup"><span data-stu-id="7d119-122">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.  <span data-ttu-id="7d119-123">ลงชื่อเข้าใช้ใน[เว็บไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="7d119-123">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="7d119-124">เลือก**บริการ**</span><span class="sxs-lookup"><span data-stu-id="7d119-124">Select **Services**.</span></span>
3.  <span data-ttu-id="7d119-125">ทำการ**ร้องขอความช่วยเหลือให้เสร็จสมบูรณ์ด้วย Microsoft ๓๖๕**ฟอร์ม</span><span class="sxs-lookup"><span data-stu-id="7d119-125">Complete the **Request for Assistance with Microsoft 365** form.</span></span> 
  
 <span data-ttu-id="7d119-126">นอกจากนี้คุณยังสามารถขอความช่วยเหลือศูนย์ FastTrack จาก[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในรายการบริการที่พร้อมใช้งานสำหรับผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="7d119-126">You can also ask for FastTrack Center help from the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) in the list of available services for your tenant.</span></span> 
    
 <span data-ttu-id="7d119-127">เมื่อเริ่มต้นความช่วยเหลือปฐมนิเทศเราตั้งตารางเวลาของการประชุมแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="7d119-127">Once onboarding assistance starts, we set up a schedule of online meetings.</span></span>
    
<span data-ttu-id="7d119-128">นอกจากนี้คู่ค้ายังสามารถรับความช่วยเหลือผ่าน[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในนามของลูกค้าได้ด้วย</span><span class="sxs-lookup"><span data-stu-id="7d119-128">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="7d119-129">เมื่อต้องการทำเช่นนั้น:</span><span class="sxs-lookup"><span data-stu-id="7d119-129">To do so:</span></span>
1.  <span data-ttu-id="7d119-130">ลงชื่อเข้าใช้ใน[เว็บไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="7d119-130">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="7d119-131">เลือก**ลูกค้าของฉัน**</span><span class="sxs-lookup"><span data-stu-id="7d119-131">Select **My Customers**.</span></span>
3.  <span data-ttu-id="7d119-132">ค้นหาลูกค้าของคุณหรือเลือกจากรายชื่อลูกค้าของคุณ</span><span class="sxs-lookup"><span data-stu-id="7d119-132">Search for your customer or select them from your customer list.</span></span>
4.  <span data-ttu-id="7d119-133">เลือก**บริการ**</span><span class="sxs-lookup"><span data-stu-id="7d119-133">Select **Services**.</span></span>
5.  <span data-ttu-id="7d119-134">ทำการ**ร้องขอความช่วยเหลือให้เสร็จสมบูรณ์ด้วย Microsoft ๓๖๕**ฟอร์ม</span><span class="sxs-lookup"><span data-stu-id="7d119-134">Complete the **Request for Assistance with Microsoft 365** form.</span></span> 

<span data-ttu-id="7d119-135">ตารางต่อไปนี้แสดงบทบาทและความรับผิดชอบสำหรับกระบวนการ</span><span class="sxs-lookup"><span data-stu-id="7d119-135">The following table lists roles and responsibilities for the process.</span></span>
    
|||
|:-----|:-----|
|<span data-ttu-id="7d119-136">**บทบาท**</span><span class="sxs-lookup"><span data-stu-id="7d119-136">**Role**</span></span> <br/> |<span data-ttu-id="7d119-137">**ชอบ**</span><span class="sxs-lookup"><span data-stu-id="7d119-137">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="7d119-138">**ผู้เชี่ยวชาญ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="7d119-138">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="7d119-139">ให้บริการปฐมนิเทศการย้ายและผู้ใช้ทั้งหมดจากระยะไกล</span><span class="sxs-lookup"><span data-stu-id="7d119-139">Provides all onboarding, migration, and user adoption services remotely.</span></span>  <br/> <span data-ttu-id="7d119-140">ช่วยให้คุณจากระยะไกลโดยใช้การรวมกันของเครื่องมือและเอกสารที่เผยแพร่</span><span class="sxs-lookup"><span data-stu-id="7d119-140">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="7d119-141">ทำงานโดยตรงกับคุณหรือตัวแทนของคุณ</span><span class="sxs-lookup"><span data-stu-id="7d119-141">Works directly with you or your representative.</span></span> <br/> <span data-ttu-id="7d119-142">ให้คำแนะนำในการถ่ายโอนอีเมล์และข้อมูล</span><span class="sxs-lookup"><span data-stu-id="7d119-142">Provides email and data migration guidance.</span></span>|
|<span data-ttu-id="7d119-143">**ศูนย์ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="7d119-143">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="7d119-144">ให้คำแนะนำเกี่ยวกับหลักและบริการปฐมนิเทศและการวางแผนการนำบริการที่มีสิทธิ์สำเร็จ</span><span class="sxs-lookup"><span data-stu-id="7d119-144">Provides guidance with core and service onboarding and planning successful adoption of eligible services.</span></span>  <br/> <span data-ttu-id="7d119-145">ให้ความช่วยเหลือและสามารถใช้ได้ในช่วงเวลาทำการปกติสำหรับภูมิภาคที่กำหนด</span><span class="sxs-lookup"><span data-stu-id="7d119-145">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="7d119-146">ให้ความช่วยเหลือในภาษาจีนแบบดั้งเดิมและภาษาจีน (ทรัพยากรพูดภาษาจีนกลางเท่านั้น), อังกฤษ, ฝรั่งเศส, เยอรมัน, อิตาลี, ญี่ปุ่น, เกาหลี, โปรตุเกส (บราซิล), สเปน, ไทย, และเวียดนาม</span><span class="sxs-lookup"><span data-stu-id="7d119-146">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|


  

