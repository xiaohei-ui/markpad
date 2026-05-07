# MarkPad

轻量的 Markdown 文件管理与查看工具。支持 iPhone / iPad / 桌面浏览器，可添加到主屏幕当作 App 使用。

## 功能

- 上传本地 .md / .markdown / .txt 文件
- 拖拽文件到页面直接打开
- 文件管理（列表、切换、删除）
- Markdown 完整渲染（标题、代码块、表格、任务列表、图片等）
- 暗色 / 亮色主题切换
- PWA 支持，iPhone 可添加到主屏幕
- 数据存储在浏览器 IndexedDB 中，关闭后不丢失

访问地址：https://xiaohei-ui.github.io/markpad/

## iPhone 添加到主屏幕

1. 用 Safari 打开网站
2. 点底部「分享」按钮（方框+箭头图标）
3. 选择「添加到主屏幕」
4. 就像原生 App 一样使用了

## 快捷键

- `Ctrl/Cmd + O` — 上传文件
- `Ctrl/Cmd + F` — 搜索
- `Esc` — 关闭侧边栏

## 技术

- 单 HTML 文件，零构建工具
- marked.js 渲染 Markdown
- IndexedDB 本地存储
- Service Worker 离线缓存
