# Codex Design

一个本地优先的 AI 原生设计工作台：在可编辑画布中整理设计意图、管理设计系统、检查视觉效果，并运行交互原型。

> 早期预览版。Codex Design 是独立项目，并非 OpenAI 官方产品。本仓库用于发布安装包和说明文档，不包含应用源码。

## 下载

当前提供 **Windows x64** 安装包：[前往 v0.1.0 Release](https://github.com/Zhouenze130923/codex-design/releases/tag/v0.1.0)。macOS 和 Linux 安装包尚未提供。

下载 Release 中的安装程序并运行。安装包目前没有代码签名，Windows 可能显示未知发布者提示；请仅从本仓库的 Release 页面下载，并核对 Release 中公布的 SHA-256。

## 开始使用

1. 安装并启动 Codex Design。
2. 创建画布元素，使用属性面板、设计意图和设计系统调整设计。
3. 若要使用 AI 设计提案或 AI 辅助的截图分析，先按照 [Codex CLI 官方文档](https://learn.chatgpt.com/docs/codex/cli) 安装 Codex CLI，在终端运行 `codex` 完成登录，并确保 `codex` 命令位于系统 `PATH` 中。安装或登录后请重新启动 Codex Design。
4. 在应用内审阅 AI 提案；只有确认后才会应用到画布。

画布编辑、设计系统和原型预览可在不连接 Codex 的情况下使用。项目数据保存在本机；使用 AI 功能时，相关请求会经由本机 Codex CLI 发送。

## 当前功能

- 可编辑画布、页面、撤销/重做和本地自动保存
- 设计意图、视觉语言预设、颜色与排版等设计令牌、组件及设计检查
- Codex 辅助设计提案，先预览再应用
- 多视口截图检查、视觉差异与有限轮次修复
- 交互、变量和动画的原型预览

这是预览版本，功能和文件格式仍可能变化。遇到问题可在本仓库提交 Issue，请勿附上登录凭据或私人项目数据。

---

**English:** Codex Design is an independent, local-first AI-native design workspace. This public repository contains downloads and documentation, not application source code. The current preview release supports Windows x64 and requires an installed, signed-in Codex CLI for AI features.
