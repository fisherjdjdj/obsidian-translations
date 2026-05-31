<div align="center">

<img src="https://obsidian.md/download" width="120" />

# Obsidian Translations

[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Obsidian Version](https://img.shields.io/badge/Obsidian-v1.0%2B-purple?style=flat-square&logo=obsidian)](https://obsidian.md)
[![Contributors](https://img.shields.io/github/contributors/your-username/obsidian-translations?style=flat-square)](https://github.com/your-username/obsidian-translations/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/your-username/obsidian-translations?style=flat-square)](https://github.com/your-username/obsidian-translations/commits/main)
[![Chinese](https://img.shields.io/badge/README-%E4%B8%AD%E6%96%87-red?style=flat-square)](README.zh-CN.md)

多语言翻译资源仓库，为 Obsidian 笔记应用提供插件、主题等核心模块的本地化配置

[English](#-about) · [中文](README.zh-CN.md)

</div>

## 📖 About

Obsidian Translations is a repository that provides multi-language translation resources for Obsidian note-taking application, covering localization configurations for core modules like plugins and themes, helping global users get a fluent multilingual experience.

## 📁 Repository Structure

```
obsidian-translations/
├── LICENSE               # MIT License
├── README.md             # English Documentation
├── README.zh-CN.md       # 中文文档
├── metadata.json         # Translation repository metadata
├── themes/               # Obsidian theme translation files
│   ├── Y7QeXvC9n2dTxgTW9oYH_02bEAZ1U5_t.json
│   ├── _qZejxIGV1Lo7WY936Vedr-OIyxtZ7Bm.json
│   └── ... (more theme files)
└── plugins/              # Obsidian plugin translation files
    ├── 4WdEgqsmUoQ7weUcqLZVWZN-UB9l9K0J.json
    ├── CXgRmgaK7CsDdCa7byISwLCwppDp_c-b.json
    └── ... (more plugin files)
```

### Directory Description

| Directory | Description |
|-----------|-------------|
| `themes/` | Multilingual translation configurations for various Obsidian themes. Each JSON file corresponds to a theme's translation resources. |
| `plugins/` | Multilingual translation configurations for Obsidian community plugins/official plugins, covering core content like feature descriptions and interface text. |
| `metadata.json` | Manages the translation repository's basic metadata (such as translation version, supported languages, changelog, etc.). |

## 🛠 Technical Specifications

### Language Specifications

- **Core translation language**: Simplified Chinese (zh-CN), compatible with Traditional Chinese (zh-TW), English (en-US), and other languages.
- **Translation file format**: Uses JSON key-value pair format, following Obsidian official localization specifications:

```json
{
  "plugin.name": "Plugin Name",
  "plugin.description": "Plugin function description",
  "setting.enable": "Enable feature"
}
```

### Coding Specifications

- All files use UTF-8 encoding to ensure proper display of multilingual characters.
- JSON files strictly follow JSON syntax specifications, with key names using camelCase/kebab-case naming consistent with Obsidian source code.

## 📊 Translation Statistics

| Type | Count |
|------|-------|
| Plugins | 13 |
| Themes | 3 |
| Total | 16 |

## 📜 License

All code and translation resources in this repository are open source under the **MIT License** (see [LICENSE](LICENSE) file for details). You may:

- Freely use, copy, modify, merge, publish, distribute the resources in this repository;
- Use for commercial/non-commercial scenarios;
- Must retain the original copyright notice and license notice.

## 🤝 Contributing

1. Fork this repository to your personal account;
2. Create a feature branch based on the `main` branch (e.g., `feat/translate-plugin-xxx`);
3. Follow the translation specifications to complete the translation/update of the corresponding module;
4. Submit a PR, noting the translated module, language, and changes;
5. Wait for review and merge, we will feedback within 1-3 working days.

## 👥 Maintainers

- Repository maintenance team: Obsidian Chinese Community Contributors
- Feedback channel: Submit Issues or Discussions, priority given to translation errors and new module translation requests.

## ✅ Compatibility

- Compatible with Obsidian v1.0+ localization specifications;
- Translation files are updated synchronously with Obsidian official plugins/mainstream community plugin versions.

---

<div align="center">

<sub>Built with ❤️ by Obsidian Chinese Community</sub>

</div>
