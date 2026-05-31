<div align="center">

<img src="https://github.com/obsidianmd/obsidian-api/raw/master/icon.svg" width="120" />

# Obsidian Translations

[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Obsidian Version](https://img.shields.io/badge/Obsidian-v1.0%2B-purple?style=flat-square&logo=obsidian)](https://obsidian.md)
[![Contributors](https://img.shields.io/github/contributors/your-username/obsidian-translations?style=flat-square)](https://github.com/your-username/obsidian-translations/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/your-username/obsidian-translations?style=flat-square)](https://github.com/your-username/obsidian-translations/commits/main)
[![English](https://img.shields.io/badge/README-English-blue?style=flat-square)](README.md)

多语言翻译资源仓库，为 Obsidian 笔记应用提供插件、主题等核心模块的本地化配置

[English](README.md) · [中文](#-关于)

</div>

## 📖 关于

Obsidian Translations 是为 Obsidian 笔记应用提供多语言翻译资源的仓库，涵盖插件、主题等核心模块的本地化配置，助力全球用户获得流畅的中文及多语言使用体验。

## 📁 仓库结构

```
obsidian-translations/
├── LICENSE               # 开源协议文件
├── README.md             # 英文文档
├── README.zh-CN.md       # 中文文档
├── metadata.json         # 翻译仓库元数据配置
├── themes/               # Obsidian 主题翻译文件目录
│   ├── Y7QeXvC9n2dTxgTW9oYH_02bEAZ1U5_t.json
│   ├── _qZejxIGV1Lo7WY936Vedr-OIyxtZ7Bm.json
│   └── ...（更多主题翻译文件）
└── plugins/              # Obsidian 插件翻译文件目录
    ├── 4WdEgqsmUoQ7weUcqLZVWZN-UB9l9K0J.json
    ├── CXgRmgaK7CsDdCa7byISwLCwppDp_c-b.json
    └── ...（更多插件翻译文件）
```

### 目录说明

| 目录 | 说明 |
|------|------|
| `themes/` | 存放 Obsidian 各类主题的多语言翻译配置，每个 JSON 文件对应一个主题的翻译资源。 |
| `plugins/` | 存放 Obsidian 社区插件/官方插件的多语言翻译配置，覆盖功能描述、界面文本等核心内容。 |
| `metadata.json` | 管理翻译仓库的基础元数据（如翻译版本、支持语言、更新日志等）。 |

## 🛠 技术规范

### 语言规范

- **核心翻译语言**：简体中文（zh-CN），同时兼容繁体中文（zh-TW）、英文（en-US）等多语言适配。
- **翻译文件格式**：采用 JSON 键值对格式，遵循 Obsidian 官方本地化规范，示例如下：

```json
{
  "plugin.name": "插件名称",
  "plugin.description": "插件功能描述",
  "setting.enable": "启用功能"
}
```

### 编码规范

- 所有文件采用 UTF-8 编码，确保多语言字符正常显示。
- JSON 文件严格遵循 JSON 语法规范，键名使用驼峰式/短横线命名，与 Obsidian 源码保持一致。

## 📊 翻译统计

| 类型 | 数量 |
|------|------|
| 插件 | 13 |
| 主题 | 3 |
| 总计 | 16 |

## 📜 开源协议

本仓库所有代码和翻译资源基于 **MIT License** 开源（详见 [LICENSE](LICENSE) 文件），您可以：

- 自由使用、复制、修改、合并、发布、分发本仓库资源；
- 用于商业/非商业场景；
- 需保留原始版权声明和许可声明。

## 🤝 贡献指南

1. Fork 本仓库至个人账号；
2. 基于 `main` 分支创建功能分支（如 `feat/translate-plugin-xxx`）；
3. 遵循翻译规范完成对应模块的翻译/更新；
4. 提交 PR，注明翻译的模块、语言及修改内容；
5. 等待审核合并，我们会在 1-3 个工作日内反馈。

## 👥 维护者

- 仓库维护团队：Obsidian 中文社区贡献者
- 反馈渠道：提交 Issue 或 Discussions，优先处理翻译错误、新增模块翻译需求。

## ✅ 兼容性

- 适配 Obsidian v1.0+ 版本的本地化规范；
- 翻译文件与 Obsidian 官方插件/主流社区插件版本同步更新。

---

<div align="center">

<sub>由 Obsidian 中文社区用 ❤️ 构建</sub>

</div>
