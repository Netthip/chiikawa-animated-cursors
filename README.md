# Chiikawa Animated Cursors 🩷

เคอร์เซอร์ชิกาว่าและคุริมันจูขยับได้สำหรับ Windows 10 / 11 และ macOS (ผ่าน Mousecape)

## Animated Friends v3 — ใหม่ / New

### Compact Size 1 — แนะนำสำหรับ Windows ที่ไม่ต้องการเพิ่มขนาดเมาส์

| Chiikawa Compact 🩷 | Kurimanju Compact 🌰 |
|---|---|
| ![Chiikawa Compact preview](v3/compact/Chiikawa_Preview.gif) | ![Kurimanju Compact preview](v3/compact/Kurimanju_Preview.gif) |
| [Download Chiikawa Compact (.zip)](v3/compact/Chiikawa_Compact_Size1.zip) | [Download Kurimanju Compact (.zip)](v3/compact/Kurimanju_Compact_Size1.zip) |

- Native 32 × 32 px, optimized for Windows pointer **Size 1**. Larger character proportions, stronger contrast, and smaller pointer symbols help retain readable eyes and outlines at the actual displayed size.
- 17 roles, 3 alternate normal pointers, animated ANI and static CUR files with transparent backgrounds and fixed hotspots.
- Extract the ZIP and run `Install.cmd` to install all 17 roles and set Size 1. `Restore.cmd` restores the pre-v3 cursor values, including pointer size if backed up. Both Compact packages share the v3 backup so switching characters does not overwrite the original cursor settings.
- Chiikawa's normal pointer is the exact Compact sample that was tested by Gift on a 27-inch display and reported clearer. All 17 Chiikawa Compact roles were installed and their active paths verified at pointer size 1. All 80 Compact cursor files passed native Windows loading and structural checks. The other roles, Kurimanju live display, and restore have not yet been exhaustively tested.

### Standard v3 — 96 / 128 px and macOS

| Chiikawa 🩷 | Kurimanju 🌰 |
|---|---|
| ![Chiikawa animated preview](v3/Chiikawa_Preview.gif) | ![Kurimanju animated preview](v3/Kurimanju_Preview.gif) |
| [Download Chiikawa v3 (.zip)](v3/Chiikawa_Animated_Friends_v3.zip) | [Download Kurimanju v3 (.zip)](v3/Kurimanju_Animated_Friends_v3.zip) |

- 17 Windows cursor roles, each with a different character pose and role-specific pointer symbol.
- 96 × 96 px (medium) and 128 × 128 px (large); each size also includes three alternate normal pointers.
- 12-frame animations with gentle bounce, tilt, squash, or rocking. Click hotspots stay fixed.
- Animated `.ani` and static `.cur` files for Windows, plus two `.cape` files for macOS using [Mousecape](https://github.com/alexzielenski/Mousecape).
- Transparent backgrounds, animated previews, pose sheets, and installation/restore instructions inside each ZIP.

### ติดตั้ง v3 / Install v3

**Windows:** แตก ZIP แล้วเลือก `Windows/96` หรือ `Windows/128` จากนั้นเปิด `Install.cmd` ไม่ต้องใช้สิทธิ์ Administrator ใช้ `Windows/Restore.cmd` เพื่อคืนค่าก่อนติดตั้ง v3 ครั้งแรก ทั้งสองชุดใช้ข้อมูลสำรองร่วมกัน จึงสลับตัวละครได้โดยไม่เสียข้อมูลเคอร์เซอร์เดิม

**macOS:** ติดตั้ง [Mousecape](https://github.com/alexzielenski/Mousecape/releases) และ Helper ตามคู่มือ เปิดไฟล์ `.cape` ในโฟลเดอร์ `macOS` จากนั้น Apply. การรองรับขึ้นอยู่กับ macOS และ Mousecape รุ่นที่ใช้งาน

**Verification:** Both standard v3 ZIPs passed integrity checks. All 160 Windows `.ani` and `.cur` files (including bonus variants) loaded successfully through the native Windows cursor loader. ANI structure, frame counts, hotspots, alpha masks, and PowerShell script syntax were checked. The four Mousecape plists and their animation image strips were structurally validated. Chiikawa was installed on Windows and tested on 14- and 27-inch displays; Windows rendered the 128 px source at a 32 px actual cursor size when Size 1 was selected. The Compact edition addresses that situation. Exhaustive live playback, restore, and Mac compatibility remain untested. Displayed cursor size may vary with OS scaling or application behavior.

## Chiikawa v2 — เวอร์ชันก่อนหน้า / Previous version

![ตัวอย่างเคอร์เซอร์ 17 แบบ](Chiikawa_Preview.gif)

### ดาวน์โหลด / Download v2

[**Chiikawa Animated Cursors V2 (.zip)**](https://github.com/Netthip/chiikawa-animated-cursors/raw/refs/heads/main/Chiikawa_Animated_Cursors_v2.zip)

- 17 Windows cursor roles × 3 sizes (32, 48, 64 px)
- 51 animated `.ani` files with 8 frames each, plus 51 static `.cur` alternatives
- Transparent backgrounds and role-specific pink pointer symbols
- Install and restore scripts; no background app required

### วิธีติดตั้ง / Installation v2

1. ดาวน์โหลด ZIP และแตกไฟล์ทั้งหมด (Extract All)
2. เปิดโฟลเดอร์ขนาดที่ต้องการ: `32`, `48` (แนะนำ) หรือ `64`
3. ดับเบิลคลิก `Install.cmd` เพื่อใช้ชุดเคอร์เซอร์ ไม่ต้องใช้สิทธิ์ Administrator
4. หากต้องการกลับไปใช้เคอร์เซอร์ก่อนติดตั้ง ให้เปิด `Restore.cmd` ในโฟลเดอร์หลัก

หากไม่ต้องการเรียกสคริปต์ ให้เปิด Windows Mouse Properties → Pointers แล้วเลือกไฟล์ `.ani` หรือ `.cur` ให้ตรงกับแต่ละสถานะ ดูรายละเอียดใน `README.txt` ภายใน ZIP

### Verification v2

All 102 cursor files passed a read-only native Windows loading check. The ZIP contents and PowerShell syntax were also checked. Live Windows animation playback, actual installation/restore, and per-app behavior have not yet been tested. All roles reuse the same approved eight-frame hopping animation; the pointer symbols and hotspots distinguish each role.

## Fan project

Unofficial, non-commercial fan project made for personal use. Chiikawa and its character rights belong to their respective rights holders. This project is not affiliated with or endorsed by the character's creators. No license to the underlying character artwork is granted by this repository.
