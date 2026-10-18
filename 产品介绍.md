# FreeClaimer

> 一键领取多家 AI 编程平台的每日免费额度，无需逐一登录。

![平台](https://img.shields.io/badge/平台-Windows-blue) ![体积](https://img.shields.io/badge/体积-35MB-green) ![许可证](https://img.shields.io/badge/许可证-MIT-orange)

---

## 它能做什么

每天打开一次，点一个按钮，自动领取你在以下平台签到接口里的免费额度：

| 渠道 | 厂商 | 额度类型 |
| --- | --- | --- |
| CodeArts | 华为云 | 积分 |
| WorkBuddy / CodeBuddy | 腾讯 | 积分 |
| LobsterAI | 有道 | 积分 |
| Qoder / Qoder 中国版 | 阿里 | 积分 |
| TRAE | 字节 | 积分 |
| Loomy | 讯飞 | 积分 |
| MiniMax Code | MiniMax | 积分 |
| ZCode | 智谱 | Token |

---

## 特性

- **一键领取全部** —— 按顺序逐个渠道领取，单个账号失败不影响其它账号
- **官网登录** —— 在弹出的官方登录页扫码，凭据只留在你本机
- **余额实时显示** —— 积分与 token 分开统计，一目了然
- **每日自动签到** —— 打开软件自动领一轮，可开关
- **托盘常驻** —— 关闭窗口后缩到托盘，不占用桌面

---

## 快速开始

1. 下载 `FreeClaimer-1.0.0-win-webview2.zip`（35MB）
2. 解压到任意目录
3. 双击 `FreeClaimer.exe`

无需安装 Node，无需管理员权限。Windows 10 1803 及以上自带所需运行时。

---

## 隐私与安全

- 账号凭据使用 **AES-256-GCM** 加密，密钥由 Windows **DPAPI** 保护（绑定当前用户账户）
- 数据仅保存在本地 `%APPDATA%\FreeClaimer`，**绝不上传**
- 不代理、不转发、不修改任何平台协议

---

## 截图

> 待补充应用界面截图

---

## 技术栈

- 界面壳：C# / .NET Framework + WebView2
- 引擎：Node.js（渠道协议与领取编排）
- 界面：原生 DOM，无框架

---

## 免责声明

免费额度由各平台**单方面提供**，随时可能调整、收费或下线。本软件仅调用各平台官方的签到接口，不做任何绕过限制的行为。

---

## 许可证

[MIT](LICENSE)

渠道协议来自第三方 MIT 项目 [deepseek-harness-codearts](https://gitee.com/iJetLi/deepseek-harness-codearts)，详见 [NOTICE.md](NOTICE.md)。
