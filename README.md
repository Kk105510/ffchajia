# FF14 市场查价

响应式国服市场查价页面，适合手机和窄窗口，支持全区及四大区价格对比、HQ/NQ、收藏、最近查询与清空历史、30 天成交趋势。

## 发布到 GitHub Pages

将 `index.html`、`styles.css`、`app.js`、`favicon.svg`、`.nojekyll` 放在仓库根目录，进入 `Settings → Pages`，使用 `Deploy from a branch`、`main`、`/(root)` 发布。已有网站直接覆盖同名文件即可，访问网址无需改变。

## 数据及隐私

查询和成交数据来自 Universalis 玩家上传记录，可能滞后或不完整。中文物品搜索依赖外部百科和名称映射服务，接口不能访问时会提示。

最近查询最多 7 条。收藏及历史分别保存在当前浏览器 `localStorage` 中，清空历史不会删除收藏或当前查询，不支持自动跨设备同步。

本项目为非官方社区工具，与 Square Enix 无关联。
