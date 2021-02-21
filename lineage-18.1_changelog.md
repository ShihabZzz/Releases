====================
     2021-02-21    
====================

project bootable/recovery/
f5a0533  recovery: Add logcat to deps  [Michael Bestas]

project build/make/
3f6b888  build: Remove some debugging props  [Henrique Silva]
a6c14aa  Use 'release-keys' for build tag  [Sultanxda]

project frameworks/av/
6302b32  CCodec: workaround for frame drops  [Wonsik Kim]
ff859f5  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
3e59054  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
7b9098c  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
4ae5b93  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
bfa8629  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
e275313  OMX AAC decode don't support getting DRC parameters  [Chuangjie Xia]
ff17aba  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
5b8399f  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
25048cc  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
b58bdb7  MediaCodec: clean up resources pending removal at init  [Wonsik Kim]
c51d311  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
4fa82d9  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
e8c27a2  CCodec: add to check pipelineFull() in feedInputBufferIfAvailableInternal()  [Taehwan Kim]
4f287f6  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
33ca9cd  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]

project frameworks/base/
59c1d63  DataSwitchTile: dont show toast on click  [micky387]
9c39f05  DataSwitchTile: collapse notification panel onClick  [DennySPB]
7349a84  SystemUI: Introduce DataSwitchTile  [Christian Oder]
711bd5a  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
8cd995c  Restore one-click to add/remove tiles after r19 merge  [ezio84]
8dc8b78  SystemUI: Remove build version from qs footer  [Pranav Vashi]
9dcff44  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
3a4b030  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
9e90245  base: Add metric for Blinx Settings  [David Trpchevski]
f1eadbf  SystemUI: Add a tile to show power menu  [DarkJoker360]
d065214  Avoid MotionEvent no finish raise unnecessary ANR  [dingxiaobo]
0823c04  SystemUI: always show screenshot tile in power menu  [Joey]
eab4371  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
c04e22bd  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
bb8e79c  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
37eb0fd  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
9cdd720  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
b961f12  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
307cb89  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
4463a7b  SystemUI: Remove unused resources  [Michael Bestas]
0267e28  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
ce12e94  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
80c2e02  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
dbd9bee  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
271c8fc  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
eac3b0b  LockIcon: refresh icon on overlay changes  [Dil3mm4]
bf23496  Properly set fonts and icons on keyguard when changing styles  [ezio84]
3a94306  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
c7f93a8  screenrec: Show dialog on bottom  [El Dainosor]
bacd5e9  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
cb66b1b  PowerProfile: allow overriding default power profile  [Alexander Martinz]
d95489a  power: Re-introduce custom charging sounds  [Bruno Martins]
abb35e2  incremental: Fix more clang-tidy warnings  [Luca Stefani]
150189a  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
ddcf4fc  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/native/
f4e9a00  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]

project frameworks/opt/net/wifi/
5ffadd2  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
86501bd  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
d20b5eb  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
9c2da9f  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
e6864cf  Fix imsi info error when insert some china operator card.  [qiongz]
dee30d6  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
40b2483  Fix to block sim selection popup for data  [Susheel Nyamala]
469f059  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
c76940a  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
c8fe491  Enable vendor Telephony plugin  [Sneh Bansal]
17a4dd6  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
1c11805  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
da8a3d6  Set default value for pressure sensor  [Hsin-Yi Chen]
bee8e1d  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
5f36532  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
0518a76  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
3c7f040  sdk: Add power button qs tile metric  [DarkJoker360]
c39fa95  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project packages/apps/Dialer/
433fc93  Enable call recording for Bangladesh  [ShihabZzz]
e248cea  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
54082ce  Dialer: Remove unused resources  [Michael Bestas]
e1cbeb8  Fix selecting phone account dialog show error.  [Grace Jia]
ef67a00  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
436d696  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
ba9fc8d  Messaging: Remove unused resources  [Michael Bestas]
9248c3b  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
9f79b0d  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
bd4d1c9  Fix crash on "Connection preferences"  [Hugh Chen]
e607478  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
0d77056  Snap: Fix SD card visibility for secondary users  [Arne Coucheron]
8eade45  Snap: Save SDCard photos to legacy path  [Kevin F. Haggerty]
8e107e3  Revert "Snap: Remove saving to sdcard"  [Arne Coucheron]

project packages/apps/Stk/
ee233ea  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
e8d2696  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]
616b4aa  Remove unused translation  [Michael Bestas]

project packages/apps/Updater/
77437dc  Update Changelog server URL  [ShihabZzz]
92ddbaf  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
f66f6cb  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project system/core/
7139a19  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
bca07d2  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
3c3ee39  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
c1e7b25  logcat: Mark as recovery_available  [Michael Bestas]
8a61aa0  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
39f04b4  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]

project system/vold/
a4d619e  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]

project vendor/lineage/
7cee90e  config: Don't build Terminal  [Luca Stefani]
2f3972a  overlay: Override config for platform number verification  [Sneh Bansal]
496f9ca  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
a978cb8  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
df97cdc  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/interfaces/
e73acb1  interfaces: Introduce vendor.qti.hardware.audiohalext@1.0 HAL  [Alexander Koskovich]

project vendor/qcom/opensource/power/
b495f20  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-02-20    
====================

project device/xiaomi/markw/
9c7eeba  markw: Add permissions for CNE app  [ZeeLog]
ed4becb  markw: biometrics: use pragma once directive  [ZeeLog]

project vendor/xiaomi/
b82b6fa  markw: Add permissions for CNE app  [ZeeLog]

====================
     2021-02-19    
====================

project device/xiaomi/markw/
f64a7c7  markw: Update C++/Java code format  [ShihabZzz]
6dce87e  markw: sepolicy: Silence gmscore log spam  [ShihabZzz]
5cb3118  markw: Update audio configs/prop  [ShihabZzz]

project lineage/mirror/
14be6cd  Updated aosp-minimal to 18-Feb-2021 13:01 UTC  [Tim Schumacher]

project vendor/lineage/
f16993e  backuptool: Correct supported partitions for addon.d v3  [Alessandro Astone]

====================
     2021-02-18    
====================

project bootable/recovery/
fd1fbeb  updater: Do not null terminate mount_flags_list array  [Alessandro Astone]

project lineage/mirror/
ad18097  Updated aosp-minimal to 17-Feb-2021 13:01 UTC  [Tim Schumacher]

project vendor/lineage/
b9aa311  kernel: Support pixel style vendor_boot modules  [Alessandro Astone]

====================
     2021-02-17    
====================

project device/xiaomi/markw/
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

project frameworks/base/
b213dbd  SystemUI: Fix shutter sound  [Michael W]
24463ec  SystemUI: Screenshots: Refactor shutter sound logic  [Michael W]
e281e53  SystemUI: Handle cases that we can't address within FODCircleView  [Dil3mm4]

project hardware/lineage/livedisplay/
3e29877  livedisplay: Remove SDM-backended AdaptiveBacklight implementation  [dianlujitao]
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

project lineage/wiki/
2e96479  wiki: Mark remaining 16.0 devices discontinued  [razorloves]
0f3bc07  Lineage is finally legal!  [Nolen Johnson]

project vendor/xiaomi/
41a7c45  markw: Patch libmmcamera2_stats_modules.so  [ShihabZzz]
5e88152  markw: Patch gx_fpd to satisfy VNDK  [ShihabZzz]
9b9885c  markw: Update perf blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
e3a55d4  markw: add a vendor copy of com.qualcomm.qti.wifidisplayhal@1.0.so  [CrisBalGreece]
0b43e17  markw: goodix: Drop libunwind & libbacktrace deps  [ZeeLog]

====================
     2021-02-16    
====================

project build/make/
e661b59  releasetools: support reading release keys out of some sort of command  [Tom Powell]

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
ca2d616  Recorder: Use AAC instead of OPUS for recording  [Arne Coucheron]
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

project vendor/qcom/opensource/interfaces/
a7d6842  Add reversed perf HAL interfaces  [dianlujitao]

====================
     2021-02-09    
====================

project lineage/mirror/
e422c3f  Updated to 08-Feb-2021 20:50 UTC  [Kevin F. Haggerty]

project packages/apps/Snap/
3abede0  SnapCam: Fix thumbnail not update  [junjiez]

project packages/providers/MediaProvider/
b9e7c79  MediaProvider: Fix insert fail while file saved in sdcard  [Wang Haijun]

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

