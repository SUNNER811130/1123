# LINE Webhook for Railway

這是一個最基本的 Node.js + Express LINE webhook 範例，部署到 Railway。

## ✅ 使用方式

1. 將此專案 Fork / 上傳到你的 GitHub
2. 到 [https://railway.app](https://railway.app) 點選 `New Project` → `Deploy from GitHub Repo`
3. 設定環境變數：
   - `CHANNEL_ACCESS_TOKEN`
   - `CHANNEL_SECRET`
4. LINE Developers 後台貼上 webhook URL：
   ```
   https://你的專案.up.railway.app/webhook
   ```
5. 開啟 Webhook 並傳訊息測試
