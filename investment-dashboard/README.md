# Investment Dashboard

个人美股投资复盘看板。

## 首版范围

- 睡前盘中复盘
- 早间收盘复盘
- 周一增量研究
- 周四增量研究
- 周六完整研究
- 真实持仓与委托摘要
- 历史报告时间线

网页数据统一读取 `data/dashboard.json`，完整报告保存在 `reports/`。

## 自动部署

合并到 `main` 后，GitHub Actions 会把 `investment-dashboard/` 发布到 GitHub Pages。

## 数据约束

网页只展示既有定时任务输出，不在前端重新分析市场，不推测订单成交。
