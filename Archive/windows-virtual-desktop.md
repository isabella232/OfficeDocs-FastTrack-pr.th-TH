---
title: Windows เดสก์ท็อปเสมือน
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack Windowsแนะนําการปรับใช้เดสก์ท็อปเสมือนที่จะช่วยคุณออนบอร์ดบนเดสก์ท็อปนี้
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283460"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="7b289-103">Windows เดสก์ท็อปเสมือน</span><span class="sxs-lookup"><span data-stu-id="7b289-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7b289-104"><strong>บริการ</strong></span><span class="sxs-lookup"><span data-stu-id="7b289-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7b289-105"><strong>รายละเอียดแนวทาง FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="7b289-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="7b289-106"><strong>ข้อกำหนดของสภาพแวดล้อมต้นทาง</strong></span><span class="sxs-lookup"><span data-stu-id="7b289-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="7b289-107">Windows เดสก์ท็อปเสมือน</span><span class="sxs-lookup"><span data-stu-id="7b289-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="7b289-108">FastTrack มอบแนวทางการปรับใช้ Windows Virtual Desktop เพื่อช่วยให้คุณออนบอร์ดในบริการการเสมือนของเดสก์ท็อปและแอปนี้ได้อย่างง่ายดายในขณะที่ใช้ประโยชน์จากประสบการณ์การใช้งานหลายเซสชันของ Windows 10 ซึ่งได้รับการปรับให้เหมาะสมกับ Microsoft 365 Apps สําหรับองค์กรด้วยการรักษาความปลอดภัยและการจัดการแบบรวมสําหรับ Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="7b289-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="7b289-109">คุณร่วมงานกับผู้เชี่ยวชาญด้าน FastTrack เพื่อ:</span><span class="sxs-lookup"><span data-stu-id="7b289-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-110">ปรับใช้สภาพแวดล้อม WVD Windows 10 Enterpriseหลายเซสชัน + Microsoft 365 Apps for Enterprise โดยใช้สิ่งต่อไปนี้:</span><span class="sxs-lookup"><span data-stu-id="7b289-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-111">รูป Azure Marketplace</span><span class="sxs-lookup"><span data-stu-id="7b289-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="7b289-112">รูปภาพที่แชร์</span><span class="sxs-lookup"><span data-stu-id="7b289-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="7b289-113">Office Deployment Toolkit (ODT)</span><span class="sxs-lookup"><span data-stu-id="7b289-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="7b289-114">กําหนดค่า FSLogix</span><span class="sxs-lookup"><span data-stu-id="7b289-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-115">ปรับใช้ตัวแทน FSLogix กับคอนเทนเนอร์โปรไฟล์</span><span class="sxs-lookup"><span data-stu-id="7b289-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="7b289-116">ปรับใช้ตัวแทน FSLogix กับOfficeคอนเทนเนอร์</span><span class="sxs-lookup"><span data-stu-id="7b289-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="7b289-117">กําหนดค่าโฟลเดอร์ FSLogix ที่มีการแยกเนื้อหาออก</span><span class="sxs-lookup"><span data-stu-id="7b289-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="7b289-118">ปรับใช้Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="7b289-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="7b289-119">ปรับใช้Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="7b289-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="7b289-120">เชื่อมต่อไคลเอ็นต์Windowsเดสก์ท็อปเสมือน</span><span class="sxs-lookup"><span data-stu-id="7b289-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="7b289-121"><strong>ต่อไปนี้เป็นการไม่อยู่ในขอบเขต</strong></span><span class="sxs-lookup"><span data-stu-id="7b289-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-122">Projectการจัดการการปรับใช้เดสก์ท็อปเสมือนWindowsของลูกค้า</span><span class="sxs-lookup"><span data-stu-id="7b289-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="7b289-123">การสนับสนุนในสถานที่</span><span class="sxs-lookup"><span data-stu-id="7b289-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="7b289-124">การเสมือน/การปรับใช้แอปพลิเคชันของบริษัทอื่น</span><span class="sxs-lookup"><span data-stu-id="7b289-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="7b289-125">รูปภาพแบบปรับแต่งเอง</span><span class="sxs-lookup"><span data-stu-id="7b289-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="7b289-126">การโยกย้ายและสถานการณ์ที่เกี่ยวข้องกับ VMware และ Citrix</span><span class="sxs-lookup"><span data-stu-id="7b289-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="7b289-127">สถานการณ์ Linux</span><span class="sxs-lookup"><span data-stu-id="7b289-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="7b289-128">การแปลงหรือการโยกย้ายโปรไฟล์ผู้ใช้</span><span class="sxs-lookup"><span data-stu-id="7b289-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="7b289-129">ติดต่อ <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> เพื่อขอรับความช่วยเหลือเกี่ยวกับบริการเหล่านี้</span><span class="sxs-lookup"><span data-stu-id="7b289-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="7b289-130">คุณควรมีสิ่งต่อไปนี้อยู่แล้ว:</span><span class="sxs-lookup"><span data-stu-id="7b289-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">ความต้องการด้านสิทธิ์การใช้งาน WVD</a></span><span class="sxs-lookup"><span data-stu-id="7b289-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="7b289-132">ระบบเครือข่าย Azure:</span><span class="sxs-lookup"><span data-stu-id="7b289-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-133">การสร้าง VNET &amp; Subnetting</span><span class="sxs-lookup"><span data-stu-id="7b289-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="7b289-134">ไฟร์วอลล์ / กลุ่มความปลอดภัยของเครือข่าย</span><span class="sxs-lookup"><span data-stu-id="7b289-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="7b289-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="7b289-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="7b289-136">การเปลี่ยนเส้นทางไปยัง Azure จากภายในองค์กร</span><span class="sxs-lookup"><span data-stu-id="7b289-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="7b289-137">กฎไฟร์วอลล์เพื่ออนุญาตให้มีการเชื่อมต่อกับ WVD</span><span class="sxs-lookup"><span data-stu-id="7b289-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">การอ้างอิงเอกสาร</a></span><span class="sxs-lookup"><span data-stu-id="7b289-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="7b289-139">Azure Active Directory การตั้งค่าทั่วไป</span><span class="sxs-lookup"><span data-stu-id="7b289-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-140">กลยุทธ์ข้อมูล <strong>เฉพาะตัว (เลือกได้เพียง 1 ตัวเลือกจาก 3 ตัวเลือกต่อไปนี้)</strong></span><span class="sxs-lookup"><span data-stu-id="7b289-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="7b289-141">Active Directory ที่มี Azure AD เชื่อมต่อใน Azure</span><span class="sxs-lookup"><span data-stu-id="7b289-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="7b289-142">Active Directory ที่มี Azure AD เชื่อมต่อภายในองค์กรผ่าน VPN / ER</span><span class="sxs-lookup"><span data-stu-id="7b289-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="7b289-143">Active Directory Domain Services</span><span class="sxs-lookup"><span data-stu-id="7b289-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
