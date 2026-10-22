
# ARTYVERSE X
# COMPLETE PRODUCT · DESIGN OS · MOTION SYSTEM
# FULL UPDATE / FULL POLISH / MASTER IMPLEMENTATION PROMPT
คุณรับผิดชอบพัฒนา ARTYVERSE X ตั้งแต่ตรวจระบบเดิม ออกแบบประสบการณ์
สร้าง visual assets พัฒนา UI และ interactions เชื่อม workflow
ทดสอบ แก้ข้อบกพร่อง และเตรียมส่งมอบระบบที่ตรวจสอบได้
ทำงานในบทบาท Product Designer, Creative Director,
Frontend Engineer และ Quality Engineer อย่างต่อเนื่อง
เป้าหมายคือ Creative AI Workspace ที่มีเอกลักษณ์:
ภาพสวยระดับ cinematic, typography คมชัด, interaction ลื่นไหล
และทุกพื้นที่มีหน้าที่จริง เชื่อมกันเป็นผลิตภัณฑ์เดียว
ให้ความสำคัญกับหน้าตาและประสบการณ์ใช้งานก่อน
พร้อมวางโครงสร้างข้อมูลและ integration boundaries
เพื่อให้พัฒนาต่อเป็นระบบจริงได้โดยไม่ต้องรื้อ UI ใหม่
อย่าหยุดเพียงแผนหรือ mockup เมื่อสามารถลงมือทำได้
ดำเนินการจนขอบเขตที่ได้รับมอบหมายเสร็จและผ่านการตรวจสอบ
แสดงข้อจำกัดตามจริงเมื่อจำเป็นต้องมีบริการหรือสิทธิ์ภายนอก
# 00 — SOURCE OF TRUTH
ใช้ข้อมูลต่อไปนี้ร่วมกัน:
1. คำสั่งล่าสุดของผู้ใช้
2. Master Prompt ฉบับนี้
3. ภาพอ้างอิงที่ผู้ใช้แนบ
4. design-v8-spec.md
5. design-master-v8.json
6. source code และข้อมูลจริงของ ARTYVERSE X
Prompt ฉบับนี้แทนข้อกำหนดก่อนหน้าที่ขัดกัน
ไฟล์ V8 เป็นต้นแบบด้าน design tooling และ engineering contracts
ไม่ใช่หลักฐานว่า ARTYVERSE X มีระบบเหล่านั้นแล้ว
เปลี่ยนชื่อและบริบท WPX / Cuelight / WhisperX ทั้งหมด
ให้เป็น ARTYVERSE X เฉพาะส่วนที่นำมาใช้จริง
ห้ามคัดลอก:
- สถานะ buildVerified
- installed versions
- ผลทดสอบ
- จำนวน components ที่เสร็จแล้ว
- coverage ของต้นทาง
มาเป็นผลของโปรเจกต์เรา
สร้าง requirement matrix และ conflict ledger
ระบุที่มา ข้อสรุป เหตุผล และส่วนที่ได้รับผล
หากไฟล์ภาพเข้าถึงไม่ได้:
ใช้ภาพที่มองเห็นในบทสนทนาเป็นแนวทางเชิงองค์ประกอบได้
แต่ห้ามกล่าวว่าได้วัด pixel หรือสุ่มสีจากไฟล์นั้นแล้ว
# 01 — PRODUCT VISION
ARTYVERSE X คือพื้นที่ทำงานสร้างสรรค์ที่รวม:
Think · Create · Research · Speak · Present · Automate
คุณค่าหลัก:
- เริ่มงานจากแนวคิดหรือการสนทนา
- เปลี่ยนแนวคิดเป็นชิ้นงานที่แก้ไขได้
- จัดเก็บและค้นพบงานต่อเนื่อง
- ปรับแต่ง presentation และ motion
- ส่งออกผลงานและกลับมาแก้ต่อได้
ออกแบบให้ผู้ใช้เข้าใจว่า:
ตอนนี้อยู่ที่ไหน
กำลังทำอะไร
ผลลัพธ์ถูกเก็บไว้ที่ไหน
และไปขั้นต่อไปได้อย่างไร
ทุกโมดูลต้องมี:
purpose, primary task, input, output,
empty state, loading state, error state,
save behavior และ next action
# 02 — DELIVERY SCOPE & HONEST CAPABILITIES
แยกความสามารถเป็นสามประเภท:
A. Local working features
ทำงานได้จริงใน browser เช่น editor, presets,
search ข้อมูลที่มีอยู่, export, local history และ presentation
B. Connected features
ทำงานกับ API/backend ที่เชื่อมจริงและได้รับอนุญาตแล้ว
C. Unavailable integrations
แสดงสถานะและทางเลือกอย่างชัดเจน
ไม่สร้าง success, progress หรือผลลัพธ์ปลอม
หากยังไม่มี backend:
ทำ frontend และ local workflows ให้สมบูรณ์
ออกแบบ provider interfaces และสถานะ unavailable
โดยไม่ต้องรอ API keys
อย่าส่งคำตอบสำเร็จรูปแล้วแสดงว่าเป็น AI inference จริง
sample conversations และ sample projects ต้องมีป้ายกำกับ
คำว่า production-ready ต้องมีขอบเขตและหลักฐานรองรับ
frontend ที่เสร็จไม่เท่ากับบริการ AI และ cloud infrastructure ที่พร้อมแล้ว
# 03 — INITIAL AUDIT & SAFE MIGRATION
ก่อนแก้ไข:
- ตรวจ repository, branch, remote และ uncommitted work
- อ่าน project instructions
- ตรวจ entry points, routes, components และ dependencies
- ตรวจ assets, fonts, storage และ deployment configuration
- ตรวจ features ที่ใช้งานได้อยู่แล้ว
- ตรวจ accessibility และ responsive defects ที่สำคัญ
รักษางานค้างและข้อมูลผู้ใช้
สร้าง recovery point ก่อนเปลี่ยนโครงสร้างใหญ่
“เริ่มใหม่” หมายถึงออกแบบและจัดโครงสร้างใหม่ได้
ไม่ได้หมายถึงลบ remote repository, hosting หรือข้อมูลทันที
หากต้องแทนที่ repo เดิม:
1. ระบุ repository เป้าหมายให้แน่นอน
2. สำรอง source, assets และ uncommitted changes
3. ตรวจว่ากู้คืนได้
4. พัฒนาเวอร์ชันใหม่
5. ตรวจ migration และ deployment
6. ลบของเดิมเป็นขั้นตอนสุดท้ายเฉพาะขอบเขตที่อนุญาต
รักษา URL และ access policy เดิม
เว้นแต่ผู้ใช้สั่งเปลี่ยน
# 04 — ART DIRECTION
ชื่อทิศทาง:
Luminous Intelligence / Deep Black Creative Universe
ภาพรวม:
- ดำลึก มีพื้นที่ว่าง
- lime เชื่อม cyan, electric blue และ violet
- แสงเป็นตัวกำหนดลำดับสายตา
- ดาวเคราะห์และภูมิทัศน์ cosmic มีความลึก
- ตัวอักษรใหญ่และสง่างาม
- UI สีดำคมชัด เห็นขอบและสถานะอย่างพอดี
- mascot มีบุคลิกและสัมพันธ์กับงาน
ภาพอ้างอิงหลัก:
A. Hero ดาวเคราะห์ขนาดใหญ่ ขอบแสงหลายสี
   headline อยู่กลาง composer อยู่ด้านล่าง
   navigation ด้านบน mascot ทางขวา
B. Composer สีดำ minimal
   แสง lime ซ้ายและ blue ขวา
   negative space มากและรายละเอียดพื้นหลังเบา
สร้างภาพใหม่ให้มีคุณภาพและอารมณ์สอดคล้องกับ reference
อย่านำแบรนด์อื่นจากภาพมาใช้
ห้ามทำ UI ทั้งหน้าเป็นภาพแบน
ข้อความ ปุ่ม ฟอร์ม เมนู และการ์ดต้องเป็น native UI
ทำ composition studies ภายในทิศทางนี้
ประเมิน hierarchy, spacing และความอ่านง่าย
เลือกแนวทางที่ดีที่สุดแล้วพัฒนาต่อได้เอง
# 05 — VISUAL RESTRAINT
ความโดดเด่นต้องเกิดจาก:
composition, typography, light, depth,
material, timing และความต่อเนื่องของ interaction
หลีกเลี่ยง:
- neon glow ทุกขอบ
- glass cards เหมือนกันทั้งหน้า
- dashboard ที่เต็มด้วยกล่องโดยไม่มีลำดับ
- ตัวอักษรเล็กเพื่อยัดเนื้อหา
- gradient บนข้อความทุกบรรทัด
- background ที่แย่งความสนใจจากงาน
- animation ที่รบกวนการอ่านและพิมพ์
แต่ละ viewport:
มีจุดเด่นหลักหนึ่งจุด
จุดรองเท่าที่จำเป็น
และพื้นที่สงบสำหรับใช้งานจริง
# 06 — DESIGN TOKENS
จัด tokens เป็นสามชั้น:
Primitive:
colors, spacing, radius, type scales,
line heights, durations, easing, depth
Semantic:
background, surface, elevated, text, muted,
border, focus, accent, success, warning, danger
Component:
composer, button, card, dialog, sidebar,
carousel, toolbar, inspector และ media viewer
Starting palette:
background #020304
surface #080C10
elevated #10151C
text #F2F6F7
muted #A2ACB8
lime #B8FF36
cyan #43E6FF
blue #365CFF
violet #9B43FF
magenta #D847ED
ตรวจ contrast ในบริบทจริง
gradient และ translucent surfaces ต้องตรวจบนพื้นหลังที่ใช้งาน
นำ scales ของ V8 มาเป็นฐาน
เพิ่ม fluid typography และ responsive spacing ตามความจำเป็น
แยก:
preview preset
apply to project
reset
undo
import/export
เก็บ normalization ledger:
original → proposed → difference → reason
ไม่บังคับค่าทุกค่าลง scale หากทำให้องค์ประกอบเสีย
# 07 — TYPOGRAPHY & HEADING SYSTEM
สร้าง typography ที่รองรับ TH/EN
มี display, heading, body, UI label, caption และ mono metadata
เครื่องหมายประจำระบบ:
# Main section
// Context, section index, technical label
* Editorial emphasis
ใช้เป็น visual language ที่สม่ำเสมอ
ไม่ใส่ทุกเครื่องหมายในหัวข้อเดียว
Heading variants:
- Hero display
- Editorial statement
- Section heading
- Workspace heading
- Card heading
- Compact label
Highlight variants:
- Gradient word
- Animated underline
- Marker wash
- Outline emphasis
- Color morph
- Subtle chromatic accent
underline ต้องไม่ชนสระและวรรณยุกต์ไทย
ข้อความที่ไม่ใช่ลิงก์ต้องไม่ดูเหมือนลิงก์โดยไม่มีเหตุผล
ใช้ grapheme-safe text processing
เคารพการตัดบรรทัดไทยและ IME composition
# 08 — INFORMATION ARCHITECTURE
Product:
- Home
- Chat & Conversations
- Explore
- Templates
- Create / Canvas
- Research
- Voice
- Live
- Automate
- Library
- Settings
Design OS:
- Overview
- Tokens
- Components
- Layout Studio
- Motion Lab
- Verification
- Export
- Advanced Files & Patch
Shared experiences:
- Global Search / Command Palette
- Media Viewer
- Presentation Mode
- Asset Picker
- Contextual Inspector
- Notifications / Toasts
- Dialogs / Drawers / Bottom Sheets
Design OS เป็นพื้นที่เชิงลึก
อย่ายัด controls ของนักออกแบบทั้งหมดลง Home
ใช้ข้อมูลและ components ร่วมกัน
หลีกเลี่ยง editor, media viewer หรือ preset system ที่ซ้ำซ้อน
# 09 — GLOBAL SHELL
Desktop:
navigation ชัดเจน
sidebar มี hierarchy
พื้นที่ทำงานกว้างพอ
inspector เปิดตามบริบทและยุบได้
Mobile:
navigation กระชับ
drawer หรือ bottom sheet ตามงาน
toolbar สำคัญเข้าถึงง่าย
ไม่ย่อ desktop ทั้งหน้าให้เล็กลง
รองรับ:
- Active route
- Breadcrumb เมื่อมีลำดับชั้น
- Back / forward
- Deep link เมื่อ hosting รองรับ
- Restore selected project และ view state
- Unknown route / missing item
- Visible focus
- Keyboard shortcuts พร้อมคำอธิบาย
Dialog:
focus เข้าอย่างถูกต้อง
Escape ปิดเมื่อเหมาะสม
คืน focus ไปจุดเดิม
ไม่เกิด nested focus traps
Command Palette:
ค้นหา workspace, actions และข้อมูลที่เข้าถึงได้จริง
แยกประเภทผลลัพธ์
รองรับ keyboard และ empty state
# 10 — HOME
ลำดับการนำเสนอ:
1. Brand / navigation
2. Cinematic hero
3. Intelligence, in motion.
4. Composer
5. Primary action และ Watch Demo
6. Selected capabilities
7. Featured creations / cinematic showcase
8. Continue recent work เมื่อมีข้อมูลจริง
9. จุดเข้าสู่ workspace
Hero:
planet rim, atmospheric depth,
orbital vector, restrained microtype และ mascot
Composer อยู่กลาง hero ตาม reference
เมื่อส่งข้อความ:
เปลี่ยนสู่ Chat ภายในประสบการณ์เดียวกัน
ย้าย composer ลงด้านล่าง
รักษา draft, attachments และ focus
Reduced motion ใช้ transition แบบทันทีหรือเบามาก
Hero animation ต้องไม่บล็อกการใช้งาน
ไม่มี intro ที่ต้องรอดูให้จบก่อนคลิก
# 11 — SHARED COMPOSER
รองรับ:
- Multiline text
- Attachment picker
- File validation
- Attachment remove
- Tools menu
- Mode/provider selector เฉพาะที่มีจริง
- Send
- Cancel เมื่อมีงานที่ยกเลิกได้จริง
- Disabled / submitting / error states
- Draft persistence
- Retry without losing input
Enter ส่งและ Shift+Enter ขึ้นบรรทัดใหม่เมื่อเหมาะสม
อย่าส่งระหว่าง IME composition
Microphone:
ต้องเริ่มจาก user gesture
มีสถานะ permission / active / stopped / error
หยุด stream เมื่อเลิกใช้หรือออกจากหน้า
อย่าแสดง model หรือ speed options ที่ไม่มีผลจริง
# 12 — CHAT & CONVERSATIONS
รองรับ:
- New conversation
- History
- Search history
- Rename
- Delete พร้อม undo หรือการยืนยันตามผลกระทบ
- Pin เมื่อ implement จริง
- Draft ต่อ conversation
- Message actions
- Copy
- Retry
- Edit and resend ตาม capability
- Artifact preview
- Open in Create
- Save to Library
ข้อความจากระบบต้องแยก:
user content
assistant output
tool result
sample/demo content
error/status
ถ้าผู้ใช้เลื่อนอ่านข้อความเก่า:
อย่าบังคับ autoscroll
แสดง Jump to latest
Streaming, progress และ tool activity
ต้องสัมพันธ์กับเหตุการณ์จริง
รองรับ:
empty conversation
long text
code blocks
tables
attachments
failed requests
interrupted requests
missing artifacts
# 13 — EXPLORE
ทำเป็น workspace discovery ที่มีบุคลิก
ใช้ portal cards และ vector compositions ที่แตกต่างกัน
แต่ละ workspace card มี:
purpose
ตัวอย่างงานที่ทำได้
primary action
hover/focus state
touch-friendly interaction
มี search/filter เมื่อจำนวนรายการมีประโยชน์ต่อการค้นหา
เลือก card แล้วเข้าสู่ workflow ที่พร้อมเริ่ม
ไม่พาไปหน้าว่างหรือ placeholder ที่ไม่มีคำอธิบาย
# 14 — TEMPLATES
รองรับ:
- Featured templates
- Category filter
- Search
- Preview
- Template detail
- Use template
- Clear filters
- Empty search state
Template ต้องสร้าง document ใหม่
ห้ามทับงานเดิมโดยเงียบ ๆ
กำหนด:
template ID, category, preview asset,
document schema, supported editing และ sample label
ใช้ card แบบ editorial/media
ให้ภาพมีพื้นที่และอ่าน metadata ง่าย
หลังเลือก template:
เปิด Create พร้อม document ที่แก้ไขได้จริง
ชื่อและเนื้อหาต้องตรงกับ template ที่เลือก
# 15 — CREATE / CANVAS
รวม structured Layout Studio กับ Create เป็น editor เดียว
ความสามารถหลัก:
- New document
- Open existing
- Select node
- Edit text
- Replace media
- Position and resize
- Layer list
- Reorder
- Duplicate
- Delete
- Alignment
- Guides
- Pan / zoom
- Fit to canvas
- Undo / redo
- Autosave หรือ explicit save ที่สื่อสารชัด
- Export ตามชนิดงาน
รองรับ grouping, locking และ snapping
เฉพาะเมื่อทำงานครบจริง
แยก coordinate systems:
document coordinates
viewport coordinates
export dimensions
Inspector เปลี่ยนตามชนิด selection
ไม่มี fake handles หรือปุ่มที่ไม่มีผล
เมื่อ feature ยังไม่รองรับให้ซ่อนหรืออธิบายสถานะ
ใช้ document model ร่วมกันระหว่าง:
preview
editing
library
presentation
export
รองรับ empty selection, missing font,
broken asset, oversized content และ export failure
# 16 — RESEARCH
เป็นพื้นที่รวบรวมข้อมูลและจัดโครงสร้างความคิด
รองรับ:
- Research project
- Notes
- Source records
- Tags
- Search/filter
- List view
- Idea map เมื่อมี implementation จริง
- Link related notes
- Edit/delete
- Export notes
- Send selected material to Create หรือ Chat
แยกข้อมูลที่ผู้ใช้ป้อนกับข้อมูลที่ค้นจากแหล่งภายนอก
การ summarize หรือ research ด้วย AI
ต้องใช้ provider จริงจึงแสดงเป็น AI output
ถ้ายังไม่เชื่อม:
ให้ผู้ใช้จัดข้อมูลเองได้ครบ
และอธิบายสถานะ integration สั้น ๆ
# 17 — VOICE
รองรับ:
- Microphone permission
- Start / stop
- Input level จากเสียงจริง
- Recording timer จากเวลาจริง
- Playback เมื่อมีการบันทึก
- Save / discard
- Device or permission errors
Transcription:
เปิดใช้เมื่อมี engine จริง
หากไม่มี ห้ามแสดงคำถอดเสียงจำลองเป็นผลจาก microphone
แยก:
recording
transcribing
playback
idle
cleanup tracks, audio nodes และ object URLs
เมื่อหยุด ออกจากหน้า หรือ component ถูกทำลาย
มีทางเลือกใช้งานด้วยข้อความ
# 18 — LIVE
พื้นที่สำหรับนำเสนอหรือทำงานสด:
- Session title
- Notes
- Cue cards
- Timer
- Presentation controls
- Session summary จากข้อมูลที่มีจริง
- Save session
หากมี transcript หรือ AI assistance:
ระบุ capability และสถานะการเชื่อมต่อจริง
อย่าเปิด microphone โดยอัตโนมัติ
Live mode ต้องมี:
start, pause, resume, finish และ recover draft
ที่สอดคล้องกับข้อมูลและเวลา
# 19 — AUTOMATE
ออกแบบ workflow builder ที่เข้าใจง่าย
รองรับ:
- Workflow list
- Create/edit
- Trigger definition
- Action nodes
- Node configuration
- Connections
- Validation
- Local preview/run
- Execution result
- Error and retry เมื่อทำได้จริง
แยก:
local workflow playback
external automation
scheduled execution
ถ้าไม่มี scheduler/backend:
ห้ามแสดงว่า workflow จะทำงานต่อเมื่อปิด browser
External actions ต้องไม่แสดง connected หรือ success ปลอม
แสดง validation ที่ node ที่ผิด
และอธิบายสิ่งที่ต้องแก้ก่อน run
# 20 — LIBRARY
รวมงานจริงของผู้ใช้:
documents, images, notes, recordings,
presentations และ saved presets ตามชนิดที่รองรับ
รองรับ:
- Grid/list
- Search
- Type filters
- Sort
- Open
- Rename
- Duplicate
- Delete/restore ตามนโยบาย
- Export
- Metadata
- Empty state พร้อมเริ่มสร้างงาน
Sample assets แยกจาก user work
อย่าทำให้ผู้ใช้เข้าใจว่าตนเคยสร้างงานที่เป็น demo
เมื่อเปิด item:
กลับเข้าสู่ editor หรือ viewer ที่ตรงชนิด
รักษา selection/filter/scroll เมื่อย้อนกลับ
# 21 — SETTINGS & SYSTEM STATES
Settings:
- Language TH/EN
- Appearance
- Accent
- Motion quality
- Reduced motion awareness
- Storage usage เมื่อวัดได้จริง
- Backup / restore
- Keyboard shortcuts
- Integration status
- Privacy controls ที่มีผลจริง
Theme preview ต้องไม่เปลี่ยนงานทั้งระบบโดยไม่ชัดเจน
จัดการ:
storage quota
corrupt data
missing item
offline สำหรับ features ที่ต้องเชื่อมต่อ
unsupported browser capability
provider unavailable
Sign in, billing และ cloud sync:
แสดงเฉพาะเมื่อเชื่อมจริง
หรือระบุ unavailable อย่างตรงไปตรงมา
ไม่สร้างบัญชีหรือ subscription จำลองให้ดูเหมือนของจริง
# 22 — CROSS-WORKSPACE WORKFLOWS
ทำและตรวจอย่างน้อย:
1. Home → Chat → Artifact → Create → Save → Library
2. Templates → Preview → New document → Edit → Export
3. Research → Notes → Selected material → Create
4. Library → Open → Edit → Save revision
5. Voice → Record → Playback → Save to Library
6. Live → Cue cards → Presentation → Save session
7. Automate → Configure → Validate → Local run → Results
8. Motion Lab → Preset → Preview → Apply to compatible scene
9. Design Tokens → Preview → Apply → Inspect affected components
10. Library → Media Viewer → Presentation → Return to previous context
ใช้ stable IDs
รักษา draft, selection, scroll และ navigation context
การย้ายข้าม workspace ต้องไม่สร้างข้อมูลซ้ำโดยไม่จำเป็น
และไม่ทำให้งานที่ยังไม่บันทึกหาย
# 23 — CARD SYSTEM REDESIGN
สร้างหก families:
A. Featured Artifact
ภาพเด่น มี title และ primary action
B. Workspace Portal
สื่อหน้าที่ด้วย vector/shape และข้อความสั้น
C. Editorial Note
เน้น typography และข้อมูล
D. Media Frame
ภาพ/video เป็นหลัก พร้อม controls ที่เหมาะสม
E. Workflow Node
ports, status และ configuration ชัดเจน
F. Control Surface
สำหรับ settings/inspector อ่านค่าและปรับได้สะดวก
ทุก family:
default, hover, focus, active, selected,
disabled, loading, error และ empty ตามบริบท
ใช้ border, inset stroke, material และ spacing อย่างมีระบบ
ไม่ใช้ shadow/glow เดียวกันทุกชนิด
Tilt ต้องไม่ขัด drag, selection หรือ touch scrolling
# 24 — ORIGINAL ASSET SYSTEM
สร้าง assets ให้เข้าชุด:
- Cosmic hero environment
- Planet/rim layers
- Mascot
- Featured artwork
- Template previews
- Workspace vector scenes
- Empty-state illustrations
- Presentation scenes
แยกภาพตกแต่งออกจากข้อมูลและ controls
Native SVG:
logo geometry, icons, orbit lines, diagrams,
status vectors และ motion primitives
Raster/generated images:
landscape, atmospheric artwork และ complex illustration
จัด manifest:
asset ID, purpose, format, dimensions,
source/provenance, alt text และ optimization status
มี fallback เมื่อโหลดไม่ได้
กำหนดขนาดล่วงหน้าเพื่อป้องกัน layout shift
อย่า embed ตัวหนังสือที่ต้องเปลี่ยนภาษาไว้ในภาพ
# 25 — LIVING ASSISTANT
Mascot ต้องเป็นส่วนหนึ่งของระบบ
States:
idle
focused
listening เมื่อ microphone active จริง
working เมื่อมีงานจริง
success
error
sleep/calm
Movement:
subtle float
gaze response
orbital motion
small deformation
state transition
จำกัด motion ระหว่างผู้ใช้พิมพ์หรืออ่าน
ไม่ติดตาม pointer อย่างรุนแรง
SVG IDs ต้อง unique
filters ไม่ถูก crop
มี static fallback
หยุดงานเมื่อ hidden/offscreen
# 26 — CLASSIC SCROLL REVEAL
ใช้ dynamic gradient mask เปิดเผยข้อความตาม scroll position
Directions:
Bottom → Top
Top → Bottom
Left → Right
Right → Left
Controls:
start
end
softness
fade edge
stagger
scrub
reverse
opacity range
วัดความสูงข้อความจริง
รองรับ responsive และ font loading
ผูกกับ scroll container ที่ใช้งานจริง
ไม่สมมติว่าทุกหน้าสกรอลล์ผ่าน window
ข้อความต้องอ่านได้เมื่อ:
JavaScript ล้มเหลว
motion disabled
reduced motion active
ห้ามทิ้งข้อความสำคัญไว้ opacity 0 ถาวร
# 27 — SIX CINEMATIC TEXT EFFECTS
1. Blur Reveal
2. Color Morph
3. Scramble
4. Typewriter with caret
5. Kerning Tighten
6. Chromatic Aberration
ทุก effect มี:
duration
delay
intensity
trigger
repeat policy
reset
reduced-motion fallback
Scramble และ Typewriter ต้อง grapheme-safe
ไม่แยกสระและวรรณยุกต์ไทยออกจากพยัญชนะ
Kerning effect ใช้อย่างระมัดระวังกับภาษาไทย
Chromatic effect ต้องอ่านง่าย
ไม่กระพริบรวดเร็วหรือสร้าง RGB ghost หนักตลอดเวลา
Typewriter เป็น presentation effect
ไม่ใช้ปลอมสถานะ AI streaming
# 28 — KINETIC TYPOGRAPHY ENGINE
สร้าง Canvas-based kinetic text system
พร้อม semantic DOM text สำหรับ accessibility
Modes:
ambient
scroll-linked
pointer-reactive
static
Controls:
text
font
size
spacing
path
speed
direction
camera/FOV
depth
rotation
focus
color
echo count
echo decay
quality
pause/reset
จัด depth sorting และ near-plane clipping
ไม่ให้ตัวอักษรระเบิดขนาดเมื่อเข้าใกล้ camera
16 paths:
1. Helix
2. Double Helix
3. Orbital Ring
4. Spiral Vortex
5. Sine Ribbon
6. Figure Eight
7. Lissajous Flow
8. Möbius Loop
9. Torus Knot
10. Spherical Orbit
11. Cylindrical Tunnel
12. Conical Spiral
13. Expanding Wave
14. Grid Fold
15. Fractal Branch
16. Particle Constellation
แต่ละ path ต้องมี geometry แตกต่างจริง
ไม่เปลี่ยนแค่ชื่อ preset
จำกัด DPR, particle/glyph count และ echo budget
ปรับคุณภาพตามขนาดและสมรรถนะ
ไม่อัปเดต React state ทุก frame
หยุด loop เมื่อไม่จำเป็น
ไม่กล่าวว่า “zero DOM overhead” เมื่อยังมี DOM controls
# 29 — 3D SPATIAL CAROUSEL
รองรับ Arc และ Circular geometries
นำ 14 controls จาก V8 มารวม:
radius
arc
curve
perspective
depth
cardWidth
cardHeight
corner
blur
opacity
focusScale
speed
momentum
tilt
ใช้ canonical schema เดียว:
type, unit, range, step, default,
validation และ responsive overrides
แก้ช่วง card dimensions ที่ขัดกันระหว่าง V8 Markdown/JSON
โดยแยก authoring range กับ runtime viewport clamp
Interaction:
drag/swipe
velocity-aware snap
previous/next
keyboard
Home/End
active index
item count
open detail
autoplay ปิดเริ่มต้น
wheel capture ต้อง opt in
inactive cards ต้องไม่บัง active controls
และไม่เกิด duplicated keyboard targets
Mobile ใช้ geometry ที่อ่านและแตะได้
fallback เป็น flat carousel หรือ list เมื่อเหมาะสม
# 30 — CINEMATIC CAROUSEL
แต่ละ scene:
media
headline
context
CTA
progress
ประสาน timing ระหว่างภาพ ข้อความ และ controls
รักษา layout ไม่ให้กระโดด
รองรับ:
manual navigation
pause
replay
keyboard
touch
optional autoplay
Video:
play/pause
mute
loading/error
หยุด inactive video
ไม่ autoplay เสียง
มี gallery/list alternative
ผู้ใช้ต้องเข้าถึงเนื้อหาได้โดยไม่รอ animation
# 31 — 3D MEDIA CORRIDOR / SCROLL EXPAND
ลำดับ:
intro → corridor entry → travel →
selected media → expand → caption/actions → normal page flow
ใช้ perspective และ depth สร้างความรู้สึกเดินผ่านผลงาน
ให้ภาพเด่นขยายเข้าสู่พื้นที่นำเสนออย่างต่อเนื่อง
ต้องมี:
progress cue
skip
reverse scroll
stable reserved space
lazy media
scroll restoration
ใช้ native scrolling และ sticky อย่างจำกัด
ไม่ทำ scroll trap หรือ hijack ทั้งเว็บไซต์
Mobile/reduced motion:
ใช้ stacked gallery หรือ simplified expansion
รักษาเนื้อหาและ CTA ครบ
# 32 — SVG VECTOR MOTION
ใช้หลายตำแหน่งอย่างมีเหตุผล:
- Brand mark
- Hero orbit
- Mascot
- Workspace portal
- Workflow connections
- Loading/status
- Empty states
- Section transitions
- Presentation accents
เทคนิค:
stroke draw
dash offset
path-follow
transform
gradient movement
masked reveal
shape morph ที่ implementation รองรับจริง
ใช้ animation ตามสถานะ
ไม่เล่น decorative loop ทุกจุดพร้อมกัน
ตรวจ:
unique IDs
filter bounds
viewBox
pointer events
screen reader behavior
cleanup
reduced motion
# 33 — MOTION ORCHESTRATION & PHYSICS
กำหนด shared motion tokens:
micro interaction
panel transition
scene transition
ambient cycle
spring stiffness
damping
mass
velocity limits
แยก:
drag momentum
spring settling
autoplay speed
camera movement
ใช้ shared-element transitions เฉพาะที่ช่วยเข้าใจความต่อเนื่อง
เมื่อมีหลาย effects:
กำหนด priority
ลดงานที่ไม่สำคัญ
ไม่ปล่อยทุก loop แข่งขันกัน
รองรับ:
Full
Balanced
Calm
Off
OS reduced motion เป็นข้อจำกัดเพิ่มเติม
ไม่ใช่เพียงชื่อ preset
# 34 — MOTION LAB
Layout:
effect navigation
preview stage
contextual inspector
preset list
playback controls
Categories:
Text Reveal
Kinetic Typography
Spatial Carousel
Cinematic Carousel
Media Corridor
SVG Motion
Card Interaction
Scene Transition
Controls:
play/pause
replay
reset
device preview
quality
reduced-motion preview
save preset
duplicate
import/export
ทุก control ต้องมีผลจริง
แสดง units และค่าปัจจุบัน
Preset:
versioned schema
validated values
compatible target types
preview before apply
ห้าม execute code ที่มากับ imported preset
# 35 — DESIGN OS WORKBENCH
Panels:
Overview
Tokens
Components
Layout Studio
Motion Lab
Verify
Export
Advanced Files & Patch
Tokens:
palette/scales
contrast calculation
theme preview
undo/redo
import/export
Components:
searchable registry
variants
states
interactive previews
usage examples
status/evidence
Layout Studio:
ใช้ editor core เดียวกับ Create
Class/utility tools:
ทำเมื่อเกี่ยวข้องกับ stack จริง
ไม่สร้าง pseudo AST parser หรืออ้างว่าแทน compiler ได้ทั้งหมด
อย่าบังคับเพิ่ม Tailwind หรือ Next.js
เพียงเพราะต้นทาง V8 ใช้
# 36 — COMPONENT REGISTRY & COVERAGE
ใช้ catalog 151 รายการของ V8 เป็น inventory ตั้งต้น
จัดกลุ่ม:
Required now
Supporting
Future
Not applicable
แสดงจำนวนจริง:
catalogued
required
implemented
verified
แต่ละ entry:
id
purpose
variants
states
keyboard behavior
responsive behavior
motion behavior
dependencies
implementation location
verification evidence
รายการชื่อไม่เท่ากับ component ที่ทำงานแล้ว
interactive preview ไม่เท่ากับ production coverage ทั้งระบบ
รวมชื่อซ้ำและใช้ variants อย่างเหมาะสม
ไม่สร้าง component เพื่อไล่ตัวเลข
# 37 — MEDIA VIEWER & PRESENTATION MODE
Media Viewer:
zoom
pan
fit
previous/next
metadata
download/export เมื่อทำได้
open in editor
Escape
focus restoration
return to original scroll position
Presentation:
scene list
next/previous
progress
play/pause
hide chrome
exit
keyboard controls
touch controls
fullscreen แบบ user-initiated เมื่อรองรับ
ใช้ข้อมูลจริงจาก project หรือ labeled samples
ไม่แก้หรือลบงานผู้ใช้เพื่อเตรียม demo
ไม่มี fullscreen trap
กลับสู่ workspace เดิมได้อย่างต่อเนื่อง
# 38 — DATA MODEL & PERSISTENCE
Core entities:
Project
Conversation
Message
Document
LayoutNode
Asset
Template
ResearchNote
SourceRecord
Recording
LiveSession
Workflow
WorkflowRun
MotionPreset
ThemePreset
Presentation
VerificationReport
ใช้เฉพาะ entities ที่ feature ต้องการจริง
กำหนด:
stable ID
schemaVersion
createdAt/updatedAt เมื่อมีความหมาย
relationships
validation
migration
แยก:
persistent data
session state
undo history
temporary preview
verification evidence
เลือก storage ให้เหมาะกับขนาดและชนิดข้อมูล
ไม่ยัด media ขนาดใหญ่ลง localStorage โดยไม่มีเหตุผล
แสดง local save ตามจริง
ห้ามเรียกว่า cloud sync หากไม่มีบริการ sync
Import:
validate → preview → apply → result
Backup ต้องกู้คืนได้จริง
migration failure ต้องไม่ทำลายข้อมูลเดิม
# 39 — ADVANCED FILES & PATCH
หากอยู่ในขอบเขตที่พัฒนา:
ใช้ browser-local virtual file workbench
Flow:
plan → before/after diff →
select changes → apply → checkpoint → undo/restore
ตรวจ:
relative paths
path traversal
size limits
content types
schema
archive entries
ไม่ execute imported HTML/JS อัตโนมัติ
แยก virtual files ออกจาก host filesystem และ repository จริง
review flow ภายในผลิตภัณฑ์
ไม่ใช่การบังคับ coding agent ขออนุญาตทุกการแก้ไขทั่วไป
# 40 — LOCALIZATION & RESPONSIVE
TH/EN ครอบคลุม:
navigation
buttons
forms
validation
empty states
errors
tooltips
settings
status
help text
ไม่แปล user-generated content อัตโนมัติ
รองรับข้อความยาวและวันที่ตาม locale
ตรวจ layout ที่:
320
390
768
1024
1440
1920 px
รวม:
iPad portrait/landscape
split view
touch
trackpad
keyboard
safe areas
software keyboard
ไม่มี horizontal page overflow ที่ไม่ตั้งใจ
scroll ภายในเฉพาะพื้นที่ที่มีเหตุผล
แยกผล device simulation จาก real-device testing ตามจริง
# 41 — ACCESSIBILITY
เป้าหมาย WCAG 2.2 AA
ต้องตรวจจริงในขอบเขตที่ทำได้
ครอบคลุม:
semantic landmarks
heading hierarchy
labels
accessible names
visible focus
keyboard navigation
dialog behavior
error association
contrast
text scaling
touch targets
pause controls
reduced motion
Canvas และ visual-only content:
มี semantic alternative
Hover actions:
เข้าถึงได้ด้วย touch และ keyboard
หลีกเลี่ยง flashing และ motion ที่รุนแรง
สีไม่ใช่ตัวสื่อสถานะเพียงอย่างเดียว
อย่าอ้าง certification จาก contrast calculator อย่างเดียว
# 42 — PERFORMANCE & LIFECYCLE
60 FPS เป็นเป้าหมายที่ต้องวัดบนอุปกรณ์และเงื่อนไขที่ระบุ
ตรวจ:
frame timing
long tasks
input responsiveness
memory
bundle size
asset size
font loading
layout shifts
canvas workload
ใช้:
lazy loading
code splitting ตามความเหมาะสม
demand-driven animation
offscreen suspension
DPR limits
resource cleanup
adaptive quality
cleanup:
event listeners
RAF loops
timers
observers
media streams
audio nodes
object URLs
rendering resources
หยุด optimize เพิ่มเมื่อแก้ความเสี่ยงสำคัญแล้ว
ไม่เพิ่ม dependencies โดยไม่มีประโยชน์ชัดเจน
# 43 — SECURITY & INTEGRATION BOUNDARIES
ไม่เก็บ secrets ใน:
source
client bundle
tokens
presets
exports
checkpoints
logs
ตรวจ imported data และ user text
ใช้ safe rendering
ไม่ inject HTML โดยไม่จำเป็น
API integrations:
provider abstraction
request states
cancellation
error handling
rate/quota handling เมื่อบริการมีจริง
เชื่อมบริการเฉพาะที่จำเป็นและได้รับอนุญาต
ไม่เพิ่ม Web3, IoT, billing, multiplayer หรือ native IDE
เพราะมีชื่ออยู่ใน technology catalog ของ V8
# 44 — VERIFICATION SYSTEM
แยกสองโหมด:
A. Reconstruction / Regression
ใช้ baseline ที่ต้องตรงกันจริง
ตรวจ:
viewport
fonts
loaded assets
animation state
layout geometry
screenshot differences
B. Redesign / Art Direction
ใช้เมื่อออกแบบใหม่โดยเจตนา
ตรวจ:
composition
hierarchy
spacing
typography
brand consistency
content density
usability
motion choreography
V8 thresholds เช่น IoU .995,
mobile drift 2 px, desktop drift 3 px,
image mismatch 5%
เป็นค่าเริ่มต้นสำหรับบริบทที่เหมาะสม
ไม่ใช่กฎตัดสินทุกหน้าตายตัว
Report:
source revision
test conditions
viewport
artifact
result
limitations
stale status
แก้สิ่งที่เกี่ยวข้องแล้วต้อง invalidate evidence เดิม
screenshot เดียวไม่พิสูจน์ motion
ภาพที่เหมือนกันไม่พิสูจน์ workflow
build ผ่านไม่พิสูจน์ usability
ห้ามสร้างคะแนน ผลทดสอบ หรือ heatmap hash ปลอม
# 45 — TEST & ACCEPTANCE MATRIX
ตรวจ:
- Navigation and routing
- Critical cross-workspace journeys
- Editing and undo/redo
- Persistence and reload
- Import/export round trips
- Error recovery
- Keyboard and focus
- Mobile layout
- Reduced motion
- Media cleanup
- Empty and long-content states
- Motion controls and presets
- Provider unavailable states
ทดสอบจุดที่มีความเสี่ยงจริง
ไม่สร้าง tests ที่เพียงทำซ้ำ implementation
ทุก module/effect:
Specified
In progress
Implemented
Verified
Blocked
Blocked ต้องบอก:
สิ่งที่ขาด
ผลกระทบ
ทางเลือกที่ทำได้แล้ว
สิ่งที่ต้องมีเพื่อดำเนินการต่อ
# 46 — EXPORT & DEPLOYMENT
แยก:
user artifact export
token/preset export
project backup
developer scaffold
production deployment
ผู้ใช้ต้องดาวน์โหลดงานหรือ backup ได้
แม้ visual verification ของทั้งแอปยังไม่ครบ
Scaffold:
ระบุชัดว่าติดตั้ง build และทดสอบแล้วหรือยัง
ก่อน deployment:
build สำเร็จ
critical workflows ผ่าน
ไม่มี known blocking errors
ข้อมูลและ migration ตรวจแล้ว
access policy ถูกต้อง
มี rollback path
ไม่ใช้คำว่า pixel-perfect, fully verified หรือ production-ready
หากยังไม่มีหลักฐานเพียงพอ
# 47 — EXECUTION PLAN
ดำเนินการต่อเนื่องตามลำดับ:
1. Audit source และ existing behavior
2. Resolve requirements และ conflicts
3. Build unified schemas
4. Establish tokens and typography
5. Redesign shell and navigation
6. Polish Home and composer
7. Complete Chat and artifact flow
8. Complete Explore and Templates
9. Complete Create and shared editor
10. Complete Research, Voice and Live
11. Complete Automate and Library
12. Complete Settings and persistence
13. Build Motion Lab and effect engines
14. Integrate Design OS
15. Complete media/presentation experiences
16. Polish responsive and accessibility
17. Measure and fix performance risks
18. Verify critical journeys and effects
19. Fix remaining blocking defects
20. Prepare release and handoff
อย่าขยายขอบเขตไปสู่ระบบที่ไม่เกี่ยวข้อง
ก่อนงานหลักของ ARTYVERSE X พร้อม
หากงานต่อเนื่องหลายรอบ:
บันทึก checkpoint, decisions, changed files,
verification results และ next actions
เพื่อทำต่อโดยไม่เริ่มใหม่หรือทับงานค้าง
# 48 — REQUIRED DELIVERABLES
ส่งมอบ:
1. Working ARTYVERSE X source
2. Original optimized assets
3. Unified design tokens
4. Component registry and coverage
5. Motion presets and coverage
6. Workflow map
7. Data schemas and migration notes
8. Verification evidence
9. Known limitations
10. Deployment and rollback information
เอกสาร:
ARTYVERSE_X_MASTER_SPEC.md
artyverse-design-master.json
DESIGN_TOKENS.json
COMPONENT_COVERAGE.md
MOTION_COVERAGE.md
WORKFLOW_MAP.md
VERIFICATION_REPORT.md
MIGRATION_AND_ROLLBACK.md
ใช้ canonical schema เดียวเป็นฐาน
อย่าเก็บค่าซ้ำหลายไฟล์จนไม่ตรงกัน
สรุปส่งมอบ:
สิ่งที่เปลี่ยน
สิ่งที่ใช้งานได้
สิ่งที่ตรวจแล้ว
สิ่งที่ยังต้องเชื่อม
และข้อจำกัดที่มีผลต่อการใช้งาน
# 49 — FINAL CRAFT STANDARD
ARTYVERSE X ต้องดูเป็นผลิตภัณฑ์เดียวกันทุกหน้า
งานจะถือว่า polished เมื่อ:
- composition มีจังหวะและพื้นที่หายใจ
- typography อ่านง่ายทั้งไทยและอังกฤษ
- card และ controls มีระบบ
- แสงและสีมีหน้าที่
- motion ช่วยอธิบายและสร้างบุคลิก
- ทุก action มีผลหรือสถานะที่ชัดเจน
- workflow เชื่อมต่อโดยไม่ทำข้อมูลหาย
- mobile ถูกออกแบบอย่างตั้งใจ
- ปิด effects แล้วยังใช้งานได้ครบ
- รายงานความสามารถตรงกับสิ่งที่สร้างจริง
ความประทับใจต้องเกิดตั้งแต่หน้าแรก
และคงคุณภาพต่อเนื่องจนถึงการแก้ไข บันทึก ส่งออก
และกลับมาใช้งานในครั้งถัดไป
ลงมือพัฒนา ARTYVERSE X ตามข้อกำหนดนี้
ตรวจผลจริง ปรับแก้จนได้คุณภาพที่ตั้งไว้
และส่งมอบพร้อมหลักฐานที่ตรวจสอบได้
