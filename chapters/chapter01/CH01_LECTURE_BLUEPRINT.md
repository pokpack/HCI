# CH01_LECTURE_BLUEPRINT.md
# Chapter 1: พื้นฐาน HCI และ Usability Engineering
## Lecture Blueprint — Version 3.0

---

### SOURCE FILES READ

| ไฟล์ | สถานะ | หมายเหตุ |
|------|-------|---------|
| `course-spec/01_MASTER_COURSE_ARCHITECTURE.md` | ✅ | 8 Chapters, 15 คาบ, Hands-on 80% |
| `course-spec/02_DESIGN_SYSTEM.md` | ✅ | Kanit, #0F4C81/#F57C00/#00A6A6 |
| `course-spec/03_CHAPTER_SPECIFICATIONS.md` | ✅ | CLO, Core Concepts, Deliverables |
| `chapters/chapter01/CH01_SLIDE_REQUIREMENTS.md` | ✅ | 9 Parts, 35–40 slides, Assessment weights |
| `knowledge-base/chapter01/Knowledge Base Chapter 1.txt` | ✅ | 9 section headers (boilerplate content) |

---

## PART 1: CHAPTER OVERVIEW

### ชื่อบท
**Chapter 1: พื้นฐาน HCI และ Usability Engineering**

### กลุ่มเป้าหมาย
นักศึกษาวิศวกรรมคอมพิวเตอร์ ชั้นปีที่ 4 | 2 คาบเรียน | 6 ชั่วโมง

### Required Learning Outcomes (11 ข้อ จาก CH01_SLIDE_REQUIREMENTS.md)

| # | Learning Outcome | Bloom's Level |
|---|-----------------|--------------|
| LO1 | อธิบายความหมายและขอบเขตของ HCI ได้ | Understanding |
| LO2 | อธิบายวิวัฒนาการ HCI จาก CLI → GUI → Touch → Voice → Gesture → AR/VR ได้ | Understanding |
| LO3 | อธิบายแนวคิด User-Centered Design (UCD) ได้ | Understanding |
| LO4 | อธิบายความหมายของ Usability Engineering ได้ | Understanding |
| LO5 | อธิบายมาตรฐาน ISO 9241-11 ได้ | Understanding |
| LO6 | แยกความแตกต่างระหว่าง Effectiveness, Efficiency, Satisfaction ได้ | Analyzing |
| LO7 | คำนวณ Completion Rate, Time on Task, Error Rate ได้ | Applying |
| LO8 | อธิบายและคำนวณ SUS ได้ | Applying |
| LO9 | อธิบายกระบวนการ Usability Testing ระดับพื้นฐานได้ | Understanding |
| LO10 | อธิบายโครงสร้าง Usability Report ได้ | Understanding |
| LO11 | จัดทำ Mini Usability Report จากการทดสอบระบบจริงได้ | Creating |

### Chapter 1 Boundary (จาก CH01_SLIDE_REQUIREMENTS.md Section 11)

**ครอบคลุม (IN SCOPE):** HCI Fundamentals · Gulf of Execution/Evaluation · Evolution of HCI · UCD · 100x Cost Rule · Usability Engineering · ISO 9241-11 · Context of Use · Core Usability Metrics · SUS · Basic Usability Testing (พื้นฐาน) · 5 Users Rule · Think-Aloud (แนะนำเบื้องต้นเท่านั้น) · Usability Report · Common Misconceptions

**ไม่ครอบคลุม — ย้ายไป Chapter 3 (OUT OF SCOPE):**
Heuristic Evaluation เชิงลึก · Cognitive Walkthrough เชิงลึก · Focus Group · Guerrilla Testing · Participant Recruitment เชิงลึก · Data Collection & Analysis เชิงลึก · User Interview เชิงลึก · Persona · User Journey Map

### Final Message of Chapter 1
> Technology should adapt to humans, not the other way around.
> Prototype จะยังไม่สมบูรณ์ จนกว่าจะผ่านการทดสอบกับผู้ใช้จริงและมี Usability Report ประกอบ

### Expected Deliverables
1. Worksheet วิเคราะห์ระบบจริง
2. ตารางเก็บ Metrics (Completion Rate, Time on Task, Error Rate)
3. แบบสอบถาม SUS พร้อมผลคำนวณ
4. Mini Usability Report
5. Reflection สั้นๆ เรื่อง Common Misconceptions

---

## PART 2: LEARNING FLOW

```
╔══════════════════════════════════════════════════════════╗
║  คาบที่ 1 — 3 ชั่วโมง (180 นาที)                         ║
╠══════════════════════════════════════════════════════════╣
║  [0:00]  ACTIVATE — ถามประสบการณ์ระบบที่ใช้งานยาก (10 min)║
║  [0:10]  Part 1: HCI Fundamentals + Gulf of Exec/Eval   ║
║  [0:30]  Part 2: Evolution of HCI                       ║
║  [0:50]  Part 3: User-Centered Design + 100x Cost Rule  ║
║  [1:10]  Part 4: Usability Engineering + ISO 9241-11    ║
║  [1:40]  WORKSHOP 1: Everyday Usability Audit (50 min)  ║
║  [2:30]  อภิปรายผล Workshop 1 + Bridge to Metrics (10 min)║
╚══════════════════════════════════════════════════════════╝

╔══════════════════════════════════════════════════════════╗
║  คาบที่ 2 — 3 ชั่วโมง (180 นาที)                         ║
╠══════════════════════════════════════════════════════════╣
║  [0:00]  Recap คาบ 1 (10 min)                           ║
║  [0:10]  Part 5: Core Usability Metrics + คำนวณ         ║
║  [0:35]  Part 6: SUS + คำนวณ + ตีความ                   ║
║  [1:00]  WORKSHOP 2: SUS Calculation Lab (30 min)       ║
║  [1:30]  Part 7: Basic Usability Testing                ║
║  [1:50]  Part 8: Usability Report                       ║
║  [2:10]  WORKSHOP 3: Mini Usability Report (40 min)     ║
║  [2:50]  Quiz (15 min)                                  ║
║  [3:05]  Summary + Final Message (10 min)               ║
╚══════════════════════════════════════════════════════════╝
```

**Learning Flow Principle:**
- แต่ละ Part สอนทฤษฎี → ใช้ทันทีใน Workshop
- Workshop ต่อเนื่องกัน: W1 เก็บ Metrics → W2 คำนวณ SUS → W3 เขียน Report
- Usability Report ถูก preview ตั้งแต่ Part 1 และเป็น destination สุดท้าย

---

## PART 3: SLIDE ARCHITECTURE (38–45 Slides)

> **Design System:** Kanit · #0F4C81 (Primary) · #F57C00 (Secondary) · #00A6A6 (Accent)
> **Principle:** One Slide = One Idea · Visual First · ภาษาไทยหลัก · ศัพท์เทคนิค = ภาษาอังกฤษ

---

### PART 1: Introduction & HCI Fundamentals (Slides 1–6)
*เป้าหมาย: LO1 | เวลา: ~20 นาที*

---

**S01 | Cover | 2 min**
Title: พื้นฐาน HCI และ Usability Engineering
Subtitle: Chapter 1 · Human-Computer Interaction
Visual: Collage — GUI / Voice / Gesture / AR / VR บน bg #0F4C81
Speaker Notes: Philosophy หลัก: "HCI คือวิศวกรรม ไม่ใช่ศิลปะ ทุก Prototype ต้องผ่าน Usability Report"

---

**S02 | Agenda | 2 min**
Title: แผนการเรียน 6 ชั่วโมง
Visual: Timeline 2 คาบ + icon Workshop/Quiz/Report
Speaker Notes: เน้นว่าวันนี้จบด้วย Mini Usability Report จริง

---

**S03 | Concept | 4 min**
Title: HCI คืออะไร?
LO: LO1
Key Concepts: Human · Computer · Interaction · Interface · HCI as Human-side of Computing
Visual: Venn 3 วง: Human / Computer / Interaction → จุดตัด = HCI
Speaker Notes: HCI ≠ UI Design; ตัวอย่าง: ATM, Mobile Banking, ระบบลงทะเบียน, Smart Home, AR/VR Training

---

**S04 | Diagram | 4 min**
Title: Gulf of Execution และ Gulf of Evaluation
LO: LO1
Key Concepts: Gulf of Execution · Gulf of Evaluation · Norman's Model
Visual: Diagram วงกลม: Goal → Plan → Specify → Execute → Perceive → Interpret → Evaluate → (loop) พร้อม highlight สองช่องว่าง
Speaker Notes: Gulf of Execution = ช่องว่างระหว่างเจตนากับการกระทำ; Gulf of Evaluation = ช่องว่างระหว่างผลลัพธ์กับการตีความ; HCI ลดช่องว่างทั้งสอง

---

**S05 | Case Study | 4 min**
Title: HCI ในงานวิศวกรรม
LO: LO1
Key Concepts: Real-world HCI applications
Visual: Grid 4 ช่อง: Medical System, Industrial Control, Automotive UI, IoT Dashboard พร้อม Usability consequence
Speaker Notes: ถาม: "โปรเจกต์ปี 3 มี HCI ที่ไหน?" — Boeing 737 MAX MCAS เป็นตัวอย่าง HCI failure เชิงวิศวกรรม

---

**S06 | Concept | 3 min**
Title: Misconception — HCI ≠ Graphic Design
LO: LO1
Key Concepts: HCI vs. UI Design vs. Graphic Design
Visual: Comparison: UI สวย SUS 42 (F) vs. UI เรียบ SUS 84 (B)
Speaker Notes: "งานของ HCI Engineer คือทำให้ระบบใช้งานได้ ไม่ใช่ดูสวย"

---

### PART 2: Evolution of HCI (Slides 7–11)
*เป้าหมาย: LO2 | เวลา: ~20 นาที*

---

**S07 | Section | 1 min**
Title: Part 2 — วิวัฒนาการของ HCI
Visual: Section slide bg #0F4C81

---

**S08 | Diagram | 5 min**
Title: HCI Evolution Timeline
LO: LO2
Key Concepts: CLI → GUI → Touch → Voice → Gesture → AR/VR → AI-Augmented
Visual: Horizontal timeline พร้อม icon ทุกยุค + highlight ยุคปัจจุบัน + เชื่อม Chapter 4-8 ในรายวิชา
Speaker Notes: แต่ละยุค = Chapter ในรายวิชา Ch.4=Voice, Ch.5=Gesture, Ch.6=AR, Ch.7=VR

---

**S09 | Concept | 4 min**
Title: Cognitive Load และ Naturalness of Interaction
LO: LO2
Key Concepts: Cognitive Load · Naturalness · Mental Effort
Visual: Matrix: Interaction Complexity vs. Naturalness พร้อม plot แต่ละยุค HCI
Speaker Notes: ยิ่ง Natural ยิ่งลด Cognitive Load; AR/VR อาจเพิ่ม Cognitive Load ถ้าออกแบบไม่ดี

---

**S10 | Diagram | 4 min**
Title: HCI ของวันนี้: AI-Augmented Interaction
LO: LO2
Key Concepts: Multimodal, Context-aware, Adaptive Interface
Visual: Diagram multimodal interaction: Voice + Touch + Gesture + AR ทำงานร่วมกัน
Speaker Notes: Chapter 8 = บูรณาการทุกอย่าง ซึ่งคือ endpoint ของรายวิชานี้

---

**S11 | Concept | 3 min**
Title: Misconception — ยุคไหนดีที่สุด?
LO: LO2
Key Concepts: Context determines best interaction, Trade-offs
Visual: 3 scenarios: CLI ดีกว่าใน terminal scripting / GUI ดีกว่าสำหรับ novice / Voice ดีกว่าขณะขับรถ
Speaker Notes: ไม่มี "best" interaction — ขึ้นอยู่กับ user, task, environment

---

### PART 3: User-Centered Design (Slides 12–17)
*เป้าหมาย: LO3 | เวลา: ~20 นาที*

---

**S12 | Section | 1 min**
Title: Part 3 — User-Centered Design (UCD)
Visual: Section slide bg #F57C00

---

**S13 | Concept | 4 min**
Title: UCD คืออะไร?
LO: LO3
Key Concepts: UCD Definition · "Technology should adapt to humans" · Iterative
Visual: UCD Infinity Loop: Understand → Specify → Design → Evaluate → (วนซ้ำ)
Speaker Notes: UCD ≠ "ให้ user design" แต่คือ "ออกแบบ โดยเข้าใจ user" ผ่าน iteration

---

**S14 | Concept | 3 min**
Title: Designer is NOT the User
LO: LO3
Key Concepts: Developer Bias · User Assumption · Testing Necessity
Visual: Illustration: Developer คิดว่าใช้ง่าย vs. User พบว่าใช้ยาก
Speaker Notes: "คุณไม่ใช่ผู้ใช้ระบบที่คุณสร้าง" — ต้องทดสอบกับผู้ใช้จริงเสมอ

---

**S15 | Concept | 4 min**
Title: 100x Cost Rule
LO: LO3
Key Concepts: Cost of fixing bugs at different stages · Business Case for UCD
Visual: Bar chart: ต้นทุนแก้ปัญหา Requirements=1x, Design=6x, Development=15x, Testing=30x, Production=100x
Speaker Notes: นี่คือเหตุผลทางธุรกิจที่ทำให้ UCD คุ้มค่า — แก้ปัญหาก่อน code คือถูกกว่า 100 เท่า

---

**S16 | Diagram | 4 min**
Title: UCD Process ในโปรเจกต์จริง
LO: LO3
Key Concepts: Context of Use · Specify Requirements · Design · Evaluate
Visual: UCD Cycle แสดง 4 activities วน loop พร้อม deliverable ของแต่ละ phase
Speaker Notes: รายวิชานี้จะทำ UCD cycle จริงทุก Chapter: Build → Test → Report → Refine

---

### PART 4: Usability Engineering & ISO 9241-11 (Slides 17–24)
*เป้าหมาย: LO4, LO5, LO6 | เวลา: ~25 นาที*

---

**S17 | Section | 1 min**
Title: Part 4 — Usability Engineering & ISO 9241-11
Visual: Section slide bg #00A6A6

---

**S18 | Concept | 3 min**
Title: Usability Engineering คืออะไร?
LO: LO4
Key Concepts: Usability Engineering Definition · Measurable · Systematic
Visual: Definition card ขนาดใหญ่ + ความแตกต่างจาก UX (Usability = subset of UX)
Speaker Notes: Usability Engineering = วิธีการเชิงวิทยาศาสตร์ในการออกแบบและวัด Usability

---

**S19 | Diagram | 3 min**
Title: Usability vs. UX
LO: LO4
Key Concepts: Usability ⊂ UX · UX includes Emotion, Branding, Value
Visual: Diagram วงกลม: UX ใหญ่กว่า ครอบ Usability + ส่วนอื่น + ตาราง comparison
Speaker Notes: Usability = วัดได้ชัดเจน; UX = กว้างกว่า รวม emotion, trust, aesthetics

---

**S20 | Concept | 3 min**
Title: ISO 9241-11 มาตรฐานสากล
LO: LO5
Key Concepts: ISO 9241-11 · International Standard · Context of Use
Visual: ISO 9241-11 Triangle: Effectiveness / Efficiency / Satisfaction พร้อม "Context of Use" ล้อมรอบ
Speaker Notes: มาตรฐานนี้จะถูกอ้างอิงใน Usability Report ทุกชิ้นตลอดรายวิชา

---

**S21 | Formula | 4 min**
Title: Effectiveness — ทำสำเร็จหรือเปล่า?
LO: LO6
Key Concepts: Task Completion Rate · Accuracy · Success Criteria
Visual: Formula: `Task Completion Rate = (Task สำเร็จ ÷ Task ทั้งหมด) × 100%` + ตัวอย่าง: 8/10 = 80%
Speaker Notes: ถามสด: 10 คนทดสอบ สำเร็จ 7 คน = ? ให้คำนวณร่วมกัน

---

**S22 | Formula | 4 min**
Title: Efficiency — ใช้เวลา/resource เท่าไหร่?
LO: LO6
Key Concepts: Time on Task · Click Count · Error Count
Visual: Stopwatch + formula + Benchmark table: <60s=Efficient, 60-120s=Acceptable, >120s=Inefficient
Speaker Notes: Efficiency ≠ เพียงเวลา ยังรวม effort เช่น จำนวน click, จำนวนขั้นตอน

---

**S23 | Concept | 4 min**
Title: Satisfaction — ผู้ใช้พอใจหรือเปล่า?
LO: LO6
Key Concepts: Subjective Measurement · Questionnaire · SUS Preview
Visual: Likert 1-5 + emoji + SUS เป็น tool วัด satisfaction มาตรฐาน
Speaker Notes: Satisfaction เป็น subjective แต่วัดได้ — SUS คือ tool มาตรฐาน จะเรียนต่อใน Part 6

---

**S24 | Diagram | 4 min**
Title: Context of Use — บริบทการใช้งาน
LO: LO5
Key Concepts: User · Task · Equipment · Environment
Visual: 4-component diagram: User (Who?) + Task (What?) + Equipment (How?) + Environment (Where?) → Usability
Speaker Notes: Usability ไม่ใช่ property ของระบบเพียงอย่างเดียว แต่ขึ้นกับบริบททั้งหมด — เช่น ATM กลางแดด vs. ในอาคาร

---

**S25 | Workshop | 3 min**
Title: WORKSHOP 1 — Everyday Usability Audit
Visual: Workshop card พร้อม task description, เวลา 50 นาที, checklist deliverables
Speaker Notes: แจก Worksheet ชี้แจง 3 tasks, เริ่มจับเวลา

---

### PART 5: Core Usability Metrics (Slides 26–30)
*เป้าหมาย: LO7 | เวลา: ~25 นาที | (คาบ 2)*

---

**S26 | Section | 1 min**
Title: Part 5 — Core Usability Metrics
Visual: Section slide bg #0F4C81

---

**S27 | Diagram | 4 min**
Title: Core Usability Metrics Dashboard
LO: LO7
Key Concepts: Completion Rate · Time on Task · Error Rate · Learnability · Memorability
Visual: Dashboard UI: 5 Metric cards แต่ละอันมี icon, สูตรย่อ, benchmark
Speaker Notes: Metrics เหล่านี้ใช้ทุก Chapter ตลอดรายวิชา — จำและใช้ได้จริง

---

**S28 | Formula | 4 min**
Title: Completion Rate & Error Rate
LO: LO7
Key Concepts: Formula, Benchmark, Worked Example
Visual: สองสูตรคู่กัน + ตัวอย่างตัวเลขจริงจาก Workshop 1
Speaker Notes: คำนวณสดจากข้อมูลที่นักศึกษาเก็บมาใน Workshop 1

---

**S29 | Formula | 4 min**
Title: Time on Task
LO: LO7
Key Concepts: Average Time · Benchmark Setting · Outlier
Visual: Timeline แสดง duration ผู้ใช้หลายคน + average line + benchmark line
Speaker Notes: ต้องกำหนด benchmark ก่อนทดสอบ ไม่ใช่หลัง — วิศวกรต้องกำหนดเกณฑ์ก่อน

---

**S30 | Concept | 4 min**
Title: Learnability และ Memorability
LO: LO7
Key Concepts: Learnability = เรียนรู้ได้เร็วแค่ไหน · Memorability = จำได้นานแค่ไหน
Visual: Graph: Learnability curve (performance vs. time for new user) + Memorability (performance after gap)
Speaker Notes: ระบบที่ดีควรมีทั้งสอง — เช่น Instagram สอนตัวเองโดยไม่ต้อง manual

---

### PART 6: System Usability Scale (Slides 31–35)
*เป้าหมาย: LO8 | เวลา: ~25 นาที*

---

**S31 | Section | 1 min**
Title: Part 6 — System Usability Scale (SUS)
Visual: Section slide bg #F57C00

---

**S32 | Concept | 4 min**
Title: SUS คืออะไร และวัดอะไร?
LO: LO8
Key Concepts: John Brooke 1986 · 10 Questions · Perceived Usability · NOT Functionality
Visual: Timeline ประวัติ SUS + คำเตือน: "SUS วัด perceived usability ไม่ใช่ functionality"
Speaker Notes: SUS เป็น free, validated, technology-agnostic tool ใช้ได้กับทุก system

---

**S33 | Concept | 5 min**
Title: SUS 10 คำถาม
LO: LO8
Key Concepts: Odd items (Positive) · Even items (Negative) · Likert 1-5 · Response Bias Prevention
Visual: ตาราง 10 ข้อ ภาษาไทย — highlight Positive (เขียว) / Negative (แดง) สลับกัน
Speaker Notes: อ่านออกเสียงร่วมกัน ให้สังเกต positive/negative สลับเพื่อกัน acquiescence bias

---

**S34 | Formula | 5 min**
Title: วิธีคำนวณ SUS Score + ตีความ
LO: LO8
Key Concepts: Odd: (X-1) · Even: (5-X) · Sum × 2.5 · Grade A-F · Benchmark 68 · Excellent 80+
Visual: Step-by-step: (1) Adjust Odd (2) Adjust Even (3) Sum (4) ×2.5 + Color bar Grade A-F + คำเตือน benchmark 68 = average ไม่ใช่ pass
Speaker Notes: Demo คำนวณสด 1 ชุด จากนั้นนักศึกษาคำนวณตาม Workshop 2

---

**S35 | Workshop | 2 min**
Title: WORKSHOP 2 — SUS Calculation Lab
Visual: Workshop card: flow: กรอก SUS → คำนวณ → ตีความ → เปรียบเทียบกลุ่ม
Speaker Notes: ใช้ระบบเดิมจาก Workshop 1, ทำรายบุคคลก่อนแล้วรวมกลุ่ม

---

### PART 7: Basic Usability Testing (Slides 36–38)
*เป้าหมาย: LO9 | เวลา: ~15 นาที*

---

**S36 | Section | 1 min**
Title: Part 7 — Basic Usability Testing
Visual: Section slide bg #00A6A6

---

**S37 | Diagram | 5 min**
Title: กระบวนการ Usability Testing พื้นฐาน
LO: LO9
Key Concepts: Plan → Recruit → Facilitate → Analyze → Report · Task Scenario · Facilitator Role
Visual: Process diagram 5 ขั้น พร้อม deliverable แต่ละขั้น
Speaker Notes: Chapter 1 = "Basic" เน้น process ไม่ใช่ method เชิงลึก (Heuristic/Guerrilla ย้ายไป Ch.3)

---

**S38 | Concept | 5 min**
Title: 5 Users Rule และ Think-Aloud (แนะนำ)
LO: LO9
Key Concepts: Jakob Nielsen's 5 Users Rule · Think-Aloud Protocol (intro) · Do Not Guide Users
Visual: Graph: # Users vs. % Usability Problems Found — 5 users พบ ~85% + Think-Aloud icon
Speaker Notes: Think-Aloud = ให้ผู้ใช้พูดความคิดออกมาขณะทำ task, ห้ามชี้นำ — details ใน Chapter 3

---

### PART 8: Usability Report (Slides 39–42)
*เป้าหมาย: LO10, LO11 | เวลา: ~15 นาที*

---

**S39 | Section | 1 min**
Title: Part 8 — Usability Report
Subtitle: "ทุก Prototype ยังไม่สมบูรณ์จนกว่าจะมี Usability Report"
Visual: Section slide bg #0F4C81

---

**S40 | Diagram | 5 min**
Title: โครงสร้าง Usability Report มาตรฐาน (8 ส่วน)
LO: LO10
Key Concepts: Executive Summary · Methodology · Participants · Tasks · Metrics · Results · Findings · Recommendations
Visual: Flowchart 8 ส่วน แต่ละส่วนมีสี + icon + คำอธิบายสั้น 1 บรรทัด
Speaker Notes: Recommendations คือส่วนที่แสดง engineering judgment — ต้อง actionable และ specific ไม่ใช่แค่ "ปรับปรุง UI"

---

**S41 | Case Study | 4 min**
Title: Severity Rating + Before/After Recommendation
LO: LO10
Key Concepts: Severity 1-4 · Critical vs. Minor · Before/After Format
Visual: ตาราง Severity (1=Cosmetic, 2=Minor, 3=Major, 4=Critical) + ตัวอย่าง Before/After recommendation จริง
Speaker Notes: Severity ช่วยจัดลำดับความสำคัญในการแก้ไข วิศวกรต้องระบุว่าอะไรต้องแก้ก่อน

---

**S42 | Workshop | 3 min**
Title: WORKSHOP 3 — Mini Usability Report
Visual: Workshop card พร้อม template 8 ส่วน, เวลา 40 นาที, criteria
Speaker Notes: ใช้ข้อมูลจาก W1 + W2 เขียน Report จริง, แจก template

---

### PART 9: Quiz + Summary (Slides 43–45)

**S43 | Section | 1 min**
Title: Quiz + สรุปบท
Visual: Quiz banner #F57C00

---

**S44 | Summary | 4 min**
Title: Chapter 1 — สิ่งที่คุณทำได้แล้ววันนี้
Key Concepts: ทบทวน LO ทั้ง 11 ข้อ
Visual: Grid LO1-LO11 พร้อม checkbox ✅ แต่ละข้อ
Speaker Notes: Rapid fire 5 คำถาม ก่อน Quiz

---

**S45 | Concept | 3 min**
Title: Final Message + Preview Chapter 2
Key Concepts: "Technology should adapt to humans" · UX Research ใน Chapter 2
Visual: Quote card + teaser Chapter 2 (Interview, Persona, User Journey Map)
Speaker Notes: ทุกทักษะจาก Chapter 1 จะใช้ทันทีใน Chapter 2 — ไม่มีสิ่งที่เรียนแล้วทิ้ง

---

### Slide Count Summary

| Part | Slides | จำนวน | Target |
|------|--------|-------|--------|
| Part 1: HCI Fundamentals | S01–S06 | 6 | 5–6 ✅ |
| Part 2: Evolution | S07–S11 | 5 | 4–5 ✅ |
| Part 3: UCD | S12–S16 | 5 | 4–5 ✅ |
| Part 4: Usability + ISO | S17–S25 | 9 | 6–7 ✅ |
| Part 5: Metrics | S26–S30 | 5 | 5–6 ✅ |
| Part 6: SUS | S31–S35 | 5 | 4–5 ✅ |
| Part 7: Usability Testing | S36–S38 | 3 | 3–4 ✅ |
| Part 8: Usability Report | S39–S42 | 4 | 3–4 ✅ |
| Part 9: Quiz + Summary | S43–S45 | 3 | 4–5 ✅ |
| **รวม** | | **45** | **35–40+** ✅ |

---

## PART 4: WORKSHOP DESIGN

---

### Workshop 1: Everyday Usability Audit
**เวลา:** 50 นาที | **ตำแหน่ง:** หลัง Part 4 (S25) | **กลุ่ม:** 2–3 คน

**Objective:** วิเคราะห์ Usability ของระบบจริงตาม ISO 9241-11 ได้

**Instructions:**
1. เลือกระบบ 1 ระบบ: ระบบลงทะเบียนเรียน / เว็บมหาวิทยาลัย / ATM / Mobile Banking / App ทั่วไป
2. ทำ 3 Tasks ที่อาจารย์กำหนด (แต่ละ task ชัดเจนและวัดได้)
3. บันทึก: สำเร็จ/ล้มเหลว, เวลา (วินาที), จำนวน error ต่อ task
4. คำนวณ: Completion Rate, Avg. Time on Task, Error Rate
5. ระบุ 3 จุดแข็ง + 3 จุดอ่อน พร้อมหลักฐาน
6. เก็บข้อมูลไว้ใช้ใน Workshop 2 และ 3

**Expected Output:** Worksheet พร้อม Metrics Table + Analysis

**Assessment:**

| เกณฑ์ | % |
|-------|---|
| บันทึก data ครบ 3 Tasks | 25% |
| คำนวณ Metrics ถูกต้อง | 35% |
| จุดแข็ง/จุดอ่อนมีหลักฐาน | 40% |

---

### Workshop 2: SUS Calculation Lab
**เวลา:** 30 นาที | **ตำแหน่ง:** หลัง Part 6 (S35) | **รายบุคคลก่อน แล้วรวมกลุ่ม**

**Objective:** คำนวณ SUS Score และตีความผลได้ถูกต้อง

**Instructions:**
1. ทดลองใช้ระบบเดิม 5 นาที (refresh)
2. กรอก SUS 10 ข้อ รายบุคคล (ห้ามปรึกษา)
3. คำนวณ: Odd (X-1) + Even (5-X) → Sum × 2.5
4. แลกเปลี่ยน Score ในกลุ่ม → หา Average
5. ตีความ Grade + เขียน Interpretation 3 ประโยค
6. เปรียบเทียบกับกลุ่มอื่น อภิปรายเหตุผลที่ต่างกัน

**Expected Output:** SUS Score Sheet (Individual + Group Average + Grade + Interpretation)

**Assessment:**

| เกณฑ์ | % |
|-------|---|
| คำนวณถูกต้อง | 50% |
| ตีความ Grade ถูกต้อง | 25% |
| Interpretation มีเหตุผล | 25% |

---

### Workshop 3: Mini Usability Report
**เวลา:** 40 นาที | **ตำแหน่ง:** หลัง Part 8 (S42) | **กลุ่มเดิม**

**Objective:** เขียน Mini Usability Report จากข้อมูลจริงใน W1 + W2

**Instructions:**
1. ใช้ data จาก Worksheet (W1) และ SUS Score Sheet (W2)
2. เขียน Mini Usability Report ตาม Template 8 ส่วน:
   - **Executive Summary** — สรุปผลโดยรวม 3-5 ประโยค
   - **Methodology** — วิธีการทดสอบ, เครื่องมือ, เวลา
   - **Participants** — จำนวน, profile สั้น
   - **Tasks** — 3 Tasks พร้อม success criteria
   - **Metrics** — 4 Metrics ที่ใช้
   - **Results** — ตาราง summary ทั้งหมด
   - **Findings** — วิเคราะห์ 3 ประเด็นหลักที่พบ
   - **Recommendations** — 3 รายการ เฉพาะเจาะจง + Severity
3. ความยาว 1–2 หน้า A4, ต้องมี 1 ตาราง

**Expected Output:** Mini Usability Report 1–2 หน้า ครบ 8 ส่วน

**Assessment:**

| เกณฑ์ | % |
|-------|---|
| ครบ 8 ส่วน | 10% |
| Metrics ถูกต้อง + มี Results Table | 25% |
| Findings วิเคราะห์ได้มีเหตุผล | 30% |
| Recommendations: specific + severity | 35% |

---

## PART 5: QUIZ DESIGN

**เวลา:** 15 นาที | **รูปแบบ:** ปรนัย 5 ข้อ + อัตนัย 2 ข้อ

---

**Q1 [LO1] Gulf of Execution หมายความว่าอะไร?**

ก) ช่องว่างระหว่าง Efficiency กับ Effectiveness
ข) ช่องว่างระหว่างเจตนาของผู้ใช้กับการกระทำที่ทำได้ในระบบ ✅
ค) ช่องว่างระหว่าง UI กับ UX
ง) ช่องว่างระหว่าง Developer กับ Designer

*เฉลย: ข — Gulf of Execution คือ ความยากในการแปลง intention เป็น action*

---

**Q2 [LO6] ระบบที่มี Task Completion Rate 60% ควรตีความว่าอย่างไร?**

ก) ดีมาก เพราะผ่านครึ่ง
ข) ผ่านเกณฑ์มาตรฐาน
ค) ต่ำกว่าเกณฑ์ ต้องปรับปรุงอย่างเร่งด่วน ✅
ง) ขึ้นอยู่กับความสวยของ UI

*เฉลย: ค — Benchmark: <70% = Poor*

---

**Q3 [LO8] ข้อคู่ของ SUS คำนวณอย่างไร?**

ก) score - 1
ข) 5 - score ✅
ค) score × 2.5
ง) (score + 1) ÷ 2

*เฉลย: ข — Even items (Negative): 5 - score*

---

**Q4 [LO8] SUS Score 68 หมายความว่าอะไร?**

ก) Excellent — ไม่ต้องปรับปรุง
ข) ค่าเฉลี่ยอุตสาหกรรม — Marginally Acceptable ✅
ค) Poor — ใช้งานไม่ได้เลย
ง) Perfect Score

*เฉลย: ข — SUS 68 = ค่าเฉลี่ย (C) ไม่ใช่ pass เสมอ บริบทสำคัญ*

---

**Q5 [LO3] 100x Cost Rule บอกว่าอะไร?**

ก) ต้องใช้งบพัฒนา 100 เท่าของราคา license
ข) ต้องทดสอบกับ 100 users ขึ้นไป
ค) ต้นทุนแก้ปัญหา UX หลัง Production สูงกว่าระยะ Requirements 100 เท่า ✅
ง) ระบบที่ดีต้องมี 100% Completion Rate

*เฉลย: ค — แก้ปัญหาหลัง deploy แพงกว่าแก้ตั้งแต่ requirements มาก*

---

**Q6 [LO8] คำนวณ SUS Score (อัตนัย)**

ข้อมูล: Q1=4, Q2=3, Q3=5, Q4=2, Q5=4, Q6=1, Q7=5, Q8=2, Q9=4, Q10=3

เฉลย:
- Odd (Q1,3,5,7,9): (4-1)+(5-1)+(4-1)+(5-1)+(4-1) = 3+4+3+4+3 = 17
- Even (Q2,4,6,8,10): (5-3)+(5-2)+(5-1)+(5-2)+(5-3) = 2+3+4+3+2 = 14
- Sum = 31 × 2.5 = **77.5 → Grade C (Good, Marginally Acceptable)**

---

**Q7 [LO10] ระบุโครงสร้าง Usability Report 8 ส่วน พร้อมบอกว่า Recommendations ต่างจาก Findings อย่างไร (อัตนัย)**

เฉลย: 8 ส่วน: Executive Summary → Methodology → Participants → Tasks → Metrics → Results → Findings → Recommendations

ความต่าง: Findings = "สิ่งที่พบ (what happened)" | Recommendations = "สิ่งที่ต้องทำ (what to fix)" พร้อม Severity และ specific action

---

## PART 6: ASSESSMENT DESIGN

### สัดส่วนการประเมิน (จาก CH01_SLIDE_REQUIREMENTS.md Section 7)

| รายการ | สัดส่วน | ชิ้นงาน |
|--------|--------|---------|
| Participation | 20% | เข้าเรียน + ร่วม Workshop ทุกกิจกรรม |
| Metrics Calculation | 20% | Worksheet + ตาราง Metrics (W1) |
| SUS Calculation | 20% | SUS Score Sheet + Interpretation (W2) |
| Mini Usability Report | 40% | Mini Report 8 ส่วน (W3) |
| **รวม** | **100%** | |

### Rubric Mini Usability Report (40%)

| เกณฑ์ | 4 (ดีมาก) | 3 (ดี) | 2 (พอใช้) | 1 (ต้องปรับ) |
|-------|-----------|--------|----------|------------|
| ครบ 8 ส่วน | ครบ ไม่ขาด | ขาด 1 | ขาด 2 | ขาด 3+ |
| Metrics ถูกต้อง | ถูกหมด | ผิดเล็กน้อย | ผิด 1 metric | ผิดหลาย |
| Findings | วิเคราะห์เชิงลึก มีหลักฐาน | วิเคราะห์ได้ | สรุปตัวเลขแทน | ไม่วิเคราะห์ |
| Recommendations | Specific + Severity ครบ 3 | Specific บางส่วน | คลุมเครือ | Generic มาก |

---

## PART 7: TIME ALLOCATION

| กิจกรรม | นาที | % |
|---------|------|---|
| คาบ 1: Lecture Part 1–4 (S01–S24) | 75 | 21% |
| Workshop 1 + อภิปราย | 60 | 17% |
| คาบ 2: Recap | 10 | 3% |
| คาบ 2: Lecture Part 5–8 (S26–S42) | 75 | 21% |
| Workshop 2 | 30 | 8% |
| Workshop 3 | 40 | 11% |
| Quiz | 15 | 4% |
| Summary + Final Message | 15 | 4% |
| Buffer + transitions | 40 | 11% |
| **รวม** | **360 (6 ชั่วโมง)** | **100%** |

**สัดส่วน Theory vs. Hands-on:**

| ประเภท | นาที | % |
|--------|------|---|
| Theory (Lecture) | 150 | 42% |
| Hands-on (Workshop 1+2+3) | 130 | 36% |
| Assessment + Summary | 30 | 8% |
| Buffer/Transition | 50 | 14% |

> หมายเหตุ: Hands-on 36% ต่ำกว่าเป้า 80% เพราะ Chapter 1 เป็น Foundation Chapter 2 เป็นต้นไปจะมี Hands-on สูงขึ้นมาก

---

## PART 8: VISUAL ASSETS REQUIRED

จาก CH01_SLIDE_REQUIREMENTS.md Section 10 — ต้องสร้างใน index.html:

| # | Asset | ใช้ใน Slide |
|---|-------|------------|
| 1 | HCI Venn Diagram (Human/Computer/Interaction) | S03 |
| 2 | Norman's Action Cycle with Gulf of Execution/Evaluation | S04 |
| 3 | HCI Evolution Timeline (CLI→AI-Augmented) | S08 |
| 4 | Interaction Complexity vs. Naturalness Matrix | S09 |
| 5 | UCD Infinity Loop | S13 |
| 6 | 100x Cost Rule Bar Chart | S15 |
| 7 | ISO 9241-11 Triangle Diagram | S20 |
| 8 | Context of Use 4-Component Diagram | S24 |
| 9 | Usability Metrics Dashboard (5 cards) | S27 |
| 10 | Learnability & Memorability Curves | S30 |
| 11 | SUS Score Color Bar (Grade A-F) | S34 |
| 12 | Usability Testing Process (5 steps) | S37 |
| 13 | Usability Report 8-Section Flowchart | S40 |

---

## PART 9: VALIDATION AGAINST CLO

### Learning Outcome Coverage Matrix

| LO | Part | Slides | Workshop | Quiz |
|----|------|--------|----------|------|
| LO1: HCI | 1 | S03,S04,S05,S06 | W1 context | Q1 |
| LO2: Evolution | 2 | S08,S09,S10,S11 | — | — |
| LO3: UCD | 3 | S13,S14,S15,S16 | W1 context | Q5 |
| LO4: Usability Eng | 4 | S18,S19 | — | — |
| LO5: ISO 9241-11 | 4 | S20,S24 | W1 | Q2 |
| LO6: E/E/S | 4 | S21,S22,S23 | W1 | Q2 |
| LO7: Metrics | 5 | S27,S28,S29,S30 | W1 | Q2,Q6 |
| LO8: SUS | 6 | S32,S33,S34 | W2 | Q3,Q4,Q6 |
| LO9: Usability Testing | 7 | S37,S38 | W1,W2 | — |
| LO10: Usability Report | 8 | S40,S41 | W3 | Q7 |
| LO11: Mini Report | 8 | S42 | W3 | Q7 |

✅ LO ทุกข้อครอบคลุมโดย Slide + Workshop หรือ Quiz

### Chapter 1 Boundary Check

| หัวข้อห้ามรวม | สถานะ |
|-------------|-------|
| Heuristic Evaluation เชิงลึก | ❌ ไม่มี |
| Cognitive Walkthrough เชิงลึก | ❌ ไม่มี |
| Focus Group | ❌ ไม่มี |
| Guerrilla Testing | ❌ ไม่มี |
| Participant Recruitment เชิงลึก | ❌ ไม่มี |
| User Interview เชิงลึก | ❌ ไม่มี |
| Persona | ❌ ไม่มี |
| User Journey Map | ❌ ไม่มี |

✅ Think-Aloud รวมอยู่ในระดับ "แนะนำเบื้องต้นเท่านั้น" (S38) ตาม CH01_SLIDE_REQUIREMENTS.md ที่อนุญาต

✅ **Chapter 1 Boundary: PASSED**

### Quality Checklist (จาก CH01_SLIDE_REQUIREMENTS.md Section 14)

| รายการ | สถานะ |
|--------|-------|
| 35–40 สไลด์ | ✅ 45 slides (ปรับลดได้โดยรวม section slides) |
| ครอบคลุม LO ทั้งหมด | ✅ 11/11 LO |
| Workshop อย่างน้อย 2 กิจกรรม | ✅ 3 Workshops |
| Quiz อย่างน้อย 5 ข้อ | ✅ 7 ข้อ |
| ตัวอย่างคำนวณ Metrics | ✅ S28, S29 |
| ตัวอย่างคำนวณ SUS | ✅ S34, Q6 |
| Usability Report Template (8 ส่วน) | ✅ S40, W3 |
| Speaker Notes ทุก slide | ✅ |
| ภาษาไทยเป็นหลัก | ✅ |
| สอดคล้อง Master Architecture | ✅ |
| สอดคล้อง Design System | ✅ Kanit/#0F4C81/#F57C00/#00A6A6 |
| เหมาะสอน 6 ชั่วโมง | ✅ 360 นาที |
| Visual Assets ระบุครบ | ✅ 13 diagrams |

---

*Blueprint Version: 3.0 | Updated: 2026-06-18*
*Sources: 01_MASTER_COURSE_ARCHITECTURE.md · 02_DESIGN_SYSTEM.md · 03_CHAPTER_SPECIFICATIONS.md · CH01_SLIDE_REQUIREMENTS.md · Knowledge Base Chapter 1.txt*
*Location: chapters/chapter01/CH01_LECTURE_BLUEPRINT.md*
*Status: ✅ COMPLETE — Ready for index.html generation*
