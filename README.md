# 作战面板 · Daily Battle Board

一个小清新风格的「日历 + 日记 + 计划」单页应用，
专为有明确目标（备考 / 求职 / 项目冲刺）的几个月过渡期设计。

🌐 试用：<https://aishaw02.github.io/my-calendar/>

## 🎯 为什么做这个

商业日历（Notion / Apple Calendar）做不到「日记 + 心情 + 待办 + 倒计时 + 备考追踪 + 求职看板」的整合，
而每一个独立工具都不够轻。这个面板专为有 3-6 个月明确目标的过渡期而生，
过完一个周期就归档，干净利落。

## ✨ 功能

- 📅 月历视图，含农历 + 节日 + 待办预览
- 📝 每日日记 + 心情 emoji（含自定义 emoji 选择器）
- ✅ 待办清单（按状态 / 逾期筛选 / 关键词搜索）
- 📖 日记回顾（按月 / 按日 / 关键词检索 + 心情统计）
- 🎓 雅思备考追踪（LRWS 每日打卡 + 模考分数曲线 + 官方算法总分）
- 💼 秋招进度看板（拖拽排序、状态色阶递进、面试复盘）
- 💡 推荐待办（雅思 / 秋招通用·互联网·国央企）
- ⏰ 关键节点倒计时（可自定义编辑）
- 💾 JSON 导入导出（跨设备数据迁移 / 备份）

## 🚀 怎么跑

**方式 1：直接用线上版**

打开 <https://aishaw02.github.io/my-calendar/> 即可，无需安装。

**方式 2：本地用**

```bash
git clone https://github.com/aishaw02/my-calendar.git
cd my-calendar
open index.html   # macOS
# Windows: 直接双击 index.html
```

## 💾 数据存在哪

所有数据存在浏览器 `localStorage` 里，不上传服务器，不需要账号。

**跨设备同步**：用右上角「导出 JSON」/「导入」手动迁移数据。

> ⚠️ 浏览器清缓存或换设备前，记得导出 JSON 备份。

## 🛠 技术栈

- 纯 HTML + CSS + 原生 JS
- 单文件部署，零依赖
- `localStorage` 持久化
- 部署：GitHub Pages

## 📄 License

MIT
