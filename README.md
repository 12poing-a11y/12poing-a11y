# Hi, I'm **yizhi!** 👋

系统化做中国商品期货研究与纸面验证。

## Now

- 构建可复现的 **CTA 路径A** 流水线（信号 → 风险预算仓位 → 周度回测）
- 用 GitHub Actions 定时跑，Notion 留痕；手机可看结果

## Featured

### [cta-path-a](https://github.com/12poing-a11y/cta-path-a)

中国期货 CTA 路径A（纸面记账，不下单）

| | |
|---|---|
| 品种 | JD · JM · CF · SR · RU · MA |
| 信号 | 20日与60日收益**同向**才开仓 |
| 仓位 | `floor(¥3000 / (ATR14 × 乘数))`（Equity 20万 × 1.5%） |
| 节奏 | 工作日 15:30 日报 · 周日周回测 |

```text
同向动量过滤  +  ATR 风险平价  →  L1 模拟仓
```

## Other repos

- [daily_stock_analysis](https://github.com/12poing-a11y/daily_stock_analysis)
- [a-stock-data](https://github.com/12poing-a11y/a-stock-data)

## Note

公开内容仅为研究框架与自动化脚手架，**不含** API Key / 实盘账户。不构成投资建议。

---

<p align="left">
  <a href="https://github.com/12poing-a11y?tab=repositories">Repositories</a> ·
  <a href="https://github.com/12poing-a11y/cta-path-a">CTA Path A</a>
</p>
