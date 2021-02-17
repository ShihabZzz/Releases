====================
     2021-02-17    
====================

project bootable/recovery/
695849a  recovery: Add logcat to deps  [Michael Bestas]

project build/make/
62751ba  build: Remove some debugging props  [Henrique Silva]
a2191d2  Use 'release-keys' for build tag  [Sultanxda]
e661b59  releasetools: support reading release keys out of some sort of command  [Tom Powell]

project device/xiaomi/markw/
176fd31  markw: Update audio configs & sepolicy rules  [ShihabZzz]
447ff11  markw: libcamshim: Compile out 32bit lib only  [ZeeLog]
bbe218b  markw: Patch libmmcamera2_stats_modules.so  [ShihabZzz]
c777a14  markw: make shims for libmmcamera2_stats_modules.so  [Lucchetto]
1cace83  markw: Patch gx_fpd to satisfy VNDK  [ShihabZzz]
0e7a69c  markw: sepolicy: Update, cleanup & refactor  [ZeeLog]
57c9faf  markw: biometrics: Start threadpool on vndbinder  [Nich]
b781390  markw: Update perf blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
338df8f  markw: snap: Disable unsupported image stabilization feature  [ShihabZzz]
0523931  markw: snap: Exclude unsupported HFR features  [ZeeLog]
6ba1cbe  markw: overlay: Exclude Snap overlays from RRO  [Quallenauge]
e275af9  markw: Drop no longer needed sepolicy rules  [ZeeLog]
a9caffa  markw: Update packages for WFD  [ZeeLog]
66dc906  markw: Build vendor variant of vendor.display.config@1.0  [ZeeLog]
ac03669  markw: Build libqdMetaData system variant  [ZeeLog]
f21500b  markw: add a vendor copy of com.qualcomm.qti.wifidisplayhal@1.0.so  [CrisBalGreece]
78e465a  markw: goodix: drop libunwind & libbacktrace deps  [ZeeLog]
8882350  markw: Build libavservices_minijail vendor variant  [ZeeLog]

project frameworks/av/
e7ef04b  CCodec: workaround for frame drops  [Wonsik Kim]
d718479  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
1ee4518  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
02cdafb  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
766f3b7  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
7f61f25  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
cbff46d  OMX AAC decode don't support getting DRC parameters  [Chuangjie Xia]
1304a4c  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
31b97da  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
ef205ca  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
15d5a78  MediaCodec: clean up resources pending removal at init  [Wonsik Kim]
35e53d4  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
5e14649  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
b154860  CCodec: add to check pipelineFull() in feedInputBufferIfAvailableInternal()  [Taehwan Kim]
b5c6ad1  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
1b83040  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]

project frameworks/base/
0d9fe02  DataSwitchTile: dont show toast on click  [micky387]
1639e46  DataSwitchTile: collapse notification panel onClick  [DennySPB]
dd9421f  SystemUI: Introduce DataSwitchTile  [Christian Oder]
b480596  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
1b10260  Restore one-click to add/remove tiles after r19 merge  [ezio84]
3b2ac66  SystemUI: Remove build version from qs footer  [Pranav Vashi]
93623be  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
1070c33  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
1db1c7c  base: Add metric for Blinx Settings  [David Trpchevski]
5d15629  SystemUI: Add a tile to show power menu  [DarkJoker360]
f9a735c  Avoid MotionEvent no finish raise unnecessary ANR  [dingxiaobo]
48e8ac2  SystemUI: always show screenshot tile in power menu  [Joey]
edca09b  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
0d7f09f  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
449474a  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
8ce9c4b  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
86486b0  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
896ba62  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
3322ee7  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
3115f2f  SystemUI: Remove unused resources  [Michael Bestas]
75009ca  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
1456c5c  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
ac76e6d  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
ce96140  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
39b1404  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
0e5be71  LockIcon: refresh icon on overlay changes  [Dil3mm4]
edb5ca7  Properly set fonts and icons on keyguard when changing styles  [ezio84]
d853fd2  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
c21cea1  screenrec: Show dialog on bottom  [El Dainosor]
1b86e64  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
4072c1b  PowerProfile: allow overriding default power profile  [Alexander Martinz]
4107102  power: Re-introduce custom charging sounds  [Bruno Martins]
2af5b63  incremental: Fix more clang-tidy warnings  [Luca Stefani]
e8d60cd  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
ea1edbf  IncrementalService: Fix clang-tidy warning  [Luca Stefani]
b213dbd  SystemUI: Fix shutter sound  [Michael W]
24463ec  SystemUI: Screenshots: Refactor shutter sound logic  [Michael W]
e281e53  SystemUI: Handle cases that we can't address within FODCircleView  [Dil3mm4]

project frameworks/native/
45df5a4  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]

project frameworks/opt/net/wifi/
f28036e  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
2103ea5  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
74a58b9  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
c9469e1  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
0d396c7  Fix imsi info error when insert some china operator card.  [qiongz]
6556ef6  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
021fa72  Fix to block sim selection popup for data  [Susheel Nyamala]
23fb392  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
f84b201  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
d0333c4  Enable vendor Telephony plugin  [Sneh Bansal]
b8ffd4b  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
afe7039  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
1c446f5  Set default value for pressure sensor  [Hsin-Yi Chen]
cd49a00  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
7d21561  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
47fdeed  livedisplay: Initial conversion to aidl  [Pig]

project hardware/lineage/livedisplay/
7910c33  livedisplay: Move away from usage of ro.vendor.display.foss  [Nolen Johnson]

project kernel/xiaomi/markw/
6986891  Redux: 2.02  [ShihabZzz]
006c2f5  markw: dtsi: Remove venus memory allocation  [ShihabZzz]
22a685b  ASoC: msm: kill logspam when voip sessions is active  [Ryan Andri]
8469221  arch/dts: markw: Enable ULPS & phy-poweroff for panels  [ShihabZzz]
a3e7a6a  markw: Rewrite audio driver from Mi OpenSource  [ShihabZzz]
f975145  Revert "sound: soc: Remove HDMI codecs dependencies from MSM8X16"  [ShihabZzz]
b5beb15  Revert "arch: markw_defconfig: Disable HDMI support"  [ShihabZzz]
a7a7232  Revert "arch/arm: dts: qcom: Fix wheezing and increased stability"  [ShihabZzz]
e361b19  Init Redux 2.0  [ShihabZzz]
78dbd5ca  net: wireguard: Patching > Merging  [ShihabZzz]
5005d79  arch/markw_defconfig: Enable WIREGUARD  [ShihabZzz]
07e10a4  drivers: Silence debugfs failing log spam  [ShihabZzz]
a2c3f10  rcu: boost: avoid preemption before calling complete()  [John Dias]
d2e87ee  BACKPORT: qseecom: Use scm_call2 when bus_scaling is enabled  [AnilKumar Chimata]
15ea317  BACKPORT: qseecom: Remove virtual address print  [Monika Singh]
80ffe05  drivers: input: touchscreen: Create keydisabler nodes  [GuaiYiHu]
2d74a45  arm:dts: msm8953: Add clock-frequency property  [Remicaa]
03772b0  thermal: Do not log an error if thermal_zone_get_temp returns -EAGAIN  [Hans de Goede]
e34ebd2  msm_thermal: initialize later than arch drivers  [Park Ju Hyung]
98699f6  msm: ipa: update msm_ipa.h with latest IPA versions constants  [Ghanim Fodi]
0fa8a15  Init Redux !!!  [ShihabZzz]

project lineage-sdk/
505d9e2  sdk: Add power button qs tile metric  [DarkJoker360]
0e86292  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/wiki/
2e96479  wiki: Mark remaining 16.0 devices discontinued  [razorloves]
0f3bc07  Lineage is finally legal!  [Nolen Johnson]

project packages/apps/Dialer/
889664a  Enable call recording for Bangladesh  [ShihabZzz]
e300c3a  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
9220fa8  Dialer: Remove unused resources  [Michael Bestas]
1bfade6  Fix selecting phone account dialog show error.  [Grace Jia]
3f101c2  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
5fbf541  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
b78d009  Messaging: Remove unused resources  [Michael Bestas]
3923e25  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
30087db  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
87760e4  Fix crash on "Connection preferences"  [Hugh Chen]
1827cf0  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
89f2ea9  Snap: Fix SD card visibility for secondary users  [Arne Coucheron]
fefac31  Snap: Save SDCard photos to legacy path  [Kevin F. Haggerty]
4e2f37e  Revert "Snap: Remove saving to sdcard"  [Arne Coucheron]

project packages/apps/Stk/
28fb064  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
d1149f4  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]
9740ebb  Remove unused translation  [Michael Bestas]

project packages/apps/Updater/
2483dd7  Update Changelog server URL  [ShihabZzz]
8ef094a  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
9634637  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project system/core/
51da6a8  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
a97b106  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
1e39e46  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
a23be13  logcat: Mark as recovery_available  [Michael Bestas]
e9cd3dd  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
bbf8a09  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]

project system/vold/
0a1a037  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]

project vendor/lineage/
cbcc4d8  config: Don't build Terminal  [Luca Stefani]
dad3668  overlay: Override config for platform number verification  [Sneh Bansal]
e400bc4  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
5d03ba3  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
b953311  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/interfaces/
ac7563d  interfaces: Introduce vendor.qti.hardware.audiohalext@1.0 HAL  [Alexander Koskovich]

project vendor/qcom/opensource/power/
e7715a5  power: Kill "Failed to acquire lock" log  [Luca Stefani]

project vendor/xiaomi/
41a7c45  markw: Patch libmmcamera2_stats_modules.so  [ShihabZzz]
5e88152  markw: Patch gx_fpd to satisfy VNDK  [ShihabZzz]
9b9885c  markw: Update perf blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
e3a55d4  markw: add a vendor copy of com.qualcomm.qti.wifidisplayhal@1.0.so  [CrisBalGreece]
0b43e17  markw: goodix: Drop libunwind & libbacktrace deps  [ZeeLog]

====================
     2021-02-16    
====================

project device/xiaomi/markw/
07d198e  markw: Switch to actual VNDK support  [ZeeLog]
7fb43a9  markw: Add missing IMS blob  [ZeeLog]
3dcb44a  markw: Move legacy thermal blob to different section  [ZeeLog]
27317ed  markw: camera: QCamera2: HAL3: Fix fdleak issue  [Ankur Maheshwari]
9e02cf9  markw: Add libnbaio to PRODUCT_PACKAGES  [Sujin Panicker]

project kernel/xiaomi/markw/
a884d16  Quark: 1.21  [ShihabZzz]
299468c  Merge tag 'LA.UM.8.6.c26-02400-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into lineage-17.1  [ShihabZzz]

project lineage/hudson/
010927c  Add experimental build targets  [Tom Powell]
d1e170c  Drop 16.0  [Tom Powell]

project lineage/mirror/
37588b4  Updated aosp-minimal to 15-Feb-2021 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
d6837c0  wiki: Restore note for LG recovery boot  [Alessandro Astone]
0ed921b  Revert "d803: Bring instructions up to date with other g2 variants"  [Alessandro Astone]

project vendor/xiaomi/
d612712  markw: Switch to actual VNDK support  [ZeeLog]
d468a5a  markw: Add missing IMS blob  [ZeeLog]

====================
     2021-02-15    
====================

project device/xiaomi/markw/
30f718d  markw: Patch camera & fingerprint blobs  [ShihabZzz]

project lineage/hudson/
0472bf3  hudson: Promote ls990 to 17.1  [Aleksander Gencel]

project lineage/wiki/
62b3dc7  wiki: Promote ls990 to 17.1  [Aleksander Gencel]

project packages/apps/Snap/
97755cb  Revert "Snap: Let mediaprovider add entry for newly taken photos"  [Arne Coucheron]

project vendor/xiaomi/
293c629  markw: Patch camera & fingerprint blobs  [ShihabZzz]

====================
     2021-02-14    
====================

project device/xiaomi/markw/
23c90bd  markw: audio: set default IIR volume to 53 for internal codec  [Rohit kumar]
d3c5d22  markw: audio: add support for bt_sco and wsa-speaker combo device.  [kunleiz]
ddc4f2b  markw: audio: Add compress-offload-playback2 for BT SCO WB  [pavanc]
2f342a4  markw: Move dpm feature prop to system ext  [ShihabZzz]
1ba1f51  markw: Move zygote preforking prop to system  [ShihabZzz]
95c2702  markw: Cleanup/Update layers  [ShihabZzz]
6a51a12  markw: Update audio configs/prop from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]

project lineage/wiki/
9c7c8d4  d803: Bring instructions up to date with other g2 variants  [Alessandro Astone]

project packages/apps/Recorder/
ca2d616  Recorder: Use AAC instead of OPUS for recording  [Arne Coucheron]

====================
     2021-02-13    
====================
project android/
b976fac  Call time on Terminal and libvterm.  [Elliott Hughes]

project frameworks/base/
e44a64e  Fix: "Clear All" recent app screen loop bug  [vincent.cw_lee]

project lineage/mirror/
cb4de66  Updated to 12-Feb-2021 16:20 UTC  [Kevin F. Haggerty]

project packages/apps/Recorder/
3661dd2  Recorder: Bring back original wav recording as an option  [2bllw8]
4ffa2a1  Recorder: Move list actions to popup menu  [joey]
0eaf975  Recorder: Add configuration for high quality  [2bllw8]
258639f  Recorder: Recording list: Don't slide in and out  [Michael W]
d538764  Recorder: Add feature to pause / resume recording  [2bllw8]
fa2c748  Recorder: Rewrite sound recording service  [2bllw8]
22145eb  Recorder: Add feature to rename recordings  [2bllw8]
45dc4d2  Recorder: Do not show double popup when asking to delete a record  [2bllw8]
498d990  Recorder: Show empty view when removing last item  [Michael W]
eb39a6d  Recorder: Add view of all my records  [2bllw8]
b3502b4  Recorder: Add support for tagging records with location name  [Joey]

====================
     2021-02-12    
====================

project external/chromium-webview/
c7ee4db  Chomium Webview repository administrative note  [Kevin F. Haggerty]

project lineage/mirror/
69f0de0  Updated aosp-minimal to 11-Feb-2021 13:01 UTC  [Tim Schumacher]

====================
     2021-02-11    
====================

project lineage/hudson/
8e8f7bc  hudson: Introduce the Motorola Edge  [Joshua Blanchard]

project lineage/mirror/
c2d4c98  Updated aosp-minimal to 10-Feb-2021 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
f706719  wiki: Add Motorola Edge (racer)  [Joshua Blanchard]

====================
     2021-02-10    
====================

project packages/apps/Snap/
3abede0  SnapCam: Fix thumbnail not update  [junjiez]

project packages/providers/MediaProvider/
b9e7c79  MediaProvider: Fix insert fail while file saved in sdcard  [Wang Haijun]

project vendor/qcom/opensource/interfaces/
a7d6842  Add reversed perf HAL interfaces  [dianlujitao]

====================
     2021-02-09    
====================

project lineage/mirror/
e422c3f  Updated to 08-Feb-2021 20:50 UTC  [Kevin F. Haggerty]

project system/core/
f29ed7d  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

====================
     2021-02-08    
====================

project packages/apps/Recorder/
1a93628  Recorder: Add new wave recording animation  [2bllw8]

project vendor/lineage/
c63fa84  backuptool: Support seamless backup and restore to extra partitions  [Alessandro Astone]
6245873  backuptool_ab: Make tmp actually tmpfs  [Alessandro Astone]

====================
     2021-02-07    
====================

project frameworks/av/
da85637  Merge tag 'android-11.0.0_r29' of https://android.googlesource.com/platform/frameworks/av into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/base/
d7c3493  Merge tag 'android-11.0.0_r29' of https://android.googlesource.com/platform/frameworks/base into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/apps/Recorder/
98a88f7  Recorder: Update gradle and dependencies  [2bllw8]
b754a21  Recorder: Actually display share notification  [Michael W]
1b9e34c  Recorder: Fix sharing  [Michael W]
d2da700  Recorder: Remove screen recorder  [Michael W]

====================
     2021-02-06    
====================

project external/cldr/
8fe1f2d  DO NOT MERGE Cherry-pick CLDR-14434: Update Android CLDR tzdata from 2020f to 2021a. [R]  [Almaz Mingaleev]

project external/icu/
a21a549  DO NOT MERGE Update Android ICU tzdata from 2020f to 2021a. [R]  [Almaz Mingaleev]

project frameworks/base/
1a41725  No need to 'addChild' when start 'FLAG_ACTIVITY_CLEAR_TOP' Activity.  [yangyankai1]
73c1924  Fix a bug in the USAP Pool refill logic.  [Chris Wailes]

project kernel/xiaomi/markw/
c19ed72  Quark: 1.20  [ShihabZzz]
3fc2f02  Merge tag 'ASB-2021-02-05_3.18'  [ShihabZzz]
862026b  Revert "net: Remove dst_cache support"  [ShihabZzz]

project system/timezone/
473d22b  DO NOT MERGE Update Android TZDB from 2020f to 2021a. [R]  [Almaz Mingaleev]

====================
     2021-02-05    
====================
project android/
2572a5b  manifest: android-11.0.0_r27 -> android-11.0.0_r29  [Kevin F. Haggerty]

project build/make/
0e7a236  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/base/
ea71eff  Partially revert "Wake up to lock screen when bouncer is visible"  [Sultan Alsawaf]
bf766d5  PhoneWindowManager: Only react to camera key when necessary  [Michael W]

project frameworks/native/
f1201c6  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project lineage/scripts/
6c01311  Update default webview to 88.0.4324.152  [Kevin F. Haggerty]

project packages/apps/Bluetooth/
cc597b3  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/apps/Settings/
513e45d  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/apps/SetupWizard/
2b90a7f  SetupWizard: Add device specific hook page  [Michael W]

project packages/providers/ContactsProvider/
755039c  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project system/core/
a231505  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project vendor/qcom/opensource/commonsys/packages/apps/Bluetooth/
9a8c62b  Check permission before sending batch scan result  [Jakub Pawlowski]
3e5a7fa  Check if advertiserId value matches valid advertiser  [Jakub Pawlowski]

====================
     2021-02-04    
====================

project lineage/mirror/
e116655  Updated aosp-minimal to 03-Feb-2021 13:01 UTC  [Tim Schumacher]

project system/core/
e8dcaba  fs_mgr: Allow remounts with Magisk installed  [Bruno Martins]
79f606e  liblog: Always report as debuggable when building userdebug/eng  [Bruno Martins]

project vendor/lineage/
2263d4b  fixup! Dialer: Add visual voicemail configs from Google Dialer  [Eamon Powell]
04bbc65  Dialer: Add visual voicemail configs from Google Dialer  [Danny Lin]

