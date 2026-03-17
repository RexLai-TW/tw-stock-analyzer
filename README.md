# 📈 REX 股票分析系統

一個簡單的台股分析工具，基於技術指標提供買賣建議。

## 功能

- 🔍 **單股快速健檢** - 輸入代號立即分析
- 📊 **健康度評分** (0-100分)
- 📈 **技術指標** - MA5、MA20、RSI、KD
- 🎯 **買賣建議** - 停利/停損計算

## 使用方式

1. 開啟 `index.html`
2. 輸入股票代號（如：2330）
3. 點擊「分析」

## 部署

```bash
# 推送到 GitHub
cd apps/tw-stock-analyzer
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/你的帳號/tw-stock-analyzer.git
git push -u origin main
```

然後在 GitHub Repo Settings > Pages 設定 Source 為 `main branch / (root)`

## License

MIT
