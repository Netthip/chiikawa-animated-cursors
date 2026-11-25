# Chiikawa Animated Cursors 🩷

เคอร์เซอร์ชิกาว่าขยับได้สำหรับ Windows 10 / 11 พร้อมสัญลักษณ์เมาส์สีชมพูพาสเทล

![ตัวอย่างเคอร์เซอร์ 17 แบบ](Chiikawa_Preview.gif)

## ดาวน์โหลด / Download

[**Chiikawa Animated Cursors V2 (.zip)**](https://github.com/Netthip/chiikawa-animated-cursors/raw/refs/heads/main/Chiikawa_Animated_Cursors_v2.zip)

- 17 Windows cursor roles × 3 sizes (32, 48, 64 px)
- 51 animated `.ani` files with 8 frames each, plus 51 static `.cur` alternatives
- Transparent backgrounds and role-specific pink pointer symbols
- Install and restore scripts; no background app required

## วิธีติดตั้ง / Installation

1. ดาวน์โหลด ZIP และแตกไฟล์ทั้งหมด (Extract All)
2. เปิดโฟลเดอร์ขนาดที่ต้องการ: `32`, `48` (แนะนำ) หรือ `64`
3. ดับเบิลคลิก `Install.cmd` เพื่อใช้ชุดเคอร์เซอร์ ไม่ต้องใช้สิทธิ์ Administrator
4. หากต้องการกลับไปใช้เคอร์เซอร์ก่อนติดตั้ง ให้เปิด `Restore.cmd` ในโฟลเดอร์หลัก

หากไม่ต้องการเรียกสคริปต์ ให้เปิด Windows Mouse Properties → Pointers แล้วเลือกไฟล์ `.ani` หรือ `.cur` ให้ตรงกับแต่ละสถานะ ดูรายละเอียดใน `README.txt` ภายใน ZIP

## Verification

All 102 cursor files passed a read-only native Windows loading check. The ZIP contents and PowerShell syntax were also checked. Live Windows animation playback, actual installation/restore, and per-app behavior have not yet been tested. All roles reuse the same approved eight-frame hopping animation; the pointer symbols and hotspots distinguish each role.

## Fan project

Unofficial, non-commercial fan project made for personal use. Chiikawa and its character rights belong to their respective rights holders. This project is not affiliated with or endorsed by the character's creators. No license to the underlying character artwork is granted by this repository.
