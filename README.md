# KMind Zen for SiYuan (Public Beta)

[中文说明](https://github.com/suka233/siyuan-kmind-zen/blob/main/README_zh_CN.md)

KMind Zen is a next-generation professional mind mapping tool that started in SiYuan and is now expanding into a broader ecosystem. Website: https://kmind.app

Unlike KMind2, KMind Zen was rebuilt from the ground up, with a redesigned core, interface, and interaction model for greater flexibility and room to grow. Today, KMind Zen is available as a SiYuan plugin, an Obsidian plugin, a web app, and an OpenClaw Skill. A standalone desktop app is also on the way.

## What's new in 0.4.1 (2026-05-02)

- Fixed node context menu behavior after multi-selecting nodes. Right-clicking an already selected node now keeps the full multi-selection highlighted.
- Node context menu actions now use the node that was right-clicked as their explicit target, including copy, todo, submap, expand, collapse, and SiYuan protocol link actions.
- Delete from the node context menu still follows the existing multi-selection delete behavior.

## Features

- Every KMind Zen host runs on the same core. A single KMind Zen source file can move smoothly between SiYuan, Obsidian, the web app, and the upcoming desktop app. You can also use the KMind Zen Skill with AI tools to turn source material into editable mind maps offline. One practical workflow is converting lecture or meeting recordings into KMind Zen documents that you can refine and archive later.
- A purpose-built `.kmindz.svg` source format. It contains the full editable source document while still being a valid SVG image, so you can preview the map without opening it first.
- Smart themes with both light and dark variants across the official theme set, switching automatically with no manual theme toggle required.
- Unlimited summary nesting, so summaries can contain their own summaries at any depth.
- Flexible cloze support for both nodes and notes, designed for memorization and review.
- An improved formula editor that can be opened quickly from the slash menu.
- Enhanced global search that goes beyond node text and also covers notes, comments, and more.
- Bidirectional links between nodes.
- Node comments that are distinct from notes and can be reviewed in chronological order, making it easier to revisit the thinking process behind a map.
- Refined drag-and-drop interactions for a smoother editing experience.
- Improved hyperlink support, including multiple links per node and custom icons for each link.
- A more polished Zen mode and read-only experience, with the current state clearly visible and easy to exit from the top-right corner.
- A mobile experience optimized as much as possible, with a dedicated UI for mobile devices. More feedback is still needed to keep improving it.
- Core editing capabilities such as rich text nodes, rich text notes, multi-root maps, node images, TODOs, icons, notes, tags, format painter, and relationship lines.

## Built for SiYuan

- Create KMind Zen mind maps directly from the SiYuan document tree, with native support for SiYuan tags, links, and related concepts.
- Turn ordinary SiYuan documents into map views, either as a read-only full block tree preview or as a heading outline organizer, then create an editable child mind map from the result.
- Drag documents from the SiYuan document tree into a map to create document cards. Document cards are special nodes that still support child nodes, relationship lines, and other map operations. They default to preview mode, where preview content refreshes at a lower frequency for performance. You can switch to live mode at any time.
- Drag SiYuan blocks directly into a map to create block cards. Block cards are also special nodes that can have child nodes, relationship lines, and more.
- Create mind maps from the SiYuan dock.
- Thanks to SiYuan's block-based architecture, both entire mind maps and individual map nodes can be copied as permanent links. You can paste those links into external apps, and clicking them will open SiYuan, load the target map, and jump straight to the specific node.

## Roadmap

- [ ] AI features
- [ ] Submaps
- [ ] Flowcharts
- [ ] Handwriting
- [ ] Collaboration

## Limitations

- KMind Zen does not yet include every KMind2 feature. The main gaps right now are MOC mode, richer shortcut support, and broader import/export options. These capabilities will be redesigned in the KMind Zen style and released gradually.
- Full block tree document maps are read-only previews. When complex blocks are created as an editable KMind Zen map, entering edit mode converts them into the editable forms currently supported by KMind Zen, so preview formatting may not be preserved exactly.
- If you use SiYuan sync, do not edit the same mind map on multiple devices at the same time.

## QA

Q: What's the difference between KMind Zen and KMind2?

A: KMind Zen is built on a brand-new core, with a more polished look, a cleaner design, and a smoother, more intuitive experience. The magic is in the details, so dive in and try it out.

Q: Do I need to pay again?

A: No. If you previously purchased a KMind2 subscription, whether lifetime or annual, you can upgrade to KMind Zen for free. Global users can contact `kmind_app@outlook.com` by email to get an upgrade code for the SiYuan edition of KMind Zen.

Q: If I only want KMind Zen, is there an early-bird discount?

A: Yes. Enter the early-bird promo code `HELLO-KMIND-ZEN` at checkout to pay 67% of the price. This code expires after 2026-05-20.

Q: Will KMind2 stop getting updates completely?

A: KMind2's feature set is already quite mature. It is also built on the external [mind-map](https://github.com/wanglin2/mind-map) library. Although that library is MIT-licensed, extending KMind2 to more hosts such as an Obsidian plugin or a standalone desktop client would inevitably create conflicts with the original author's product direction. Because of that, all new features will be developed on KMind Zen's self-developed core. KMind2 is entering maintenance mode and will remain stable and usable. If future SiYuan updates make KMind2 unavailable, fixes will be provided promptly.

Q: Does KMind Zen still offer an education discount?

A: Yes. The policy is the same as KMind2. Send a non-failing transcript from your school's academic email account to `kmind_app@outlook.com`, and you can follow the instructions to receive a free annual KMind Zen membership.
