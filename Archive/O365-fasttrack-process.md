---
title: กระบวนการ FastTrack
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: กระบวนการ FastTrack มีบริการการออนบอร์ดและการนํามาใช้ของผู้ใช้
ms.openlocfilehash: 6d13e6fc9247196c9a2e6cf7692abf3fa75152dc
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283499"
---
# <a name="the-fasttrack-process"></a><span data-ttu-id="b6611-103">กระบวนการ FastTrack</span><span class="sxs-lookup"><span data-stu-id="b6611-103">The FastTrack Process</span></span>

> [!CAUTION]
> <span data-ttu-id="b6611-104">เนื้อหานี้จะไม่ใช่เนื้อหาปัจจุบันอีกต่อไปและถูกจัดเวลาให้เอาออก</span><span class="sxs-lookup"><span data-stu-id="b6611-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="b6611-105">ใช้สารบัญในการนําทางด้านซ้ายมือกับเนื้อหาปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="b6611-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="b6611-106">กระบวนการ FastTrack มีบริการการออนบอร์ดและการนํามาใช้ของผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="b6611-106">The FastTrack process provides onboarding and user adoption services.</span></span> 
  
<span data-ttu-id="b6611-107">Onboarding ประกอบด้วย:</span><span class="sxs-lookup"><span data-stu-id="b6611-107">Onboarding consists of:</span></span>
  
- <span data-ttu-id="b6611-108">*การออนบอร์ดหลัก*— นี่คืองานที่ต้องใช้ในการกําหนดค่าและการรวมผู้เช่าAzure Active Directory (Azure AD) ถ้าต้องการ</span><span class="sxs-lookup"><span data-stu-id="b6611-108">*Core onboarding* — These are tasks required for tenant configuration and integration with Azure Active Directory (Azure AD) if needed.</span></span> <span data-ttu-id="b6611-109">การออนบอร์ดหลักยังมอบข้อมูลพื้นฐานในการออนบอร์ดบริการอื่นๆ ที่มีสิทธิ์อีกด้วย</span><span class="sxs-lookup"><span data-stu-id="b6611-109">Core onboarding also provides the baseline for onboarding other eligible services.</span></span> 
- <span data-ttu-id="b6611-110">*การออนบอร์ดและการโยกย้ายบริการ* — งานการออนบอร์ดบริการจะเปิดใช้งานสถานการณ์สมมติในผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="b6611-110">*Service onboarding and migration* — Service onboarding tasks enable scenarios in your tenant.</span></span> <span data-ttu-id="b6611-111">การโยกย้ายข้อมูล (รวมถึงอีเมลและไฟล์) จะ [ครอบคลุมในการโยกย้าย](O365-data-migration.md)ข้อมูล</span><span class="sxs-lookup"><span data-stu-id="b6611-111">Data migration (including email and files) is covered in [Data Migration](O365-data-migration.md).</span></span> 
    
<span data-ttu-id="b6611-112">บริการการเริ่มนํามาใช้ของผู้ใช้ประกอบด้วยงานที่มีแนวทางสําหรับคุณเพื่อให้แน่ใจว่าผู้ใช้ของคุณตระหนักถึงบริการที่มีสิทธิ์และสามารถใช้เพื่อผลักดันมูลค่าทางธุรกิจได้</span><span class="sxs-lookup"><span data-stu-id="b6611-112">User adoption services are comprised of tasks that provide guidance for you to ensure your users are aware of the eligible services and can use them to drive business value.</span></span> <span data-ttu-id="b6611-113">ความช่วยเหลือนี้จะเกิดขึ้นควบคู่ไปกับกิจกรรมการออนบอร์ด</span><span class="sxs-lookup"><span data-stu-id="b6611-113">This assistance occurs in parallel to onboarding activities.</span></span>
  
> [!NOTE]
> <span data-ttu-id="b6611-114">FastTrack จะให้วิธีการที่แนะนํา แนวทาง และแนวทางปฏิบัติที่แนะนําซึ่งออกแบบมาเพื่อให้ผลลัพธ์ที่รวดเร็วและคาดการณ์ได้</span><span class="sxs-lookup"><span data-stu-id="b6611-114">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="b6611-115">หากคุณเลือกที่จะปรับใช้ภายนอกแนวทางนี้ ประสบการณ์การออนบอร์ดและการใช้งานบริการของคุณอาจได้รับผลกระทบ</span><span class="sxs-lookup"><span data-stu-id="b6611-115">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="b6611-116">การแนะนําจะถูกกําหนดเป็นการผสมของความช่วยเหลือด้วยวาจาและที่เป็นลายลักษณ์อักษร</span><span class="sxs-lookup"><span data-stu-id="b6611-116">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="b6611-117">เมื่อผู้เชี่ยวชาญด้าน FastTrack ให้แนวทาง FastTrack บุคลากรจะไม่สามารถกระทาการในนามของคุณได้</span><span class="sxs-lookup"><span data-stu-id="b6611-117">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="b6611-118">คุณสามารถใช้บริการ FastTrack เพื่อออนบอร์ดและปรับใช้ปริมาณงานของผลิตภัณฑ์ที่มีคุณสมบัติเหมาะสมได้ตราบใดที่การสมัครใช้งานของคุณอยู่ในปัจจุบัน</span><span class="sxs-lookup"><span data-stu-id="b6611-118">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span> 
  
## <a name="the-onboarding-process"></a><span data-ttu-id="b6611-119">กระบวนการออนบอร์ด</span><span class="sxs-lookup"><span data-stu-id="b6611-119">The onboarding process</span></span>

<span data-ttu-id="b6611-120">ไดอะแกรมต่อไปนี้แสดงกระบวนการออนบอร์ด</span><span class="sxs-lookup"><span data-stu-id="b6611-120">The following diagram illustrates the onboarding process.</span></span>
  
![ไทม์ไลน์ในการใช้สิทธิประโยชน์ Onboarding](media/o365-onboarding-timeline-m365-apps.png)
  
<span data-ttu-id="b6611-122">คุณสามารถรับความช่วยเหลือผ่าน[ศูนย์Microsoft 365หรือ](https://go.microsoft.com/fwlink/?linkid=2032704)ไซต์[FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="b6611-122">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 

<span data-ttu-id="b6611-123">เมื่อต้องการรับความช่วยเหลือผ่าน [Microsoft 365ผู้ดูแลระบบ](https://go.microsoft.com/fwlink/?linkid=2032704)ของคุณ ลงชื่อเข้าใช้ในศูนย์การจัดการ แล้วคลิกวิดเจ็ต **ต้องการ** ความช่วยเหลือหรือไม่</span><span class="sxs-lookup"><span data-stu-id="b6611-123">To get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704), your admin signs into the admin center and then clicks the **Need help?** widget.</span></span> 

<span data-ttu-id="b6611-124">เมื่อต้องการรับความช่วยเหลือผ่านไซต์[FastTrack:](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="b6611-124">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="b6611-125">ลงชื่อเข้าใช้ไซต์[FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="b6611-125">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="b6611-126">เลือก **ขอความช่วยเหลือเกี่ยวกับMicrosoft 365** จาก **การด่วน** ที่ด้านบนของเพจเริ่มต้นของคุณ</span><span class="sxs-lookup"><span data-stu-id="b6611-126">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="b6611-127">กรอกฟอร์ม **ความช่วยเหลือในMicrosoft 365** เอกสาร</span><span class="sxs-lookup"><span data-stu-id="b6611-127">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="b6611-128">คู่ค้ายังสามารถรับความช่วยเหลือ [ผ่านไซต์ FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) ในนามของลูกค้า</span><span class="sxs-lookup"><span data-stu-id="b6611-128">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="b6611-129">วิธีการ:</span><span class="sxs-lookup"><span data-stu-id="b6611-129">To do so:</span></span>
1.    <span data-ttu-id="b6611-130">ลงชื่อเข้าใช้ไซต์[FastTrack](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="b6611-130">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="b6611-131">เลือก **ขอความช่วยเหลือเกี่ยวกับMicrosoft 365** จาก **การด่วน** ที่ด้านบนของเพจเริ่มต้นของคุณ</span><span class="sxs-lookup"><span data-stu-id="b6611-131">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="b6611-132">ค้นหาลูกค้าของคุณโดยการใส่ชื่อลูกค้า โดเมน หรือ TPID</span><span class="sxs-lookup"><span data-stu-id="b6611-132">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="b6611-133">เลือกลูกค้าจากผลลัพธ์การค้นหา</span><span class="sxs-lookup"><span data-stu-id="b6611-133">Select customer from the search results.</span></span>
5.    <span data-ttu-id="b6611-134">กรอกฟอร์ม **ความช่วยเหลือในMicrosoft 365** เอกสาร</span><span class="sxs-lookup"><span data-stu-id="b6611-134">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
 <span data-ttu-id="b6611-135">คุณยังสามารถขอความช่วยเหลือจากศูนย์ FastTrack จากไซต์ [FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) ในรายการบริการที่พร้อมใช้งานของผู้เช่าของคุณ</span><span class="sxs-lookup"><span data-stu-id="b6611-135">You can also ask for FastTrack Center help from the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) in the list of available services for your tenant.</span></span> 
    
 <span data-ttu-id="b6611-136">เมื่อความช่วยเหลือในการออนบอร์ดเริ่มขึ้น เราจะตั้งค่าตารางการประชุมออนไลน์</span><span class="sxs-lookup"><span data-stu-id="b6611-136">Once onboarding assistance starts, we set up a schedule of online meetings.</span></span>

<span data-ttu-id="b6611-137">ตารางต่อไปนี้แสดงรายการบทบาทและความรับผิดชอบของกระบวนการ</span><span class="sxs-lookup"><span data-stu-id="b6611-137">The following table lists roles and responsibilities for the process.</span></span>
    
|||
|:-----|:-----|
|<span data-ttu-id="b6611-138">**บทบาท**</span><span class="sxs-lookup"><span data-stu-id="b6611-138">**Role**</span></span> <br/> |<span data-ttu-id="b6611-139">**ความรับผิดชอบ**</span><span class="sxs-lookup"><span data-stu-id="b6611-139">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="b6611-140">**ผู้เชี่ยวชาญด้าน FastTrack**</span><span class="sxs-lookup"><span data-stu-id="b6611-140">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="b6611-141">ให้บริการการออนบอร์ด การโยกย้าย และการนํามาใช้ของผู้ใช้ทั้งหมดจากระยะไกล</span><span class="sxs-lookup"><span data-stu-id="b6611-141">Provides all onboarding, migration, and user adoption services remotely.</span></span>  <br/> <span data-ttu-id="b6611-142">ช่วยเหลือคุณจากระยะไกลโดยใช้เครื่องมือและเอกสารที่เผยแพร่ร่วมกัน</span><span class="sxs-lookup"><span data-stu-id="b6611-142">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="b6611-143">ติดต่อคุณหรือตัวแทนของคุณโดยตรง</span><span class="sxs-lookup"><span data-stu-id="b6611-143">Works directly with you or your representative.</span></span> <br/> <span data-ttu-id="b6611-144">ให้แนวทางการโยกย้ายอีเมลและข้อมูล</span><span class="sxs-lookup"><span data-stu-id="b6611-144">Provides email and data migration guidance.</span></span>|
|<span data-ttu-id="b6611-145">**ศูนย์ FastTrack**</span><span class="sxs-lookup"><span data-stu-id="b6611-145">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="b6611-146">ให้แนวทางพร้อมการออนบอร์ดหลักและบริการและการวางแผนการปรับใช้บริการที่มีสิทธิ์ได้สเร็จ</span><span class="sxs-lookup"><span data-stu-id="b6611-146">Provides guidance with core and service onboarding and planning successful adoption of eligible services.</span></span>  <br/> <span data-ttu-id="b6611-147">ให้ความช่วยเหลือและพร้อมให้ใช้งานในระหว่างชั่วโมงการงานปกติในภูมิภาคที่ระบุ</span><span class="sxs-lookup"><span data-stu-id="b6611-147">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="b6611-148">ให้ความช่วยเหลือในภาษาจีนดั้งเดิมและภาษาจีนประยุกต์ (แหล่งข้อมูลที่พูดจีนกลางเท่านั้น), อังกฤษ, ฝรั่งเศส, เยอรมัน, อิตาลี, ญี่ปุ่น, เกาหลี, โปรตุเกส (บราซิล), สเปน, ไทย และเวียดนาม</span><span class="sxs-lookup"><span data-stu-id="b6611-148">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
