# XposedSmsCode

<div align="center">

![Total Downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.github.tianma8023.xposed.smscode/total) [![Latest Release](https://img.shields.io/github/v/release/magisk317/XposedSmsCode?include_prereleases&label=Latest%20Release)](https://github.com/magisk317/XposedSmsCode/releases) [![Stars](https://img.shields.io/github/stars/magisk317/XposedSmsCode?style=social)](https://github.com/magisk317/XposedSmsCode)

</div>

识别短信验证码的Xposed模块，并将验证码拷贝到剪切板，亦可以自动输入验证码。

An Xposed module which can recognize, parse SMS code and copy it to clipboard when a new message arrives. It can also input SMS code automatically.

# 功能
- 收到验证码短信后将验证码复制到系统剪贴板
- 收到验证码时显示Toast
- 收到验证码时显示通知
- 将验证码短信标记为已读（试验性）
- 删除验证码短信（试验性）
- 拦截验证码短信（试验性）
- 自定义验证码短信关键字（正则表达式）
- 自定义验证码匹配规则，并支持规则导入导出
- 自动输入验证码

# Features
- Copy verification code to clipboard when a new message arrives.
- Show toast when a SMS verification code is copied.
- Show notification when code SMS parsed.
- Mark verification code message as read(experimental).
- Delete verification SMS when it's extracted successfully(experimental).
- Block verification SMS if it's extracted successfully(experimental).
- Custom keywords about verification code message (regular expressions allowed).
- Support the SMS code match rules customization, importation and exportation.
- Auto-input SMS code.

# 更多
参考: [详细信息](https://github.com/magisk317/XposedSmsCode/blob/dev/README.md)

# More
refer to [More Information](https://github.com/magisk317/XposedSmsCode/blob/dev/README-EN.md)