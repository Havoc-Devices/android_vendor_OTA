===HAVOC-OS===
==[07/06/19]==
• Added new Gaming mode
  (Havoc Settings > Misc)
• Added a toggle for charging animation
• Added Battery temp in battery usage
• Fixed analog clocks not refreshing in AOD
• Improved Android Q clock related stuff
• Some more fixes/improvements
==[23/06/19]==
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
===PAYTON===
==[09/06/19]==
Device Changelog:-
• ipacm: Fix memory leaks
• Remove send_mic_mute_to_AudioManager overlay
• overlay: enable ethernet in networkAttributes and radioAttributes
• Use tether automatic upstream selection
Kernel Changelog:-
• Reverted more misc changes for stability
• Hotfix: Revert last Wireless Update for now
• Fix cpufreq: times:
    -concurrent_active_time by pid
    -concurrent_policy_time by pid
    -/proc/uid_time_in_state
    -/proc/uid_cpupower/concurrent_active_time
    -/proc/uid_cpupower/concurrent_policy_time
==[30/06/19]==
Device Changelog:-
• Add all IMS APNs for Airtel [IN]
• CarrierConfig: Rework/Nuke many incompatable overlays
• Update power_profile.xml
• Update init scripts
• Update ueventd
• Build sysfs livedisplay
• Move to CAF bluetooth
• Fix MotoFM with correct prop
• Set correct interface for cne server 1.1
• Allow OEM unlock reporting (Not advisable to Uncheck)
Kernel Changelog:-
• X-Payton: v1.8 [Rebased from New MOTO/CAF SDM660, upstreamed to 4.4.184]
• No more random screen jitter/tearing
• Increased overall stability
• VDSO Patchset added
• Add DTS Headphone:X
• Merge CAF Tag: LA.UM.7.2.r1-07000-sdm660.0
• Merge Latest WLAN CAF Tags: LA.UM.7.2.r1-07000-sdm660.0
    -qcacld-3.0
    -qca-wifi-host-cmn
    -fw-api
