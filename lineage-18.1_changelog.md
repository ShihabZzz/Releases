====================
     2021-03-12    
====================
project android/
b5e0fc5  Call time on Terminal and libvterm.  [Elliott Hughes]

project bootable/recovery/
6680a92  recovery: Add logcat to deps  [Michael Bestas]

project build/make/
e5b1a45  build: Remove some debugging props  [Henrique Silva]
d2c58ac  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
4f52c92  markw: Remove VoLTE reset work-around  [ShihabZzz]
1915f13  markw: Update QMI from LA.UM.9.6.2.r1-03600-89xx.0  [ShihabZzz]
7631c6a  markw: Remove BOARD_PROPERTY_OVERRIDES_SPLIT_ENABLED  [Georg Veichtlbauer]
37308a9  markw: display: Clean up dead targets  [ZeeLog]

project frameworks/base/
f8856f3  Kill off provider info logspam  [Harsh Shandilya]
d096b27  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
9958b8f  core: jni: Switch to -O3  [Simão Gomes Viana]
1f2f9b6  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
8d5477b  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
0dba295  telephony: URI cannot be created with negative subIds  [jlask]
cf68514  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
3c16527  DataSwitchTile: dont show toast on click  [micky387]
28a8a4d  DataSwitchTile: collapse notification panel onClick  [DennySPB]
718dd3f  SystemUI: Introduce DataSwitchTile  [Christian Oder]
7215875  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
9a5fb70  SystemUI: Remove build version from qs footer  [Pranav Vashi]
d77fea3  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
af0e966  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
b61c7b4  base: Add metric for Blinx Settings  [David Trpchevski]
4bc8771  SystemUI: Add a tile to show power menu  [DarkJoker360]
245964d  Revert "No need to 'addChild' when start 'FLAG_ACTIVITY_CLEAR_TOP' Activity."  [Han Wang]
6383015  SystemUI: always show screenshot tile in power menu  [Joey]
c503c0a  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
b307a7e  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
9b83cfa  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
5645875  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
7acc642  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
f6f2780  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
0ef6a66  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
73f241a  SystemUI: Remove unused resources  [Michael Bestas]
88d89a4  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
2eed02c  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
3a4b220  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
cc52b29  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
6d89828  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
5d78eba  LockIcon: refresh icon on overlay changes  [Dil3mm4]
9df7c27  Properly set fonts and icons on keyguard when changing styles  [ezio84]
c7ad909  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
03ce4e6  screenrec: Show dialog on bottom  [El Dainosor]
a0101b1  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
19d361f  power: Re-introduce custom charging sounds  [Bruno Martins]
41f80e2  incremental: Fix more clang-tidy warnings  [Luca Stefani]
2bbd249  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
8bd2bc1  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/native/
665f2e1  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]

project frameworks/opt/net/wifi/
4c45de1  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
0bc4d47  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
b6ebb27  RIL: Fix manual network selection with old modem  [faust93]

project hardware/interfaces/
fc85257  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
3e33644  Set default value for pressure sensor  [Hsin-Yi Chen]
ad2df63  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
dce094f  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
3d2f93e  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
1801a22  sdk: Add power button qs tile metric  [DarkJoker360]
b1be16b  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/wiki/
66fc4d9  wiki: Reorder gts4lv maintainers  [LuK1337]
c843dba  wiki: Add remaining retail devices to gts4lv models  [LuK1337]

project packages/apps/Camera2/
3b54f25  Camera2: Set targetSdkVersion=29  [Michael Bestas]
73079fb  AOSP/Camera2 - Fix bug causing edit, share, delete buttons to not appear  [Colin Marsch]
4bd5c2a  AOSP/Camera2 - Remove Saving bar after taking a photo  [Colin Marsch]
d8c152b  AOSP/Camera2 - Update Storage method to be compatible with API 29  [Colin Marsch]
70bf669  Revert "Revert "Camera2: Migrate to new storage API""  [Colin Marsch]

project packages/apps/Dialer/
493dcc7  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
14a67ba  Dialer: Remove unused resources  [Michael Bestas]
728cbca  Fix selecting phone account dialog show error.  [Grace Jia]
f065eea  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/Eleven/
d8f86ad  Eleven: Add a Material Theme and a Dark Theme  [Marcos Lopez]
13a8ec2  Eleven: declare support for ACTION_SEEK_TO  [Marcos Lopez]
5c590d7  Eleven: the great cleanup  [Joey]
c7ea9e2  Eleven: Update gradle and dependencies  [Michael W]
ede1aaf  Eleven: Audio preview: Follow dark/light theming  [Michael W]

project packages/apps/LineageParts/
89e0fed  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
8bef02a  Messaging: Remove unused resources  [Michael Bestas]
ecb996a  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
640051c  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]
fa801b5  Mark messages as failed if SIM is inactive  [Taesu Lee]
42609f3  Fix creating a new conversation including own number  [Taesu Lee]

project packages/apps/PermissionController/
6da7c9c  [DO NOT MERGE] Deep-update live datas and update on isStale in getInitializedValue  [Eugene Susla]

project packages/apps/Recorder/
917d1c5  Recorder: support bazel build  [2bllw8]
6ab9510  Recorder: draw full edge-to-edge  [2bllw8]
9148e67  Recorder: Correct WAV header creation  [Paul Keith]

project packages/apps/Settings/
d5e5944  Fix crash on "Connection preferences"  [Hugh Chen]
3782445  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
62b531a  Snap: Fix SD card visibility for secondary users  [Arne Coucheron]
9b58619  Snap: Save SDCard photos to legacy path  [Kevin F. Haggerty]
a0a0870  Revert "Snap: Remove saving to sdcard"  [Arne Coucheron]

project packages/apps/Stk/
1b0dee2  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
2413af6  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
37cd019  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
26fb0a0  Update Changelog server URL  [ShihabZzz]
ee74a47  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
4f463b7  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project packages/inputmethods/LatinIME/
c4d5e50  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
0b7fbe5  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
e5067b6  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
6ec15f1  Remove webview from the view system before destroying webview  [lucaslin]
09e7e80  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
5e49770  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/modules/NetworkStack/
f4f9ce8  Merge tag 'android-11.0.0_r32' of https://android.googlesource.com/platform/packages/modules/NetworkStack into lineage-18.1  [ShihabZzz]

project packages/providers/MediaProvider/
7c645e9  MediaProvider: Fix insert fail while file saved in sdcard  [Wang Haijun]

project packages/providers/TelephonyProvider/
0731475  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]
2cf38b4  Fix wrong index access in getSingleMessageFromIcc()  [Taesu Lee]
7894f36  Support delete all the messages in SIM  [Taesu Lee]
c2131cb  Fallback to other address type for EF_SMS  [Taesu Lee]

project system/core/
fd8aad8  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
6ee35e8  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
38e9c60  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
18b5be2  logcat: Mark as recovery_available  [Michael Bestas]
d2a6913  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
0ee8d44  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]

project system/sepolicy/
eef52fc  Export ro.vendor.product.cpu.abilist*  [SzuWei Lin]
59ffd4f  Sepolicy for dumsys suspend_control in bugreport  [Kalesh Singh]
25f547f  Add ro.cpuvulkan.version to property_contexts  [Inseob Kim]
1bda334  Add ro.cdma.home.operator. properties  [Inseob Kim]
76247e4  Allow dumpstate to dump hal_light  [Roman Kiryanov]
decfd2c  Allow dumpstate to get thermal and power hal debug info  [TeYuan Wang]

project system/vold/
fb50d33  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]

project tools/extract-utils/
1da3655  Remove support for /sbin  [Michael Bestas]

project vendor/lineage/
7a6ea8a  config: Don't build Terminal  [Luca Stefani]
0c82c67  overlay: Override config for platform number verification  [Sneh Bansal]
9e36a7b  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
0334273  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
c6baf49  lineage: repopick: pick only open changes in a topic  [Akhil Narang]
ade9895  config: Set screen size defaults globally  [Alessandro Astone]

project vendor/qcom/opensource/interfaces/
d3bfd49  interfaces: Introduce vendor.qti.hardware.audiohalext@1.0 HAL  [Alexander Koskovich]

project vendor/qcom/opensource/power/
cfbfee2  power: Kill "Failed to acquire lock" log  [Luca Stefani]

project vendor/xiaomi/
002335d  markw: Update QMI from LA.UM.9.6.2.r1-03600-89xx.0  [ShihabZzz]

====================
     2021-03-11    
====================
project lineage/mirror/
0bf9386  Updated aosp-minimal to 11-Mar-2021 13:01 UTC  [Tim Schumacher]

====================
     2021-03-10    
====================
project lineage/hudson/
476f594  hudson: Show Recovery on castor  [Nolen Johnson]

project lineage/wiki/
ca7766c  wiki: Add Sony Xperia Tablet Z2 LTE (castor)  [Georg Veichtlbauer]

project vendor/lineage/
db31384  lineage: targets: x86{,_64}_ab: Don't explicitly include SDK addon  [Nolen Johnson]
52be5fc  lineage: targets: Add support for Legacy GSIs  [Nolen Johnson]

====================
     2021-03-09    
====================
project lineage/wiki/
8efe06c  wiki: before_lineage_install_flox: Format userdata at correct time  [Nolen Johnson]

====================
     2021-03-08    
====================
project build/make/
1c4c909  build: Turn redundant path requirements error into a warning  [Alessandro Astone]

project lineage/mirror/
976a2ef  Updated aosp-minimal to 08-Mar-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/Dialer/
f321ae8  dialer: Allow Call Recording For Bangladesh  [Nahid Hasan Riyad]

====================
     2021-03-07    
====================
project device/lineage/sepolicy/
9175be9  fixup! sepolicy: common: Move Moto Health HAL to dynamic policy  [Aayush Gupta]
d13d4fa  sepolicy: common: Move Moto Health HAL to dynamic policy  [Joshua Blanchard]

project device/xiaomi/markw/
4c7ce63  markw: Update ANT+/BT blobs from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]
dc98618  markw: sepolicy: Shush! spam...  [ShihabZzz]
2584309  markw: overlay: enable config_sf_limitedAlpha  [srfarias]

project frameworks/av/
848ad26  CCodec: workaround for frame drops  [Wonsik Kim]
0b2ecd0  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
80e20ae  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
842477a  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
2bc5b22  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
1710b85  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
18f63b9  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
c03f236  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
40473d6  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
7107081  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
7eff92e  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
b88a5a2  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
ea94564  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]

project lineage/wiki/
494a9d2  wiki: g2: Instruct to exit adb shell after bootloader dd  [Alessandro Astone]

====================
     2021-03-06    
====================
project device/lineage/sepolicy/
a5640c3  lineage: common: public: Address Motorola Health HAL denial  [Nolen Johnson]

project frameworks/base/
e388fe7  Sharesheet: Set max ranked items to 8  [LuK1337]
d274c33  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/native/
8734385  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/opt/telephony/
9f153db  Merge 'lineage-18.1' into 11.0  [Pranav Vashi]

project lineage-sdk/
4457a81  lineage-sdk: Fix NPE when using getPictureAdjustmentRanges()  [Han Wang]

project system/core/
38d2a0e  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/vold/
748ecf7  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

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
project frameworks/base/
d0b4d17  BatteryService: Mod: Check against all conditions  [Ali B]

project vendor/qcom/opensource/commonsys-intf/display/
8c1a0d2  qdMetadata: Ignore UNUSED parameter  [cjh1249131356]

====================
     2021-03-02    
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

project device/qcom/sepolicy-legacy-um/
a49ec66  sepolicy: Remove poweroffalarm system uid and redundant rules  [Guixiong Wei]

project external/cldr/
1e4de98  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project external/icu/
9631b02  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/av/
26a64fb  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/base/
df71b93  BatteryManager: Mark battery moto mods constants as hidden  [LuK1337]

project frameworks/native/
9e07dbd  Ensure that expected present time is in the future  [Snild Dolkow]
c02140b  SF: handle long waiting Layer sync point  [KaiChieh Chuang]

project frameworks/opt/net/wifi/
5f3c73c  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project frameworks/opt/telephony/
fad7a3a  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

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

project system/core/
95cc2d2  fastboot: Bring back legacy A/B support  [LuK1337]

project system/sepolicy/
f351416  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/timezone/
4181b85  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project system/update_engine/
0732d12  Merge tag 'android-11.0.0_r32' into staging/lineage-18.1_merge-android-11.0.0_r32  [Kevin F. Haggerty]

project vendor/qcom/opensource/commonsys/system/bt/
3a0ad0d  SDP: Only start discovery once  [Myles Watson]

====================
     2021-03-01    
====================
project device/xiaomi/markw/
fca6a1d  markw: rro: Exclude CarrierConfig overlays from RRO  [Quallenauge]

project lineage/hudson/
e1c3738  hudson: Add castor to 17.1  [Georg Veichtlbauer]

project system/vold/
d023c4b  cryptfs: Fix legacy QCOM HW FDE encryption  [chrmhoffmann]

====================
     2021-02-28    
====================
project device/xiaomi/markw/
ab8f7b9  markw: sepolicy: Minor cleanup  [ShihabZzz]

project frameworks/base/
009dd8b  Automatic translation import  [Michael Bestas]

project lineage-sdk/
09b2736  Automatic translation import  [Michael Bestas]

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

project packages/providers/DownloadProvider/
cb1fbfe  Automatic translation import  [Michael Bestas]

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

project packages/services/Telephony/
6c79ae1  Automatic translation import  [Taesu Lee]

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
d30ecef  Updated aosp-minimal to 27-Feb-2021 13:01 UTC  [Tim Schumacher]

project vendor/qcom/opensource/cryptfs_hw/
aaa8a78  cryptfs_hw: Choose keymaster version for key signing  [Neeraj Soni]

