# Claude Conversations Viewer

An elegant offline viewer for your Claude conversations — look back at every chat with dignity, even after getting banned.

---

## What

![Screenshot](./screenshot.png)
After Claude bans you, all you get is a cold, unreadable JSON export. This single-file HTML tool recreates the familiar Claude chat experience from that data dump — same warm beige palette, same serif elegance. Search, sort, Markdown rendering — you know, the whole shebang — so you don't leave empty-handed.

## Features

- Color scheme & typography matching Claude's official UI — feels like home, even in exile
- Conversation list sidebar with keyword search & highlighting
- Sort by last updated or created time
- Full Markdown rendering (code blocks, tables, blockquotes, lists, etc.)
- Collapsible tool use / tool result blocks
- Zero install — just open the file (fonts & marked.js loaded from CDN)

## Usage

1. Go to [Claude Privacy Settings](https://claude.ai/settings/privacy) and export your data — you'll get a JSON file
2. Double-click `ClaudeDataLoader.html` to open it
3. Click **Load JSON** in the top-left corner and select your downloaded JSON file
4. Browse, search, and revisit your conversations in the sidebar

## Notes

- The JSON file is parsed entirely in your browser — nothing is uploaded anywhere
- Internet connection required for CDN fonts & marked.js (cacheable after first load)
- Large files (thousands of conversations) may load slowly — just be patient

## License

WTFPL — Getting banned sucks enough, do whatever you want.

---

# Claude Conversations Viewer

一个优雅的 Claude 对话离线查看器 —— 被封号后也能体面地回顾你与 Claude 的每一段对话。

---

## 这是什么

Claude 封号后官方只给你一个冷冰冰的 JSON 导出文件，没法直接看对话内容。这个单文件 HTML 工具把那份数据变回你熟悉的 Claude 聊天界面 —— 同样的暖米色调，同样的衬线优雅。搜索、排序、Markdown 渲染全都有，让你"净身出户"后也不至于一无所有。

## 功能

- 配色 & 字体神还原 Claude 官方界面 —— 被扫地出门了，但家的感觉还在
- 对话列表侧边栏，支持关键词搜索 & 高亮
- 按更新时间 / 创建时间排序
- 完整 Markdown 渲染（代码块、表格、引用、列表等）
- Tool use / Tool result 折叠展示
- 零依赖，下载即用（字体和 marked.js 从 CDN 加载）

## 使用方法

1. 前往 [Claude 隐私设置](https://claude.ai/settings/privacy) 导出你的数据（Export Data），得到一个 JSON 文件
2. 双击打开 `ClaudeDataLoader.html`
3. 点击页面左上角 **Load JSON**，选择你下载的 JSON 文件
4. 开始在侧边栏浏览、搜索、回顾你的对话

## 注意事项

- JSON 文件完全在浏览器本地解析，不会上传到任何服务器
- 需要网络连接以加载字体和 marked.js CDN 资源（首次加载后可缓存）
- 大文件（数千条对话）加载可能稍慢，耐心等待即可

## 许可

WTFPL — 被封号已经够惨了，随便用。
