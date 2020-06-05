---
title: 1 ปีกว่ากับโปรเจกต์ที่ไม่รู้ว่ามีอะไร และ ไม่รู้ว่าจะออกมายังไง
subtitle: จากการเริ่มต้นที่ไม่รู้ว่าจะต้องทำอะไร จนอยากจะส่งจดหมายหาตัวเองในวันงานเสร็จ
layout: post-it-blog
author: Theethawat Savastham
category: it-blog
git:
created_year: 2020
comments: true
---

เคยมั้ยครับที่เราเองก็ไม่รู้ว่าตอนจบ ไม่สิ ตอนต่อไปของเรื่องจะเป็นยังไง เราจะเจออะไรบ้าง เราจะมีความสุข จะทุกข์ จะอะไรก็ตามที่เราจินตนาการไม่ถูก ถ้าเรายังไม่เห็นมัน

ผมเองก็เป็นเหมือนกัน และเป็นบ่อยด้วยในช่วงที่เราต้องเจออะไรใหม่ ๆ ทั้งตอนไปฝึกงาน ที่ตอนนั้นเขียน Postcard ไปที่บ้านของตัวเองเพื่อจะอ่านตอนฝึกงานเสร็จ เพราะคือไม่รู้เลยว่าเราจะเจออะไรบ้าง และอีกอย่างนึงก็คือ โปรเจกต์ผมเนี่ยแหละ โอเคก่อนแหละเรารู้ว่าเราจะได้อะไรมา เพราะมันคือผลลัพธ์ของโปรเจกต์ แต่เราไม่รู้เลยว่า เราต้องเขียนโค้ดยังไง ทำอะไรบ้าง จนกว่าเราจะได้มันมา แน่นอนนะครับในการเขียนบทความนี้ผมจะไม่ให้กระทบใครอยู่แล้ว อ่านแล้วก็อาจจะมึน ๆ หน่อยนะครับ เพราะคนเขียนตอนเขียนก็มึน

## E-health for Personal Sensor Application

![ภาพไอ้ผมคนนี้กำลังทดลองใช้อุปกรณ์ต่าง ๆ อยู่](/assets/senior-project/measurement.jpg/)

นี่คือชื่อโปรเจกต์ของผมครับ หลายคนอาจจะไม่ทราบว่ามันคืออะไร ซึ่งผมเองก็อยากบอกว่า เออ มันก็งงจริง ๆ นั่นแหละ อ่าว แต่แปลง่าย ๆ เลยครับจากหลังมาหน้า คือ แอพพลิเคชั่น ที่ใช้ในการรวบรวมสุขภาพส่วนบุคคล จากตัวรับรู้ (เซนเซอร์) ต่าง ๆ ซึ่งในรายงานเอง ผมเองยังมองว่าคำว่าเซนเซอร์ อาจไม่เข้าใจมากนัก บางจุด ผมเลยเขียนว่าอุปกรณ์ดูแลสุขภาพมากกว่า มันคือการรับค่าจากอุปกรณ์ดูแลสุขภาพต่าง ๆ เข้ามาแสดงผลที่แอพพลิเคชั่น โดยไม่จำกัดบริษัท (จริง ๆ ก็จำกัดแหละ แต่ไม่ได้หมายความว่าทำให้ทำงานกับอุปกรณ์บริษัทใดบริษัทหนึ่ง) จริง ๆ มันก็คือจำกัดอยู่ดี อ่าว งงตัวเอง

**แต่ทั้งหมดนี้ทำได้หมดแล้ว** อ้าวแล้วอะไรเนี่ย มันคือมวยล้มต้มคนดูหรือเปล่าเนี่ย ผมก็ถามตัวเองเหมือนกัน เนื่องจากมันเป็นโปรเจกต์ต่อยอด แล้วให้ผมทำอะไร ผมถามไป แล้วคุณจะทำอะไร ผมได้รับคำถามกลับมา

### เออนั่นแหละ แล้วอยากจะทำอะไรหละ

![คอมพิวเตอร์ของผม](/assets/senior-project/com-photo.jpg/)
**_แชะภาพเพื่อนรักของผม น้องคอมเราเอง_**

ใช่ครับ เพราะนี่คือโปรเจกต์ของผม ผมอยากจะทำอะไรก็ได้ อาจารย์บอกว่าอาจารย์เป็นที่ปรึกษา และ กรรมการ ที่จะให้คะแนนตามสิ่งที่คุณทำ คุณคิดว่ามันมีปัญหาอะไรบ้าง อยากจะทำอะไรกับมันบ้าง ทำอะไรแล้วคิดว่ามันมีประโยชน์บ้าง เขาอนุญาติให้ใช้ Library ใดก็ได้ หรือ ใช้ Source Code ของโปรแกรมที่มีอยู่ได้ ใช่ส่วนของโปรแกรมได้ แต่สุดท้ายคุณต้องรายงานออกมาว่าสิ่งที่คุณทำคืออะไร งานของคุณอยู่ที่ไหน

เออ พูดไปพูดมา ย่อหน้าที่ผ่านมา เอามาประยุกต์เป็นคำคมได้เลยนะเนี่ย

อยากจะบอกตรง ๆ ว่าเราใช้เวลาหลายเดือนมากทั้งใน Prepare Project และใน Project 1 ในการเคลียร์เรื่องดังกล่าวข้างบนนี้ เนื่องจากผมเองก็ยังไม่คิดเป็นระบบเท่าไหร่ ดังนั้นการเข้าใจให้ได้ข้อความในย่อหน้านี้ แม้ตอนพิมพ์จะใช้เวลาเพียง 3-4 นาที แต่ในการทำ กระบวนการ คลุ่มเวลากว่า 6 - 7 เดือน

## การทำโจทย์ที่ (ยัง) ไม่มี Solution

หลังจากนั้น ซึ่งจริง ๆ มันก็คือ ระหว่างนั้นนั่นแหละ ถึงแม้โปรเจกต์ยังไม่มี Scope ทั้งหมด แต่มันก็มีอะไรให้ทำ และเยอะด้วย นั้นก็คือส่วนการแก้ข้อผิดพลาด ของอุปกรณ์ 1 ใน 4 อุปกรณ์ ที่มีการทำงานพลาดอยู่ จากการทดสอบของผม และ เพื่อนผมด้วย ว่ามันไม่ได้จริง ๆ ถึงแม้อาจารย์จะยืนยันว่าได้ จนถึงวันนี้ที่ผมจะซ่อมได้แล้ว ผมก็ยังหาเหตุผลอยู่ว่า เพราะอะไรกันแน่ ที่ทำให้ตัวนี้ผิดพลาดไป เหตุผลที่ผมคิดว่าน่าจะใช่ที่สุดก็คือ การเปลี่ยนชนิดของ Database แต่โอเคแหละ เมื่อไม่รู้ ผมก็ต้องพยายามหา และ พยายามแก้

การแก้งานตรงนี้ แม้จะมีพื้นที่ประมาณ 1 ใน 4 ของรายงานและการนำเสนอ เทียบกับฟีเจอร์อื่น ๆ แต่กินเวลา 3 ใน 4 ของทั้งหมด ผมเองก็เริ่มเรียนรู้วิธีที่จะแก้ปัญหาตรงนี้ เอ้ ผมจะทำยังไงดี เพราะมันเป็น Stack ที่ค่อนข้างจะยาก มีทั้ง Android with Kotlin, ReactiveX, Dagger2 และ อื่น ๆ

ส่วนนี้ผมยกให้ ReactiveX (RxJava2) เป็นพระเอกเลยเอา ส่วน Dagger ผมเองพยายามเลี่ยง เท่าที่เลี่ยงได้ เพราะสำหรับผมรู้สึกว่า เห้ย ทำไมมันยากจังวะ เทียบกับส่วนอื่น ๆ ที่ทำด้วย Rx และทำด้วยไลบารี่อื่น ๆ ที่มันเห็นภาพ และมี Document ค่อนข้างดี แน่นอนเป็นโชคดีที่ผมไม่ต้องไปเกาะกับตัว Dagger มากนัก เพราะสิ่งที่ผมทำมันอยู่ใน Class ซึ่งมันก็มีการ Dependencies Injector นั่นแหละ แต่เราไม่ต้องไปแตะมันมาก แค่รู้ว่า เออ มันทำงานยังไง และมันทำให้เกิดอะไรขึ้น ส่วนที่ผมเขียนเองนี่ ผมยอมรับว่าผมไม่แตะ Dagger2 เลย ใครสนใจ Rx ลองไปดูได้ [ReactiveX](http://reactivex.io)

### เพราะมันไม่ใช่การบ้านทั่วไปที่เราทำ

อย่าว่าเฉลยตายตัวเลย เฉลยอ้อม ๆ ยังไม่มีเลย เสร็จแล้วยัง ทำไมไม่ทำให้เสร็จ ๆ ไป ก็มันคิดไม่ออกอ่ะปัดโถ่ หลังจากทำงานนี้ไปซักพัก คุณจะพบว่างานเอย การบ้านเอย โค้ดเล็ก ๆ เอย มันง่ายไปเลย เพราะว่ามันมี start และ end ของมัน มันมีขอบเขต มี Milestone มีจุดที่รู้ว่ามันคือ Solution ของมัน แต่ตอนนี้เราต้อง define Start,End,Milestone และ Solution ต่าง ๆ เองทั้งหมด

### เอ้าไล่โค้ดไป

![ภาพแผนผังงานของโปรแกรมที่ผมพยายามแกะออกมา](/assets/senior-project/process-photo.jpg)

**_ตอนแรกก็มีการมานั่งวาดผังงานอยู่เหมือนกันนะ ใช้ Visio เลย แต่ตอนหลัง ก็ไม่รู้ว่าเรามานั่งวาดไปทำไมว้าา เขียนธรรมดาก็ได้ สุดท้ายทั้งหมดนี้ไม่ได้ใช้ครับ เอาไว้โชว์อาจารย์เฉย ๆ 555_**

ผมใช้วิธีการไล่โค้ดใน Android Studio ไปเรื่อย ๆ ครับ ตอนนั้นผมยังใช้เครื่องมือ Debug ไม่เป็น เหมือนตอนนี้ ผมใช้วิธีการคลาสสิกก็คือ พ่น Log ออกมาเรื่อย ๆ ให้รู้ว่าปัญหามันอยู่ครงไหน และอีกอย่างคือ โปรแกรมมันเดินทางยังไง ซึ่งพูดดูมันเหมือนง่าย แต่จริง ๆ มันไม่ง่ายเลยเพราะว่าคนเริ่มต้นเขียน Android อย่างผม มาเจอกับโครงสร้างโค้ดที่ซับซ้อน แต่โคตร Clean เลย (ซึ่งนี่คือโชคดีของผม)

ถ้าจะเล่าประสบการณ์ที่ผ่านมาทั้งหมดคงไม่ได้หรอก ไม่ใช่อะไร เดี๋ยวมันจะยาวเกิน หรือ ไม่ก็พิมพ์ไม่ไหว แต่อยากจะบอกว่ารู้มั้ยตอนที่ผมแก้มาจนได้เห็นระบบมันรับข้อมูลครั้งแรกได้ โอ้ย ผมแทบอยากจะกระโดดให้ลั่นห้อง

![หนึ่งในกระบวนการฟิลเตอร์ข้อมูล](/assets/senior-project/filter.jpg)
**_โต๊ะที่ผมทำงานและสไลด์วิธีการฟิลเตอร์ข้อมูลที่ผมคิดว่า เออ ใช้วิธีนี้แหละ_**

ผมเองพบว่าปัญหามันเกิดจาก 2 ส่วน ข้อมูลที่มันเป็นสตรีมของอุปกรณ์ตัวนี้ แต่ตัวอื่น ๆ ข้อมูลมันเป็นดิสครีต แน่นอนเราจะเก็บสตรีมที่มาเรื่อย ๆ ในรูปของดิสครีตก็คงไม่ได้ ทำได้เพียง เลือกจุดที่เหมาะสมที่สุดในสตรีม เป็นตัวแทนของข้อมูลสตรีมนั้น อีกส่วนคือ ระบบยังไม่สามารถ detect ได้เนี่ยเองว่า อุปกรณ์นี้นะ มันให้ค่าที่ระบบต้องการได้นะ You ไปเก็บข้อมูลสิ

ยังเขียนไม่เสร็จ แต่ Push ลง Git ก่อน