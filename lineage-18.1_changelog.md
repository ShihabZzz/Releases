====================
     2021-01-08    
====================

project build/make/
47269dc  build: Remove some debugging props  [Henrique Silva]
4d39bee  Use 'release-keys' for build tag  [Sultanxda]

project device/lineage/sepolicy/
3e9d48f  touch: Add IKeySwapper context  [Arian]

project device/xiaomi/markw/
f182a93  markw: Sync sensor_def_qcomdev with LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
09ba901  markw: Remove libI420colorconvert  [Michael Bestas]
8f5501a  markw: Enable IWLAN assisted mode  [Luca Stefani]
976ad8a  markw: doze: update preference category title text color  [Timi]
2009921  markw: doze: fixup! Fix dark theme issues  [ZeeLog]

project frameworks/base/
ab24fb1  DataSwitchTile: dont show toast on click  [micky387]
bd89fe1  DataSwitchTile: collapse notification panel onClick  [DennySPB]
2918710  SystemUI: Introduce DataSwitchTile  [Christian Oder]
c1274e4  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
9b64241  Restore one-click to add/remove tiles after r19 merge  [ezio84]
8d33af0  SystemUI: Remove build version from qs footer  [Pranav Vashi]
300e79e  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
6554607  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
0c2f24d  base: Add metric for Blinx Settings  [David Trpchevski]
fa07145  SystemUI: Add a tile to show power menu  [DarkJoker360]
65763db  SystemUI: Remove unused resources  [Michael Bestas]
e984175  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
9e40c9f  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
77d473f  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
65762fb  LockIcon: refresh icon on overlay changes  [Dil3mm4]
5eb595b  Properly set fonts and icons on keyguard when changing styles  [ezio84]
adeecc4  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
0b13a62  screenrec: Show dialog on bottom  [El Dainosor]
20a192b  SystemUI: Use AVCProfileMain for screen recorder  [Arne Coucheron]
9a84e21  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
0a56ab9  PowerProfile: allow overriding default power profile  [Alexander Martinz]
33b7810  power: Re-introduce custom charging sounds  [Bruno Martins]
239eff8  incremental: Fix more clang-tidy warnings  [Luca Stefani]
b6e840d  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
ee02403  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/opt/telephony/
1df7071  RIL: Fix manual network selection with old modem  [faust93]
df52daf  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
64c0b9f  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
44d899b  Fix imsi info error when insert some china operator card.  [qiongz]
dd0ffa7  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
0026952  Fix to block sim selection popup for data  [Susheel Nyamala]
1615057  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
ef0ac23  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
f9ca9fb  Enable vendor Telephony plugin  [Sneh Bansal]
a560401  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
2a8efcf  wifi: Add support for Dual Station combination.  [Khanjan Desai]
05a5f1a  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]
cd43830  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
074c455  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
8e8c9de  Add 'vendor.' prefix to a vendor HAL service name  [Jaekyun Seok]
49376e3  Add interface info to .rc files  [Felix]
22c1cc7  livedisplay: Initial conversion to aidl  [Pig]
ba7d528  touch: Add keys swap interface  [Arian]

project kernel/xiaomi/markw/
2556fc0  Redux: 1.05  [ShihabZzz]
e9be543  arch/markw_defconfig: Enable WIREGUARD  [ShihabZzz]
bd15d87  drivers: Silence debugfs failing log spam  [ShihabZzz]
b0b6aab  rcu: boost: avoid preemption before calling complete()  [John Dias]
ce9d2e0  BACKPORT: qseecom: Use scm_call2 when bus_scaling is enabled  [AnilKumar Chimata]
8fa06e9  BACKPORT: qseecom: Remove virtual address print  [Monika Singh]
0887b10  drivers: input: touchscreen: Create keydisabler nodes  [GuaiYiHu]
68d355c  arm:dts: msm8953: Add clock-frequency property  [Remicaa]
60a273c  thermal: Do not log an error if thermal_zone_get_temp returns -EAGAIN  [Hans de Goede]
c296639  msm_thermal: initialize later than arch drivers  [Park Ju Hyung]
0e7744e  msm: ipa: update msm_ipa.h with latest IPA versions constants  [Ghanim Fodi]
51c2a10  Init Redux !!!  [ShihabZzz]
332bcce  Quark: 1.19  [ShihabZzz]
8ff317d  net: Remove dst_cache support  [ShihabZzz]
21c9055  prima: Guard akm_type check with WLAN_FEATURE_SAE  [baunilla]
6f1b5e9  Merge tag 'LA.UM.8.6.c26-01600-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into lineage-17.1  [ShihabZzz]
db2dc60  Merge tag 'LA.UM.8.6.c26-01300-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into lineage-17.1  [ShihabZzz]
b0f2865  Merge tag 'ASB-2021-01-05_3.18'  [ShihabZzz]

project lineage-sdk/
000ee7f  sdk: Add power button qs tile metric  [DarkJoker360]
0918a23  lineage-sdk: Tweak default charging sound path again  [Han Wang]
056187e  LineageHardwareManager: Introduce keys swap feature support  [Arian]

project lineage/mirror/
1e70f99  Updated lineage-minimal to 07-Jan-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/Dialer/
b65fc3a  Dialer: Remove unused resources  [Michael Bestas]
f2d3afd  Fix selecting phone account dialog show error.  [Grace Jia]
1f6b903  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
7c63d64  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
2d37fa3  Messaging: Remove unused resources  [Michael Bestas]
6667a70  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
d7e57cb  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
96c02f3  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
65e4c30  Snap: Remove warnings for generated ids  [Michael W]
f85786e  Snap: there is no camera icon shown if have no camera in first boot up  [zhang sanshan]

project packages/apps/Stk/
1b04e51  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
fd37ca0  Remove unused translation  [Michael Bestas]

project packages/apps/Updater/
1e4aa01  Update Changelog server URL  [ShihabZzz]
b092fb7  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
3ffaadc  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project packages/resources/devicesettings/
072a548  devicesettings: Add common styles  [Bruno Martins]

project system/core/
6bc1d20  logcat: Mark as recovery_available  [Michael Bestas]
60f6edc  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
a92d533  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
a554b0e  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

project system/vold/
a505b31  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
e729b02  Fix the group permissions of the sdcard root.  [Jani Lusikka]
fe9f7da  vold ext4/f2fs: do not use dirsync if we're mounting adopted storage  [Sam Mortimer]
9f10590  vold: Mount ext4/f2fs portable storage with sdcard_posix  [Jani Lusikka]
053e07b  vold: Honor mount options for ext4/f2fs partitions  [Tom Marshall]
afbeb42  vold: Support internal storage partitions  [Tom Marshall]
7cd56fa  vold: Fix fsck on public volumes  [Michael Bestas]
9067e93  vold: add support for more filesystems for public storage  [Dan Pasanen]

project vendor/lineage/
a643e46  backuptool: Support seamless backup and restore to extra partitions  [Alessandro Astone]
b9f5db1  backuptool_ab: Make tmp actually tmpfs  [Alessandro Astone]
8a7176f  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
1a36d44  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
8078326  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
2fd8912  power: Kill "Failed to acquire lock" log  [Luca Stefani]

project vendor/xiaomi/
a55efdd  markw: Remove libI420colorconvert  [Michael Bestas]

====================
     2021-01-07    
====================
project android/
869041b  manifest: Track our forked hardware/google/pixel  [Peter Cai]
c1c7802  manifest: android-11.0.0_r19 -> android-11.0.0_r27  [Michael Bestas]

project frameworks/base/
b4296af  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project hardware/lineage/interfaces/
4f96e3f  trust: set system vintf fragment xml to framework  [Michael Benedict]

project lineage/crowdin/
b65c024  Initial setup for lineage-18.1 translations  [Michael Bestas]

project lineage/hudson/
69758ef  hudson: add Asus Zenfone 5Z (ZS620KL)  [Marc Bourgoin]

project lineage/scripts/
f07e158  aosp-merger: Get branch reliably  [Chirayu Desai]

project lineage/wiki/
71a95c6  wiki: Add Asus Zenfone 5Z (Z01R)  [rohan]

project packages/apps/LineageParts/
c77e9f8  ButtonSettings: Add a setting to swap capacitive keys  [Arian]
5f25790  LineageParts: update preference category title text color  [Timi]

project packages/apps/Trebuchet/
94afb12  Revert "Trebuchet: Add extra privapp permissions xml"  [Michael Bestas]

====================
     2021-01-06    
====================
project android/
5ae2bba  manifest: Sync QTI bootctrl HAL  [LuK1337]

project build/make/
c5362f0  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project development/
c140a31  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project device/lineage/sepolicy/
1165bf2  qcom: gmscore_app: Ignore denials on DSP files too  [Bruno Martins]
0ee6bd8  lineage: Suppress bash related ioctl denials  [Bruno Martins]
811e656  qcom: gmscore_app: suppress denials on firmware  [Adam Shih]

project external/gptfdisk/
60f8818  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project frameworks/av/
ea00c9f  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project frameworks/base/
b0d54ee  SystemUI: add FloatingRotationButton for hw-key devices  [Michal Pražák]

project frameworks/native/
144dd1e  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project hardware/lineage/interfaces/
315d284  gnss: fix -Wreorder-init-list  [Nick Desaulniers]

project hardware/qcom-caf/bootctrl/
d1c4ad0  Expose 1.1 impl via cc_defaults  [LuK1337]
dc8ec5d  Build bootctrl.sdm845 using Android.bp  [Hridya Valsaraju]
432ead1  Drop dependency on librecovery_updater  [LuK1337]

project hardware/qcom-caf/msm8996/audio/
daae2d2  audio: Drop LOCAL_COPY_HEADERS usage  [Pig]
c579dd7  hal: use omx core headers as a header library  [Jaideep Sharma]
cdaff8b  hal: Remove libhwbinder/libhidltransport deps  [Steven Moreland]
d14bf56  audio: Fix flac offload not working  [Keith Mok]
941e9c3  audio: Extend platform parser to allow device name aliasing  [Ethan Chen]
ea82283  hal: Use log/log.h instead of cutils/log.h  [Michael Bestas]
5a25ad6  hal: fix misc audio hal errors  [Weiyin Jiang]
735a825  Build audio.primary.* with BOARD_VNDK_VERSION  [Jiyong Park]
c408b0d  hal: Support the audio amplifier hook  [Daniel Hillenbrand]
16f9b7d  audio: free and assign NULL to global static device pointer  [Preetam Singh Ranawat]
4b08fb4  hal: fix media param not sent during gapless transition  [Weiyin Jiang]
211d5d9  ultrasound: Use log/log.h instead of cutils/log.h  [Michael Bestas]
a30ded0  hal: Add open source HAL for Elliptic Ultrasound  [Balázs Triszka]
09bf07c  audio: Use normal tinycompress  [Rashed Abdel-Tawab]
7be29ef  audio: Use libprocessgroup unconditionally  [Artem Borisov]
e7ec63e  audio: Fix complilation errors under Clang  [Steve Kondik]
d14ea87  audio: Use direct project pathmap  [Ethan Chen]

project hardware/qcom-caf/msm8996/display/
57182e0  Merge tag 'LA.UM.9.6.2.r1-03600-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into eleven-4.x  [ShihabZzz]

project hardware/qcom-caf/msm8996/media/
a2aa811  Merge tag 'LA.UM.9.6.2.r1-03600-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into eleven-4.x  [ShihabZzz]

project lineage/hudson/
24da43f  hudson: promote s3ve3g{xx,jv,ds} to 17.1  [Francescodario Cuzzocrea]

project lineage/wiki/
1242f0d  wiki: devices: promote s3ve3g{xx,jv,ds} to 17.1  [Francescodario Cuzzocrea]

project packages/apps/DocumentsUI/
532d2bd  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project system/bt/
c1f9733  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project vendor/lineage/
d8ad094  audio: Add missing Effect_Tick.ogg effect sound used by the UI  [Adrian DC]

project vendor/qcom/opensource/commonsys/system/bt/
b3a5563  ACL: Drop broadcasts  [Myles Watson]
f23129f  Fix potential OOB write in libbluetooth  [Ted Wang]
62a1288  Fix a security issue in sdp_server.cc  [Hansong Zhang]
37a143b  Check Classic key before cross-key derivation  [Chen Chen]
26aa768  Send a response to an smp security request depending on the callback event  [Rahul Sabnis]
1f868de  [system][bt] fix -Wdangling-gsl  [Nick Desaulniers]
d7ae831  Fix read out of bounds in BtifAvEvent::DeepCopy  [Jakub Pawlowski]

====================
     2021-01-05    
====================

project device/lineage/sepolicy/
cbba130  common: dynamic: Replace packageblacklist with packageexludelist  [Arian]

project device/xiaomi/markw/
4164f39  markw: Set property procedure_bytes to SKIP  [Sandeep Gutta]
72549ce  markw: Don't build vndk_package  [Luca Stefani]
2eb79cd  markw: Deduplicate handheld_core_hardware.xml copy rule  [Bruno Martins]
5d81252  markw: Place a copy of thermal.msm8953.so  [ZeeLog]
9e6a795  markw: Restore Thermal HAL 1.0  [ZeeLog]
4b83415  markw: Remove duplicate bfq scheduler setting  [ZeeLog]
817b93b  markw: Update time related properties  [ZeeLog]
d5e6687  markw: sepolicy: Update after LA.UM.9.2.1.r1-05500-sdm660.0 merge  [ShihabZzz]
cadb03b  markw: sepolicy: Address power off alarm denials  [ShihabZzz]
c916fd6  markw: sepolicy: allow cnd to access qti mwqemadapter  [ZeeLog]
a865ece  markw: GPS: Ditch slim_daemon  [ZeeLog]
5829c09  markw: Drop 32bit blobs for Gatekeeper & Keystore  [ZeeLog]
57a253b  markw: Update blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]

project frameworks/base/
364462f  camera: Support exposing aux camera to apps  [Sauhard Pande]

project hardware/lineage/interfaces/
742a534  trust: Include VINTF fragments  [Michael Bestas]

project kernel/xiaomi/markw/
a98f8b7  locking/atomic, kref: Add KREF_INIT()  [Peter Zijlstra]
5869e11  ANDROID: usb: f_accessory: Do not sync non-existent work queues  [Lee Jones]
c6ff8a1  fbdev: s6e8ax0: avoid unused function warnings  [Arnd Bergmann]
5a56200  mtd: cfi: enforce valid geometry configuration  [Arnd Bergmann]
2181ec2  mtd: sh_flctl: pass FIFO as physical address  [Arnd Bergmann]
951ce58  amd-xgbe: Fix unused suspend handlers build warning  [Borislav Petkov]
2e0e366  fbdev: auo_k190x: avoid unused function warnings  [Arnd Bergmann]
2ad262f  driver-core: use 'dev' argument in dev_dbg_ratelimited stub  [Arnd Bergmann]
051102b  target/user: Fix cast from pointer to phys_addr_t  [Arnd Bergmann]
90f0efa  tty: hvc_xen: hide xen_console_remove when unused  [Arnd Bergmann]
7b4ce910  usb: musb/ux500: remove duplicate check for dma_is_compatible  [Arnd Bergmann]
2ebc81c  pwc: hide unused label  [Arnd Bergmann]
edb9be3  SCSI: initio: remove duplicate module device table  [Arnd Bergmann]
fe6b53f  scsi: mvumi: use __maybe_unused to hide pm functions  [Arnd Bergmann]
bb4838a  video: Use bool instead int pointer for get_opt_bool() argument  [Daniel Wagner]
bba2f09  fbdev: sis: enforce selection of at least one backend  [Arnd Bergmann]
c18e98d  staging: ste_rmi4: avoid unused function warnings  [Arnd Bergmann]
0e0d3e4  video: fbdev: sis: remove unused variable  [Sudip Mukherjee]
ef1b60c  scsi: fdomain: drop fdomain_pci_tbl when built-in  [Arnd Bergmann]
359bb1e  mptfusion: hide unused seq_mpt_print_ioc_summary function  [Arnd Bergmann]
987526c  mtd: maps: add __init attribute  [Julia Lawall]
2108823  mtd: ichxrom: maybe-uninitialized with gcc-4.9  [Arnd Bergmann]

project vendor/lineage/
64b5b1c  partner_gms: Simplify if/else if logic  [Ethan Chen]

project vendor/xiaomi/
06c31ee  markw: Place a copy of thermal.msm8953.so  [ShihabZzz]

====================
     2021-01-04    
====================

project packages/apps/ThemePicker/
4885e54  ThemePicker: Make naming page look the same as the other ones  [Michael W]

====================
     2021-01-03    
====================

project device/qcom/sepolicy-legacy-um/
f481ca5  legacy: Add vendor prefix to sensors_dbg_prop  [ShihabZzz]

project device/xiaomi/markw/
348f30f  markw: manifest: Remove Trust interface entry  [Michael Bestas]
7fedac5  markw: Remove android.hardware.graphics.composer@2.1-impl  [Michael Bestas]
0b33438  markw: Use CodeAurora ImsService implementation for RCS  [Bruno Martins]
127fb4c  markw: Replace BOARD_CHARGER_DISABLE_INIT_BLANK with equivalent prop  [Bruno Martins]
c34df9e  markw: Don't duplicate TARGET_USES_MEDIA_EXTENSIONS flag  [Ethan Chen]
cd975bd  markw: Fix libhwbinder/libhidltransport related commit derps  [ShihabZzz]

project packages/apps/WallpaperPicker2/
12ff1a2  WallpaperPicker2: Increase height of bottom area  [Michael W]
00295a8  WallpaperPicker2: Match backgrounds to device theme  [Filippo]

project vendor/lineage/
151e171  build: Relocate extract utils to tools/extract-utils  [Michael Bestas]

project vendor/xiaomi/
7a92807  markw: GPS: Ditch slim_daemon  [ZeeLog]
da15d80  markw: Drop 32bit blobs for Gatekeeper & Keystore  [ZeeLog]
14c1c49  markw: Update blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]

====================
     2021-01-02    
====================

project device/qcom/sepolicy-legacy-um/
3871bda  legacy: Remove power/light AIDL file context declaration  [ShihabZzz]
e2fdb8e  Merge tag 'LA.UM.9.2.1.r1-05500-sdm660.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into lineage-18.1-legacy-um  [ShihabZzz]

project frameworks/base/
31355d7  NotificationPanelViewController: Fix DT2S gesture handling  [Arian]
48fa9f4  SystemUI: Hide lockscreen media art if media is not playing  [Ezio Lacandia Bijelkic]

project lineage-sdk/
54d862c  SystemUI: NetworkTraffic: Refactor message handling  [Michael W]

project packages/apps/Settings/
e4faed9  Gestures: Allow power menu settings for advanced restart on Go  [Adrian DC]

project vendor/lineage/
790ab1d  config: Handle TARGET_EXCLUDES_AUDIOFX in the products definitions  [Adrian DC]

====================
     2021-01-01    
====================
project android/
efc9672  lineage: Enable legacy NXP repo  [Bruno Martins]

project bootable/recovery/
a45cc8d  recovery: Add logcat to deps  [Michael Bestas]

project lineage/mirror/
e6c6534  Updated to 31-Dec-2020 15:30 UTC  [Kevin F. Haggerty]

project packages/apps/AudioFX/
89a6bb9  AudioFX: Convert to Android.bp  [Michael Bestas]
493a7e6  AudioFX: Remove deprecated ONE_SHOT_MAKEFILE  [Michael Bestas]
4d06212  AudioFX: Use the TARGET_EXCLUDES_AUDIOFX flag in products, not .mk  [Adrian DC]

project packages/apps/SetupWizard/
e90cf31  SetupWizard: update recovery after setup  [Timi]

project vendor/lineage/
3aa50f8  config: Add dataservices to PRODUCT_SOONG_NAMESPACES if needed  [Michael Bestas]

====================
     2020-12-31    
====================
project android/
3748528  manifest: Track our own external toybox and boringssl repos  [Adrian DC]

project art/
fd08014  Use the non-debug apex for userdebug builds  [Baligh Uddin]

project device/xiaomi/markw/
394106b  Revert "markw: Update qti privapp permissions"  [ZeeLog]
4ad044d  markw: sepolicy: Use BOARD_VENDOR_SEPOLICY_DIRS  [Felix]
92276a5  markw: Switch to standalone extract utils  [Michael Bestas]

project kernel/xiaomi/markw/
f5b3332  md: avoid warning for 32-bit sector_t  [Arnd Bergmann]
45b3dba3  profile: hide unused functions when !CONFIG_PROC_FS  [Arnd Bergmann]
c4648ed  dpt_i2o: fix build warning  [Sudip Mukherjee]
f25da14  drivers/net: fix eisa_driver probe section mismatch  [Fabian Frederick]
625cf92  scsi: sim710: fix build warning  [Sudip Mukherjee]
6df868a  x86/boot: Avoid warning for zero-filling .bss  [Arnd Bergmann]
a7acdd8  thermal: spear: use __maybe_unused for PM functions  [Arnd Bergmann]
8a07820  ssb: mark ssb_bus_register as __maybe_unused  [Arnd Bergmann]
41e4c12  reiserfs: avoid a -Wmaybe-uninitialized warning  [Arnd Bergmann]
e422a28  ALSA: hda/ca0132 - fix possible NULL pointer use  [Arnd Bergmann]
5876601  arm64: Kconfig: select COMPAT_BINFMT_ELF only when BINFMT_ELF is set  [Kefeng Wang]
57d64b5  scsi: advansys: fix uninitialized data access  [Arnd Bergmann]
006d321  x86: add MULTIUSER dependency for KVM  [Arnd Bergmann]
8ab117e  x86/build: Silence the build with "make -s"  [Arnd Bergmann]
65eb89b  x86/fpu/math-emu: Fix possible uninitialized variable use  [Arnd Bergmann]
85bb806  x86/ras/inject: Make it depend on X86_LOCAL_APIC=y  [Borislav Petkov]
e38556a  scsi: advansys: fix build warning for PCI=n  [Arnd Bergmann]
ecd8222  video: fbdev: via: remove possibly unused variables  [Arnd Bergmann]
7102a02  platform/x86: intel_mid_thermal: Fix suspend handlers unused warning  [Borislav Petkov]
fb673fb  gpio: intel-mid: Fix build warning when !CONFIG_PM  [Augusto Mecking Caringi]
99bff7a  vmxnet3: prevent building with 64K pages  [Arnd Bergmann]
c92aa1b  isdn: icn: remove a #warning  [Arnd Bergmann]
3d902e3  virtio_balloon: prevent uninitialized variable use  [Arnd Bergmann]
c9c7971  RDMA/cma: Make sure that PSN is not over max allowed  [Moni Shoua]
fb10dad  ARM: OMAP2+: Fix SRAM virt to phys translation for save_secure_ram_context  [Tony Lindgren]
ef2f2b9  staging: android: ashmem: Fix a race condition in pin ioctls  [Ben Hutchings]
e3a09ef  Make DST_CACHE a silent config option  [Dave Jones]
6d18aa7  KVM: x86: fix escape of guest dr6 to the host  [Wanpeng Li]
7b5efa2  drm: Require __GFP_NOFAIL for the legacy drm_modeset_lock_all  [Chris Wilson]
5ee260e  blktrace: fix unlocked registration of tracepoints  [Jens Axboe]
04deaf6  xfrm: Fix stack-out-of-bounds read on socket policy lookup.  [Steffen Klassert]
44469c8  cfg80211: check dev_set_name() return value  [Johannes Berg]
a92c6ba  net: add dst_cache support  [Paolo Abeni]
417c4c7  ARM: pxa/tosa-bt: add MODULE_LICENSE tag  [Arnd Bergmann]
de06c6e  vfs: don't do RCU lookup of empty pathnames  [Linus Torvalds]
d56423e  mvpp2: fix multicast address filter  [Mikulas Patocka]
176aa4a  ALSA: usb-audio: add implicit fb quirk for Behringer UFX1204  [Lassi Ylikojola]
21afbcf  ALSA: hda/realtek: PCI quirk for Fujitsu U7x7  [Jan-Marek Glogowski]
075f112  ALSA: usb-audio: Fix UAC2 get_ctl request with a RANGE attribute  [Kirill Marinushkin]
53f836f  ALSA: usb-audio: Fix parameter block size for UAC2 control requests  [Julian Scheel]
07c4d29  Btrfs: Initialize btrfs_root->highest_objectid when loading tree root and subvolume roots  [Chandan Rajendra]
78219d5  ALSA: hda - Fix headset mic detection problem for two Dell machines  [Hui Wang]
6101fba  Btrfs: fix unexpected -EEXIST when creating new inode  [Liu Bo]
1344e55  mm: hide a #warning for COMPILE_TEST  [Arnd Bergmann]
c5120456  x86/cpu: Change type of x86_cache_size variable to unsigned int  [Gustavo A. R. Silva]
09571d1  ovl: fix failure to fsync lower dir  [Amir Goldstein]
dc4318d  btrfs: Handle btrfs_set_extent_delalloc failure in fixup worker  [Nikolay Borisov]
958fe2c  Bluetooth: btsdio: Do not bind to non-removable BCM43341  [Hans de Goede]
4503d8b  watchdog: imx2_wdt: restore previous timeout after suspend+resume  [Martin Kaiser]
c948b18  ahci: Add Intel Cannon Lake PCH-H PCI ID  [Mika Westerberg]
e094301  ahci: Add PCI ids for Intel Bay Trail, Cherry Trail and Apollo Lake AHCI  [Hans de Goede]
4510762  ahci: Annotate PCI ids for mobile Intel chipsets as such  [Hans de Goede]
34c7d96  nfs/pnfs: fix nfs_direct_req ref leak when i/o falls back to the mds  [Scott Mayhew]
5b84a9b  ubi: block: Fix locking for idr_alloc/idr_remove  [Bradley Bolen]
320441a  mtd: cfi: convert inline functions to macros  [Arnd Bergmann]
d396fe5  dmaengine: dmatest: fix container_of member in dmatest_callback  [Yang Shunyong]
0becece  media: soc_camera: soc_scale_crop: add missing MODULE_DESCRIPTION/AUTHOR/LICENSE  [Jesse Chan]
31902e2  ASoC: rsnd: avoid duplicate free_irq()  [Kuninori Morimoto]
56c9326  ASoC: rsnd: don't call free_irq() on Parent SSI  [Kuninori Morimoto]
9e93dca  brcmfmac: Add support for bcm43340/1 wireless chipsets  [Arend van Spriel]

project lineage/mirror/
c07fe56  Updated lineage-minimal to 30-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
44e1c32  wiki: Add Adreno 308 as a valid GPU  [Jarl-Penguin]

project system/core/
0e21924  init: Add activation logs for flattened APEX folders with details  [Adrian DC]
f7603c9  Reboot sequence: Unmount active apexes before unmounting /data  [Nikita Ioffe]
5dcd1b8  init: Sort the list of flattened APEX folders to avoid variations  [Adrian DC]

project vendor/qcom/opensource/dataservices/
821b3b0  dataservices: Define soong namespace  [razorloves]

====================
     2020-12-30    
====================
project android/
cae0362  lineage: Sync standalone extract utils  [Michael Bestas]

project build/soong/
2bc83fb  Check `base` property before using it  [Jooyung Han]

project device/xiaomi/markw/
1721da3  markw: Update sha1sum for modified lowi.conf  [ZeeLog]
7ff427b  markw: do not build useless packages  [Demon Singur]
6a3061a  markw: Remove unnecessary android.hardware.radio entries  [Ethan Chen]
fa01ff9  markw: Remove unnecessary netutils packages  [Ethan Chen]
83dd138  markw: Enable ipsec_tunnel feature  [Prakash Pabba]
22fe0f5  markw: Drop TARGET_USES_NEW_ION_API flag  [Cosme Domínguez Díaz]
6a4a097  markw: Remove deprecated TARGET_USES_OVERLAY  [Nolen Johnson]
d0c2ac4  markw: Remove obsolete dex settings  [Anton Hansson]
7040f6d  markw: kill deprecated/unneeded board flags  [Nolen Johnson]
22a1cd8  markw: Remove TARGET_USES_64_BIT_BINDER  [Kilian von Pflugk]
1fce2cd  markw: Remove deprecated TARGET_BOARD_PLATFORM_GPU  [Arne Coucheron]
2410efe  markw: Sign Tether RROs with default cert  [Bruno Martins]
e1f45a6  markw: Don't sign Wifi RROs with platform cert  [David Su]
8de09db  markw: TetheringOverlay: Drop custom dhcp range  [Michael Bestas]
1c6dfcf  markw: Opt out recovery update  [ZeeLog]
11a3a67  markw: Update CarrierConfig from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]

project frameworks/base/
ec93ea4  audio: Discard QTI only codecs when AOSP BT stack is in use  [LuK1337]

project kernel/xiaomi/markw/
50e1b77  ANDROID: usb: f_accessory: Don't drop NULL reference in acc_disconnect()  [Will Deacon]
8a2145c  ANDROID: usb: f_accessory: Avoid bitfields for shared variables  [Will Deacon]
89f6d21  ANDROID: usb: f_accessory: Cancel any pending work before teardown  [Will Deacon]
d4f0ff5  ANDROID: usb: f_accessory: Don't corrupt global state on double registration  [Will Deacon]
d3c9e6d  ANDROID: usb: f_accessory: Fix teardown ordering in acc_release()  [Will Deacon]
1f1baf4  ANDROID: usb: f_accessory: Add refcounting to global 'acc_dev'  [Will Deacon]
878433b  ANDROID: usb: f_accessory: Wrap '_acc_dev' in get()/put() accessors  [Will Deacon]
cf6c7cf  ANDROID: usb: f_accessory: Remove useless assignment  [Will Deacon]
089f40c  ANDROID: usb: f_accessory: Remove useless non-debug prints  [Will Deacon]
e00d235  ANDROID: usb: f_accessory: Remove stale comments  [Will Deacon]
8339340  ANDROID: USB: f_accessory: Check dev pointer before decoding ctrl request  [Vijayavardhan Vennapusa]
5a1d004  ANDROID: usb: gadget: f_accessory: fix CTS test stuck  [Macpaul Lin]

project vendor/lineage/
f17c855  lineage: apns: Update T-Mobile US to reflect latest carrier changes  [Zachariah Anderson]

project vendor/xiaomi/
5c80e46  markw: Remove copyright headers from automatically generated files  [Michael Bestas]
2a03321  markw: gps: lowi.conf: lower debug level  [ZeeLog]

====================
     2020-12-29    
====================

project external/boringssl/
7bac33a  libcrypto: Add support for toybox_static build dependencies  [Adrian DC]

project external/toybox/
48ba553  toybox: Restore support for toybox_static binary  [Adrian DC]

project frameworks/base/
2373904  SystemUI: Resolve faulty keyguard clock logs outputs  [Adrian DC]
a31439f  SystemUI: Fix size of icon of vibrate ringer mode for additional icon packs  [Volodymyr Zhdanov]

project lineage/hudson/
368fd5c  hudson: Promote FP3 to 17.1  [Daniel Köster]

project lineage/mirror/
b85f1a0  Updated to 28-Dec-2020 13:00 UTC  [Tim Schumacher]

project packages/apps/Nfc/
1c9d53d  nxp: Add support for Android 11 API changes  [Adrian DC]
b5c160a  nxp: Q api updates  [Alessandro Astone]
b63424e  nxp: jni: Implement AOSP P abstract methods  [Adrian DC]
5de0924  nxp: jni: Remove unused variables and functions  [Adrian DC]
757e2ae  nxp: jni: use proper nativehelper headers  [Steven Moreland]
6269e32  nxp: NativeNfcManager: Implement missing inherited abstract methods  [Bruno Martins]
8582bf4  nxp: jni: Forward-port the stack sources  [Adrian DC]
748a5e0  NFC: Restore legacy NXP stack  [Adrian DC]

project tools/extract-utils/
fb4ad78  Remove support for /sbin  [Michael Bestas]
55ec886  templates: Support extracting only either common or target device blobs  [Bruno Martins]
805a684  Update sdat2img.py  [Michael Bestas]
41cd5a0  Replace Apache 2.0 boilerplate/reference with SPDX  [Michael Bestas]
830a9cb  Add multi-device templates and update normal templates  [Michael Bestas]

====================
     2020-12-28    
====================

project device/xiaomi/markw/
6ec4779  markw: sepolicy: Address more gmscore & iorap related denials  [ShihabZzz]

project external/chromium-webview/
c780a2e  webview: Hard no to persistent histograms  [Kevin F. Haggerty]

project lineage/wiki/
caad00f  devices: FP3: Promote to 17.1  [Daniel Köster]

project packages/apps/Camera2/
49af717  Camera2: Set targetSdkVersion=29  [Michael Bestas]

project packages/apps/Updater/
29ca6e5  update push script: remove bashisms  [chrmhoffmann]

project prebuilts/tools-lineage/
214ba0c  Relocate extract tools to prebuilts/extract-tools  [Michael Bestas]

project tools/extract-utils/
8e4a039  Remove copyright headers from automatically generated files  [Michael Bestas]
ab77884  Remove branding from script variables  [Michael Bestas]
5a82907  Adapt for new tools location  [Michael Bestas]
8f82a58  Adapt for new script location  [Michael Bestas]
490e38e  fixup! extract_utils: implement patchelf  [Sebastiano Barezzi]

====================
     2020-12-27    
====================
project android/
f315bb7  manifest: Track our own tzdata-related repos  [Kevin F. Haggerty]
fa215b0  lineage: Re-sync QTI BT repos  [Pig]

project device/qcom/sepolicy_vndr/
0a4f9ef  legacy: Allow writing WLAN driver/fw version into property  [Bruno Martins]

project external/cldr/
bca0ad9  RESTRICT AUTOMERGE CLDR-14225 tz database 2020b updates [R]  [Neil Fuller]
1b1fe92  RESTRICT AUTOMERGE CLDR-13739 Changed some tzdata files to rear-guard version. (#445)  [Neil Fuller]

project external/icu/
56b88bc  RESTRICT AUTOMERGE Update Android to tzdb 2020d [R]  [Neil Fuller]
e0583f3  RESTRICT AUTOMERGE Update Android to tzdb 2020c [R]  [Neil Fuller]
394ae3d  RESTRICT AUTOMERGE Update Android to tzdb 2020b [R]  [Neil Fuller]

project frameworks/base/
f72364c  Add LC3 codec type.  [pramod kotreshappa]
d78d862  Audio: Add support for lc3 codec.  [Manisha Agarwal]
d620f88  Bluetooth: Add APTX-Adaptive and APTX-TWS+ entries.  [Kiran Kelageri]
77aa064  Add callback onA2dpCodecConfigChanged  [Mingbo Zhang]
10a9885  Audio: Do not disconnect profiles till Bluetooth Off  [Gurpreet Ghai]
3518d60  Audio: use cached BT codec info during disconnecting  [Zhou Song]
de3689c  Audio: Update current active bt device of mApmConnectedDevices.  [Manisha Agarwal]
9a44270  BT-Audio: Keep track of Active TWS+ EB device in BTHelper  [Sagar Verma]
3d08aec  BLE: Fix NPE during start advertising  [Sravan Voleti]
42ca62d  Fix build errors  [Scott Lobdell]
0f9e029  Fix BLE transport discovery scan filter  [Subramanian Srinivasan]
ca935c9  BT: Relocate A2DP codec strings for translation  [dianlujitao]
0218bfb  Enable codec change request when mode changes in aptX-adaptive  [Naval saini]
70f4132  Keep a null check before accessing the BluetoothA2dpWrapper APIs.  [Satheesh Kumar Pallemoni]
371694c  Bluetooth: Fix for out of bound exception  [pramod kotreshappa]
75b80d1  BT Dev: Increase array size for codec selection in Dev Op  [Gurpreet Ghai]
73da27f  Keep the BluetoothHeadset finalize() method protected  [Diego Wilson]
fc7ce01  Bluetooth: Fix for Global reference table overflow issue[1/2]  [Bandari Ramesh]
c2d32c0  BT: Add new intent to broadcast IOT device details  [Gurpreet Ghai]
79e027d  BT_Audio: Updated Check for TWS+ switch  [Gurpreet Ghai]
8f24488  TWS_A2DP: Handle active device change between TWS+ earbuds  [pramod kotreshappa]
f9167b3  audio: Add support for APTX TWSP audio codec  [Dhananjay Kumar]
6e6110f  audio: Add support for audio extended codecs  [Naresh Tanniru]
143de07  Use BluetoothUtils instead of Utils  [Diego Wilson]
282ac82  GAP: Handle the race condition cases in auto connect logic  [Venkata Jagadeesh Garaga]
408ffd1  Obex: Squashed commit of the following  [Sravan Kumar V]
64067a1  Add scan filter for Transport Discovery data  [Subramanian Srinivasan]
8ce3d8d  Support CALLBACK_TYPE_SENSOR_ROUTING  [Mingbo Zhang]
d72d3aa  Add support for Transport discovery AD type (1/2)  [Subramanian Srinivasan]
6c0ca70  Bluetooth: TWSP: Support Battery Status information display  [Bhakthavatsala Raghavendra]
624f769  BT: Send info if call is CS type from telecomm service to BT apps.  [Sumit Bajpai]
b28fd0b  GAP: Reset bondingInitiatedLocally flag(1/3)  [Venkata Jagadeesh Garaga]
be64cbb  Bluetooth-TWS: Disable outgoing connection to 2nd earbud  [Kiran Kelageri]
82f0609  Bluetooth-TWS: Disable outgoing connection for 2nd earbud.  [Kiran Kelageri]
9289829  Bluetooth: Rename bluetooth property to support new P Treble rules  [Safoorah Banu Shaik]
37661a4  Bluetooth: Unpair both earbuds on unpair.  [Kiran Kelageri]
86eb709  Bluetooth: Add SDK API support for TWS feature (2)  [Bandari Ramesh]
948cad4  Revert the change: AudioService: remove dead BT code.  [Samyak Jain]
0a5e399  TWS-A2DP: Add TWS+ codec to DevUI support  [pramod kotreshappa]
7ddab604  BT: Adding aptX-Adaptive codec entry to Framework  [Gurpreet Ghai]
3511ebd  Add BluetoothQualityReport class(1/2)  [Mingbo Zhang]

project hardware/google/pixel/
2a8b589  pixel: theme_set: Use dark splash unconditionally  [Paul Keith]

project packages/apps/Settings/
f7178f5  A2dpSrc: Bluetooth codec Dev-UI support for QVA codecs  [Satheesh Kumar Pallemoni]
7a6c634  bluetooth: update SavedBluetoothTwsDeviceUpdater for superclass ctor signature change  [Steven Laver]
594ac09  Implement abstract method getPreferenceKey in SavedBluetoothTwsDeviceUpdater  [Justin DeMartino]
941dd0d  BT: Use translated a2dp codec strings  [dianlujitao]
683fd8d  A2dpSrc: DEV-UI support for Blutooth Audio codec.  [Satheesh Kumar Pallemoni]
e320a8b  Bluetooth-TWS: UI updates based on Filter matched  [zhenchao]
51b1283  Bluetooth-TWS: UI updates based on profile connection.  [Kiran Kelageri]
bb7abee  Fix build error  [Jiyong Park]
7092980  Bluetooth-TWS: Filter TWS devices  [Kiran Kelageri]
6372a3a  Bluetooth: Create new catogory for earbuds  [Kiran Kelageri]

project system/timezone/
16a8d2a  RESTRICT AUTOMERGE Update Android from 2020c to 2020d [R]  [Neil Fuller]
927672e  RESTRICT AUTOMERGE Update Android from 2020b to 2020c [R]  [Neil Fuller]
5c9bf9b  RESTRICT AUTOMERGE Update Android from 2020a to 2020b [R]  [Neil Fuller]

project vendor/lineage/
f85f7e8  config: Setup soong namespaces for TARGET_USE_QTI_BT_STACK  [Pig]

====================
     2020-12-26    
====================

project device/xiaomi/markw/
b1d4bf2  markw: Update & switch IMS Stack from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
cb5687d  markw: sepolicy: Address more denials  [ZeeLog]
456a380  markw: Import missing Media blobs from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
78f3d2b  markw: Build android.hardware.health@2.1-impl.recovery package  [ZeeLog]
2c034b8  markw: Only include bitness of hal impls that is used.  [Steven Moreland]
e1c2ac4  markw: light: Add missing hidl_default flag  [ShihabZzz]
dc3607d  markw: Add vintf fragments for specific HALs  [ZeeLog]
b31c2da  markw: Append vendor prefix to qcamerasvr service name  [ZeeLog]

project lineage/hudson/
d28011c  Revert "Drop kuntao"  [Michael Bestas]

project packages/apps/Eleven/
4e9dac3  Eleven: Set targetSdkVersion to 29  [Michael Bestas]

project packages/apps/Snap/
a3fddbc  {Capture,MultiCamera}UI: Match video stop icon to API1 mode  [Paul Keith]

