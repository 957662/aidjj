# JevQuant Console

JevQuant 的生产 Web 控制台（OKX Demo only）。

## 安全边界

- 只显示 Trading Engine / OKX Demo 返回的真实数据。
- 不生成假余额、假行情、假订单或假 PnL。
- OKX、Jev、火山方舟密钥只提交到你自己的 Trading Engine，仓库与 GitHub Pages 不保存密钥。
- Web 控制台和 24×7 Engine 分离部署；Engine 地址保存在当前浏览器 localStorage。
- 永久保留 SIMULATION ONLY 标识。

## Site

GitHub Pages 自动部署工作流：`.github/workflows/pages.yml`
