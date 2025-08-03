# 小米 HyperOS/MIUI 优化工具

> 无需ROOT，移除不必要的系统应用，优化手机性能

# 环境准备

## Windwos

1. 下载并解压 [ADB工具 Android SDK Platform Tools](https://www.123912.com/s/iz5Pjv-GeB6d)，然后进入解压后的 platform-tools 文件夹

2. 按住 Shift 键并右键点击空白处，选择 `在此处打开命令窗口` 或 `在此处打开 PowerShell 窗口`

3. [在手机设置中启用开发者选项和 USB 调试](#在手机设置中启用开发者选项和 USB 调试)

4. 使用 USB 数据线连接手机到电脑

5. 在命令行中验证连接

   ``` she
   ~> .\adb.exe devices
   List of devices attached
   3406d1d5	device
   ```

6. 进入 ADB Shell 环境

   ``` shell
   ~> .\adb.exe shell
   vermeer:/ $
   ```

## macOS

1. 使用 Homebrew 安装

   ``` shell
   brew install android-platform-tools
   ```

2. [在手机设置中启用开发者选项和 USB 调试](#在手机设置中启用开发者选项和 USB 调试)

3. 使用 USB 数据线连接手机到 Mac

4. 在终端中验证连接

   ``` shell
   ~> adb devices
   List of devices attached
   3406d1d5	device
   ```

5. 进入 ADB Shell 环境

   ``` shell
   ~> adb shell
   vermeer:/ $
   ```

## Linux

1. 安装命令

   - Ubuntu/Debian

     ``` she
     sudo apt install adb
     ```

   - CentOS/RHEL/Fedora

     ``` shell
     sudo yum install android-tools
     ```

   - Arch Linux

     ``` shell
     sudo pacman -S android-tools
     ```

2. [在手机设置中启用开发者选项和 USB 调试](#在手机设置中启用开发者选项和 USB 调试)

3. 使用 USB 数据线连接手机到电脑

4. 在终端中验证连接

   ``` shell
   ~> adb devices
   List of devices attached
   3406d1d5	device
   ```

5. 进入 ADB Shell 环境

   ``` shell
   ~> adb shell
   vermeer:/ $
   ```


# 在手机设置中启用开发者选项和 USB 调试

1. 进入手机 `设置` → `我的设备` → `(往下翻)` → `全部参数与信息`
2. 连续点击 `OS版本` 7次，开启开发者选项
3. 返回设置，进入 `更多设置` → `开发者选项`
4. 开启 `USB调试` 和 `USB调试 (安全设置)`
5. 使用数据线连接电脑，在手机上确认允许USB调试

# 一键优化

## 卸载优化

一次性执行一批非必要软件的 `卸载` 和 `优化` 命令，必须在 ADB Shell 环境中执行

``` shell
pm uninstall --user 0 com.miui.hybrid && pm uninstall --user 0 com.miui.analytics && pm uninstall --user 0 com.miui.daemon && pm uninstall --user 0 com.miui.systemAdSolution && settings put system send_security_reports 0 && settings put secure send_action_app_error 0 && settings put global activity_starts_logging_enabled 0
```

## 恢复还原

一次性执行还原命令以恢复原有软件和设置，必须在 ADB Shell 环境中执行

``` shell
cmd package install-existing --user 0 com.miui.hybrid && cmd package   install-existing --user 0 com.miui.analytics && cmd package install-existing --user 0 com.miui.daemon && cmd package install-existing --user 0 com.miui.systemAdSolution && settings put system send_security_reports 1 && settings put secure send_action_app_error 1 && settings put global activity_starts_logging_enabled 1
```

# 应用卸载

以下命令只能在 ADB Shell 环境中执行

命令执行成功后会显示 `Success` 信息，表示应用已成功移除/恢复

返回"Failure [not installed for 0]"表示该应用已经卸载过

## 一般性应用

### 小米快应用框架

``` shell
pm uninstall --user 0 com.miui.hybrid # 卸载（卸载后，在设置中搜索"快应用"，找不到则成功卸载）
cmd package install-existing --user 0 com.miui.hybrid # 恢复
```

### 小米云控（此组件有争议，卸载后可能导致部分功能无法使用）

``` shell
pm uninstall --user 0 com.xiaomi.joyose # 卸载（卸载后，在 设置->应用管理 中搜索"joyose"，找不到则成功卸载）
cmd package install-existing --user 0 com.xiaomi.joyose # 恢复
```

### 小米分析

``` shell
pm uninstall --user 0 com.miui.analytics # 卸载
cmd package install-existing --user 0 com.miui.analytics # 恢复
```

### 小米质量服务

``` shell
pm uninstall --user 0 com.miui.daemon # 卸载
cmd package install-existing --user 0 com.miui.daemon # 恢复
```

### 小米内置广告服务

``` shell
pm uninstall --user 0 com.miui.systemAdSolution # 卸载
cmd package install-existing --user 0 com.miui.systemAdSolution # 恢复
```

## [更多内置组件](built_in_components/built_in_components.md)

# 系统优化

以下命令只能在 ADB Shell 环境中执行

命令执行后通常不会返回任何信息，这是正常现象，表示命令已成功执行

[命令执行异常提示: Exception occurred while executing 'put' ?](aq/exception_occurred_while_executing_[put].md)

## 禁用安全报告

```shell
settings put system send_security_reports 0 # 优化
settings put system send_security_reports 1 # 恢复
```

## 禁用错误报告

```shell
settings put secure send_action_app_error 0 # 优化
settings put secure send_action_app_error 1 # 恢复
```

## 禁用活动日志

```shell
settings put global activity_starts_logging_enabled 0 # 优化
settings put global activity_starts_logging_enabled 1 # 恢复
```

# 超频

固定性能模式，开启后会导致设备发热，请谨慎操作

应同步开启电池设置中的性能模式，此功能开启后可以达到类似超频效果，原理是通过锁定 CPU 和 GPU 的时钟频率来最大化性能，非常适合搭配散热背夹的情况下进行游戏，以获得极佳游戏体验，但日常使用中应关闭它，防止设备过热

```shell
cmd power set-fixed-performance-mode-enabled true # 开启性能模式并固定
cmd power set-fixed-performance-mode-enabled false # 恢复
```

# [谷歌相机安装指南](google_cam_install_guide/google_cam_install_guide.md)

# [手动去除广告](manually_remove_ads/manually_remove_ads.md)

# [常见问题](aq/aq.md)

