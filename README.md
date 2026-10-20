# Hi, I'm **yizhi!** 👋

系统化做中国商品期货研究与纸面验证。

## 档案可视化

**[打开个人研究台 →](https://12poing-a11y.github.io/)**

信号板 · 验证参数 · 流水线一览（GitHub Pages）

## 第二大脑

- Notion 主控：**第二大脑 · 余**
- Vault 镜像：https://github.com/12poing-a11y/second-brain

## Now

- 构建可复现的 **CTA 路径A** 流水线（信号 → 风险预算仓位 → 周度回测）
- GitHub Actions 定时跑；Notion 留痕；可视化已挂主页
- 下一步：接入 Grokbot 云电脑上的 **Obsidian** 知识库

## Featured

### [cta-path-a](https://github.com/12poing-a11y/cta-path-a)

中国期货 CTA 路径A（纸面记账，不下单）

| | |
|---|---|
| 品种 | JD · JM · CF · SR · RU · MA |
| 信号 | 20日与60日收益**同向**才开仓 |
| 仓位 | `floor(¥3000 / (ATR14 × 乘数))`（Equity 20万 × 1.5%） |
| 节奏 | 工作日 15:30 日报 · 周日周回测 |
| 可视化 | [12poing-a11y.github.io](https://12poing-a11y.github.io/) |

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
  <a href="https://12poing-a11y.github.io/">研究台</a> ·
  <a href="https://github.com/12poing-a11y?tab=repositories">Repositories</a> ·
  <a href="https://github.com/12poing-a11y/cta-path-a">CTA Path A</a>
</p>
