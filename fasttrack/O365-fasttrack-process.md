---
title: กระบวนการ FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 3/03/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: กระบวนการ FastTrack ให้บริการปฐมนิเทศและผู้ใช้
ms.openlocfilehash: 0a0b25956542edf1a0bc6636918c4bbbb07e388c
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347665"
---
# <a name="the-fasttrack-process"></a><span data-ttu-id="d3232-103">กระบวนการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="d3232-103">The FastTrack Process</span></span>

<span data-ttu-id="d3232-104">กระบวนการ FastTrack ให้บริการปฐมนิเทศและผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="d3232-104">The FastTrack process provides onboarding and user adoption services.</span></span> 
  
<span data-ttu-id="d3232-105">ปฐมนิเทศประกอบด้วย:</span><span class="sxs-lookup"><span data-stu-id="d3232-105">Onboarding consists of:</span></span>
  
- <span data-ttu-id="d3232-106">*หลักปฐมนิเทศ*—เหล่านี้เป็นงานที่จำเป็นสำหรับการกำหนดค่าผู้เช่าและการรวมกับ Azure ใช้งานไดเรกทอรี (azure AD) ถ้าจำเป็น</span><span class="sxs-lookup"><span data-stu-id="d3232-106">*Core onboarding* — These are tasks required for tenant configuration and integration with Azure Active Directory (Azure AD) if needed.</span></span> <span data-ttu-id="d3232-107">หลักปฐมนิเทศยังให้ข้อมูลพื้นฐานสำหรับการปฐมนิเทศบริการที่มีสิทธิ์อื่นๆ</span><span class="sxs-lookup"><span data-stu-id="d3232-107">Core onboarding also provides the baseline for onboarding other eligible services.</span></span> 
- <span data-ttu-id="d3232-108">*บริการปฐมนิเทศและการโยกย้าย*—งานปฐมนิเทศบริการเปิดใช้งานสถานการณ์ในผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="d3232-108">*Service onboarding and migration* — Service onboarding tasks enable scenarios in your tenant.</span></span> <span data-ttu-id="d3232-109">การย้ายข้อมูล (รวมถึงอีเมลและไฟล์) จะครอบคลุมในการ[ย้ายข้อมูล](O365-data-migration.md)</span><span class="sxs-lookup"><span data-stu-id="d3232-109">Data migration (including email and files) is covered in [Data Migration](O365-data-migration.md).</span></span> 
    
<span data-ttu-id="d3232-110">บริการการยอมรับผู้ใช้จะประกอบด้วยงานที่ให้คำแนะนำแก่คุณเพื่อให้ผู้ใช้ทราบถึงบริการที่มีสิทธิ์และสามารถใช้พวกเขาในการขับค่าทางธุรกิจ</span><span class="sxs-lookup"><span data-stu-id="d3232-110">User adoption services are comprised of tasks that provide guidance for you to ensure your users are aware of the eligible services and can use them to drive business value.</span></span> <span data-ttu-id="d3232-111">ความช่วยเหลือนี้จะเกิดขึ้นควบคู่ไปกับกิจกรรมปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="d3232-111">This assistance occurs in parallel to onboarding activities.</span></span>
  
> [!NOTE]
> <span data-ttu-id="d3232-112">FastTrack ให้ลูกค้าด้วยวิธีการที่แนะนำคำแนะนำและแนวทางปฏิบัติที่ดีที่สุดที่ออกแบบมาเพื่อให้ผลลัพธ์ที่รวดเร็วและคาดเดาได้</span><span class="sxs-lookup"><span data-stu-id="d3232-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="d3232-113">ถ้าคุณเลือกที่จะปรับใช้ภายนอกของคำแนะนำนี้, ประสบการณ์ปฐมนิเทศของคุณและการใช้งานของบริการอาจได้รับผลกระทบ.</span><span class="sxs-lookup"><span data-stu-id="d3232-113">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="d3232-114">คำแนะนำถูกกำหนดเป็นการรวมกันของการให้ความช่วยเหลือทางวาจาและเป็นลายลักษณ์อักษร</span><span class="sxs-lookup"><span data-stu-id="d3232-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="d3232-115">เมื่อผู้เชี่ยวชาญ FastTrack ให้คำแนะนำ, เจ้าหน้าที่ FastTrack ไม่สามารถดำเนินการในนามของคุณ.</span><span class="sxs-lookup"><span data-stu-id="d3232-115">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="d3232-116">คุณสามารถใช้บริการ FastTrack กับออนบอร์ดและนำค่าปริมาณของผลิตภัณฑ์ที่มีคุณสมบัติเหมาะสมตราบใดที่การสมัครใช้งานของคุณเป็นปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="d3232-116">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span> 
  
## <a name="the-onboarding-process"></a><span data-ttu-id="d3232-117">กระบวนการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="d3232-117">The onboarding process</span></span>

<span data-ttu-id="d3232-118">แผนภาพต่อไปนี้แสดงให้เห็นถึงกระบวนการปฐมนิเทศ</span><span class="sxs-lookup"><span data-stu-id="d3232-118">The following diagram illustrates the onboarding process.</span></span>
  
![ระยะเวลาในการใช้ประโยชน์ปฐมนิเทศ](media/O365-Onboarding-Timeline.png)
  
<span data-ttu-id="d3232-120">คุณสามารถขอรับความช่วยเหลือผ่านทาง[Microsoft ๓๖๕ admin ศูนย์](https://go.microsoft.com/fwlink/?linkid=2032704)หรือ[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="d3232-120">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 

<span data-ttu-id="d3232-121">หากต้องการรับความช่วยเหลือผ่าน[ศูนย์การดูแล Microsoft ๓๖๕](https://go.microsoft.com/fwlink/?linkid=2032704)ผู้ดูแลของคุณจะลงชื่อเข้าใช้ศูนย์การดูแลจากนั้นคลิก**ต้องการความช่วยเหลือ**วิดเจ็ต</span><span class="sxs-lookup"><span data-stu-id="d3232-121">To get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704), your admin signs into the admin center and then clicks the **Need help?** widget.</span></span> 

<span data-ttu-id="d3232-122">เมื่อต้องการรับความช่วยเหลือผ่าน[เว็บไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698):</span><span class="sxs-lookup"><span data-stu-id="d3232-122">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.  <span data-ttu-id="d3232-123">ลงชื่อเข้าใช้ใน[เว็บไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="d3232-123">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="d3232-124">เลือก**คำขอความช่วยเหลือสำหรับ Microsoft ๓๖๕**จาก**การดำเนินการด่วน**ที่ด้านบนของเพจเริ่มต้นของคุณหรือโดยการเลือก**คำขอความช่วยเหลือสำหรับ Microsoft ๓๖๕**บนการ์ดการปรับใช้</span><span class="sxs-lookup"><span data-stu-id="d3232-124">Select **Request assistance for Microsoft 365** from the **quick actions** on the top of your landing page or by selecting **Request assistance for Microsoft 365** on the deploy card.</span></span>
3.  <span data-ttu-id="d3232-125">ดำเนินการความ**ช่วยเหลือในการร้องขอสำหรับ Microsoft ๓๖๕**ฟอร์ม</span><span class="sxs-lookup"><span data-stu-id="d3232-125">Complete the **Request Assistance for Microsoft 365** form.</span></span> 
  
 <span data-ttu-id="d3232-126">นอกจากนี้คุณยังสามารถขอความช่วยเหลือศูนย์ FastTrack จาก[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในรายการบริการที่พร้อมใช้งานสำหรับผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="d3232-126">You can also ask for FastTrack Center help from the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) in the list of available services for your tenant.</span></span> 
    
 <span data-ttu-id="d3232-127">เมื่อเริ่มต้นความช่วยเหลือปฐมนิเทศเราตั้งตารางเวลาของการประชุมแบบออนไลน์</span><span class="sxs-lookup"><span data-stu-id="d3232-127">Once onboarding assistance starts, we set up a schedule of online meetings.</span></span>
    
<span data-ttu-id="d3232-128">นอกจากนี้คู่ค้ายังสามารถรับความช่วยเหลือผ่าน[ไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)ในนามของลูกค้าได้ด้วย</span><span class="sxs-lookup"><span data-stu-id="d3232-128">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="d3232-129">เมื่อต้องการทำเช่นนั้น:</span><span class="sxs-lookup"><span data-stu-id="d3232-129">To do so:</span></span>
1.  <span data-ttu-id="d3232-130">ลงชื่อเข้าใช้ใน[เว็บไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="d3232-130">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="d3232-131">เลือก**ลูกค้าของฉัน**</span><span class="sxs-lookup"><span data-stu-id="d3232-131">Select **My Customers**.</span></span>
3.  <span data-ttu-id="d3232-132">ค้นหาลูกค้าของคุณหรือเลือกจากรายชื่อลูกค้าของคุณ</span><span class="sxs-lookup"><span data-stu-id="d3232-132">Search for your customer or select them from your customer list.</span></span>
4.  <span data-ttu-id="d3232-133">เลือก**บริการ**</span><span class="sxs-lookup"><span data-stu-id="d3232-133">Select **Services**.</span></span>
5.  <span data-ttu-id="d3232-134">ดำเนินการความ**ช่วยเหลือในการร้องขอสำหรับ Microsoft ๓๖๕**ฟอร์ม</span><span class="sxs-lookup"><span data-stu-id="d3232-134">Complete the **Request Assistance for Microsoft 365** form.</span></span> 

<span data-ttu-id="d3232-135">ตารางต่อไปนี้แสดงบทบาทและความรับผิดชอบสำหรับกระบวนการ</span><span class="sxs-lookup"><span data-stu-id="d3232-135">The following table lists roles and responsibilities for the process.</span></span>
    
|||
|:-----|:-----|
|<span data-ttu-id="d3232-136">**บทบาท**</span><span class="sxs-lookup"><span data-stu-id="d3232-136">**Role**</span></span> <br/> |<span data-ttu-id="d3232-137">**ชอบ**</span><span class="sxs-lookup"><span data-stu-id="d3232-137">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="d3232-138">**ผู้เชี่ยวชาญ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="d3232-138">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="d3232-139">ให้บริการปฐมนิเทศการย้ายและผู้ใช้ทั้งหมดจากระยะไกล</span><span class="sxs-lookup"><span data-stu-id="d3232-139">Provides all onboarding, migration, and user adoption services remotely.</span></span>  <br/> <span data-ttu-id="d3232-140">ช่วยให้คุณจากระยะไกลโดยใช้การรวมกันของเครื่องมือและเอกสารที่เผยแพร่</span><span class="sxs-lookup"><span data-stu-id="d3232-140">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="d3232-141">ทำงานโดยตรงกับคุณหรือตัวแทนของคุณ</span><span class="sxs-lookup"><span data-stu-id="d3232-141">Works directly with you or your representative.</span></span> <br/> <span data-ttu-id="d3232-142">ให้คำแนะนำในการถ่ายโอนอีเมล์และข้อมูล</span><span class="sxs-lookup"><span data-stu-id="d3232-142">Provides email and data migration guidance.</span></span>|
|<span data-ttu-id="d3232-143">**ศูนย์ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="d3232-143">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="d3232-144">ให้คำแนะนำเกี่ยวกับหลักและบริการปฐมนิเทศและการวางแผนการนำบริการที่มีสิทธิ์สำเร็จ</span><span class="sxs-lookup"><span data-stu-id="d3232-144">Provides guidance with core and service onboarding and planning successful adoption of eligible services.</span></span>  <br/> <span data-ttu-id="d3232-145">ให้ความช่วยเหลือและสามารถใช้ได้ในช่วงเวลาทำการปกติสำหรับภูมิภาคที่กำหนด</span><span class="sxs-lookup"><span data-stu-id="d3232-145">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="d3232-146">ให้ความช่วยเหลือในภาษาจีนแบบดั้งเดิมและภาษาจีน (ทรัพยากรพูดภาษาจีนกลางเท่านั้น), อังกฤษ, ฝรั่งเศส, เยอรมัน, อิตาลี, ญี่ปุ่น, เกาหลี, โปรตุเกส (บราซิล), สเปน, ไทย, และเวียดนาม</span><span class="sxs-lookup"><span data-stu-id="d3232-146">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|


  

