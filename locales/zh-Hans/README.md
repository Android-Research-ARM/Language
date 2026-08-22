<div align="center">
### 🌐 Languages / Langues / Idiomas / 语言 / لغات
[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • [🇧🇷 Português (Brasil)](../pt-BR/README.md) • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • **[🇨🇳 简体中文](../zh-Hans/README.md)**  

</div>

---
# 帮助翻译 ARAS

ARAS 由我们社区的成员共同翻译。如果您掌握其他语言，可以帮助我们让菜单、按钮和提示信息更加符合母语使用习惯，让更多人轻松使用。

您无需任何编程经验，无需安装特定软件，也无需访问 ARAS 源代码。所有操作都可以直接在 GitHub 的网页浏览器中完成。

## 参与方式

- 添加尚未列出的新语言
- 补全仍显示为英文的文本
- 修正拼写或语法错误
- 优化翻译，使表达更自然流畅
- 提升菜单与提示信息之间的用词一致性
- 审查其他贡献者提交的翻译

无论改进大小我们都非常欢迎。您不必一次性翻译整个语言文件。

## 编辑现有语言

1. 在 `.json` 文件列表中找到您的语言。例如简体中文是 `zh-Hans.json`，法语是 `fr.json`。
2. 打开文件并点击右上角的铅笔图标（**Edit this file**）。
3. 仅修改每对键值对右侧的翻译文本。
4. 点击 **Preview changes** 预览并核对您的修改。
5. 点击 **Propose changes** 并创建拉取请求（Pull Request）。

```json
"Cancel": "取消"
```

左侧的 `Cancel` 是英文原文。右侧的 `取消` 是中文翻译。请仅修改右侧内容。

## 申请添加新语言

提交一个 Issue 并告知我们：

- 语言名称
- 国家或地区（若用语存在地域差异）
- 用该语言书写的本族语名称
- 您是否可以参与翻译或校对

项目维护者会为您准备好语言文件模板，随后您可直接在 GitHub 页面上进行翻译。

## 重要翻译提示

- 保持 `ARAS` 不变，这是产品名称。
- 通常保持 Android、macOS、Mac、ProMotion 和 Adreno 等专有名词不变。
- 保持技术缩写不变：ADB、QEMU、QCOW2、DPI、FPS、GiB。
- 符合母语表达习惯，避免生硬死板的字面直译。
- 菜单和按钮文本应保持简明扼要。
- 对于“设备”、“设置”、“存储空间”、“更新”等核心词汇保持全文一致。
- 涉及删除或重置数据的警告提示必须明确、严谨。
- 不确定的词条可暂时保留英文，并在 Pull Request 中寻求帮助。
- 机器翻译可作为初稿参考，但必须由人工核对校准。
- 严禁添加任何广告、外链、个人信息或无关内容。

部分文本包含格式化占位符，如 `%@`、`%ld`、`%s`、`%.1f` 或 `\n`。请原样保留，切勿修改或删除。 ARAS 会在运行时将其动态替换为具体的名称、数字或换行符。

更多写作规范请参阅 [翻译风格指南](STYLE_GUIDE.md)。

## 语言文件命名规则

文件名中的字母标识语言代码：

- `de.json` — 德语
- `pt-BR.json` — 巴西葡萄牙语
- `zh-Hans.json` — 简体中文

如不确定该选择哪个文件，可在 Issue 中咨询。

## 审核与校对

翻译 Pull Request 将由维护者及社区母语校对员进行审核，可能会就用词、语调、一致性或界面空间限制提出优化建议。

所有交流均须遵守我们的 [社区行为准则](CODE_OF_CONDUCT.md)。

## [CONTRIBUTING.md](CONTRIBUTING.md)

## 社区文档

- `README.md` — 帮助与翻译入门
- `CONTRIBUTING.md` — 贡献指南与提交流程
- `CODE_OF_CONDUCT.md` — 社区行为准则
- `STYLE_GUIDE.md` — 翻译风格与术语规范
- `REVIEW_CHECKLIST.md` — 审核员检查清单
- `../../zh-Hans.json` — ARAS 简体中文语言包

## 开源协议

本仓库中的翻译文件与文档均基于 [MIT 协议](../../LICENSE) 开源。提交贡献即代表您同意在此协议下共享您的翻译。

ARAS 及其徽标为各自所有者的财产。本翻译许可不授予 ARAS 品牌商标使用权。
