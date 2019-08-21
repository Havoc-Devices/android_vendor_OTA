Full Changelog:

••••• 20-08-2019 •••••
Device Changelog:
• Removed the missing NFC confs of whyred
• Fixed HIDL Camera after decryption
• Sensor are now working fine
• Partizion size is now correct
• Set default hotpost name
• Powersave governor in charger mode, to have a better charging time and for not to exceed the temperatures
• Reduced GPS debug level
• Google assistant is now fixed
• Fixed videocalls lag and removed switch, now you can do it with both HAL3 and HAL1 without lags
• Fixed SlowMotion with Google Camera
• HAL3 Enabled by default
• Fixed signal strength visual bug
• Improved battery
• Fixed time_daemon, now you can reboot without lost time
• Fixed Screen Off Torch
• Updated blobs from MIUI 9.8.1
• You can format /cache partition to F2FS filesystem
• Really Improved UI, now it's really smoother
• Removed some obsolete properties
• The installer mention which image is being flashed and only when it actually is
• Enabled Smart Clock
• Now you can perform an OEM Unlock/Relock from developer settings
• Updated CarrierConfing from MIUI 9.8.1
• Hide unsupported color effects entry of Snap Camera
• Fixed Widevine L1
• Powerded by latest Genom-HMP-LA.UM.7.2.r1-07400

••••• 08-08-2019 •••••
Device Changelog:
• Removed the missing NFC confs of whyred
• Fixed HIDL Camera after decryption
• Sensor are now working fine
• Partizion size is now correct
• Set default hotpost name
• Powersave governor in charger mode, to have a better charging time and for not to exceed the temperatures
• Reduced GPS debug level
• Google assistant is now fixed
• Fixed videocalls lag and removed switch, now you can do it with both HAL3 and HAL1 without lags
• Fixed SlowMotion with Google Camera
• HAL3 Enabled by default
• Fixed signal strength visual bug
• Improved battery
• Fixed time_daemon, now you can reboot without lost time
• Fixed Screen Off Torch
• Updated blobs from MIUI 9.8.1
• You can format /cache partition to F2FS filesystem
• Really Improved UI, now it's really smoother
• Removed some obsolete properties
• The installer mention which image is being flashed and only when it actually is
• Enabled Smart Clock
• Now you can perform an OEM Unlock/Relock from developer settings
• Updated CarrierConfing from MIUI 9.8.1
• Hide unsupported color effects entry of Snap Camera
• Fixed Widevine L1
• Powerded by latest Genom-HMP-LA.UM.7.2.r1-07400

••••• 08-08-2019 •••••
ROM Changelog:
• Merged August Security Patch
• Added ability to restrict app vpn usage
• Added translations for Text Clock
• Enabled OP gestures on keyguard
• Improved Dynamic gaming mode
• Updated prebuilt apps
• Other fixes and improvements

Device Changelog:
• Added Polish Translation to HAL3 Switcher
• Fixed a sepolicy denial camera related
• Set gWlanMccToSccSwitchMode to enforce SCC
• Enable NAN data path support 
• A lots of Wi-FI improvements
• Remove crashcheck and resize flag from fstab
• Clean up non-existed props
• Remove config_tether_upstream_types overlay
• Add support for 2 digit normal dialing numbers
• Enable config_enable_video_crbt for more mnc/mcc
• Fixed Google Assistant and enabled by default
• Fixed ADB enabled on boot even if disabled
• Add IIFAAService for Alipay fingerprint payment
• Fixed IFAA crash
• Increase number of max visible notifications icons to 5
• Improved Wi-Fi Hotspot
• Overwrite Bluetooth operating voltage to 3.7V
• Update GPS HAL from LA.UM.7.2.r1-07400-sdm660.0
• Enabled support to Pocket Bridge
• Reference volume index for music stream to limit headphone volume changed to 8
• Improved SSR restart_level for not lost time after reboot
• Remove hw_acc effect
• Enable fluence for audio/voice rec
• Run tftp_server with system group
• Run sensors.qcom with system group
• Build libnl and libwfdaac to fix Wi-Fi display
• Add back correctly created /data/misc/camera folder to fix MIUI camera
• Move control sockets of wpa_supplicant to /data/vendor
• Don't modify permissions of /dev/hw_random
• Set thermal data path
• Drop custom display flags
• Powered by Evira Pure 1.6

••••• 26-07-2019 •••••
ROM Changelog:
• Added Gesture Anywhere
• Added NFC Sounds
• Added translations for Text Clock
• Changed Text Clock color to Wallpaper based
• Improved Battery Estimates
• Improved Pocket Lock
• Improved App info
• Improved Sound settings
• Fixed PiP for Multi-user
• Removed QS tile overlays from app list
• Updated Lawnchair to alpha-2338
• Other fixes and improvements

Device Changelog:
• Disabled 2 UX Optimizations that causes a slowdown of the system
• Included a missing blob for power-off alarm feature

••••• 24-07-2019 •••••
ROM Changelog:
• Added Gaming mode QS tile
• Improved Gaming mode
• Improved OP gestures feedback duration
• Improved Aggressive battery
• Improved LiveDisplay
• Improved Pocket lock
• Fixed crash with some music players
• Performance improvements
• Other fixes and improvement

Device Changelog:
• Rebased to AmulyaX trees
• Improved rounded corners
• Included MIUI 10 vibration pattern
• HAL3 Switcher now translated in RU, ES
• Fixed status bar height
• Fixed FM Radio
• Added thermal engine service on charging
• Show internal storage in DocumentsUI by default
• FM Blobs updated from LA.UM.7.2.r1-06900-sdm660.0
• Improved Dirac
• Updated GPS confs from Jason
• Fixed bug in dual SIM device where preferred data selection didn't stick after reboot
• Disabled unused locations services for GPS
• Updated HAL buffering configuration
• Removed HWUI deprecated properties
• Improved Wi-Fi speed by 2.4GHz channel bonding
• Media volume now have 25 steps
• Disabled RX wakelock in Wi-Fi
• Disabled VSync for CPU rendered apps
• Fixed random Wi-Fi drops
• Pre-opt SystemUI
• Disabled bluetooth at first boot
• Installer now check baseband and not trustzone
• Disabled Interaction Boost
• Compiled libhwui in perf mode
• Increased sound a little
• Fixed audio in apps like Footej, Instagram or Whatsapp
• Adaptive Brightness enabled by default
• Totally fixed Off-Charging
• Improved performance and battery backup
• Included Team_Lavender Stock Kernel

••••• 03-07-2019 •••••
ROM Changelog:
• Merged July Security Patches
• Improved Gaming mode
• Improved Statusbar icon padding
• Improved Smart charging
• Removed Quick unlock
• Updated Lawnchair to alpha-2238
• Other fixes and improvements

Device Changelog:
• Updated Alarm blobs from MIUI 9.6.27
• Re-added HighSpeed profiles for codecs

••••• 02-07-2019 •••••
Device Changelog:
• Added HAL3 | HAL1 Switch, you can find it in Settings > System > Advanced and don't need to reboot for apply changes.
• Disabled ALMK
• Updated Wi-FI Configs
• Turn on Adaptive Brightness by default
• Picked alarm and time blobs from SubDragonzj tree
• Added libinit_lavender

••••• 30-06-2019 •••••
ROM Changelog:
• Added Android Q activity animations
• Added new QS tile styles
• Added new Gaming mode
• Improved Pocket mode
• Improved LiveDisplay
• Improved media notifications
• Improved statusbar items layout
• Improved navbar pixel animation
• Changed battery stats reset level to 95%
• Removed screenshot delay

Device Changelog:
• Used MIUI poweroff charging animation
• Fixed bad microphone quality
• Added HotwordEnrollment blobs for OK Google
• Imported cutout values from MIUI
• Enable workaround for old MCC/MNC format and fixed manual network selection
• Enabled 4K video recording with front camera
• Disabled proximity sensor check before pulsing
• Disabled doze display blank
• Improved AOD
• Fixed Audio HIDL HAL after decryption
• Fixed VoLTE and ViLTE
• Updated Wi-Fi configs from MIUI 9.6.20
• Fixed P2P when connected to 5GHz access point
• Improved audio quality
• Fixed proximity sensor at all
• Enabled HAC
• Enabled "LTE only" button
• Enable NightLight
• Remove cusom VSYNC offsets and improved GPU
• Enabled some UX optimizations and improved performance
• Allow newer baseband
• Fix SlowMotion
• Updated blobs from LA.UM.7.2.r1-06900-sdm660.0
• Don't allow 360° rotations since we have a notch
• Compiled HWUI in perf mode
• Improved battery
• Disabled Interaction Boost since we 't have LineageOS PowerHALs
• Enabled LTE also on 2nd SIMs
• Updated GPS from LA.UM.7.2.r1-07000-sdm660.0
• Updated build fingerprint to V10.3.6.0 stable
• Add glink lpass irq to ignored list
• Improved Notch
• Powered by Evira 3.3 (thanks to @Resurrect88)

••••• 19-06-2019 •••••
• Re-enabled HAL3 (u can disable it for fix WhatsApp videocalls)
• Fixed off-charging
• Fixed rounded corners
• Enabled A-GPS
• Fixed typo of build.prop
• Powered by Evira 2.6

••••• 17-06-2019 •••••
• Reworked live display modes
• Enabled notch settings
• Update GPS from LA.UM.7.2.r1-06900-sdm660
• Updated media and audio codecs
• Fixed vibration
• Some fixed related to camera
• Updated Audio HALs from LA.UM.7.2.r1-07000-sdm660.0
• Always on display is now available
• Updated GPU Bblobs from MIUi 9.6.13
• Added Mi Dirac Audio
• Added support for F2FS
• Fixed sensors
• Fixed vendor mismatch
• Enabled auto power modes
• Enabled Adaptive Battery
• Enabled Smart Pixels
• Fixed Smart Charging
• Enabled multi-user Ui
• Added Bokeh mode to Snap
• Disabled HAL3 for fix WhatsApp videocalls
• Performance improved
• Powered by Evira 2.4

••••• 10-06-2019 •••••
• Fixed Official Tag
• Enabled AOD
• Fixed LTE Signal Strength
• Increased in-call earpiece volume

