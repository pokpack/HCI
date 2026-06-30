# PROJECT UNDERSTANDING REPORT
## HCI Course Development — วิศวกรรมคอมพิวเตอร์ ชั้นปีที่ 4

---

## 1. Course Understanding

รายวิชา Human-Computer Interaction (HCI) นี้ออกแบบสำหรับนักศึกษาวิศวกรรมคอมพิวเตอร์ชั้นปีที่ 4 ซึ่งมีพื้นฐานด้านการพัฒนาระบบแล้ว รายวิชาแบ่งออกเป็น **8 บท** ใน **2 Module** ครอบคลุมตั้งแต่พื้นฐาน HCI ไปจนถึงเทคโนโลยีขั้นสูงอย่าง AR/VR และ Gesture Recognition

สัดส่วนการเรียนรู้คือ **Hands-on 80%** ซึ่งหมายความว่าทุกบทต้องมี Workshop และผลลัพธ์ที่จับต้องได้ ไม่ใช่เพียงการบรรยายทฤษฎี ทุก Prototype ต้องผ่านการทดสอบกับผู้ใช้จริงและมี Usability Report ก่อนถือว่าสมบูรณ์

**โครงสร้างรายวิชา:**

- **Module 1 — GUI + Voice:** Chapter 1–4 (พื้นฐาน HCI, UX Research, GUI Design, Voice Recognition)
- **Module 2 — Gesture + AR/VR:** Chapter 5–8 (Gesture, AR, VR, Integration)

---

## 2. Course Philosophy

หลักคิดสำคัญที่สุดของรายวิชาสรุปได้ใน 3 ระดับ:

**ระดับที่ 1 — Engineering Mindset:** HCI ในรายวิชานี้ไม่ใช่วิชาออกแบบกราฟิก แต่เป็นวิศวกรรมที่ต้องวัดผลได้ ความสวยงามเป็นผลพลอยได้ ไม่ใช่เป้าหมาย

**ระดับที่ 2 — Evidence-Based Iteration:** ทุก Prototype ต้องผ่าน Usability Testing → Evaluation → Metrics → Report วงจรนี้ไม่ใช่ optional แต่เป็นเงื่อนไขบังคับก่อนถือว่า Prototype "สมบูรณ์"

**ระดับที่ 3 — Real System Building:** นักศึกษาต้องสร้างระบบจริง ไม่ใช่ Mockup เพื่อประเมิน ทุกบทจึงต้องมี deliverable ที่ทดสอบได้จริงกับผู้ใช้จริง

Philosophy นี้สร้าง feedback loop ที่ชัดเจน: **Build → Test → Measure → Report → Refine**

---

## 3. Architecture Analysis

### Module Structure

```
Module 1: GUI + Voice (Chapter 1–4)
├── Ch.1  HCI Fundamentals + Usability Engineering  [Foundation]
├── Ch.2  UX Research + User Analysis               [Research Skills]
├── Ch.3  GUI Design                                [Build GUI]
└── Ch.4  Voice Interaction                         [Extend Interface]

Module 2: Gesture + AR/VR (Chapter 5–8)
├── Ch.5  Gesture Recognition                       [Physical Interaction]
├── Ch.6  Augmented Reality (AR)                    [Mixed Reality]
├── Ch.7  Virtual Reality (VR)                      [Immersive]
└── Ch.8  Technology Integration                    [Capstone]
```

### Chapter Dependency Logic

Chapter 1 เป็น **foundation** ที่ทุก Chapter อ้างอิง โดยเฉพาะ Usability Metrics และ SUS ซึ่งจะถูกใช้ซ้ำในทุกบทเมื่อประเมิน Prototype Chapter 8 เป็น Capstone ที่บูรณาการทุกอย่าง ดังนั้น Chapter 1 ต้องมีคุณภาพสูงสุดและครอบคลุมพอที่จะเป็นฐานตลอดรายวิชา

### Chapter 1 Boundary (Critical)

มีการกำหนดขอบเขตชัดเจนว่า Chapter 1 ครอบคลุมเฉพาะ:
HCI Fundamentals, Evolution of HCI, UCD, Usability Engineering, ISO 9241-11, Core Usability Metrics, SUS, Basic Usability Testing, Usability Report, Common Misconceptions

และต้องย้ายหัวข้อเหล่านี้ไป Chapter 2:
Think-Aloud Protocol, Heuristic Evaluation, Cognitive Walkthrough, Focus Group, Guerrilla Testing, Participant Recruitment, Task Scenario Design, Data Collection & Analysis, UX Research Methods เชิงลึก

ข้อกำหนดนี้สำคัญมากเพราะป้องกัน Chapter 1 บวม (scope creep) และรักษาความสมดุลของเนื้อหาระหว่าง Chapter 1 และ 2

---

## 4. Knowledge Base Strategy

Knowledge Base คือ **Single Source of Truth** ของเนื้อหาวิชาการ บทบาทหลัก:

- เป็นแหล่งข้อมูลที่ verified แล้วสำหรับสร้าง Learning Outcomes
- ป้องกันการสร้างเนื้อหาที่ขัดแย้งกันระหว่าง Chapter
- ทำให้ Workshop, Quiz, Assignment ยึดหลักการเดียวกัน
- ช่วยให้ผู้สอนหลายคนสามารถพัฒนาเนื้อหาได้โดยไม่ขัดแย้งกัน

**ลำดับการใช้งาน Knowledge Base ที่ถูกต้อง:**
```
Knowledge Base → Learning Outcomes → Workshop → Assessment → Slides → PDF
```

ไม่มีขั้นตอนใดข้ามได้ โดยเฉพาะห้ามเริ่มจากสไลด์ก่อน เพราะสไลด์ที่ดีต้องมาจาก Learning Outcomes ที่ชัดเจน ซึ่งมาจาก Knowledge Base ที่ครบถ้วน

**สถานะปัจจุบัน:** Knowledge Base directory ยังไม่มีในโปรเจกต์ — นี่คือ gap สำคัญที่ต้องแก้ไขก่อน

---

## 5. Design System Understanding

รายวิชากำหนดให้ใช้ `02_DESIGN_SYSTEM.md` เป็นมาตรฐานการออกแบบสื่อการสอน ซึ่งหมายความว่า:

- สไลด์ทุก Chapter ต้องใช้รูปแบบเดียวกัน (typography, color, layout)
- ห้ามออกแบบรูปแบบใหม่เองโดยไม่จำเป็น
- ความสอดคล้องของรูปแบบช่วยให้นักศึกษาจดจ่อที่เนื้อหา ไม่ใช่รูปแบบ
- Reveal.js ถูกเลือกเป็น presentation engine ซึ่งรองรับ web-based delivery และ interactive elements

**สถานะปัจจุบัน:** `02_DESIGN_SYSTEM.md` ยังไม่ถูกสร้าง — ต้องสร้างก่อนที่จะพัฒนาสไลด์ใดๆ

---

## 6. Role of Usability Report

Usability Report ถูกกำหนดให้เป็น **แกนหลัก** ของรายวิชาด้วยเหตุผลสำคัญ 4 ประการ:

**6.1 เป็น Engineering Deliverable** — ต่างจากรายวิชาออกแบบทั่วไปที่ประเมินจากความสวยงาม Usability Report ทำให้ HCI วัดผลได้เชิงวิศวกรรม เช่น Task Completion Rate, Time-on-Task, SUS Score

**6.2 เป็น Quality Gate** — Prototype ที่ไม่มี Usability Report ถือว่าไม่สมบูรณ์ ไม่ว่าจะ implement ได้สวยงามแค่ไหนก็ตาม ทำให้มาตรฐานการประเมินชัดเจนและยุติธรรม

**6.3 เชื่อมทุก Chapter เข้าหากัน** — ไม่ว่าจะเรียน GUI, Voice, Gesture, หรือ VR ทุก Chapter ต้องใช้ Usability Metrics เดิมจาก Chapter 1 ทำให้ทักษะสะสมและต่อเนื่อง ไม่ได้แยกจากกัน

**6.4 เตรียมนักศึกษาสู่การทำงานจริง** — ในอุตสาหกรรมซอฟต์แวร์ การ validate ด้วย User Testing และ Report เป็นทักษะที่ตลาดต้องการ

---

## 7. Risks and Gaps

### 7.1 Critical Gaps (ต้องแก้ไขก่อนเริ่มพัฒนา)

| Gap | ผลกระทบ | ความเร่งด่วน |
|-----|---------|-------------|
| `course-spec/` ว่างเปล่า — ไม่มี MASTER_COURSE_ARCHITECTURE.md, DESIGN_SYSTEM.md, CHAPTER_SPECIFICATIONS.md | ไม่มี Source of Truth → เนื้อหาอาจขัดแย้งกัน | 🔴 Critical |
| ไม่มี `knowledge-base/` directory | ไม่มีฐานความรู้ → เนื้อหาสไลด์ไม่มีที่มา | 🔴 Critical |
| ไม่มีไฟล์ใดๆ ในโปรเจกต์เลย | ทุกอย่างต้องสร้างใหม่ตั้งแต่ต้น | 🟡 High |

### 7.2 Design Risks

**Scope Creep ใน Chapter 1:** หัวข้อที่ควรอยู่ใน Chapter 2 (Think-Aloud, Heuristic Evaluation ฯลฯ) มีแนวโน้มสูงที่จะถูก include ใน Chapter 1 ถ้าไม่มีการตรวจสอบขอบเขตอย่างเข้มงวด ต้องมี checklist ยืนยันก่อน finalize

**Usability Testing กับ Real Users:** การกำหนดว่า "ทุก Prototype ต้องทดสอบกับผู้ใช้จริง" ต้องการการวางแผน Participant Pool ล่วงหน้า — ไม่ชัดเจนว่าผู้ใช้จริงคือนักศึกษากันเอง, บุคลากร, หรือบุคคลภายนอก

**Workshop Feasibility:** Chapter 5–7 (Gesture, AR, VR) ต้องการ hardware พิเศษ ยังไม่ชัดเจนว่า lab มีอุปกรณ์เพียงพอหรือไม่

**Content Volume vs. Contact Hours:** 8 Chapter ครอบคลุมเนื้อหาตั้งแต่พื้นฐานถึง VR Integration ยังไม่ชัดว่าแต่ละ Chapter ได้กี่สัปดาห์ อาจเสี่ยงต่อการ overload

### 7.3 Consistency Risks

หากไม่มี Design System และ Chapter Specifications เป็น reference การพัฒนาแต่ละ Chapter อาจมีรูปแบบไม่สอดคล้องกัน โดยเฉพาะหากพัฒนาโดยคนหลายคนหรือหลาย session

---

## 8. Recommendations

### 8.1 สิ่งที่ต้องทำก่อนสร้าง Chapter 1 (Priority Order)

**ขั้นที่ 1 — สร้าง Source of Truth Files (เร่งด่วนที่สุด)**

ต้องสร้างไฟล์ต่อไปนี้ใน `course-spec/` ก่อนทุกอย่าง:
- `01_MASTER_COURSE_ARCHITECTURE.md` — กำหนด 8 Chapter, learning outcomes ระดับรายวิชา, ความเชื่อมโยงระหว่าง Chapter
- `02_DESIGN_SYSTEM.md` — color palette, typography, layout rules, component library สำหรับ Reveal.js
- `03_CHAPTER_SPECIFICATIONS.md` — template มาตรฐานสำหรับแต่ละ Chapter (จำนวนสไลด์, workshop format, assessment format)

**ขั้นที่ 2 — สร้าง Knowledge Base สำหรับ Chapter 1**

สร้าง `knowledge-base/chapter01/` ประกอบด้วย:
- ทฤษฎี HCI พื้นฐานและประวัติศาสตร์
- มาตรฐาน ISO 9241-11 (Effectiveness, Efficiency, Satisfaction)
- Usability Metrics ที่จะใช้ตลอดรายวิชา
- SUS (System Usability Scale) — คำถาม 10 ข้อ, วิธีคิดคะแนน, การตีความ
- Template ของ Usability Report มาตรฐาน

**ขั้นที่ 3 — ยืนยัน Chapter 1 Boundary**

ก่อนเขียนเนื้อหา ให้ทำ checklist ว่าหัวข้อทุกข้อที่จะ include อยู่ใน boundary ที่กำหนด และหัวข้อที่ควรอยู่ใน Chapter 2 ถูกนำออกแล้ว

**ขั้นที่ 4 — กำหนด Participant Pool**

ชี้แจงว่าการ Usability Testing จะใช้ผู้ใช้กลุ่มใด เพื่อให้ Workshop และ Assignment สามารถออกแบบได้อย่างเหมาะสม

### 8.2 ข้อเสนอแนะด้าน Process

- ใช้ลำดับ Knowledge Base → Learning Outcomes → Workshop → Assessment → Slides → PDF อย่างเคร่งครัด
- ทุก Chapter ควรมี Usability Report Template ที่สอดคล้องกับ Chapter 1 ไม่ใช่ออกแบบใหม่ทุกครั้ง
- พิจารณาสร้าง `03_CHAPTER_SPECIFICATIONS.md` ที่มี template มาตรฐานต่อ Chapter เพื่อความ consistency

---

## Summary

โปรเจกต์มี **vision ที่ชัดเจนและแข็งแกร่ง** — การผสมผสาน Engineering Mindset กับ Hands-on Learning และ Usability-as-Quality-Gate เป็นแนวทางที่ถูกต้องสำหรับนักศึกษาวิศวกรรมชั้นปีที่ 4

**อุปสรรคหลักในตอนนี้คือ:** ยังไม่มี Source of Truth Files ใดเลย โปรเจกต์เป็นเพียงโครงสร้างโฟลเดอร์เปล่า ต้องสร้าง course-spec files และ knowledge-base ก่อนจึงจะเริ่มพัฒนา Chapter 1 ได้อย่างถูกต้อง

---
*Report generated: 2026-06-18*
*Status: Pre-development — awaiting Source of Truth file creation*
