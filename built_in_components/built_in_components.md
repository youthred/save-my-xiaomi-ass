## 内置组件

*`CTRL` + `F` 进行搜索*

执行命令后返回 `Success` 表示成功卸载，返回 `Failure [not installed for 0]` 表示该应用已经卸载过

下方列出的应用并非都可以安全删除！某些系统核心组件的删除可能导致设备功能异常或无法正常使用

请在删除前仔细确认应用的作用，并自行承担删除风险

建议仅删除您确定不需要的应用

### 系统打印服务(Systemprintingservice)

```shell
pm uninstall --user 0  com.android.bips # 卸载
cmd package install-existing --user 0  com.android.bips # 恢复
```

### BluetoothMIDIService

```shell
pm uninstall --user 0  com.android.bluetoothmidiservice # 卸载
cmd package install-existing --user 0  com.android.bluetoothmidiservice # 恢复
```

### BookmarkProvider

```shell
pm uninstall --user 0  com.android.bookmarkprovider # 卸载
cmd package install-existing --user 0  com.android.bookmarkprovider # 恢复
```

### 浏览器(Browser)

```shell
pm uninstall --user 0  com.android.browser # 卸载
cmd package install-existing --user 0  com.android.browser # 恢复
```

### 日历(Calendar)

```shell
pm uninstall --user 0  com.android.calendar # 卸载
cmd package install-existing --user 0  com.android.calendar # 恢复
```

### CallLogBackupRestore

```shell
pm uninstall --user 0  com.android.calllogbackup # 卸载
cmd package install-existing --user 0  com.android.calllogbackup # 恢复
```

### CameraExtensionsProxy

```shell
pm uninstall --user 0  com.android.cameraextensions # 卸载
cmd package install-existing --user 0  com.android.cameraextensions # 恢复
```

### 运营商默认应用(CarrierDefaultUnknown)

```shell
pm uninstall --user 0  com.android.carrierdefault # 卸载
cmd package install-existing --user 0  com.android.carrierdefault # 恢复
```

### CellBroadcastService

```shell
pm uninstall --user 0  com.android.cellbroadcastservice # 卸载
cmd package install-existing --user 0  com.android.cellbroadcastservice # 恢复
```

### 证书安装程序(CertificateInstaller)

```shell
pm uninstall --user 0  com.android.certinstaller # 卸载
cmd package install-existing --user 0  com.android.certinstaller # 恢复
```

### 配套设备管理器(CompanionDeviceManager)

```shell
pm uninstall --user 0  com.android.companiondevicemanager # 卸载
cmd package install-existing --user 0  com.android.companiondevicemanager # 恢复
```

### 时钟(Clock)

```shell
pm uninstall --user 0  com.android.deskclock # 卸载
cmd package install-existing --user 0  com.android.deskclock # 恢复
```

### 基本互动屏保(BasicDaydreams)

```shell
pm uninstall --user 0  com.android.dreams.basic # 卸载
cmd package install-existing --user 0  com.android.dreams.basic # 恢复
```

### DynamicSystemUpdates

```shell
pm uninstall --user 0  com.android.dynsystem # 卸载
cmd package install-existing --user 0  com.android.dynsystem # 恢复
```

### 电子邮件(Mail)

```shell
pm uninstall --user 0  com.android.email # 卸载
cmd package install-existing --user 0  com.android.email # 恢复
```

### 急救信息(Emergencyinformation)

```shell
pm uninstall --user 0  com.android.emergency # 卸载
cmd package install-existing --user 0  com.android.emergency # 恢复
```

### 外部存储设备(ExternalStorage)

```shell
pm uninstall --user 0  com.android.externalstorage # 卸载
cmd package install-existing --user 0  com.android.externalstorage # 恢复
```

### 文件管理(FileManager)

```shell
pm uninstall --user 0  com.android.fileexplorer # 卸载
cmd package install-existing --user 0  com.android.fileexplorer # 恢复
```

### HTML查看器(HTMLViewer)

```shell
pm uninstall --user 0  com.android.htmlviewer # 卸载
cmd package install-existing --user 0  com.android.htmlviewer # 恢复
```

### 输入设备(InputDevices)

```shell
pm uninstall --user 0  com.android.inputdevices # 卸载
cmd package install-existing --user 0  com.android.inputdevices # 恢复
```

### 工作设置(WorkSetup)

```shell
pm uninstall --user 0  com.android.managedprovisioning # 卸载
cmd package install-existing --user 0  com.android.managedprovisioning # 恢复
```

### MmsService

```shell
pm uninstall --user 0  com.android.mms.service # 卸载
cmd package install-existing --user 0  com.android.mms.service # 恢复
```

### PacProcessor

```shell
pm uninstall --user 0  com.android.pacprocessor # 卸载
cmd package install-existing --user 0  com.android.pacprocessor # 恢复
```

### 打印处理服务(PrintSpooler)

```shell
pm uninstall --user 0  com.android.printspooler # 卸载
cmd package install-existing --user 0  com.android.printspooler # 恢复
```

### 主屏幕提示(Homescreentips)

```shell
pm uninstall --user 0  com.android.protips # 卸载
cmd package install-existing --user 0  com.android.protips # 恢复
```

### 存储已屏蔽的号码(BlockedNumbersStorage)

```shell
pm uninstall --user 0  com.android.providers.blockednumber # 卸载
cmd package install-existing --user 0  com.android.providers.blockednumber # 恢复
```

### 日历存储(Calendarstorage)

```shell
pm uninstall --user 0  com.android.providers.calendar # 卸载
cmd package install-existing --user 0  com.android.providers.calendar # 恢复
```

### 联系人存储(ContactsStorage)

```shell
pm uninstall --user 0  com.android.providers.contacts # 卸载
cmd package install-existing --user 0  com.android.providers.contacts # 恢复
```

### 下载管理程序(Downloads)

```shell
pm uninstall --user 0  com.android.providers.downloads # 卸载
cmd package install-existing --user 0  com.android.providers.downloads # 恢复
```

### 下载管理(Downloads)

```shell
pm uninstall --user 0  com.android.providers.downloads.ui # 卸载
cmd package install-existing --user 0  com.android.providers.downloads.ui # 恢复
```

### 用户字典(UserDictionary)

```shell
pm uninstall --user 0  com.android.providers.userdictionary # 卸载
cmd package install-existing --user 0  com.android.providers.userdictionary # 恢复
```

### ProxyHandler

```shell
pm uninstall --user 0  com.android.proxyhandler # 卸载
cmd package install-existing --user 0  com.android.proxyhandler # 恢复
```

### 搜索(Search)

```shell
pm uninstall --user 0  com.android.quicksearchbox # 卸载
cmd package install-existing --user 0  com.android.quicksearchbox # 恢复
```

### SecureElementUnknownlication

```shell
pm uninstall --user 0  com.android.se # 卸载
cmd package install-existing --user 0  com.android.se # 恢复
```

### Shell

```shell
pm uninstall --user 0  com.android.shell # 卸载
cmd package install-existing --user 0  com.android.shell # 恢复
```

### SimUnknownDialog

```shell
pm uninstall --user 0  com.android.simUnknowndialog # 卸载
cmd package install-existing --user 0  com.android.simUnknowndialog # 恢复
```

### 声音(Sounds)

```shell
pm uninstall --user 0  com.android.soundpicker # 卸载
cmd package install-existing --user 0  com.android.soundpicker # 恢复
```

### 录音机(Recorder)

```shell
pm uninstall --user 0  com.android.soundrecorder # 卸载
cmd package install-existing --user 0  com.android.soundrecorder # 恢复
```

### IntentFilterVerificationService

```shell
pm uninstall --user 0  com.android.statementservice # 卸载
cmd package install-existing --user 0  com.android.statementservice # 恢复
```

### USIM卡应用(SIMClaro)

```shell
pm uninstall --user 0  com.android.stk # 卸载
cmd package install-existing --user 0  com.android.stk # 恢复
```

### 系统跟踪(SystemTracing)

```shell
pm uninstall --user 0  com.android.traceur # 卸载
cmd package install-existing --user 0  com.android.traceur # 恢复
```

### VpnDialogs

```shell
pm uninstall --user 0  com.android.vpndialogs # 卸载
cmd package install-existing --user 0  com.android.vpndialogs # 恢复
```

### LiveWallpaperPicker

```shell
pm uninstall --user 0  com.android.wallpaper.livepicker # 卸载
cmd package install-existing --user 0  com.android.wallpaper.livepicker # 恢复
```

### CatchLog(Loggenerator)

```shell
pm uninstall --user 0  com.bsp.catchlog # 卸载
cmd package install-existing --user 0  com.bsp.catchlog # 恢复
```

### FIDOUAF1.0ASM

```shell
pm uninstall --user 0  com.fido.asm # 卸载
cmd package install-existing --user 0  com.fido.asm # 恢复
```

### FIDOUAF1.0Client

```shell
pm uninstall --user 0  com.fido.xiaomi.uafclient # 卸载
cmd package install-existing --user 0  com.fido.xiaomi.uafclient # 恢复
```

### Goodix指纹(DelmarFingerprint)

```shell
pm uninstall --user 0  com.goodix.fingerprint.setting # 卸载
cmd package install-existing --user 0  com.goodix.fingerprint.setting # 恢复
```

### PrintServiceRecommendationService

```shell
pm uninstall --user 0  com.google.android.printservice.recommendation # 卸载
cmd package install-existing --user 0  com.google.android.printservice.recommendation # 恢复
```

### Google通讯录同步(GoogleContactsSync)

```shell
pm uninstall --user 0  com.google.android.syncadapters.contacts # 卸载
cmd package install-existing --user 0  com.google.android.syncadapters.contacts # 恢复
```

### 小米画报(MiWallpaperCarousel)

```shell
pm uninstall --user 0  com.mfashiongallery.emag # 卸载
cmd package install-existing --user 0  com.mfashiongallery.emag # 恢复
```

### 健康(Health)

```shell
pm uninstall --user 0  com.mi.health # 卸载
cmd package install-existing --user 0  com.mi.health # 恢复
```

### 投屏(Cast)

```shell
pm uninstall --user 0  com.milink.service # 卸载
cmd package install-existing --user 0  com.milink.service # 恢复
```

### 钱包(Wallet)

```shell
pm uninstall --user 0  com.mipay.wallet # 卸载
cmd package install-existing --user 0  com.mipay.wallet # 恢复
```

### 小米无障碍(MiAccessibility)

```shell
pm uninstall --user 0  com.miui.accessibility # 卸载
cmd package install-existing --user 0  com.miui.accessibility # 恢复
```

### 小米分析 Analytics

```shell
pm uninstall --user 0  com.miui.analytics # 卸载
cmd package install-existing --user 0  com.miui.analytics # 恢复
```

### AudioEffect

```shell
pm uninstall --user 0  com.miui.audioeffect # 卸载
cmd package install-existing --user 0  com.miui.audioeffect # 恢复
```

### 录音助手(Recordingassistant)

```shell
pm uninstall --user 0  com.miui.audiomonitor # 卸载
cmd package install-existing --user 0  com.miui.audiomonitor # 恢复
```

### 用户反馈(Feedback)

```shell
pm uninstall --user 0  com.miui.bugreport # 卸载
cmd package install-existing --user 0  com.miui.bugreport # 恢复
```

### 计算器(Calculator)

```shell
pm uninstall --user 0  com.miui.calculator # 卸载
cmd package install-existing --user 0  com.miui.calculator # 恢复
```

### CIT

```shell
pm uninstall --user 0  com.miui.cit # 卸载
cmd package install-existing --user 0  com.miui.cit # 恢复
```

### 垃圾清理(Cleaner)

```shell
pm uninstall --user 0  com.miui.cleanmaster # 卸载
cmd package install-existing --user 0  com.miui.cleanmaster # 恢复
```

### 桌面云备份(Cloudbackup​)

```shell
pm uninstall --user 0  com.miui.cloudbackup # 卸载
cmd package install-existing --user 0  com.miui.cloudbackup # 恢复
```

### 小米云服务(XiaomiCloud)

```shell
pm uninstall --user 0  com.miui.cloudservice # 卸载
cmd package install-existing --user 0  com.miui.cloudservice # 恢复
```

### CloudServiceSysbase

```shell
pm uninstall --user 0  com.miui.cloudservice.sysbase # 卸载
cmd package install-existing --user 0  com.miui.cloudservice.sysbase # 恢复
```

### 指南针(Compass)

```shell
pm uninstall --user 0  com.miui.compass # 卸载
cmd package install-existing --user 0  com.miui.compass # 恢复
```

### 应用程序扩展服务(UnknownlicationExtensionService)

```shell
pm uninstall --user 0  com.miui.contentcatcher # 卸载
cmd package install-existing --user 0  com.miui.contentcatcher # 恢复
```

### 小爱建议

```shell
pm uninstall --user 0  com.xiaomi.aireco # 卸载
cmd package install-existing --user 0  com.xiaomi.aireco # 恢复
```

### 广告服务API

```shell
pm uninstall --user 0  com.android.adservices.api # 卸载
cmd package install-existing --user 0  com.android.adservices.api # 恢复
```

### 传送门(Taplus)

```shell
pm uninstall --user 0  com.miui.contentextension # 卸载
cmd package install-existing --user 0  com.miui.contentextension # 恢复
```

### MIUI质量服务(MIUIDaemon)

```shell
pm uninstall --user 0  com.miui.daemon # 卸载
cmd package install-existing --user 0  com.miui.daemon # 恢复
```

### Bokeh

```shell
pm uninstall --user 0  com.miui.extraphoto # 卸载
cmd package install-existing --user 0  com.miui.extraphoto # 恢复
```

### 相册(Gallery)

```shell
pm uninstall --user 0  com.miui.gallery # 卸载
cmd package install-existing --user 0  com.miui.gallery # 恢复
```

### 安全守护服务(FamilyGuard)

```shell
pm uninstall --user 0  com.miui.greenguard # 卸载
cmd package install-existing --user 0  com.miui.greenguard # 恢复
```

### 小米换机(MiMover)

```shell
pm uninstall --user 0  com.miui.huanji # 卸载
cmd package install-existing --user 0  com.miui.huanji # 恢复
```

### 快应用服务框架(QuickUnknownsServiceFramework)

```shell
pm uninstall --user 0  com.miui.hybrid # 卸载
cmd package install-existing --user 0  com.miui.hybrid # 恢复
```

### 智慧生活(SmartScenes)

```shell
pm uninstall --user 0  com.miui.hybrid.accessory # 卸载
cmd package install-existing --user 0  com.miui.hybrid.accessory # 恢复
```

### 维修模式(MaintenanceMode)

```shell
pm uninstall --user 0  com.miui.maintenancemode # 卸载
cmd package install-existing --user 0  com.miui.maintenancemode # 恢复
```

### 小米相册-编辑(GalleryEditor)

```shell
pm uninstall --user 0  com.miui.mediaeditor # 卸载
cmd package install-existing --user 0  com.miui.mediaeditor # 恢复
```

### MediaFeature合集

```shell
pm uninstall --user 0  com.miui.mediafeature # 卸载
cmd package install-existing --user 0  com.miui.mediafeature # 恢复
```

### 小米云同步 MiCloudSync

```shell
pm uninstall --user 0  com.miui.micloudsync # 卸载
cmd package install-existing --user 0  com.miui.micloudsync # 恢复
```

### 服务与反馈(Services&feedback)

```shell
pm uninstall --user 0  com.miui.miservice # 卸载
cmd package install-existing --user 0  com.miui.miservice # 恢复
```

### 小米互传(MiShare)

```shell
pm uninstall --user 0  com.miui.mishare.connectivity # 卸载
cmd package install-existing --user 0  com.miui.mishare.connectivity # 恢复
```

### 音质音效(Earphones)

```shell
pm uninstall --user 0  com.miui.misound # 卸载
cmd package install-existing --user 0  com.miui.misound # 恢复
```

### 壁纸(WallPaper)

```shell
pm uninstall --user 0  com.miui.miwallpaper # 卸载
cmd package install-existing --user 0  com.miui.miwallpaper # 恢复
```

### 内容中心(ContentCenter)

```shell
pm uninstall --user 0  com.miui.newhome # 卸载
cmd package install-existing --user 0  com.miui.newhome # 恢复
```

### 小米云盘(MiDrive)

```shell
pm uninstall --user 0  com.miui.newmidrive # 卸载
cmd package install-existing --user 0  com.miui.newmidrive # 恢复
```

### 小米支付(NextPay)

```shell
pm uninstall --user 0  com.miui.nextpay # 卸载
cmd package install-existing --user 0  com.miui.nextpay # 恢复
```

### 笔记(Notes)

```shell
pm uninstall --user 0  com.miui.notes # 卸载
cmd package install-existing --user 0  com.miui.notes # 恢复
```

### 智能助理(Unknownvault) 负一屏

```shell
pm uninstall --user 0  com.miui.personalassistant # 卸载
cmd package install-existing --user 0  com.miui.personalassistant # 恢复
```

### 常用语(Frequentphrases)

```shell
pm uninstall --user 0  com.miui.phrase # 卸载
cmd package install-existing --user 0  com.miui.phrase # 恢复
```

### 音乐(Music)

```shell
pm uninstall --user 0  com.miui.player # 卸载
cmd package install-existing --user 0  com.miui.player # 恢复
```

### 屏幕录制(ScreenRecorder)

```shell
pm uninstall --user 0  com.miui.screenrecorder # 卸载
cmd package install-existing --user 0  com.miui.screenrecorder # 恢复
```

### 系统服务组件(Systemserviceplugin)

```shell
pm uninstall --user 0  com.miui.securityadd # 卸载
cmd package install-existing --user 0  com.miui.securityadd # 恢复
```

### 安全核心组件(SecurityCoreComponent)

```shell
pm uninstall --user 0  com.miui.securitycore # 卸载
cmd package install-existing --user 0  com.miui.securitycore # 恢复
```

### 小米安全键盘(MiSecureKeyboard)

```shell
pm uninstall --user 0  com.miui.securityinputmethod # 卸载
cmd package install-existing --user 0  com.miui.securityinputmethod # 恢复
```

### 智能服务(SmartService)

```shell
pm uninstall --user 0  com.miui.systemAdSolution # 卸载
cmd package install-existing --user 0  com.miui.systemAdSolution # 恢复
```

### 三方应用异常分析(ThirdpartyUnknownproblems)

```shell
pm uninstall --user 0  com.miui.thirdUnknownassistant # 卸载
cmd package install-existing --user 0  com.miui.thirdUnknownassistant # 恢复
```

### 悬浮球(Quickball)

```shell
pm uninstall --user 0  com.miui.touchassistant # 卸载
cmd package install-existing --user 0  com.miui.touchassistant # 恢复
```

### 小米视频(MiVideo)

```shell
pm uninstall --user 0  com.miui.video # 卸载
cmd package install-existing --user 0  com.miui.video # 恢复
```

### 我的服务(Myservices)

```shell
pm uninstall --user 0  com.miui.vipservice # 卸载
cmd package install-existing --user 0  com.miui.vipservice # 恢复
```

### 全球上网(MiRoaming)

```shell
pm uninstall --user 0  com.miui.virtualsim # 卸载
cmd package install-existing --user 0  com.miui.virtualsim # 恢复
```

### 小爱同学(MiAI)

```shell
pm uninstall --user 0  com.miui.voiceassist # 卸载
cmd package install-existing --user 0  com.miui.voiceassist # 恢复
```

### 语音唤醒(Wakewithvoice)

```shell
pm uninstall --user 0  com.miui.voicetrigger # 卸载
cmd package install-existing --user 0  com.miui.voicetrigger # 恢复
```

### MiuiVpnSdkManager

```shell
pm uninstall --user 0  com.miui.vpnsdkmanager # 卸载
cmd package install-existing --user 0  com.miui.vpnsdkmanager # 恢复
```

### MConnService

```shell
pm uninstall --user 0  com.miui.vsimcore # 卸载
cmd package install-existing --user 0  com.miui.vsimcore # 恢复
```

### 天气(Weather)

```shell
pm uninstall --user 0  com.miui.weather2 # 卸载
cmd package install-existing --user 0  com.miui.weather2 # 恢复
```

### WMService

```shell
pm uninstall --user 0  com.miui.wmsvc # 卸载
cmd package install-existing --user 0  com.miui.wmsvc # 恢复
```

### 生活黄页(Yellowpages)

```shell
pm uninstall --user 0  com.miui.yellowpage # 卸载
cmd package install-existing --user 0  com.miui.yellowpage # 恢复
```

### 小米弹屏通知

```shell
pm uninstall --user 0  com.xiaomi.barrage # 卸载
cmd package install-existing --user 0  com.xiaomi.barrage # 恢复
```

### textaction

```shell
pm uninstall --user 0  com.miuix.editor # 卸载
cmd package install-existing --user 0  com.miuix.editor # 恢复
```

### SystemHelper

```shell
pm uninstall --user 0  com.mobiletools.systemhelper # 卸载
cmd package install-existing --user 0  com.mobiletools.systemhelper # 恢复
```

### WAPI证书(WAPIcertificate)

```shell
pm uninstall --user 0  com.wapi.wapicertmanage # 卸载
cmd package install-existing --user 0  com.wapi.wapicertmanage # 恢复
```

### 小米商城系统组件(MiStoreSystemComponents)

```shell
pm uninstall --user 0  com.xiaomi.ab # 卸载
cmd package install-existing --user 0  com.xiaomi.ab # 恢复
```

### AI电话助手 小爱接听

```shell
pm uninstall --user 0  com.xiaomi.aiasst.service # 卸载
cmd package install-existing --user 0  com.xiaomi.aiasst.service # 恢复
```

### 小爱翻译 AiasstVision

```shell
pm uninstall --user 0  com.xiaomi.aiasst.vision # 卸载
cmd package install-existing --user 0  com.xiaomi.aiasst.vision # 恢复
```

### 火星超级壁纸

```shell
pm uninstall --user 0  com.miui.miwallpaper.mars # 卸载
cmd package install-existing --user 0  com.miui.miwallpaper.mars # 恢复
```

### 地球超级壁纸

```shell
pm uninstall --user 0  com.miui.miwallpaper.earth # 卸载
cmd package install-existing --user 0  com.miui.miwallpaper.earth # 恢复
```

### 几何超级壁纸

```shell
pm uninstall --user 0  com.miui.miwallpaper.geometry # 卸载
cmd package install-existing --user 0  com.miui.miwallpaper.geometry # 恢复
```

### 土星超级壁纸

```shell
pm uninstall --user 0  com.miui.miwallpaper.saturn # 卸载
cmd package install-existing --user 0  com.miui.miwallpaper.saturn # 恢复
```

### MIUIBluetooth

```shell
pm uninstall --user 0  com.xiaomi.bluetooth # 卸载
cmd package install-existing --user 0  com.xiaomi.bluetooth # 恢复
```

### 相机标定(CameraTools)

```shell
pm uninstall --user 0  com.xiaomi.cameratools # 卸载
cmd package install-existing --user 0  com.xiaomi.cameratools # 恢复
```

### digitalkey

```shell
pm uninstall --user 0  com.xiaomi.digitalkey # 卸载
cmd package install-existing --user 0  com.xiaomi.digitalkey # 恢复
```

### 驾车场景(MIUIDirveScene)

```shell
pm uninstall --user 0  com.xiaomi.drivemode # 卸载
cmd package install-existing --user 0  com.xiaomi.drivemode # 恢复
```

### 游戏中心(Games)

```shell
pm uninstall --user 0  com.xiaomi.gamecenter # 卸载
cmd package install-existing --user 0  com.xiaomi.gamecenter # 恢复
```

### 游戏服务(GameService)

```shell
pm uninstall --user 0  com.xiaomi.gamecenter.sdk.service # 卸载
cmd package install-existing --user 0  com.xiaomi.gamecenter.sdk.service # 恢复
```

### Polaris

```shell
pm uninstall --user 0  com.xiaomi.gnss.polaris # 卸载
cmd package install-existing --user 0  com.xiaomi.gnss.polaris # 恢复
```

### Joyose 小米云控

```shell
pm uninstall --user 0  com.xiaomi.joyose # 卸载
cmd package install-existing --user 0  com.xiaomi.joyose # 恢复
```

### 天星金融(AirstarFinance)

```shell
pm uninstall --user 0  com.xiaomi.jr # 卸载
cmd package install-existing --user 0  com.xiaomi.jr # 恢复
```

### 游戏相关 Gaming Mi Macro

```shell
pm uninstall --user 0  com.xiaomi.macro # 卸载
cmd package install-existing --user 0  com.xiaomi.macro # 恢复
```

### 讯飞输入法-小米版

```shell
pm uninstall --user 0  com.iflytek.inputmethod.miui # 卸载
cmd package install-existing --user 0  com.iflytek.inputmethod.miui # 恢复
```

### 网络位置服务(Networklocationprovider)

```shell
pm uninstall --user 0  com.xiaomi.metoknlp # 卸载
cmd package install-existing --user 0  com.xiaomi.metoknlp # 恢复
```

### 小米互联通信服务(MiConnect)

```shell
pm uninstall --user 0  com.xiaomi.mi_connect_service # 卸载
cmd package install-existing --user 0  com.xiaomi.mi_connect_service # 恢复
```

### 游戏高能时刻(MiGameService)

```shell
pm uninstall --user 0  com.xiaomi.migameservice # 卸载
cmd package install-existing --user 0  com.xiaomi.migameservice # 恢复
```

### 小米澎湃AI引擎

```shell
pm uninstall --user 0  com.xiaomi.aicr # 卸载
cmd package install-existing --user 0  com.xiaomi.aicr # 恢复
```

### 投屏服务(Casting)

```shell
pm uninstall --user 0  com.xiaomi.miplay_client # 卸载
cmd package install-existing --user 0  com.xiaomi.miplay_client # 恢复
```

### MiRCS

```shell
pm uninstall --user 0  com.xiaomi.mircs # 卸载
cmd package install-existing --user 0  com.xiaomi.mircs # 恢复
```

### MIUI+Beta版(MIUI+Beta)

```shell
pm uninstall --user 0  com.xiaomi.mirror # 卸载
cmd package install-existing --user 0  com.xiaomi.mirror # 恢复
```

### 背屏(Reardisplay)

```shell
pm uninstall --user 0  com.xiaomi.misubscreenui # 卸载
cmd package install-existing --user 0  com.xiaomi.misubscreenui # 恢复
```

### TAMservice

```shell
pm uninstall --user 0  com.xiaomi.otrpbroker # 卸载
cmd package install-existing --user 0  com.xiaomi.otrpbroker # 恢复
```

### 米币支付(MiCoin)

```shell
pm uninstall --user 0  com.xiaomi.payment # 卸载
cmd package install-existing --user 0  com.xiaomi.payment # 恢复
```

### 耗电检测(PowerDetector)

```shell
pm uninstall --user 0  com.xiaomi.powerchecker # 卸载
cmd package install-existing --user 0  com.xiaomi.powerchecker # 恢复
```

### 扫一扫(Scanner)

```shell
pm uninstall --user 0  com.xiaomi.scanner # 卸载
cmd package install-existing --user 0  com.xiaomi.scanner # 恢复
```

### SecurityOnetrackService

```shell
pm uninstall --user 0  com.xiaomi.security.onetrack # 卸载
cmd package install-existing --user 0  com.xiaomi.security.onetrack # 恢复
```

### 小米商城

```shell
pm uninstall --user 0  com.xiaomi.shop # 卸载
cmd package install-existing --user 0  com.xiaomi.shop # 恢复
```

### 米家(MiHome)

```shell
pm uninstall --user 0  com.xiaomi.smarthome # 卸载
cmd package install-existing --user 0  com.xiaomi.smarthome # 恢复
```

### 小米社区

```shell
pm uninstall --user 0  com.xiaomi.vipaccount # 卸载
cmd package install-existing --user 0  com.xiaomi.vipaccount # 恢复
```

### 小米有品

```shell
pm uninstall --user 0  com.xiaomi.youpin # 卸载
cmd package install-existing --user 0  com.xiaomi.youpin # 恢复
```

### 设备信息(DeviceInfo)

```shell
pm uninstall --user 0  com.qti.qualcomm.deviceinfo # 卸载
cmd package install-existing --user 0  com.qti.qualcomm.deviceinfo # 恢复
```

### QDCM-FF

```shell
pm uninstall --user 0  com.qti.snapdragon.qdcm_ff # 卸载
cmd package install-existing --user 0  com.qti.snapdragon.qdcm_ff # 恢复
```

### LocationServices

```shell
pm uninstall --user 0  com.qualcomm.location # 卸载
cmd package install-existing --user 0  com.qualcomm.location # 恢复
```

### CneUnknown

```shell
pm uninstall --user 0  com.qualcomm.qti.cne # 卸载
cmd package install-existing --user 0  com.qualcomm.qti.cne # 恢复
```

### AdrenoGraphicsDrivers

```shell
pm uninstall --user 0  com.qualcomm.qti.gpudrivers.lahaina.api30 # 卸载
cmd package install-existing --user 0  com.qualcomm.qti.gpudrivers.lahaina.api30 # 恢复
```

### SecCamService

```shell
pm uninstall --user 0  com.qualcomm.qti.seccamservice # 卸载
cmd package install-existing --user 0  com.qualcomm.qti.seccamservice # 恢复
```

### SystemHelperService

```shell
pm uninstall --user 0  com.qualcomm.qti.services.systemhelper # 卸载
cmd package install-existing --user 0  com.qualcomm.qti.services.systemhelper # 恢复
```

### XRCB

```shell
pm uninstall --user 0  com.qualcomm.qti.xrcb # 卸载
cmd package install-existing --user 0  com.qualcomm.qti.xrcb # 恢复
```

### WfdService

```shell
pm uninstall --user 0  com.qualcomm.wfd.service # 卸载
cmd package install-existing --user 0  com.qualcomm.wfd.service # 恢复
```

### hplp

```shell
pm uninstall --user 0  com.qxwz.ps.hpls # 卸载
cmd package install-existing --user 0  com.qxwz.ps.hpls # 恢复
```

### aidlserverdemo

```shell
pm uninstall --user 0  com.rongcard.eidapi # 卸载
cmd package install-existing --user 0  com.rongcard.eidapi # 恢复
```

### IFAAService

```shell
pm uninstall --user 0  org.ifaa.aidl.manager # 卸载
cmd package install-existing --user 0  org.ifaa.aidl.manager # 恢复
```

### CACertApp

```shell
pm uninstall --user 0  vendor.qti.hardware.cacert.server # 卸载
cmd package install-existing --user 0  vendor.qti.hardware.cacert.server # 恢复
```

### QesdkSysApp

```shell
pm uninstall --user 0  vendor.qti.qesdk.sysservice # 卸载
cmd package install-existing --user 0  vendor.qti.qesdk.sysservice # 恢复
```

### 万能遥控(MiRemote)

```shell
pm uninstall --user 0  com.duokan.phone.remotecontroller # 卸载
cmd package install-existing --user 0  com.duokan.phone.remotecontroller # 恢复
```

### 阅读

```shell
pm uninstall --user 0  com.duokan.reader # 卸载
cmd package install-existing --user 0  com.duokan.reader # 恢复
```

### 小米文档查看器（WPS定制） `可删`

```shell
pm uninstall --user 0  cn.wps.moffice_eng.xiaomi.lite # 卸载
cmd package install-existing --user 0  cn.wps.moffice_eng.xiaomi.lite # 恢复
```

### 搜狗输入法小米版 `可删`

```shell
pm uninstall --user 0  com.sohu.inputmethod.sogou.xiaomi # 卸载
cmd package install-existing --user 0  com.sohu.inputmethod.sogou.xiaomi # 恢复
```
