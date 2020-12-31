====================
     2020-12-31    
====================

project build/make/
dc43428  build: Remove some debugging props  [Henrique Silva]
ff88992  Use 'release-keys' for build tag  [Sultanxda]

project device/xiaomi/markw/
394106b  Revert "markw: Update qti privapp permissions"  [ZeeLog]
4ad044d  markw: sepolicy: Use BOARD_VENDOR_SEPOLICY_DIRS  [Felix]
92276a5  markw: Switch to standalone extract utils  [Michael Bestas]

project frameworks/base/
f75958f  DataSwitchTile: dont show toast on click  [micky387]
69d48a9  DataSwitchTile: collapse notification panel onClick  [DennySPB]
dae54bb  SystemUI: Introduce DataSwitchTile  [Christian Oder]
9e79282  base: Change QS customizer 'drag to add tile' string  [Alex Cruz]
fec72de  Restore one-click to add/remove tiles after r19 merge  [ezio84]
6721af2  SystemUI: Remove build version from qs footer  [Pranav Vashi]
8a59681  RebootTile: Make default state inactive  [Pranav Vashi]
33910d8  Extend reboot tile to add power off  [Pranav Vashi]
b643516  RebootTile: Fix gradient message display for reboot to recovery  [Pranav Vashi]
98a7257  Add Reboot/Recovery QS Tile  [fusionjack]
d4d3716  SystemUI: Update SoundTile  [Ali B]
864fd5f  QS: Add Sound tile to Quick Settings  [Yoshinori Hirano]
7bfbb90  SettingsProvider: Fix for google backup and restore  [PlayfulGod]
635143c  Add missing STORAGE_INTERNAL permission for BackupRestoreConfirmation  [c_jyuan]
b9d09d3  base: Add metric for Blinx Settings  [David Trpchevski]
da4eb50  SystemUI: Remove unused resources  [Michael Bestas]
f3cc632  SystemUI: Improve volume panel expansion/contraction animation  [Danny Lin]
f4bd609  SystemUI: Fix display cutout handling in expanding volume panel  [Danny Lin]
d7696f9  overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack  [Aman Singh]
d58c1a8  LockIcon: refresh icon on overlay changes  [Dil3mm4]
41a487d  Properly set fonts and icons on keyguard when changing styles  [ezio84]
9b3cf56  StatusBar: Dismiss qs when screen's going off if showing  [Dil3mm4]
f7f2623  screenrec: Show dialog on bottom  [El Dainosor]
e4a4524  camera: Support exposing aux camera to apps  [Sauhard Pande]
08128f1  SystemUI: Use AVCProfileMain for screen recorder  [Arne Coucheron]
babdab4  Use proper coded alphabet when a contact is written into EF_ADN of USIM.  [Umashankar Godachi]
ca97085  PowerProfile: allow overriding default power profile  [Alexander Martinz]
3dd26de  power: Re-introduce custom charging sounds  [Bruno Martins]
fbba927  incremental: Fix more clang-tidy warnings  [Luca Stefani]
6c665d2  incremental: Don't pollute namespace with android::{incfs,incremental}  [Luca Stefani]
20a0493  IncrementalService: Fix clang-tidy warning  [Luca Stefani]

project frameworks/opt/telephony/
72ca385  RIL: Fix manual network selection with old modem  [faust93]
859313f  SimPhoneBook: Add ANR/EMAIL support for USIM phonebook.  [Yujing Gu]
2236b1e  Define EF MSPL/MLPL/PRL values and paths  [zhu youhua]
db09a46  Fix imsi info error when insert some china operator card.  [qiongz]
e78d0ff  FR57912: Add support for pdp data reject with cause code 29,33,55  [Susheel Nyamala]
7a7946e  Fix to block sim selection popup for data  [Susheel Nyamala]
1d1d748  Add support for retry with new DDS API and update QtiPhoneSwitcher  [Susheel Nyamala]
0248845  CDMA MO SMS follow on DC feature  [Chaitanya Saggurthi]
e76551f  Enable vendor Telephony plugin  [Sneh Bansal]
8267a76  Enable vendor Telephony plugin: MSIM Changes  [Sneh Bansal]

project hardware/interfaces/
57fe14d  wifi: Add support for Dual Station combination.  [Khanjan Desai]
f0db7da  wifi: Add provision to create/remove dynamic interface(s).  [Purushottam Kushwaha]
a2a3b7e  Revert "Fix so that dual access points (AP) works."  [Purushottam Kushwaha]
b18459f  Generate unique random mac address per AP interface  [Veerendranath Jakkam]

project hardware/lineage/interfaces/
b58672e  livedisplay: Initial conversion to aidl  [Pig]

project lineage-sdk/
e767361  lineage-sdk: Tweak default charging sound path again  [Han Wang]

project lineage/mirror/
c07fe56  Updated lineage-minimal to 30-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
44e1c32  wiki: Add Adreno 308 as a valid GPU  [Jarl-Penguin]

project packages/apps/Dialer/
91e4ef3  Dialer: Remove unused resources  [Michael Bestas]
5cae33c  Fix selecting phone account dialog show error.  [Grace Jia]
d9cd238  CallLogFragment: Move Un-registering call log observer to destroy  [Varun Date]

project packages/apps/Messaging/
d434e08  Messaging: Remove unused resources  [Michael Bestas]
b64e686  Messaging: Show quick reply choices only on wearable devices  [Han Wang]
6ffc82b  Messaging: Add "Mark as read" quick action for message notifications  [Paul Keith]

project packages/apps/Settings/
811c3f8  Settings: Add LineageParts charging sound settings preference  [Sam Mortimer]

project packages/apps/Snap/
c69ccf1  Snap: Remove warnings for generated ids  [Michael W]
9567e1d  Snap: there is no camera icon shown if have no camera in first boot up  [zhang sanshan]

project packages/apps/Stk/
8bad0d0  stk: Add minSdkVersion and targetSdkVersion  [baalajimaestro]

project system/core/
19b9978  fastboot: Don't fail when unable to get boot partition size  [Michael Bestas]
5390a90  libutils: Restore old RefBase-behavior for SDK < Q to avoid loops with legacy blobs  [Joel Stein]
4f12dcc  init: Don't run update_sys_usb_config if /data isn't mounted  [Michael Bestas]

project system/vold/
b1b36e3  vold: Accept Linux GPT partitions on external SD cards  [lambdadroid]
6300d70  Fix the group permissions of the sdcard root.  [Jani Lusikka]
e2a0cfb  vold ext4/f2fs: do not use dirsync if we're mounting adopted storage  [Sam Mortimer]
de854ff  vold: Mount ext4/f2fs portable storage with sdcard_posix  [Jani Lusikka]
8f12e94  vold: Honor mount options for ext4/f2fs partitions  [Tom Marshall]
b274e40  vold: Support internal storage partitions  [Tom Marshall]
0bea6ee  vold: Fix fsck on public volumes  [Michael Bestas]
df6519b  vold: add support for more filesystems for public storage  [Dan Pasanen]

project vendor/lineage/
d61c78d  build: Relocate extract utils to tools/extract-utils  [Michael Bestas]
eba9f13  overlay: Allow restoring Seedvault backup after initial setup  [Michael Bestas]
b323879  lineage: repopick: Add support for picking multiple topics  [Giuseppe Maggio]
798a5ee  lineage: repopick: pick only open changes in a topic  [Akhil Narang]

project vendor/qcom/opensource/power/
bc4b457  power: Kill "Failed to acquire lock" log  [Luca Stefani]

====================
     2020-12-30    
====================
project android/
cae0362  lineage: Sync standalone extract utils  [Michael Bestas]

project device/xiaomi/markw/
1721da3  markw: Update sha1sum for modified lowi.conf  [ZeeLog]
7ff427b  markw: do not build useless packages  [Demon Singur]
6a3061a  markw: Remove unnecessary android.hardware.radio entries  [Ethan Chen]
fa01ff9  markw: Remove unnecessary netutils packages  [Ethan Chen]
83dd138  markw: Enable ipsec_tunnel feature  [Prakash Pabba]
22fe0f5  markw: Drop TARGET_USES_NEW_ION_API flag  [Cosme Domínguez Díaz]
6a4a097  markw: Remove deprecated TARGET_USES_OVERLAY  [Nolen Johnson]
d0c2ac4  markw: Remove obsolete dex settings  [Anton Hansson]
7040f6d  markw: kill deprecated/unneeded board flags  [Nolen Johnson]
22a1cd8  markw: Remove TARGET_USES_64_BIT_BINDER  [Kilian von Pflugk]
1fce2cd  markw: Remove deprecated TARGET_BOARD_PLATFORM_GPU  [Arne Coucheron]
2410efe  markw: Sign Tether RROs with default cert  [Bruno Martins]
e1f45a6  markw: Don't sign Wifi RROs with platform cert  [David Su]
8de09db  markw: TetheringOverlay: Drop custom dhcp range  [Michael Bestas]
1c6dfcf  markw: Opt out recovery update  [ZeeLog]
11a3a67  markw: Update CarrierConfig from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]

project frameworks/base/
ec93ea4  audio: Discard QTI only codecs when AOSP BT stack is in use  [LuK1337]

project vendor/lineage/
f17c855  lineage: apns: Update T-Mobile US to reflect latest carrier changes  [Zachariah Anderson]

project vendor/xiaomi/
5c80e46  markw: Remove copyright headers from automatically generated files  [Michael Bestas]
2a03321  markw: gps: lowi.conf: lower debug level  [ZeeLog]

====================
     2020-12-29    
====================

project frameworks/base/
2373904  SystemUI: Resolve faulty keyguard clock logs outputs  [Adrian DC]
a31439f  SystemUI: Fix size of icon of vibrate ringer mode for additional icon packs  [Volodymyr Zhdanov]

project lineage/hudson/
368fd5c  hudson: Promote FP3 to 17.1  [Daniel Köster]

project lineage/mirror/
b85f1a0  Updated to 28-Dec-2020 13:00 UTC  [Tim Schumacher]

project packages/apps/Trebuchet/
c7127d8  Remove unused translation  [Michael Bestas]

project tools/extract-utils/
fb4ad78  Remove support for /sbin  [Michael Bestas]
55ec886  templates: Support extracting only either common or target device blobs  [Bruno Martins]
805a684  Update sdat2img.py  [Michael Bestas]
41cd5a0  Replace Apache 2.0 boilerplate/reference with SPDX  [Michael Bestas]
830a9cb  Add multi-device templates and update normal templates  [Michael Bestas]

====================
     2020-12-28    
====================

project device/xiaomi/markw/
6ec4779  markw: sepolicy: Address more gmscore & iorap related denials  [ShihabZzz]

project external/chromium-webview/
c780a2e  webview: Hard no to persistent histograms  [Kevin F. Haggerty]

project lineage/wiki/
caad00f  devices: FP3: Promote to 17.1  [Daniel Köster]

project packages/apps/Camera2/
49af717  Camera2: Set targetSdkVersion=29  [Michael Bestas]

project prebuilts/tools-lineage/
214ba0c  Relocate extract tools to prebuilts/extract-tools  [Michael Bestas]

project tools/extract-utils/
8e4a039  Remove copyright headers from automatically generated files  [Michael Bestas]
ab77884  Remove branding from script variables  [Michael Bestas]
5a82907  Adapt for new tools location  [Michael Bestas]
8f82a58  Adapt for new script location  [Michael Bestas]
490e38e  fixup! extract_utils: implement patchelf  [Sebastiano Barezzi]

====================
     2020-12-27    
====================
project android/
f315bb7  manifest: Track our own tzdata-related repos  [Kevin F. Haggerty]
fa215b0  lineage: Re-sync QTI BT repos  [Pig]

project device/qcom/sepolicy_vndr/
0a4f9ef  legacy: Allow writing WLAN driver/fw version into property  [Bruno Martins]

project external/cldr/
bca0ad9  RESTRICT AUTOMERGE CLDR-14225 tz database 2020b updates [R]  [Neil Fuller]
1b1fe92  RESTRICT AUTOMERGE CLDR-13739 Changed some tzdata files to rear-guard version. (#445)  [Neil Fuller]

project external/icu/
56b88bc  RESTRICT AUTOMERGE Update Android to tzdb 2020d [R]  [Neil Fuller]
e0583f3  RESTRICT AUTOMERGE Update Android to tzdb 2020c [R]  [Neil Fuller]
394ae3d  RESTRICT AUTOMERGE Update Android to tzdb 2020b [R]  [Neil Fuller]

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

project system/timezone/
16a8d2a  RESTRICT AUTOMERGE Update Android from 2020c to 2020d [R]  [Neil Fuller]
927672e  RESTRICT AUTOMERGE Update Android from 2020b to 2020c [R]  [Neil Fuller]
5c9bf9b  RESTRICT AUTOMERGE Update Android from 2020a to 2020b [R]  [Neil Fuller]

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

project packages/apps/Eleven/
4e9dac3  Eleven: Set targetSdkVersion to 29  [Michael Bestas]

project packages/apps/Snap/
a3fddbc  {Capture,MultiCamera}UI: Match video stop icon to API1 mode  [Paul Keith]

====================
     2020-12-25    
====================

project device/qcom/sepolicy_vndr/
2f7337d  common: Address BT denials  [Bruno Martins]

project device/xiaomi/markw/
d159198   markw: Update media configs from LA.UM.9.6.2.r1-03300-89xx.0  [ShihabZzz]
401f72d  markw: Build LineageOS touch HAL  [ShihabZzz]

project frameworks/base/
1e19a67  UserRestrictionUtils: Return null Bundle if there are no restrictions  [Paul Keith]

project lineage/mirror/
86ecd60  Updated aosp-minimal to 24-Dec-2020 13:01 UTC  [Tim Schumacher]

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
f32e528  lineage: Sync SimpleDeviceConfig  [Michael Bestas]

project bootable/recovery/
c4b3e64  recovery: Allow going back in rescue party menu  [Alessandro Astone]

project device/xiaomi/markw/
6dc0a34  markw: touch: Update C/C++ code format  [ShihabZzz]
684993c  markw: Implement key disabler nodes & update sepolicy rules  [ShihabZzz]
be8b714  markw: touch: Remove libhwbinder/libhidltransport deps  [smore-lore]
935df54  markw: touch: Don't include <binder/ProcessState.h>  [Artem Borisov]
56789ac  markw: Implement lineage touch HIDL HAL  [Bruno Martins]

project frameworks/base/
1108fc3  Keyguard: Allow disabling fingerprint wake-and-unlock  [Steve Kondik]
5d5e5e2c  SystemUI: Increase icon padding in QS privacy chip  [Danny Lin]

project lineage/hudson/
93e132a  Drop kuntao  [Michael Bestas]

project lineage/mirror/
f229d03  Updated to 23-Dec-2020 13:46 UTC  [Kevin F. Haggerty]
b4080c5  Updated lineage-minimal to 23-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
25d9aaf  wiki: cheeseburger,dumpling: firmware is not handleded by user  [Timi]

project packages/apps/Etar/
a4cced1  Etar: Add local com.google.android.material_material prebuilt  [LuK1337]
8a5a01f  Hardcode `locationIconRounded` corner size  [LuK1337]
3c8850d  Add accidentally deleted code (#820)  [Gitsaibot]
c70e067  Release version 1.0.24 (#817)  [Gitsaibot]
f779d0d  Update submodules (#819)  [Jochen Sprickerhof]
735feb5  Let widget respect app theme colors (#816)  [Gitsaibot]
ffa837a  Improve location drop box (#815)  [Gitsaibot]
3cf0c4d  Set api21 as minsdk  [Gitsaibot]

project packages/apps/Settings/
59fe5d0  Add translations for face unlock strings  [Chirayu Desai]
b46d1f7  Add strings for face unlock feature  [Chirayu Desai]
9423d76  Revert "Remove permission bar chart in Privacy setting"  [Michael Bestas]

project packages/providers/TelephonyProvider/
eea40c6  Fix wrong index access in getSingleMessageFromIcc()  [Taesu Lee]
80ccfdb  Support delete all the messages in SIM  [Taesu Lee]
2fe61e1  Fallback to other address type for EF_SMS  [Taesu Lee]

project vendor/lineage/
85359e5  fixup! extract_utils: implement patchelf  [Sebastiano Barezzi]
fe8a057  config: Allow more legacy apps to use conversation notifications  [Danny Lin]

====================
     2020-12-23    
====================

project device/xiaomi/markw/
86a1dc0  markw: Build with clang 11.0.5  [ShihabZzz]

project kernel/xiaomi/markw/
f6b59f1  Redux: 1.04  [ShihabZzz]
d04ebca  drivers: Silence debugfs failing log spam  [ShihabZzz]

project prebuilts/clang/host/linux-x86/clang-r399163b/
f2a3d15  Add include dir to remote_toolchain_inputs to allow Bazel and RE-client to interoperate.  [Rupert Shuttleworth]

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
0aab4ae  Updated lineage-minimal to 20-Dec-2020 13:01 UTC  [Tim Schumacher]

project vendor/xiaomi/
49914d4  markw: wifi: Update and modify wcnss_service  [Quallenauge]

====================
     2020-12-20    
====================

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

project lineage/mirror/
c4533eb  Updated to 18-Dec-2020 14:09 UTC  [Kevin F. Haggerty]
4c9a5a4  Updated aosp-minimal to 18-Dec-2020 13:01 UTC  [Tim Schumacher]

project packages/apps/Settings/
fc6c9a5  Settings: Add hotspot setting to allow VPN upstreams  [Sam Mortimer]

project vendor/lineage/
f91f11a  overlay: Enable privacy indicators  [Danny Lin]
a9bf8b0  overlay: Delegate DeviceConfig permissions to custom provisioning service  [Danny Lin]
969ba44  config: Build simple DeviceConfig provisioning service  [Danny Lin]

====================
     2020-12-18    
====================

project lineage/mirror/
4e89d82  Updated aosp-minimal to 17-Dec-2020 13:01 UTC  [Tim Schumacher]

project lineage/wiki/
45041be  wiki: Move how-tos to a better url scheme  [Michael W]
b4e3df4  State that Gerrit username is case-sensitive  [Phyks (Lucas Verney)]
77a8c73  Make local bundle/vendor install of Jekyll easier  [Phyks (Lucas Verney)]

project packages/apps/Backgrounds/
44344d3  Backgrounds: Move to /product  [Michael Bestas]
d2ff9ab  Backgrounds: Update resource name to match AOSP changes in WallpaperPicker2  [LuK1337]

project packages/apps/Eleven/
2c5faa1  Eleven: Convert to Android.bp  [Michael Bestas]

project packages/apps/ExactCalculator/
c3602a5  ExactCalculator: Move to /product  [Michael Bestas]
64fe55a  ExactCalculator: Convert to Android.bp  [Michael Bestas]

project system/bt/
1f8acc3  bluetooth: select bluetooth modules by fully qualified namespace.  [Steven Laver]

