# MarkEditor

> 单文件、零依赖、完全离线的所见即所得 Markdown 编辑器 —— Typora 的免费开源替代品。

一个 HTML 文件就是全部：无需安装、无需联网、无需注册，双击即用。支持数学公式、Mermaid 图表、多主题、导出 Word/HTML/PDF、本地工作区直读直写。

[![version](https://img.shields.io/badge/version-1.0.3-blue)](https://github.com/YCG1995/MarkEditor/releases)
[![license](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![platform](https://img.shields.io/badge/platform-cross--platform-orange)](#下载)
[![online](https://img.shields.io/badge/在线体验-MarkEditor-brightgreen)](#在线体验)

---

## 在线体验

无需下载，浏览器直接打开：

**https://ycg1995.github.io/MarkEditor/**

---

## 下载

桌面版基于 [Neutralinojs](https://neutralino.js.org/) 打包，使用系统自带 WebView，每个平台仅约 3 MB，自包含单文件、解压即用、完全离线（Mermaid 图表除外）。

| 平台 | 下载 |
| --- | --- |
| Windows 10/11 x64 | [MarkEditor-1.0.3-windows-x64.zip](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-windows-x64.zip) |
| macOS Intel (x64) | [MarkEditor-1.0.3-macos-x64.tar.gz](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-macos-x64.tar.gz) |
| macOS Apple Silicon (M1+) | [MarkEditor-1.0.3-macos-arm64.tar.gz](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-macos-arm64.tar.gz) |
| macOS 通用 (Universal) | [MarkEditor-1.0.3-macos-universal.tar.gz](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-macos-universal.tar.gz) |
| Linux x64 | [MarkEditor-1.0.3-linux-x64.tar.gz](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-linux-x64.tar.gz) |
| Linux arm64 | [MarkEditor-1.0.3-linux-arm64.tar.gz](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-linux-arm64.tar.gz) |
| Linux armhf | [MarkEditor-1.0.3-linux-armhf.tar.gz](https://github.com/YCG1995/MarkEditor/releases/download/v1.0.3/MarkEditor-1.0.3-linux-armhf.tar.gz) |

更多版本见 [Releases](https://github.com/YCG1995/MarkEditor/releases)。

### 运行方式

- **Windows**：解压后双击 `MarkEditor.exe`。
- **macOS / Linux**：解压后在终端执行 `chmod +x MarkEditor && ./MarkEditor`。
- **macOS** 首次打开若提示"无法验证开发者"：到「系统设置 → 隐私与安全性」点击「仍要打开」。
- **Linux** 需系统带 WebKitGTK，例如 Ubuntu：`sudo apt install libwebkit2gtk-4.1-0`。

---

## 特性

### 所见即所得编辑
- 直接输入 Markdown 语法即时渲染
- `Ctrl + /` 一键切换源码 / 可视模式，光标位置精确映射
- 表格可视化编辑：浮动工具栏增删行列、切换对齐、导出 CSV
- 代码块语法高亮 + 行号 + 一键复制
- 引用块与 Callout 提示块（TIP / WARNING / INFO 等 9 种）

### 完整 Markdown 支持
标题 H1–H6（支持自动编号）、无序/有序/任务列表、链接、图片（拖拽/粘贴、相对路径、Base64）、脚注、分割线、目录 `[TOC]`、Front Matter。

### 数学与图表
- 内置轻量 TeX 渲染器，行内 `$E=mc^2$` 与块级 `$$...$$`，**无需联网**
- Mermaid 流程图、时序图、甘特图等，联网自动加载、离线优雅降级

### 工作区与导出
- 打开文件夹作为工作区，左侧文件树浏览，右键重命名/复制/删除
- 最近文件 / 最近工作区快速恢复，`Ctrl+P` 快速打开，`Ctrl+Shift+F` 全局搜索
- 导出 Word（.doc，带样式）、静态 HTML、可编辑 HTML、打印 / 另存 PDF

### 编辑体验
- 5 套主题（GitHub Light / GitHub Dark / Night / Newsprint / Pixyll）
- 专注模式（F8）、打字机模式（F9）、全屏（F11）
- 可折叠大纲面板，窄屏默认折叠
- 查找替换（支持正则、区分大小写）、命令面板（72+ 命令）
- 缩放 70%–160%、页面宽度可调、拼写检查、自动草稿保存

---

## 常用快捷键

| 功能 | 快捷键 | 功能 | 快捷键 |
| --- | --- | --- | --- |
| 加粗 | `Ctrl+B` | 斜体 | `Ctrl+I` |
| 下划线 | `Ctrl+U` | 高亮 | `Ctrl+E` |
| 行内代码 | `Ctrl+Shift+\`` | 链接 | `Ctrl+K` |
| 插入图片 | `Ctrl+Shift+I` | 清除格式 | `Ctrl+\` |
| 一级标题 | `Ctrl+1` | 正文段落 | `Ctrl+0` |
| 无序列表 | `Ctrl+Shift+]` | 有序列表 | `Ctrl+Shift+[` |
| 代码块 | `Ctrl+Shift+K` | 公式块 | `Ctrl+Shift+M` |
| 引用 | `Ctrl+Shift+Q` | 增加缩进 | `Ctrl+]` |
| 查找 | `Ctrl+F` | 替换 | `Ctrl+H` |
| 命令面板 | `Ctrl+Shift+P` | 快速打开 | `Ctrl+P` |
| 工作区搜索 | `Ctrl+Shift+F` | 切换侧边栏 | `Ctrl+Shift+L` |
| 源码模式 | `Ctrl+/` | 专注模式 | `F8` |
| 打字机模式 | `F9` | 全屏 | `F11` |
| 保存 | `Ctrl+S` | 另存为 | `Ctrl+Shift+S` |
| 偏好设置 | `Ctrl+,` | 撤销 / 重做 | `Ctrl+Z` / `Ctrl+Y` |

> macOS 用户：`Ctrl` = `⌘`，`Alt` = `⌥`，`Shift` = `⇧`。

---

## 浏览器兼容性

| 浏览器 | 状态 | 说明 |
| --- | --- | --- |
| Chrome 86+ | ✅ 完全支持 | 推荐 |
| Edge 86+ | ✅ 完全支持 | 推荐 |
| Firefox 111+ | ⚠️ 部分支持 | 工作区（File System Access API）不可用，其余正常 |
| Safari 15.2+ | ⚠️ 部分支持 | 同上 |

> 工作区功能（打开文件夹、直接读写文件）需要 Chrome / Edge 86+。其他浏览器可使用「打开文件」和下载保存。

---

## 技术实现

- 纯原生 HTML / CSS / JavaScript，零框架、零依赖
- ContentEditable + 自定义 Markdown 引擎，实现真正的所见即所得
- File System Access API 实现本地文件直读直写
- IndexedDB 存储最近文件 / 工作区句柄，localStorage 保存草稿与设置
- 内置轻量 TeX 渲染器，数学公式无需联网
- Mermaid 通过 CDN 按需加载，离线优雅降级
- 桌面端基于 Neutralinojs 打包，自包含单文件

---

## 许可证

MIT License — 自由使用、修改、分发。

---

**开始写作吧。** 🎉
