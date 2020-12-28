====================
     2020-12-28    
====================

project build/make/
e69a4c6  build: Remove some debugging props  [Henrique Silva]
adb9ad1  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
d5d0ec8  markw: Update CarrierConfig from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]
6ec4779  markw: sepolicy: Address more gmscore & iorap related denials  [ShihabZzz]

project external/chromium-webview/
c780a2e  webview: Hard no to persistent histograms  [Kevin F. Haggerty]

project frameworks/base/
9729c77  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
416dcdb  Restore one-click to add/remove tiles after r19 merge  [ezio84]
1bf96b8  SystemUI: Remove build version from qs footer  [Pranav Vashi]
19baee7  RebootTile: Make default state inactive  [Pranav Vashi]
d8ab649  Extend reboot tile to add power off  [Pranav Vashi]
230399c  RebootTile: Fix gradient message display for reboot to recovery  [Pranav Vashi]
4bc6b0a  Add Reboot/Recovery QS Tile  [fusionjack]
ef1df67  SystemUI: Update SoundTile  [Ali B]
a8f51f8  QS: Add Sound tile to Quick Settings  [Yoshinori Hirano]
a44cc34  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
75f8389  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
b0fa359  base: Add metric for Blinx Settings  [David Trpchevski]
1b83d6e  SystemUI: Fix size of icon of vibrate ringer mode for additional icon packs  [Volodymyr Zhdanov]
e4fd3bc  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
d8557c7  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
d119d2a  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
26f84af  LockIcon: refresh icon on overlay changes  [Dil3mm4]
eea5306  Properly set fonts and icons on keyguard when changing styles  [ezio84]
39be053  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
f4c7455  screenrec: Show dialog on bottom  [El Dainosor]
e3c6eb1  camera: Support exposing aux camera to apps  [Sauhard Pande]
0086748  SystemUI: Use AVCProfileMain for screen recorder  [Arne Coucheron]
0924504  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
b2cd840  PowerProfile: allow overriding default power profile  [Alexander Martinz]
b265572  power: Re-introduce custom charging sounds  [Bruno Martins]
56dcc5e  incremental: Fix more clang-tidy warnings  [Luca Stefani]
9e85572  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
74fdac6  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/opt/telephony/
f5faa4b  RIL: Fix manual network selection with old modem  [faust93]
fbeee3d  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
942ddf0  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
295a52c  Fix imsi info error when insert some china operator card.  [qiongz]
4310571  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
ca1ff02  Fix to block sim selection popup for data  [Susheel Nyamala]
37a26bc  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
caf7d8a  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
b433f46  Enable vendor Telephony plugin  [Sneh Bansal]
1803308  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
d22b3fa  wifi: Add support for Dual Station combination.  [Khanjan Desai]
7f6536c  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]
a8fbf1b  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
5a5b919  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
cce2d57  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
b704db6  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project packages/apps/Dialer/
02e3068  Fix selecting phone account dialog show error.  [Grace Jia]
d1abb47  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/Messaging/
834319a  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
729990d  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
a4d472f  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Stk/
10b26a3  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project system/core/
17f8530  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
f5c5edf  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
5960ba9  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

project system/vold/
c32e17a  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
e87f3bd  Fix the group permissions of the sdcard root.  [Jani Lusikka]
786703c  vold ext4/f2fs: do not use dirsync if we're mounting adopted storage  [Sam Mortimer]
5d0c26c  vold: Mount ext4/f2fs portable storage with sdcard_posix  [Jani Lusikka]
6b3c337  vold: Honor mount options for ext4/f2fs partitions  [Tom Marshall]
c3a69cc  vold: Support internal storage partitions  [Tom Marshall]
202d0c5  vold: Fix fsck on public volumes  [Michael Bestas]
bd65303  vold: add support for more filesystems for public storage  [Dan Pasanen]

project vendor/lineage/
94bf61d  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
a3a60d0  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
b339c7d  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
fca71fa  power: Kill "Failed to acquire lock" log  [Luca Stefani]
fb49456  power: Handle setBoost interaction events  [Arian]

====================
     2020-12-27    
====================
project android/
fa215b0  lineage: Re-sync QTI BT repos  [Pig]

project device/qcom/sepolicy_vndr/
0a4f9ef  legacy: Allow writing WLAN driver/fw version into property  [Bruno Martins]

project frameworks/base/
f72364c  Add LC3 codec type.  [pramod kotreshappa]
d78d862  Audio: Add support for lc3 codec.  [Manisha Agarwal]
d620f88  Bluetooth: Add APTX-Adaptive and APTX-TWS+ entries.  [Kiran Kelageri]
77aa064  Add callback onA2dpCodecConfigChanged  [Mingbo Zhang]
10a9885  Audio: Do not disconnect profiles till Bluetooth Off  [Gurpreet Ghai]
3518d60  Audio: use cached BT codec info during disconnecting  [Zhou Song]
de3689c  Audio: Update current active bt device of mApmConnectedDevices.  [Manisha Agarwal]
9a44270  BT-Audio: Keep track of Active TWS+ EB device in BTHelper  [Sagar Verma]
3d08aec  BLE: Fix NPE during start advertising  [Sravan Voleti]
42ca62d  Fix build errors  [Scott Lobdell]
0f9e029  Fix BLE transport discovery scan filter  [Subramanian Srinivasan]
ca935c9  BT: Relocate A2DP codec strings for translation  [dianlujitao]
0218bfb  Enable codec change request when mode changes in aptX-adaptive  [Naval saini]
70f4132  Keep a null check before accessing the BluetoothA2dpWrapper APIs.  [Satheesh Kumar Pallemoni]
371694c  Bluetooth: Fix for out of bound exception  [pramod kotreshappa]
75b80d1  BT Dev: Increase array size for codec selection in Dev Op  [Gurpreet Ghai]
73da27f  Keep the BluetoothHeadset finalize() method protected  [Diego Wilson]
fc7ce01  Bluetooth: Fix for Global reference table overflow issue[1/2]  [Bandari Ramesh]
c2d32c0  BT: Add new intent to broadcast IOT device details  [Gurpreet Ghai]
79e027d  BT_Audio: Updated Check for TWS+ switch  [Gurpreet Ghai]
8f24488  TWS_A2DP: Handle active device change between TWS+ earbuds  [pramod kotreshappa]
f9167b3  audio: Add support for APTX TWSP audio codec  [Dhananjay Kumar]
6e6110f  audio: Add support for audio extended codecs  [Naresh Tanniru]
143de07  Use BluetoothUtils instead of Utils  [Diego Wilson]
282ac82  GAP: Handle the race condition cases in auto connect logic  [Venkata Jagadeesh Garaga]
408ffd1  Obex: Squashed commit of the following  [Sravan Kumar V]
64067a1  Add scan filter for Transport Discovery data  [Subramanian Srinivasan]
8ce3d8d  Support CALLBACK_TYPE_SENSOR_ROUTING  [Mingbo Zhang]
d72d3aa  Add support for Transport discovery AD type (1/2)  [Subramanian Srinivasan]
6c0ca70  Bluetooth: TWSP: Support Battery Status information display  [Bhakthavatsala Raghavendra]
624f769  BT: Send info if call is CS type from telecomm service to BT apps.  [Sumit Bajpai]
b28fd0b  GAP: Reset bondingInitiatedLocally flag(1/3)  [Venkata Jagadeesh Garaga]
be64cbb  Bluetooth-TWS: Disable outgoing connection to 2nd earbud  [Kiran Kelageri]
82f0609  Bluetooth-TWS: Disable outgoing connection for 2nd earbud.  [Kiran Kelageri]
9289829  Bluetooth: Rename bluetooth property to support new P Treble rules  [Safoorah Banu Shaik]
37661a4  Bluetooth: Unpair both earbuds on unpair.  [Kiran Kelageri]
86eb709  Bluetooth: Add SDK API support for TWS feature (2)  [Bandari Ramesh]
948cad4  Revert the change: AudioService: remove dead BT code.  [Samyak Jain]
0a5e399  TWS-A2DP: Add TWS+ codec to DevUI support  [pramod kotreshappa]
7ddab604  BT: Adding aptX-Adaptive codec entry to Framework  [Gurpreet Ghai]
3511ebd  Add BluetoothQualityReport class(1/2)  [Mingbo Zhang]

project packages/apps/Settings/
f7178f5  A2dpSrc: Bluetooth codec Dev-UI support for QVA codecs  [Satheesh Kumar Pallemoni]
7a6c634  bluetooth: update SavedBluetoothTwsDeviceUpdater for superclass ctor signature change  [Steven Laver]
594ac09  Implement abstract method getPreferenceKey in SavedBluetoothTwsDeviceUpdater  [Justin DeMartino]
941dd0d  BT: Use translated a2dp codec strings  [dianlujitao]
683fd8d  A2dpSrc: DEV-UI support for Blutooth Audio codec.  [Satheesh Kumar Pallemoni]
e320a8b  Bluetooth-TWS: UI updates based on Filter matched  [zhenchao]
51b1283  Bluetooth-TWS: UI updates based on profile connection.  [Kiran Kelageri]
bb7abee  Fix build error  [Jiyong Park]
7092980  Bluetooth-TWS: Filter TWS devices  [Kiran Kelageri]
6372a3a  Bluetooth: Create new catogory for earbuds  [Kiran Kelageri]

project vendor/lineage/
f85f7e8  config: Setup soong namespaces for TARGET_USE_QTI_BT_STACK  [Pig]

====================
     2020-12-26    
====================

project device/xiaomi/markw/
b1d4bf2  markw: Update & switch IMS Stack from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
cb5687d  markw: sepolicy: Address more denials  [ZeeLog]
456a380  markw: Import missing Media blobs from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
78f3d2b  markw: Build android.hardware.health@2.1-impl.recovery package  [ZeeLog]
2c034b8  markw: Only include bitness of hal impls that is used.  [Steven Moreland]
e1c2ac4  markw: light: Add missing hidl_default flag  [ShihabZzz]
dc3607d  markw: Add vintf fragments for specific HALs  [ZeeLog]
b31c2da  markw: Append vendor prefix to qcamerasvr service name  [ZeeLog]

project lineage/hudson/
d28011c  Revert "Drop kuntao"  [Michael Bestas]

project packages/apps/Snap/
a3fddbc  {Capture,MultiCamera}UI: Match video stop icon to API1 mode  [Paul Keith]

====================
     2020-12-25    
====================

project frameworks/base/
1e19a67  UserRestrictionUtils: Return null Bundle if there are no restrictions  [Paul Keith]

project packages/apps/Camera2/
3b12532  AOSP/Camera2 - Fix bug causing edit, share, delete buttons to not appear  [Colin Marsch]
88fb7fa  AOSP/Camera2 - Remove Saving bar after taking a photo  [Colin Marsch]
bb6cde9  AOSP/Camera2 - Update Storage method to be compatible with API 29  [Colin Marsch]
269a879  Revert "Revert "Camera2: Migrate to new storage API""  [Colin Marsch]

project packages/apps/Contacts/
4496174  Contacts: Enable support for device contact.  [Toha]

project packages/apps/Snap/
d08c78d  Snap: chmod 0644  [Paul Keith]
05e1f3f  Snap: dos2unix  [Paul Keith]
600377c  CaptureModule: Only look for ssm capture results if ssm is enabled  [Paul Keith]
7c2678a  CaptureModule: Fix init sequence  [Paul Keith]

project packages/apps/Trebuchet/
2a0aa6a  Disable MULTI_DB_GRID_MIRATION_ALGO  [Michael Bestas]

project packages/providers/ContactsProvider/
78f2b52  ContactsProvider: Prevent device contact being deleted.  [Toha]

project vendor/codeaurora/telephony/
c72e95d  ims-ext-common: Forward the legacy getAutoReject call to obtain compatibility with older ims.apk  [Arian]
1fae6d5  Revert "IMS: Remove API and constants related to ECT."  [Josh Chasky]

project vendor/xiaomi/
c7fe9b1  markw: Update & switch IMS Stack from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]
4551546  markw: Import missing Media blobs from LA.UM.9.6.2.r1-03300-89xx.0  [ZeeLog]

====================
     2020-12-24    
====================
project android/
13cb0cf  lineage: Track our Snap Camera  [althafvly]

project bootable/recovery/
c4b3e64  recovery: Allow going back in rescue party menu  [Alessandro Astone]

project device/qcom/sepolicy_vndr/
2f7337d  common: Address BT denials  [Bruno Martins]

project device/xiaomi/markw/
d159198   markw: Update media configs from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]
401f72d  markw: Build LineageOS touch HAL  [ShihabZzz]
6dc0a34  markw: touch: Update C/C++ code format  [ShihabZzz]
684993c  markw: Implement key disabler nodes & update sepolicy rules  [ShihabZzz]
be8b714  markw: touch: Remove libhwbinder/libhidltransport deps  [smore-lore]
935df54  markw: touch: Don't include <binder/ProcessState.h>  [Artem Borisov]
56789ac  markw: Implement lineage touch HIDL HAL  [Bruno Martins]

project frameworks/base/
1108fc3  Keyguard: Allow disabling fingerprint wake-and-unlock  [Steve Kondik]

project lineage/mirror/
86ecd60  Updated aosp-minimal to 24-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
25d9aaf  wiki: cheeseburger,dumpling: firmware is not handleded by user  [Timi]

project packages/providers/TelephonyProvider/
eea40c6  Fix wrong index access in getSingleMessageFromIcc()  [Taesu Lee]
80ccfdb  Support delete all the messages in SIM  [Taesu Lee]
2fe61e1  Fallback to other address type for EF_SMS  [Taesu Lee]

project vendor/lineage/
85359e5  fixup! extract_utils: implement patchelf  [Sebastiano Barezzi]

====================
     2020-12-23    
====================
project android/
f32e528  lineage: Sync SimpleDeviceConfig  [Michael Bestas]

project device/xiaomi/markw/
86a1dc0  markw: Build with clang 11.0.5  [ShihabZzz]

project frameworks/base/
5d5e5e2c  SystemUI: Increase icon padding in QS privacy chip  [Danny Lin]

project kernel/xiaomi/markw/
f6b59f1  Redux: 1.04  [ShihabZzz]
d04ebca  drivers: Silence debugfs failing log spam  [ShihabZzz]

project lineage/hudson/
93e132a  Drop kuntao  [Michael Bestas]

project lineage/mirror/
f229d03  Updated to 23-Dec-2020 13:46 UTC  [Kevin F. Haggerty]
b4080c5  Updated lineage-minimal to 23-Dec-2020 13:01 UTC  [Tim Schumacher]

project packages/apps/Settings/
59fe5d0  Add translations for face unlock strings  [Chirayu Desai]
b46d1f7  Add strings for face unlock feature  [Chirayu Desai]
9423d76  Revert "Remove permission bar chart in Privacy setting"  [Michael Bestas]

project prebuilts/clang/host/linux-x86/clang-r399163b/
f2a3d15  Add include dir to remote_toolchain_inputs to allow Bazel and RE-client to interoperate.  [Rupert Shuttleworth]

project vendor/lineage/
fe8a057  config: Allow more legacy apps to use conversation notifications  [Danny Lin]

====================
     2020-12-22    
====================

project frameworks/base/
969918b  fw/b: Add capability to allow tethering to use VPN upstreams  [Sam Mortimer]
fb08f60  NavBar: Don't crash when we can't find navigation overlays  [Alessandro Astone]

project kernel/xiaomi/markw/
8c8db80  rcu: boost: avoid preemption before calling complete()  [John Dias]
070ef48  prima: Guard akm_type check with WLAN_FEATURE_SAE  [baunilla]
201d2c2  Merge tag 'LA.UM.8.6.c26-01600-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into lineage-18.1  [ShihabZzz]
df1b25c  Merge tag 'LA.UM.8.6.c26-01300-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into lineage-18.1  [ShihabZzz]
59de759  BACKPORT: qseecom: Use scm_call2 when bus_scaling is enabled  [AnilKumar Chimata]
b12543b  BACKPORT: qseecom: Remove virtual address print  [Monika Singh]
ca12878  drivers: input: touchscreen: Create keydisabler nodes  [GuaiYiHu]
d2004df  Redux: 1.03  [ShihabZzz]
38ab11c  arm:dts: msm8953: Add clock-frequency property  [Remicaa]
0e118ef  thermal: Do not log an error if thermal_zone_get_temp returns -EAGAIN  [Hans de Goede]
2932c0f  msm_thermal: initialize later than arch drivers  [Park Ju Hyung]
0cbfaea  msm: ipa: update msm_ipa.h with latest IPA versions constants  [Ghanim Fodi]
9dd4e29  Redux: 1.0  [ShihabZzz]
9f3b184  Quark: 1.18  [ShihabZzz]
ceb1235  Merge tag 'v1.0.20201221' of https://github.com/WireGuard/wireguard-linux-compat into lineage-17.1  [ShihabZzz]

project lineage-sdk/
89f2037  lineage-sdk: Create minimal lineagesettings library for apex use  [Sam Mortimer]
967b1a8  Profile: Don't NPE when service is not started  [Alessandro Astone]

project lineage/hudson/
e3a616c  hudson: add Galaxy Tab S6 Lite Wi-Fi (gta4xlwifi)  [Tim Zimmermann]

project lineage/wiki/
b7f3120  wiki: Fix up gta4xlwifi data  [Harry Youd]
716983e  wiki: add Galaxy Tab S6 Lite Wi-Fi (gta4xlwifi)  [Tim Zimmermann]

project packages/apps/Snap/
dc83fd7  SnapdragonCamera: Correct the mBackCameraId and mFrontCameraId  [xianming wang]
c9d8fe6  Snap: Port all string improvements from lineage-17.1  [Michael Bestas]
991dec3  Snap: Fix swipe right to open menu  [Arne Coucheron]

project system/core/
8a68cd2  healthd: allow custom charger images  [Scott Mertz]

====================
     2020-12-21    
====================

project device/xiaomi/markw/
78be93e  markw: wifi: Update and modify wcnss_service.  [Quallenauge]

project kernel/xiaomi/markw/
47e2782  version: bump  [Jason A. Donenfeld]
f01be98  socket: remove bogus __be32 annotation  [Jann Horn]
2730072  global: avoid double unlikely() notation when using IS_ERR()  [Antonio Quartulli]

project lineage/mirror/
1587a04  Updated to 20-Dec-2020 18:51 UTC  [Kevin F. Haggerty]

project vendor/xiaomi/
49914d4  markw: wifi: Update and modify wcnss_service  [Quallenauge]

====================
     2020-12-20    
====================

project lineage/mirror/
0aab4ae  Updated lineage-minimal to 20-Dec-2020 13:01 UTC  [Tim Schumacher]

====================
     2020-12-19    
====================
project android/
152615b  manifest: Switch to our Gallery2 fork  [Michael Bestas]
5b29ae8  fixup! manifest: Track soundtrigger and ipacfg-mgr for floral  [Nolen Johnson]
f376989  manifest: Track soundtrigger and ipacfg-mgr for floral  [Nolen Johnson]
a09e0e6  Move hardware/libhardware_legacy back to AOSP remote  [Bruno Martins]

project hardware/knowles/athletico/sound_trigger_hal/
c66811b  Use generated kernel headers  [Chirayu Desai]

project hardware/qcom/sm8150/data/ipacfg-mgr/
3cbf948  Use generated kernel headers  [Chirayu Desai]
4efc7c0  Kernel Header Changes  [arnav_s]

project kernel/xiaomi/markw/
8dcc75d  simd: detect -rt kernels >= 5.4  [Jason A. Donenfeld]

project packages/apps/Settings/
fc6c9a5  Settings: Add hotspot setting to allow VPN upstreams  [Sam Mortimer]

====================
     2020-12-18    
====================

project lineage/mirror/
c4533eb  Updated to 18-Dec-2020 14:09 UTC  [Kevin F. Haggerty]
4c9a5a4  Updated aosp-minimal to 18-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
45041be  wiki: Move how-tos to a better url scheme  [Michael W]
b4e3df4  State that Gerrit username is case-sensitive  [Phyks (Lucas Verney)]
77a8c73  Make local bundle/vendor install of Jekyll easier  [Phyks (Lucas Verney)]

project system/bt/
1f8acc3  bluetooth: select bluetooth modules by fully qualified namespace.  [Steven Laver]

project vendor/lineage/
f91f11a  overlay: Enable privacy indicators  [Danny Lin]
a9bf8b0  overlay: Delegate DeviceConfig permissions to custom provisioning service  [Danny Lin]
969ba44  config: Build simple DeviceConfig provisioning service  [Danny Lin]

====================
     2020-12-17    
====================

project device/xiaomi/markw/
26bbf0f  markw: fix restorecon_recursive command sequence  [Jiten Patel]
f71e602  markw: init.qcom.rc: remove unused property  [Sean Tranchetti]
9041298  markw: Misc update & cleanup  [ShihabZzz]

project hardware/qcom-caf/wlan/
bb71c38  wcnss-service: Opt-in to disable copying WCNSS_qcom_cfg.ini to userdata  [Michael Bestas]

project kernel/xiaomi/markw/
d2faea8  gitignore: ignore intermediary build file  [L.W.Reek]

project lineage/mirror/
4e89d82  Updated aosp-minimal to 17-Dec-2020 13:01 UTC  [Tim Schumacher]

project packages/apps/Backgrounds/
44344d3  Backgrounds: Move to /product  [Michael Bestas]
d2ff9ab  Backgrounds: Update resource name to match AOSP changes in WallpaperPicker2  [LuK1337]

project packages/apps/Eleven/
2c5faa1  Eleven: Convert to Android.bp  [Michael Bestas]

project packages/apps/ExactCalculator/
c3602a5  ExactCalculator: Move to /product  [Michael Bestas]
64fe55a  ExactCalculator: Convert to Android.bp  [Michael Bestas]

project packages/apps/PermissionController/
fcef90c  PermissionController: Implement getPermissionUsages API  [Danny Lin]
85a27e7  PermissionController: Remove warning from permission dashboard  [Danny Lin]

====================
     2020-12-16    
====================

project frameworks/base/
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

project lineage/mirror/
b421d0f  Updated aosp-minimal to 16-Dec-2020 13:01 UTC  [Tim Schumacher]

project packages/apps/Messaging/
fa7a972  Mark messages as failed if SIM is inactive  [Taesu Lee]
a536231  Fix creating a new conversation including own number  [Taesu Lee]

project packages/modules/CaptivePortalLogin/
73468f6  Add NPE protection to prevent illegal CaptivePortal in the intent  [Chiachang Wang]
a4b8a6b  Remove webview from the view system before destroying webview  [lucaslin]
09ccf33  Fix captive portal downloads on private DNS  [Remi NGUYEN VAN]
47f3321  Move min/target_sdk_version to java_defaults  [Jooyung Han]

project packages/services/BuiltInPrintService/
4c6694b  use RGB when delivering images to printers  [Glade Diviney]

project packages/services/Telecomm/
3d64b4f  add support to check if Cs Call InProgress  [himta ram]
c1da8a2  Bluetooth: Support to know if there is High Def call  [Nivedita Sarkar]

project system/core/
4b05abc  Boost init priority before main loop  [Wei Wang]

project system/media/
436ecb4  media: update path for vendor specific config files  [Banajit Goswami]

project system/netd/
a3947bd  netd: Allow devices to force-add directly-connected routes  [Lukas0610]

project vendor/lineage/
4562fe4  prebuilt: Remove content-types.properties  [Han Wang]
0adb3e0  ThemePicker: Define clocks stub package  [Danny Lin]
d02c314  SystemUI: Whitelist QuickAccessWallet plugin  [Danny Lin]
7a31b36  config: Build QuickAccessWallet plugin for SystemUI  [Danny Lin]
46b6e3a  extract_utils: generate_prop_list: Ignore vdex/odex files too  [Alessandro Astone]

project vendor/qcom/opensource/interfaces/
0b195ee  interfaces: Introduce vendor.qti.hardware.audiohalext@1.0 HAL  [Alexander Koskovich]

====================
     2020-12-15    
====================
project android/
647418a  Switch to our forks of QCOM display / gps / media  [Elektroschmock]

project build/make/
be5c38a  Remove unused locale data for recovery  [Alessandro Astone]

project device/xiaomi/markw/
11a816e  markw: Update CarrierConfig from LA.UM.8.6.r1-04700-89xx.0  [ShihabZzz]

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

project kernel/xiaomi/markw/
f7f5546  compat: drop rhel 8.2, add rhel 8.4 support  [Jason A. Donenfeld]

project lineage/mirror/
6f597a9  Updated to 15-Dec-2020 13:11 UTC  [Kevin F. Haggerty]
9240572  Updated lineage-minimal to 15-Dec-2020 13:02 UTC  [Tim Schumacher]
cfcbbb1  Updated to 15-Dec-2020 13:01 UTC  [Tim Schumacher]
45f0dae  Updated to 14-Dec-2020 16:02 UTC  [Kevin F. Haggerty]

project lineage/wiki/
ca6bc32  devices: klteactivexx: We don't support the AT&T varaint  [Nolen Johnson]
8776c6f  devices: flo: State that 17.1 and beyond codename is now flox  [Nolen Johnson]

