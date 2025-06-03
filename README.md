# 跑馬燈控制與顯示頁（UI 版本）

這是配合 Render Static Site 的 HTML 前端介面，包含：

- control-WebSocket.html（控制頁）
- display-long-WebSocket.html（顯示長版）
- display-short-WebSocket.html（顯示短版）

## Render Static Site 部署步驟：

1. 上傳此資料夾至 GitHub 新 repo（例如：marquee-ui）
2. 到 Render.com 建立 `Static Site`，選該 repo
3. 設定如下：
   - Build command：空白
   - Publish directory：`.`（一個點）
4. 點 `Create Static Site`

建完後你就會拿到網址，如：
[https://marquee-ui.onrender.com/display-long-WebSocket.html](https://marquee-ui.onrender.com/control-WebSocket.html)

即可搭配 WebSocket Server 使用！
