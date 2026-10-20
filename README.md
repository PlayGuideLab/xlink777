# Xlink777

仓库身份与边界见 [PURPOSE.md](PURPOSE.md)：这是外链方法研究与展示实验，不是游戏模板、游戏站或自动对外提交系统。

X 样式的外链记录页。版式在 index.html，内容在 data/feed.json。

定时任务只追加 data/feed.json 和 data/outbound_links.csv，不要改 index.html。页面打开时会读取 GitHub 上的 data/feed.json，所以新记录推上去之后，刷新就能看到。

上述定时任务描述是内容维护约定，不代表当前任务已运行或数据已同步；运行状态和内容有效性需要单独核验。
