# Cursor collection sizes

Animated Friends v3 includes Chiikawa and Kurimanju in 96 and 128 px, plus a native 32 px Compact edition specifically tuned for Windows pointer Size 1. The original Chiikawa V2 still includes 64 px (as well as 32 and 48 px).

| Size | Character size |
|---|---|
| 32 × 32 px | v3 Compact (Windows Size 1) |
| 64 × 64 px | Previous v2 size |
| 96 × 96 px | v3 Medium |
| 128 × 128 px | v3 Large |

ตัวละครจะมีขนาดใหญ่ขึ้นตามจำนวนพิกเซลที่เลือก โดยยังคงสัดส่วนและรายละเอียดของตัวละครไว้

The higher the pixel size, the larger the character is designed to appear, while maintaining its original proportions and details.

像素数值越大，鼠标指针中的角色就越大，同时保持原有的比例和细节。

Actual displayed size depends on cursor scaling and display settings. On the test computer, Windows displayed the 128 px source at 32 px with the pointer slider at Size 1. The native Compact normal pointer was tested on a 27-inch display and reported clearer; all 17 Chiikawa Compact roles were then installed and their paths verified. All Compact files passed native loading and structural validation. Full per-role live playback, restore, Kurimanju live display and macOS compatibility remain untested. Existing V2 remains unchanged.

For modern macOS, MaCursor v3.2 Retina Beta uses a 32-point theme with 32/64/160/320 px (1x/2x/5x/10x) representations. Cursor Scale can be adjusted within [MaCursor](https://github.com/writronic/MaCursor), without changing macOS system size. A Mac user reported that v3.1 loaded but its enlarged hand was pixelated; v3.2 redraws high-resolution symbols directly at each scale. Both v3.2 themes passed structural validation; their actual import, apply and animation remain to be tested.
