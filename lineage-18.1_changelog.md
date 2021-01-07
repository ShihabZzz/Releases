====================
     2021-01-07    
====================
project android/
869041b  manifest: Track our forked hardware/google/pixel  [Peter Cai]
c1c7802  manifest: android-11.0.0_r19 -> android-11.0.0_r27  [Michael Bestas]

project build/make/
29906ae  build: Remove some debugging props  [Henrique Silva]
eca617b  Use 'release-keys' for build tag  [Sultanxda]

project frameworks/base/
9f9f396  DataSwitchTile: dont show toast on click  [micky387]
a3b208c  DataSwitchTile: collapse notification panel onClick  [DennySPB]
4b149a2  SystemUI: Introduce DataSwitchTile  [Christian Oder]
26c4f6a  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
781ceed  Restore one-click to add/remove tiles after r19 merge  [ezio84]
d8053f1  SystemUI: Remove build version from qs footer  [Pranav Vashi]
dc71945  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
390c565  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
91c4ab8  base: Add metric for Blinx Settings  [David Trpchevski]
a88c18d  SystemUI: Add a tile to show power menu  [DarkJoker360]
0c3c278  SystemUI: Remove unused resources  [Michael Bestas]
523cd11  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
c80d748  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
fb9c202  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
7a4b9fc  LockIcon: refresh icon on overlay changes  [Dil3mm4]
3799e02  Properly set fonts and icons on keyguard when changing styles  [ezio84]
8ff4351  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
a43c7d7  screenrec: Show dialog on bottom  [El Dainosor]
67e9bbb  SystemUI: Use AVCProfileMain for screen recorder  [Arne Coucheron]
811f566  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
fa83bf3  PowerProfile: allow overriding default power profile  [Alexander Martinz]
6419101  power: Re-introduce custom charging sounds  [Bruno Martins]
723967c  incremental: Fix more clang-tidy warnings  [Luca Stefani]
15b5f03  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
aca426e  IncrementalService: Fix clang-tidy warning  [Luca Stefani]
b4296af  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project frameworks/opt/telephony/
4aba88b  RIL: Fix manual network selection with old modem  [faust93]
6512132  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
bff1893  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
509bcd8  Fix imsi info error when insert some china operator card.  [qiongz]
3fd1fa6  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
20e45c6  Fix to block sim selection popup for data  [Susheel Nyamala]
a0ed9d7  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
5dc874e  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
4f6873d  Enable vendor Telephony plugin  [Sneh Bansal]
357353d  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
55ebb8e  wifi: Add support for Dual Station combination.  [Khanjan Desai]
60af4ad  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]
c95f73c  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
6a3a8c6  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
311c7f8  livedisplay: Initial conversion to aidl  [Pig]
4f96e3f  trust: set system vintf fragment xml to framework  [Michael Benedict]

project lineage-sdk/
ae9ac8c  sdk: Add power button qs tile metric  [DarkJoker360]
b5c498b  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/crowdin/
b65c024  Initial setup for lineage-18.1 translations  [Michael Bestas]

project lineage/hudson/
69758ef  hudson: add Asus Zenfone 5Z (ZS620KL)  [Marc Bourgoin]

project lineage/scripts/
f07e158  aosp-merger: Get branch reliably  [Chirayu Desai]

project lineage/wiki/
71a95c6  wiki: Add Asus Zenfone 5Z (Z01R)  [rohan]

project packages/apps/Dialer/
9f5c360  Dialer: Remove unused resources  [Michael Bestas]
872ca6f  Fix selecting phone account dialog show error.  [Grace Jia]
3cb73bb  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
75f00bc  LineageParts: Tweak default charging sound path  [Han Wang]
5f25790  LineageParts: update preference category title text color  [Timi]

project packages/apps/Messaging/
1d0fbab  Messaging: Remove unused resources  [Michael Bestas]
d847321  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
d93d3a0  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
2f0c578  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
eff0ceb  Snap: Remove warnings for generated ids  [Michael W]
c94c662  Snap: there is no camera icon shown if have no camera in first boot up  [zhang sanshan]

project packages/apps/Stk/
c9b3771  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
4f13ef7  Remove unused translation  [Michael Bestas]
94afb12  Revert "Trebuchet: Add extra privapp permissions xml"  [Michael Bestas]

project packages/apps/Updater/
b4db809  Update Changelog server URL  [ShihabZzz]
e2b453d  Unofficial OTA configuration  [David Trpchevski]

project system/core/
f57aa02  logcat: Mark as recovery_available  [Michael Bestas]
0d5a05c  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
b4a6803  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
64fb25b  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

project system/vold/
eede996  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
e5fbca0  Fix the group permissions of the sdcard root.  [Jani Lusikka]
a6e294f  vold ext4/f2fs: do not use dirsync if we're mounting adopted storage  [Sam Mortimer]
1d5e221  vold: Mount ext4/f2fs portable storage with sdcard_posix  [Jani Lusikka]
137b098  vold: Honor mount options for ext4/f2fs partitions  [Tom Marshall]
951ef15  vold: Support internal storage partitions  [Tom Marshall]
1118e67  vold: Fix fsck on public volumes  [Michael Bestas]
45adc72  vold: add support for more filesystems for public storage  [Dan Pasanen]

project vendor/lineage/
8998f1e  backuptool: Support seamless backup and restore to extra partitions  [Alessandro Astone]
d46f1d1  backuptool_ab: Make tmp actually tmpfs  [Alessandro Astone]
839f485  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
1d779a7  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
42bbdfe  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
1c12acf  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-01-06    
====================
project android/
5ae2bba  manifest: Sync QTI bootctrl HAL  [LuK1337]

project device/lineage/sepolicy/
0ee6bd8  lineage: Suppress bash related ioctl denials  [Bruno Martins]
811e656  qcom: gmscore_app: suppress denials on firmware  [Adam Shih]

project frameworks/base/
b0d54ee  SystemUI: add FloatingRotationButton for hw-key devices  [Michal Pražák]

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

project build/make/
c5362f0  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project development/
c140a31  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

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

project external/gptfdisk/
60f8818  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project frameworks/av/
ea00c9f  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project frameworks/base/
364462f  camera: Support exposing aux camera to apps  [Sauhard Pande]

project frameworks/native/
144dd1e  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project hardware/lineage/interfaces/
742a534  trust: Include VINTF fragments  [Michael Bestas]

project packages/apps/DocumentsUI/
532d2bd  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project system/bt/
c1f9733  Merge tag 'android-11.0.0_r27' into staging/lineage-18.1_merge-android-11.0.0_r27  [Michael Bestas]

project vendor/lineage/
64b5b1c  partner_gms: Simplify if/else if logic  [Ethan Chen]

project vendor/xiaomi/
06c31ee  markw: Place a copy of thermal.msm8953.so  [ShihabZzz]

====================
     2021-01-04    
====================

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

project lineage-sdk/
54d862c  SystemUI: NetworkTraffic: Refactor message handling  [Michael W]

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

project lineage/mirror/
c07fe56  Updated lineage-minimal to 30-Dec-2020 13:01 UTC  [Tim Schumacher]

project vendor/lineage/
f17c855  lineage: apns: Update T-Mobile US to reflect latest carrier changes  [Zachariah Anderson]

project vendor/xiaomi/
5c80e46  markw: Remove copyright headers from automatically generated files  [Michael Bestas]
2a03321  markw: gps: lowi.conf: lower debug level  [ZeeLog]

====================
     2020-12-29    
====================

project external/toybox/
48ba553  toybox: Restore support for toybox_static binary  [Adrian DC]

project frameworks/base/
2373904  SystemUI: Resolve faulty keyguard clock logs outputs  [Adrian DC]
a31439f  SystemUI: Fix size of icon of vibrate ringer mode for additional icon packs  [Volodymyr Zhdanov]

project lineage/hudson/
368fd5c  hudson: Promote FP3 to 17.1  [Daniel Köster]

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

project external/boringssl/
7bac33a  libcrypto: Add support for toybox_static build dependencies  [Adrian DC]

project external/chromium-webview/
c780a2e  webview: Hard no to persistent histograms  [Kevin F. Haggerty]

project lineage/mirror/
b85f1a0  Updated to 28-Dec-2020 13:00 UTC  [Tim Schumacher]

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

====================
     2020-12-25    
====================

project device/qcom/sepolicy_vndr/
2f7337d  common: Address BT denials  [Bruno Martins]

project device/xiaomi/markw/
d159198   markw: Update media configs from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]
401f72d  markw: Build LineageOS touch HAL  [ShihabZzz]

project frameworks/base/
1e19a67  UserRestrictionUtils: Return null Bundle if there are no restrictions  [Paul Keith]

project packages/apps/Camera2/
3b12532  AOSP/Camera2 - Fix bug causing edit, share, delete buttons to not appear  [Colin Marsch]
88fb7fa  AOSP/Camera2 - Remove Saving bar after taking a photo  [Colin Marsch]
bb6cde9  AOSP/Camera2 - Update Storage method to be compatible with API 29  [Colin Marsch]
269a879  Revert "Revert "Camera2: Migrate to new storage API""  [Colin Marsch]

project packages/apps/Contacts/
4496174  Contacts: Enable support for device contact.  [Toha]

project packages/apps/Snap/
d08c78d  Snap: chmod 0644  [Paul Keith]
05e1f3f  Snap: dos2unix  [Paul Keith]
600377c  CaptureModule: Only look for ssm capture results if ssm is enabled  [Paul Keith]
7c2678a  CaptureModule: Fix init sequence  [Paul Keith]

project packages/apps/Trebuchet/
2a0aa6a  Disable MULTI_DB_GRID_MIRATION_ALGO  [Michael Bestas]

project packages/providers/ContactsProvider/
78f2b52  ContactsProvider: Prevent device contact being deleted.  [Toha]

project vendor/codeaurora/telephony/
c72e95d  ims-ext-common: Forward the legacy getAutoReject call to obtain compatibility with older ims.apk  [Arian]
1fae6d5  Revert "IMS: Remove API and constants related to ECT."  [Josh Chasky]

project vendor/xiaomi/
c7fe9b1  markw: Update & switch IMS Stack from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
4551546  markw: Import missing Media blobs from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]

