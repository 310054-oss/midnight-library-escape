# 決策紀錄

## GitHub repository 與 Pages 可見度

- 狀態：已依建議建立公開 repository `310054-oss/midnight-library-escape`；程式尚未推送，Pages 尚未發布。
- 建議：維持公開 repository，讓 GitHub Free 的 Pages 可用。GitHub Free 的 Pages 需使用公開 repository；Pages 網站本身會公開給網際網路使用者。
- 公開範圍：原始碼、README、knowledge 文件與 Git 歷史可被任何人瀏覽。部署 workflow 僅上傳 `site/`，所以 `knowledge/` 不會出現在 Pages 網站本身。
- 依據：<https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site>。

## 待完成的手機與玩家驗證

- 狀態：桌面瀏覽器 390px、320px 窄視窗版面和基本操作已檢查；真機觸控/鍵盤行為，以及外部玩家的理解度回饋尚未取得。
- 需要的外部條件：一支可開啟公開遊戲網址的手機，以及至少一位願意自行遊玩的測試者。代理人不能從桌面 viewport 模擬可靠判斷真機虛擬鍵盤、觸控感受或玩家是否能理解線索。
- 建議執行方式：先在 iOS Safari 或 Android Chrome 真機從頭玩到結局，確認場景沒有水平溢位、線索熱區容易點選、密碼欄位能使用數字鍵盤輸入且對話框可完整顯示；再請一位未看過解答的玩家獨立遊玩，記錄每章卡關處、線索理解方式及完成時間。取得實際觀察後再更新 `knowledge/plan.md` 與 `knowledge/experience.md`。
- 建議：保留兩項獨立待辦，直到真機和玩家各自提供直接證據；不要因桌面模擬或開發者本人通關而勾選。
- 範圍：適用於以觸控為主要操作方式，且謎題理解度會影響遊玩完成率的響應式網頁遊戲。

