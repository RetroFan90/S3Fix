# S3Fix

This 29-byte `.COM` utility is designed to fix the black level pedestal bit issue on the **S3 Trio3D (86C366)** graphics card. 

When executed in MS-DOS, it clears bit 5 in Sequencer Register `1A` (`SR1A`), removing the washed-out 7.5 IRE pedestal and restoring true, deep black levels.

### Usage
Run `S3FIX.COM` directly from the MS-DOS prompt or add it to your `AUTOEXEC.BAT` file to automatically fix the display on boot. 

*Note: You will notice the screen brightness drop slightly when executed—this is completely normal and means the elevated gray-black pedestal has been successfully disabled.*

### Background & Testing
* **Built with:** MS-DOS 6.22 `DEBUG.COM`
* **Tested hardware:** IBM PC300GL (Type 6275) with S3 Trio3D GPU
* **BIOS Version:** 2.0B.05c-C5.03.08

### Acknowledgments
Developed with assistance from Google Gemini AI and research from **Bits Und Bolts (BuB)** on S3 pedestal bit register fixes.

---
*RetroFan90*
