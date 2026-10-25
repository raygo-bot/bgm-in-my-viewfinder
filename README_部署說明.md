# 鏡頭裡的 BGM｜BGM in My Viewfinder

這是無需編譯的靜態網站。

## GitHub
1. 新建儲存庫（例如 `bgm-in-my-viewfinder`）。
2. 解壓縮 ZIP。透過 Add file -> Upload files，上傳解壓縮後的 **所有檔案與資料夾** 到儲存庫最外層。
3. 確認儲存庫最外層直接看得到 `index.html`、`assets/`、`photos/`、`songs.json`。不要只上傳 ZIP 檔。

## Render
- New -> Static Site（不是 Web Service）
- 連接 GitHub 儲存庫
- Branch：main
- Root Directory：留空
- Build Command：`echo "Static site ready"`
- Publish Directory：`.`
- Create Static Site / Deploy

Render 成功後會提供 `https://你的網站名稱.onrender.com/`。
測試首頁和 `?s=01`，確認照片及四平台按鈕顯示。

## 展場 QR 管理
上線後，開啟 `https://你的網站名稱.onrender.com/?manage=1` 產生各作品 QR Code。
建議正式網站網址確定後才列印 QR Code。
