====================
     2021-05-19    
====================
project android/
eebba81  Call time on Terminal and libvterm.  [Elliott Hughes]

project build/make/
804449f  build: Remove some debugging props  [Henrique Silva]
f4d70b3  Use 'release-keys' for build tag  [Sultanxda]

project device/lineage/sepolicy/
7916f95  selinux: Introduce Applock [3/3]  [rituj]

project device/xiaomi/markw/
4ca415d  markw: Drop no longer needed libCB.so  [ZeeLog]
afe5402  markw: Drop deprecated OpenGLRenderer props  [Bruno Martins]
db74070  markw: Trim QTI whitelists  [Bruno Martins]
787c053  markw: qcc-tr: define new AID for qcc-trd  [Shawn Shin]
6c8d8b4  markw: overlay: Configure SQLite to operate in MEMORY mode  [Jesse Chan]
a305fe5  markw: camera: build 32-bit android.frameworks.displayservice@1.0  [Pranav Vashi]
5f00c1d  markw: media_profiles: msm8953: Remove 2k and qhd profiles  [Sanjay Singh]
a29b67a  markw: init.qcom.rc: create directory for wifihal service  [Vinay Gannevaram]
506e3c2  markw: init: cleanup location services entries  [ZeeLog]
33658b7  markw: add edgnss socket directory  [Hoss Zhou]
cc61866  markw: Add veth_ipa_config to modify tcp buffer values  [Pavan Kumar M]
56768a2  markw: Remove com.qualcomm.qti.presenceappSub2 from whitelist  [Pavan Kumar M]
5628afa  markw: Enable blurs, under dev-option  [Lucas Dupin]

project frameworks/base/
8813d51  base: Improvements for swipe to screenshot  [Henrique Silva]
a27392a  base: SwipeToScreenshot: Import MIUI implementation  [Henrique Silva]
3b768db  base: Add three-fingers-swipe to screenshot [1/2]  [ghbhaha]
970f14a  Base: fix facelock crash when lock screen is disabled  [Altaf-Mahdi]
25117f7  LockSettingsService: Fix face removal when disabling security  [jhenrique09]
dea9a81  configure same GID based APNs as per carrier requirements  [Avinash Nalluri]
e9cb410  Fix issue: https://issuetracker.google.com/issues/183024999  [Tang Ding]
ad2c1c8  RingtoneManager: Set an default ringtone for the SIM 2  [micky387]
5740276  base: Phone ringtone setting for Multi SIM device [1/3]  [Ting Yu]
58a9122  base: applock: Check current and called activity package before locking again  [Pranav Kapoor]
c97aa9a  base: applock: Add option to instantly lock app on closing [1/2]  [Pranav Kapoor]
9e78d5f  base: AppLock: Call activityStopped when activity has stopped  [Rituj Beniwal]
c37cd84  base: Introduce Applock [1/3]  [rituj]
6200eae  SystemUI: Fix Wakelock issue  [Alberto Ponces]
ba86515  BrightnessController: Fix thread exception  [jhenrique09]
ff43918  LockIcon: Don't cache icon when scanning face  [jhenrique09]
848c003  AuthBiometricFingerprintView: Fix indicator text color on dark theme  [jhenrique09]
b4995f5  fixup - [1/2] Allow using face as auth method for apps  [jhenrique09]
13eace6  AuthContainerView: fix rare SystemUI crash  [Simão Gomes Viana]
b5e215c  FaceService: Nuke useless call to getAuthenticatorId  [jhenrique09]
506a226  Allow using face as auth method for apps  [jhenrique09]
81ba4ff  cleanup - SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
3187758  Add isFaceAuthEnabledForUser checks in KeyguardLiftController  [jie shen]
162b863  SystemUI: Allow listening for face only on pin/pass view  [jhenrique09]
1c7ce0c3  base: do not use new lockscreen layout for bypass  [Ethan Halsall]
e0c6508  fwb: Guard some functions against face unlock  [jhenrique09]
ea9ead8  Port face unlock feature  [jhenrique09]
0262e1d  Kill off provider info logspam  [Harsh Shandilya]
4ede679  SystemServer: Only enable fd leak tracker on eng  [Simão Gomes Viana]
b07803f  core: jni: Switch to -O3  [Simão Gomes Viana]
0abc230  ActivityManagerService: dont be so hectic on cpu battery stats  [Simao Gomes Viana]
2ec3acc  base: SystemUI: Allow user to add/remove QS with one click  [Andrzej Ressel]
1c97b25  telephony: URI cannot be created with negative subIds  [jlask]
dbcfa89  TelephonyRegistry: Avoid adding duplicate listener  [Wileen Chiu]
68ea886  DataSwitchTile: dont show toast on click  [micky387]
7b8cd97  DataSwitchTile: collapse notification panel onClick  [DennySPB]
bec9216  SystemUI: Introduce DataSwitchTile  [Christian Oder]
d69a3f7  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
572071f  SystemUI: Remove build version from qs footer  [Pranav Vashi]
87f55ab  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
d680435b  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
3c53764  base: Add metric for Blinx Settings  [David Trpchevski]
05a41b5  SystemUI: Add a tile to show power menu  [DarkJoker360]
d667e19  LayoutInflater: Opportunistically create views directly for performance  [Danny Lin]
3213683  SystemServiceRegistry: Replace ArrayMap with HashMap for performance  [Danny Lin]
cd29df8  PackageManagerService: Replace ArrayMap with HashMap for performance  [Danny Lin]
afd6141  InsetsStateController: Replace ArrayMap with HashMap for performance  [Danny Lin]
6b29953  LocalServices: Replace ArrayMap with HashMap for performance  [Danny Lin]
debbc42  ThemedResourceCache: Replace ArrayMap with HashMap for performance  [Danny Lin]
b00ff90  Trace: Disable debug tracing in non-engineering builds  [Danny Lin]
23cb6b9  statsd: Disable native stats collection service  [Danny Lin]
582b5c7  EventLog: Disable event writing in non-engineering builds  [Danny Lin]
ecf124d  PackageInfo: Optimize ApplicationInfo creation  [Danny Lin]
3c629f2  Revert "Pre-emptively take a snapshot when finishing an activity before changing visibility"  [Danny Lin]
961a9dc  AutoBrightness: Add support for one shot auto-brightness:  [Cédric Bellegarde]
2419c05  Make isUidIsolated public  [Oliver Scott]
ab16da0  Implement backup/restore for network policy  [Oliver Scott]
71d12ca  Split network policy XML parsing into read/write helper functions  [Oliver Scott]
4cfedba  SystemUI: VolumeDialog: Improve expandable volumepanel  [althafvly]
1064d4b  Fixed a crash in settings in tts engine selection screen.  [Deve]
5a40031  EasterEgg: Fix some warnings  [Michael W]
3ac21cd  Don't enable extra StrictMode features for userdebug builds  [Sultan Alsawaf]
473d48d  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
2ad044f  SystemUI: Remove unused resources  [Michael Bestas]
854f836  LockIcon: refresh icon on overlay changes  [Dil3mm4]
7204457  Properly set fonts and icons on keyguard when changing styles  [ezio84]
051f62d  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
19a9f0e  screenrec: Show dialog on bottom  [El Dainosor]
d83192d  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
8957a53  power: Re-introduce custom charging sounds  [Bruno Martins]
d588c3a  GlobalActionsDialog: Remove broken PhoneStateListener for airplane mode toggle  [Gegham Zakaryan]
e405dfe  frameworks: New Users dialog for GlobalActions  [Gegham Zakaryan]
e2ea580  frameworks: Add tunable for GlobalActions configuration  [Gegham Zakaryan]
6b9f529  frameworks: Power menu customizations for R  [Gegham Zakaryan]

project frameworks/opt/net/wifi/
6580f65  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
259185e  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project lineage-sdk/
1eee43d  sdk: Add power button qs tile metric  [DarkJoker360]
4208112  lineage-sdk: Add preference keys for one shot auto-brightness  [Cédric Bellegarde]
6ea70c6  LineageSettingsProvider: Mark lookup features as deprecated  [Bruno Martins]
1281d2c  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/mirror/
bba232e  Updated aosp-minimal to 19-May-2021 12:01 UTC  [Tim Schumacher]

project packages/apps/Dialer/
5c636f3  CallRecordingAutoMigrator: Handle all exceptions  [Pranav Vashi]
a64dcde  Dialer: Make recording names sortable  [Pranav Vashi]
1f3e617  Add autorecord feature  [DennySPB]
fb00cc3  Dialer: use black/white navigation colors  [Timi]
e04587a  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
3986431  Dialer: Remove unused resources  [Michael Bestas]
e1a9b6d  Fix selecting phone account dialog show error.  [Grace Jia]

project packages/apps/Eleven/
7b0ba02  Eleven: Settings: add "About" category and show version of app  [Alexander Martinz]
d8cc6df  ImageCache: tweak configuration  [Alexander Martinz]
fde6b97  ElevenUtils: remove forceSerial from #execute()  [Alexander Martinz]
23ddacc  ElevenUtils: remove custom RejectedExecutionHandler  [Alexander Martinz]
82ccc34  PreferenceUtils: remove usage of AsyncTask  [Alexander Martinz]

project packages/apps/LineageParts/
c78b331  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
8343df0  Messaging: Remove unused resources  [Michael Bestas]

project packages/apps/Seedvault/
313757c  Only treat eng builds as debug  [Chirayu Desai]
ca0fc98  Switch all text references to github.com/seedvault-app  [Michael Bestas]
fbbd5b1  Disable AOSP K/V Call log backups  [Oliver Scott]

project packages/apps/Settings/
5e56ae7  Settings: Add three-fingers-swipe to screenshot [2/2]  [ghbhaha]
afe22be  Settings: Add option to instantly lock app on closing [2/2]  [Pranav Kapoor]
200b598  Settings: Use AOSP translations for MSIM ringtone  [jhenrique09]
5b03c4b  Settings: enable SIM card ringtone only if slot not empty  [maxwen]
eafa07e  Settings: Phone ringtone setting for Multi SIM device [2/3]  [Ting Yu]
65044d1  Settings: Introduce Applock [2/3]  [rituj]
70fe3b2  Allow using face as auth method for apps  [jhenrique09]
ad00c5e  Port faceunlock feature  [jhenrique09]
e49e8e2  Settings: Add preference for one shot auto-brightness  [Cédric Bellegarde]
e79759e  Use our string for restrict_background  [Chirayu Desai]
044a6e8  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/SetupWizard/
4f46bfd  Add gesture to skip setup wizard  [Oliver Scott]
9f86053  Add button to setup eSIM on missing SIM page  [Oliver Scott]
d99525f  Fix SimMissingActivity never showing  [Oliver Scott]

project packages/apps/Stk/
694a448  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
58a5ef3  Trebuchet: Fix NPE when swiping up widgets ...  [Joey]
9150ceb  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]

project packages/apps/Updater/
1825d88  Update Changelog server URL  [ShihabZzz]
3290dcc  Unofficial OTA configuration  [David Trpchevski]

project packages/inputmethods/LatinIME/
c8b616a  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
65f4903  LatinIME: Enable full flag emoji support  [George Zacharia]

project packages/modules/CaptivePortalLogin/
0514741  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
9f1caf5  Remove webview from the view system before destroying webview  [lucaslin]
04ce1bc  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
f8f5f1c  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/TelephonyProvider/
5912f88  Mcc and mnc from xml in RRO may be integers  [Mattias Nilsson]

project packages/services/Telecomm/
f2b15d5  Telecomm: Phone ringtone setting for Multi SIM device [3/3]  [Ting Yu]

project system/core/
44f8866  Filter out QTI performance spam  [DennySPB]
049c418  Silence spammy logs from camera blobs (mm-camera)  [Sultanxda]

project system/netd/
e135f36  bw: Always apply penalty box  [Chirayu Desai]

project vendor/lineage/
39d2cf8  vendor: Add back FaceUnlock support  [jhenrique09]
2e60358  config: Don't build Terminal  [Luca Stefani]
96191c2  overlay: Override config for platform number verification  [Sneh Bansal]
d34c322  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
32d0381  config: Add globalactions service permissions  [Gegham Zakaryan]
39c30b5  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
39bacec  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
d2fdd10  power: Kill "Failed to acquire lock" log  [Luca Stefani]

project vendor/xiaomi/
17ecc14  markw: Drop no longer needed libCB.so  [ZeeLog]

====================
     2021-05-18    
====================
project packages/apps/Settings/
45c2085  Settings: remove Bluetooth related text from DNS-dialog  [Timi Rautamäki]

project packages/apps/Trebuchet/
6cde7ce  Trebuchet: Set 5x6 grid to 5 hotseat icons  [Sam Mortimer]

project system/vold/
3a62ded  Revert "Switch to exfatprogs compatible fsck parameter"  [Luca Stefani]

project vendor/lineage/
fb45458  Fix voicemail for Bouygues Telecom France  [Gnumdk]

====================
     2021-05-17    
====================
project android/
3b3bee1  android: Update source control tools reference  [Aayush Gupta]

project lineage/wiki/
1332fd1  Revert "templates: fastboot_ab: Don't expect user to boot recovery at this stage"  [Nolen Johnson]

project packages/apps/Bluetooth/
fb65cb7  Bluetooth: sync dialog layout for consistency  [Timi]
ed86fed  Bluetooth: follow system theme in dialogs  [Timi]

project packages/resources/devicesettings/
359ceb0  devicesettings: Add strings for "Disabled" + wake on pick-up  [LuK1337]

====================
     2021-05-16    
====================
project frameworks/base/
de06a3c  FODCircleView: Hide fod when screen is off  [AdarshGrewal]
ff120e6  Automatic translation import  [LineageOS Builder]

project lineage-sdk/
a0aac8b  lineage-sdk: Add LineageGlobalActions service  [Gegham Zakaryan]
bcdb265  lineage-sdk: Follow AOSP order of PowerMenuConstants  [Gegham Zakaryan]
43ebae3  Revert "sdk: Deprecate POWER_MENU_ACTIONS"  [Gegham Zakaryan]
3a38117  Automatic translation import  [LineageOS Builder]

project lineage/hudson/
108bed2  hudson: Ship Zenfone Max M2  [danascape]

project lineage/wiki/
490e574  wiki: Add Asus Zenfone Max M2 (X01AD)  [danascape]

project packages/apps/Etar/
00e00b3  Automatic translation import  [LineageOS Builder]

project packages/apps/LineageParts/
983b7cb  PowerMenuActions: Add emergency option  [Gegham Zakaryan]
046484d  PowerMenuActions: Add more checks for bugreport and lockdown option states  [Gegham Zakaryan]
6546cd5  PowerMenuActions: Move methods to SDK service  [Gegham Zakaryan]
3966161  Revert "LineageParts: Drop power menu actions settings"  [Gegham Zakaryan]
149e258  Automatic translation import  [LineageOS Builder]

project packages/apps/Settings/
4ad2d4e  Automatic translation import  [LineageOS Builder]

project packages/apps/Snap/
5f4ccfb  Automatic translation import  [LineageOS Builder]

====================
     2021-05-15    
====================
project device/lineage/sepolicy/
13c250d  sepolicy: Add policy for globalactions service  [Gegham Zakaryan]

project frameworks/base/
5921a43  ReadingModeTile: Drop dependency on wellbeing app  [Bruno Martins]

project lineage/mirror/
0d59b46  Updated to 14-May-2021 17:17 UTC  [Kevin F. Haggerty]

project lineage/wiki/
1b5eabf  wiki: Update `peripherals` for OnePlus 6->8  [LuK1337]

project packages/apps/LineageParts/
549117e  LiveDisplaySettings: Unlock Reading Mode whenever is possible  [Bruno Martins]

project packages/apps/Settings/
0491b67  Version info: make Lineage specific entries not selectable  [Timi]

====================
     2021-05-14    
====================
project frameworks/base/
b0675ce  VolumeDialogImpl: Get the location in window instead of on screen  [HrX03]
678a06b  VolumeDialogImpl: Remove insets listener on dismiss  [HrX03]
c380560  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]

project lineage-sdk/
6fe262a  lineage-sdk: Disallow KILL_APP action when task is pinned  [LuK1337]

project lineage/hudson/
a4f8a56  hudson: Promote X00TD & X01BD to 18.1  [Vivekachooz]

project lineage/wiki/
67a4dc6  wiki: Bump YTX703L/YTX703F to 18.1  [Quallenauge]
1654bae  wiki: devices: Promote X00TD & X01BD to 18.1  [Vivekachooz]

project packages/apps/Eleven/
3fbcef8  gradle: squashed maintainance  [Alexander Martinz]

project packages/apps/Snap/
cc82877  Snap: api2: reduce unneeded animations  [Timi]

project vendor/lineage/
94aaca4  apns-conf: Add TPG Singapore configs  [Nicholas Lim]
fb59cfd  apns: Remove T-Mobile UK  [Michael W]
e21a1e8  vendor: apns: Add LIDL Connect  [Michael W]
6c32584  apns: Enable IPV6 for China Telecom  [zhaoguomanong]
9f1696a  apns: Enable IPV6 for China Unicom  [sjllls]
d377a1c  apns: Enable IPV6 for China Mobile  [sjllls]

====================
     2021-05-13    
====================

====================
     2021-05-12    
====================
project external/chromium-webview/
8174659  Update Chromium Webview to 90.0.4430.210  [Kevin F. Haggerty]

project external/exfatprogs/
1ae2120  libexfat: Remove unused parameter in exfat_show_volume_serial  [Luca Stefani]
dd3f3bd  [DNM] exfatprogs: Merge 1.1.1  [Luca Stefani]

project lineage-sdk/
1167224  lineage-sdk: Retire HostnamePreference as net.hostname no longer works  [LuK1337]

project lineage/mirror/
d14a216  Updated to 11-May-2021 17:19 UTC  [Kevin F. Haggerty]

project lineage/wiki/
1a05c8e  wiki: Use push-update script from current device branch  [razorloves]
235e285  wiki: Update bardock & bardockpro info  [Alexander K]

project packages/apps/Settings/
a3d630e  Revert "Expose option to change the device hostname."  [LuK1337]

project vendor/lineage/
4f5669c  overlay: Set the device hostname like the device name in About Phone  [Ezio Lacandia Bijelkic]

====================
     2021-05-11    
====================
project lineage/hudson/
b735f8e  hudson: Promote blueline/crosshatch to 18.1  [razorloves]

project lineage/scripts/
8d34acd  device-deps-regenerator: Drop 16.0  [razorloves]

project packages/apps/Jelly/
01ec94e  Jelly: MainActivity: Replace applyThemeColor with setUiMode  [Aayush Gupta]
ce7abca  Jelly: Switch to mavenCentral() inplace of jCenter()  [Aayush Gupta]
71d6085  Jelly: Upgrade gradle to v4.2.0 stable release  [Aayush Gupta]

project packages/apps/Settings/
ed7df03  Settings: Make setup wizard go through ChooseLockPatternSize if needed  [LuK1337]
92de599  Settings: Make FRP go through ChooseLockPatternSize if needed  [LuK1337]
2c261b6  Settings: Remove hardcoded extras from ChooseLockPatternSize  [LuK1337]

====================
     2021-05-10    
====================
project frameworks/base/
e97818f  WifiManager: Add StaState API [1/2]  [Kshitij Gupta]

project lineage/hudson/
9c5828e  hudson: Promote YTX703L/YTX703F to 18.1  [Quallenauge]

project lineage/wiki/
5434cf0  wiki: devices: Promote blueline/crosshatch to 18.1  [razorloves]
b2fce12  wiki: devices: Promote Motorola msm8937 family to 18.1  [Jarl-Penguin]

project packages/apps/Snap/
8cd66af  Snap: api2: add QR scanner mode  [Timi]
029c55f  Snap: api2: update promode icons  [Timi]
cf411ba  Snap: api2: use nicer icons in settings  [Timi]

project vendor/lineage/
8137c7c  roomservice: Set exit status if we fail to fetch data from github  [LuK1337]

====================
     2021-05-09    
====================
project build/make/
d8dffd8  backuptool: Map extra dynamic partitions for Addon.d V3  [Alessandro Astone]

project packages/apps/Settings/
0a9477f  Settings: Remove dependency on pref object for min refresh rate isAvailable()  [LuK1337]

====================
     2021-05-08    
====================
project frameworks/base/
653674c  Merge tag 'android-11.0.0_r37' into staging/lineage-18.1_merge-android-11.0.0_r37  [Kevin F. Haggerty]

project frameworks/opt/net/wifi/
94c32fb  wifi: Add StaState API [2/2]  [Kshitij Gupta]

project frameworks/opt/telephony/
9e3ffa6  Reset APN settings after SIM refresh  [Avinash Nalluri]
7bb935a  Fix isCellularSupported check in RIL  [Sneh Bansal]
12a0579  IMS: Fix incall MMI code failure after turning volte off  [Muhammed Siju]
1ae075c  Fix 2 race issues on handover between IWLAN and WWAN  [Mengjun Leng]
d4dc23a  Stop evaluating default data SUB before SUB info is ready  [Mengjun Leng]
cd33642  Filter APN Settings based on carrier requiremnets  [Avinash Nalluri]
10d90b6  Fix vendor class compilation  [Pranav Vashi]
cd720de  Phone exception Issue  [Vidyalakshmi Badiger]
57a086c  Telcel: Fix data call retry for apn change event  [Susheel Nyamala]
36fd215  Retry temp dds switch for UI setting  [Susheel Nyamala]
d63ea28  Add support to extend methods from VendorPhoneSwitcher  [Susheel Nyamala]
6cae6b2  Restore getSubIdFromNetworkRequest method  [Alex Koskovich]
1b2df40  Restore isEmergency method  [Alex Koskovich]
3f70f6c  Telephony: Fix crash while updating Operator Name  [Pranav Vashi]
3f6ba8f  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
6e22278  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
21a433d  Fix imsi info error when insert some china operator card.  [qiongz]
7a211a8  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
83ab028  Fix to block sim selection popup for data  [Susheel Nyamala]
edab02a  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
e185106  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
5df175f  Enable vendor Telephony plugin  [Sneh Bansal]
362aadf  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project lineage/wiki/
2fcd413  wiki: devices: Update maintainers for cheeseburger, dumpling  [Georg Veichtlbauer]

project vendor/lineage/
11c43d2  backuptool: use correct BLK_PATH on a-only dynamic partitions devices  [Tim Zimmermann]

====================
     2021-05-07    
====================
project lineage/hudson/
bf8c8a8  hudson: Promote Motorola msm8937 family to 18.1  [Jarl-Penguin]

project lineage/mirror/
0e493ff  Updated aosp-minimal to 07-May-2021 12:01 UTC  [Tim Schumacher]

project lineage/wiki/
cf71bc6  wiki: Warn about fastbootd not being available on old builds for OP fw update  [LuK1337]
5cc3b77  wiki: Fix wording in fastboot_ab template  [razorloves]
f95a2b8  wiki: Remove duplicated lines from firmware_update_oneplus_sm8250.md  [LuK1337]

project packages/apps/FaceUnlockService/
673ce8e  Automatic translation import  [PixelExperience Automation]

project packages/apps/Snap/
868d2a3  Snap: api2: close mode switcher on promode events  [Timi]
96b64e6  Snap: api2: close mode switcher on back-keypress  [Timi]

project packages/providers/DownloadProvider/
1b788a8  Stop downloads delegated from UIDs blocked by network policy  [Oliver Scott]

====================
     2021-05-06    
====================
project frameworks/base/
029edb3  SystemUI: Force left-to-right for network traffic monitor holder  [LuK1337]

project lineage/wiki/
497ae4e  templates: fastboot_ab: Don't expect user to boot recovery at this stage  [Nolen Johnson]
3dd5307  wiki: templates: fastboot_ab: Fastboot on legacy A/B is fixed now  [Nolen Johnson]

project packages/apps/Eleven/
c80c952  Eleven: bump minSdk to 28  [Alexander Martinz]
dd4d77e  Eleven: Blur: move RenderScript references to BlurBitmapWorkerTask  [Alexander Martinz]

project packages/apps/Snap/
686f695  Snap: api2: correct format-setting icon  [Timi]

