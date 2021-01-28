====================
     2021-01-28    
====================

project build/make/
aaf6705  build: Remove some debugging props  [Henrique Silva]
a8cc338  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
4ad9abf  markw: Update audio configs/prop from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]
9aa6d4d  markw: audio: Add gsm-mode path  [ShihabZzz]
26e4f87  markw: sepolicy: Allow permission controller to use tethering service  [ShihabZzz]
4befc66  Revert "markw: Enabling sound trigger V2_2"  [ShihabZzz]

project frameworks/av/
20c229e  CCodec: workaround for frame drops  [Wonsik Kim]
1352b0f  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
0a3019d  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
7ceb932  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
939a8af  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
b872b1f  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
e0701ee  OMX AAC decode don't support getting DRC parameters  [Chuangjie Xia]
122df0a  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
d18fe56  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
662b99a  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
754d781  MediaCodec: clean up resources pending removal at init  [Wonsik Kim]
c281e8f  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
af68c98  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
a2ea5cb  CCodec: add to check pipelineFull() in feedInputBufferIfAvailableInternal()  [Taehwan Kim]
ebec455  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
7a17246  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]

project frameworks/base/
7d2b0bc  DataSwitchTile: dont show toast on click  [micky387]
53d27d5  DataSwitchTile: collapse notification panel onClick  [DennySPB]
ce1b5bc  SystemUI: Introduce DataSwitchTile  [Christian Oder]
e27d37e  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
d58c3d5  Restore one-click to add/remove tiles after r19 merge  [ezio84]
9b1a717  SystemUI: Remove build version from qs footer  [Pranav Vashi]
4bbf24b  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
04f3e09  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
8db56cd  base: Add metric for Blinx Settings  [David Trpchevski]
a5885c0  SystemUI: Add a tile to show power menu  [DarkJoker360]
7fa97e5  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
6449b14  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
496dfee  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
4d86f12  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
0df317e  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
f38d813  Allow SBC as HD audio codec in Bluetooth device configuration  [ValdikSS]
8c4fc1b  Add Dual Channel into Bluetooth Audio Channel Mode developer options menu  [ValdikSS]
49784db  Add CHANNEL_MODE_DUAL_CHANNEL constant  [ValdikSS]
e2079ab  SystemUI: Remove unused resources  [Michael Bestas]
1f3d0fe  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
1cff644  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
95e50ec  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
5fcbbd6  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
b3224da  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
c2456f1  LockIcon: refresh icon on overlay changes  [Dil3mm4]
576170e  Properly set fonts and icons on keyguard when changing styles  [ezio84]
94ca11a  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
e58b065  screenrec: Show dialog on bottom  [El Dainosor]
8552de7  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
5c7f016  PowerProfile: allow overriding default power profile  [Alexander Martinz]
f402c5f  power: Re-introduce custom charging sounds  [Bruno Martins]
97294b7  incremental: Fix more clang-tidy warnings  [Luca Stefani]
bd58681  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
b657502  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/opt/telephony/
ed1f2c1  RIL: Fix manual network selection with old modem  [faust93]
0ba219e  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
6166d3a  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
5f9959d  Fix imsi info error when insert some china operator card.  [qiongz]
7b86d4e  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
f792ec6  Fix to block sim selection popup for data  [Susheel Nyamala]
021217f  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
b0d405f  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
2a7baea  Enable vendor Telephony plugin  [Sneh Bansal]
d3df42f  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
482328d  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
8a4a02a  Set default value for pressure sensor  [Hsin-Yi Chen]
d077b59  wifi: Add support for Dual Station combination.  [Khanjan Desai]
ce3766a  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]
7a0692f  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
538fdd7  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
658c1e6  livedisplay: Initial conversion to aidl  [Pig]

project kernel/xiaomi/markw/
5e846db  Init Redux 2.0  [ShihabZzz]
7d772d9  arch/dts: markw: Enable ULPS & phy-poweroff for panels  [ShihabZzz]

project lineage-sdk/
ba929b0  sdk: Add power button qs tile metric  [DarkJoker360]
477148c  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project packages/apps/Dialer/
79f9976  Enable call recording for Bangladesh  [ShihabZzz]
caae98f  Dialer: Remove unused resources  [Michael Bestas]
6e2188a  Fix selecting phone account dialog show error.  [Grace Jia]
6e09085  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
7238a37  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
d4f7dc0  Messaging: Remove unused resources  [Michael Bestas]
2d30a8c  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
bb4c4f1  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
166b20f  Fix crash on "Connection preferences"  [Hugh Chen]
da0060a  Add Dual Channel into Bluetooth Audio Channel Mode developer options menu  [ValdikSS]
d314891  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Stk/
1f75d2d  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
1fa3f60  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]
7ff1f58  Remove unused translation  [Michael Bestas]

project packages/apps/Updater/
8b21a8e  Update Changelog server URL  [ShihabZzz]
2838973  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
baa9b5a  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project packages/resources/devicesettings/
b8568cc  Turn devicesettings resources into a static library  [Pig]
91e2aea  devicesettings: Add common adaptive icon  [Asher Simonds]

project system/core/
d9cc4be  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
a077bed  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
55f75e6  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
7f1314f  logcat: Mark as recovery_available  [Michael Bestas]
04af436  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
06aa86e  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
61cef2c  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

project system/vold/
d60d2cb  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
6338a6f  Fix the group permissions of the sdcard root.  [Jani Lusikka]
fe8d76e  vold ext4/f2fs: do not use dirsync if we're mounting adopted storage  [Sam Mortimer]
98959a4  vold: Mount ext4/f2fs portable storage with sdcard_posix  [Jani Lusikka]
f2b6ee4  vold: Honor mount options for ext4/f2fs partitions  [Tom Marshall]
603e45a  vold: Support internal storage partitions  [Tom Marshall]
fc03d18  vold: Fix fsck on public volumes  [Michael Bestas]
29ce8f6  vold: add support for more filesystems for public storage  [Dan Pasanen]

project vendor/lineage/
02a1ab6  backuptool: Support seamless backup and restore to extra partitions  [Alessandro Astone]
5d50ba3  backuptool_ab: Make tmp actually tmpfs  [Alessandro Astone]
3724a55  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
991b2a2  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
4cdaff9  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
33efefe  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-01-27    
====================

project device/xiaomi/markw/
39053dc  markw: zygote: enable unspecialized app process pool  [Jesse Chan]
f3b1689  markw: Ditch amplifier support  [ShihabZzz]

====================
     2021-01-26    
====================

====================
     2021-01-25    
====================

====================
     2021-01-24    
====================

project device/xiaomi/markw/
a2cb3fa  power: Handle Mode::LAUNCH power hints.  [Quallenauge]
38c2544  markw: power: Switch to TARGET_POWERHAL_MODE_EXT  [LuK1337]
7f0fbde  markw: Create stune directory  [ShihabZzz]
f3bf0fd  markw: sepolicy: Silence goodix blobs spam  [ShihabZzz]
ee5e7da  markw: rootdir: stop/start > restart [ VoLTE SIM Slot switching ]  [ShihabZzz]
7b596a3  markw: biometrics: shim: Transition to blueprint  [ShihabZzz]
8c71df2  markw: biometrics: fakelogprint: Update include  [tImIbreakdown]
b679462  markw: Goodix FP HAL: Be quiet!  [Jan Engelmohr]

====================
     2021-01-23    
====================

project kernel/xiaomi/markw/
9806777  markw: Rewrite audio driver from Mi OpenSource  [ShihabZzz]
2c8c012  Revert "sound: soc: Remove HDMI codecs dependencies from MSM8X16"  [ShihabZzz]
4f0c5bf  Revert "arch: markw_defconfig: Disable HDMI support"  [ShihabZzz]

====================
     2021-01-22    
====================
project android/
afc0d41  manifest: Sync 8994 HALS  [Nolen Johnson]

project hardware/lineage/interfaces/
8fac36e  lineage/interfaces: add fastcharge HAL  [Francescodario Cuzzocrea]

project lineage/wiki/
7c5fb03  wiki: Improve special boot mode naming  [razorloves]

project packages/apps/Settings/
920510f  Settings: Add FastCharge preference into Battery settings  [Bruno Martins]

====================
     2021-01-21    
====================

project lineage/hudson/
88bebad  Regenerate device dependency mappings  [razorloves]
f6d0295  hudson: Ship Moto G5S (montana)  [Jarl-Penguin]
b19d5bc  hudson: Ship Moto G5 (cedric)  [Jarl-Penguin]
7465aa4  hudson: Ship Moto E5 Plus (ahannah/hannah/rhannah)  [Jarl-Penguin]
234e951  hudson: Enter the ether  [Nolen Johnson]

project lineage/wiki/
ae0217e  wiki: Add Moto G5S (montana)  [Jarl-Penguin]
470c52c  wiki: Add Moto G5 (cedric)  [Jarl-Penguin]
d025341  wiki: Add Moto E5 Plus (ahannah/hannah/rhannah)  [Jarl-Penguin]
d4f9b8c  wiki: devices: Promote ether to 17.1  [Nolen Johnson]

project tools/repohooks/
147b6c3  Add aidl-format as a new builtin hook  [Jiyong Park]

project vendor/qcom/opensource/power/
7e7c42d  power: Allow device specific hooks for setBoost, isBoostSupported  [Quallenauge]
061c303  power: Reduce log level of setBoost() method to VERBOSE.  [Quallenauge]
4b11fbd  power: Avoid reaching req limit of qti perf service.  [Quallenauge]
2977a6d  power: Handle Boost:INTERACTION.  [Quallenauge]

====================
     2021-01-20    
====================

project device/google/atv/
9c591b4  products: Include ATV x86_64 target  [Nolen Johnson]
479e60b  products: Add generic x86_64 TV target  [Nolen Johnson]

project external/chromium-webview/
e455e42  Update Chromium Webview to 88.0.4324.93  [Kevin F. Haggerty]

project kernel/xiaomi/markw/
544430b  Revert "arch/arm: dts: qcom: Fix wheezing and increased stability"  [ShihabZzz]

project lineage/wiki/
be3d76e  wiki: Fix recovery mode boot steps on pixels  [razorloves]

project vendor/lineage/
c2d63c6  lineage: targets: Add support for ATV GSI builds  [Nolen Johnson]

====================
     2021-01-19    
====================

project device/lineage/sepolicy/
9840990  lineage: Make FastCharge service discoverable by Settings app  [Bruno Martins]

project lineage/mirror/
bbb1713  Updated to 19-Jan-2021 14:02 UTC  [Kevin F. Haggerty]
69647a9  Updated to 19-Jan-2021 13:12 UTC  [Kevin F. Haggerty]

project lineage/wiki/
ee0b20e  wiki: payton: update maintainers  [Marc Bourgoin]

project vendor/qcom/opensource/power/
f55e27f  power: Re-Enable power_hint() call for Mode::LAUNCH.  [Quallenauge]

====================
     2021-01-18    
====================

project lineage/mirror/
65e78e4  Updated to 18-Jan-2021 13:01 UTC  [Tim Schumacher]

====================
     2021-01-17    
====================

project device/xiaomi/markw/
687c21d  markw: sepolicy: Address gpuservice denial  [ShihabZzz]
7d81898  markw: doze: Remove unused XML files  [ShihabZzz]

project lineage/hudson/
03e6f51  hudson: Drop find7  [Michael Bestas]

project lineage/wiki/
3d3d520  wiki: Fix FP3 supported versions  [razorloves]
3c7f61f  Remove myself from legacy devices  [Michael Bestas]
e75831e  wiki: Update aleasto nickname  [aleasto]

====================
     2021-01-16    
====================

project device/qcom/sepolicy-legacy-um/
71f1313  legacy: Resolve more surfaceflinger related denial  [ShihabZzz]

project lineage/wiki/
a3668cc  wiki: devices: flox: Opt-in to fastboot boot requirement  [Nolen Johnson]
94d21d4  wiki: templates: Add support for requiring fastboot boot  [Nolen Johnson]

project packages/apps/Snap/
ae1f52c  Snap: Remove warnings for generated ids  [Michael W]
b6ebe16  Snap: there is no camera icon shown if have no camera in first boot up  [zhang sanshan]

project vendor/lineage/
c3710ba  config: Remove persist.sys.dun.override again  [Han Wang]

====================
     2021-01-15    
====================

project device/xiaomi/markw/
d8d0c8c  Revert "markw: Use dex2oat64"  [ZeeLog]
99d6beb  markw: overlay: Change wifi tether regex  [Roshan Pius]
6f2060d  markw: TetheringOverlay: Remove bnep\\d from tetherable BT interfaces  [LuK1337]
a8e3e01  markw: Remove gnss hidl entries in manifest.xml  [Yingjie Wang]
d21e74b  markw: Drop no-op board flags  [ZeeLog]
38c0673  markw: Update Bluetooth (Shared Dependencies) from Tissot V10.0.24.0  [ShihabZzz]
db8e090  markw: Add eMBMS blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
e183a59  markw: overlay: Disable window rounded corner animations  [Lucas Dupin]
9385f94  markw: Update QMI/RIL from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
aac2665  markw: sepolicy: Resolve gmscore app denial  [ShihabZzz]

project frameworks/base/
0177db1  SystemUI: Use AVCProfileMain for screen recorder  [Arne Coucheron]

project lineage/wiki/
ae0008d  devices: ms013g: Specify that we use TWRP  [Daniel Jacob Chittoor]
abf67ee  wiki: Remove leftover custom_recovery_codename  [razorloves]
da268ae  wiki: Fix us996 supported versions  [razorloves]

project vendor/xiaomi/
90d0655  markw: Update Bluetooth (Shared Dependencies) from Tissot V10.0.24.0  [ShihabZzz]
c00817b  markw: Add eMBMS blobs from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]
7b55b46  markw: Update QMI/RIL from LA.UM.9.6.2.r1-03600-89xx.0  [ZeeLog]

