====================
     2021-02-07    
====================

project bootable/recovery/
393fece  recovery: Add logcat to deps  [Michael Bestas]

project build/make/
a5aa45b  build: Remove some debugging props  [Henrique Silva]
34cdfd2  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
ca5ce82  markw: Cleanup/Update layers  [ShihabZzz]

project frameworks/av/
e876b26  CCodec: workaround for frame drops  [Wonsik Kim]
87a1ac3  Codec2: Initialize InputSurfaceWrapper::Config structure fields  [wangchenyang]
71fd5a3  ACodec: Handle HDR10+ metadata at OutputPortSettingsChangedState  [Houxiang Dai]
5d6d91c  CCodec: GraphicBufferSourceWrapper: fix to apply nBufferCountActual for deciding number of inputs  [Taehwan Kim]
97b4e51  CCodec: fix ByteBuffer mode image  [Wonsik Kim]
392e3b5  C2AllocatorBlob: allow multiple maps  [Wonsik Kim]
d462c87  OMX AAC decode don't support getting DRC parameters  [Chuangjie Xia]
536c635  omx: calculate nodePrefix only for components listed in IOmx  [Lajos Molnar]
82308a4  CCodec: Increase max linear buffer size for 8K video  [Sungtak Lee]
423b3df  C2OMXNode: read delay from component to determine buffer count  [Wonsik Kim]
118b815  MediaCodec: clean up resources pending removal at init  [Wonsik Kim]
c33f483  NuPlayerRenderer: Reset negative media time to zero  [Paras Nagda]
d60915c  ACodec: submit extra output metadata buffers if in low latency mode  [Wonsik Kim]
b859702  CCodec: add to check pipelineFull() in feedInputBufferIfAvailableInternal()  [Taehwan Kim]
ce7e9ae  OMX Opus decoder omits sample rate / channel count  [Ray Essick]
75028de  CCodec: fix underflow issue on handleImageData  [Taehwan Kim]
da85637  Merge tag 'android-11.0.0_r29' of https://android.googlesource.com/platform/frameworks/av into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/base/
a97ca9e  DataSwitchTile: dont show toast on click  [micky387]
3a3b470  DataSwitchTile: collapse notification panel onClick  [DennySPB]
073d41c  SystemUI: Introduce DataSwitchTile  [Christian Oder]
b15c302  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
bf5e6c6  Restore one-click to add/remove tiles after r19 merge  [ezio84]
c146c7c  SystemUI: Remove build version from qs footer  [Pranav Vashi]
56c0a59  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
3d1de2a  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
d1273aa  base: Add metric for Blinx Settings  [David Trpchevski]
42a5037  SystemUI: Add a tile to show power menu  [DarkJoker360]
caa4e7c  SystemUI: Fix shutter sound  [Michael W]
303dd62  SystemUI: Screenshots: Refactor shutter sound logic  [Michael W]
042ca63  Fix: "Clear All" recent app screen loop bug  [vincent.cw_lee]
550151c  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
a812212  Fix NetworkPolicyManagerService deadlock  [Zhengyu Zhan]
abf27b1  MediaCodecInfo: do not alter performance points for 32-bit processes  [Wonsik Kim]
53e7cee  MediaCodecInfo: limit resolution to 4K for 32-bit processes  [Wonsik Kim]
6fc42f59  Revert "Revert "Restore preferred activity filter if it not inside""  [Songchun Fan]
a237f73  Revert "Restore preferred activity filter if it not inside"  [Wale Ogunwale]
18229956  Restore preferred activity filter if it not inside  [vend_wsd_am_052]
b7a663a  Allow SBC as HD audio codec in Bluetooth device configuration  [ValdikSS]
d75cfff  Add Dual Channel into Bluetooth Audio Channel Mode developer options menu  [ValdikSS]
912e77f  Add CHANNEL_MODE_DUAL_CHANNEL constant  [ValdikSS]
0ed2a29  SystemUI: Remove unused resources  [Michael Bestas]
ae7d36e  VolumeDialogImpl: Reschedule the timeout on clicks on captions  [Arian]
c4b55ae  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
92f3b86  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
6922995  SystemUI: VolumeDialog: Separate expandable indicator and media output container  [althafvly]
b83920d  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
72deb6e  LockIcon: refresh icon on overlay changes  [Dil3mm4]
246b479  Properly set fonts and icons on keyguard when changing styles  [ezio84]
70e20f0  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
f69fe38  screenrec: Show dialog on bottom  [El Dainosor]
b316801  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
37107ea  PowerProfile: allow overriding default power profile  [Alexander Martinz]
294c820  power: Re-introduce custom charging sounds  [Bruno Martins]
dc7eea1  incremental: Fix more clang-tidy warnings  [Luca Stefani]
3c6a1fa  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
eb0e77c  IncrementalService: Fix clang-tidy warning  [Luca Stefani]
d7c3493  Merge tag 'android-11.0.0_r29' of https://android.googlesource.com/platform/frameworks/base into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/native/
2fd3a6d  gralloc4: fix PlaneLayout encode typecasting  [SeYeong Byeon]

project frameworks/opt/net/wifi/
11c73d2  Fix abnormal wake up caused by WifiConnectivityManager  [zhujiatai]

project frameworks/opt/telephony/
c5e2be9  RIL: Fix manual network selection with old modem  [faust93]
a309bf5  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
b204886  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
df2dcb4  Fix imsi info error when insert some china operator card.  [qiongz]
88ece41  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
a7e91cb  Fix to block sim selection popup for data  [Susheel Nyamala]
008661f  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
64db2ff  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
f65fa37  Enable vendor Telephony plugin  [Sneh Bansal]
5c10ab2  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
00a50e3  Adjust the parameters of accelerometer and hinge angle sensor  [Hsin-Yi Chen]
876ddab  Set default value for pressure sensor  [Hsin-Yi Chen]
5ab9e2a  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
4cf45ce  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
beecf3d  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
398e267  sdk: Add power button qs tile metric  [DarkJoker360]
edfd19d  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project packages/apps/Bluetooth/
ea7cd66  Assume optional codecs are supported if were supported previously  [ValdikSS]
e0d695f  SBC Dual Channel (SBC HD Audio) support  [ValdikSS]

project packages/apps/Dialer/
49d5215  Enable call recording for Bangladesh  [ShihabZzz]
a198d42  Dialer: Notify content observers upon call log entry deletion  [LuK1337]
d33620c  Dialer: Remove unused resources  [Michael Bestas]
11b411c  Fix selecting phone account dialog show error.  [Grace Jia]
ed429f7  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/LineageParts/
0efbd55  LineageParts: Tweak default charging sound path  [Han Wang]

project packages/apps/Messaging/
c03a375  Messaging: Remove unused resources  [Michael Bestas]
b89379a  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
1f440ef  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
e5f4bef  Fix crash on "Connection preferences"  [Hugh Chen]
9d7f5ce  Add Dual Channel into Bluetooth Audio Channel Mode developer options menu  [ValdikSS]
85a3ed4  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
7c43efe  SnapCam: Fix thumbnail not update  [junjiez]
e3e35b0  Revert "Snap: Let mediaprovider add entry for newly taken photos"  [Arne Coucheron]

project packages/apps/Stk/
57d9acd  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
0f25d4d  Trebuchet: Honor desktop show labels preference for folder icons  [LuK1337]
c5a098b  Remove unused translation  [Michael Bestas]

project packages/apps/Updater/
a4c2db5  Update Changelog server URL  [ShihabZzz]
cbd987d  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
99291d4  WallpaperPicker2: Fix race condition for fast-loading wallpapers  [Danny Lin]

project system/core/
9f3188b  Adding 'postinstall' root dir unconditionally.  [Bowgo Tsai]
8d8cfdf  Store result of mount_all for mounted userdata by metadata encryption  [Qilin Tan]
569e129  Only store result of mount_all that mounted userdata  [Nikita Ioffe]
0959246  logcat: Mark as recovery_available  [Michael Bestas]
ef17165  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
3e82385  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
f915065  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

project system/vold/
e5aa087  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]

project vendor/lineage/
e178f9e  overlay: Override config for platform number verification  [Sneh Bansal]
ffdf22d  backuptool: Support seamless backup and restore to extra partitions  [Alessandro Astone]
a98b8e4  backuptool_ab: Make tmp actually tmpfs  [Alessandro Astone]
66e6c22  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
9f6718e  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
5b7c3d7  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
c02d827  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2021-02-06    
====================

project external/chromium-webview/
d8c9c41  Update Chromium Webview to 88.0.4324.152  [Kevin F. Haggerty]

project kernel/xiaomi/markw/
b1feb26  Redux: 2.01  [ShihabZzz]
5a5fa78  markw: dtsi: Remove venus memory allocation  [ShihabZzz]
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
     2021-02-05    
====================
project android/
2572a5b  manifest: android-11.0.0_r27 -> android-11.0.0_r29  [Kevin F. Haggerty]

project frameworks/base/
1a41725  No need to 'addChild' when start 'FLAG_ACTIVITY_CLEAR_TOP' Activity.  [yangyankai1]
73c1924  Fix a bug in the USAP Pool refill logic.  [Chris Wailes]
ea71eff  Partially revert "Wake up to lock screen when bouncer is visible"  [Sultan Alsawaf]
bf766d5  PhoneWindowManager: Only react to camera key when necessary  [Michael W]

project frameworks/native/
f1201c6  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/apps/Bluetooth/
cc597b3  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/apps/Settings/
513e45d  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/providers/ContactsProvider/
755039c  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project system/core/
a231505  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project vendor/qcom/opensource/commonsys/packages/apps/Bluetooth/
9a8c62b  Check permission before sending batch scan result  [Jakub Pawlowski]
3e5a7fa  Check if advertiserId value matches valid advertiser  [Jakub Pawlowski]

====================
     2021-02-04    
====================

project build/make/
0e7a236  Merge tag 'android-11.0.0_r29' into staging/lineage-18.1_merge-android-11.0.0_r29  [Kevin F. Haggerty]

project packages/apps/SetupWizard/
2b90a7f  SetupWizard: Add device specific hook page  [Michael W]

project system/core/
e8dcaba  fs_mgr: Allow remounts with Magisk installed  [Bruno Martins]
79f606e  liblog: Always report as debuggable when building userdebug/eng  [Bruno Martins]

project vendor/lineage/
2263d4b  fixup! Dialer: Add visual voicemail configs from Google Dialer  [Eamon Powell]
04bbc65  Dialer: Add visual voicemail configs from Google Dialer  [Danny Lin]

====================
     2021-02-03    
====================

project lineage/mirror/
e116655  Updated aosp-minimal to 03-Feb-2021 13:01 UTC  [Tim Schumacher]

project tools/repohooks/
f1e0b3b  android_test_mapping_format: drop Python 2 support  [Mike Frysinger]

project vendor/lineage/
ec016fd  qcom: Add bengal platform  [TheMalachite]

====================
     2021-02-02    
====================

project lineage/hudson/
c714e23  hudson: Promote s2 to 17.1  [tImIbreakdown]

project lineage/mirror/
a1693c2  Updated aosp-minimal to 02-Feb-2021 13:01 UTC  [Tim Schumacher]
8d3f411  aosp-minimal: Always add platform/manifest  [Chirayu Desai]

project lineage/wiki/
d23bc0f  wiki: Correct d803 architecture  [Michael W]
042b33a  wiki: Add my name to lavender  [Usaamah Patel]

project tools/repohooks/
42e4aa4  config: switch to stdlib get() fallback logic  [Mike Frysinger]

====================
     2021-02-01    
====================

project lineage/hudson/
22be650  hudson: Re-add Redmi Note 7 (lavender)  [Usaamah Patel]

project lineage/wiki/
8e5e64b  wiki: Promote s2 to 17.1  [tImIbreakdown]

project packages/apps/Settings/
2dd2222  KeyboardSettings: Add a RemotePreference for device-specific panel  [Bruno Martins]

project packages/apps/SetupWizard/
da735e0  SuW: Avoid showing exceptions if packages are not installed  [Bruno Martins]

project system/core/
0a3ac9b  adb_root: Make encryption action an argument to mkdir  [Paul Crowley]

project vendor/lineage/
916ecda  init: Make encryption action an argument to mkdir  [Paul Crowley]

====================
     2021-01-31    
====================

====================
     2021-01-30    
====================

project frameworks/base/
a6eff9c  AudioService: Remove Analog Dock from fixed-volume devices  [Vachounet]

project hardware/google/pixel/
b2333c4  pixel: Add lineage touch hal  [Alessandro Astone]

project lineage/mirror/
20ff477  Updated aosp-minimal to 29-Jan-2021 17:02 UTC  [Tim Schumacher]

project lineage/wiki/
421c499  wiki: Improve addon install terminology  [razorloves]

project tools/repohooks/
d57f9c5  utils: drop Python 2 support  [Mike Frysinger]
8349d89  config: drop Python 2 support  [Mike Frysinger]

====================
     2021-01-29    
====================
project android/
bf91c0f  lineage: Enable msm8952 HALs  [Michael Bestas]

project hardware/interfaces/
8fd638a  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]

project kernel/xiaomi/markw/
b851dce  sched/numa: Use down_read_trylock() for the mmap_sem  [Vlastimil Babka]
a8ceed5  ext4: handle the rest of ext4_mb_load_buddy() ENOMEM errors  [Konstantin Khlebnikov]
0be0b30  arp: honour gratuitous ARP _replies_  [Ihar Hrachyshka]
5d81d3c  drivers/misc/vmw_vmci/vmci_queue_pair.c: fix a couple integer overflow tests  [Dan Carpenter]
e680327  VMCI: Guard against overflow in queue pair allocation  [Jorgen Hansen]

project lineage/hudson/
e0ab036  hudson: Drop Redmi note 7 (lavender)  [Erfan Abdi]
e8e261f  hudson: Drop exynos 9810 devices  [Erfan Abdi]

project lineage/wiki/
e4a36dc  wiki: Remove my name from ginkgo and lavender  [Erfan Abdi]
a5d3845  wiki: Drop exynos 9810 devices  [Erfan Abdi]

project packages/apps/Gallery2/
4e96ca6  Gallery2: dark theme  [Timi]

project packages/apps/Settings/
c98196f  Settings: Remove empty category from Security Settings  [Michael W]

project packages/inputmethods/LatinIME/
c92ab81  LatinIME: Remove hardcoded emoji row logic  [George Zacharia]
4ffad79  LatinIME: Enable full flag emoji support  [George Zacharia]

====================
     2021-01-28    
====================

project device/xiaomi/markw/
4ad9abf  markw: Update audio configs/prop from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]
9aa6d4d  markw: audio: Add gsm-mode path  [ShihabZzz]
26e4f87  markw: sepolicy: Allow permission controller to use tethering service  [ShihabZzz]
4befc66  Revert "markw: Enabling sound trigger V2_2"  [ShihabZzz]

project kernel/xiaomi/markw/
fbb600d  net: cdc_ncm: Fix TX zero padding  [Jim Baxter]
e4cb90d  spi: davinci: fix up dma_mapping_error() incorrect patch  [Greg Kroah-Hartman]
ed6f60c  nospec: Kill array_index_nospec_mask_check()  [Dan Williams]
4bafa7a  nospec: Move array_index_nospec() parameter checking into separate macro  [Will Deacon]
01ef093  llist: clang: introduce member_address_is_nonnull()  [Alexander Potapenko]
261a89a  RDMA/ucma: Introduce safer rdma_addr_size() variants  [Roland Dreier]
339b3ab  RDMA/ucma: Don't allow join attempts for unsupported AF family  [Leon Romanovsky]
eaa053a  RDMA/ucma: Check that device exists prior to accessing it  [Leon Romanovsky]
09399e6  RDMA/ucma: Check that device is connected prior to access it  [Leon Romanovsky]
609adb5  RDMA/ucma: Ensure that CM_ID exists prior to access it  [Leon Romanovsky]
6a30cb2  RDMA/ucma: Fix use-after-free access in ucma_close  [Leon Romanovsky]
eb9b80f  RDMA/ucma: Check AF family prior resolving address  [Leon Romanovsky]
1a87350  arm64: avoid overflow in VA_START and PAGE_OFFSET  [Nick Desaulniers]
0513608  selinux: Remove redundant check for unknown labeling behavior  [Matthias Kaehlcke]
d9486bc  netfilter: ctnetlink: Make some parameters integer to avoid enum mismatch  [Matthias Kaehlcke]

====================
     2021-01-27    
====================

project device/xiaomi/markw/
39053dc  markw: zygote: enable unspecialized app process pool  [Jesse Chan]
f3b1689  markw: Ditch amplifier support  [ShihabZzz]

project kernel/xiaomi/markw/
a7234a4  tty: provide tty_name() even without CONFIG_TTY  [Arnd Bergmann]
91af14e  frv: declare jiffies to be located in the .data section  [Matthias Kaehlcke]
3c681b1  jiffies.h: declare jiffies and jiffies_64 with ____cacheline_aligned_in_smp  [Matthias Kaehlcke]
dc605f3  fs: compat: Remove warning from COMPATIBLE_IOCTL  [Mark Charlebois]
42f7317  selinux: Remove unnecessary check of array base in selinux_set_mapping()  [Matthias Kaehlcke]
2fc62d3  cpumask: Add helper cpumask_available()  [Matthias Kaehlcke]
f7099a6  genirq: Use cpumask_available() for check of cpumask variable  [Matthias Kaehlcke]
4a7f602  netfilter: nf_nat_h323: fix logical-not-parentheses warning  [Nick Desaulniers]
a257c74  Input: mousedev - fix implicit conversion warning  [Nick Desaulniers]
19f5145  dm ioctl: remove double parentheses  [Matthias Kaehlcke]
c824055  ACPI, PCI, irq: remove redundant check for null string pointer  [Colin Ian King]
a3208ac  net: systemport: Rewrite __bcm_sysport_tx_reclaim()  [Florian Fainelli]

====================
     2021-01-26    
====================

project kernel/xiaomi/markw/
2c58e7b  bpf, x64: increase number of passes  [Daniel Borkmann]
f6f951ac  kbuild: disable clang's default use of -fmerge-all-constants  [Daniel Borkmann]
1a20ade  x86/boot/64: Verify alignment of the LOAD segment  [H.J. Lu]
776dfa9  x86/build/64: Force the linker to use 2MB page size  [H.J. Lu]
8cd0e5d  mtd: nand: fsl_ifc: Fix nand waitfunc return value  [Jagdish Gediya]
1712239  drm/radeon: Don't turn off DP sink when disconnected  [Michel Dänzer]
c511188  ahci: Add PCI-id for the Highpoint Rocketraid 644L card  [Hans de Goede]
db33619  PCI: Add function 1 DMA alias quirk for Highpoint RocketRAID 644L  [Hans de Goede]
a8dbff1  RDMA/iwpm: Fix uninitialized error code in iwpm_send_mapinfo()  [Geert Uytterhoeven]
497ca02  Input: twl4030-pwrbutton - use correct device for irq request  [Sebastian Reichel]
4afe494  drm/nouveau/kms: Increase max retries in scanout position queries.  [Mario Kleiner]
2567efe  mmc: sdhci-of-esdhc: limit SD clock for ls1012a/ls1046a  [yangbo lu]
80fc124  NFS: don't try to cross a mountpount when there isn't one there.  [NeilBrown]
5f025d1  infiniband/uverbs: Fix integer overflows  [Vlad Tsyrklevich]
fda10bc  netfilter: xt_CT: fix refcnt leak on error path  [Gao Feng]
09db8e5  iommu/omap: Register driver before setting IOMMU ops  [Suman Anna]
4d64449b  rtc: cmos: Do not assume irq 8 for rtc when there are no legacy irqs  [Hans de Goede]
9174f48  block: fix use-after-free in disk_part_iter_next  [Ming Lei]
84ee15b  block: rsxx: select CONFIG_CRC32  [Arnd Bergmann]
3b90369  wil6210: select CONFIG_CRC32  [Arnd Bergmann]
19709da  cpufreq: powernow-k8: pass policy rather than use cpufreq_cpu_get()  [Colin Ian King]

====================
     2021-01-25    
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

