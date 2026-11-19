# 遊戲計畫

## 願景

做出一款可直接在瀏覽器遊玩的繁體中文密室逃脫遊戲。玩家在有氣氛的房間裡探索、收集線索、解開謎題並逃出；操作直覺、手機可玩，之後能持續擴充。首作《午夜圖書室：最後一頁》包含三間連續房間。

## 目前狀態

- 本機版本已完成三章，包含線索筆記、密碼鎖、錯誤提示、通關、重新開始、音效開關及減少動態偏好；已完成主要流程的瀏覽器驗證。
- GitHub 公開 repository `310054-oss/midnight-library-escape` 已建立，`main` 分支已初始化；程式碼、知識文件與部署 workflow 尚未上傳。
- GitHub Actions workflow 位於 `.github/workflows/pages.yml`，部署範圍為 `site/`；Pages 尚未啟用或驗證。

## 已完成

- [x] 從對話確立密室逃脫類型與繁體中文。
- [x] 建立《午夜圖書室》第一章：探索、兩條線索、密碼 3142。
- [x] 建立《雲頂天文室》第二章：接續探索、密碼 4182。
- [x] 建立《鐘樓書庫》第三章：最終謎題密碼 2751，完成故事收尾。
- [x] 加入線索保留、章節進度、錯誤密碼提示與重新開始。
- [x] 加入通關音效開關、系統減少動態支援、至少 44px 觸控目標。
- [x] 建立 GitHub Actions + Pages 工作流程，推送至 `main` 時部署 `site/`。
- [x] 本機 JavaScript 語法檢查與完整三章流程驗證。
- [x] 建立公開 GitHub repository `310054-oss/midnight-library-escape`。

## 剩餘項目

- [ ] 上傳目前本機版本與 knowledge 文件到 `main`。
- [ ] 設定 Pages 使用 GitHub Actions，確認 Actions 部署成功。
- [ ] 記錄公開網址，並在 hosted site 完成三章遊玩流程。
- [ ] 收集實際遊玩回饋，並在真機確認手機操作。

## 完成條件

三間房間可在桌面與手機瀏覽器依序遊玩，所有線索與密碼有效；公開 GitHub repository 有完整程式與知識文件；GitHub Actions 自動發布 GitHub Pages 且 hosted site 完成基本通關驗證。
