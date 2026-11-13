# 🧋 啵啵手账 · 把快乐喝进日常

一个中文奶茶记录小网站，收藏每一杯饮品与生活中的小确幸。

**在线体验：[打开啵啵手账](https://sdfhrherht.github.io/boba-diary/)**

## 功能

- 概览：本月杯数、花费、平均评分和最爱品牌。
- 记录：饮品、品牌、日期、价格、甜度、温度、杯型、评分与心情。
- 历史：编辑、删除、关键词搜索和品牌筛选。
- 日历：按月浏览，点击日期查看当天的记录。
- 发现：最近七天趋势、品牌偏好、甜度偏好与六种成就。
- 备份：JSON 导出和合并导入。
- 桌面与手机布局，个人手账与示例手账独立保存。

## 使用

打开网站，点击「开始我的手账」，再点击「记一杯快乐」。初次访问显示示例数据，方便体验完整效果。

记录保存在当前浏览器的 localStorage 中，无需账户，不会自动同步。清理浏览器数据会清除记录，请定期导出备份。更换设备、浏览器或网站域名后，可以用「饮茶记录 → 导入备份」迁移。导入会合并新增记录，重复导入会产生重复记录。

## 项目与部署

纯 HTML、CSS 和 JavaScript，无构建依赖。`index.html` 是入口，`style.css` 提供样式，`app.js` 实现交互。字体无法加载时会使用系统中文字体。

GitHub Pages 使用 `main` 分支根目录发布，提交更新后会自动部署。`.nojekyll` 让 Pages 直接发布静态文件。

本地预览：在项目目录运行 `python -m http.server 5173`，然后打开 `http://localhost:5173`。

## 设计参考

- [Habitify 进度网格](https://habitify.featurebase.app/changelog/new-grid-view-for-extended-tracking-on-website-app)
- [Daylio 轻量日记与成就](https://daylio.net/)
- [Exist 个人统计](https://exist.io/)

使用原创奶油白与薄荷绿视觉、CSS 奶茶插画和卡片排版，没有复制参考网站的素材。
