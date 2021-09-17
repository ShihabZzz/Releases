====================
     2021-09-17    
====================
project build/make/
293af06  build: Remove some debugging props  [Henrique Silva]
6e9718c  Use 'release-keys' for build tag  [Sultanxda]

project development/
9e5d29c  make-key: Enforce PBEv1 password-protected signing keys  [Vasyl Gello]

project frameworks/base/
7c6a146  KeyStore: Prevent NPE with trust manager service  [Pranav Vashi]
6e63fb5  base: Improvements for swipe to screenshot  [Henrique Silva]
79ed669  base: SwipeToScreenshot: Import MIUI implementation  [Henrique Silva]
0d0b558  base: Add three-fingers-swipe to screenshot [1/2]  [ghbhaha]
7f110cc  Base: fix facelock crash when lock screen is disabled  [Altaf-Mahdi]
e9267c0  LockSettingsService: Fix face removal when disabling security  [jhenrique09]
5a3af86  configure same GID based APNs as per carrier requirements  [Avinash Nalluri]
f8bd36c  Fix issue: https://issuetracker.google.com/issues/183024999  [Tang Ding]
89b1283  RingtoneManager: Set an default ringtone for the SIM 2  [micky387]
941761a  base: Phone ringtone setting for Multi SIM device [1/3]  [Ting Yu]
54cf49b  SystemUI: Fix Wakelock issue  [Alberto Ponces]
0bda402  LockIcon: Don't cache icon when scanning face  [jhenrique09]
535952f  fixup - [1/2] Allow using face as auth method for apps  [jhenrique09]
11a5c9f  AuthContainerView: fix rare SystemUI crash  [Simão Gomes Viana]
5dc166b  FaceService: Nuke useless call to getAuthenticatorId  [jhenrique09]
f2d895e  Allow using face as auth method for apps  [jhenrique09]
285acd3  cleanup - SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
034a4be  Add isFaceAuthEnabledForUser checks in KeyguardLiftController  [jie shen]
10d866a  SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
17aceee  base: do not use new lockscreen layout for bypass  [Ethan Halsall]
ef68c35  fwb: Guard some functions against face unlock  [jhenrique09]
a9f5ae8  Port face unlock feature  [jhenrique09]
399ff17  Kill off provider info logspam  [Harsh Shandilya]
8e2c193  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
f60d112  core: jni: Switch to -O3  [Simão Gomes Viana]
e85dbdb  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
b6d07f0  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
281ab47  telephony: URI cannot be created with negative subIds  [jlask]
47c4e80  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
fe56a5b  DataSwitchTile: dont show toast on click  [micky387]
c2a3485  DataSwitchTile: collapse notification panel onClick  [DennySPB]
b52f39f  SystemUI: Introduce DataSwitchTile  [Christian Oder]
9627f3e  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
07c9560  SystemUI: Remove build version from qs footer  [Pranav Vashi]
802ea67  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
06cb775  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
d5a4948  base: Add metric for Blinx Settings  [David Trpchevski]
5610308  SystemUI: Add a tile to show power menu  [DarkJoker360]
49c2403  SystemUI: Set brightness slider view restriction from the right thread  [Sultan Alsawaf]
c00412c  More consistently retry system calls on EINTR  [Hans Boehm]
ce34ec6  Use tmpArgBuffer correctly when argBuffer is null  [Wang Han]
1ba20a3  Add dalvik.vm.force-java-zygote-fork-loop  [Hans Boehm]
9217d57  Fix error formatting issues  [Hans Boehm]
9bb6525  Don't fork USAPs with open argument buffer  [Hans Boehm]
3fe36e4  Allow app zygote preload to retain files across fork  [Egor Pasko]
35cedb7  Add zygote native fork loop  [Hans Boehm]
bf35c30  One more Build.FINGERPRINT to Build.DATE change  [maxwen]
7808c06  LayoutInflater: Opportunistically create views directly for performance  [Danny Lin]
f22d50c  SystemServiceRegistry: Replace ArrayMap with HashMap for performance  [Danny Lin]
0b252958f  PackageManagerService: Replace ArrayMap with HashMap for performance  [Danny Lin]
65e72b8  InsetsStateController: Replace ArrayMap with HashMap for performance  [Danny Lin]
8077985  LocalServices: Replace ArrayMap with HashMap for performance  [Danny Lin]
3fced5b  ThemedResourceCache: Replace ArrayMap with HashMap for performance  [Danny Lin]
116fb99  Trace: Disable debug tracing in non-engineering builds  [Danny Lin]
4edb8a3  statsd: Disable native stats collection service  [Danny Lin]
c1df02f  EventLog: Disable event writing in non-engineering builds  [Danny Lin]
fa08c9c  PackageInfo: Optimize ApplicationInfo creation  [Danny Lin]
668126e  Revert "Pre-emptively take a snapshot when finishing an activity before changing visibility"  [Danny Lin]
21578fc  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
3d5f657  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
0da84e5  Implement backup/restore for network policy  [Oliver Scott]
dcd4d9c  Split network policy XML parsing into read/write helper functions  [Oliver Scott]
a19ad13  power: Keep file scheme when not using content URI  [Han Wang]
aace2b4  power: Explicitly check for silent ringtone  [Sam Mortimer]
962bbfc  power: Extend custom charging sounds  [Bruno Martins]
2de4f4f  power: Respect global vibration setting for charging sounds  [Michael Bestas]

project frameworks/opt/net/wifi/
5fe59a7  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
1f072ac  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project lineage-sdk/
f5eb56d  sdk: Add power button qs tile metric  [DarkJoker360]
fabb8ef  lineage: res: Introduce config to declare wireless charging support  [Bruno Martins]
4c6186d  LineageSettings: Deprecate charging sound settings in favor of AOSP ones  [Bruno Martins]

project lineage/hudson/
6b41ac9  Non-QCOM master-race  [Nolen Johnson]

project lineage/wiki/
c8379c7  wiki: devices: Add Moto-Exynos-9610 family  [Nolen Johnson]

project packages/apps/CellBroadcastReceiver/
0e3f54c  CellBroadcastReceiver: Allow framework to do dark theming automatically  [Michael Bestas]

project packages/apps/Dialer/
04660fc  CallRecordingAutoMigrator: Handle all exceptions  [Pranav Vashi]
4ff1ccb  Dialer: Make recording names sortable  [Pranav Vashi]
6b00185  Add autorecord feature  [DennySPB]
c30a22a  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
fb2dad9  Fix selecting phone account dialog show error.  [Grace Jia]

project packages/apps/Gallery2/
ecd2964  Gallery2: Preserve the decimals in coordinates  [George Zacharia]

project packages/apps/LineageParts/
764aeb1  ChargingSoundsSettings: Support wireless charging sounds  [Bruno Martins]
66b6545  ChargingSoundsSettings: Migrate to AOSP settings  [Bruno Martins]
59aa234  ChargingSoundsSettings: Tweak default charging sound path  [Han Wang]

project packages/apps/Seedvault/
aae7458  Disable AOSP K/V Call log backups  [Oliver Scott]

project packages/apps/Settings/
c53731f  Settings: Add three-fingers-swipe to screenshot [2/2]  [ghbhaha]
bd1065b  Settings: Use AOSP translations for MSIM ringtone  [jhenrique09]
942fbe0  Settings: enable SIM card ringtone only if slot not empty  [maxwen]
596ee71  Settings: Phone ringtone setting for Multi SIM device [2/3]  [Ting Yu]
7a2b763  Allow using face as auth method for apps  [jhenrique09]
8a24765  Port faceunlock feature  [jhenrique09]
0be4ec9  Settings: Whitelist WRITE_DEVICE_CONFIG permission  [saikiran2001]
a517706  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Stk/
a9b2a85  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
71145ad  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
9741d58  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
f80bc4f  Update Changelog server URL  [ShihabZzz]
9915b89  Unofficial OTA configuration  [David Trpchevski]

project packages/inputmethods/LatinIME/
3ec96a5  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
c0d8268  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
9b0915b  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
f64e080  Remove webview from the view system before destroying webview  [lucaslin]
f5442c7  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
aa6d140  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/DownloadProvider/
e4cae2d  Improve duplicate file naming scheme  [Timi]

project packages/providers/TelephonyProvider/
15d29f7  MNCs not in carrier_list can get the wrong MNC value  [Mattias Nilsson]
0f22462  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]

project packages/services/Telecomm/
0256c8f  Telecomm: Phone ringtone setting for Multi SIM device [3/3]  [Ting Yu]

project system/bt/
5e3907d  A2DP: Restrict MTU while using SBC middle quality  [Cheney Ni]
c329f63  A2DP: AAC encoder uses same value in tick interval and feeding data  [Cheney Ni]
45d52b0  BluetoothAudioHAL: MTU not exceed an AVDTP packet  [Cheney Ni]
da34598  Fix A2dp encoder counter deviation.  [Daren Liao]
9e987b9  Fix for Multiplication overflow will be crash btstack  [cnx421]

project system/core/
be3e8d8  Shut up camera debug output  [faust93]
44fc316  Filter out QTI performance spam  [DennySPB]
4292622  Silence spammy logs from camera blobs (mm-camera)  [Sultanxda]

project system/sepolicy/
fcdb540  sepolicy: Allow to access zygote sockets from app domain.  [Quallenauge]
d813d31  sepolicy: Allow to receive FDs from app_zygote  [Egor Pasko]

project vendor/lineage/
78e81ea  vendor: Add back FaceUnlock support  [jhenrique09]
3fa940b  overlay: Override config for platform number verification  [Sneh Bansal]
110b2a3  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
53b9ae0  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
b918abd  power: Kill "Failed to acquire lock" log  [Luca Stefani]

project vendor/xiaomi/
4d5deed  markw: Drop libsdm-disp-apis.so  [Sebastiano Barezzi]
8ee6e6a  markw: Drop QCOM WFD  [Marc Bourgoin]

====================
     2021-09-16    
====================
project lineage/wiki/
9ae0dac  Explicitly select the container registry in Dockerfiles  [Tim Schumacher]

project packages/apps/TvSettings/
d0b7690  TvSettings: fix double ripple in Wifi selection  [Timi Rautamäki]

====================
     2021-09-15    
====================
project lineage/hudson/
8f360c4  hudson: Start builds for surya!  [Willy Gardiol]

project lineage/wiki/
3bc629d  wiki: add surya  [Willy Gardiol]
06baae9  Add the `export LC_ALL=C` workaround to the build page  [Tim Schumacher]

project packages/apps/Updater/
81dc120  Updater: follow TwoPanelSettings styling  [Timi Rautamäki]
a96d54f  Updater: initial layout for TV  [Timi Rautamäki]

project vendor/lineage/
bcac3f3  apns: Update Vodafone NL  [Michael W]

====================
     2021-09-14    
====================
project lineage/hudson/
88cde4f  hudson: add SHIFT6mq (axolotl)  [Joey]
a40487a  hudson: Add Lenovo Z5 Pro GT (heart)  [Marc Bourgoin]

project lineage/mirror/
1234809  Updated to 14-Sep-2021 03:00 UTC  [Kevin F. Haggerty]
86adeb7  Updated to 13-Sep-2021 22:29 UTC  [Kevin F. Haggerty]
311628c  Updated to 13-Sep-2021 22:12 UTC  [Kevin F. Haggerty]
0bee845  Updated to 13-Sep-2021 21:45 UTC  [Kevin F. Haggerty]

project lineage/wiki/
e8372af  wiki: add axolotl  [Joey]
70de6d5  wiki: Add Lenovo Z5 Pro GT (heart)  [Marc Bourgoin]

====================
     2021-09-13    
====================
project build/make/
a1a18d4  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project frameworks/base/
b8404be  SystemUI: Unblock gestural navigation on clearScreenshot()  [Timi Rautamäki]
74544b9  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]
1bbd566  Revert "Revert "Detects all activities for whether showing work challenge""  [Chirayu Desai]

project lineage/hudson/
931588f  hudson: Asus -> ASUS  [Alexander Koskovich]

project lineage/mirror/
54a4520  Updated to 13-Sep-2021 12:52 UTC  [Kevin F. Haggerty]

project lineage/wiki/
396d6e0  wiki: Add ASUS ZenFone 8 (sake)  [Alexander Koskovich]
4269d82  wiki: Account for devices with vendor_boot partitions.  [Alexander Koskovich]
c31296e  wiki: Asus -> ASUS  [Alexander Koskovich]

project packages/apps/Seedvault/
ec1120d  Only treat eng builds as debug  [Chirayu Desai]

====================
     2021-09-12    
====================
project device/xiaomi/markw/
ed6793a  markw: Drop libsdm-disp-apis.so  [Sebastiano Barezzi]
e0cfc61  markw: Remove coresight leftovers  [Michael Bestas]
fa9c80a  markw: Drop QCOM WFD  [Marc Bourgoin]
352e79e  Revert "markw: Add veth_ipa_config to modify tcp buffer values"  [ZeeLog]
c8c7352  markw: overlay: Use CarrierConfig CSP boolean.  [Alexander Koskovich]
8d64552  markw: Disable sdm rotator downscaler  [Jorim Jaggi]
a4276fb  markw: overlay: Disable wallpaper zooming  [amanrajOO7]
2e918c5  markw: Remove unused video property  [Rajeshwar Kurapaty]

project frameworks/base/
6945498  Disallow click to partial screenshot right after screenshot is taken  [LuK1337]

====================
     2021-09-11    
====================

====================
     2021-09-10    
====================
project packages/apps/FaceUnlockService/
9b41264  Automatic translation import  [PixelExperience Automation]

project vendor/lineage/
c57312c  apns: Update APNs for Chinese carriers  [Martincz Gao]

====================
     2021-09-09    
====================
project build/make/
564b498  Add support for separate kernels for boot and recovery [2/2]  [marcost2]

project lineage/wiki/
9acc60f  wiki: contributors: Update Committers/Reviewers to match Gerrit  [Nolen Johnson]

project tools/extract-utils/
8b33503  extract_utils: Don't fixup pinned files when they are supposed to be kept  [Arian]
302226b  extract_utils: Display the fixup hash when keeping pinned files  [Arian]

project vendor/lineage/
fad4142  Add support for separate kernels for boot and recovery [1/2]  [marcost2]

====================
     2021-09-08    
====================
project android/
056dae6  manifest: android-11.0.0_r40 -> android-11.0.0_r43  [Kevin F. Haggerty]

project frameworks/base/
5d4222a  Fixed a crash in settings in tts engine selection screen.  [Deve]

project frameworks/native/
11c9e3c  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project lineage/wiki/
5d4e96b  wiki: templates: Update ADB sideload alert tip.  [Alexander Koskovich]

project packages/apps/Nfc/
671a210  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project packages/apps/Settings/
a70ea07  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project packages/apps/Trebuchet/
c8d5010  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project system/bt/
29f5941  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project system/sepolicy/
fd95208  Merge tag 'android-11.0.0_r43' into staging/lineage-18.1_merge-android-11.0.0_r43  [Kevin F. Haggerty]

project vendor/qcom/opensource/commonsys/system/bt/
19a4d6b  SMP: Reject pairing if public_key.x match  [Hansong Zhang]

====================
     2021-09-07    
====================
project frameworks/base/
422769a  fixup! SystemUI: Show bluetooth battery level when available  [Luca Stefani]

project lineage/wiki/
cd32a30  wiki: Bump required FW version for enchilada  [LuK1337]

====================
     2021-09-06    
====================

====================
     2021-09-05    
====================
project lineage/hudson/
17fc61a  hudson: Time to bake sake  [Alexander Koskovich]

project lineage/mirror/
b341340  Updated to 04-Sep-2021 14:46 UTC  [Kevin F. Haggerty]

project packages/apps/SetupWizard/
841512b  SUW: Move re-enabling of status bar to FinishActivity  [Alessandro Astone]
367f321  SUW: restore: Handle RESULT_SKIP from Seedvault  [Alessandro Astone]

====================
     2021-09-04    
====================
project build/make/
a33a4a7  Check for vintf compatiblity early in generation process  [Kelvin Zhang]

project frameworks/av/
d635749  audioflinger: Fix audio for WifiDisplay  [myfluxi]
9009eef  stagefright: Fix buffer handle retrieval in signalBufferReturned  [Angelo G. Del Regno]
11799cf  stagefright: Fix SurfaceMediaSource getting handle from wrong position issue  [zhangbo_a]
535fd9b  libstagefright_wfd: video encoder does not actually release MediaBufferBase when done  [Vladimir Oltean]
930e597  libstagefright_wfd: compilation fixes  [Vladimir Oltean]
7746d18  Partial revert "Move unused classes out of stagefright foundataion"  [Nico]
562c08b  Revert "stagefright: remove Miracast sender code"  [Vladimir Oltean]
9904747  Revert "Removed unused class and its test"  [Vladimir Oltean]

project frameworks/base/
0f31254  fixup! AutoBrightness: Add support for one shot auto-brightness:  [Eamon Powell]

project lineage/mirror/
aadbe8c  Updated to 04-Sep-2021 14:19 UTC  [Kevin F. Haggerty]
87e2f0f  Updated to 04-Sep-2021 14:03 UTC  [Kevin F. Haggerty]
89d66d5  Updated to 04-Sep-2021 13:51 UTC  [Kevin F. Haggerty]

project packages/apps/Settings/
864537e  Settings: Adjust one shot auto-brightness strings  [Eamon Powell]
a643cef  fixup! Settings: Add preference for one shot auto-brightness  [Eamon Powell]

project packages/apps/TvSettings/
a2d9da3  TwoPanelSettings: fix double ripple in Wifi selection  [Timi Rautamäki]
5cfa3fc  TwoPanelSettings: bring back ripple  [Timi Rautamäki]
3a763cf  TwoPanelSettings: improve category title text appearance  [Timi Rautamäki]

project vendor/lineage/
31a8d98  backuptool: Support tab-delimited fstab  [Erik Jensen]

