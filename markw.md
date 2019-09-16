====================
    16-09-2019
====================

  * Bind restricted apps to cores
  * Double entries are removed from dev tree code
  * Surface Flinger fine tune
  * A lot of code cleanup
  * Network related cleanup
  * Under-the-hood improvements

====================
    13-09-2019
====================

  * Sync with Havoc OS upstream: Android Q Wifi and Signal icon
  * Some GPS speed improvements
  * New NTP servers through GPS

====================
    10-09-2019
====================

  * Sync with Havoc OS upstream: https://t.me/Havoc_OS/1427
  * Camera improvements
  * Physical key binding fixed (thx for Yu Setiadi)

====================
    30-08-2019
====================

  * Missing snapshot feature is fixed
  * Camera is pinned again

====================
    26-08-2019
====================

  * Havoc OS update:  https://t.me/Havoc_OS/1397

====================
    25-08-2019
====================

   * Synced with upstream Havoc source
   * Optimise bluetooth
   * Statusbar adjustments
   * Display supports Doze
   * Re-worked USB Fastcharge
   * Wifi tunings
   * Camera is not pinned
   * Switching to Franco kernel (thx for ShihabZzz)
   * Various under-the-hood improvements

====================
     12-08-2019
====================

   * Synced with upstream Havoc source
   * Fixed WiFi issues found in previous build
   * Power consumption improvement
   * Update of FP HAL

====================
     08-08-2019
====================

   * Synced with upstream Havoc source
   * Reserving 128 MB for critical components (thx jsharkey)
   * Various QCamera improvements
   * Some WiFi improvements
   * FP sensor improvements
   * General code cleanup

====================
     25-07-2019
====================

   * Synced with upstream Havoc source
   * Zeus Kernel update
   * Removed CNE from the build
   * Removed test package from camera (thx zeelog)
   * Swap set to be 896 MB
   * Disabled RX Wakelock (thx luk1337)
   * Max TCP buffer limit increas (thx Astridxx)
   * Removed unnecessary GPS packages (thx davidtrpcevski)

====================
     16-07-2019
====================

   * Synced with upstream Havoc source
   * Enable default support for Aptx Adaptive (thx for mishra)
   * Removed ANT+ completely
   * VoLTE properties are enabled
   * Qualcomm Boost Framework enabled
   * Finger Print is silented in the log
   * Cleanup & Update USB configuration (thx for zeelog)
   * Update Telecomm & Telephony Overlay (thx for ShihabZzz)
   * Critical apps are pinned to avoid swapping (thx for Jorim)
   * General performance and stability improvements
   * General code cleanup

====================
     02-07-2019
====================

   * Synced with upstream Havoc source

====================
     24-06-2019
====================

   * Updated power profile
   * Disabled G11h support on WiFi
   * Removed ANT+ HAL (very-very limited usage)
   * Safetynet bypass hack (thx for Granrage)
   * Update of LiveDisplay HAL
   * Made app startup faster
   * Synced with upstream kernel source
   * Synced with upstream Havoc source

====================
     12-06-2019
====================

   * Added Fast Charge toggle (in XiaomiParts)
   * Added flinger velocity (smooth scrolling)
   * Added NTP server for time sync
   * Added GPS properties (thx SonicBSV)
   * Revert vibration pattern
   * Removed NFC HAL
   * General code cleanup and alignment
   * Synced with Havoc OS upstream

====================
     10-06-2019
====================

   * CPU speed throttling to 2016 MHz is solved (thx @Alphajoza)
   * Vibration pattern from Pixel 2 imported
   * Unnecessary WiFi package is removed
   * Set ZRAM for SWAP
   * Synced with Havoc OS upstream

====================
     06-06-2019
====================

   * Fetched XiaomiParts from previous builds
   * Sepolicy defined for live display (by DennySPB)
   * Missing selinux rule was set for USB (by kondor1995)

====================
     30-05-2019
====================

   * Switching back to Nosgoth kernel
   * Set proper battery capacity for phone
   * Increase JPEG Quality (by YourDeathWish)
   * Removed QC location provider (by Flex1911)
   * Cleaned up some unused BT flags (by Matadeen Mishra)
   * Removed notch capability (by ShihabZzz)

====================
     26-05-2019
====================

   * Smart charge fixed (by DennySPB)
   * PowerHAL is set (by kondors1995)
   * Virtual Display is set to 0 (by nichcream)
   * Reverted OP3 Graphic and Media
   * Slow Motion in GCam disabled (by Granrage)
   * Sync with Havoc upstream

====================
     22-05-2019
====================

   * Updated fingerprint (by nichcream)
   * Media and Graphic update from OP T3 (by ZeeLog)
   * Default network type set to LTE/WCDMA (by Granrage)
   * Wait for MPCTL to start at boot (by dianlujitao)
   * Added Doze properties (by pavlaras)
   * Added proper device name
   * Enable olympian_markw_defconfig for kernel
   * Update with upstream kernel source

====================
     20-05-2019
====================

   * Porting ShihabZzz's Update Dexpreopt commit
   * Use default Dalvik values	
   * Enable dev specific GPS
   * Enable dev specific FMRadio
   * Android Q text clock Hungarian translation
   * Revert "hwui: Enable quicksilver"
   * Further update of Hungarian translation
   * Update of Hungarian translation in Havoc Settings
   * Disable VSYNC and enable FM properties

====================
     17-05-2019
====================

   * Ported Skulshady's "op3: Show battery icon in the QS header"
   * Switched to Olympian Kernel
   * Synced with Havoc upstream

====================
     16-05-2019
====================

   * Added kcal support (thx for NotesOfReality)
   * Added XiaomiParts
   * Under the hood tweaks in XiaomiParts
   * Ported Razziell's "init: clear and simplify init, remove hack for GSI" commit, which aims to bring stability
   * Synced with Havoc source: https://t.me/Havoc_OS/1024 and https://t.me/Havoc_OS/1064

====================
     12-05-2019
====================

   * device/xiaomi/markw/
87a51e0 Added maintainer name and removed hardware key backlight in Settings
203d0ab overlay: disable buttons lights (no hardware support)

   * frameworks/base/
fd9f34a0830 Revert "hwui: Enable quicksilver"
07523095420 base: SystemUI: fix themeing of notification shelf dot
fb5f843c261 Remove useless warning when dismissing notification
51c03601467 pocket: Use MD2 lock drawable
8506599337a KeyguardSliceView: Align as per the Clock Style
715da0ca193 base: Make FP detection in pocket mode configurable [1/2]
a99fb871186 Don't force show battery percentage while charging or powersave
ff1bbb393b8 Android Q text clock Portuguese translation

   * kernel/xiaomi/markw/
6ff91b5e026 Disable UserSpace & Conservative
52910bfc503 Add Usb Fast Charge

   * packages/apps/HavocSettings/
eda9d3d Settings: : Make FP detection in pocket mode configurable [2/2]

   * packages/apps/Settings/
c274d5ae0e Update Russian translations
