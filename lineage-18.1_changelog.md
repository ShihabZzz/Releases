====================
     2021-03-07    
====================
project android/
8600f94  Call time on Terminal and libvterm.  [Elliott Hughes]

project bootable/recovery/
ccc2a41  recovery: Add logcat to deps  [Michael Bestas]

project build/make/
bb05e11  build: Remove some debugging props  [Henrique Silva]
d4892bf  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
4c7ce63  markw: Update ANT+/BT blobs from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]
dc98618  markw: sepolicy: Shush! spam...  [ShihabZzz]
2584309  markw: overlay: enable config_sf_limitedAlpha  [srfarias]

project frameworks/av/
b4ff836  CCodec: workaround for frame drops  [Wonsik Kim]
97bef79  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
d0b552a  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
3a6d6ba  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
7164056  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
d15f84c  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
ec9867a  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
cb4d9e5  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
e1c42b8  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
528a62e  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
69490cb  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
b3be1f6  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
d7d1a69  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]

project frameworks/base/
517ffd8  Kill off provider info logspam  [Harsh Shandilya]
9c1c677  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
4b0299f  core: jni: Switch to -O3  [Simão Gomes Viana]
1634236  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
a5919b8  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
2936329  telephony: URI cannot be created with negative subIds  [jlask]
3677d8d  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
4dcb66b  DataSwitchTile: dont show toast on click  [micky387]
9e0b93e  DataSwitchTile: collapse notification panel onClick  [DennySPB]
affafdb  SystemUI: Introduce DataSwitchTile  [Christian Oder]
1945fa0  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
b44e739  SystemUI: Remove build version from qs footer  [Pranav Vashi]
694ecae  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
d7d42d4  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
14a8d72  base: Add metric for Blinx Settings  [David Trpchevski]
443a504  SystemUI: Add a tile to show power menu  [DarkJoker360]
e5ee5d7  Revert "No need to 'addChild' when start 'FLAG_ACTIVITY_CLEAR_TOP' Activity."  [Han Wang]
86596ea  SystemUI: always show screenshot tile in power menu  [Joey]
eac6f8c  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
739c126  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
7402bda  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
980694c  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
f7970ea  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
5484ec0  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
08254e8  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
a287dfc  SystemUI: Remove unused resources  [Michael Bestas]
d2dcd19  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
c56f506  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
1cf2287  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
338001e  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
5ebb526  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
0eb1d08  LockIcon: refresh icon on overlay changes  [Dil3mm4]
503fc1b  Properly set fonts and icons on keyguard when changing styles  [ezio84]
37adc80  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
5cd7e1d  screenrec: Show dialog on bottom  [El Dainosor]
f2d6f8c1  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
53e4d9f  power: Re-introduce custom charging sounds  [Bruno Martins]
7ec86ec  incremental: Fix more clang-tidy warnings  [Luca Stefani]
2ebdb64  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
8e1e439  IncrementalService: Fix clang-tidy warning  [Luca Stefani]
e388fe7  Sharesheet: Set max ranked items to 8  [LuK1337]
d274c33  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/native/
c2f5da2  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]
8734385  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/opt/net/wifi/
bf5194c  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
2b12025  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project hardware/interfaces/
daacea8  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
d53189c  Set default value for pressure sensor  [Hsin-Yi Chen]
bbb63d1  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
c1d0ae8  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
ebb4e24  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
0bc59b8  sdk: Add power button qs tile metric  [DarkJoker360]
a7ff99c  lineage-sdk: Tweak default charging sound path again  [Han Wang]
4457a81  lineage-sdk: Fix NPE when using getPictureAdjustmentRanges()  [Han Wang]

project packages/apps/Camera2/
f04708f  Camera2: Set targetSdkVersion=29  [Michael Bestas]
033d86a  AOSP/Camera2 - Fix bug causing edit, share, delete buttons to not appear  [Colin Marsch]
11b360a  AOSP/Camera2 - Remove Saving bar after taking a photo  [Colin Marsch]
abaf769  AOSP/Camera2 - Update Storage method to be compatible with API 29  [Colin Marsch]
818a57b  Revert "Revert "Camera2: Migrate to new storage API""  [Colin Marsch]

project packages/apps/Dialer/
95dbd9e  Enable call recording for Bangladesh  [ShihabZzz]
da10d74  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
32d388b  Dialer: Remove unused resources  [Michael Bestas]
1aac57c  Fix selecting phone account dialog show error.  [Grace Jia]
40d005b  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/Eleven/
0d18b71  Eleven: Add a Material Theme and a Dark Theme  [Marcos Lopez]
cb90f7d  Eleven: declare support for ACTION_SEEK_TO  [Marcos Lopez]
85a422b  Eleven: the great cleanup  [Joey]
d356032  Eleven: Update gradle and dependencies  [Michael W]
e032b30  Eleven: Audio preview: Follow dark/light theming  [Michael W]

project packages/apps/LineageParts/
9738cfa  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
7512192  Messaging: Remove unused resources  [Michael Bestas]
f2f0ce4  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
727eb32  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]
8e6fc36  Mark messages as failed if SIM is inactive  [Taesu Lee]
2bdb62b  Fix creating a new conversation including own number  [Taesu Lee]

project packages/apps/PermissionController/
b5479e0  [DO NOT MERGE] Deep-update live datas and update on isStale in getInitializedValue  [Eugene Susla]

project packages/apps/Recorder/
54e2b4c  Recorder: support bazel build  [2bllw8]
89b2a2c  Recorder: Correct WAV header creation  [Paul Keith]
fdd111a  Recorder: draw full edge-to-edge  [2bllw8]

project packages/apps/Settings/
773eb9e  Fix crash on "Connection preferences"  [Hugh Chen]
c7041ce  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
810c2df  Snap: Fix SD card visibility for secondary users  [Arne Coucheron]
e357d6f  Snap: Save SDCard photos to legacy path  [Kevin F. Haggerty]
f4e5c00  Revert "Snap: Remove saving to sdcard"  [Arne Coucheron]

project packages/apps/Stk/
dec8681  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
4b35b98  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
99dd19c  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
7afe1c7  Update Changelog server URL  [ShihabZzz]
bdc78e3  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
edf9826  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project packages/inputmethods/LatinIME/
1106cec  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
e8bb39e  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
99119a7  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
ef87752  Remove webview from the view system before destroying webview  [lucaslin]
557eeb9  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
d4bc615  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/MediaProvider/
69109db  MediaProvider: Fix insert fail while file saved in sdcard  [Wang Haijun]

project packages/providers/TelephonyProvider/
22422fb  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]
8f278f0  Fix wrong index access in getSingleMessageFromIcc()  [Taesu Lee]
9f9142e  Support delete all the messages in SIM  [Taesu Lee]
d1dd52f  Fallback to other address type for EF_SMS  [Taesu Lee]

project system/core/
5c227b3  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
d9927a9  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
5d27c57  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
c62a5bb  logcat: Mark as recovery_available  [Michael Bestas]
3707b13  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
7a3e2f4  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
38d2a0e  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/sepolicy/
535ec32  Export ro.vendor.product.cpu.abilist*  [SzuWei Lin]
c26da05  Sepolicy for dumsys suspend_control in bugreport  [Kalesh Singh]
c31c190  Add ro.cpuvulkan.version to property_contexts  [Inseob Kim]
76efb9d  Add ro.cdma.home.operator. properties  [Inseob Kim]
6c66a71  Allow dumpstate to dump hal_light  [Roman Kiryanov]
f75a230  Allow dumpstate to get thermal and power hal debug info  [TeYuan Wang]

project system/vold/
759cc40  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
748ecf7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project tools/extract-utils/
94c7cb3  Remove support for /sbin  [Michael Bestas]

project vendor/lineage/
6a2c545  config: Don't build Terminal  [Luca Stefani]
cb8b5f4  overlay: Override config for platform number verification  [Sneh Bansal]
603237c  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
5ee1174  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
33efb90  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/interfaces/
a614a22  interfaces: Introduce vendor.qti.hardware.audiohalext@1.0 HAL  [Alexander Koskovich]

project vendor/qcom/opensource/power/
4f98de7  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-03-06    
====================

project device/lineage/sepolicy/
a5640c3  lineage: common: public: Address Motorola Health HAL denial  [Nolen Johnson]

project vendor/xiaomi/
0c3c136  markw: Update ANT+/BT blobs from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]

====================
     2021-03-05    
====================

project external/chromium-webview/
94d5734  Update Chromium Webview to 89.0.4389.72  [Kevin F. Haggerty]

====================
     2021-03-04    
====================
project android/
2914b89  manifest: android-11.0.0_r29 -> android-11.0.0_r32  [Kevin F. Haggerty]

project vendor/nxp/opensource/pn5xx/halimpl/
b5a5253  A stack OOB write vuln of nxp nfc hal library  [Alisher Alikhodjaev]

project vendor/nxp/opensource/sn100x/halimpl/
cad836e  A stack OOB write vuln of nxp nfc hal library  [Alisher Alikhodjaev]

project vendor/qcom/opensource/commonsys/packages/apps/Bluetooth/
2592b10  Prevent drawing on top of Bluetooth activities  [Jakub Pawlowski]

====================
     2021-03-03    
====================

project art/
aad295f  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project bionic/
3a00387  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project bootable/recovery/
b320ec0  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project build/make/
2f68654  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project build/soong/
72b6170  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project external/cldr/
1e4de98  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project external/icu/
9631b02  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/av/
26a64fb  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/base/
d0b4d17  BatteryService: Mod: Check against all conditions  [Ali B]
df71b93  BatteryManager: Mark battery moto mods constants as hidden  [LuK1337]

project frameworks/native/
9e07dbd  Ensure that expected present time is in the future  [Snild Dolkow]
c02140b  SF: handle long waiting Layer sync point  [KaiChieh Chuang]

project frameworks/opt/net/wifi/
5f3c73c  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/opt/timezonepicker/
b001963  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project hardware/google/pixel/
3439a86  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project hardware/interfaces/
229285d  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project hardware/knowles/athletico/sound_trigger_hal/
339f25d  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project hardware/nxp/nfc/
111aecc  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project lineage/mirror/
10ac4b5  Updated aosp-minimal to 02-Mar-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/BasicSmsReceiver/
24073c6  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Bluetooth/
4953e5b  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/CarrierConfig/
f9c56d7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/CellBroadcastReceiver/
2daf3ec  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/CertInstaller/
615fe43  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Contacts/
514d1ab  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/DocumentsUI/
27a3507  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/EmergencyInfo/
9c1ad2e  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/ManagedProvisioning/
778a6b5  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Nfc/
71a38be  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/PermissionController/
f4b38f2  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/PhoneCommon/
aa2a9c7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Settings/
5b06dc2  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/SettingsIntelligence/
b3da2c5  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/StorageManager/
6792c91  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Tag/
e2c10b7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/ThemePicker/
05efb67  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Traceur/
ee15011  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/Trebuchet/
fd3fde7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/TvSettings/
d7facce  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/apps/WallpaperPicker2/
6b89cbd  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/modules/CaptivePortalLogin/
352c5d4  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/providers/ContactsProvider/
9237c99  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/providers/DownloadProvider/
f9d9d32  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/providers/MediaProvider/
8124230  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/providers/TelephonyProvider/
2bcb7d9  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/services/BuiltInPrintService/
c8a1e5c  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/services/Telecomm/
84063bd  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/services/Telephony/
030ccd7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project packages/wallpapers/LivePicker/
c282b0b  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/bt/
464b040  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/sepolicy/
f351416  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/timezone/
4181b85  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/update_engine/
0732d12  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project vendor/qcom/opensource/commonsys-intf/display/
8c1a0d2  qdMetadata: Ignore UNUSED parameter  [cjh1249131356]

project vendor/qcom/opensource/commonsys/system/bt/
3a0ad0d  SDP: Only start discovery once  [Myles Watson]

====================
     2021-03-02    
====================

project device/qcom/sepolicy-legacy-um/
a49ec66  sepolicy: Remove poweroffalarm system uid and redundant rules  [Guixiong Wei]

project kernel/xiaomi/markw/
5cf8280  arch/dts: Restore devfreq-cpufreq modified map  [ShihabZzz]
06fcfc1  wireguard: version: 1.0.20210219  [Jason A. Donenfeld]
bafa773  wireguard: compat: zero out skb->cb before icmp  [Jason A. Donenfeld]
87795dd  wireguard: compat: skb_mark_not_on_list will be backported to Ubuntu 18.04  [Thadeu Lima de Souza Cascardo]
242c829  wireguard: queueing: get rid of per-peer ring buffers  [Jason A. Donenfeld]
a5732c5f  wireguard: device: do not generate ICMP for non-IP packets  [Jason A. Donenfeld]
9deb771  wireguard: peer: put frequently used members above cache lines  [Jason A. Donenfeld]
c29fa19  wireguard: compat: remove unused version.h headers  [Jason A. Donenfeld]
cc7dede  wireguard: compat: skb_mark_not_on_list was backported to 4.14  [Jason A. Donenfeld]
cc20fa5  wireguard: compat: SYM_FUNC_* was backported to c8s  [Jason A. Donenfeld]
dcf7bae  wireguard: socket: remove bogus __be32 annotation  [Jann Horn]
f0c8274  wireguard: global: avoid double unlikely() notation when using IS_ERR()  [Antonio Quartulli]
1b7e620  wireguard: simd: detect -rt kernels >= 5.4  [Jason A. Donenfeld]
e7cd97b  wireguard: compat: drop rhel 8.2, add rhel 8.4 support  [Jason A. Donenfeld]
42cc1a4  pinctrl: qcom: Update irq handle for GPIO pins  [Archana Sathyakumar]
a3c3353  qseecom: Added boundary checks between two subsequent fields  [Nitin LNU]
4fbb093  prima: Send assoc reject upon failing to post ASSOC_IND  [Srinivas Dasari]
d084533  dts: msm8953: Disable unhandled or broken IRQ monitoring  [kdrag0n]
704ac68  Redux: 2.02  [ShihabZzz]
d5ea481  markw: dtsi: Remove venus memory allocation  [ShihabZzz]
caa9274  ASoC: msm: kill logspam when voip sessions is active  [Ryan Andri]
f3cc41b  arch/dts: markw: Enable ULPS & phy-poweroff for panels  [ShihabZzz]
f65fb83  markw: Rewrite audio driver from Mi OpenSource  [ShihabZzz]
3160e27  Revert "sound: soc: Remove HDMI codecs dependencies from MSM8X16"  [ShihabZzz]
8430407  Revert "arch: markw_defconfig: Disable HDMI support"  [ShihabZzz]
a0587bb  Revert "arch/arm: dts: qcom: Fix wheezing and increased stability"  [ShihabZzz]
c1fff83  Init Redux 2.0  [ShihabZzz]
e341bb2  net: wireguard: Patching > Merging  [ShihabZzz]
62082ad  arch/markw_defconfig: Enable WIREGUARD  [ShihabZzz]
5196073  drivers: Silence debugfs failing log spam  [ShihabZzz]
649b1dc  rcu: boost: avoid preemption before calling complete()  [John Dias]
9b9cc0d  BACKPORT: qseecom: Use scm_call2 when bus_scaling is enabled  [AnilKumar Chimata]
e8a6e8e  BACKPORT: qseecom: Remove virtual address print  [Monika Singh]
0cee061  drivers: input: touchscreen: Create keydisabler nodes  [GuaiYiHu]
99c92b9  arm:dts: msm8953: Add clock-frequency property  [Remicaa]
888e357  thermal: Do not log an error if thermal_zone_get_temp returns -EAGAIN  [Hans de Goede]
88458ff  msm_thermal: initialize later than arch drivers  [Park Ju Hyung]
fd5e620  msm: ipa: update msm_ipa.h with latest IPA versions constants  [Ghanim Fodi]
8bd2ad7  Init Redux !!!  [ShihabZzz]
d3e14fb  Quark: 1.22  [ShihabZzz]
ebf6b05  Merge tag 'ASB-2021-03-05_3.18'  [ShihabZzz]

project system/core/
95cc2d2  fastboot: Bring back legacy A/B support  [LuK1337]

====================
     2021-03-01    
====================

project device/xiaomi/markw/
fca6a1d  markw: rro: Exclude CarrierConfig overlays from RRO  [Quallenauge]
ab8f7b9  markw: sepolicy: Minor cleanup  [ShihabZzz]

project frameworks/base/
009dd8b  Automatic translation import  [Michael Bestas]

project packages/providers/DownloadProvider/
cb1fbfe  Automatic translation import  [Michael Bestas]

project packages/services/Telephony/
6c79ae1  Automatic translation import  [Taesu Lee]

project system/vold/
d023c4b  cryptfs: Fix legacy QCOM HW FDE encryption  [chrmhoffmann]

====================
     2021-02-28    
====================

project lineage-sdk/
09b2736  Automatic translation import  [Michael Bestas]

project lineage/mirror/
d30ecef  Updated aosp-minimal to 27-Feb-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/AudioFX/
61c0b0c  Automatic translation import  [Michael Bestas]

project packages/apps/Bluetooth/
8e8a27e  Automatic translation import  [Michael Bestas]

project packages/apps/Camera2/
ff976ad  Automatic translation import  [Michael Bestas]

project packages/apps/CellBroadcastReceiver/
6d2de4a  Automatic translation import  [Michael Bestas]

project packages/apps/CertInstaller/
a76e061  Automatic translation import  [Michael Bestas]

project packages/apps/Contacts/
c9fdee6  Automatic translation import  [Michael Bestas]

project packages/apps/DeskClock/
a6ca1e0  Automatic translation import  [Michael Bestas]

project packages/apps/Dialer/
5a1bf25  Automatic translation import  [Michael Bestas]

project packages/apps/DocumentsUI/
860e6bd  Automatic translation import  [Michael Bestas]

project packages/apps/Eleven/
fd4180f  Automatic translation import  [Michael Bestas]

project packages/apps/EmergencyInfo/
80a9b04  Automatic translation import  [Michael Bestas]

project packages/apps/Etar/
85c3563  Automatic translation import  [Michael Bestas]

project packages/apps/FlipFlap/
c243b20  Automatic translation import  [Michael Bestas]

project packages/apps/Gallery2/
96b3331  Gallery2: Preserve the decimals in coordinates  [George Zacharia]
12dedab  Automatic translation import  [Michael Bestas]

project packages/apps/HTMLViewer/
28c88ac  Automatic translation import  [Michael Bestas]

project packages/apps/Jelly/
0591712  Automatic translation import  [Michael Bestas]

project packages/apps/KeyChain/
4ae08c8  Automatic translation import  [Michael Bestas]

project packages/apps/LineageParts/
b723287  Automatic translation import  [Michael Bestas]

project packages/apps/ManagedProvisioning/
9e0b3f2  Automatic translation import  [Michael Bestas]

project packages/apps/Messaging/
d23ebe4  Automatic translation import  [Michael Bestas]

project packages/apps/Nfc/
b96085d  Automatic translation import  [Michael Bestas]

project packages/apps/PermissionController/
245faee  Automatic translation import  [Michael Bestas]

project packages/apps/PhoneCommon/
6a7dd26  Automatic translation import  [Michael Bestas]

project packages/apps/Recorder/
d21a50f  Automatic translation import  [Michael Bestas]

project packages/apps/SafetyRegulatoryInfo/
7a20e4b  Automatic translation import  [Michael Bestas]

project packages/apps/Settings/
c4a02fd  Automatic translation import  [Michael Bestas]

project packages/apps/SetupWizard/
f1b9098  Automatic translation import  [Michael Bestas]

project packages/apps/Snap/
2a72f37  Automatic translation import  [Michael Bestas]

project packages/apps/Stk/
1b18e7d  Automatic translation import  [Michael Bestas]

project packages/apps/StorageManager/
5e17b9c  Automatic translation import  [Michael Bestas]

project packages/apps/Tag/
6856a19  Automatic translation import  [Michael Bestas]

project packages/apps/ThemePicker/
71d5df0  Automatic translation import  [Michael Bestas]

project packages/apps/Trebuchet/
6ec5de2  Automatic translation import  [Michael Bestas]

project packages/apps/TvSettings/
3f97219  Automatic translation import  [Michael Bestas]

project packages/apps/Updater/
5a9c747  Automatic translation import  [Michael Bestas]

project packages/apps/WallpaperPicker2/
9fccfe5  Automatic translation import  [Michael Bestas]

project packages/inputmethods/LatinIME/
2da36c4  Automatic translation import  [Michael Bestas]

project packages/modules/CaptivePortalLogin/
f07b392  Automatic translation import  [Michael Bestas]

project packages/providers/BlockedNumberProvider/
8721f75  Automatic translation import  [Michael Bestas]

project packages/providers/BookmarkProvider/
f9f7d5b  Automatic translation import  [Michael Bestas]

project packages/providers/CalendarProvider/
625d6f7  Automatic translation import  [Michael Bestas]

project packages/providers/CallLogProvider/
0b14c94  Automatic translation import  [Michael Bestas]

project packages/providers/ContactsProvider/
d25b1d5  Automatic translation import  [Michael Bestas]

project packages/providers/MediaProvider/
f1bbe5e  Automatic translation import  [Michael Bestas]

project packages/providers/TelephonyProvider/
5c9d45a  Automatic translation import  [Michael Bestas]

project packages/providers/UserDictionaryProvider/
ac74f35  Automatic translation import  [Michael Bestas]

project packages/resources/devicesettings/
254e40a  Automatic translation import  [Michael Bestas]

project packages/screensavers/Basic/
191ea06  Automatic translation import  [Michael Bestas]

project packages/screensavers/PhotoTable/
cc71e4e  Automatic translation import  [Michael Bestas]

project packages/services/BuiltInPrintService/
b57d21e  Automatic translation import  [Michael Bestas]

project packages/services/Mms/
75b2c16  Automatic translation import  [Michael Bestas]

project packages/services/Telecomm/
d8959b6  Automatic translation import  [Michael Bestas]

project packages/wallpapers/LivePicker/
0b31d3a  Automatic translation import  [Michael Bestas]

project vendor/qcom/opensource/fm-commonsys/
bfbc875  Automatic translation import  [Michael Bestas]

====================
     2021-02-27    
====================

project device/qcom/sepolicy-legacy-um/
d3a9cce  common: Allow system_app to read fm_radio_device  [Jarl-Penguin]

project lineage/mirror/
8502c21  Updated aosp-minimal to 26-Feb-2021 13:01 UTC  [Tim Schumacher]

project vendor/qcom/opensource/cryptfs_hw/
aaa8a78  cryptfs_hw: Choose keymaster version for key signing  [Neeraj Soni]

====================
     2021-02-26    
====================

project device/xiaomi/markw/
f616e90  markw: Update libqcmaputils & libqrtr from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
6363d9d  markw: Add MWQEM adapter manifest entry.  [Manoj Basapathi]
951067f  markw: sepolicy: address additional denials  [ZeeLog]
111676f  markw: Enable Power save functionality for modem  [ZeeLog]
8103b9a  markw: Resurrect DPM features  [ZeeLog]
d6ee10c  markw: Add CNE/DPM blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
dfb26af  markw: Add capability NET_BIND_SERVICE to gnss 2.1 service.  [Quallenauge]
68cf248  markw: qmi: add qmi_fw.conf  [Alin Jerpelea]
903dab0  markw: Update media/radio blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ShihabZzz]

project frameworks/base/
d4cca21  BatteryService: Add support for battery Moto Mods  [Vachounet]

project kernel/xiaomi/markw/
486f70b  x86/pti: Do not enable PTI on CPUs which are not vulnerable to Meltdown  [David Woodhouse]

project lineage/website/
872416a  Engineering: Basics of Working with SELinux on Android  [Aayush Gupta]

project vendor/xiaomi/
d9b615b  markw: Update libqcmaputils & libqrtr from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
0423d75  markw: Update DPM blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]

====================
     2021-02-25    
====================

project kernel/xiaomi/markw/
e2b3b03  x86/paravirt: Make native_save_fl() extern inline  [Nick Desaulniers]
5891838  xhci: Fix perceived dead host due to runtime suspend race with event handler  [Mathias Nyman]
1d36dc9  tg3: Add higher cpu clock for 5762.  [Sanjeev Bansal]
f235850  KVM/Eventfd: Avoid crash when assign and deassign specific eventfd in parallel.  [Lan Tianyu]
2138d81  net: cxgb3_main: fix potential Spectre v1  [Gustavo A. R. Silva]
076ff1a  ocfs2: subsystem.su_mutex is required while accessing the item->ci_parent  [alex chen]
5656601  x86/asm: Add _ASM_ARG* constants for argument registers to <asm/asm.h>  [H. Peter Anvin]
dd97e7b  compiler-gcc.h: Add __attribute__((gnu_inline)) to all inline declarations  [Nick Desaulniers]
33ebfa1  compiler, clang: always inline when CONFIG_OPTIMIZE_INLINING is disabled  [David Rientjes]
0b61f62  compiler, clang: properly override 'inline' for clang  [Linus Torvalds]
3686545  compiler, clang: suppress warning for unused static inline functions  [David Rientjes]
f7bd0a3  x86/cpu: Probe CPUID leaf 6 even when cpuid_level == 6  [Andy Lutomirski]
d89a414  uprobes/x86: Remove incorrect WARN_ON() in uprobe_init_insn()  [Oleg Nesterov]
47775ca  x86/cpufeature: Speed up cpu_feature_enabled()  [Borislav Petkov]
03dea2a  x86/boot: Simplify kernel load address alignment check  [Alexander Kuleshov]
d1f28ba  x86/alternatives: Add an auxilary section  [Borislav Petkov]

project lineage/mirror/
6bcc573  Updated aosp-minimal to 24-Feb-2021 13:01 UTC  [Tim Schumacher]

project vendor/xiaomi/
6bf90ed  markw: Add capability NET_BIND_SERVICE to gnss 2.1 service.  [Quallenauge]
4a14464  markw: Update media/radio blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ShihabZzz]

====================
     2021-02-24    
====================

project frameworks/base/
3e9fa16  Allow SBC as HD audio codec in Bluetooth device configuration  [ValdikSS]
24de8e5  Add Dual Channel into Bluetooth Audio Channel Mode developer options menu  [ValdikSS]
5c15088  Add CHANNEL_MODE_DUAL_CHANNEL constant  [ValdikSS]

project hardware/lineage/interfaces/
4e8790e  Import Motorola Health HAL  [Vachounet]

project lineage/mirror/
3c0203c  Updated lineage-minimal to 23-Feb-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/Bluetooth/
b4615fd  Assume optional codecs are supported if were supported previously  [ValdikSS]
eef20ba  SBC Dual Channel (SBC HD Audio) support  [ValdikSS]

project packages/apps/Settings/
c6bc9ee  Add Dual Channel into Bluetooth Audio Channel Mode developer options menu  [ValdikSS]

project prebuilts/extract-tools/
2ffd09a  tools-lineage: Add prebuilt patchelf v0.8  [Sebastiano Barezzi]

project tools/extract-utils/
7f0c788  extract_utils: Implement versioned patchelf and patchelf 0.8  [Sebastiano Barezzi]

====================
     2021-02-23    
====================

project kernel/xiaomi/markw/
8052a57  x86/cpufeature: Cleanup get_cpu_cap()  [Borislav Petkov]
6075b93  x86/cpufeature: Move some of the scattered feature bits to x86_capability  [Borislav Petkov]
b07e5b5  HID: usbhid: add quirk for innomedia INNEX GENESIS/ATARI adapter  [Tomasz Kramkowski]
c222564  USB: serial: cp210x: add another USB ID for Qivicon ZigBee stick  [Olli Salonen]
ffe4cac  USB: serial: ch341: fix type promotion bug in ch341_control_in()  [Dan Carpenter]
25c8056  ahci: Disable LPM on Lenovo 50 series laptops with a too old BIOS  [Hans de Goede]
cfc3798  staging: comedi: quatech_daqp_cs: fix no-op loop daqp_ao_insn_write()  [Dan Carpenter]
c6c07c3  mm, page_alloc: do not break __GFP_THISNODE by zonelist reset  [Vlastimil Babka]
e7936df  HID: hiddev: fix potential Spectre v1  [Gustavo A. R. Silva]
5ab578f  ext4: check superblock mapped prior to committing  [Jon Derrick]
36db2999  ext4: include the illegal physical block in the bad map ext4_error msg  [Theodore Ts'o]
6063903  drbd: fix access after free  [Lars Ellenberg]
ab2e138  tracing: Fix missing return symbol in function_graph output  [Changbin Du]
f8c117c  mm: hugetlb: yield when prepping struct pages  [Cannon Matthews]
cd4c82f  netfilter: nf_tables: use WARN_ON_ONCE instead of BUG_ON in nft_do_chain()  [Taehee Yoo]
c601840  kprobes/x86: Do not modify singlestep buffer while resuming  [Masami Hiramatsu]
d2cae7c  i2c: rcar: fix resume by always initializing registers before transfer  [Wolfram Sang]
564cb9f  n_tty: Access echo_* variables carefully.  [Tetsuo Handa]
acb4063  USB: serial: cp210x: add Silicon Labs IDs for Windows Update  [Karoly Pados]
94269f6  USB: serial: cp210x: add CESINEL device ids  [Johan Hovold]
fe2b599  usb: cdc_acm: Add quirk for Uniden UBC125 scanner  [Houston Yaroschoff]
89253cc  Btrfs: fix unexpected cow in run_delalloc_nocow  [Liu Bo]
ce032ca  ALSA: hda/realtek - Add a quirk for FSC ESPRIMO U9210  [Takashi Iwai]
590d571  Input: elantech - fix V4 report decoding for module with middle key  [???]
78fea60  Input: elantech - enable middle button of touchpads on ThinkPad P52  [Aaron Ma]
1dbdd06  xfrm: skip policies marked as dead while rehashing  [Florian Westphal]
b89af66  xfrm: Ignore socket policies when rebuilding hash tables  [Tobias Brunner]
5972a95  ubi: fastmap: Cancel work upon detach  [Richard Weinberger]
e33a82f  Btrfs: fix clone vs chattr NODATASUM race  [Omar Sandoval]
2e8eee4  RDMA/mlx4: Discard unknown SQP work requests  [Leon Romanovsky]
bca3f77  IB/qib: Fix DMA api warning with debug kernel  [Mike Marciniszyn]
1e43b51  fuse: fix control dir setup and teardown  [Miklos Szeredi]
be32f57  1wire: family module autoload fails because of upper/lower case mismatch.  [Ingo Flaschberger]
e908ec7  serial: sh-sci: Use spin_{try}lock_irqsave instead of open coding version  [Daniel Wagner]
9ec4dba  x86/spectre_v1: Disable compiler optimizations over array_index_mask_nospec()  [Dan Williams]
6d11d46  cpufreq: Fix new policy initialization during limits updates via sysfs  [Tao Wang]
b0e36de  ALSA: hda: add dock and led support for HP ProBook 640 G4  [Dennis Wassenberg]
0d858b2  ALSA: hda: add dock and led support for HP EliteBook 830 G5  [Dennis Wassenberg]
02d0e46  driver core: Don't ignore class_dir_create_and_add() failure.  [Tetsuo Handa]

project vendor/lineage/
7c42814  soong: Add TARGET_LEGACY_HW_DISK_ENCRYPTION conditional  [Nolen Johnson]

====================
     2021-02-22    
====================

project lineage/mirror/
1a1ee4b  Updated aosp-minimal to 21-Feb-2021 13:01 UTC  [Tim Schumacher]

