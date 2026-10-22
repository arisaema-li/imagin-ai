# 绘梦 ImaginAI · 发布仓库

**本仓库仅用于分发安装包与自动更新文件，不包含源码。**

## 下载

最新版本请到 [Releases](https://github.com/x1094724864/imagin-ai/releases/latest) 下载。

## 每次发布的文件

| 文件 | 用途 |
| --- | --- |
| `绘梦-setup-<版本>-x64.exe` | Windows 安装包（NSIS） |
| `绘梦-setup-<版本>-x64.exe.blockmap` | 增量更新的块索引 |
| `latest.yml` | electron-updater 读取的版本清单 |

## 系统要求

- Windows 10 及以上（x64）
- 安装包未做代码签名，首次运行可能出现 SmartScreen 提示，选择「更多信息 → 仍要运行」即可

## 数据位置

- 配置与会话数据库：`%APPDATA%\ImaginAI`
- 图库图片：安装目录下 `library\<会话ID>\<日期>\`
