<div align="center">

# 🔮 Awesome AI Reverse Engineering

**AI 驱动的逆向工程工具集**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Last Updated](https://img.shields.io/badge/last%20updated-2026--04-orange.svg)

*当 LLM 遇上逆向工程，一切开始变得不一样。*

</div>

---

## 📖 Overview

> 一份精心整理的 **AI + 逆向工程** 工具清单，涵盖 MCP（Model Context Protocol）服务器、Cursor/Claude Skills、IDE 插件等，助你用 AI 大模型高效完成 JS 逆向、二进制分析、Android 安全研究与流量抓包。

**为什么需要这份清单？**

- 🤖 LLM 正在重塑逆向工程的工作流，但工具散落各处
- 🔗 MCP 协议让 AI 助手直接操控 IDA Pro、Ghidra、Frida 等专业工具
- 🚀 一站式发现最前沿的 AI 逆向工程生态

---

## 📑 Table of Contents

- [JS 逆向工程](#-js-逆向工程)
- [二进制 / 原生逆向](#-二进制--原生逆向)
- [Android 安全分析](#-android-安全分析)
- [浏览器自动化 / 流量分析](#-浏览器自动化--流量分析)

---

## 🌐 JS 逆向工程

> JavaScript 运行时 Hook、混淆还原、协议分析、自动化逆向

| 项目 | 简介 |
|------|------|
| [jshookmcp](https://github.com/vmoranv/jshookmcp) | 面向 AI 辅助 JS 安全分析的 MCP 服务器，集成浏览器自动化、CDP 调试、网络监控、JS Hook、WASM 工具链、Source Map 重建、AST 变换等能力于一体。 |
| [JS Reverse MCP](https://github.com/zhizhuodemao/js-reverse-mcp) | JS 逆向 MCP 服务器，让 Claude/Cursor/Copilot 等 AI 编码助手直接调试和分析网页 JavaScript 代码。 |
| [Camoufox Skill](https://github.com/WhiteNightShadow/hello_js_reverse_skill) | 面向逆向分析与爬虫对抗的 Skill，基于 Camoufox 反检测浏览器实现网络捕获、源码定位、Hook 调试与算法还原的完整工作流。 |
| [js-reverse-automation--skill](https://github.com/Fausto-404/js-reverse-automation--skill) | 结合 chrome-devtools-mcp 与 Skill 规范，实现 JSRPC + Flask + autoDecoder 的前端 JS 逆向自动化方案。 |
| [JSHook Reverse Tool](https://github.com/wuji66dde/jshook-skill) | AI 驱动的 JavaScript 逆向工程工具。 |
| [reverse-skill](https://github.com/715494637/reverse-skill/) | Web JS 逆向 Skill 仓库，覆盖请求链定位、运行时诊断、AST 混淆恢复、JSVMP、Worker、WASM、Webpack 与协议语义分析。 |
| [xbsReverseSkill](https://github.com/lwjjike/xbsReverseSkill) | Web/JS 逆向分析 Skill 仓库，包含 AST 反混淆、纯算/协议逆向、浏览器补环境三大能力模块。 |
| [ruishu-mcp](https://github.com/xuange520/ruishu-mcp) | 专为 AI Agent 打造的瑞数防爬流量净化 MCP 工具 / An MCP Tool for AI Agents to Stealthily Bypass and Purify Ruishu WAF Traffic |

## 🔬 二进制 / 原生逆向

> IDA Pro、Ghidra、Binary Ninja 等专业工具的 AI 集成

| 项目 | 简介 |
|------|------|
| [IDA-NO-MCP](https://github.com/P4nda0s/IDA-NO-MCP) | 告别 IDA MCP 复杂、冗长、卡顿的交互模式。AI 逆向，无需额外配置。 |
| [IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp) | 简洁的 MCP 服务器，在 IDA Pro 中实现 AI vibe reversing。 |
| [ida-mcp-rs](https://github.com/blacktop/ida-mcp-rs) | 用于 AI 逆向工程的无头 IDA Pro MCP 服务器（Rust 实现）。 |
| [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | 让 LLM 自主对应用程序进行逆向工程的 MCP 服务器，将 Ghidra 核心功能暴露给 MCP 客户端。 |
| [Binary Ninja MCP](https://github.com/fosdickio/binary_ninja_mcp) | Binary Ninja 插件 + MCP 服务器 + 桥接器，将 Binary Ninja 功能与 LLM 客户端无缝集成。 |
| [revula](https://github.com/president-xd/revula) | 面向通用逆向工程自动化的生产级 MCP 服务器。 |

## 📱 Android 安全分析

> APK 反编译、动态插桩、设备管理与 API 提取

| 项目 | 简介 |
|------|------|
| [Android RE Skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) | 反编译 APK/XAPK/JAR/AAR 文件，自动提取 Retrofit 端点、OkHttp 调用、硬编码 URL 等 HTTP API。 |
| [JADX-AI-MCP](https://github.com/zinja-coder/jadx-ai-mcp) | 全自动 MCP 服务器 + JADX 插件，通过 LLM 分析 Android APK，发现漏洞与逆向工程。 |
| [Frida MCP Server](https://github.com/zhizhuodemao/frida-mcp) | MCP 服务器，让 AI 模型使用 Frida 进行 Android 动态分析。 |
| [Android Proxy MCP](https://github.com/zhizhuodemao/android_proxy_mcp) | 基于 MCP 的 Android 抓包服务，AI 助手帮你抓取和分析 HTTP/HTTPS 流量。 |
| [ADB MCP Server](https://github.com/zhizhuodemao/adb-mcp) | 面向 ADB 操作的 MCP 服务器，提供完整的 Android 设备管理功能。 |

## 🌍 浏览器自动化 / 流量分析

> 反检测浏览器、抓包代理与自动化控制

| 项目 | 简介 |
|------|------|
| [DrissionPage MCP](https://github.com/wxhzhwxhzh/DrissionPageMCP) | 基于 DrissionPage + FastMCP 的浏览器自动化 MCP 服务器，提供丰富的浏览器操作 API。 |
| [Camoufox MCP Server](https://github.com/whit3rabbit/camoufox-mcp) | 基于 Camoufox（隐私优先的 Firefox 分叉版）的浏览器自动化 MCP 服务器，具有先进的反检测功能。 |
| [Charles MCP Server](https://github.com/heizaheiza/Charles-mcp) | 将 Charles Proxy 接入 MCP 客户端，让 Agent 稳定读取实时流量、分析历史录包。 |
| [Anything Analyzer](https://github.com/Mouseww/anything-analyzer) | 操作一遍网站或应用，AI 就把协议逆向、加密分析、安全审计全干了。 |

---

