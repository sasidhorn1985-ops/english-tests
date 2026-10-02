
วิธีแก้ 404 + ทำให้ส่งคะแนนได้ (ทำตามนี้เป๊ะๆ ครับ)

1. แก้ Google Sheet ก่อน (ที่ว่างอยู่)
   - เปิดลิงก์ Google Sheet ของครู: https://docs.google.com/spreadsheets/d/1Eh3pKLVjXDZeLdxRhVhTrHu45RDKLWMkg2Lr_ozYyFs/edit
   - ไปเมนู Extensions > Apps Script
   - ลบโค้ดเก่าทั้งหมดทิ้ง แล้วก๊อปโค้ดจากไฟล์ Code.gs ที่พี่ให้ไปวางแทน
   - กด Save (Ctrl+S)
   - กดปุ่ม Deploy > Manage deployments > กดรูปดินสอแก้ไข > Version: New version > กด Deploy
   - สำคัญ: Execute as = Me, Who has access = Anyone
   - กด Deploy แล้ว Copy URL ใหม่ (ถ้า URL เปลี่ยน ให้บอกพี่ เดี๋ยวพี่แก้ไฟล์ให้ใหม่)

2. แก้ GitHub ให้ทับไฟล์เก่า (ที่ทำให้ป๊อปอัพไม่ขึ้น)
   ปัญหา: ในรูปครูเปิด https://sasidhorn1985-ops.github.io/english-tests/Is-Am-Are-Vs.html แล้วยังเป็นไฟล์เก่า ไม่มีป๊อปอัพ
   วิธีทับที่ชัวร์สุด:
   - เข้าไปที่ https://github.com/sasidhorn1985-ops/sasidhorn1985-ops.github.io
   - เข้าโฟลเดอร์ english-tests
   - กดที่ไฟล์ Is-Am-Are-Vs.html > กดปุ่มถังขยะ Delete > Commit
   - กลับมาที่โฟลเดอร์ english-tests > Add file > Upload files > ลากไฟล์ Is-Am-Are-Vs.html ตัวใหม่จากโฟลเดอร์นี้ไปวาง > Commit
   - ทำแบบเดียวกันกับอีก 9 ไฟล์ + index.html
   - หรือลบทั้งโฟลเดอร์ english-tests ทิ้ง แล้วอัพโฟลเดอร์ใหม่นี้ทั้งโฟลเดอร์ไปเลยทีเดียว จะง่ายสุด

3. รอ 2-3 นาที แล้วเปิดลิงก์ใหม่แบบ Private/Incognito
   - เปิด https://sasidhorn1985-ops.github.io/english-tests/
   - ต้องเห็น 10 ข้อสอบ ไม่ใช่ 4 อันแบบเก่า
   - เปิด Is-Am-Are-Vs.html ลองทำ 20 ข้อให้จบ จะต้องเด้งป๊อปอัพ "ทำเสร็จแล้ว! ส่งคะแนนเลยไหม?"
   - กรอกชื่อแล้วกดส่ง กลับไปดู Google Sheet ต้องมีชื่อขึ้นแล้ว

ถ้าทำตามนี้แล้วยังไม่ขึ้น แคปหน้า Apps Script Deployments มาให้พี่ดูนะครับ
