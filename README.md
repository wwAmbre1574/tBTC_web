# 📊 tBTC Sentio 數據彙整

這是一個用於下載和處理 tBTC Sentio 數據的網頁應用程式。

## 功能特色

- 🔄 一鍵下載最新的 CSV 數據檔案
- 📈 自動處理 Sentio 數據
- 🎨 簡潔美觀的使用者介面
- ⚡ 快速響應的網頁應用

## 使用方法

1. 點擊「取得最新 CSV」按鈕
2. 等待處理完成
3. 自動下載 `tBTC_Created_Filtered.csv` 檔案

## 技術架構

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **後端 API**: Railway 部署的 Node.js 服務
- **數據處理**: 自動化 CSV 生成和過濾

## 部署

這個專案使用 GitHub Pages 進行靜態網頁部署。

### 本地開發

1. 克隆專案：
   ```bash
   git clone https://github.com/wwAmbre1574/tBTC_web.git
   cd tBTC_web
   ```

2. 在瀏覽器中開啟 `index.html`

## 配置

請確保在 `index.html` 中更新 `API_BASE` 變數為你的 Railway API 網址：

```javascript
const API_BASE = "https://your-railway-app.up.railway.app";
```

## 授權

MIT License

## 貢獻

歡迎提交 Issue 和 Pull Request！

---

**注意**: 請確保後端 API 服務正在運行，否則下載功能將無法正常工作。 