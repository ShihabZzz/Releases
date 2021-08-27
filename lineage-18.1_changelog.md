====================
     2021-08-27    
====================
project build/make/
ed48ec1  build: Remove some debugging props  [Henrique Silva]
4f032d7  Use 'release-keys' for build tag  [Sultanxda]

project development/
4c940cd  make-key: Enforce PBEv1 password-protected signing keys  [Vasyl Gello]

project frameworks/base/
90c04dd  KeyStore: Prevent NPE with trust manager service  [Pranav Vashi]
6aea9c0  base: Improvements for swipe to screenshot  [Henrique Silva]
389a72b  base: SwipeToScreenshot: Import MIUI implementation  [Henrique Silva]
52e1301  base: Add three-fingers-swipe to screenshot [1/2]  [ghbhaha]
eb658c7  Base: fix facelock crash when lock screen is disabled  [Altaf-Mahdi]
e5bc32d  LockSettingsService: Fix face removal when disabling security  [jhenrique09]
9a57646  configure same GID based APNs as per carrier requirements  [Avinash Nalluri]
75ad5e5  Fix issue: https://issuetracker.google.com/issues/183024999  [Tang Ding]
ffe0723  RingtoneManager: Set an default ringtone for the SIM 2  [micky387]
22364c9  base: Phone ringtone setting for Multi SIM device [1/3]  [Ting Yu]
bd91b50  SystemUI: Fix Wakelock issue  [Alberto Ponces]
aa9c114  LockIcon: Don't cache icon when scanning face  [jhenrique09]
bcbf261  fixup - [1/2] Allow using face as auth method for apps  [jhenrique09]
8975a96  AuthContainerView: fix rare SystemUI crash  [Simão Gomes Viana]
beffd29  FaceService: Nuke useless call to getAuthenticatorId  [jhenrique09]
57b9558  Allow using face as auth method for apps  [jhenrique09]
b37bb7a  cleanup - SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
15bbb21  Add isFaceAuthEnabledForUser checks in KeyguardLiftController  [jie shen]
82c7130  SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
c7bd1f5  base: do not use new lockscreen layout for bypass  [Ethan Halsall]
74394e7  fwb: Guard some functions against face unlock  [jhenrique09]
bc30bd6  Port face unlock feature  [jhenrique09]
19b0a2c  Kill off provider info logspam  [Harsh Shandilya]
542c8ef  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
6fa548a  core: jni: Switch to -O3  [Simão Gomes Viana]
9f52893  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
8fcbced  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
11f9068  telephony: URI cannot be created with negative subIds  [jlask]
73ffb26  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
43f6488  DataSwitchTile: dont show toast on click  [micky387]
bd9c4e3  DataSwitchTile: collapse notification panel onClick  [DennySPB]
1189d39  SystemUI: Introduce DataSwitchTile  [Christian Oder]
8288c47  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
6d5dabe  SystemUI: Remove build version from qs footer  [Pranav Vashi]
37f39ce  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
18e293b  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
e5d6f0b  base: Add metric for Blinx Settings  [David Trpchevski]
a098683  SystemUI: Add a tile to show power menu  [DarkJoker360]
5eb3375  SystemUI: Set brightness slider view restriction from the right thread  [Sultan Alsawaf]
d1675d2  Make battery clickable again in quick QS status  [Marc K]
70c615a  More consistently retry system calls on EINTR  [Hans Boehm]
0fefa7d  Use tmpArgBuffer correctly when argBuffer is null  [Wang Han]
04ebd92  Add dalvik.vm.force-java-zygote-fork-loop  [Hans Boehm]
02fe417  Fix error formatting issues  [Hans Boehm]
1f03407d  Don't fork USAPs with open argument buffer  [Hans Boehm]
8900e30  Allow app zygote preload to retain files across fork  [Egor Pasko]
69785ac  Add zygote native fork loop  [Hans Boehm]
19bd493  One more Build.FINGERPRINT to Build.DATE change  [maxwen]
bf13acf  LayoutInflater: Opportunistically create views directly for performance  [Danny Lin]
a8186cf  SystemServiceRegistry: Replace ArrayMap with HashMap for performance  [Danny Lin]
7727896  PackageManagerService: Replace ArrayMap with HashMap for performance  [Danny Lin]
fb5ada3  InsetsStateController: Replace ArrayMap with HashMap for performance  [Danny Lin]
9ec4554  LocalServices: Replace ArrayMap with HashMap for performance  [Danny Lin]
f6d4ca6  ThemedResourceCache: Replace ArrayMap with HashMap for performance  [Danny Lin]
15e2291  Trace: Disable debug tracing in non-engineering builds  [Danny Lin]
562c44b  statsd: Disable native stats collection service  [Danny Lin]
a024c8c  EventLog: Disable event writing in non-engineering builds  [Danny Lin]
efe1322  PackageInfo: Optimize ApplicationInfo creation  [Danny Lin]
02bad91  Revert "Pre-emptively take a snapshot when finishing an activity before changing visibility"  [Danny Lin]
c6e5a0c  Fixed a crash in settings in tts engine selection screen.  [Deve]
54313ae  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
5eaf91d  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
a4ad35c  Implement backup/restore for network policy  [Oliver Scott]
7b69752  Split network policy XML parsing into read/write helper functions  [Oliver Scott]
221a213  power: Keep file scheme when not using content URI  [Han Wang]
69b0cbd  power: Explicitly check for silent ringtone  [Sam Mortimer]
bacc5a3  power: Extend custom charging sounds  [Bruno Martins]
3a73731  power: Respect global vibration setting for charging sounds  [Michael Bestas]

project frameworks/opt/net/wifi/
75bc066  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
0416daf  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project hardware/qcom-caf/msm8996/display/
e0a88b0  gralloc: Remove unused variable  [xNombre]
26f8f84  display-commonsys-intf: Remove gralloc warnings  [Jabiyeff]
49a0738  display-commonsys-intf: suppress log spam  [ZeeLog]
7adbcb5  display: Drop LOCAL_COPY_HEADERS usage  [Pig]
1345bbb  hwc2,libdisplayconfig: Remove libhwbinder/libhidltransport deps  [Steven Moreland]
1227d8c  Don't build lights module if vendor supplies it  [Steve Kondik]
d705104  display: Use project pathmap  [Ethan Chen]
3582f27  Checkout 'display-commonsys-intf' from LA.UM.9.6.2.r1-04200-89xx.0  [ShihabZzz]

project hardware/qcom-caf/msm8996/media/
8999705  media: Switch to display_headers lib include  [Bruno Martins]
12d7d30  media: Drop LOCAL_COPY_HEADERS usage  [Pig]
1a09786  media: Don't link libgpustats  [Ethan Chen]
3194a18  media: Add extrapolated gpustats header for PQ  [Rashed Abdel-Tawab]
44593ae  media: libOmxSw encoders require prop headers :(  [Ricardo Cerqueira]
38d2d8d  venc: Fix VQZip issue  [Steve Kondik]
02ef37b  media: Use project pathmap  [Ethan Chen]

project lineage-sdk/
4590210  sdk: Add power button qs tile metric  [DarkJoker360]
34187f1  lineage: res: Introduce config to declare wireless charging support  [Bruno Martins]
f9d9be0  LineageSettings: Deprecate charging sound settings in favor of AOSP ones  [Bruno Martins]

project packages/apps/CellBroadcastReceiver/
2d223b8  CellBroadcastReceiver: Allow framework to do dark theming automatically  [Michael Bestas]

project packages/apps/Dialer/
c9dd7a4  CallRecordingAutoMigrator: Handle all exceptions  [Pranav Vashi]
ba4ceda  Dialer: Make recording names sortable  [Pranav Vashi]
5c02fae  Add autorecord feature  [DennySPB]
39fa51b  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
01df62f  Fix selecting phone account dialog show error.  [Grace Jia]

project packages/apps/Gallery2/
a143103  Gallery2: Preserve the decimals in coordinates  [George Zacharia]

project packages/apps/LineageParts/
4eac442  ChargingSoundsSettings: Support wireless charging sounds  [Bruno Martins]
8e9b565  ChargingSoundsSettings: Migrate to AOSP settings  [Bruno Martins]
59f9ba7  ChargingSoundsSettings: Tweak default charging sound path  [Han Wang]

project packages/apps/Seedvault/
111bdaf  Don't hide navigation bar in setup wizard  [Michael Bestas]
79f5e41  Disable Nextcloud restore when not installed and no store available  [Michael Bestas]
4b2d82a  Only treat eng builds as debug  [Chirayu Desai]

project packages/apps/Settings/
fba3775  Settings: Add three-fingers-swipe to screenshot [2/2]  [ghbhaha]
f9f5fb4  Settings: Use AOSP translations for MSIM ringtone  [jhenrique09]
0f86941  Settings: enable SIM card ringtone only if slot not empty  [maxwen]
7b1b4d0  Settings: Phone ringtone setting for Multi SIM device [2/3]  [Ting Yu]
33fcece  Allow using face as auth method for apps  [jhenrique09]
113d1bc  Port faceunlock feature  [jhenrique09]
9c188c2  Settings: Migrate one shot auto-brightness strings  [Eamon Powell]
202c63c  Settings: default to GlifV3Theme  [Timi Rautamäki]
02cd6f5  Settings: Whitelist WRITE_DEVICE_CONFIG permission  [saikiran2001]
7d54a96  Use our string for restrict_background  [Chirayu Desai]
b0ed292  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Stk/
bb14da7  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
ef961fe  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
8ad00af  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
ac22c51  Update Changelog server URL  [ShihabZzz]
64a710d  Unofficial OTA configuration  [David Trpchevski]

project packages/inputmethods/LatinIME/
c168b41  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
85955b9  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
acbb680  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
dceaa2b  Remove webview from the view system before destroying webview  [lucaslin]
8eb1a90  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
7dc6e42  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/DownloadProvider/
b1b9a3f  Improve duplicate file naming scheme  [Timi]

project packages/providers/TelephonyProvider/
ab41a56  MNCs not in carrier_list can get the wrong MNC value  [Mattias Nilsson]
d4ed30d  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]

project packages/services/Telecomm/
19ece86  Telecomm: Phone ringtone setting for Multi SIM device [3/3]  [Ting Yu]

project system/bt/
93b34e2  A2DP: Restrict MTU while using SBC middle quality  [Cheney Ni]
2f651f8  A2DP: AAC encoder uses same value in tick interval and feeding data  [Cheney Ni]
c8087a8  BluetoothAudioHAL: MTU not exceed an AVDTP packet  [Cheney Ni]
633d7b9  Fix A2dp encoder counter deviation.  [Daren Liao]
32b9595  Fix for Multiplication overflow will be crash btstack  [cnx421]

project system/core/
57f25c9  Shut up camera debug output  [faust93]
96d56a2  Filter out QTI performance spam  [DennySPB]
7d9a225  Silence spammy logs from camera blobs (mm-camera)  [Sultanxda]

project system/netd/
31cc3b7  bw: Always apply penalty box  [Chirayu Desai]

project vendor/lineage/
f400592  vendor: Add back FaceUnlock support  [jhenrique09]
7a31009  overlay: Override config for platform number verification  [Sneh Bansal]
fc7d382  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
810fe03  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
eb8fe59  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-08-26    
====================
project device/xiaomi/markw/
9817fad  markw: Disable camera gyroscope feature  [Isaac Chen]
afd92a6  markw: Update graphics firmware from Daisy  [ZeeLog]
657c939  markw: Update Audio/BT/Listen from Daisy V11.0.21.0.QDLMIXM  [ShihabZzz]
c10ff57  markw: move media configs to separate folder  [ZeeLog]
99a89cb  markw: copy out v1 codec and performance xml  [Paras Nagda]
8318a03  markw: Remove unused TARGET_NO_RPC flag  [Michael Bestas]
1798abf  markw: Drop USE_DEVICE_SPECIFIC_{GPS}  [Wang Han]
94816aa  markw: Nuke deprecated bluetooth flag  [Erfan Abdi]
20e5871  markw: move RLIMIT_MEMLOCK to init.target.rc  [ZeeLog]
b7ed227  markw: Remove cpusets setup  [Artem Borisov]
2d6dc1c  markw: move camera daemon cpuset settings to boot section  [ZeeLog]
c0992ac  markw: Remove no longer existing BT props  [Arne Coucheron]
08b6c5a  markw: Configure Zram on all devices, if enabled  [Adam Farden]

project vendor/xiaomi/
40fb277  markw: Update graphics firmware from Daisy V11.0.21.0.QDLMIXM  [ZeeLog]
a12b7eb  markw: Update Audio/BT/Listen from Daisy V11.0.21.0.QDLMIXM  [ShihabZzz]

====================
     2021-08-25    
====================
project packages/apps/Etar/
e640218  Divider color fixes (#973)  [Kavita Patil]
9539704  Fixed crash of WeekView, Agenda, Settings & MonthView screens when calendar permission is not given (#965)  [Kavita Patil]
043c90b  updated build settings for more aggressive CPU and memory utilization  [Sergey Parshin]
abebf06  Bugfix Release  [Gitsaibot]
7db07e2  Refresh view only when themePref "system" is selected (#941)  [Gitsaibot]
0289951  Home time zone setting grayed out if not enabled  [Gitsaibot]
b1eea5c  Bump kotlinx-coroutines-core from 1.5.0 to 1.5.1  [dependabot[bot]]
1230f9a  Bump kotlinx-coroutines-android from 1.5.0 to 1.5.1  [dependabot[bot]]
4ecfef0  Bump gradle from 4.2.1 to 4.2.2  [dependabot[bot]]
b4d9ec5  Bump material from 1.3.0 to 1.4.0  [dependabot[bot]]
3de0725  Bump kotlin_version from 1.5.0 to 1.5.20  [dependabot[bot]]
756efac  Replace dip with sp in event info text size  [04cfb1ed]
b86f79c  Avoid text overlapping in start, end date fields (#946)  [04cfb1ed]
12e5b75  Update submodules  [Jochen Sprickerhof]

project packages/apps/Seedvault/
78cda94  Disable AOSP K/V Call log backups  [Oliver Scott]
e0d53f4  Merge branch 'android11' of https://github.com/seedvault-app/seedvault into lineage-18.1  [Michael Bestas]

project packages/providers/ContactsProvider/
015e107  Move Call Log backup back to ContactsProvider  [Oliver Scott]

====================
     2021-08-24    
====================
project frameworks/base/
0071222  AutoBrightness: Add support for one shot auto-brightness:  [Cédric Bellegarde]

project lineage-sdk/
6e7936c  lineage-sdk: Add preference keys for one shot auto-brightness  [Cédric Bellegarde]

project lineage/mirror/
c45da7b  Updated aosp-minimal to 24-Aug-2021 12:01 UTC  [Tim Schumacher]

project packages/apps/Settings/
ffd8671  Settings: Add preference for one shot auto-brightness  [Cédric Bellegarde]

project tools/extract-utils/
72d5bdf  fixup! extract_utils: Add support for overriding packages  [LuK1337]
3749ce5  extract_utils: Add support for overriding packages  [TheStrix]

project vendor/lineage/
d5b4b59  kernel: Fix vdso32 building for 4.19+ kernels  [LibXZR]

====================
     2021-08-23    
====================
project device/qcom/sepolicy-legacy-um/
a790801  legacy: Resolve more surfaceflinger related denial  [ShihabZzz]
f5f98d1  Allow surfaceflinger to search hal_graphics_composer_default  [ChengYou Ho]

project kernel/xiaomi/markw/
93e2d09  wireguard: crypto: curve25519-x86_64: solve register constraints with reserved registers  [Mathias Krause]
6579e4c  wireguard: compat: account for grsecurity backports and changes  [Mathias Krause]
65e2880  markw/arch: Remove pstore support...  [ShihabZzz]

project packages/apps/Messaging/
07958b8  Automatic translation import  [Michael Bestas]

project tools/extract-utils/
eed0c8c  extract_utils: Skip colored echo when piped  [Bruno Martins]
f12ce8b  extract_utils: Add a bit of color to the output  [Bruno Martins]
ac8ec32  extract_utils: Introduce colored echo helper function  [Bruno Martins]

project vendor/lineage/
38f3891  lineage: config: DEVICE_PACKAGE_OVERLAYS -> PRODUCT_PACKAGE_OVERLAYS  [Alexander Koskovich]
393b0e8  lineage: overlay: Remove MMS user agent URL  [Alexander Koskovich]

project vendor/qcom/opensource/usb/
561ce41  usb: Add USB Soong namespace to product makefile.  [Alexander Koskovich]

====================
     2021-08-22    
====================

====================
     2021-08-21    
====================
project frameworks/base/
8a27e35  Automatic translation import  [Michael Bestas]

project lineage-sdk/
ce85343  Automatic translation import  [Michael Bestas]

project lineage/mirror/
32d1156  Updated aosp-minimal to 21-Aug-2021 12:01 UTC  [Tim Schumacher]

project packages/apps/AudioFX/
3eaa8f2  Automatic translation import  [Michael Bestas]

project packages/apps/Bluetooth/
de55f17  Automatic translation import  [Michael Bestas]

project packages/apps/Camera2/
a4c840a  Automatic translation import  [Michael Bestas]

project packages/apps/CellBroadcastReceiver/
5ff5102  Automatic translation import  [Michael Bestas]

project packages/apps/CertInstaller/
6a116c7  Automatic translation import  [Michael Bestas]

project packages/apps/Contacts/
631ce50  Automatic translation import  [Michael Bestas]

project packages/apps/DeskClock/
b3433a2  Automatic translation import  [Michael Bestas]

project packages/apps/Dialer/
087d382  Automatic translation import  [Michael Bestas]

project packages/apps/DocumentsUI/
ea74df8  Automatic translation import  [Michael Bestas]

project packages/apps/Eleven/
7c8a3fd  Automatic translation import  [Michael Bestas]

project packages/apps/EmergencyInfo/
00a46ad  Automatic translation import  [Michael Bestas]

project packages/apps/Etar/
57ca7e4  Automatic translation import  [Michael Bestas]

project packages/apps/ExactCalculator/
6d116dd  Automatic translation import  [Michael Bestas]

project packages/apps/FMRadio/
608e0ec  Automatic translation import  [Michael Bestas]

project packages/apps/Gallery2/
211d328  Automatic translation import  [Michael Bestas]

project packages/apps/Jelly/
c7ed0f4  Automatic translation import  [Michael Bestas]

project packages/apps/KeyChain/
a468317  Automatic translation import  [Michael Bestas]

project packages/apps/LineageParts/
fe58be2  Automatic translation import  [Michael Bestas]

project packages/apps/ManagedProvisioning/
9c15a20  Automatic translation import  [Michael Bestas]

project packages/apps/Nfc/
bd2b598  Automatic translation import  [Michael Bestas]

project packages/apps/PermissionController/
5eb248b  Automatic translation import  [Michael Bestas]

project packages/apps/PhoneCommon/
ee0931a  Automatic translation import  [Michael Bestas]

project packages/apps/Recorder/
4b283d7  Automatic translation import  [Michael Bestas]

project packages/apps/Settings/
38fbd1a  Automatic translation import  [Michael Bestas]

project packages/apps/SetupWizard/
d23252f  Automatic translation import  [Michael Bestas]

project packages/apps/Snap/
e8a3152  Automatic translation import  [Michael Bestas]

project packages/apps/Stk/
39afae2  Automatic translation import  [Michael Bestas]

project packages/apps/StorageManager/
4eab62c  Automatic translation import  [Michael Bestas]

project packages/apps/Tag/
1ff8f98  Automatic translation import  [Michael Bestas]

project packages/apps/Terminal/
1849511  Automatic translation import  [Michael Bestas]

project packages/apps/ThemePicker/
22b9ec1  Automatic translation import  [Michael Bestas]

project packages/apps/Trebuchet/
cda2204  Automatic translation import  [Michael Bestas]

project packages/apps/TvSettings/
6fc5eb7  Automatic translation import  [Michael Bestas]

project packages/apps/Updater/
6e5bbda  Automatic translation import  [Michael Bestas]

project packages/apps/WallpaperPicker2/
5d60b1a  Automatic translation import  [Michael Bestas]

project packages/inputmethods/LatinIME/
d4c6ca8  Automatic translation import  [Michael Bestas]

project packages/modules/CaptivePortalLogin/
ba02a0d  Automatic translation import  [Michael Bestas]

project packages/providers/BlockedNumberProvider/
1898cec  Automatic translation import  [Michael Bestas]

project packages/providers/CalendarProvider/
1c6dfbb  Automatic translation import  [Michael Bestas]

project packages/providers/DownloadProvider/
c23a1bf  Automatic translation import  [Michael Bestas]

project packages/providers/MediaProvider/
7f3c7ea  Automatic translation import  [Michael Bestas]

project packages/resources/devicesettings/
b259f67  Automatic translation import  [Michael Bestas]

project packages/services/BuiltInPrintService/
b5c1eed  Automatic translation import  [Michael Bestas]

project packages/services/Telecomm/
617d40d  Automatic translation import  [Michael Bestas]

project packages/services/Telephony/
53e0d10  Automatic translation import  [Michael Bestas]

project packages/wallpapers/LivePicker/
d374960  Automatic translation import  [Michael Bestas]

project vendor/qcom/opensource/fm-commonsys/
8920992  Automatic translation import  [Michael Bestas]

====================
     2021-08-20    
====================

====================
     2021-08-19    
====================
project external/chromium-webview/
b58d049  Update Chromium Webview to 92.0.4515.159  [Kevin F. Haggerty]

project lineage/mirror/
8c22d3b  Updated aosp-minimal to 19-Aug-2021 12:02 UTC  [Tim Schumacher]

project lineage/scripts/
36798f0  Update default webview to 92.0.4515.159  [Kevin F. Haggerty]

====================
     2021-08-18    
====================
project lineage/mirror/
5471ac2  Updated aosp-minimal to 18-Aug-2021 01:08 UTC  [Tim Schumacher]

====================
     2021-08-17    
====================

====================
     2021-08-16    
====================

====================
     2021-08-15    
====================
project lineage/wiki/
2c7a49a  wiki: zippo: Add required Android 11 FW  [Marc Bourgoin]

====================
     2021-08-14    
====================
project lineage/wiki/
b1990da  wiki: Mention supported firmware version in firmware_update_oneplus_fastbootd  [LuK1337]

