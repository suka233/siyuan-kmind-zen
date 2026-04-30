# KMind Zen SiYuan Changelog

## 0.3.3 - 2026-04-30

### English

- Fix the notes rich text toolbar layering and click behavior in SiYuan.

### 中文

- 修复思源端备注富文本工具栏被遮挡、点击后动作不生效的问题。

## 0.3.2 - 2026-04-30

### English

- Improve SiYuan entry stability after long-running sessions, plugin data sync, and development reloads.
- Fix cases where the KMind Zen dock entry may not appear after the 0.3.1 stability update.

### 中文

- 提升思源长时间运行、同步插件数据或开发重载后的入口稳定性。
- 修复 0.3.1 稳定性更新后，部分情况下 KMind Zen Dock 入口可能不显示的问题。

## 0.3.1 - 2026-04-30

### English

- Fix duplicated KMind Zen topbar and dock icons after SiYuan stays open for a long time, syncs plugin data, or reloads the plugin during development.

### 中文

- 修复思源长时间运行、同步插件数据或开发重载后，顶部栏和 Dock 栏重复出现 KMind Zen 图标的问题。

## 0.3.0 - 2026-04-29

### English

- Add XMind file import support through the shared KMind import flow.
- Support modern `.xmind` files with `content.json`, including topic trees, free topics, multi-sheet projects, notes, labels, hyperlinks, images, relationships, and summaries.
- Report unsupported XMind features before import, and fail clearly for legacy XML, encrypted files, or unsupported zip compression.

### 中文

- 通过共享 KMind 导入流程新增 XMind 文件导入支持。
- 支持现代 `.xmind` 文件中的 `content.json`，包括主题树、自由主题、多画布项目、备注、标签、超链接、图片、关联线和概要。
- 导入前提示暂不支持的 XMind 特性；旧版 XML、加密文件或不支持的 zip 压缩方式会明确失败。

## 0.2.0 - 2026-04-29

### English

- Upgrade the shared KMind core to 0.2.0.
- Fix chemical equation rendering in extreme cases, including mhchem labels that contain CJK text.
- Refresh the SiYuan dock icon with a cleaner host-colored `currentColor` glyph, so it fits better with SiYuan light and dark themes.

### 中文

- 将共享 KMind 内核升级到 0.2.0。
- 修复极端情况下的化学方程式渲染问题，包括 mhchem 条件标签中包含中文时的显示异常。
- 更新思源 Dock 栏图标视觉效果，改为更清爽的 `currentColor` 单色字形，以更好适配思源浅色和深色主题。

## 0.1.0 - 2026-04-04

- Initial public release of KMind Zen for SiYuan.
- Rebuilt the KMind experience from the ground up with a new core, new UI, and a more extensible interaction model.
- Added direct SiYuan integration, including creating mind maps from the document tree, opening maps from the dock, and dragging SiYuan documents or blocks into maps as special cards.
- Introduced the KMind Zen source format with portable `.kmindz.svg` files that remain editable while still being previewable as SVG images.
- Added advanced mapping features such as unlimited summary nesting, cloze nodes and notes, bidirectional links, node comments, multiple hyperlinks per node, rich text editing, multi-root maps, tags, notes, images, TODOs, and relationship lines.
- Improved editing ergonomics with smarter drag-and-drop, a faster formula workflow from the slash menu, enhanced global search, automatic light and dark theme support, and a more polished Zen/read-only mode.
- Enabled permanent SiYuan deep links for both whole maps and individual nodes, making it easier to reference and reopen specific ideas from outside SiYuan.
