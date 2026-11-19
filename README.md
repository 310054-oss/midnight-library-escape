# 午夜圖書室：最後一頁

一款繁體中文單頁密室逃脫遊戲，共三間連續房間：午夜圖書室的密碼是 `3142`，雲頂天文室的密碼是 `4182`，鐘樓書庫的密碼是 `2751`。

## 本機遊玩

直接用瀏覽器開啟 `site/index.html` 即可，不需要安裝套件或啟動伺服器。

## 發布到 GitHub Pages

專案已包含 `.github/workflows/pages.yml`。將程式推送到 `main` 後，GitHub Actions 會建立 Pages artifact 並部署網站。

首次設定 repository 時，請在 **Settings → Pages → Build and deployment** 將來源設為 **GitHub Actions**。部署完成後可在 Actions 的部署工作或 Settings → Pages 查看網站網址。

## 遊玩方式

1. 點選「進入圖書室」。
2. 調查房內物件，線索會加入右側筆記。
3. 解開每間房間的四位數密碼後，沿故事前往下一間。
4. 找回最後一頁即可完成遊戲；可隨時重新開始。

