---
title: Windows เดสก์ท็อปเสมือน
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
ms.localizationpriority: ''
ms.collection: FastTrack
description: FastTrackแนะWindowsนําการปรับใช้เดสก์ท็อปเสมือนที่จะช่วยคุณออนบอร์ดบนเดสก์ท็อปนี้
ms.openlocfilehash: 5dcd6724c6ce7c86acecd0ecf7310b59cf59858a
ms.sourcegitcommit: 3d086ab6c4743afbedebed55a3ddb65f05422a1b
ms.translationtype: MT
ms.contentlocale: th-TH
ms.lasthandoff: 08/30/2021
ms.locfileid: "58710218"
---
# <a name="windows-virtual-desktop"></a>Windows เดสก์ท็อปเสมือน

<table>
<thead>
<tr class="header">
<th><strong>บริการ</strong></th>
<th><strong>FastTrack รายละเอียดการแนะนํา</strong></th>
<th><strong>ข้อกำหนดของสภาพแวดล้อมต้นทาง</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows เดสก์ท็อปเสมือน</td>
<td><p>FastTrack ให้แนวทางการปรับใช้ Windows Virtual Desktop เพื่อช่วยให้คุณออนบอร์ดในบริการการเสมือนของเดสก์ท็อปและแอปนี้ได้อย่างง่ายดายในขณะที่ใช้ประโยชน์จากประสบการณ์การใช้งานหลายเซสชันของ Windows 10 ซึ่งได้รับการปรับให้เหมาะสมกับ Microsoft 365 Apps สําหรับองค์กรด้วยการรักษาความปลอดภัยและการจัดการแบบรวมสําหรับ Microsoft 365</p>
<p>คุณร่วมงานกับFastTrackเฉพาะทางเพื่อ:</p>
<ul>
<li><p>ปรับใช้สภาพแวดล้อม WVD Windows 10 Enterpriseหลายเซสชัน + Microsoft 365 Apps for Enterprise โดยใช้สิ่งต่อไปนี้:</p>
<ul>
<li><p>รูป Azure Marketplace</p></li>
<li><p>รูปภาพที่แชร์</p></li>
<li><p>Office Deployment Toolkit (ODT)</p></li>
</ul></li>
<li><p>กําหนดค่า FSLogix</p>
<ul>
<li><p>ปรับใช้ตัวแทน FSLogix กับคอนเทนเนอร์โปรไฟล์</p></li>
<li><p>ปรับใช้ตัวแทน FSLogix กับOfficeคอนเทนเนอร์</p></li>
<li><p>กําหนดค่าโฟลเดอร์ FSLogix ที่มีการแยกเนื้อหาออก</p></li>
</ul></li>
<li><p>ปรับใช้Microsoft Edge</p></li>
<li><p>ปรับใช้Microsoft Teams</p></li>
<li><p>เชื่อมต่อไคลเอ็นต์Windowsเดสก์ท็อปเสมือน</p></li>
</ul>
<p><strong>ต่อไปนี้เป็นการไม่อยู่ในขอบเขต</strong></p>
<ul>
<li><p>Projectการจัดการการปรับใช้เดสก์ท็อปเสมือนWindowsของลูกค้า</p></li>
<li><p>การสนับสนุนในสถานที่</p></li>
<li><p>การเสมือน/การปรับใช้แอปพลิเคชันของบริษัทอื่น</p></li>
<li><p>รูปภาพแบบปรับแต่งเอง</p></li>
<li><p>การโยกย้ายและสถานการณ์ที่เกี่ยวข้องกับ VMware และ Citrix</p></li>
<li><p>สถานการณ์ Linux</p></li>
<li><p>การแปลงหรือการโยกย้ายโปรไฟล์ผู้ใช้</p></li>
</ul>
<p>ติดต่อ <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> เพื่อขอรับความช่วยเหลือเกี่ยวกับบริการเหล่านี้</p></td>
<td><p>คุณควรมีสิ่งต่อไปนี้อยู่แล้ว:</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">ความต้องการด้านสิทธิ์การใช้งาน WVD</a></p></li>
<li><p>ระบบเครือข่าย Azure:</p>
<ul>
<li><p>การสร้าง VNET &amp; Subnetting</p></li>
<li><p>ไฟร์วอลล์ / กลุ่มความปลอดภัยของเครือข่าย</p></li>
<li><p>VPN / ExpressRoute</p></li>
<li><p>การเปลี่ยนเส้นทางไปยัง Azure จากภายในองค์กร</p></li>
<li><p>กฎไฟร์วอลล์เพื่ออนุญาตให้มีการเชื่อมต่อกับ WVD</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">การอ้างอิงเอกสาร</a></p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory การตั้งค่าทั่วไป</p>
<ul>
<li><p>กลยุทธ์ข้อมูล <strong>เฉพาะตัว (เลือกเพียง 1 ตัวเลือกจาก 3 ตัวเลือกต่อไปนี้)</strong></p>
<ul>
<li><p>Active Directory ที่มี Azure AD เชื่อมต่อใน Azure</p></li>
<li><p>Active Directory ที่มี Azure AD เชื่อมต่อภายในองค์กรผ่าน VPN / ER</p></li>
<li><p>Active Directory Domain Services</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
