# 🎪 สวนเกมของหนู

รวมเกมฝึกตัวเลข คณิตศาสตร์ และภาษาสำหรับเด็ก — เล่นสนุก เรียนง่าย

🔗 **เข้าเล่นได้เลยที่หน้าหลัก:** [tkosin.github.io/bcc185-global](https://tkosin.github.io/bcc185-global/)

หน้าหลักจะพาไปเลือกเกมทั้งหมด และในทุกเกมจะมีปุ่ม 🏠 (มุมซ้ายบน) สำหรับกลับมาหน้าหลักได้ตลอดเวลา

---

## เกมสะกดเลข 0–10 🎮

เกมฝึกสะกดตัวอักษรสำหรับเด็ก — ลากตัวอักษรเรียงให้ถูกต้องเพื่อสะกดชื่อตัวเลข 0 ถึง 10 ทั้งภาษาไทยและภาษาอังกฤษ

🔗 **เล่นออนไลน์ได้เลย:** [tkosin.github.io/bcc185-global/spelling-game.html](https://tkosin.github.io/bcc185-global/spelling-game.html)

---

## 🚂 รถไฟตัวเลข

เกมฝึกคณิตศาสตร์เบื้องต้นสำหรับเด็ก — เลือกโหมด **บวกเลข** (นับสิ่งของแล้วตอบผลรวม) หรือ **ต่อขบวนรถไฟ** (หาเลขที่หายไปในลำดับ) พร้อมเสียงและคอนเฟตติเมื่อตอบถูก

🔗 **เล่นออนไลน์ได้เลย:** [tkosin.github.io/bcc185-global/number-train-game.html](https://tkosin.github.io/bcc185-global/number-train-game.html)

---

## 🚀 ผจญภัยอวกาศ ตัวเลข

เกมฝึกคณิตศาสตร์แบบผจญภัยอวกาศ — เลือกโหมด **บวกดวงดาว** หรือ **ต่อแถวดาวเคราะห์** เลือกระดับความยาก (ง่าย/ปานกลาง) และเล่นได้ทั้งคนเดียวหรือสองคนผลัดกันตอบ พร้อมปุ่มฟังโจทย์ 🔊 และเคล็ดลับสำหรับผู้ปกครอง

🔗 **เล่นออนไลน์ได้เลย:** [tkosin.github.io/bcc185-global/space-adventure-game.html](https://tkosin.github.io/bcc185-global/space-adventure-game.html)

---

## 🏮 แพนด้าล่าโคมไฟศัพท์จีน

เกมฝึกคำศัพท์ภาษาจีน HSK 1 สำหรับเด็ก มี 3 ด่าน: **เปิดโคมสมบัติ** (เรียนคำศัพท์ใหม่ทีละคำพร้อมฟังเสียง), **จับคู่สายฟ้า** (เกมความจำจับคู่คำจีนกับความหมาย), และ **ศึกประลองมังกร** (ตอบคำถามปรนัย 4 ตัวเลือก A/B/C/D)

🔗 **เล่นออนไลน์ได้เลย:** [tkosin.github.io/bcc185-global/chinese-lantern-game.html](https://tkosin.github.io/bcc185-global/chinese-lantern-game.html)

---

## วิธีเล่น

1. เลือกโหมดภาษา: ภาษาไทย / English / ทั้งสองภาษา
2. กด **เริ่มเล่น**
3. ดูตัวเลขที่แสดง แล้ว**ลากหรือแตะ**ตัวอักษรเรียงลงในช่องให้ถูกต้อง
4. เมื่อเรียงถูกจะได้รับดาว ⭐ และดูคอนเฟตติ 🎉
5. กด 💡 **ใบ้** หากติด — กด 🔊 **ฟังเสียง** (โหมดอังกฤษ) เพื่อฟังการออกเสียง

---

## คุณสมบัติ

| ฟีเจอร์ | รายละเอียด |
|---|---|
| 🌐 สองภาษา | ไทย & อังกฤษ หรือสลับกันแบบผสม |
| 👆 Drag & Tap | รองรับทั้งเมาส์และหน้าจอสัมผัส |
| 🔊 Text-to-Speech | ออกเสียงคำภาษาอังกฤษผ่าน Web Speech API |
| 🎆 เอฟเฟกต์ | คอนเฟตติ + พลุไฟ + เสียงฉลอง เมื่อผ่านด่าน |
| 💡 ระบบใบ้ | แนะนำตัวอักษรทีละตัวเมื่อต้องการความช่วยเหลือ |
| 📱 Responsive | ใช้งานได้บนมือถือ แท็บเล็ต และเดสก์ท็อป |

---

## เทคโนโลยีที่ใช้

- **HTML5 / CSS3 / Vanilla JavaScript** — ไม่มี dependencies ภายนอก
- **Web Speech API** — สำหรับ Text-to-Speech
- **Canvas API** — สำหรับ confetti และพลุไฟ
- **Pointer Events API** — รองรับการลากบนทุกอุปกรณ์
- **Google Fonts** — Fredoka & Mali

---

## การติดตั้งและรันในเครื่อง

ไม่ต้องติดตั้งอะไรเพิ่มเติม เปิดไฟล์ได้เลย:

```bash
git clone https://github.com/tkosin/bcc185-global.git
cd bcc185-global
open index.html                  # macOS — หน้าหลัก
open spelling-game.html          # macOS
open number-train-game.html      # macOS
open space-adventure-game.html   # macOS
open chinese-lantern-game.html   # macOS
# หรือ
start index.html                 # Windows — หน้าหลัก
start spelling-game.html         # Windows
start number-train-game.html     # Windows
start space-adventure-game.html  # Windows
start chinese-lantern-game.html  # Windows
```

---

## License

MIT

