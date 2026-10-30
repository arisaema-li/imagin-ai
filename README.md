# 绘梦 ImaginAI · 发布仓库

**本仓库仅用于分发安装包与自动更新文件，不包含源码。**

## 当前版本：v1.1.0

发布日期：2026-10-30 · [查看发布说明](https://github.com/arisaema-li/imagin-ai/releases/tag/v1.1.0)

- 新增独立应用图标选择，同步桌面窗口、托盘与已有快捷方式。
- 调整马卡龙主题配色，支持自定义取色、实时预览及最近使用的颜色。
- 新增实验室设置，可控制自定义主题色和悬停提示配色。
- 改善更新检查、退出安装和更新完成提示。
- 修复聊天提交、图片重试和划词引用相关问题。

## 下载

最新版本请到 [Releases](https://github.com/arisaema-li/imagin-ai/releases/latest) 下载。

## 每次发布的文件

| 文件 | 用途 |
| --- | --- |
| `huimeng-setup-<版本>-x64.exe` | Windows 安装包（NSIS） |
| `huimeng-setup-<版本>-x64.exe.blockmap` | 增量更新的块索引 |
| `latest.yml` | electron-updater 读取的版本清单 |

## 系统要求

- Windows 10 及以上（x64）
- 安装包未做代码签名，首次运行可能出现 SmartScreen 提示，选择「更多信息 → 仍要运行」即可

## 数据位置

- 配置与会话数据库：`%APPDATA%\ImaginAI`
- 图库图片：安装目录下 `library\<会话ID>\<日期>\`
