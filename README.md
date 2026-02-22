# LucrTrade Obsidian Plugin

![GitHub Release](https://img.shields.io/github/v/release/lucrtrade/lucrtrade-obsidian-plugin) ![GitHub Release Date](https://img.shields.io/github/release-date/lucrtrade/lucrtrade-obsidian-plugin)

LucrTrade 是一个专为 Obsidian 用户打造的加密货币交易追踪与分析插件。它能够将您的中心化交易所 (CEX) 数据无缝集成到 Obsidian 知识库中，让您以笔记的形式管理交易记录。

## 核心功能

- **自动化数据同步**
  基于 `ccxt` 库，支持连接主流交易所，自动拉取账户余额、持仓及历史订单数据。

- **结构化交易笔记**
  将每一笔持仓、每一个账户都映射为独立的 Markdown 笔记。通过 Frontmatter 存储元数据，利用 Obsidian 的双链系统关联交易策略、复盘笔记与市场分析。

- **专业级图表可视化**
  - **金融图表**: 集成 TradingView Advanced Charts，在笔记中直接渲染带有买卖点标记的 K 线图，支持多种图表类型、时间周期和绘图工具。
  - **交易日历**: 直观展示每日交易频率与盈亏概览。
  - **盈亏热力图**: 可视化展示长期交易表现。

- **综合仪表盘**
  提供 React 构建的现代化仪表盘，一站式查看多账户资产分布、未结持仓及近期交易动态。

## 支持的交易所

| 交易所 | 类型 | 手动模式 | API 同步 |
|--------|------|----------|----------|
| Binance Future | 合约 (USDM) | ✓ | ✓ |
| Binance | 现货 | ✓ | 暂不支持 |
| OKX | 现货 | ✓ | 暂不支持 |
| OKX Future | 合约 | ✓ | 暂不支持 |
| Bybit | 现货 | ✓ | 暂不支持 |
| Bybit Future | 合约 | ✓ | 暂不支持 |
| BitMEX | 现货 | ✓ | 暂不支持 |
| Gate.io | 现货 | ✓ | 暂不支持 |
| Coinbase | 现货 | ✓ | 暂不支持 |
| Kraken | 现货 | ✓ | 暂不支持 |

## 为什么选择 LucrTrade？

如果您习惯使用 Obsidian 记录笔记，并且是加密货币交易者，LucrTrade 能帮助您：

1. **数据私有化**: 所有交易数据存储在本地 Markdown 文件中，安全可控。
2. **深度复盘**: 结合 Obsidian 的各项插件功能，对每一笔交易进行深度复盘和归档。
3. **构建交易体系**: 将碎片化的交易记录转化为系统化的交易知识库。

## 安装

### 🚀 极速安装 (推荐)

1. 点击安装并启用 [BRAT 插件](https://obsidian.md/plugins?id=obsidian42-brat)
2. 复制以下地址到浏览器打开，即可添加 LucrTrade 插件：

   ```
   obsidian://brat?plugin=lucrtrade/lucrtrade-obsidian-plugin
   ```

### 手动安装 (Manual)

1. 从 [Releases](https://github.com/lucrtrade/lucrtrade-obsidian-plugin/releases) 页面下载最新版本。
2. 将 `main.js`、`manifest.json` 和 `styles.css` 文件解压到您的 vault 的 `.obsidian/plugins/lucrtrade-obsidian-plugin` 文件夹中。
3. 重新加载 Obsidian。
4. 在社区插件 (Community Plugins) 选项卡中启用该插件。
