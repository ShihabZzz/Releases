====================
     2020-12-16    
====================

project build/make/
faf147f  build: Remove some debugging props  [Henrique Silva]
1903192  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
26bbf0f  markw: fix restorecon_recursive command sequence  [Jiten Patel]
f71e602  markw: init.qcom.rc: remove unused property  [Sean Tranchetti]
9041298  markw: Misc update & cleanup  [ShihabZzz]

project frameworks/base/
e521875  SystemUI: Remove build version from qs footer  [Pranav Vashi]
c001432  RebootTile: Make default state inactive  [Pranav Vashi]
bff2131  Extend reboot tile to add power off  [Pranav Vashi]
f1a0a2a  RebootTile: Fix gradient message display for reboot to recovery  [Pranav Vashi]
643fa8f  Add Reboot/Recovery QS Tile  [fusionjack]
511c817  SystemUI: Update SoundTile  [Ali B]
93f37e6  QS: Add Sound tile to Quick Settings  [Yoshinori Hirano]
734b7a1  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
4cf508e  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
1e58b13  base: Add metric for Blinx Settings  [David Trpchevski]
2cc2d16  PrivacyItemController: Enable permission hub by default  [Luca Stefani]
955af32  NavBar: Don't crash when we can't find navigation overlays  [Alessandro Astone]
faed335  camera: Support exposing aux camera to apps  [Sauhard Pande]
066f999  SystemUI: Use AVCProfileMain for screen recorder  [Arne Coucheron]
f3b3f0b  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
2e4f31b  PowerProfile: allow overriding default power profile  [Alexander Martinz]
abf6e34  power: Re-introduce custom charging sounds  [Bruno Martins]
1f267ef  incremental: Fix more clang-tidy warnings  [Luca Stefani]
ee20a9d  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
0d82f75  IncrementalService: Fix clang-tidy warning  [Luca Stefani]
e7701b9  AutoBrightness: Remove handler's messages before send.  [yangyankai1]
aa6dd79  Unregistering PackageMonitor only when has registered it  [Zhuying Li]
dbdea98  IdleMaint: run IdleMaint if battery is charging  [Jaegeuk Kim]
0084a33  SystemUI: use DOUBLE_TAP_TO_WAKE setting also for wake from aod  [maxwen]
8d288d1  SystemUI: Fix uneven volume icon padding in status bar  [Danny Lin]
bed7b35  SystemUI: Restore analog and bubble clock styles  [Danny Lin]
f6232ff  Revert "Disable ClockOptionsProvider"  [Danny Lin]
c4df634  overlays: Fix icon pack target packages for AOSP  [Danny Lin]
6cb4f79  QS: Opportunistically show 3 rows with media player  [Danny Lin]

project frameworks/native/
7e654fc  input: Adjust priority  [Steve Kondik]

project frameworks/opt/net/wifi/
005bfdd  wifi: Not reset country code for Dual SIM if any slot is active  [Hu Wang]
99be4e5  WiFi: Ignore connectivity scans during WFD session  [Arif Hussain]

project frameworks/opt/telephony/
a1e4d1c  RIL: Fix manual network selection with old modem  [faust93]
44df502  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
272c6bb  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
76c4b4c  Fix imsi info error when insert some china operator card.  [qiongz]
8c556b8  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
159ac63  Fix to block sim selection popup for data  [Susheel Nyamala]
60b5dbc  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
aa44a67  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
580786d  Enable vendor Telephony plugin  [Sneh Bansal]
93d30d0  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
69bd01c  wifi: Add support for Dual Station combination.  [Khanjan Desai]
f42962f  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]
5f35fa6  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
4156551  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
16afddc  livedisplay: Initial conversion to aidl  [Pig]

project hardware/qcom-caf/wlan/
bb71c38  wcnss-service: Opt-in to disable copying WCNSS_qcom_cfg.ini to userdata  [Michael Bestas]

project lineage-sdk/
99c8dd3  Profile: Don't NPE when service is not started  [Alessandro Astone]
2e1dc90  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/mirror/
b421d0f  Updated aosp-minimal to 16-Dec-2020 13:01 UTC  [Tim Schumacher]

project packages/apps/Camera2/
d841a97  AOSP/Camera2 - Fix bug causing edit, share, delete buttons to not appear  [Colin Marsch]
f1a5344  AOSP/Camera2 - Remove Saving bar after taking a photo  [Colin Marsch]
de53407  AOSP/Camera2 - Update Storage method to be compatible with API 29  [Colin Marsch]
d56f214  Revert "Revert "Camera2: Migrate to new storage API""  [Colin Marsch]
e1740dc  Revert "Camera2: Migrate to new storage API"  [Raman Tenneti]
3a3ecd5  Camera2: Migrate to new storage API  [Shuzhen Wang]

project packages/apps/Contacts/
db69088  Contacts: Enable support for device contact.  [Toha]

project packages/apps/Dialer/
3282616  Fix selecting phone account dialog show error.  [Grace Jia]
9250433  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/Gallery2/
7a5a6d3  Gallery2: Remove LOCAL_NDK_STL_VARIANT  [Arne Coucheron]
a6a4925  Gallery2: Fix jni build warnings  [Luca Stefani]
53fd84a  Fix warnings and set Werror flag to not let them happen again.  [Tomasz Wasilczyk]
00f63f0  Remove application/SDP from Gallery2's ACTION_VIEW and REVIEW filters.  [Fares Alhassen]
051703e  Revert "AOSP/Gallery2 - Updated to sdkVersion 29."  [Raman Tenneti]
34354db  Remove use of android.text.format.Time class  [Neil Fuller]
e449a43  Cleanup warnings in jni.  [Dan Albert]
af98265  Revert "Fix compiling warnings"  [Michael Bestas]
118ac93  AOSP/Gallery2 - Updated to sdkVersion 29.  [Raman Tenneti]
9eff6ff  AOSP/Gallery2 - Updated to sdkVersion 29. Deleted usage of GROUP BY from the WHERE clause. Changed all COUNT(*) to COUNT(_id).  [Raman Tenneti]
9386920  Gallery: rotate icon is counter-clockwise, so do it!  [SpiritCroc]
89f23ee  Bump API to match dependencies.  [Dan Albert]

project packages/apps/Messaging/
a43c0b9  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
59f92a1  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]
fa7a972  Mark messages as failed if SIM is inactive  [Taesu Lee]
a536231  Fix creating a new conversation including own number  [Taesu Lee]

project packages/apps/Settings/
08756b3  Add translations for face unlock strings  [Chirayu Desai]
0ff633d  Add strings for face unlock feature  [Chirayu Desai]
8619419  Settings: Enable permission hub by default  [Luca Stefani]
4bbf480  Revert "Remove permission bar chart in Privacy setting"  [Michael Bestas]

project packages/apps/Stk/
e0e75c0  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project packages/apps/Trebuchet/
0aab69e  Trebuchet: Move privapp perms to system_ext  [Nolen Johnson]

project packages/modules/CaptivePortalLogin/
73468f6  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
a4b8a6b  Remove webview from the view system before destroying webview  [lucaslin]
09ccf33  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
47f3321  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/providers/ContactsProvider/
4772c02  ContactsProvider: Prevent device contact being deleted.  [Toha]

project packages/providers/MediaProvider/
5c7f549  MediaProvider: Fix sorting by DATE_TAKEN  [BeYkeRYkt]

project packages/providers/TelephonyProvider/
4f3235c  Fix wrong index access in getSingleMessageFromIcc()  [Taesu Lee]
82718ff  Support delete all the messages in SIM  [Taesu Lee]
46ab285  Fallback to other address type for EF_SMS  [Taesu Lee]

project packages/services/BuiltInPrintService/
4c6694b  use RGB when delivering images to printers  [Glade Diviney]

project system/core/
66752dc  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
da9af0c  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
c94e3d8  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]
4b05abc  Boost init priority before main loop  [Wei Wang]

project system/media/
436ecb4  media: update path for vendor specific config files  [Banajit Goswami]

project system/netd/
a3947bd  netd: Allow devices to force-add directly-connected routes  [Lukas0610]

project system/vold/
f8125ec  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
1c3d75c  Fix the group permissions of the sdcard root.  [Jani Lusikka]
80ee1dc  vold ext4/f2fs: do not use dirsync if we're mounting adopted storage  [Sam Mortimer]
d01142a  vold: Mount ext4/f2fs portable storage with sdcard_posix  [Jani Lusikka]
0983655  vold: Honor mount options for ext4/f2fs partitions  [Tom Marshall]
4a6b796  vold: Support internal storage partitions  [Tom Marshall]
a91b688  vold: Fix fsck on public volumes  [Michael Bestas]
e966b95  vold: add support for more filesystems for public storage  [Dan Pasanen]

project vendor/lineage/
fdf4b1d  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
f4729d9  config: Allow more legacy apps to use conversation notifications  [Danny Lin]
43804d4  repopick: Always use path override from args when it is provided  [Michael Bestas]
9cce7e2  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
efd50f7  lineage: repopick: pick only open changes in a topic  [Akhil Narang]
4562fe4  prebuilt: Remove content-types.properties  [Han Wang]
0adb3e0  ThemePicker: Define clocks stub package  [Danny Lin]
d02c314  SystemUI: Whitelist QuickAccessWallet plugin  [Danny Lin]
7a31b36  config: Build QuickAccessWallet plugin for SystemUI  [Danny Lin]

project vendor/qcom/opensource/interfaces/
0b195ee  interfaces: Introduce vendor.qti.hardware.audiohalext@1.0 HAL  [Alexander Koskovich]

project vendor/qcom/opensource/power/
97c6726  power: Kill "Failed to acquire lock" log  [Luca Stefani]
e10abaa  power: Handle setBoost interaction events  [Arian]

====================
     2020-12-15    
====================

project build/make/
be5c38a  Remove unused locale data for recovery  [Alessandro Astone]

project device/xiaomi/markw/
11a816e  markw: Update CarrierConfig from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]

project lineage/mirror/
6f597a9  Updated to 15-Dec-2020 13:11 UTC  [Kevin F. Haggerty]
9240572  Updated lineage-minimal to 15-Dec-2020 13:02 UTC  [Tim Schumacher]
cfcbbb1  Updated to 15-Dec-2020 13:01 UTC  [Tim Schumacher]

project vendor/lineage/
46b6e3a  extract_utils: generate_prop_list: Ignore vdex/odex files too  [Alessandro Astone]

====================
     2020-12-14    
====================
project android/
647418a  Switch to our forks of QCOM display / gps / media  [Elektroschmock]
3bc4dc9  Track our external/perfetto fork  [Sourajit Karmakar]

project device/xiaomi/markw/
8967ffb  markw: Sync qti_whitelist with LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
9c8a955  markw: Update public libraries from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]
30e9d8b  markw: Kang libmmrtp blobs from vangogh  [ZeeLog]
268455d  markw: Update sha1sum for modified ims.apk  [ZeeLog]
1d7bdf6  markw: Add WFD lib dependencies from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
5c7fd2c  markw: sepolicy: Address same process HALs denials  [ZeeLog]
6dd741c  markw: Update blobs from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
e076959  markw: Add missing display color blobs  [ZeeLog]
02c0b11  markw: Update CarrierConfig overlays from vangogh  [ShihabZzz]
e797b43  markw: Update IMS stack from vangogh  [ZeeLog]

project hardware/qcom-caf/msm8996/display/
3e35170  Checkout 'display-commonsys-intf' from https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/display-commonsys-intf/log/?h=LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]
2c415b8  Merge tag 'LA.UM.9.6.2.r1-03300-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into eleven-4.x  [ShihabZzz]

project hardware/qcom-caf/msm8996/media/
3fe4b1f  Merge tag 'LA.UM.9.6.2.r1-03300-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into eleven-4.x  [ShihabZzz]

project hardware/qcom/gps/
9bd070f  msm8084: Silence build warnings  [Elektroschmock]
159f240  msm8084: Remove obsolete BUILD_TINY_ANDROID check  [Elektroschmock]
eedfcce  msm8084: Cleanup obsolete LOCAL_PRELINK_MODULE  [Ying Wang]
6bcd73b  msm8084: Removing header copying to out folder  [Dante Russo]
db07d0e  gps: Correct week rollover timestamps  [jlask]
975c6c4  gps: Fix for buffer overrun crash at copying nmea string  [Katz Yamada]
571805e  gps: msm8960: Fix compiler warnings  [Arne Coucheron]
32b3068  msm8960: Return the correct length of nmea sentence  [Dante Russo]
6743135  gps: msm8960: Move device dependent modules to /vendor  [Diego Wilson]
361bb7b  gps: msm8960: Cleanup obsolete LOCAL_PRELINK_MODULE  [Ying Wang]
e32f328  msm8960: Default apn ip type to ipv4  [Dante Russo]
e2764a2  msm8960: Add support for IPV6 in AGPS Interface  [Dante Russo]
df74739  msm8084: Return the correct length of nmea sentence  [Dante Russo]
61e7709  msm8084: gps: Fix for buffer overrun crash at copying nmea string  [Katz Yamada]
b98fe34  msm8084: gps: Fix for buffer overrun crash at copying nmea string  [Katz Yamada]
0f8cf71  gps: Add libprocessgroup dependency to set_sched_policy users  [Suren Baghdasaryan]
8685b07  msm8084: Handle race condition in HAL post SSR  [Hema Iyer Sankaranarayanan]
635aa37  msm8084: Memory management fixes  [Kevin Tang]
3fff53f  msm8084: Add new event mask for timezone  [Tushar Janefalkar]
d2b147d  msm8084: Remove reporting gps status from loc eng layer  [Dante Russo]
0dff100  msm8084: Remove Redundant Log  [Jiafei Wen]
dd596d1  msm8084: LocTimer repeated expiration  [Kevin Tang]
e8ced5c  msm8084: MsgTask thread must call associator function always  [Neethu Joseph]
5dd9cca  msm8084: Adding a number of utilities  [Kevin Tang]
d963c73  msm8084: gps.conf parameters are in sap.conf table  [Kevin Tang]
f61483c  msm8084: Adding Mutex for Creating Context  [Jiafei Wen]
07c4f40  msm8084: Removed unused code and unnecessary notice files  [Qiang Chen]
b344df7  msm8084: Avoiding race conditions during the pallellized builds in Android system  [sudarsanarao makupalli]
64ddab7  msm8974: Add -Wno-error to compile with global -Werror.  [Chih-Hung Hsieh]
7a94733  msm8974: Return the correct length of nmea sentence  [Dante Russo]
92b1f1e  msm8974: Don't rely on transitively included headers  [Jiyong Park]
106587c  msm8974: Fix logging level and remove nmea log  [Dante Russo]
24fab77  msm8974: Fix duplicate gps.conf for hammerhead  [Dan Willemsen]
6328367  msm8974: Move device dependent modules to /vendor  [Diego Wilson]
3d009ea  msm8974: Cleanup obsolete LOCAL_PRELINK_MODULE  [Ying Wang]
e2b2a0b  msm8974: Default apn ip type to ipv4  [Dante Russo]
fb735fb  msm8974: Add missing liblog dependency  [Dimitry Ivanov]
616adc9  Revert "msm8974: remove from top level makefile"  [Chirayu Desai]
55896f7  Revert "msm8974: deprecate msm8974"  [Chirayu Desai]

project lineage/mirror/
45f0dae  Updated to 14-Dec-2020 16:02 UTC  [Kevin F. Haggerty]

project lineage/wiki/
ca6bc32  devices: klteactivexx: We don't support the AT&T varaint  [Nolen Johnson]
8776c6f  devices: flo: State that 17.1 and beyond codename is now flox  [Nolen Johnson]

project packages/apps/Settings/
93dfef7  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project vendor/lineage/
2855e94  soong: add TARGET_HAS_MEMFD_BACKPORT conditional  [Jan Altensen]

project vendor/xiaomi/
b992efb  markw: Kang libmmrtp blobs from vangogh  [ZeeLog]
67d9409  markw: ims.apk: Fix video call orientation  [ZeeLog]
1632817  markw: Add WFD lib dependencies from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
bf5d36d  markw: Update blobs from from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
6ffcf98  markw: Add missing display color blobs  [ZeeLog]
fec272f  markw: Update IMS Stack from vangogh  [ZeeLog]

====================
     2020-12-13    
====================

project lineage/mirror/
0c24537  Updated to 13-Dec-2020 13:01 UTC  [Tim Schumacher]

====================
     2020-12-12    
====================
project android/
3c9029f  Lineage 18.1  [Michael Bestas]
b765901  manifest: android-11.0.0_r17 -> android-11.0.0_r19  [Michael Bestas]
b9752fc  README: Jenkins is dead, so point to its replacement  [Bruno Martins]

project art/
dd1d9ba  art: Conditionally remove version check for memfd_create()  [Nicholas Lim]

project bootable/recovery/
dc9268f  recovery: make /etc/fstab only include entries that match the detected fs type  [Alessandro Astone]
0c3b2bd  recovery: Don't print mount errors when checking for encryption  [Alessandro]
ac5322f  recovery: Hide unmountable volumes from selection  [Tom Marshall]
f698d9f  recovery: Implement a volume manager  [Tom Marshall]
9e6ff0f  Return the correct action for PromptAndWait  [Kelvin Zhang]
576edb3  applypatch: Update recovery only when enabled in Updater settings  [Brint E. Kriebel]
f5818ed  minui: Allow skipping EV_REL input devices.  [Vitalii Kulikov]
18dc716  recovery: allow A/B updater to downgrade  [Alessandro Astone]
304cbe6  recovery: Allow bypassing signature verification on non-release builds  [Tom Marshall]
a882d20  recovery: wipe bootloader message from index 0 when using custom offsets  [Alessandro Astone]
0e369f4  recovery: Allow custom bootloader msg offset in block misc  [Alessandro Astone]
ee62384  recovery: Handle LINEAGE_VERSION_APPEND_TIME_OF_DAY in ver_date  [LuK1337]
0da37be  recovery: Always use the text menu for rescue party  [Alessandro Astone]
860bca1  recovery: Draw header lines with less padding  [Alessandro Astone]
4806147  recovery: Map logical partitions before installation  [Erfan Abdi]
c02e5bd  recovery: Remove the "Format system partition" menu on A/B devices  [Richard Hansen]
af7f7a5  recovery_ui: Tell the user they're actually formatting  [Nolen Johnson]
f3d15c0  bootable: Read all asserts in case there are more than one  [Hernán Castañón]
bd68af6  recovery: use ensure_volume_unmounted in format_volume  [Alessandro Astone]
d8c81de  recovery: Add runtime checks for A/B vs traditional updates  [Christopher N. Hesse]
f81e1c4  recovery: Add "Enable ADB" to advanced options  [LuK1337]
084a831  recovery: Print the active slot  [Richard Hansen]
22d7623  recovery: Display recovery version  [Richard Hansen]
356f5c5  recovery: Draw the help message below the menu on non-touch devices  [Richard Hansen]
898adc2  recovery: Clarify help text  [Richard Hansen]
2275561  recovery: Set the INFO color to the recovery/fastboot light color  [Richard Hansen]
0eeabc5  recovery: apply new design to menu padding, color and arrow  [Jesse Chan]
7848b56  recovery: Stop showing fastbootd logo for devices without it  [Nicholas Lim]
a4495a9  recovery: add new recovery and fastbootd logos  [Alessandro Astone]
1c38f83  recovery: compute displayable item count while drawing  [Alessandro Astone]
abb943d  recovery: Dejank the menus  [Tom Marshall]
19a7e58  recovery: split in submenus  [Tom Marshall]
abdd2a9  recovery: calibrate touchscreen  [Tom Marshall]
c4071b4  recovery: New install/progress animation  [Tom Marshall]
5bfb844  recovery: touch UI  [Alessandro Astone]
73ac9ef  recovery: simple graphical ui  [Alessandro Astone]
188035e  recovery: Mark as Lineage Recovery  [Nolen Johnson]
6c1a7cf  recovery: allow opting-in to fastbootd  [Alessandro Astone]
0417e1c  recovery: sdcard is data/media/0  [Alessandro Astone]
43bde98  recovery: symlink /sbin for script compatibility  [Alessandro Astone]
72ad19a  recovery: init: mount pstore fs  [Vojtech Bocek]
7846dc4  recovery: Puke out an /etc/fstab so stuff like busybox/toybox is happy  [Steve Kondik]
31d4783  recovery: Get a proper shell environment in recovery  [Steve Kondik]
a9e7fa0  recovery: Provide caching for sideload files  [Tom Marshall]
d59526b  Don't allow formatting & mounting system on user builds  [Luca Stefani]
601503f  recovery: Also hide rescue mode from non eng builds  [Michael Bestas]
2f56de8  recovery: Only show tests in eng builds  [Michael Bestas]
f8291f3  recovery: Expose reboot to recovery option  [Michael Bestas]
9650b0a  recovery: Enable the menu for User builds  [Pat Erley]
1dcb3a4  recovery: Add wipe system partition option  [Michael Bestas]
7974218  recovery_utils: add support for unmounting entire volumes  [Simon Shields]
82ca10b  recovery: Don't consider manual install aborts as errors  [Alessandro Astone]
1e0e1df  recovery: Provide sideload cancellation  [Tom Marshall]
7b1aa85  recovery: Allow device-specific recovery modules  [Matt Mower]
040f18e  recovery: Blank screen on init  [Michael Bestas]
29a07e7  recovery: ui: Support hardware virtual keys  [Tom Marshall]
23b4b88  recovery: ui: Minor cleanup for touch code  [Tom Marshall]
3cfc7fb  recovery: ui: Default to touch enabled  [Tom Marshall]
b1eaf78  recovery: Remove HOST_OS guard for f2fs tools  [Tom Marshall]
c304500  Bring back file-based OTA edify functions  [Michael Bestas]

project build/blueprint/
48e46e9  Add CreateAliasVariation  [Colin Cross]
ddd8175  Combine variant fields into variant struct  [Colin Cross]
91768e7  Add ReplaceDependeciesIf to allow for conditional replacement  [Paul Duffin]
6a922fe  Add ctx.OtherModule(Reverse)DependencyVariantExists.  [Martin Stjernholm]

project build/make/
9a6a725  soong: Add ability to build scudo-free 32-bit libc variant.  [Quallenauge]
63d22c5  Switch boot jars package check to use dexdump xml output  [Paul Duffin]
1ec6a23  Add $(PRODUCT_OUT)/install to INTERNAL_RECOVERYIMAGE_FILES  [LuK1337]
802eddb  check_boot_jars: Add QCOM WFD to whitelist  [LuK1337]
300dea3  Bring old CheckJar back and use for non-dex jars  [LuK1337]
3a96832  Switch boot jars package check to using dex jars  [Paul Duffin]
bf678a9  Stop including vendor specific clear_vars.mk  [Michael Bestas]
0149ce9  Add build support for XZ ramdisks  [Luca Stefani]
3314e0c  Fix recovery image generation with LZ4 compressed ramdisk  [Arne Coucheron]
d50fd46  build: allow refreshmod with external out directory  [Alessandro Astone]
f8f0098  soong: add TARGET_SPECIFIC_HEADER_PATH  [Jan Altensen]
ce32fb2  Drop lineage soong product variables inclusion  [Pig]
6a098a0  Unset BOARD_EXT4_SHARE_DUP_BLOCKS  [LuK1337]
0ef23dc  Allow a device to generically define its own headers  [Ricardo Cerqueira]
20bac47  All operating systems are beautiful  [Christopher N. Hesse]
142d9c7  build_image: Allow disabling custom inode count calculation  [Christian Oder]
8c79664  releasetools: do not remove dynamic partitions in system-only builds  [Peter Cai]
ed285e3  NFC: Disable build for AOSP NFC  [Bhuvan Varshney]
2080d8c  check_boot_jars: Add IFAA Manager to whitelist  [Michael Bestas]
37644b3  check_boot_jars: Add CAF IMS to whitelist  [Felix]
6f61be7  Add LineageOS additions to boot jars whitelist  [Luca Stefani]
5f2a3bd  build: Make sure we're building our secondary resource package as dependency.  [Adnan Begovic]
a62cde1  build/target: Include Lineage platform jar in system server.  [Adnan Begovic]
5bec9e9  backuptool: do not unmap dynamic partition after finished  [Jesse Chan]
d489a13  releasetools: support dynamic partitions for backuptool  [Jesse Chan]
bd80e0c  releasetools: Move system mount handling to backuptool  [Davide Garberi]
beeaa2c  releasetools: squash backuptool support  [Chris Soyars]
4f82bb1  releasetools: Use the first entry of a mount point when reading fstab  [Brint E. Kriebel]
8bb8147  Edify: Add abort message for bootloader asserts  [Matt Mower]
def3f14  ota: Disable downgrade check  [Andrew Dodd]
cd3efe1  Add blank_unblank_on_init to PRIVATE_RECOVERY_UI_PROPERTIES  [Michael Bestas]
f246357  Allow setting the recovery density separately from the aapt config  [Chirayu Desai]
f62793b  build: Separate commands in recovery foreach loops  [Matt Mower]
4776bee  build: recovery: Support adding device-specific items  [Tom Marshall]
cd87c62  build: ota: Support for install tools in /tmp/install  [Tom Marshall]
17eb189  releasetools: ota_from_target_files: add FullOTA_PostValidate  [M1cha]
c024555  Add missing languages  [Michael W]
2946eaf  Don't enable ADB by default on userdebug builds  [Michael Bestas]
c015033  build: Add support for device tree in boot.img  [David Ng]
71fd15b  Add BOARD_CUSTOM_BOOTIMG_MK support  [Ricardo Cerqueira]
5899154  Don't make recovery patch for devices with prebuilt vendor  [TheScarastic]
c35861a  Allow override of device asserts, including multi-device support.  [Steve Kondik]
7724468  Move recovery-from-boot.p from /system to /vendor  [dianlujitao]
5cea7d3  build: Ensure /system unmounted at install start  [Matt Mower]
6c67d7e  core: Add support for overriding build.prop settings  [Koushik Dutta]
323b6db  build: Automatically replace old-style kernel header includes with new header lib  [Rashed Abdel-Tawab]
a9f9427  Add extra variables to _readonly_late_variables  [dianlujitao]
9f00744  Add roomservice  [Koushik Dutta]
2617411  build: Add Lineage build support  [Luca Stefani]

project device/generic/goldfish-opengl/
5259dd9  android-emu: Fix -Wunused-function warning  [Luca Stefani]
b940188  android-emu: Fix -Wunused-parameter warnings  [Luca Stefani]
d1495b0  vulkan: Remove unused variable  [Luca Stefani]
9f9ec2b  libOpenglSystemCommon: Fix -Wformat warnings  [Luca Stefani]

project device/qcom/sepolicy-legacy/
480fed5  legacy: display.qservice is now a vendor service for everyone  [Bruno Martins]

project device/xiaomi/markw/
696879c  markw: Remove hbtp components  [Ethan Chen]
cbe2051  markw: audio: remove inexistent package  [ZeeLog]
be3ec8a  markw: Build Fwk-detect vendor variant  [ZeeLog]
f1b801c  markw: ims: silence all ims dpl related logspam  [ZeeLog]
ddb2a26  markw: bluetooth: Disable clean turn on  [Nolen Johnson]
34130f9  markw: Build Health HAL 2.1  [ZeeLog]
dba4866  markw: camera: silence excessive logs  [ZeeLog]

project external/e2fsprogs/
f6638bb  resize: Make a target for standalone resize2fs_static binary  [Bruno Martins]
cd5d3e7  Mark libext2_blkid as vendor available  [LuK1337]

project external/gptfdisk/
9f871cd  gptfdisk: include gptcl.h after sgdisk.h  [Tom Marshall]
93fc48e  gptfdisk: Provide sgdisk_read for direct reads of the partition table  [Tom Marshall]
6457c36  gptfdisk: Build lib for recovery  [Tom Marshall]

project external/guice/
341b365  guice: Remove .class files from srcjar  [Luca Stefani]
dafe43d  guice: Make guice_munge_srcjar generation quiet  [Luca Stefani]

project external/libcxx/
8e12f3e  Make libc++fs vendor available and as a shared lib  [Aaron Kling]

project external/mksh/
7703b0f  mksh: Set TERM to xterm-256color  [Luca Stefani]
8f2a4a8  mksh: don't use /data/local for TMPDIR in recovery  [Alessandro Astone]
bfed213  mksh: Mark mkshrc as recovery_available  [Michael Bestas]

project external/perfetto/
8efd17c  perfetto: Conditionally remove version check for memfd_create()  [Wang Han]

project external/tinyalsa/
65b23d8  Mark tinymix/tinyplay as vendor_available  [Michael Bestas]

project external/tinycompress/
d78bf3b  tinycompress: Conditionally enable extended compress format  [Michael Bestas]
a230b0d  tinycompress: Use generated kernel headers  [Sam Mortimer]

project frameworks/av/
800626f  stagefright: add changes related to high-framerates in CameraSource  [Paras Nagda]
3f216b8  Request to reset effect buffer in clearInputBuffer  [Ryoichi Yasutake]
27c460c  Enable legacy adaptive playback for QCOM_BSP_LEGACY  [Arne Coucheron]
5a5606d  camera: Allow devices to load custom CameraParameter code  [Pig]
3b925d3  libstagefright: Fix memory leak due to lock timeout  [Priyanka Gujjula]
121ece3  Camera: check metadata type before releasing frame  [Milos Ratkovic]
03d3d20  camera/media: Support legacy HALv1 camera in mediaserver  [Simon Shields]
8ae9636  camera: include: Don't override possible overlayed header  [Bruno Martins]
007a082  libstagefright: use 64-bit usage for native_window_set_usage  [Milos Ratkovic]
d8bb39e  libstagefright: Free buffers on observer died  [Manikanta Kanamarlapudi]
eedcf47  stagefright: ACodec: Resolve empty vendor parameters usage  [Adrian DC]
f8cc94a  stagefright: omx: Don't signal dataspace change on legacy QCOM  [Arne Coucheron]
fc32a94  libstagefright: Support YVU420SemiPlanar camera format  [Ethan Chen]
294d390  camera: Don't segfault if we get a NULL parameter  [Steve Kondik]
00d8431  nuplayer: Avoid crash when codec fails to load  [Steve Kondik]
d04d6f9  Camera: Add support for preview frame fd  [Susmitha Gummalla]
dadcb34  Camera: Add extensions to CameraClient  [Shuzhen Wang]
b24b542  audiopolicy: support extended feature in audiopolicymanager  [Revathi Uddaraju]
aa5b051  audiopolicy: make audio policy extensible  [Naresh Tanniru]
e9491d3  camera: Only link and use vendor.qti.hardware.camera.device if specified  [Rashed Abdel-Tawab]
a545aca  Camera: Miscellaneous fixes in QDataCallback and binder death scenarios.  [Mounika Reddy Tangirala]
73a72df  Camera: CameraHardwareInterface changes to support Extended FD  [Sauhard Pande]
14259c0  audiopolicy: Add AudioSessionInfo API  [Steve Kondik]

project frameworks/base/
7e0f34b  Implement click to take partial screenshot [1/3]  [Jesse Chan]
d9dd94f  SystemUI: implement better partial screenshot  [Demon000]
fd41656  SettingsProvider: adaptive icon  [Asher Simonds]
02c8c82  fw/b: Add support for per app network isolation  [Sam Mortimer]
a04932b  fw/b: Squash of app fw restriction commits  [Danesh M]
eaba9b4  Updates to various icons:  [Dan Sandler]
9f34b96  FODCircleView: ensure that when we check for bouncer, we're on keyguard.  [Dil3mm4]
d73dede  SystemUI: Don't shift KeyguardSecurityContainer when FOD isn't available  [Dil3mm4]
4369843  FODCircleView: various improvements.  [Dil3mm4]
c927518  SystemUI: Allow privileged system apps to access screenshot service  [Danny Lin]
847e469  core: Expose method to start assistant through Binder  [Danny Lin]
353712c  WifiDisplayController: handle preexisting p2p connection status  [Li Sun]
b291dea  Merge changes for launching wifidisplay from system settings  [Indranil Chakraborty]
2fa684d  PowerManagerService: Add nullptr checks around button/keyboard lights  [LuK1337]
ccc135a  Implement edge long swipe gesture [1/3]  [Nico]
dcdb0b7  PackageManager: allow build-time disabling of components  [Pawit Pornkitprasan]
1b51cbb  sensors: Create bool to select what timestamp to use  [flintman]
ac09dfa  CameraServiceProxy: Loosen UID check conditionally  [Danny Baumann]
99d9d81  frameworks: Power menu customizations  [Michael Bestas]
f6fddb3  Sharesheet: Set max ranked items to 8  [LuK1337]
64bc6b6  SystemUI: Reset horizontal panel position when on keyguard  [LuK1337]
612526f  SystemUI: Handle profiles with disabled lockscreen  [LuK1337]
25277aa  fw/b: Resolve black forced lights with notifications channels  [Adrian DC]
42ae650  Pad ime_switcher same as navbar buttons  [codingkerensa]
3e363c9  fwb: Re-introduce keyboard backlight brightness control  [Bruno Martins]
6930f2c  Allow lineage resources package to be overlayed by RRO packages  [LuK1337]
ae95ff3  Only play sound effects if stream is not muted.  [David Overton]
80c55b3  SystemUI: Implement hide gestural navigation hint bar [1/5]  [Jesse Chan]
5daf701  Skip screen on animation when wake and unlock via biometrics  [Jesse Chan]
874d6ad  fw/b torch: Let long press power turn torch off when screen is on.  [Sam Mortimer]
2638fe3  SystemUI: Fix showing duplicated charging status  [Scott Warner]
3feb1ac  SystemUI: Allow disabling BrightlineFalsingManager with config flag  [Arne Coucheron]
d31050e  SystemUI: Don't sleep on double tap below status bar  [dianlujitao]
60aae8b  Check UID's process state before restricting its network.  [xiamengsen]
c597e18  PackageManager: Add configuration to specify vendor platform signatures  [Ethan Chen]
a806ea4  Forward port CM Screen Security settings (1/2)  [Michael Bestas]
1b9adc4  LockSettingsService : Restrict access to getpassword API  [Prerna Kalla]
8e32486  Fix Build Credentials refactored to use byte[]  [Justin DeMartino]
9be8995  frameworks: base: Port password retention feature  [AnilKumar Chimata]
f3512b3  SystemUI: Bring back expanded volume panel  [HrX03]
8a43aacdb  SystemUI: Adapt screenshot sound to ringer modes  [Ashwin R C]
74c6966  Remove DUN requirement for tethering  [Dave Daynard]
a159feb  Camera: allow camera to use power key as shutter  [Danesh M]
9228669  Fix WebView vulnerability by disallowing file access  [Chen Xu]
bbc5d61  Sanitize Bluetooth device names without regex  [Dan Sandler]
70f777f  Fix color mismatch of pointers  [xuejianbao]
086c21d  Fix CDM.requestNotificationAccess() in profile.  [Oasis Feng]
e9117db  Don't start fingerprint for FOD devices early  [TheScarastic]
b1a9be6  Squashed import of in-display fingerprint sensors related changes  [Peter Cai]
37ed76d  Camera: Add feature extensions  [Sauhard Pande]
18d16bf  SystemUI: Relax AVC level requirement  [Wang Han]
161aad9  frameworks/base: Support for third party NFC features and extensions  [Puneet Mishra]
9f82b6b6  SystemUI: Allow overlaying max notification icons  [LuK1337]
eb355c2  Download: Add support to manually pause/resume download  [qqzhou]
0c93eee  SystemUI: Add visualizer feature  [Utkarsh Gupta]
09fd157  SystemUI: Allow to enable Lockscreen Media Art [1/3]  [beanstown106]
fde1e80  frameworks/base: Lights notifications brightness support  [Adrian DC]
be44d03  frameworks/base: Battery and Notification Lights  [Sam Mortimer]
4452321  SystemUI: Add Profiles tile  [Roman Birg]
8f6faf7  SystemUI: Enable and fix QS detail view, adapt layout to 11  [eray orçunus]
f3bd1ca  SystemUI: Add powershare QS tile  [Linux4]
18e0333  SystemUI: Add AOD QS tile  [Marko Man]
f2b6cd5  SystemUI: Add VPN tile  [Danny Baumann]
2a6a124  SystemUI: Add reading mode tile  [Joey]
610a471  SystemUI: Add LiveDisplay tile  [Steve Kondik]
57798a0  SystemUI: Add USB Tether tile  [BestPig]
f14eb01  SystemUI: Add AmbientDisplay tile  [Adnan Begovic]
124b386  SystemUI: Add tile to show volume panel  [stofstik]
3f61bfd  SystemUI: Add Sync tile  [Altaf-Mahdi]
3bbffcc  SystemUI: Add heads up tile  [Michael Bestas]
deb2e5f  SystemUI: Add caffeine QS tile  [Keith Mok]
57878bd  SystemUI: Enable NFC tile  [Tim Schumacher]
22fbce6  SystemUI: Fix up right clock handling when showing heads up  [LuK1337]
a8cf484  Allow adjusting screen density to smaller sizes.  [Danny Baumann]
04cffc5  frameworks: Add unlinked ringtone and notification volumes  [Adnan Begovic]
ee6ef55  SystemUI: Only add GarbageMonitor tile to default tiles on ENG builds  [Arne Coucheron]
f6b7b1a  SystemUI: runtime configurable audio panel location  [a.derendyaev]
a3ed532  Implement quick QS brightness slider [1/3]  [Jesse Chan]
a36be17  SystemUI: Port statusbar brightness control  [Alberto97]
ac97928  SystemUI: Port brightness slider changes  [Alberto97]
c66b2c9  Use the try catch to deal with the StaleDataException.  [guofei.xue]
2d820b2  When the mUri is null,it will happen NullPointerException.  [guofei.xue]
96d48d1  Ringtone uri should add type query  [wan.li]
2fe1100  SystemUI: Make clock truly invisible  [Michael W]
3a5656b  Correction in logic of roundend size calculation of SD card  [Chetan Gurjar]
9695d60  SystemUI: Bring back good ol' circle battery style  [Luca Stefani]
29065ba  SystemUI: Add tunables for clock AM/PM style  [Michael Bestas]
cd4ab71  SystemUI: Add tunables for clock position  [Luca Stefani]
c0e4a2f  Keyguard: Add option to scramble pin layout when unlocking (2/2).  [Adnan]
237d6a5  Support enforcing a minimum delay between notification sounds of an app.  [Danny Baumann]
279dd4a  SystemUI: Disable heads up debugging on non eng builds  [Han Wang]
72591e6  SystemUI: Network Traffic [1/3]  [Sam Mortimer]
6e09f20  SystemUI: Add Lineage statusbar item holder  [Sam Mortimer]
2e081ab  Add an option to force pre-O apps to use full screen aspect ratio  [Jesse Chan]
f07940e  SystemUI: handle camera launch gesture from keyhandler  [Roman Birg]
25fb536  Move high touch sensitivity and hovering to InputService  [Danesh M]
446ecf5  PowerManagerService: Wake on plug (1/2)  [Jon Evans]
94ec0db  SystemUI: Add double tap to sleep gesture  [Rashed Abdel-Tawab]
5c2ce49  SystemUI: Add quick settings pull down with one finger  [Roman Birg]
fd83658  Camera button support  [HazouPH]
d2ad3ba  SystemUI: add left and right virtual buttons while typing  [Roman Birg]
561f874  SystemUI: Add navbar layout inversion tuning  [LuK1337]
0f2af9c  Add support for runtime toggle of navbar  [Bruno Martins]
5b5cb7e31  PowerManager: Add proximity check on wake  [Bruno Martins]
0f6ae09  base: add Trust usb restrictor  [Joey]
b3ee221  Fix other lights when backlight uses SurfaceController API  [Pierre-Hugues Husson]
64b76d4  PowerManager: Allow to distinguish different keypresses  [Corinna Vinschen]
a12a16f  PowerManagerService: Allow to light up buttons only when pressed  [Anas Karbila]
4b6041b  fw/b: Button backlight brightness  [Ricardo Cerqueira]
52b34ac  Forward port 'Swap volume buttons' (1/3)  [nadlabak]
6719f97  PhoneWindowManager: Allow torch and track skip during ambient display  [ezio84]
89acede  fw/b: Allow customisation of navbar app switch long press action  [Sam Mortimer]
e7631b8b  PhoneWindowManager: Implement press home to answer call  [Oleksandr Byelkin]
bd0d29f  PhoneWindowManager: Tap volume buttons to answer call  [martincz]
f271dd5  Reimplement device hardware wake keys support  [LuK1337]
ed88353  Reimplement hardware keys custom rebinding  [Phil Tunstall]
9cc078b  Long-press power while display is off for torch  [beanstown106]
5efbbb8  PhoneWindowManager: add LineageButtons volumekey hook  [Simon Shields]
6d3ca2d  Framework: Volume key cursor control  [Konsta]
05b7137  Allow lid to send a generic COVER_CHANGED broadcast  [jrior001]
15f0f99  FingerprintService: Prevent cleanup of unused fingerprints  [codeworkx]
c169ce0  biometrics: Allow posting reset runnable for all clients  [LuK1337]
ca30f8b  fingerprint: handle PerformanceStats NULL pointers  [Ícaro Hoff]
42ac423  SystemUI: Dismiss keyguard on boot if disabled by current profile  [Gabriele M]
ef1ecd3  SystemUI: Show bluetooth battery level when available  [LuK1337]
79c6df8  SystemUI: support black theme for dark mode [1/4]  [Jesse Chan]
2953a7c  Squashed import of adb root patches  [LuK1337]
0460db5  SystemUI: Allow using tuner API for LineageSettings  [Rashed Abdel-Tawab]
bdac799  SystemUI: Bringup tuner navbar and statusbar changes  [Rashed Abdel-Tawab]
98e96e4  fw/b: Use ro.build.date to signal OTA upgrades  [dhacker29]
6e1f0df  Screenshot: Append app name to filename  [ezio84]
d7cccbe  webkit: SystemImpl: Make systemIsDebuggable() check IS_ENG as well  [LuK1337]
7c18b19  Enable Binder Proxy Tracking by Uid only on eng builds  [dianlujitao]
7b62910  Disable notification channel warnings by default  [Bruno Martins]
2a58013  WiredAccessoryManager: support for multiple display ports  [Vignesh Kulothungan]
2958c7a  audio: update WiredAccessoryManager to use ExtconUEventObserver based on events available  [Dhananjay Kumar]
f2e9556  WiredAccessoryManager: Support for multiple extconn devices  [Haynes Mathew George]
e842bc6  WiredAccessoryManager: update extcon file paths  [Aalique Grahame]
0bdfc1c  WiredAccessoryManager: Add support for DisplayPort Audio  [Revathi Uddaraju]
408d334  SystemUI: Add support for persistent usb drive notification.  [Adnan Begovic]
f5b7346  SystemUI: Allow snoozing SD card notification unconditionally  [LuK1337]
7a53163  SystemUI: Sync sw600dp and sw600dp-port notification_panel_width  [LuK1337]
19e01dc  Fix bug Device that can't support adoptable storage cannot read the sdcard.  [sangho.yoon]
8f64852  UpdateEngine: Add perf mode binder interface  [Luca Stefani]
7aaeab8  SystemUI: Fix toggling lockscreen rotation [1/3]  [Dan Pasanen]
f854f4f  Configurable 0, 90, 180 and 270 degree rotation  [Ricardo Cerqueira]
92df502  Support for device specific key handlers  [Bruno Martins]
2e2b0b6  SettingsProvider: Allow accessing LineageSettings via settings command  [d34d]
18063ed  SystemUI: Add lineage-sdk dep  [Sam Mortimer]
5b401f9  services: Include org.lineageos.platform.internal  [Rashed Abdel-Tawab]
014c067  services: Kick off to LineageSystemServer for external service init.  [Adnan Begovic]
dca3212  Add lineage sdk resource APK to Zygote FD whitelist  [Steve Kondik]
88415f7  androidfw: Squash of declare and load lineage sdk resource package w/ id  [Adnan Begovic]

project frameworks/native/
b17859e  DO NOT MERGE Correct physical orientation  [liyong]
32184c1  Correct PowerManager transaction IDs. These transaction IDs must be kept in sync with the method order from IPowerManager.aidl.  [Wang Wen]
ab44e2a  SurfaceFlinger: Don't cleanup resources from previous frame  [Arne Coucheron]
381416d  surfaceflinger: Add support for extension lib  [Pierre-Hugues Husson]
ff2caa1  sf: Exclude VDS use of HWC on non-UM platforms  [dianlujitao]
23776d7  sf: Fix virtual display related issues.  [Ramakant Singh]
1794f2f  Forward port 'Swap volume buttons' (2/3)  [nadlabak]
c7ad867  InputDispatcher: On keypress, deliver keycode to pokeUserActivity  [Corinna Vinschen]
b4b8205  PowerManager.h: Define USER_ACTIVITY_FLAG values  [Corinna Vinschen]
8bf8bf5  libui: Allow extension of valid gralloc 1.0 buffer usage bits  [Kevin F. Haggerty]

project frameworks/opt/net/wifi/
e6611b3  resurrect mWifiLinkLayerStatsSupported counter  [Stefan Assmann]

project frameworks/opt/timezonepicker/
05af715  Restore time_zone_item ripple effect  [LuK1337]
dee8f19  Change ItemBackground for Black Theme  [Gitsaibot]

project hardware/broadcom/libbt/
ec39e72  correct WBS config VSC params  [Nagarjuna Kristam]
bc15025  libbt: configure audio codec right after firmware  [z3DD3r]
b5ed425  libbt: Add support for using two stop bits  [Steve Kondik]
78e3ee3  libbt: Add btlock support  [Steve Kondik]
88e8c8c  libbt: Add prepatch support  [Steve Kondik]

project hardware/interfaces/
434a7c2  camera: Only link and use vendor.qti.hardware.camera.device if specified  [Rashed Abdel-Tawab]

project hardware/libhardware/
90e3ce2  hardware/libhw: Add display_defs.h to declare custom enums/flags  [Arun Kumar K.R]
f3ad567  libhardware: Add new display types.  [Dileep Marchya]
1535276  audio: Add audio amplifier HAL  [Ethan Chen]

project hardware/libhardware_legacy/
bcaaf65  Add wifi_add_or_remove_virtual_intf() to the legacy wifi hal  [Purushottam Kushwaha]

project hardware/qcom/data/ipacfg-mgr/
d9334ba  ipacfg-mgr: Use generated kernel headers  [Bruno Martins]
9d85206  Kernel Header Changes  [arnav_s]

project hardware/qcom/sdm845/display/
39287d7  Add C2D_COLOR_FORMAT_420_TP10 to C2D_YUV_FORMAT  [LuK1337]
cd86365  display: Fix path to vendor/qcom/opensource  [razorloves]

project hardware/ril/
f958793  Make RIL command headers overlayable by devices.  [Danny Baumann]
51d4358  FR51015: Tuning of Binder buffer for rild.  [Ruthwar Ambeer]
21ae3dc  libril: Fix manual network selection with old modem  [faust93]
a6d44aa  libril: Restore support for RIL v6, v8 and v9 stacks  [Adrian DC]
572c16a  libril: Bounds check s_commands  [Paul Keith]
386a7ab  libril: allow board to provide libril  [Tom Giordano]

project packages/apps/Camera2/
0632ee8  jni: Build libs against current sdk  [Michael Bestas]
8e47084  Camera2: Remove LOCAL_NDK_STL_VARIANT  [Arne Coucheron]
f60db97  Camera2: Fix missing permissions failure on boot  [doc HD]
56e8170  Camera2: Move to /system_ext  [LuK1337]
e00eb75  AOSP/Camera2: there is no camera icon shown if have no camera in first boot up  [zhang sanshan]
d465bd3  Dismiss keyguard when opening settings  [Felix]
bdd8558  Camera2: Request for ACCESS_FINE_LOCATION permission  [Wang Han]
5403c73  Fix crash if Exif-Tag buffer-length and component-count are both 0  [tobigun]
0c2e7a7  Camera2: Fix Undo button behaviour  [NBruderman]
6006140  Camera2: Remove google help preference  [Michael Bestas]
fa71118  Camera2: Add option to set max screen brightness  [Michael Bestas]
164dad0  Camera2: Add privapp permissions xml  [Michael Bestas]
e988822  Camera: Powerkey shutter (2/2)  [Danesh M]
428662a  Camera2: Remove settings preferences only once  [Konsta]
546bb5f  Camera2: Only autofocus before a snap if we are actually in "auto" mode.  [Steve Kondik]
56f0987  Don't attempt to convert degree to orientation enum twice  [Ethan Chen]
9dcbec1  Camera2: adaptive icon  [Asher Simonds]

project packages/apps/Dialer/
b60bd6c  Dialer: handle database downgrade from lineage-16.0  [Michael Bestas]
c4d7fbe  Fix theme for PostCallActivity  [Sungjae]
4b937fc  Fix translation of 'contacts' tab title and main menu.  [Danny Baumann]
e729d8b   Failed to show hold call when user click swap and merge simultaneously  [rongmei.li]
f5251dc  Dialer: Use a DayNight launch theme  [Scott Warner]
97cca09  Dialer: allow framework to do dark theming automatically  [Jesse Chan]
1efec63  Updated target SDK from 28 to 29.  [Raman Tenneti]
9f88668  Dialer: AudioModeProvider: use wired route for usb headsets  [codeworkx]
bfe4fea  Control dialer's incoming call proximity sensor check via an overlay  [blunden]
f7d5150  Re-add dialer lookup.  [Xiao-Long Chen]
b51f11c  Re-add call statistics.  [Danny Baumann]
ce6bc0e  Allow per-call account selection.  [Danny Baumann]
a6593be  Re-add call recording.  [Danny Baumann]
399647d  Add setting to enable Do Not Disturb during calls  [blunden]
25237ec  Generalize the in-call vibration settings category  [blunden]
7c55bb4  Add back in-call vibration features  [Danny Baumann]
491fb7a  Revert "Remove dialer sounds and vibrations settings fragments and redirect to the system sound settings fragment instead."  [Danny Baumann]
a00c299  Dialer: disable anti-falsing for call answer screen  [Adrian DC]
8ca4832  Dialer: adaptive icon  [Asher Simonds]
d73e998  Dialer: define app category  [Joey]
96251f2  Dialer: Fix proto warning with optmize for lite  [Luca Stefani]

project packages/apps/Messaging/
1f8c1f3  Messaging: Contact Colors  [Blaise]
47be79c  Messaging: Use a DayNight launch theme  [Scott Warner]
6e50d8e  Messaging: disable auto dark theming on message bubble  [Jesse Chan]
9e28ebe  Messaging: allow framework to do dark theming automatically  [Jesse Chan]
9d72e33  Messaging: Require external legacy storage  [Han Wang]
23d247e  Messaging: bump target SDK version to 29  [Jesse Chan]
db537f7  Messaging: Add sysconfig whitelist xml  [Michael Bestas]
c973721  Messaging: Notification channel string fixes  [Michael Bestas]
66f2711  Messaging: Implement per conversation channels. Update API level to 28.  [Luca Stefani]
1fb2c6c  Don't build with platform certificate  [Luca Stefani]
1658805  Messaging: use white nav bar  [Joey]
833c903  MediaPicker: Check for NPE  [Ankit Gupta]
e455fbd  Play an audible notification on receiving a class zero message.  [Arun Valiaparambil]
c467414  Messaging: bring back accent color  [jrizzoli]
26e8634  Messaging: Toggable keyboard emoticons access  [AdrianDC]
2f39149  Messaging: Implement option for swipe right to delete.  [Adnan Begovic]
2663a37  Messaging: adaptive icon  [Asher Simonds]
2fefbe4  Messaging: define app category  [Joey]
85b59bf  Fix NoSuchMethodError for getTypeInfo()  [Taesu Lee]
47f994a  Remove advanced category if no preference  [Taesu Lee]
ad56918  AOSP/Messaging - Changed minSdkVersion to 19.  [Raman Tenneti]
d1ab9de  Fix SecurityException at getActiveSubscriptionInfoList() on N and O  [Taesu Lee]
49d065c  Fix app initialization issue if no permissions  [Taesu Lee]
c7526d0  AOSP/Messaging - Changed midSdkVersion to 14 and reverted to using Telephony.Carriers.CONTENT_URI instead of  Telephony.Carriers.SIM_APN_URI.  [Raman Tenneti]
c3208cc  Remove only one Lambda Exp for JAVA 7  [Taesu Lee]
24c8a63  Fix handling format based on API level accordingly.  [Taesu Lee]
addcc49  Fix creating ConnectivityUtil to work on any platform  [Taesu Lee]
c9d2882  Fix missing computeIfAbsent() method in L_MR1 and M  [Taesu Lee]
b916953  Remove unnecessary methods from MmsUtils  [Taesu Lee]
ee56742  Allow call to phone numbers or voice mail numbers only  [Taesu Lee]
be50095  Check CONFIG_SEND_MULTIPART_SMS_AS_SEPARATE_MESSAGES always  [Taesu Lee]
d0256b1  Fix ConcurrentModificationException  [Taesu Lee]
36f49e4  Parse recipients from RESPOND_VIA_MESSAGE correctly  [Taesu Lee]
6064046  Remove dead code  [Taesu Lee]
5fa0673  Disallow making a call to emergency numbers  [Taesu Lee]
549ca47  Check whether dialable only  [Taesu Lee]
da34882  Auto re-sending MMS for all the transient failures  [Taesu Lee]
7332c3d  Rescheduling pending messages after outside window failure  [Taesu Lee]
0f67717  Fix NPE on MultiConversationNotificationState  [Taesu Lee]
121597e  Hide APN prefs if platform APIs are used  [Taesu Lee]
2c01f3e  Use ic_add_white for consistency instead  [Taesu Lee]
7ef588b  Fix to show APN prefs correctly  [Taesu Lee]
4f1dc87  Fix NPE  [Taesu Lee]
135873f  Handle delivered messages as completed messages  [Taesu Lee]
f644f3c  Dismiss SnackBar when detached  [Taesu Lee]
9557ae8  Fix assert fail during onSaveInstanceState()  [Taesu Lee]
520936c  Fix WindowLeaked issue on AttachmentPreview  [Taesu Lee]
2f894e9  Fix undesirable ripple effect on GalleryGridView  [Taesu Lee]
4bcc718  New interface to pick a contact as attachment  [Taesu Lee]
60949fd  ProcessPendingMessagesAction works based on subscriptions  [Taesu Lee]
2e48262  Allow intent shared subject or title to be mms subject  [Marco Sirabella]
651630b  Update runner to AndroidJUnittest  [Julien Desprez]

project packages/apps/PermissionController/
e0086a8  PermissionController: Enable permission hub by default  [Luca Stefani]

project packages/apps/Settings/
49282c1  Hide ADB Root preference on user builds  [Luca Stefani]
38504e5  Settings: Bump privacy category's initial expanded children count to 10  [LuK1337]
b432122  Don't change nouns in summaries to lower case for German  [Danny Baumann]
9b81e22  Settings: Fix the failing strings  [Michael Bestas]
4624eac  Allow sorting Applications by size  [Roman Royer]
90ab4ba  Settings: Add support for per app network isolation  [Sam Mortimer]
fd3152a  Settings: per-app cellular data, vpn and wifi restrictions  [Uldiniad]

project packages/apps/SettingsIntelligence/
1dcca1c  Normalize dynamic search result in Japanese  [Qiang Wu]
184a8cb  Scrolling search results and autorotate cause crash  [Pingzhi Wang]
12d0b74  SettingsIntelligence: Regen database on build version change  [Luca Stefani]
379b205  SettingsIntelligence: Match Settings style  [Luca Stefani]

project packages/apps/ThemePicker/
5198c08  ThemePicker: Grant missing wallpaper permissions  [Danny Lin]
ea62629  ThemePicker: Use title capitalization for style name field  [Danny Lin]
48ef1d8  ThemePicker: Use more descriptive icon pack names  [Danny Lin]

project packages/apps/Trebuchet/
f702057  Launcher3: Fix launcher preview rendering  [Danny Lin]

project packages/apps/Updater/
988181a  Update Changelog server URL  [ShihabZzz]
69726cd  Unofficial OTA configuration  [David Trpchevski]

project packages/apps/WallpaperPicker2/
d2ff99d  WallpaperPicker2: Declare usage of missing permissions  [Danny Lin]

project packages/inputmethods/LatinIME/
c3e0809  LatinIME: Update emojis  [Michael Bestas]
f6c0dab  Include Bulgarian Extended Keyboard Layout  [Iliya Bazlyankov]
a85cc5d  LatinIME: Move keyboard height setting from debug to advanced  [Tom Marshall]
d3fab05  LatinIME: Fix back-arrow finishing activity  [Michael W]
1c575ad  LatinIME: Remove dividers everywhere  [Michael W]
5ce2310  LatinIME: Do we really still want Holo?  [Michael W]
9f91cf9  LatinIME: Add setting for theme to follow system setting  [Michael W]
bd6fcb3  LatinIME: Update key_styles_currency euro lists.  [Arekusu Rin]
3d71981  LatinIME: Add Luxembourgish keyboard & spellchecking dictionary  [Michel Weimerskirch]
f59a7c7  LatinIME: Add support for Australian English  [Michael Bestas]
3e7fb6f  Add support for Bépo keyboard layout  [Julien "_FrnchFrgg_" RIVAUD]
315163f  LatinIME: Add Hungarian QWERTY, enable predictive dictionary  [dh-harald]
835c994  LatinIME: HU enable predictive dictionary and remove unused letters  [Tamás Tóth]
df1f93c  LatinIME: Enable spellchecker for additional languages  [blunden]
e3c8d4b  LatinIME: Add Bulgarian, Georgian and Ukrainian wordlists  [Michael Bestas]
ac70137  LatinIME: Set proper keyboard for Georgian script  [Vasyl Gello]
bebe62e  LatinIME: Add new type for Bulgarian script  [Vasyl Gello]
fa2ce62  LatinIME: Add "more" keys to ALL the keys  [Steve Kondik]
8573064  LatinIME: Add shortcuts support  [Janet Sun]
ea9e685  Don't interrupt active gesture input by modifier key presses.  [Danny Baumann]
eaaf601  LatinIME: Add fallback loader for JNI lib  [Steve Kondik]
04ad7cc  LatinIME: Update emojis  [Joey Rizzoli]
cc22619  LatinIME: disable sound on keypress on all devices by default  [Dan Pasanen]
1e5f097  LatinIME: Regenerate KeyboardTextsTable  [Michael Bestas]
023af59  LatinIME: support for incognito mode  [Joey]
333046d  Fix send button not being centered for non-standard densities.  [Danny Baumann]

project packages/providers/BlockedNumberProvider/
64fbbf4  BlockedNumberProvider: adaptive icon  [Asher Simonds]

project packages/providers/BookmarkProvider/
b920966  BookmarkProvider: adaptive icon  [Asher Simonds]

project packages/providers/CalendarProvider/
dc089ae  CalendarProvider: adaptive icon  [Asher Simonds]

project packages/providers/CallLogProvider/
1de0689  CallLogBackup: adaptive icon  [Asher Simonds]

project packages/wallpapers/LivePicker/
af4f4f5  LivePicker: adaptive icon  [Joey]

project prebuilts/build-tools/
c1ce7c0  prebuilts: Update xz to non-broken version  [Kevin F. Haggerty]

project prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/
be79a1c  gcc-4.9: Restore GCC  [Josh Fox (XlxFoXxlX)]

project prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/
da10d2b  gcc-4.9: Restore GCC  [Josh Fox (XlxFoXxlX)]

project prebuilts/gcc/linux-x86/x86/x86_64-linux-android-4.9/
33cdb04  gcc-4.9: Restore GCC  [althafvly]

project system/incremental_delivery/
766ee48  libdataloader: Don't pollute namespace with android::dataloader  [Luca Stefani]
7b61dda  incfs: Get rid of short ab for android::base  [Luca Stefani]
a5f61b4  incfs: Don't pollute namespace with android::incfs  [Luca Stefani]
9ec5044  incfs: Don't pollute namespace with std::chrono  [Luca Stefani]
73a3d2a  incfs: Don't pollute namespace with sysprop  [Luca Stefani]

project system/libufdt/
4eff1af  mkdtboimg: Sanitize dt filename  [Luca Stefani]
98fabd4  mkdtboimg: Allow specifying full path for dtb  [Luca Stefani]
8f61df6  Make mkdtboimg.py compatible with python3  [Hridya Valsaraju]
707b8d3  mkdtboimg: fix redundant 1 argument on compression_info()  [Gah0]
5796e2f  mkdtboimg: Add support to V0 DTBO image creation  [Luca Stefani]
8ad9ed9  mkdtboimg: Make filepath search recursive  [Luca Stefani]

project system/netd/
48947dc  system/netd: Add support for per app network isolation  [Sam Mortimer]
3a676b8  system/netd: Squash of netd uid bandwidth restriction commits  [Uldiniad]

project system/sepolicy/
b9adc43  Export missing audio volume properties  [Michael Bestas]
faa2181  Allow init to write to /proc/cpu/alignment  [Kevin F. Haggerty]
31f3ea2  sepolicy: Treat proc-based DT fstab the same and sys-based  [Kevin F. Haggerty]
2814cfc  Fix storaged access to /sys/block/mmcblk0/stat after 48027a00  [Vladimir Oltean]

project system/tools/mkbootimg/
ed76fcc  mkbootimg: add support for --dt  [M1cha]

project system/update_engine/
5374eaa  update_engine: Run backuptool only in debuggable builds  [Luca Stefani]
82e5255  update_engine: Transition to backuptool domain  [Luca Stefani]
62ab9bb  update_engine: Run backuptool script before normal postinstall script  [Dan Pasanen]
0b01022  update_engine: Add performance mode  [Gabriele M]

project vendor/lineage/
e1df13e  Lineage 18.1 is here for Xmas  [Bruno Martins]

project vendor/qcom/opensource/commonsys/packages/apps/Bluetooth/
7d38518  Bluetooth: Require libbluetooth_qti instead of libbluetooth  [Pig]
e3be86d  Use component flag to configure profile support flag.  [weichinweng]
afbb7b9  Remove dependency on telephony-common from Bluetooth  [Zongheng Wang]
d29bde0  BT: Prefer LDAC over aptX family  [dianlujitao]
fe081bd  Bluetooth string: removed id="sender" in bt_sm_2_1_  [Yinchu Chen]
7978a0c  translate="false" -> translatable="false"  [Edward Savage-Jones]
381444b  Remove intent filter without any action  [Bruno Martins]
193e06b  Fix null pointer exception on AvrcpTargetService  [slki.shin]
032d1ad  Bluetooth: Remove unused string resources  [Michael Bestas]

project vendor/qcom/opensource/commonsys/system/bt/
4afbf1c  Return after removing sample LTK device  [li-wei.cheng]
ee95a4e  Fix possible OOB when receive gatt read type response data  [weichinweng]
e051ef0  Remove pairing on incoming bond request  [Myles Watson]
37aa413  Enable bitpool sanity checks  [Joseph Pirozzo]
0564d32  GattServcer: Check invalid offset  [Hansong Zhang]

project vendor/qcom/opensource/interfaces/
c715742  interfaces: Introduce vendor.qti.hardware.btconfigstore@2.0 HAL  [Volodymyr Zhdanov]

====================
     2020-12-11    
====================

project external/chromium-webview/
33ab33d  Update Chromium Webview to 87.0.4280.101  [Kevin F. Haggerty]

project kernel/xiaomi/markw/
6e1682b  Redux: 1.03  [ShihabZzz]
91d3361  arm:dts: msm8953: Add clock-frequency property  [Remicaa]
797a2f6  thermal: Do not log an error if thermal_zone_get_temp returns -EAGAIN  [Hans de Goede]
72a2820  msm_thermal: initialize later than arch drivers  [Park Ju Hyung]
ade25a4  msm: ipa: update msm_ipa.h with latest IPA versions constants  [Ghanim Fodi]
fbfb861  Redux: 1.0  [ShihabZzz]
4fd7020f  Quark: 1.17  [ShihabZzz]
634c29b  Merge tag 'v1.0.20201112' of https://github.com/WireGuard/wireguard-linux-compat into lineage-17.1  [ShihabZzz]
f5999a3  Revert "noise: take lock when removing handshake entry from table"  [ShihabZzz]

project lineage-sdk/
6b80931  PerformanceManagerService: Account for QCOM perf HAL 2.0  [Han Wang]

project lineage/mirror/
e5a9d33  Updated aosp-minimal to 11-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
7c6d2f5  wiki: Add Nexus 7 2013 Wi-Fi Repartitioned (flox)  [surblazer]

====================
     2020-12-10    
====================

project device/xiaomi/markw/
ef32c70  markw: Add netutils-wrapper to device compatibility matrix.  [Yifan Hong]
15e9eec  markw: Restore Radio/IMS blobs from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]
7002436  markw: Update extractor scripts  [ShihabZzz]
2d1093b  markw: init: Override sensor HAL service access  [ZeeLog]
57e9988  markw: Remove vendor prefix from low power mode prop  [ShihabZzz]

project lineage/mirror/
a9d0a89  Updated aosp-minimal to 10-Dec-2020 13:01 UTC  [Tim Schumacher]

project vendor/lineage/
b4e31b2  README: Jenkins is dead, so point to its replacement  [Bruno Martins]
29f1e8a  README: Just point to Wiki for build instructions  [Bruno Martins]

====================
     2020-12-09    
====================
project android/
dea881f  manifest: switch to our fork of system/netd  [Oliver Scott]

project build/soong/
0e0bfb7  Add ability to enable scudo-free 32-bit libc variant.  [Quallenauge]
60ece2d  cleanbuild: Add `install` to installclean files  [LuK1337]
7e5cbc1  Add support for macOS 11 SDK  [Dan Willemsen]
e7c330b  soong: Add equivalent for LOCAL_EXPORT_CFLAGS  [Alessandro Astone]
0cf1d1c  Add dumpvars for WITH_SU and WITH_GMS  [Abhisek Devkota]
1959a9e  soong: Add LINEAGE_VERSION to dumpvars  [Rashed Abdel-Tawab]
5989a57  soong: allow overriding header files  [Jan Altensen]
1666f2c  soong: Drop lineage soong product variables  [Pig]
ddf5458  soong: Give priority to modules in exported namespaces for bootjars  [Sam Mortimer]
9078314  soong: Squash of lineage-sdk bringup commits  [Rashed Abdel-Tawab]
c743f0c  soong sbox: Add option to allow copying all generated output  [Sam Mortimer]
087b65e  soong: Make sure to preserve lineage product variables  [dianlujitao]
691b181  soong: add support for nested structs in variableProperties  [Simon Shields]
ccfd636  soong: extend with lineage board flags  [Simon Shields]
191bf4e  soong: Add PathForSourceRelaxed  [Sam Mortimer]
8122ae5  Reland: Deduplicate APEX variants that would build identically  [Colin Cross]
c432a7f  Rename ApexName to ApexVariationName  [Colin Cross]

project device/qcom/sepolicy-legacy/
ade08dc  legacy-common: Resolve camera daemon denial on system_data_root_file  [Arne Coucheron]
f875f7d  legacy-common: Label cam_socket0 file  [Arne Coucheron]

project lineage/mirror/
4b293a7  Updated to 09-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/scripts/
550c7d8  Update default webview to 87.0.4280.101  [Kevin F. Haggerty]

project packages/apps/ThemePicker/
4d1f350  ThemePicker: Fix ugly black/transparent bar under nav area  [LuK1337]
b2f28ce  Fix preview tile in grid option picker  [Marc K]
88306a4  ThemePicker: Show item name under the category name  [El Dainosor]
85ec3d5  ThemePicker: limit number of icon previews shown  [Demon000]

====================
     2020-12-08    
====================

project art/
b7102e8  Add an option to disable sse4.2 features  [Luca Stefani]

project bionic/
e3c150e  Add ability to build scudo-free 32-bit libc variant.  [Quallenauge]
7b86399  bionic: Support wildcards in cached hosts file  [Tom Marshall]
cc2b855  bionic: Sort and cache hosts file data for fast lookup  [Tom Marshall]
c9a49c1  linker: Convert lineage product variables to soong config variables  [LuK1337]
519a618  bionic: Squash of pre-P mutex behavior restoration  [Ethan Chen]
fc1fe32  Implement per-process target SDK version override.  [Danny Baumann]
f935cf5  libc: Mark libstdc++ as vendor available  [Rashed Abdel-Tawab]
36a43e5  linker: Add support for dynamic SHIM libraries  [Christopher R. Palmer]
7182b0a  Add inaddr.h header file  [Roopesh Rajashekharaiah Nataraja]

project build/make/
de925c0  Source lineage specific envsetup  [Michael Bestas]
0a7f3d7  envsetup: export ANDROID_BUILD_TOP earlier  [Chirayu Desai]
3818652  build: Include vendor/extra/BoardConfigExtra.mk if available  [Steve Kondik]
a25a453  Sync modules required by releasetools  [Luca Stefani]
759bc20  Build required modules from default  [Kiyoung Kim]
1795072  releasetools: Use du -b  [Chirayu Desai]
b206b86  Remove empty new-space in dynamic_partition_list and super_$(group)_partition_list  [Luca Stefani]
c9a6d53  Refactor how MODULES-IN-* is defined  [Dan Willemsen]

project build/soong/
3eef007  Add CreateAliasVariation to BottomUpMutatorContext  [Colin Cross]
3e99975  Restrict replacements of source dependencies with prebuilts  [Paul Duffin]
4850982  Stop java_sdk_library_import from depending on source modules  [Paul Duffin]
b14a8d4  Track the current java_sdk_library(_import) deps  [Paul Duffin]
c07f891  Avoid creating APEX variant for sdk member  [Paul Duffin]
a0a95f1  apexDepsMutator uses WalkDeps  [Jooyung Han]
824d95d  Remove conditional running of checklast during checkapi  [Anton Hansson]
67fed44  cleanbuild: add *.zip.md5sum to installclean_files  [Michael Bestas]

project development/
4d3d497  privapp_permissions: Check product privapp_permissions  [Christian Oder]

project device/generic/goldfish/
4394963  camera: Fix -Wformat warnings  [Luca Stefani]
fbabf0a  camera: Set missing functions to NULL  [Luca Stefani]

project device/google/atv/
388260c  Disable Traceur on userdebug  [Aaron Kling]

project frameworks/av/
131ab4e  Allow graceful degradation of MediaProfile with broken configuration.  [Alex Zhang]

project frameworks/base/
635c656  Allow adjusting progress on touch events.  [Danny Baumann]
fcd1c33  perf: Add support for HIDL Lineage power HAL  [dianlujitao]
3874e9c  LockPatternUtils: Make settings getter and setters protected  [d34d]
16c3196  Check for null callerPackage in getStorageEncryptionStatus  [Ethan Chen]
4037370  admin: Restore requireSecureKeyguard interface.  [Adnan Begovic]
ab92d93  fw/b: Add NotificationGroup class for use by lineage sdk system profiles  [Martin Long]

project frameworks/native/
16aef7c  Add vendor version for libgui  [Vinay Verma]
3df7916  [cleanup] Fix a clang-tidy warning  [Yurii Zubrytskyi]
77fb8a9  SurfaceFlingerProperties: Use proper prop scope  [Luca Stefani]
ee89b02  SurfaceFlingerProperties: Use proper prop scope  [Luca Stefani]

project frameworks/opt/net/wifi/
cf6fa56  wifi_hal: add slsi wifi hal support  [Jan Altensen]

project frameworks/opt/telephony/
a69a76f  Telephony: Add option for using regular poll state for airplane mode  [Arne Coucheron]
1c2c0c3  2G wants proper signal strength too  [Arne Coucheron]
9263b72  Avoid SubscriptionManager#getUriForSubscriptionId calls with invalid subIds  [Bruno Martins]
2d14a23  Remove setIsoCountryProperty method along with partially dead code  [Bruno Martins]
b29ba20  telephony: Squashed support for simactivation feature  [Bruno Martins]
aa4c7f1  Failed to show hold call when user click swap and merge simultaneously  [rongmei.li]
ce2f337  Truncate baseband version string to 45 characters at most  [Yujing Gu]

project hardware/interfaces/
0c6c407  Camed HAL extension: Added support in HIDL for Extended FD.  [Sauhard Pande]
91aa7cc  keymasterV4_0: Tags support for FBE wrapped key.  [Shivaprasad Hongal]

project hardware/nxp/nfc/
512adbd  nfc: Restore pn548 support to 1.1 HAL  [Rashed Abdel-Tawab]

project kernel/xiaomi/markw/
1ca7495  Merge tag 'ASB-2020-12-05_3.18'  [ShihabZzz]

project lineage/mirror/
9494c1d  Updated aosp-minimal to 08-Dec-2020 13:01 UTC  [Tim Schumacher]

project packages/apps/Bluetooth/
17330d5  Bluetooth string: removed id="sender" in bt_sm_2_1_  [Yinchu Chen]

project packages/apps/CarrierConfig/
980db98  Fix voicemail for Bouygues Telecom France  [gnumdk]

project packages/apps/Contacts/
ba16711  Contacts: Make the launch screen follow the system theme  [Scott Warner]
5725635  Contacts: manually configure dark theme for list  [Jesse Chan]
e48a175  Contacts: allow framework to do dark theming automatically  [Jesse Chan]
c1974f3  Contacts: use white nav bar  [Joey]
3409386  Allow calling contacts via specific phone accounts.  [Danny Baumann]
1280855  Place EmergencyInfo shortcut on drawer  [yuichiro fujiwara]
60121da  Place MyInfo shortcut on drawer  [yuichiro fujiwara]
3713221  Contacts: adaptive icon  [Asher Simonds]
ba98dde  Contacts: define app category  [Joey]

project packages/apps/DeskClock/
a47f676  Provide upgrade path for cm-14.1 -> lineage-18.0  [Pavel Kirpichyov]
cae4d4c  DeskClock: Properly align settings  [Michael W]
47af23e  DeskClock: Move notification channel strings for translation  [Michael Bestas]
4ef6d49  DeskClock: Fix german translation of "days"  [Michael W]
ea98b72  DeskClock: Setup data model before calling super.onStart()  [LuK1337]
5c4625e  DeskClock: Fix FAB not being shown everytime  [Michael W]
9ef3d79  DeskClock: Replace ViewPager with manual fragment handling  [Michael W]
248c679  DeskClock: Move navigation bar to bottom  [Michael W]
7829e74  DeskClock: also apply disabled color to annotations  [Jesse Chan]
aa0db9f  DeskClock: Come to the dark side...  [Michael W]
a62d5e8  DeskClock: Modernize timer_setup_time look  [LuK1337]
20b3001  DeskClock: Update drawables  [LuK1337]
7da2d84  DeskClock: Use sans-serif-thin font for the clock widget  [Arne Coucheron]
c2d5352  DeskClock: Add some more visible shadow to the clock widget  [Arne Coucheron]
a110ac9  DeskClock: Use POWER_OFF_ALARM permission  [Mao Jinlong]
f086ad8  DeskClock: Add support of power off alarm feature  [Mao Jinlong]
bbd8031  DeskClock: Add back flip and shake actions  [Wilhelm Fitzpatrick]
88de0c3  DeskClock: adaptive icon  [Asher Simonds]
107b550  Deskclock: define app category  [Joey]
8dd096c  DeskClock: Add sysconfig whitelist xml  [Michael Bestas]
a62e779  AOSP/DeskClock - Clean up some TODOs and deprecated calls  [Colin Marsch]
0cbc389  AOSP/DeskClock - Fix deprecated calls: ScreensaverSettings,SettingsActivity  [Colin Marsch]
c6da36a  AOSP/DeskClock - Upgrade Handler inits to use undeprecated constructor  [Colin Marsch]
676ae03  AOSP/DeskClock - Update Fragment related code to use AndroidX  [Colin Marsch]
96c7cd5  DeskClock: Rework notification channel implementation  [Michael W]
b7718e7  AOSP/DeskClock: Improve AlarmNotification priority to pop up alarm  notification.  [Raman Tenneti]
dcefd87  AOSP/DeskClock - Call executePendingTransactions only if mFragmentManager is not destroyed. Fixes the crash bug. Code matches internal code.  [Raman Tenneti]
8376293  Import translations. DO NOT MERGE  [Bill Yi]
e37ea18  AOSP/DeskClock - Updated to sdkVersion 29.  [Raman Tenneti]
053cd71  Change most notfications category  [Marko Man]
0f8acd1  Require USE_FULL_SCREEN_INTENT permission  [Marko Man]

project packages/apps/DocumentsUI/
b6314dc  Remove unused string resources  [Michael Bestas]
d7eda52  DocumentsUI: adaptive icon  [Asher Simonds]
ea4cd39  DocumentsUI: define appcategory  [Joey]

project packages/apps/Nfc/
f057190  NFC: Adding new vendor specific interface to NFC Service  [Puneet Mishra]
264a547  Avoid NFC continuous crash  [Maoliang Tang]

project packages/apps/PhoneCommon/
5799e79  Mark dialpad letters as untranslatable.  [Grace Jia]

project packages/apps/Settings/
160c4af  get outer NFC preference to listen for changes  [inthewaves]
82e6e8a  Remove unused translations  [Michael Bestas]
ddcb918  Set highest priority as default value to Bluetooth codec  [timhypeng]
af6dd73  [Telephony settings] Settings crashes when rotate screen in Preferred network type  [changbetty]
329b799  Fix for incorrect display of preferred network type on UI  [Avinash Nalluri]
11d0e20  Avoid unexpected state changes for enhanced preferences  [Taesu Lee]
d59ff4a  [Settings] subscription UI should be closed when SIM is removed  [Bonian Chen]
0417b03  Add NR network type to "Global" mode preference  [Avinash Nalluri]
dab1304  Settings: Fix exception in about phone during SIM swap  [hoffc]
6a2fdb0  Prevent errors when updating operator pref summary  [Sneh Bansal]
de15d02  Improve the performance of displaying preference - multithread.  [Zoey Chen]
3162f57  Remove "storage type" preference from Settings  [joffenberg]
034512c  Fix mvno data field summary not update issue  [Wei Huang]
7990093  Fix NPE if default supervisor is not defined  [Wang Han]
7943d29  Disable 'Mobile data' selection after removing SIM  [Grace Jia]
b1e143b  Settings: Hide carrier settings version if empty  [Wang Han]
f8b03f2  Preserve icon for "manage space"  [Wang Han]
efa41ca  Button text for app space management is overwritten  [Pingzhi Wang]
77ca1bd  Usb preference title changed when rotating  [Xinli Zhang]
ab5e0ca  RESTRICT AUTOMERGE Allow LockScreenPattern to be launched in the pinning screen  [Mill Chen]
ea9d859  Fix NPE in PanelFragment  [Daniel Hunt]
30c892f  Fix for User edit info dialog during rotation  [Rafael Matias de Lima]
1c2b374  Settings: Pass Locale.US when formatting refresh rate string  [LuK1337]
28945c4  Settings: Add preference for KEY_MIN_REFRESH_RATE  [LuK1337]
4fd8e72  Settings: Check if we have any color modes declared in overlay  [Luca Stefani]
eae4c1f  Backup: Don't hardcode ignored backup transports  [Michael Bestas]
1733186  Settings: Add rotation settings  [Steve Kondik]
9b4f038  One does not simply become a Developer  [Chirayu Desai]
d09824f  Settings: Add advanced restart switch  [Steve Kondik]
5d1d508  Allow the user to change the BackupTransport  [Torsten Grote]
fd58eb5  Fix resultCodes from WifiPickerActivity  [inthewaves]
68f0e48  Settings: Only show gesture navigation if device has a software nav bar  [Rashed Abdel-Tawab]
2c90ab6  Settings: Hide unsupported USB modes automatically  [Wang Han]
80fc36c  Settings: Set preference controller for all VideoPreference widget usages  [LuK1337]
d6a13c5  BasebandVersionPreferenceController: Trim baseband if needed  [Bruno Martins]
50b7a02  Settings: Implement hide gestural navigation hint bar [2/5]  [Jesse Chan]
eaa53d0  Settings: Hide AOD pref is device provides Doze settings  [Bruno Martins]
3744065  hardwareinfo: Hide hardware revision if empty  [Arian]
d725f70  Settings: Forward port pattern visibility settings (2/2)  [Michael Bestas]
c384940  Settings: Forward port lock pattern grid size (2/2)  [Michael Bestas]
1f11b8d  Settings: adaptive icon  [Asher Simonds]
ae860d2  Settings: Add a RemotePreference for device-specific doze settings  [Steve Kondik]
cce734e  Settings: Add lockscreen visualizer toggle  [Steve Kondik]
c2b630f  Settings: Add toggle for Lockscreen Media Art [2/3]  [beanstown106]
3b240e4  Settings: Add back battery and notification lights settings  [Sam Mortimer]
b505cdf  Settings: Add back increasing ring feature (2/2).  [Danny Baumann]
b634a6c  Settings: Fix default value for proximity on wake pref  [Pranav Vashi]
dd326a3  Settings: Add toggle for heads up notifications  [Michael Bestas]
49a329f  Settings: Use correct icon for ring volume  [Michael Bestas]
3a405b8  Settings: Add switch for linked ring and media notification volumes  [Bruno Martins]
a447e9f  Settings: Add option to scramble pin layout when unlocking (1/2).  [Adnan]
20454ca  Settings: Add setup UI for minimum delay between an app's notification sounds  [Danny Baumann]
b1c57de  Settings: battery: Add LineageParts perf profiles  [Zhao Wei Liew]
a6de312  Settings: Allow removing livedisplay pref screen with config_enableLiveDisplay  [Paul Keith]
8c0c833  Settings: Add an option to force pre-O apps to use full screen aspect ratio  [Jesse Chan]
8f511ca  Settings: Add high touch sensitivity and touchscreen hovering toggles  [LuK1337]
792804c  Settings: display: Add wake on plug switch  [Jon Evans]
19cc45e  fingerprint: Allow devices to configure sensor location  [d34d]
a541709  Settings: Allow devices to provide remote gesture preferences  [Bruno Martins]
5993236  Settings: gesture: Add LineageParts touchscreen gesture settings  [Zhao Wei Liew]
f25a3ae  Settings: Add double tap to sleep preference  [Rashed Abdel-Tawab]
f85657f  Settings: Add proximity check on wake preference  [Bruno Martins]
559b102  Settings: Fix fallback summary for power_button_instantly_locks preference  [LuK1337]
db79180  Settings: support black theme for dark mode [2/4]  [Jesse Chan]
b7b66a3  Add toggle to enable ADB root  [Luca Stefani]
96b4227  Disable notification channel warnings by default  [Bruno Martins]
3150161  Expose option to change the device hostname.  [Alex Avance]
6caa65b  Settings: Drop custom preferenceFragmentCompatStyle  [LuK1337]
702e03c  Settings: Add package name to installed app details  [Luca Stefani]
a0b311e  Settings: Add LineageOS legal info  [Roman Birg]
224fe65  Settings: Add LineageOS entries into device info  [LuK1337]
205c94a  Settings: Depend on lineage platform library  [Sam Mortimer]

project packages/apps/Stk/
f8e224a  Close Tone Dialog if the requested tone has already been stopped  [Yoshiaki Naka]
4222653  Fix the incorrect title for DISPLAY TEXT dialog.  [Umashankar Godachi]
e3b91ca  Stk: adaptive icon  [Joey]

project packages/apps/ThemePicker/
90407f9  Specify we read and write launcher settings  [Luca Stefani]
7087e99  Add wallpaper default permissions  [LuK1337]
7d8f524  Add wallpaper privapp whitelist  [Luca Stefani]

project packages/apps/Trebuchet/
80bda87  QuickStep: Google Feed integration  [Edward Cross]
20d1bd1  Trebuchet: Move Duo into Google folder as per GMS sample integration  [Bruno Martins]
465bea1  Trebuchet: Update GMS packages in the default workspaces  [Bruno Martins]
79aa869  TrebuchetGo: Add Go specific default workspace  [Bruno Martins]
4cbbef2  Launcher3: Add 2x2 workspace grid option  [Danny Lin]
acad8cc  Add missing default workspace changes in LauncherFiles  [Michael Bestas]
a0906ba  Trebuchet: optimization of searching apps in Chinese  [zhaoguomanong]
2fd00ea  Trebuchet: Add extra privapp permissions xml  [Michael Bestas]
c7ae915  Trebuchet: Allow enabling icon labels for landscape mode  [LuK1337]
3636885  Trebuchet: allow disabling workspace edit  [Joey]
0908ebd  Trebuchet: implement hidden & protected apps  [Joey]
85c5e2f  Trebuchet: add toggle for desktop and drawer labels  [Joey]
4c9caeb  Don't discard custom grid on config changes  [LuK1337]
6cefc88  Specify the component name to start the picker  [Luca Stefani]
582bf79  Specify the wallpaper picker package  [Luca Stefani]
86e8912  Properly expose GridOptionsProvider  [Luca Stefani]
274c8e8  Globally disable debug logging  [Bruno Martins]
75e5931  Launcher3: Retrieve the searchbar padding from device profile  [Chris Crump]
b437b80  QSB: request round search bar  [Edward Cross]
0b8e64e  Disable QSB on first screen by default  [Arne Coucheron]
f65d9a9  Change icon drawable padding  [Arne Coucheron]
bde2275  Trebuchet: Add 5x6, 5x7 and 6x6 default workspaces  [dwardo]
9ee8671  Replace 4x4 grid option with a 4x5 one  [Arne Coucheron]
5b88f31  Trebuchet: Update default workspace  [Bruno Martins]
d46bbd6  Trebuchet: adaptive icon  [Asher Simonds]
f2547da  Change app name to Trebuchet  [Joey]
1d1389b  DeviceProfile: fix divide by zero  [Alexander Martinz]
d08ccc4  Launcher3: Can't search out local app by Chinese  [yingrenw]
c6fdb71  Workspace: Allow resizing any widget  [Nebojsa Cvetkovic]
04f83a2  Launcher3: Stability NullPointer issue  [yingrenw]
c8e3307  Launcher3: No Calendarwidget 4x4 widget displayed  [ningl]
6342af8  Launcher3: exclude from recents  [cretin45]
9bed65d  Trebuchet: update build configs  [Joey]

project packages/apps/TvSettings/
3a46d1c  Add rooted development option  [Aaron Kling]
10e4ecb  Show Trust in security settings  [Aaron Kling]
2b6528f  Add button to shut down device  [Aaron Kling]
726fc37  Settings: Add intent to launch LineageOS platlogo upon multiple taps  [Zhao Wei Liew]
21e6a47  Add build date (ro.build.date from build.prop) to About screen.  [dhacker29]
1883cc9  One does not simply become a Developer  [dhacker29]
2c8beb9  Add LineageOS version to the About screen  [dhacker29]

project packages/apps/WallpaperPicker2/
b6bc22e  Return valid wallpaper id for PartnerWallpaperInfo  [LuK1337]

project packages/providers/ContactsProvider/
2d36cd9  CallLogDatabase: Try to re-run the version 6 upgrade path  [Quallenauge]
bc7227b  ContactsProvider: adaptive icon  [Asher Simonds]

project packages/providers/DownloadProvider/
24fcc9a  DownloadProvider: Add support for manual pause/resume  [Zhao Wei Liew]
c6ffb8f  DownloadProvider: Display download speed in notification  [Lasse Brudeskar Vikås]
2aefac8  Fix "Invalid columns in request:" errors, when there are multiple columns  [Pierre-Hugues Husson]

project packages/providers/MediaProvider/
114958f  MediaProvider: adaptive icon  [Asher Simonds]

project packages/providers/TelephonyProvider/
f1e77da  TelephonyProvider: add upgrade support from lineage-16.0  [Michael Bestas]
a5fe31e  Telephony: Upgrade: Also migrate empty strings  [Michael W]
7fa04a5  TelephonyProvider: adaptive icon  [Asher Simonds]
69c1351  Fix MmsSmsDatabaseHelper onUpgrade always destroying the database  [Michael Bestas]

project packages/services/Mms/
645a0b3  Mms: adaptive icon  [Asher Simonds]
b820a00  Add app label  [Michael Bestas]

project packages/services/Telecomm/
f386d06  Telecomm: Squashed phone_type switch support  [Bruno Martins]
276d58d  Telecomm: adaptive icon  [Asher Simonds]
9b4e194  CallLog: Get rid of warning  [Michael W]
d33f072  Add back increasing ring feature (1/2).  [Danny Baumann]
a57db68  Telecom: Add sensitive phone numbers hooks  [Luca Stefani]

project packages/services/Telephony/
3dd8187  Telephony: Add ERI configuration for U.S. Cellular  [Arne Coucheron]
8adc11d  MSIM: Fix non-protected broadcasts sent from phone process.  [Umashankar Godachi]
ff4c49f  Telephony: Mark enhanced_4g_lte_mode_title_variant as untranslatable  [Michael Bestas]
539d6f2  Telephony: adaptive icon  [Asher Simonds]
cc1dd03  Telephony: use Build.DATE to check for system update  [maxwen]

project system/bt/
6f0accd  Add support to force disable enhanced sco commands  [cb]
d70e971  Revert "Bluetooth HFP: Use WBS by default (1/5)"  [Danny Wood]
7d3206f  Changed HID_DEV_MTU_SIZE from 64 to 512  [Danny Trunk]
b229925  gd: proto: Remove optimize_for = LITE_RUNTIME  [Luca Stefani]
6af99d6  gd: Remove unneeded optimize_for lite  [Luca Stefani]

project system/core/
e76ffcf  fs_mgr: autodetect filesystem type  [Dan Pasanen]
185dd0a  core: mark libsysutils and libdiskconfig recovery_available  [Alessandro]
73a022d  init: Convert lineage product variables to soong config variables  [Pig]
09c40c8  logcat: Map '-C' to 'logcat -v color'  [Adnan Begovic]
0750b0f  debuggerd: add Lineage version to tombstones  [Scott Mertz]
972f602  healthd: Reinitialize mChargerNames for every battery update  [Abhijeet Dharmapurikar]
722c297  healthd: Add support for HVDCP_3 chargers  [Abhijeet Dharmapurikar]
ff1ddfd  healthd: Add DASH charger type  [Steve Kondik]
ab8d649  Camera: Add feature extensions  [Sauhard Pande]
7bc78d1  init: Add vendor-specific initialization hooks.  [David Ng]
22df0a1  Add wrapped key support  [dianlujitao]
dcd8dbb  Squashed import of adb root patches  [LuK1337]
ff248cd  ziptool: restore unzip for recovery  [Alessandro Astone]
2dd35c1  adb: Add ro.adb.secure.recovery handling  [LuK1337]
ef50585  reboot: allow opting-in to fastbootd  [Alessandro Astone]
a8de8c6  Revert "Format formattable partitions if mount fails"  [Tom Marshall]
f191610  fs_mgr: mount: don't set the block device as ro for recovery  [Alessandro Astone]
f1c02e5  errno_restorer: Make bool operator explicit  [Luca Stefani]
b0139f3  Remove unneeded optimize_for lite  [Luca Stefani]
462f2f5  [cleanup] Fix a clang-tidy warning  [Yurii Zubrytskyi]
9ef4d23  adb: Look for shell executable in alternate places  [Tom Marshall]
0b265e3  init: don't skip starting a service with no domain if permissive  [William Bellavance]

project system/sepolicy/
bb4d016  Only require compat mapping files if they exist.  [Chris Gross]
2741936  sepolicy: Allow recovery to alter /  [Gabriele M]
c032133  sepolicy: whitelist recovery from node creation neverallow  [Alessandro Astone]
c65d07c  sepolicy: Add sdcard_posix_contextmount_type attribute  [LuK1337]

project system/vold/
c731e3d  vold: skip first disk change when converting MBR to GPT  [Scott Mertz]
bc2566c  Switch to exfatprogs compatible fsck parameter  [LuK1337]
c27ee42  cryptfs: Fix build for QCOM HW crypto devices  [Bruno Martins]
e51bdd2  Add "changepw" command to vdc.  [LuK1337]
740377d  vold: Adapt req-crypt based HW disk encryption  [Neeraj Soni]
cfc9229  vold: Move QCOM HW FDE inclusion under Lineage namespace  [Michael Bestas]
aa065c3  system: vold: Close crypto block device if it was created  [Neeraj Soni]
a3c9ff2  Updates for migrated code upstream  [Yifan Hong]
4b262c4  system: vold: fix block disk encryption to work with metadata encryption  [Neeraj Soni]
30e6124  Fix for CTS test CtsAppSecurityHostTestCases  [Shivaprasad Hongal]
ad92a41  system: vold: Remove crypto block device creation  [AnilKumar Chimata]
659d376  vold: Add Hardware FDE feature  [AnilKumar Chimata]
c856e2f  vold: Bring in more wrapped key changes  [Pig]
f78e6bc  system: vold: Upgrade the FBE key  [Neeraj Soni]
8df5a5a  vold: Enable legacy support for wrapped key  [Neeraj Soni]
7924840  system: vold: Use wrapped key for metadata encryption  [Neeraj Soni]

project tools/metalava/
21659a2  [Metalava] don't use reflections  [Makoto Onuki]
1cf7675  Limit metalava visibility  [Makoto Onuki]

====================
     2020-12-07    
====================
project android/
0a340db  manifest: Switch to our openssh fork  [Michael Bestas]

project device/qcom/sepolicy-legacy-um/
fab72b3  sdm660: Remove overly broad init rule  [Michael Bestas]
bbf6a73  Address init denials regarding socket_device  [Aayush Gupta]

project packages/apps/Eleven/
c31ddfd  Eleven: Increase the height of the play queue slider.  [Craig G]
fa46b8b  Eleven: Fix SettingsActivity crash  [Craig G]
06bbd2e  Eleven: 'audio.id as _id' doesn't seem to make sense  [Craig G]
3b592f0  Eleven: Fix album id column  [Craig G]
c161acb  Eleven: Fix integer overflow  [Craig G]
20c2fe0  Eleven: Remove dead code  [Bruno Martins]

====================
     2020-12-06    
====================
project android/
3de0a6a  Switch to our forks of qcom audio/ipacfg-mgr  [Michael Bestas]
9a22190  Switch to our fork of external/tinyalsa  [Michael Bestas]

====================
     2020-12-05    
====================

project device/lineage/sepolicy/
9c543b7  qcom: add msm8960 and apq8084 into upstream list  [surblazer]

project lineage-sdk/
c127bb2  sdk: Set AOSP default behavior for app switch button long press action  [Bruno Martins]

project packages/apps/LineageParts/
a60eeb3  LineageParts: Tweak default charging sound path  [Han Wang]

project tools/repohooks/
ea6c7d7  pre-upload: warn whenever a hook is too slow am: 8f1ceeb31d  [Mike Frysinger]

project vendor/lineage/
ab69681  apn: Ting: Adding missing flag to list of types  [Thomas Karl Pietrowski]

====================
     2020-12-04    
====================

project kernel/xiaomi/markw/
2766cd1  x86/efi-bgrt: Fix kernel panic when mapping BGRT data  [Sai Praneeth]
490f6e5  spi: SPI_FSL_DSPI should depend on HAS_DMA  [Geert Uytterhoeven]
d29fefd  drm: Apply range restriction after color adjustment when allocation  [Chris Wilson]
7339425  cx231xx-cards: fix NULL-deref on missing association descriptor  [Johan Hovold]
476412f  IB/srp: Avoid that a cable pull can trigger a kernel crash  [Bart Van Assche]
a9ca253  target: Fix QUEUE_FULL + SCSI task attribute handling  [Nicholas Bellinger]
df256e45  fix a page leak in vhost_scsi_iov_to_sgl() error recovery  [Al Viro]
00d3bba  ALSA: hda/realtek - Fix ALC700 family no sound issue  [Kailang Yang]
4e9b51c  ARM: 8722/1: mm: make STRICT_KERNEL_RWX effective for LPAE  [Philip Derrin]
9a6aa1e  vsock: use new wait API for vsock_stream_sendmsg()  [WANG Cong]
b3cce09  AF_VSOCK: Shrink the area influenced by prepare_to_wait  [Claudio Imbrenda]
3ac3b00  mm/pagewalk.c: report holes in hugetlb ranges  [Jann Horn]
564d1e2  bonding: discard lowest hash bit for 802.3ad layer3+4  [Hangbin Liu]
eee23d3  staging: rtl8712: fixed little endian problem  [Jannik Becher]
5def43b  ixgbe: add mask for 64 RSS queues  [Emil Tantilov]
b3e5125  ixgbe: Add new support for X550 MAC's  [Don Skidmore]
3cc85a5  ALSA: hda/realtek - Add new codec ID ALC299  [Kailang Yang]
e3d67b8  scsi: ufs: add capability to keep auto bkops always enabled  [subhashj@codeaurora.org]
6049402  fm10k: request reset when mbx->state changes  [Ngai-Mint Kwan]
5e5bfdf  dmaengine: dmatest: warn user when dma test times out  [Adam Wallis]
2f59ddf  net: qmi_wwan: fix divide by 0 on bad descriptors  [Bjørn Mork]
904d8fb  xen-blkback: don't leak stack data via response ring  [Jan Beulich]
7894e63  KVM: x86: fix singlestepping over syscall  [Paolo Bonzini]
88bd8cd  ppp: fix race in ppp device destruction  [Guillaume Nault]
8786074  tools: firmware: check for distro fallback udev cancel rule  [Luis R. Rodriguez]
be125f0  selftests: firmware: send expected errors to /dev/null  [Luis R. Rodriguez]
1a8d9e8  selftests: firmware: add empty string and async tests  [Brian Norris]
cbfda33  test: firmware_class: report errors properly on failure  [Brian Norris]
3594b2a  platform/x86: hp-wmi: Do not shadow error values  [Carlo Caione]
0a4cdce  platform/x86: hp-wmi: Fix error value for hp_wmi_tablet_state  [Carlo Caione]
a86976b  platform/x86: hp-wmi: Fix detection for dock and tablet mode  [Carlo Caione]
263eb15  PCI: mvebu: Handle changes to the bridge windows while enabled  [Jason Gunthorpe]
e4bd5cd  adv7604: Initialize drive strength to default when using DT  [Lars-Peter Clausen]
f1ad60b  mei: return error on notification request to a disconnected client  [Alexander Usyskin]
bb75751  exynos4-is: fimc-is: Unmap region obtained by of_iomap()  [Arvind Yadav]
e2381307  staging: lustre: llite: don't invoke direct_IO for the EOF case  [Yang Sheng]
3ee6634  new helper: iov_iter_rw()  [Omar Sandoval]
77b5493  mfd: ab8500-sysctrl: Handle probe deferral  [Linus Walleij]

project lineage/mirror/
d413190  Updated aosp-minimal to 04-Dec-2020 13:01 UTC  [Tim Schumacher]

====================
     2020-12-03    
====================

project lineage/wiki/
1f64f9a  devices: j{active,f,fve}lte*: Correct recovery mode key-combo  [Thue]
ec3466d  templates: {odin,heimdall}: Provide tip about no-reboot intricacies  [Thue]
2c18241  wiki: templates: device_install: Add tip about adb sideload 47% bug  [Thue]

project vendor/lineage/
ca94a97  soong: Add flag for disabling postrender cleanup  [Arne Coucheron]
bcf6cd5  partner_gms: Add support for Android Go GMS  [Bruno Martins]
f64ce28  lineage: Add Android Go specific configs  [Bruno Martins]
1f0f73d  common_mobile: Don't forcibly ship optional AOSP packages  [Bruno Martins]

