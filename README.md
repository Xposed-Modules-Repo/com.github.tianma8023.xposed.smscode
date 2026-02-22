# XposedSmsCode

![Star History Chart](https://api.star-history.com/svg?repos=magisk317/XposedSmsCode&type=Date)

<div align="center">
    <a href="https://play.google.com/store/apps/details?id=com.github.tianma8023.xposed.smscode">
        <img src="https://play.google.com/intl/zh-CN/badges/static/images/badges/zh-cn_badge_web_generic.png" alt="Get it on Google Play" height="80"/>
    </a>
    <a href="https://github.com/magisk317/XposedSmsCode/releases">
        <img src="https://raw.githubusercontent.com/machiav3lli/oandbackupx/master/badge_github.png" alt="Get it on GitHub" height="80"/>
    </a>
</div>

<div align="center">

[![Module Downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.github.tianma8023.xposed.smscode/total?style=flat-square&label=Module%20Downloads)](https://github.com/Xposed-Modules-Repo/com.github.tianma8023.xposed.smscode/releases) [![Commits](https://img.shields.io/github/commit-activity/y/magisk317/XposedSmsCode?style=flat-square)](https://github.com/magisk317/XposedSmsCode/graphs/commit-activity) [![Last Commit](https://img.shields.io/github/last-commit/magisk317/XposedSmsCode?style=flat-square)](https://github.com/magisk317/XposedSmsCode/commits) [![Contributors](https://img.shields.io/github/contributors/magisk317/XposedSmsCode?style=flat-square)](https://github.com/magisk317/XposedSmsCode/graphs/contributors) [![CI](https://img.shields.io/github/actions/workflow/status/magisk317/XposedSmsCode/ci.yml?style=flat-square&label=Build&logo=github-actions&logoColor=white)](https://github.com/magisk317/XposedSmsCode/actions/workflows/ci.yml) [![Latest Release](https://img.shields.io/github/v/release/magisk317/XposedSmsCode?include_prereleases&style=flat-square&logo=github)](https://github.com/magisk317/XposedSmsCode/releases) [![Release Date](https://img.shields.io/github/release-date/magisk317/XposedSmsCode?style=flat-square)](https://github.com/magisk317/XposedSmsCode/releases) [![Downloads](https://img.shields.io/github/downloads/magisk317/XposedSmsCode/total?style=flat-square&color=blue)](https://github.com/magisk317/XposedSmsCode/releases) [![License](https://img.shields.io/github/license/magisk317/XposedSmsCode?style=flat-square)](https://github.com/magisk317/XposedSmsCode/blob/dev/LICENSE)

[![Kotlin](https://img.shields.io/badge/Kotlin-2.3.20--RC-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org) [![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-BOM_2026.02.00-4285F4?style=flat-square&logo=android&logoColor=white)](https://developer.android.com/jetpack/compose) [![Gradle](https://img.shields.io/badge/Gradle-9.5.0--nightly-02303A?style=flat-square&logo=gradle&logoColor=white)](https://gradle.org) [![AGP](https://img.shields.io/badge/AGP-9.2.0--alpha01-3DDC84?style=flat-square&logo=gradle&logoColor=white)](https://developer.android.com/studio/releases/gradle-plugin) [![Min SDK](https://img.shields.io/badge/Min_SDK-24-brightgreen?style=flat-square&logo=android)](https://developer.android.com/about/versions) [![Target SDK](https://img.shields.io/badge/Target_SDK-36-blue?style=flat-square&logo=android)](https://developer.android.com/about/versions) [![Xposed API](https://img.shields.io/badge/Xposed_API-82-orange?style=flat-square)](https://github.com/rovo89/XposedBridge) [![Telegram](https://img.shields.io/badge/Telegram-Group-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/+NR2QaQ4dlEgxYmNl)

</div>

识别短信验证码的Xposed模块，并将验证码拷贝到剪切板，亦可以自动输入验证码。

[English Version](https://github.com/magisk317/XposedSmsCode/blob/dev/README-EN.md)

# 应用截图
<img src="https://raw.githubusercontent.com/magisk317/XposedSmsCode/dev/art/cn/01.png" width="180"/><img src="https://raw.githubusercontent.com/magisk317/XposedSmsCode/dev/art/cn/02.png" width="180"/><img src="https://raw.githubusercontent.com/magisk317/XposedSmsCode/dev/art/cn/03.png" width="180"/>

# 交流与反馈
- [Telegram Group](https://t.me/+NR2QaQ4dlEgxYmNl)
- [Issues](https://github.com/magisk317/XposedSmsCode/issues)

# 使用
1. Root你的设备，安装Xposed框架；
2. 安装本模块，激活并重启；
3. Enjoy it！

欢迎反馈，欢迎提出意见或建议。

# 注意
- **此模块适用于偏原生的系统，其他第三方定制Rom可能不适用。**
- **兼容性：最低 Android 7.0（API 24），目标 Android 16（API 36）。**
- **支持 LSPosed / Xposed API 82+（具体取决于系统与框架实现）。**
- **代码库：100% Kotlin + Jetpack Compose + Room + Coroutines**
- **遇到问题请先阅读模块中的"常见问题"**

# 功能
- 收到验证码短信后将验证码复制到系统剪贴板
- 收到验证码时显示Toast
- 收到验证码时显示通知
- 将验证码短信标记为已读（实验性）
- 验证码提取成功后，删除验证码短信（实验性）
- 拦截验证码短信
- 自定义验证码短信关键字（正则表达式）
- 自定义验证码匹配规则，并支持规则导入导出
- 自动输入验证码

# 文档
- [更新日志 (Changelog)](https://github.com/magisk317/XposedSmsCode/blob/dev/docs/CHANGELOG.md)
- [重构汇总 (Refactoring Summary)](https://github.com/magisk317/XposedSmsCode/blob/dev/docs/REFACTORING.md)
- [隐私政策 (Privacy Policy)](https://github.com/magisk317/XposedSmsCode/blob/dev/docs/PRIVACY.md)

# 源码
- [主仓库 (magisk317/XposedSmsCode)](https://github.com/magisk317/XposedSmsCode)
- [原始项目 (tianma8023/XposedSmsCode)](https://github.com/tianma8023/XposedSmsCode)

# 协议
所有源码遵循 [GPLv3](https://www.gnu.org/licenses/gpl-3.0.txt) 协议。
