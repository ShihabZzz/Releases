====================
     2021-05-01    
====================
project android/
09f4aad  Call time on Terminal and libvterm.  [Elliott Hughes]

project build/make/
1291d3f  build: Remove some debugging props  [Henrique Silva]
d4acb5e  Use 'release-keys' for build tag  [Sultanxda]

project device/lineage/sepolicy/
2a0f62d  selinux: Introduce Applock [3/3]  [rituj]

project device/xiaomi/markw/
4c333db  markw: Update blobs from LA.UM.9.6.2.r1-04200-89xx.0  [ShihabZzz]
717c277  markw: wifi: Enable 2.4GHz channel bonding  [Michael W]
4611642  markw: Remove odex/oat files from pinner list.  [Nicolas Geoffray]
16ad81c  markw: copy out 64bit variant only of btconfigstore  [ZeeLog]
449353a  markw: Set voice call volume steps to 6  [Brock5555]
82160fb  markw: Remove IWlan  [Arian]
8777c5b  markw: Remove unused QTI BT audio blobs  [ZeeLog]

project frameworks/base/
0997384  configure same GID based APNs as per carrier requirements  [Avinash Nalluri]
875a6aa  Fix issue: https://issuetracker.google.com/issues/183024999  [Tang Ding]
23f5d5e  RingtoneManager: Set an default ringtone for the SIM 2  [micky387]
db16fe6  base: Phone ringtone setting for Multi SIM device [1/3]  [Ting Yu]
f05bf53  base: applock: Check current and called activity package before locking again  [Pranav Kapoor]
14bc406  base: applock: Add option to instantly lock app on closing [1/2]  [Pranav Kapoor]
9cf0a9b  base: AppLock: Call activityStopped when activity has stopped  [Rituj Beniwal]
d888d91  base: Introduce Applock [1/3]  [rituj]
9a8b08c  SystemUI: Fix Wakelock issue  [Alberto Ponces]
a971a18  BrightnessController: Fix thread exception  [jhenrique09]
0f5d3e3  LockIcon: Don't cache icon when scanning face  [jhenrique09]
afda196  AuthBiometricFingerprintView: Fix indicator text color on dark theme  [jhenrique09]
9c86882  fixup - [1/2] Allow using face as auth method for apps  [jhenrique09]
0db2610  AuthContainerView: fix rare SystemUI crash  [Simão Gomes Viana]
bbca22f  FaceService: Nuke useless call to getAuthenticatorId  [jhenrique09]
08e57af  Allow using face as auth method for apps  [jhenrique09]
e46c035  cleanup - SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
ec63d13  Add isFaceAuthEnabledForUser checks in KeyguardLiftController  [jie shen]
7887bdf  SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
44e1487  base: do not use new lockscreen layout for bypass  [Ethan Halsall]
595caae  fwb: Guard some functions against face unlock  [jhenrique09]
9d7c174  Port face unlock feature  [jhenrique09]
4a1491c  Kill off provider info logspam  [Harsh Shandilya]
ee1c5ac  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
278ac3e  core: jni: Switch to -O3  [Simão Gomes Viana]
fd0199b  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
5c23249  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
b89e065  telephony: URI cannot be created with negative subIds  [jlask]
2cd22d4  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
aa89eec  DataSwitchTile: dont show toast on click  [micky387]
c8194f4  DataSwitchTile: collapse notification panel onClick  [DennySPB]
9a4cb73  SystemUI: Introduce DataSwitchTile  [Christian Oder]
1f3dfb0  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
e3f8e27  SystemUI: Remove build version from qs footer  [Pranav Vashi]
7d329a8  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
0895095  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
fe52fc5  base: Add metric for Blinx Settings  [David Trpchevski]
1ff293d  SystemUI: Add a tile to show power menu  [DarkJoker360]
0b67123  VolumeDialogImpl: Get the location in window instead of on screen  [HrX03]
eb78087  VolumeDialogImpl: Remove insets listener on dismiss  [HrX03]
c79bccb  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
b1900fc  SystemUI: VolumeDialog: Improve expandable volumepanel  [althafvly]
3c60cfe  Fixed a crash in settings in tts engine selection screen.  [Deve]
11cf5f5  EasterEgg: Fix some warnings  [Michael W]
ded5a63  Don't enable extra StrictMode features for userdebug builds  [Sultan Alsawaf]
8c214de  SystemUI: always show screenshot tile in power menu  [Joey]
d915b5e  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
a3779ca  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
fd9a535  SystemUI: Remove unused resources  [Michael Bestas]
a99522c  overlays: Fix inactive WiFi icon fill/stroke alpha for Circular, Filled, and Kai themes  [Aman Singh]
e14e8cd  LockIcon: refresh icon on overlay changes  [Dil3mm4]
994e484  Properly set fonts and icons on keyguard when changing styles  [ezio84]
17db167  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
701d28a  screenrec: Show dialog on bottom  [El Dainosor]
d9d05b7  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
3285dce  power: Re-introduce custom charging sounds  [Bruno Martins]

project frameworks/opt/net/wifi/
6fb5a61  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
92892cd  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
20cbeba  RIL: Fix manual network selection with old modem  [faust93]

project lineage-sdk/
bca25b7  sdk: Add power button qs tile metric  [DarkJoker360]
295c36c  LineageSettingsProvider: Mark lookup features as deprecated  [Bruno Martins]
c9672f8  lineage-sdk: Tweak default charging sound path again  [Han Wang]
c47d955  BatteryLights: Add ability to turn off LED when fully charged  [Bruno Martins]

project lineage/hudson/
392c33c  Reland: "hudson: Bump 0x859583888993818481 and 0x86819189a381 to 18.1"  [LuK1337]

project lineage/wiki/
07869bf  Reland: "wiki: Bump fajita to 18.1"  [LuK1337]

project packages/apps/Dialer/
d862f90  CallRecordingAutoMigrator: Handle all exceptions  [Pranav Vashi]
e9196cb  Dialer: Make recording names sortable  [Pranav Vashi]
eaf9402  Add autorecord feature  [DennySPB]
61c1d6f  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
1fbd2cf  Dialer: Remove unused resources  [Michael Bestas]
309433c  Fix selecting phone account dialog show error.  [Grace Jia]

project packages/apps/Jelly/
16e5ac7  Jelly: Add support for viewable content:// scheme  [LuK1337]
47ad959  Jelly: Start using OpenMultipleDocuments for FileShower  [Luca Stefani]

project packages/apps/LineageParts/
a447b70  LineageParts: Tweak default charging sound path  [Han Wang]
fa3b1bd  LineageParts: Add color mode preview from AOSP Settings  [LuK1337]
c642690  BatteryLightSettings: Add ability to turn off LED when fully charged  [Bruno Martins]

project packages/apps/Messaging/
5a697c6  Messaging: Remove unused resources  [Michael Bestas]

project packages/apps/Settings/
2a5f823  Settings: Add option to instantly lock app on closing [2/2]  [Pranav Kapoor]
ad909fc  Settings: Use AOSP translations for MSIM ringtone  [jhenrique09]
bd46b96  Settings: enable SIM card ringtone only if slot not empty  [maxwen]
287f242  Settings: Phone ringtone setting for Multi SIM device [2/3]  [Ting Yu]
b652c07  Settings: Introduce Applock [2/3]  [rituj]
9b26b7d  Allow using face as auth method for apps  [jhenrique09]
70eaa97  Port faceunlock feature  [jhenrique09]
66511d3  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/SetupWizard/
caf02a1  Add gesture to skip setup wizard  [Oliver Scott]
1e85632  Add button to setup eSIM on missing SIM page  [Oliver Scott]
d077f17  Fix SimMissingActivity never showing  [Oliver Scott]

project packages/apps/Stk/
9fbdade  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
a299218  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
053670c  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
3596ac5  Update Changelog server URL  [ShihabZzz]
fa670c1  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
276c210  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project packages/inputmethods/LatinIME/
496a7b3  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
eb8dd8c  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
3da0446  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
f8a3711  Remove webview from the view system before destroying webview  [lucaslin]
9d10ed2  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
a7a2258  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/TelephonyProvider/
91531fd  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]

project packages/services/Telecomm/
de84bfd  Telecomm: Phone ringtone setting for Multi SIM device [3/3]  [Ting Yu]

project system/core/
f828daa  Filter out QTI performance spam  [DennySPB]
98b3d89  Silence spammy logs from camera blobs (mm-camera)  [Sultanxda]

project vendor/lineage/
6bc51b2  vendor: Add back FaceUnlock support  [jhenrique09]
e9911d0  apns-conf: Add Kena Mobile entries  [Sebastiano Barezzi]
fa09b49  apns-conf: Update PosteMobile entries  [Sebastiano Barezzi]
e4d2694  apns-conf: Add ho.mobile configs  [Sebastiano Barezzi]
f6c8b8c  apns-conf: Update CoopVoce entries  [Sebastiano Barezzi]
778c29d  config: Don't build Terminal  [Luca Stefani]
00f2666  overlay: Override config for platform number verification  [Sneh Bansal]
7e5c81c  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
0613496  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
a18a1df  lineage: repopick: pick only open changes in a topic  [Akhil Narang]
70925d6  vendor: apns: Add Ting  [Michael W]
9b70f83  envsetup: Make dopush() /system_ext aware  [Bruno Martins]

project vendor/qcom/opensource/power/
1d86011  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-04-30    
====================
project lineage/hudson/
a5d0a5c  Revert "hudson: Bump 0x859583888993818481 and 0x86819189a381 to 18.1"  [LuK1337]

project lineage/wiki/
e1aacca  Revert "wiki: Bump fajita to 18.1"  [LuK1337]

====================
     2021-04-29    
====================
project frameworks/av/
3bcf5d2  Don't fail AAC decoding if DRC parameter isn't available  [Pierre-Hugues Husson]

project frameworks/base/
8f854f4  [DO NOT MERGE] Use loadDrawableAsUser in MediaDataManager  [Isak Lilja]

project kernel/xiaomi/markw/
cea733f  Redux: 2.05  [ShihabZzz]

project lineage/hudson/
3ff89cc  hudson: Bump 0x859583888993818481 and 0x86819189a381 to 18.1  [LuK1337]

project lineage/mirror/
7e39acc  Updated aosp-minimal to 29-Apr-2021 12:01 UTC  [Tim Schumacher]

project lineage/wiki/
8b290ac  wiki: Bump fajita to 18.1  [LuK1337]

project vendor/xiaomi/
98dd0e2  markw: Update blobs from LA.UM.9.6.2.r1-04200-89xx.0  [ShihabZzz]

====================
     2021-04-28    
====================
project device/qcom/sepolicy-legacy-um/
5dced87  legacy: Resolve more surfaceflinger related denial  [ShihabZzz]
da11028  Allow surfaceflinger to search hal_graphics_composer_default  [ChengYou Ho]

project frameworks/base/
2807f50  SystemUI: allow to limit the max framerate of built-in screen recorder  [Kuba Wojciechowski]

project lineage/mirror/
d944f35  Updated to 28-Apr-2021 11:39 UTC  [Kevin F. Haggerty]

project lineage/wiki/
99979ee  wiki: Go back to payload-dumper-go  [LuK1337]
c9d67d7  wiki: Instruct users to reboot to recovery past copy-partitions  [LuK1337]

project packages/apps/Settings/
e039c25  Settings: Allow devices to provide their own color mode strings  [LuK1337]

project packages/apps/Updater/
a36be60  Updater: appbar: Set the collapsing animation duration to 0ms  [Dhina17]

project vendor/xiaomi/
776147f  markw: Remove IWlan  [Arian]
eb07b16  markw: Remove unused QTI BT audio blobs  [ZeeLog]
4ae4902  markw: Remove unused blobs  [ZeeLog]
410853d  markw: Update DRM Widevine & BT Aptx from Crosshatch  [ZeeLog]

====================
     2021-04-27    
====================
project device/xiaomi/markw/
6e88c22  markw: Remove unused blobs  [ZeeLog]
0501d99  markw: Align device properties with CAF  [ZeeLog]
e026a18  markw: Update DRM Widevine & BT Aptx from Crosshatch  [ZeeLog]
9c5fe1b  markw: Allow xtwifi-client to access wake alarm  [Baili Feng]
8083ceb  markw: Added BLOCK_SUPSPEND capability for xtwifi-client  [Mike Cailean]
5ecff0b  markw: config.fs: Add pd-mapper and xtwifi-client mapping  [Mike Cailean]
006b6e0  markw: Update uceservice HAL to 2.3  [Pavan Kumar M]
6651ed2  Revert "markw: Switch to Audio HAL V6"  [dianlujitao]

project frameworks/base/
be00ba5  SystemUI: Apply system_icons_keyguard_padding_end to parent view  [LuK1337]

project lineage/mirror/
dac64e9  Updated aosp-minimal to 27-Apr-2021 12:01 UTC  [Tim Schumacher]

project vendor/lineage/
4280154  envsetup: replace  __detect_shell with basename $SHELL  [Dhina17]
5c1d8be  envsetup: fix lineagegerrit push for zsh  [Dhina17]

====================
     2021-04-26    
====================
project device/xiaomi/markw/
a4c2251  markw: Update blobs from LA.UM.9.6.2.r1-04100-89xx.0  [ShihabZzz]
12ea791  markw: Fix GNSS sed command  [ShihabZzz]
b056bb1  markw: Switch to patchelf from tools-lineage  [Michael Bestas]
db92fd4  markw: libshim_wfdmmsink: Build 32bit variant only  [ZeeLog]
cbf663e  markw: Provide a shim for libwfdmmsink  [Arian]
1a5184d  markw: wfd: remove patched blobs  [ZeeLog]

project vendor/xiaomi/
c3841ba  markw: Update blobs from LA.UM.9.6.2.r1-04100-89xx.0  [ShihabZzz]
da09024  markw: Add shim dependency for libwfdmmsink  [ZeeLog]
a354f1a  markw: remove wfd patched blobs  [ZeeLog]

====================
     2021-04-25    
====================
project android/
23280b5  manifest: Track our fork of system/media  [dianlujitao]

project frameworks/base/
6cd9135  Keyguard: Fix mapping mismatch between KeyEvent and NumPadKey  [LuK1337]

project lineage/hudson/
0f4e8f4  Promote jason to 18.1  [dianlujitao]

project lineage/mirror/
65fec70  Updated to 25-Apr-2021 12:00 UTC  [Tim Schumacher]

project lineage/wiki/
e3dc817  wiki: devices: promote jason to 18.1  [dianlujitao]

project system/media/
b432f63  Merge tag 'android-11.0.0_r34' staging/lineage-18.1_merge-android-11.0.0_r34  [Michael Bestas]

====================
     2021-04-24    
====================
project packages/apps/Messaging/
07ae0bb  Messaging: Update cellbroadcast package name  [z3DD3r]

====================
     2021-04-23    
====================
project device/xiaomi/markw/
ab1ce57  markw: fakelogprint: resolve unused parameter warnings  [tImIbreakdown]

====================
     2021-04-22    
====================
project frameworks/base/
01b994a  [SQUASH]base: Revert secondary home handle  [Ido Ben-Hur]

project lineage/mirror/
1d702f0  Updated to 22-Apr-2021 00:12 UTC  [Kevin F. Haggerty]
d403946  Updated to 21-Apr-2021 17:55 UTC  [Kevin F. Haggerty]
4a0a5fb  Updated to 21-Apr-2021 17:23 UTC  [Kevin F. Haggerty]
a0ec6ef  Updated to 21-Apr-2021 17:14 UTC  [Kevin F. Haggerty]

project tools/repohooks/
2163340  utils: run: fix crash with failing tools & combined stderr  [Mike Frysinger]

====================
     2021-04-21    
====================
project external/chromium-webview/
729ee65  Update Chromium Webview to 90.0.4430.82  [Kevin F. Haggerty]

project lineage/wiki/
3cd9dc9  wiki: devices: Remove channels flag from Z01R  [razorloves]

project packages/apps/Eleven/
3fe3151  proguard: welcome 2021  [Alexander Martinz]
f2e1a14  Eleven: convert last remaining png icons to svg  [Joey]
1fa2153  Eleven: version: 4.0.1 (401)  [Alexander Martinz]
7250d2e  Eleven: simplify layout  [Joey]
0bc7c61  Eleven: remove unused resources  [Joey]
8ea97f7  Eleven: update playPause button animation  [Joey]
91bc555  Eleven: convert default artwork to svg  [Joey]
e22e9bf  Eleven: AlbumScrimImage: generate drawable for default artwork  [Alexander Martinz]
0c4a3ae  MusicUtils: ensure query parameters are not null  [Alexander Martinz]
bc518e8  !fixup "Eleven: ensure we got proper permissions before initializing"  [Alexander Martinz]
8186899  Eleven: remove dragdrop package  [Joey]
31b872a  Eleven: convert playlist songs list to RecyclerView  [2bllw8]
2fcdb0c  Eleven: convert queue list to RecyclerView  [2bllw8]
e14b7a8  Eleven: Update artist, songs and smart playlists lists to RecyclerView  [2bllw8]
f96b0dc  Eleven: convert playlist list to RecyclerView  [2bllw8]
eadfb42  Eleven: convert albums and artist lists to RecyclerView  [2bllw8]
8181a71  Eleven: use more easy to understand drag drop icons  [2bllw8]
c9b5fde  Eleven: allow to reset to default photo  [2bllw8]
10366aa  Eleven: update to sdk 30  [2bllw8]
c84c8a6  Eleven: AudioPreviewActivity: do not use deprecated APIs for audio focus changes  [2bllw8]
3857e63  Eleven: AudioPreviewActivity: use static handler class  [2bllw8]
f6553f1  Eleven: ViewDragHelper: use Overscroller  [2bllw8]

project packages/apps/Settings/
e333d56  Device picker: add title to fix offset in progressbar  [Timi]
76869b9  ProgressCategory: update title style for consistency  [Timi]

project vendor/lineage/
ea6f9a7  lineage: atv: Disable LiveDisplay  [Nolen Johnson]

====================
     2021-04-20    
====================
project device/qcom/sepolicy-legacy-um/
bf514b8  common: Allow system_app to read fm_radio_device  [Jarl-Penguin]
3f031ba  sdm660: Remove overly broad init rule  [Michael Bestas]
77caf56  Address init denials regarding socket_device  [Aayush Gupta]
04808ca  Use set_prop() macro for property sets  [Michael Bestas]
61b6695  sepolicy: Switch to BOARD_VENDOR_SEPOLICY_DIRS  [Aayush Gupta]
72f52b0  legacy-um: qva: Label dpmd in /system/product/ again  [Aayush Gupta]
c589f05  sdm660: Generate contexts for rtc  [Aayush Gupta]
277f836  Label old telephony extension  [Michael Bestas]
14cb6bc  Label persist.vendor.bluetooth. properties  [Michael Bestas]
c226356  sepolicy : Add rule to set property for wlan driver/fw ver info  [Vinay Gannevaram]
1f12a66  Allow hal_sensors read vendor_sensors_dbg_prop  [Michael Bestas]
4673819  sepolicy: cnd: Conditionally allow access to wifi_prop  [Nolen Johnson]
0ed559b  Sepolicy: add define for lksecapp vbmeta and dtbo  [Arthur Shuai]
e6ac732  sepolicy-legacy-um: Allow Snap to read camera props  [Bruno Martins]
223774b  msm8953: Label additional SSR sysfs  [Michael Bestas]
38bbed0  Label persist/rfs recursively  [Chirayu Desai]
830728c  Allow vendor_init set vendor_time_service_prop  [Michael Bestas]
ef57b0d  sdm660: Label sysfs_uio_file  [Michael Bestas]
32e1a94  sdm660: Label sysfs_ssr_toggle  [Michael Bestas]
85876f8  common: Fix sysfs_socinfo Label for sensors  [Max Weffers]
79bbaeb  common: Label persist.vendor.camera.debug.logfile  [Michael Bestas]
f83b482  sepolicy : msm8998: remove regexp for ssr node on sysfs  [Shashi Shekar Shankar]
62662a5  sepolicy: setting secontext to rtc node  [Mohit Aggarwal]
d5b97a9  sepolicy: Add rw permission for i2c touch sys node  [Amit P Choudhari]
457a62f  msm8998: Label LED sysfs  [Michael Bestas]
136be27  msm8998: Label usbpd sysfs  [Michael Bestas]

project device/qcom/sepolicy_vndr/
805006e  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy_vndr into lineage-18.1  [Michael Bestas]

project hardware/qcom-caf/thermal/
08cefce  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/thermal into lineage-18.1  [Michael Bestas]

project hardware/qcom-caf/wlan/
23c6098  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into lineage-18.1-caf  [Michael Bestas]

project lineage/hudson/
3923d73  hudson: promote Z01R to 18.1  [Marc Bourgoin]

project lineage/mirror/
9ac85ea  Updated aosp-minimal to 20-Apr-2021 12:01 UTC  [Tim Schumacher]

project lineage/wiki/
d2bb499  wiki: devices: promote Z01R to 18.1  [Marc Bourgoin]
1ae994c  wiki: Update signing builds instructions  [LuK1337]

project packages/apps/Eleven/
808fa75  Eleven: PropertiesStore: use try-with-resource  [2bllw8]
b51f0a2  Eleven: use FragmentActivity  [2bllw8]
b0c6002  Eleven: cleanup findById usages  [2bllw8]
6524fc6  Eleven: update android gradle plugin version to 4.1.3  [2bllw8]
cc0bd10  Eleven: use default transaction animations to fragments  [2bllw8]

project vendor/codeaurora/telephony/
4b8a379  Keep old APIs for Auto Reject  [Pranav Vashi]

project vendor/qcom/opensource/commonsys-intf/display/
17b02be  Merge tag 'LA.QSSI.11.0.r1-11400-qssi.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/display-commonsys-intf into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/data-ipa-cfg-mgr/
5acf202  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/power/
46ec6ba  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/power into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/usb/
4692565  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/usb into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/vibrator/
17efe07  Merge tag 'LA.UM.9.12.r1-11000-SMxx50.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/vibrator into lineage-18.1  [Michael Bestas]

====================
     2021-04-19    
====================
project device/qcom/sepolicy-legacy-um/
9bcf8e2  sepolicy: allow vold to read persist dirs  [jrior001]
6305336  Import msm8996 policy from lineage-17.1-legacy-um  [Michael Bestas]
e05c326  sepolicy: Allow mm-qcamerad to access v4L "name" node  [Bruno Martins]
30e84cc  sepolicy: Fix video4linux "name" node labeling  [Bruno Martins]
2b143f3  Use set_prop() macro for property sets  [Michael Bestas]
a826c0b  qcom: Label vendor files with (vendor|system/vendor) instead of vendor  [Rashed Abdel-Tawab]
fdbed5d  sepolicy: Label persist partition for all SoCs  [Michael Bestas]
eb83f6b  sepolicy: Unlabel aux camera whitelist prop  [dianlujitao]
dc1cf5b  sepolicy: Remove rules for non legacy platforms  [Michael Bestas]
1837c80  sepolicy: Include Lineage-specific QCOM sepolicy  [Pig]
7c71fe4  legacy: Fix newline in file_contexts  [Volodymyr Zhdanov]
50983df  sepolicy: Update paths for new repository location  [Michael Bestas]
c0ebb88  sepolicy: Remove QCOM guards  [Pig]

project packages/apps/Updater/
7cfeb81  Updater: Fix exporting updates  [Michael W]

project vendor/codeaurora/telephony/
3905bd4  Merge tag 'LA.QSSI.11.0.r1-11400-qssi.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/audio/
77abc79  Merge tag 'LA.QSSI.11.0.r1-11400-qssi.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/fm-commonsys/
3709d0a  Merge tag 'LA.QSSI.11.0.r1-11400-qssi.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/fm-commonsys into lineage-18.1  [Michael Bestas]

project vendor/qcom/opensource/interfaces/
f50e5c3  Merge tag 'LA.QSSI.11.0.r1-11400-qssi.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into lineage-18.1  [Michael Bestas]

====================
     2021-04-18    
====================
project external/rsync/
1f24516  config: Undef USE_ICONV_OPEN as it segfaults for us  [LuK1337]

project packages/apps/Seedvault/
9794a15  Only treat eng builds as debug  [Chirayu Desai]

