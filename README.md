# WARP+ WireGuard Configuration Generator

這是一個基於 GitHub Pages 的純前端 工具，可在瀏覽器端直接生成 Cloudflare WARP+ (WireGuard) 設定檔。

## 特色
- **安全無虞**：金鑰對 (Curve25519) 完全於瀏覽器本地生成，私鑰不會經過任何第三方伺服器。
- **一鍵部署**：無須後端或 GitHub Actions，開啟 GitHub Pages 即可使用。

## 使用方式
1. 開啟本專案的 GitHub Pages 網址。
2. 點擊「生成 WARP+ 設定檔」。
3. 複製生成的內容並另存為 `warp.conf`，即可匯入 WireGuard / Shadowrocket / Surge 等客戶端使用。
