====================
     2021-02-11    
====================

project bootable/recovery/
79bbb64  recovery: Add logcat to deps  [Michael Bestas]

project build/make/
a7581b6  build: Remove some debugging props  [Henrique Silva]
801f00c  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
e43a81a  markw: Move dpm feature prop to system ext  [ShihabZzz]
f579729  markw: Move zygote preforking prop to system  [ShihabZzz]

project frameworks/av/
4983f68  CCodec: workaround for frame drops  [Wonsik Kim]
e66536d  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
3d5bb78  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
821e5b6  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
9641d70  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
a2a497a  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
687ef49  OMX AAC decode don't support getting DRC parameters  [Chuangjie Xia]
c74ac09  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
9a664ef  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
fd5d31f  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
120b396  MediaCodec: clean up resources pending removal at init  [Wonsik Kim]
80f430e  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
e28e157  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
0ae31bd  CCodec: add to check pipelineFull() in feedInputBufferIfAvailableInternal()  [Taehwan Kim]
4bf0a4b  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
ff6ff02  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]

project frameworks/base/
ed61cd0  DataSwitchTile: dont show toast on click  [micky387]
b3bcbb9  DataSwitchTile: collapse notification panel onClick  [DennySPB]
a13b675  SystemUI: Introduce DataSwitchTile  [Christian Oder]
312432d  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
800807b  Restore one-click to add/remove tiles after r19 merge  [ezio84]
c70921e  SystemUI: Remove build version from qs footer  [Pranav Vashi]
56ac29d  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
ca31d95  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
14a5c6e  base: Add metric for Blinx Settings  [David Trpchevski]
e2286da  SystemUI: Add a tile to show power menu  [DarkJoker360]
31629f2  SystemUI: Fix shutter sound  [Michael W]
d943955  SystemUI: Screenshots: Refactor shutter sound logic  [Michael W]
6d2ae6a  Fix: "Clear All" recent app screen loop bug  [vincent.cw_lee]
c9cc8d2  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
c4c87c7  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
89aea75  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
7704430  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
27fe011  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
3348363  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
682dcf7  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
afd080b  SystemUI: Remove unused resources  [Michael Bestas]
a41b8f3  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
1d758b0  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
6bb9aa8  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
08d8c9b  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
fb3500b  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
0c083de  LockIcon: refresh icon on overlay changes  [Dil3mm4]
27cc019  Properly set fonts and icons on keyguard when changing styles  [ezio84]
ea7525b  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
0b421cf  screenrec: Show dialog on bottom  [El Dainosor]
4e137b0  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
4295ec9  PowerProfile: allow overriding default power profile  [Alexander Martinz]
8c5a460  power: Re-introduce custom charging sounds  [Bruno Martins]
ca6188a  incremental: Fix more clang-tidy warnings  [Luca Stefani]
205392d  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
4be6d7f  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/native/
533ec7a  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]

project frameworks/opt/net/wifi/
36068c2  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
a767b1d  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
32ddfb1  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
a30598b  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
eebfeed  Fix imsi info error when insert some china operator card.  [qiongz]
2ef47bb  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
a7edf97  Fix to block sim selection popup for data  [Susheel Nyamala]
00de4b6  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
a418583  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
524aa42  Enable vendor Telephony plugin  [Sneh Bansal]
d8b2f80  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
b381ed4  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
650db3f  Set default value for pressure sensor  [Hsin-Yi Chen]
26066b1  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
26419a7  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
ff0e82f  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
2f8082e  sdk: Add power button qs tile metric  [DarkJoker360]
a108948  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/mirror/
69f0de0  Updated aosp-minimal to 11-Feb-2021 13:01 UTC  [Tim Schumacher]

project packages/apps/Dialer/
feea053  Enable call recording for Bangladesh  [ShihabZzz]
33178a2  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
488e5ea  Dialer: Remove unused resources  [Michael Bestas]
464de9c  Fix selecting phone account dialog show error.  [Grace Jia]
0c499cc  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
029e103  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
742cefc  Messaging: Remove unused resources  [Michael Bestas]
5189141  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
44e54a3  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Recorder/
eeca1a3  Recorder: bring back original wav recording as an option  [2bllw8]
8fd87b8  Recorder: Move list actions to popup menu  [joey]
91631d5  Recorder: Add configuration for high quality  [2bllw8]
ca91148  Recorder: Recording list: Don't slide in and out  [Michael W]
836913a  Recorder: Show empty view when removing last item  [Michael W]
ef80af9  Recorder: Update gradle and dependencies  [2bllw8]
e8362bf  Recorder: Add feature to pause / resume recording  [2bllw8]
8fc826e  Recorder: Rewrite sound recording service  [2bllw8]
e771ae7  Recorder: Add feature to rename recordings  [2bllw8]
547bcc4  Recorder: Do not show double popup when asking to delete a record  [2bllw8]
fb0c729  Recorder: Add view of all my records  [2bllw8]
79ad25b  Recorder: Add support for tagging records with location name  [Joey]
117758e  Recorder: Add new wave recording animation  [2bllw8]

project packages/apps/Settings/
d2e5252  Fix crash on "Connection preferences"  [Hugh Chen]
47c0763  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
dfa9ff1  Snap: Fix SD card visibility for secondary users  [Arne Coucheron]
81c22d2  Snap: Save SDCard photos to legacy path  [Kevin F. Haggerty]
527b316  Revert "Snap: Remove saving to sdcard"  [Arne Coucheron]
b06adaf  Revert "Snap: Let mediaprovider add entry for newly taken photos"  [Arne Coucheron]

project packages/apps/Stk/
4794920  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
07ae256  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]
99f4a4f  Remove unused translation  [Michael Bestas]

project packages/apps/Updater/
198da2d  Update Changelog server URL  [ShihabZzz]
b451be4  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
d4647bb  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project system/core/
fb2fa99  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
d6c2735  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
0f20ca0  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
64f1647  logcat: Mark as recovery_available  [Michael Bestas]
d746021  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
025c7b1  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]

project system/vold/
7a23661  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]

project vendor/lineage/
2112bfe  overlay: Override config for platform number verification  [Sneh Bansal]
80bd7b8  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
6644a1b  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
789b4a9  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
f0f1382  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-02-10    
====================

project lineage/mirror/
c2d4c98  Updated aosp-minimal to 10-Feb-2021 13:01 UTC  [Tim Schumacher]

====================
     2021-02-09    
====================

project lineage/mirror/
e422c3f  Updated to 08-Feb-2021 20:50 UTC  [Kevin F. Haggerty]

project packages/apps/Snap/
3abede0  SnapCam: Fix thumbnail not update  [junjiez]

project packages/providers/MediaProvider/
b9e7c79  MediaProvider: Fix insert fail while file saved in sdcard  [Wang Haijun]

====================
     2021-02-08    
====================

project system/core/
f29ed7d  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

====================
     2021-02-07    
====================

project packages/apps/Recorder/
b754a21  Recorder: Actually display share notification  [Michael W]
1b9e34c  Recorder: Fix sharing  [Michael W]
d2da700  Recorder: Remove screen recorder  [Michael W]

project vendor/lineage/
c63fa84  backuptool: Support seamless backup and restore to extra partitions  [Alessandro Astone]
6245873  backuptool_ab: Make tmp actually tmpfs  [Alessandro Astone]

====================
     2021-02-06    
====================

project device/xiaomi/markw/
ca5ce82  markw: Cleanup/Update layers  [ShihabZzz]

project external/cldr/
8fe1f2d  DO NOT MERGE Cherry-pick CLDR-14434: Update Android CLDR tzdata from 2020f to 2021a. [R]  [Almaz Mingaleev]

project external/icu/
a21a549  DO NOT MERGE Update Android ICU tzdata from 2020f to 2021a. [R]  [Almaz Mingaleev]

project frameworks/av/
da85637  Merge tag 'android-11.0.0_r29' of https://android.googlesource.com/platform/frameworks/av into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/base/
d7c3493  Merge tag 'android-11.0.0_r29' of https://android.googlesource.com/platform/frameworks/base into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project kernel/xiaomi/markw/
b1feb26  Redux: 2.01  [ShihabZzz]
5a5fa78  markw: dtsi: Remove venus memory allocation  [ShihabZzz]

project system/timezone/
473d22b  DO NOT MERGE Update Android TZDB from 2020f to 2021a. [R]  [Almaz Mingaleev]

====================
     2021-02-05    
====================

project external/chromium-webview/
d8c9c41  Update Chromium Webview to 88.0.4324.152  [Kevin F. Haggerty]

project frameworks/base/
1a41725  No need to 'addChild' when start 'FLAG_ACTIVITY_CLEAR_TOP' Activity.  [yangyankai1]
73c1924  Fix a bug in the USAP Pool refill logic.  [Chris Wailes]
ea71eff  Partially revert "Wake up to lock screen when bouncer is visible"  [Sultan Alsawaf]

project kernel/xiaomi/markw/
f6d57f0  ASoC: msm: kill logspam when voip sessions is active  [Ryan Andri]
b3a68ea  Init Redux 2.0  [ShihabZzz]
c7aeb37  arch/dts: markw: Enable ULPS & phy-poweroff for panels  [ShihabZzz]
1d8d24d  markw: Rewrite audio driver from Mi OpenSource  [ShihabZzz]
49d6355  Revert "sound: soc: Remove HDMI codecs dependencies from MSM8X16"  [ShihabZzz]
03dbdc2  Revert "arch: markw_defconfig: Disable HDMI support"  [ShihabZzz]
8c33f76  Revert "arch/arm: dts: qcom: Fix wheezing and increased stability"  [ShihabZzz]
95eb7fe  net: wireguard: Patching > Merging  [ShihabZzz]
9df0ae8  Redux: 1.05  [ShihabZzz]
7c76a06  arch/markw_defconfig: Enable WIREGUARD  [ShihabZzz]
e5b247c  drivers: Silence debugfs failing log spam  [ShihabZzz]
5641e22  rcu: boost: avoid preemption before calling complete()  [John Dias]
1c41d61  BACKPORT: qseecom: Use scm_call2 when bus_scaling is enabled  [AnilKumar Chimata]
2d76f29  BACKPORT: qseecom: Remove virtual address print  [Monika Singh]
501fbef  drivers: input: touchscreen: Create keydisabler nodes  [GuaiYiHu]
6ce9f07  arm:dts: msm8953: Add clock-frequency property  [Remicaa]
97ffc4b  thermal: Do not log an error if thermal_zone_get_temp returns -EAGAIN  [Hans de Goede]
c0f4eda  msm_thermal: initialize later than arch drivers  [Park Ju Hyung]
fb6c404  msm: ipa: update msm_ipa.h with latest IPA versions constants  [Ghanim Fodi]
7e563f9  Init Redux !!!  [ShihabZzz]
c19ed72  Quark: 1.20  [ShihabZzz]
3fc2f02  Merge tag 'ASB-2021-02-05_3.18'  [ShihabZzz]
862026b  Revert "net: Remove dst_cache support"  [ShihabZzz]

====================
     2021-02-04    
====================
project android/
2572a5b  manifest: android-11.0.0_r27 -> android-11.0.0_r29  [Kevin F. Haggerty]

project build/make/
0e7a236  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/base/
bf766d5  PhoneWindowManager: Only react to camera key when necessary  [Michael W]

project frameworks/native/
f1201c6  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

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
e8dcaba  fs_mgr: Allow remounts with Magisk installed  [Bruno Martins]
79f606e  liblog: Always report as debuggable when building userdebug/eng  [Bruno Martins]

project vendor/lineage/
2263d4b  fixup! Dialer: Add visual voicemail configs from Google Dialer  [Eamon Powell]
04bbc65  Dialer: Add visual voicemail configs from Google Dialer  [Danny Lin]

project vendor/qcom/opensource/commonsys/packages/apps/Bluetooth/
9a8c62b  Check permission before sending batch scan result  [Jakub Pawlowski]
3e5a7fa  Check if advertiserId value matches valid advertiser  [Jakub Pawlowski]

====================
     2021-02-03    
====================

project lineage/mirror/
e116655  Updated aosp-minimal to 03-Feb-2021 13:01 UTC  [Tim Schumacher]

====================
     2021-02-02    
====================

project lineage/mirror/
a1693c2  Updated aosp-minimal to 02-Feb-2021 13:01 UTC  [Tim Schumacher]
8d3f411  aosp-minimal: Always add platform/manifest  [Chirayu Desai]

project lineage/wiki/
d23bc0f  wiki: Correct d803 architecture  [Michael W]

project tools/repohooks/
f1e0b3b  android_test_mapping_format: drop Python 2 support  [Mike Frysinger]

project vendor/lineage/
ec016fd  qcom: Add bengal platform  [TheMalachite]

====================
     2021-02-01    
====================

project lineage/hudson/
c714e23  hudson: Promote s2 to 17.1  [tImIbreakdown]
22be650  hudson: Re-add Redmi Note 7 (lavender)  [Usaamah Patel]

project lineage/wiki/
042b33a  wiki: Add my name to lavender  [Usaamah Patel]

project packages/apps/SetupWizard/
da735e0  SuW: Avoid showing exceptions if packages are not installed  [Bruno Martins]

project system/core/
0a3ac9b  adb_root: Make encryption action an argument to mkdir  [Paul Crowley]

project tools/repohooks/
42e4aa4  config: switch to stdlib get() fallback logic  [Mike Frysinger]

project vendor/lineage/
916ecda  init: Make encryption action an argument to mkdir  [Paul Crowley]

====================
     2021-01-31    
====================

project lineage/wiki/
8e5e64b  wiki: Promote s2 to 17.1  [tImIbreakdown]

project packages/apps/Settings/
2dd2222  KeyboardSettings: Add a RemotePreference for device-specific panel  [Bruno Martins]

====================
     2021-01-30    
====================

project frameworks/base/
a6eff9c  AudioService: Remove Analog Dock from fixed-volume devices  [Vachounet]

project frameworks/opt/net/wifi/
1590c96  Fix abnormal wake up caused by WifiConnectivityManager  [zhujiatai]

project hardware/google/pixel/
b2333c4  pixel: Add lineage touch hal  [Alessandro Astone]

project lineage/wiki/
421c499  wiki: Improve addon install terminology  [razorloves]

project tools/repohooks/
d57f9c5  utils: drop Python 2 support  [Mike Frysinger]
8349d89  config: drop Python 2 support  [Mike Frysinger]

====================
     2021-01-29    
====================

project hardware/interfaces/
8fd638a  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]

project lineage/hudson/
e0ab036  hudson: Drop Redmi note 7 (lavender)  [Erfan Abdi]
e8e261f  hudson: Drop exynos 9810 devices  [Erfan Abdi]

project lineage/mirror/
20ff477  Updated aosp-minimal to 29-Jan-2021 17:02 UTC  [Tim Schumacher]

project lineage/wiki/
e4a36dc  wiki: Remove my name from ginkgo and lavender  [Erfan Abdi]
a5d3845  wiki: Drop exynos 9810 devices  [Erfan Abdi]

