====================
     2021-03-30    
====================
project android/
f5b058b  Call time on Terminal and libvterm.  [Elliott Hughes]

project build/make/
132d261  build: Remove some debugging props  [Henrique Silva]
be9d75f  Use 'release-keys' for build tag  [Sultanxda]
58dec6a  build tools: Fix TypeError when signing builds with Python3  [ThePiGuy]

project device/lineage/sepolicy/
f25761c  selinux: Introduce Applock [3/3]  [rituj]

project device/xiaomi/markw/
e095fe4  markw: parts: Add sound control  [ZeeLog]
0ab1bbb  markw: Update perf blobs from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]
2269ffb  markw: Use half-resolution version of the boot animation  [zeelog]

project frameworks/av/
60bf554  Don't fail AAC decoding if DRC parameter isn't available  [Pierre-Hugues Husson]

project frameworks/base/
5f87013  RingtoneManager: Set an default ringtone for the SIM 2  [micky387]
4bdc822  base: Phone ringtone setting for Multi SIM device [1/3]  [Ting Yu]
e71e2dc  base: Introduce Applock [1/3]  [rituj]
2c0330d  SystemUI: Fix Wakelock issue  [Alberto Ponces]
1515c9f  BrightnessController: Fix thread exception  [jhenrique09]
a1f0a46  LockIcon: Don't cache icon when scanning face  [jhenrique09]
abbb023  AuthBiometricFingerprintView: Fix indicator text color on dark theme  [jhenrique09]
cb4eadb  fixup - [1/2] Allow using face as auth method for apps  [jhenrique09]
d1f3ef4  AuthContainerView: fix rare SystemUI crash  [Simão Gomes Viana]
e6d2bff  FaceService: Nuke useless call to getAuthenticatorId  [jhenrique09]
a731ddc  Allow using face as auth method for apps  [jhenrique09]
ba0d2fd  cleanup - SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
a068464  Add isFaceAuthEnabledForUser checks in KeyguardLiftController  [jie shen]
0d099ac  SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
5e253f0  base: do not use new lockscreen layout for bypass  [Ethan Halsall]
23087dc  fwb: Guard some functions against face unlock  [jhenrique09]
7ba9c76  Port face unlock feature  [jhenrique09]
b155ae2  Kill off provider info logspam  [Harsh Shandilya]
3847b41  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
f6d1557  core: jni: Switch to -O3  [Simão Gomes Viana]
bb19650  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
0dc6d87  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
1413c0f  telephony: URI cannot be created with negative subIds  [jlask]
6fd47a1  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
9a5075b  DataSwitchTile: dont show toast on click  [micky387]
1eab38e  DataSwitchTile: collapse notification panel onClick  [DennySPB]
fdf1647  SystemUI: Introduce DataSwitchTile  [Christian Oder]
d46436f  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
5530a9e  SystemUI: Remove build version from qs footer  [Pranav Vashi]
e48ad6f  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
8b18930  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
cbf5534  base: Add metric for Blinx Settings  [David Trpchevski]
ea321e2  SystemUI: Add a tile to show power menu  [DarkJoker360]
09584c8  SystemUI: always show screenshot tile in power menu  [Joey]
fff454f  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
0bee133  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
1a32e52  SystemUI: Remove unused resources  [Michael Bestas]
6c7764c  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
de26bca  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
c598a3a  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
ca40fce  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
55a8cf6  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
8f71579  LockIcon: refresh icon on overlay changes  [Dil3mm4]
7f5cdc9  Properly set fonts and icons on keyguard when changing styles  [ezio84]
5348efa  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
6927df8  screenrec: Show dialog on bottom  [El Dainosor]
6fe4ec0  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
e292616  power: Re-introduce custom charging sounds  [Bruno Martins]

project frameworks/opt/net/wifi/
3a59cc3  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
ce09fa1  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
966bdb4  RIL: Fix manual network selection with old modem  [faust93]

project hardware/qcom-caf/msm8996/audio/
1b7f30f  audio: Drop LOCAL_COPY_HEADERS usage  [Pig]
3ba81ff  hal: use omx core headers as a header library  [Jaideep Sharma]
17250c9  hal: Remove libhwbinder/libhidltransport deps  [Steven Moreland]
e6acb2a  audio: Fix flac offload not working  [Keith Mok]
1737eff  audio: Extend platform parser to allow device name aliasing  [Ethan Chen]
300cfc3  hal: Use log/log.h instead of cutils/log.h  [Michael Bestas]
e8d32b9  hal: fix misc audio hal errors  [Weiyin Jiang]
cd887d6  Build audio.primary.* with BOARD_VNDK_VERSION  [Jiyong Park]
49ac856  audio: free and assign NULL to global static device pointer  [Preetam Singh Ranawat]
f8c19ec  hal: fix media param not sent during gapless transition  [Weiyin Jiang]
d8d93e1  Revert "hal: Fix audio compilation issues"  [ShihabZzz]
fb16e1f  audio: Use normal tinycompress  [Rashed Abdel-Tawab]
4c69c43  audio: Use libprocessgroup unconditionally  [Artem Borisov]
cc30301  audio: Fix complilation errors under Clang  [Steve Kondik]
e820816  audio: Use direct project pathmap  [Ethan Chen]

project kernel/xiaomi/markw/
dd02132  arch/markw_defconfig: Enable sound control again!  [ShihabZzz]
e24cf19  arm/dts: markw: Slight camera sensor cleanup  [ShihabZzz]
40cf834  [Squash] Restore sound control  [flar2]
9b0643d  [Squash] Disable HDMI support again!  [Hikari-no-Tenshi]
9c221a9  sound: codecs: Reduce boot spam  [ShihabZzz]

project lineage-sdk/
a4eaa08  sdk: Add power button qs tile metric  [DarkJoker360]
5cebbb6  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/hudson/
cd27faa  hudson: Rename Moto E5 Plus variants  [Jarl-Penguin]

project lineage/wiki/
e255430  wiki: devices: bacon: Update maintainer list  [Nolen Johnson]
92584db  wiki: Rename Moto E5 Plus variants  [Jarl-Penguin]

project packages/apps/Dialer/
d98da30  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
7d77f2e  Dialer: Remove unused resources  [Michael Bestas]
781d58f  Fix selecting phone account dialog show error.  [Grace Jia]
de5231c  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
feedecb  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
57caef5  Messaging: Remove unused resources  [Michael Bestas]
48d799b  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
d922bad  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]
a6bd15f  Mark messages as failed if SIM is inactive  [Taesu Lee]
14b3ba6  Fix creating a new conversation including own number  [Taesu Lee]

project packages/apps/Settings/
c9a49ac  Settings: Use AOSP translations for MSIM ringtone  [jhenrique09]
6fe6424  Settings: enable SIM card ringtone only if slot not empty  [maxwen]
c108760  Settings: Phone ringtone setting for Multi SIM device [2/3]  [Ting Yu]
026b395  Settings: Introduce Applock [2/3]  [rituj]
db39ece  Allow using face as auth method for apps  [jhenrique09]
2e67938  Port faceunlock feature  [jhenrique09]
c714429  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/SetupWizard/
c718719  Add gesture to skip setup wizard  [Oliver Scott]
615408d  Add button to setup eSIM on missing SIM page  [Oliver Scott]
f221a1a  Fix SimMissingActivity never showing  [Oliver Scott]

project packages/apps/Stk/
6a86d49  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
c852386  Trebuchet: Remove workspaceStatusBarScrim  [Michael W]
b24af7e  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
c7357e5  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
6020981  Update Changelog server URL  [ShihabZzz]
cb8c66b  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
369cd24  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project packages/inputmethods/LatinIME/
10de70b  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
c01754d  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
d7e94a3  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
c746f20  Remove webview from the view system before destroying webview  [lucaslin]
d2757fe  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
d7876e9  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/TelephonyProvider/
bbb2cd6  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]
0f8db3d  Fix wrong index access in getSingleMessageFromIcc()  [Taesu Lee]
20f1b47  Support delete all the messages in SIM  [Taesu Lee]
43b4098  Fallback to other address type for EF_SMS  [Taesu Lee]

project packages/services/Telecomm/
d7cbafb  Telecomm: Phone ringtone setting for Multi SIM device [3/3]  [Ting Yu]

project system/core/
84c8249  Filter out QTI performance spam  [DennySPB]
88cd0a9  Silence spammy logs from camera blobs (mm-camera)  [Sultanxda]

project vendor/lineage/
029242b  vendor: Add back FaceUnlock support  [jhenrique09]
a2b1fc6  apns-conf: Add Kena Mobile entries  [Sebastiano Barezzi]
fda5bed  apns-conf: Update PosteMobile entries  [Sebastiano Barezzi]
72c4a09  apns-conf: Add ho.mobile configs  [Sebastiano Barezzi]
e8cab53  apns-conf: Update CoopVoce entries  [Sebastiano Barezzi]
170b76a  config: Don't build Terminal  [Luca Stefani]
3659f82  overlay: set Trebuchet as default notification listener  [althafvly]
1337b1a  Allow unified location provider as possible location provider (not as used location provider)  [Greenflash1986]
7d51ebc  overlay: Override config for platform number verification  [Sneh Bansal]
dda74a9  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
574be33  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
1c3c337  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
949962e  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-03-29    
====================
project vendor/lineage/
adaad8f  backuptool: Do not set ADDOND_VERSION=2 for a-only  [Alessandro Astone]
b5f3a4a  backuptool: Ensure to cleanup the environment on failure  [Alessandro Astone]

project vendor/xiaomi/
62ceb3f  markw: Update perf blobs from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]

====================
     2021-03-28    
====================
project build/make/
8505a10  sign_target_files_apks: Relax ro.build.description requirements  [Stefen Wakefield]

project lineage/hudson/
1b4c009  hudson: Set correct codename for ROG Phone 2  [OrdenKrieger]

project lineage/wiki/
0fe5038  wiki: Set correct codename for ROG Phone 2  [OrdenKrieger]

project packages/apps/Eleven/
30b0348  Eleven: Remove unused class  [Michael W]

project packages/apps/Nfc/
3a59915  NativeNfcTag: Treat MIFARE_CLASSIC same as NFC_A in getTechExtras()  [LuK1337]

====================
     2021-03-27    
====================
project bootable/recovery/
119a2a3  roots: Correct mount flags in /etc/fstab  [Alessandro Astone]

project device/google/atv/
61e3e9f  Remove minimize debug symbol flags  [Aaron Kling]

project device/xiaomi/markw/
9da3eda  markw: Convert XiaomiDoze into XiaomiParts  [Bruno Martins]
9d97781  markw: rro_overlays: Move to Vendor  [Andrew Hexen]
5ee3f2d  markw: Remove libllvm-qcom.so  [Andrew Hexen]

project packages/apps/Eleven/
9e08cc0  Eleven: ensure we got proper permissions before initializing  [Alexander Martinz]
36a7789  Eleven: update widgets UI  [Joey]
073a49a  Eleven: Fix White on White Bug.  [lopez05656]

project packages/apps/Snap/
113ebcf  Snap: Fix SD card visibility for secondary users  [Arne Coucheron]
f2068cc  Snap: Save SDCard photos to legacy path  [Kevin F. Haggerty]
f968486  Revert "Snap: Remove saving to sdcard"  [Arne Coucheron]

project packages/providers/MediaProvider/
7a9f0c3  MediaProvider: Fix insert fail while file saved in sdcard  [Wang Haijun]

project vendor/xiaomi/
7d6b4f5  markw: Remove libllvm-qcom.so  [ShihabZzz]

====================
     2021-03-26    
====================
project bootable/recovery/
dbd2467  Add controller support  [Aaron Kling]

project frameworks/base/
bc36ac0  SystemUI: AODTile: Actually start using SecureSetting  [LuK1337]
90a1fae  SystemUI: AODTile: Use SecureSetting to change doze setting  [Luca Stefani]

project lineage/wiki/
6e24e58  wiki: templates: Add instructions for building emulator images  [Tim Schumacher]
558c594  wiki: devices: crackling: Instruct users to install required firmware  [115ek]

project packages/apps/CellBroadcastReceiver/
32aea65  CellBroadcastReceiver: Allow framework to do dark theming automatically  [Michael Bestas]

project vendor/lineage/
271ba02  sensitive_pn: Run XML lint against the schema  [Luca Stefani]
2b30c72  sensitive_pn: Convert to new format  [Michael W]
e4359d9  sensitive_pn: Comment, add and change numbers for multiple countries.  [Arekusu Rin]

====================
     2021-03-25    
====================
project build/make/
8c8f429  releasetools: Add script to sign zips  [Gabriele M]

project build/soong/
3ead21d  Revert "Add AIDL lineage power HAL to VndkMustUseVendorVariantList"  [LuK1337]

project external/chromium-webview/
dcdf525  Update Chromium Webview to 89.0.4389.105  [Kevin F. Haggerty]

project hardware/lineage/interfaces/
af905cd  Drop VNDK support from vendor.lineage.power aidl interface  [LuK1337]

project lineage/hudson/
6a6ddbf  experimentals: Cover all test-cases  [Nolen Johnson]

====================
     2021-03-24    
====================
project device/xiaomi/markw/
ac82575  markw: sepolicy: Quiet system_app attempts to find disallowed services  [Kevin F. Haggerty]

project lineage/wiki/
3433899  wiki: templates: ab_copy_partitions: Remove mapper from the loop  [Nolen Johnson]

project packages/apps/SetupWizard/
6b9de1c  SetupWizard: Move to system_ext  [Luca Stefani]
c102a32  SetupWizard: Convert to Android.bp  [Luca Stefani]
29e7774  SetupWizard: Disable mobile data at least once  [Michael W]

====================
     2021-03-23    
====================
project frameworks/base/
401638a7  VolumeDialogImpl: Don't vibrate when volume dialog is not visible  [LuK1337]

====================
     2021-03-22    
====================
project build/soong/
fa55b7c  Add AIDL lineage power HAL to VndkMustUseVendorVariantList  [dianlujitao]

project device/lineage/sepolicy/
13f733d  sepolicy: Label AIDL lineage power HAL service  [dianlujitao]

project device/xiaomi/markw/
72d1336  markw: Fix derps...  [ShihabZzz]

project frameworks/base/
6bd9c12  perf: Support AIDL Lineage power HAL service  [dianlujitao]
6941cbf  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
95fa768  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
62da546  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
3de49ba  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
d394326  Restore preferred activity filter if it not inside  [vend_wsd_am_052]

project frameworks/native/
1e7f9e6  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]

project hardware/interfaces/
297cf89  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
2ad0d81  Set default value for pressure sensor  [Hsin-Yi Chen]

project hardware/lineage/interfaces/
7858a4c  Add AIDL lineage power HAL  [dianlujitao]

project lineage/wiki/
19e05d0  wiki: Correct button combinations on espressowifi  [Harry Cutts]

project packages/apps/PermissionController/
67260eb  [DO NOT MERGE] Deep-update live datas and update on isStale in getInitializedValue  [Eugene Susla]

project packages/apps/Settings/
35eebd2  Fix crash on "Connection preferences"  [Hugh Chen]

project system/core/
f5c18f8  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
0fdfe77  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
ba44a40  Only store result of mount_all that mounted userdata  [Nikita Ioffe]

project system/sepolicy/
95da6f3  Export ro.vendor.product.cpu.abilist*  [SzuWei Lin]
996e744  Sepolicy for dumsys suspend_control in bugreport  [Kalesh Singh]
5a9e45a  Add ro.cpuvulkan.version to property_contexts  [Inseob Kim]
46d058f  Add ro.cdma.home.operator. properties  [Inseob Kim]
73da57f  Allow dumpstate to dump hal_light  [Roman Kiryanov]
8baeefa  Allow dumpstate to get thermal and power hal debug info  [TeYuan Wang]

====================
     2021-03-21    
====================
project frameworks/opt/telephony/
048025d  Merge 'lineage-18.1' into 11.0  [Pranav Vashi]

project lineage/wiki/
b2fefa9  wiki: contributors: Update Committers/Reviewers to match Gerrit  [Kevin F. Haggerty]
e5bf897  wiki: contributors: Sort Committers  [Kevin F. Haggerty]

project system/update_engine/
6c1699d  update_engine: Do not attempt to run backuptool in recovery  [Alessandro Astone]

====================
     2021-03-20    
====================

====================
     2021-03-19    
====================
project device/xiaomi/markw/
9192f61  Revert "markw: camera: QCamera2: HAL3: Fix fdleak issue"  [ShihabZzz]

====================
     2021-03-18    
====================
project frameworks/base/
d209b41  SystemUI: AmbientTile: Default the setting to 1  [Luca Stefani]
e928b5d  SystemUI: SecureSetting: Allow specifying a non-zero default  [Luca Stefani]
4d3d8db  SystemUI: AmbientTile: Actually start using SecureSetting  [LuK1337]
810cac8  SystemUI: AmbientTile: Use SecureSetting to change doze setting  [Luca Stefani]
5ca4149  SystemUI: AmbientTile: Don't hardcode display settings intent  [Luca Stefani]

project frameworks/opt/telephony/
26b8abd  Update external card state based on current app  [Wileen Chiu]

project lineage/mirror/
fe36af6  Updated to 17-Mar-2021 13:52 UTC  [Kevin F. Haggerty]
5638820  Updated aosp-minimal to 17-Mar-2021 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
d7a8295  Revert "devices: channel: Use custom TWRP"  [Nolen Johnson]

project packages/apps/Eleven/
ba4ec3a  Eleven: Add a Material Theme and a Dark Theme  [Marcos Lopez]
f8b4fc5  Eleven: declare support for ACTION_SEEK_TO  [Marcos Lopez]
c71ba79  Eleven: the great cleanup  [Joey]
c9c8288  Eleven: Update gradle and dependencies  [Michael W]
365a1e7  Eleven: Audio preview: Follow dark/light theming  [Michael W]

project packages/apps/SetupWizard/
bc224d5  SetupWizard: Remove libphonenumber dep  [Luca Stefani]

====================
     2021-03-17    
====================
project kernel/xiaomi/markw/
bcf0a24  arm64/configs: markw: Disable CPU Subsystem Dumping support  [ShihabZzz]

project lineage/mirror/
e29cf02  Updated to 16-Mar-2021 13:35 UTC  [Kevin F. Haggerty]
0b8d155  Updated aosp-minimal to 16-Mar-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/Recorder/
9a36896  Recorder: update UI theme  [2bllw8]
148c038  Recorder: add paused title  [2bllw8]
6c9c3a8  Recorder: update to sdk 30  [2bllw8]
d98e93e  Recorder: draw full edge-to-edge  [2bllw8]

