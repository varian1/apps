---
title: ล็อกหน้าจอ แตะครั้งเดียว
name: TapLock
tagline: ล็อกมือถือแตะเดียว ปลดล็อกด้วยลายนิ้วมือและใบหน้าได้เหมือนเดิม
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## TapLock ทำอะไรได้บ้าง

TapLock วางปุ่ม **Lock** ใหญ่ ๆ ไว้บนหน้าจอ แตะแล้วมือถือจะล็อกทันที เหมือนกดปุ่มเปิด/ปิดเครื่อง เหมาะเมื่อปุ่มเปิด/ปิดกดยาก เสื่อมสภาพ หรือเสีย

- ถ้าใช้ Accessibility lock คุณยังปลดล็อกด้วยลายนิ้วมือ ใบหน้า PIN หรือรูปแบบได้ตามปกติ
- Device Admin lock เป็นวิธีล็อกอีกแบบ ใช้ได้โดยไม่ต้องเปิด Accessibility
- หนึ่งหน้าจอ หนึ่งปุ่ม ไม่ต้องสมัครสมาชิกหรือเข้าสู่ระบบ
- ใช้ฟรี มีโฆษณา

## เริ่มต้นใช้งาน

1. เปิด TapLock ครั้งแรก ข้อความใต้ปุ่ม **Lock** จะขึ้นว่า "One-time setup needed (about a minute)."
2. แตะ **Set up TapLock** หน้าจอ **Lock setup** จะเปิดขึ้น
3. เลือกวิธีล็อกอย่างใดอย่างหนึ่งจากสองวิธี
   - **Accessibility lock** (แนะนำ ใช้กับ Android 9 ขึ้นไป): ล็อกเหมือนกดปุ่มเปิด/ปิดเครื่อง และปลดล็อกด้วยลายนิ้วมือหรือใบหน้าได้เหมือนเดิม
   - **Device Admin lock**: ใช้ได้โดยไม่ต้องเปิด Accessibility Android จะขอ PIN รูปแบบ หรือรหัสผ่านของคุณในการปลดล็อกครั้งถัดไป
4. ทำตามขั้นตอนของวิธีที่คุณเลือกด้านล่าง

คุณเปิด **Lock setup** อีกครั้งได้ทุกเมื่อ โดยแตะไอคอนการตั้งค่าที่มุมขวาบนของหน้าหลัก

## เปิด Accessibility lock

1. ในหน้า **Lock setup** ที่การ์ด **Accessibility lock** แตะ **Turn on Accessibility lock**
2. กล่องข้อความถามว่า **Allow TapLock to use Accessibility?** อ่านรายละเอียดว่า TapLock ใช้สิทธิ์นี้อย่างไร
3. แตะ **Agree** เพื่อไปต่อ ถ้าแตะ **Decline** จะไม่มีอะไรเปลี่ยนแปลงและ Accessibility lock จะยังปิดอยู่
4. หน้าการตั้งค่าการช่วยเหลือพิเศษของ Android จะเปิดขึ้น ให้หา TapLock ซึ่งมักอยู่ใต้ "Downloaded apps"
5. เปิด "Use TapLock" แตะ **Allow** แล้วกลับมาที่ TapLock
6. การ์ดจะแสดง **On** และด้านบนจะขึ้น **You're all set** แตะ **Back to Lock**

![กล่องข้อความ "Allow TapLock to use Accessibility?" พร้อมปุ่ม Decline และ Agree](shots/04-accessibility-consent.png)

**ทำไม TapLock จึงขอสิทธิ์ Accessibility** TapLock ใช้ Accessibility Service API เพื่อล็อกหน้าจอเมื่อคุณแตะปุ่ม **Lock** เท่านั้น เหมือนกดปุ่มเปิด/ปิดเครื่อง จึงปลดล็อกด้วยลายนิ้วมือและใบหน้าได้เหมือนเดิม TapLock ไม่อ่านหน้าจอของคุณ ไม่เห็นสิ่งที่คุณพิมพ์ และไม่เก็บ บันทึก หรือแบ่งปันข้อมูลส่วนบุคคลใด ๆ ผ่านสิทธิ์นี้ คุณเลือก **Agree** หรือ **Decline** ได้ก่อนที่หน้าการตั้งค่าของ Android จะเปิด และปิดสิทธิ์นี้ได้ทุกเมื่อ

ถ้าการ์ดแสดง **Starting** นานเกินสองสามวินาที ให้ปิดแล้วเปิด TapLock ใหม่ในการตั้งค่าการช่วยเหลือพิเศษ ถ้าสวิตช์ในการตั้งค่าของ Android เป็นสีเทากดไม่ได้ ให้แตะ **Switch greyed out?** ในหน้า **Lock setup** แล้วทำตามคำแนะนำ

## ใช้ Device Admin lock แทน

1. ในหน้า **Lock setup** ที่การ์ด **Device Admin lock** แตะ **Enable Device Admin**
2. Android จะขอให้คุณยืนยัน TapLock ใช้สิทธิ์นี้เพื่อล็อกหน้าจอเมื่อคุณแตะปุ่ม **Lock** เท่านั้น
3. การ์ดจะแสดง **On**

![หน้าจอ Lock setup: การ์ด Accessibility lock แสดง On และการ์ด Device Admin lock มีปุ่ม Enable Device Admin](shots/02-setup.png)

เมื่อล็อกด้วยวิธีนี้ Android จะขอ PIN รูปแบบ หรือรหัสผ่านในการปลดล็อกครั้งถัดไป แทนการใช้ลายนิ้วมือหรือใบหน้า ถ้าเปิดไว้ทั้งสองวิธี TapLock จะใช้ Accessibility lock

## ล็อกหน้าจอ

1. เปิด TapLock ข้อความใต้ปุ่มจะขึ้นต้นว่า "Ready."
2. แตะ **Lock** หน้าจอจะล็อกทันที
3. ปลดล็อกมือถือตามปกติ

![หน้าหลักที่มีปุ่ม Lock กลม และข้อความ "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## ใช้โหมดมืด

1. เปิดธีมมืดในการตั้งค่า Android ของมือถือ
2. เปิด TapLock แอปจะทำตามมือถือและเปลี่ยนเป็นโหมดมืดเอง ในแอปไม่มีการตั้งค่าแยกต่างหาก

![หน้าหลักของ TapLock ในโหมดมืด](shots/03-dark-mode.png)

## เปลี่ยนภาษา

1. ที่หน้าหลัก แตะไอคอนการตั้งค่าเพื่อเปิด **Lock setup**
2. เปิดตัวเลือกภาษา
3. เลือกหนึ่งใน 31 ภาษา หรือคงค่าเริ่มต้นของระบบไว้ เพื่อให้ TapLock ใช้ภาษาเดียวกับมือถือ

![ตัวเลือกภาษาพร้อมรายการภาษา](shots/06-language.png)

ภาษาอาหรับ อูรดู และฮีบรูจะแสดงจากขวาไปซ้าย บน Android 13 ขึ้นไป คุณยังเปลี่ยนภาษาของ TapLock ได้ในการตั้งค่าภาษาของแอปใน Android

## ปิดวิธีล็อก หรือถอนการติดตั้ง

1. ที่หน้าหลัก แตะไอคอนการตั้งค่าเพื่อเปิด **Lock setup**
2. หากต้องการปิด Accessibility lock แตะ **Manage in Accessibility settings** แล้วปิด TapLock ที่นั่น
3. หากต้องการปิด Device Admin lock แตะ **Turn off Device Admin**
4. ปิด Device Admin ก่อนถอนการติดตั้ง TapLock เพราะ Android ไม่อนุญาตให้ถอนแอปที่ยังเป็นผู้ดูแลอุปกรณ์อยู่

![หน้า Lock setup ที่มีการ์ด "You're all set" และปุ่มสำหรับปิด Device Admin](shots/05-device-admin-on.png)

## คำถามที่พบบ่อย

**ทำไม TapLock ต้องขอสิทธิ์ Accessibility**
เพื่อล็อกหน้าจอเมื่อคุณแตะ **Lock** เท่านั้น เหมือนกดปุ่มเปิด/ปิดเครื่อง แอปไม่อ่านหน้าจอและไม่เห็นสิ่งที่คุณพิมพ์ ถ้าไม่ต้องการอนุญาต ให้ใช้ Device Admin lock

**ลายนิ้วมือใช้ไม่ได้หลังล็อกด้วย TapLock เพราะอะไร**
คุณกำลังใช้ Device Admin lock ซึ่งทำให้ Android ขอ PIN รูปแบบ หรือรหัสผ่านหนึ่งครั้ง ให้เปิด Accessibility lock เพื่อใช้ลายนิ้วมือและใบหน้าปลดล็อกได้ต่อไป

**ถอนการติดตั้ง TapLock ไม่ได้ ทำอย่างไรดี**
เปิด **Lock setup** แตะ **Turn off Device Admin** แล้วถอนการติดตั้ง

**ต้องใช้ Android เวอร์ชันไหน**
Accessibility lock ต้องใช้ Android 9 ขึ้นไป ส่วนเวอร์ชันเก่ากว่านั้นให้ใช้ Device Admin lock

**ใช้ TapLock เป็นภาษาของฉันได้ไหม**
ได้ TapLock มี 31 ภาษา เลือกภาษาของคุณได้ที่ **Lock setup** หรือคงค่าเริ่มต้นของระบบไว้

## ความเป็นส่วนตัว

TapLock ใช้สิทธิ์ Accessibility และ Device Admin เพื่อล็อกหน้าจอเท่านั้น และไม่เก็บข้อมูลส่วนบุคคลผ่านสิทธิ์เหล่านี้ แอปแสดงโฆษณาจาก Google AdMob ในพื้นที่ที่กฎหมายกำหนด คุณเปลี่ยนตัวเลือกโฆษณาได้ที่ **Privacy settings** ในหน้า **Lock setup** อ่าน[นโยบายความเป็นส่วนตัว](https://varian1.github.io/LockAppOnlyWeb/privacy.html)ฉบับเต็มได้ที่ลิงก์นี้
