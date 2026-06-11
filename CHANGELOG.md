# KMind Zen SiYuan Changelog

## 0.17.1 - 2026-06-11

### English

- Fix an issue where editing a block map did not refresh the document preview after external image organizers moved the block map preview image into an `assets` subfolder.

### 中文

- 修复使用外部图片整理工具将块导图预览图移动到 `assets` 子目录后，编辑块导图但正文预览不刷新的问题。

## 0.17.0 - 2026-06-03

### English

- Improve the Dock maps panel so it feels closer to a native SiYuan dock, including a real panel minimize button.
- Replace Dock text actions with accessible SiYuan icon buttons for new, refresh, copy link, rename, and delete.
- Keep row actions compact on desktop with hover and keyboard-focus reveal, while keeping them always visible on mobile and coarse-pointer devices.
- Let the Dock panel inherit SiYuan's own background for better theme compatibility.

### 中文

- 优化 Dock 导图面板，使其更接近思源原生 Dock 体验，并补齐真正收起面板的缩小按钮。
- 将 Dock 顶部和行内文字操作改为可访问的思源 icon button，覆盖新建、刷新、复制链接、重命名和删除。
- 桌面端行内操作在 hover / 键盘 focus 时显示，移动端和粗指针设备常显。
- Dock 面板背景继承思源宿主背景，适配各种主题。

## 0.16.0 - 2026-06-03

### English

- Add map template support for faster repeatable mind map creation.
- Add theme and template preselection when creating document-tree mind maps.
- Add global defaults for map creation and one-click conversion workflows, so they can start from your preferred default map/template.
- Add in-map interactive guidance from the bottom-right help button: `?` -> `Interactive guide`.
- Save reusable templates from the first button in the left floating toolbar: `Save template`.

### 中文

- 新增导图模板功能，便于复用固定结构快速创建导图。
- 新增创建文档树导图的时候预选主题 & 模板的功能。
- 新增全局配置，可配置创建导图、一键转换导图等流程使用的默认导图 / 模板。
- 新增导图内引导交互，入口：导图内部右下角悬浮工具栏的问号按钮 -> 交互式引导。
- 模板保存入口：导图内部左侧悬浮工具栏第一个按钮 -> 保存模板。

## 0.15.0 - 2026-05-21

### English

- Add a canvas drag habit setting with Pan-first and Select-first modes.
- In Select-first mode, drag blank map space to marquee-select and hold Space while dragging to pan.
- Keep Space reserved for canvas navigation so custom shortcuts do not interfere with panning.

### 中文

- 新增画布拖拽习惯设置，可在平移优先和选择优先之间切换。
- 选择优先模式下，导图空白处左键拖拽框选，按 Space + 左键拖拽平移画布。
- Space 会保留给画布导航使用，避免自定义快捷键影响平移操作。

## 0.14.0 - 2026-05-21

### English

- Add automatic image compression for inserted images in the plugin, enabled by default.
- Add direct node-image resizing.
- Add drag-and-drop node-image positioning across top, bottom, left, and right slots.

### 中文

- 插件端新增插入图片自动压缩配置，默认开启。
- 节点图片新增直接拖动调整大小。
- 节点图片支持拖拽到上、下、左、右方位。

## 0.13.1 - 2026-05-20

### English

- Improve dark-mode editing for nodes and rich-text notes.
- Improve dark-mode adaptation for rich-text toolbar dropdowns, link/cloze/slash/formula popovers, and context-menu scrollbars.
- Improve dark-mode adaptation for relationship-line creation and format-painter cursor-following hints.

### 中文

- 优化 dark 模式下的节点编辑和富文本备注编辑体验。
- 优化富文本工具栏下拉、链接 / 挖空 / 斜杠 / 公式浮层和右键菜单滚动条的 dark 适配。
- 优化关联线添加和格式刷的鼠标跟随提示的 dark 适配

## 0.13.0 - 2026-05-18

### English

- Improve summary node localization and interaction details.
- Add bulk node dragging: after multi-selecting nodes, drag any selected node to move them together.
- Add automatic node centering when a map is first created.

### 中文

- 优化概要节点 i18n 和交互细节。
- 新增批量节点拖拽：多选节点后，按住任意已选中节点即可整体移动。
- 新增初次创建导图时，节点自动居中的功能。

## 0.12.0 - 2026-05-18

### English

- Improve relationship line editing and interactions, with new dashed and dotted line styles.
- Add relationship line color configuration for clearer cross-branch structure.
- Add project-level relationship line settings so maps can keep a consistent relationship style.
- Add relationship line support for summaries.

### 中文

- 优化关联线功能与交互，新增虚线 / 点线样式选择。
- 新增关联线颜色配置，让跨分支关系表达更清晰。
- 新增项目级别关联线配置，便于整张导图保持统一的关联线风格。
- 为概要新增关联线支持。

## 0.11.0 - 2026-05-17

### English

- Add polished PNG export with the currently available clean window frame style.
- Add PNG clarity options in the export dialog so exported images can balance size and sharpness.
- Improve the canvas and node "Copy as image" context menu with visual style previews for original and window-framed images.
- Improve context-menu submenu hover tolerance.

### 中文

- 普通 PNG 导出新增图片美化能力，当前开放简洁窗口外框风格。
- 导出弹窗新增 PNG 清晰度选择，可在文件体积和图片清晰度之间按需取舍。
- 画布和节点右键“复制为图片”升级为带预览的样式选择，支持原图和窗口外框图片。
- 优化右键菜单二级菜单的悬停宽限。

## 0.10.0 - 2026-05-15

### English

- Design and save local KMind Zen themes directly inside the SiYuan plugin.
- Import and export `.kmind-theme.json` packages for offline theme sharing.
- Apply local themes from the map theme popover after saving or importing them.
- Use compact, default, and relaxed project density presets to adjust map spacing quickly.
- Upgrade the shared KMind core to 0.5.0, improve performance, fix theme spacing isolation, and improve core-layout vertical spacing stability.

### 中文

- 可以直接在思源插件中设计并保存本地 KMind Zen 主题。
- 支持导入 / 导出 `.kmind-theme.json` 离线主题分享包。
- 保存或导入本地主题后，可以从导图内主题 Popover 应用到当前项目。
- 项目设置新增紧凑、默认、舒展三档密度预设，用于快速调整导图间距。
- 更新内核至 0.5.0，优化性能，修复主题间距隔离问题，并优化内核布局的纵向间距稳定性。

## 0.9.0 - 2026-05-09

### English

- Add shortcut customization in the SiYuan plugin settings, with changes applying across KMind Zen tabs.
- Rework the SiYuan settings dialog into clearer sections so general options and shortcuts are easier to browse.
- Add a rich-text shortcut reference for node text, notes, and comments.
- Show the current shortcut next to supported context-menu actions, including custom bindings.
- Add more default shortcuts for notes, comments, zoom reset, submaps, and common copy/paste actions.

### 中文

- 新增思源插件全局快捷键配置，修改后会对 KMind Zen 导图标签页统一生效。
- 重构思源设置弹窗，将常规设置和快捷键设置分区展示，浏览更轻松。
- 快捷键面板新增富文本快捷键提示，覆盖节点正文、备注和批注编辑。
- 右键菜单会在对应操作旁显示当前真实快捷键，包括用户自定义后的快捷键。
- 补齐备注、批注、重置缩放、子导图和常用复制粘贴操作的默认快捷键。

## 0.8.0 - 2026-05-08

### English

- Add SiYuan PDF annotation links: copy a PDF annotation in SiYuan, paste it onto a KMind Zen node, and click the PDF icon to jump back to that annotation.
- Support both text annotations and rectangle annotations copied from SiYuan's PDF reader.
- When no node is selected, pasting a PDF annotation now creates a new node with the PDF link.
- Keep legacy KMind PDF annotation links openable in KMind Zen.
- PDF annotation links are not treated as SiYuan block previews, avoiding incorrect hover previews.

### 中文

- 新增思源 PDF 标注链接：在思源 PDF 阅读器复制标注后，可直接粘贴到 KMind Zen 节点，并通过 PDF 图标跳回对应标注。
- 支持思源 PDF 的文字标注和矩形标注复制格式。
- 未选中节点时，粘贴 PDF 标注会自动创建一个带 PDF 链接的新节点。
- 兼容旧 KMind 的 PDF 标注链接，迁移后的导图仍可打开对应标注。
- PDF 标注链接不会被当作思源块预览处理，避免悬浮时出现错误预览。

## 0.7.0 - 2026-05-08

### English

- Add SiYuan mirror blocks: copy a whole map or a selected node from KMind Zen, paste it into normal SiYuan content, and render a read-only live map preview.
- Add SiYuan block maps: insert a KMind Zen map from the slash menu, show it as a native image in the note, and open it from the image action button for editing.
- Block maps export as normal images while still carrying a recoverable KMind Zen map package.
- Refresh mirror blocks after the source map is saved, including documents that contain multiple mirror blocks from the same map.
- Upgrade the shared KMind core to 0.4.0 with a smoother experience for large maps, outline mode, and split mode.

### 中文

- 新增思源镜像块：可以从 KMind Zen 源导图复制整图或选中节点，粘贴到普通思源正文后以只读导图预览呈现。
- 新增思源块导图：可以从斜杠菜单在正文插入 KMind Zen 导图，正文中表现为思源原生图片块，点击图片右上角编辑按钮即可快速编辑。
- 块导图导出思源文档时仍是普通图片，同时图片自身也携带可恢复的 KMind Zen 导图包。
- 源导图保存后镜像块自动刷新；同一文档内放置多个镜像块时，也会同步显示最新内容。
- 将共享 KMind 内核升级到 0.4.0，大图、导图、大纲和分屏体验更顺滑。

## 0.6.0 - 2026-05-03

### English

- Add SiYuan MOC document-tree maps, including document-level MOC mode and notebook-level MOC tabs.
- Support organizing MOC nodes as SiYuan documents: create child documents, rename titles, reorder or move documents, and delete documents after confirmation.
- Show MOC nodes with SiYuan document-tree style icons and document preview links, and keep the SiYuan file tree refreshed after MOC writebacks.
- Add MOC capsule actions for refresh and copying the current MOC map as PNG, with clearer messages for client bitmap limits.
- Make SiYuan doc-to-map and MOC part of the Pro feature set, while keeping Dock maps free.
- Fix MOC menu icon rendering and alignment in SiYuan document and notebook context menus.

### 中文

- 新增思源 MOC 文档树导图，支持文档级 MOC 模式和笔记本级 MOC 标签页。
- 支持在 MOC 中以导图方式整理思源文档：新建子文档、重命名标题、调整顺序或层级，以及二次确认后删除文档。
- MOC 节点改为展示接近思源文档树的图标和文档预览链接，并在写回后刷新思源文件树。
- MOC 胶囊支持刷新和复制当前 MOC 导图为 PNG，并对客户端位图限制给出更准确提示。
- 将思源文档一键转导图和 MOC 纳入 Pro 功能范围，Dock 导图仍保持免费。
- 修复思源文档和笔记本右键菜单中的 MOC 图标渲染与对齐问题。

## 0.5.0 - 2026-05-03

### English

- Redesign the Project Popover with visual layout cards, light/dark theme previews, rainbow edge settings, and background color presets plus custom color input.
- Redesign the root-node theme switching popover with visual layout, theme, and edge route previews, making layout and line style changes easier to compare before applying.
- Localize layout, theme, and edge route display names across the SiYuan plugin UI.
- Upgrade the shared KMind core to 0.3.0 so preview cards and real maps stay aligned on official edge routing behavior.

### 中文

- 重构 Project Popover，改为可视化布局卡片、明暗主题预览、彩虹连线设置、背景色预设和自定义颜色输入。
- 重构根节点“切换主题”Popover，用可视化卡片展示布局、主题和连线路由，方便用户在应用前比较效果。
- 为思源插件界面补齐布局、主题和连线路由的本地化展示名。
- 将共享 KMind 内核升级到 0.3.0，让预览卡片与真实导图在官方连线路由表现上保持一致。

## 0.4.1 - 2026-05-02

### English

- Fix node context menu behavior after multi-selecting nodes: right-clicking an already selected node now keeps the full multi-selection highlighted.
- Make node context menu actions use the node that was right-clicked as their explicit target, including copy, todo, submap, expand, collapse, and SiYuan protocol link actions.
- Keep delete behavior aligned with multi-selection, so deleting from the node context menu still deletes the selected node group.

### 中文

- 修复多选节点后的右键菜单行为：右键某个已选节点时，其它已选节点会继续保持选中态。
- 节点右键菜单现在会以被右键的节点作为明确目标，覆盖复制、待办、子导图、展开、折叠和思源协议链接等操作。
- 保持删除行为与多选语义一致，从节点右键菜单删除时仍会删除当前选中的节点组。

## 0.4.0 - 2026-05-02

### English

- Add one-click SiYuan document map view with full block tree preview and heading outline modes.
- Support creating an editable KMind Zen child document from the current document map view.
- Add the document map capsule controls for mode switching, refresh, return to editor, create map, copy as PNG, and long-running progress feedback.
- Improve full block tree conversion fidelity for rich inline content, lists, images, formulas, tables, blockquotes, callouts, super blocks, and safe fallback cards for complex blocks.
- Allow heading outline nodes to open editable SiYuan Protyle popovers and reorder headings through SiYuan's outline move API.
- Clarify read-only preview boundaries and report oversized PNG copy failures as client bitmap limits instead of clipboard permission errors.

### 中文

- 新增思源文档一键导图视图，支持完整块树预览和标题大纲两种模式。
- 支持将当前文档导图视图创建为可编辑的 KMind Zen 子文档导图。
- 新增文档导图右上角胶囊操作区，支持模式切换、刷新、返回编辑、创建导图、复制 PNG 和耗时进度提示。
- 提升完整块树转换保真度，覆盖行级富文本、列表、图片、公式、表格、引述块、提示块、超级块，以及复杂块的安全回退卡片。
- 标题大纲模式支持打开可编辑的思源 Protyle 浮窗，并通过思源大纲移动 API 写回标题顺序或层级。
- 明确模式一只读预览边界；复制 PNG 过大时提示客户端位图限制，而不是泛化为剪贴板权限问题。

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
