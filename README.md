# NCT DREAM — Our Dream Journey

這是一個完整的繁體中文 NCT DREAM 介紹網站（非官方課程專題），已經將你上傳的森林團體照片設定為 **index.html 首頁主圖**。

## 如何預覽
1. 解壓縮 ZIP。
2. 開啟 `NCT_DREAM_Our_Dream_Journey` 資料夾。
3. 直接雙擊 `index.html`，就能在瀏覽器看到網站。
4. 也可在 VS Code 選擇「File → Open Folder」，開啟專案資料夾。
5. 若安裝 Live Server，可以在 `index.html` 按右鍵選「Open with Live Server」。

## 頁面
- `index.html`：首頁（你提供的團體照片）
- `members.html`：成員介紹
- `history.html`：2016–2026 團體歷程
- `music.html`：歌曲介紹與分類篩選
- `gallery.html`：團體照片與官方舞台相關連結
- `concerts.html`：新增 THE DREAM SHOW 1–4 演唱會系列介紹（AI 依規則延伸示範）
- `sources.html`：資料來源和版權

## 重要路徑
- 首頁圖片：`assets/images/nct-dream-group.jpg`
- 網站樣式：`assets/css/style.css`
- 網站互動：`assets/js/main.js`
- AI 專案規範：`AGENTS.md`

## GitHub Pages 發布方式
1. 登入 GitHub，新建 Public repository，例如 `nct-dream-website`。
2. 將 **專案資料夾內部所有檔案與 assets 資料夾** 上傳至儲存庫根目錄（`index.html` 必須位於根目錄）。
3. 進入 Repository → Settings → Pages。
4. Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/(root)`，按 Save。
5. 部署完成後到 Pages 頁面找公開網站網址。

## 提醒
首頁照片由使用者提供，放在此專案不代表已取得公開發表或再散布授權。公開前請確認原始圖片的著作權和使用條件。部分字型使用 Google Fonts，無網路時會自動改用系統字型。所有主要網站內容與圖片本身皆能離線顯示。


## 老師第 5 題：用 AI 繼續延伸網站（已實作）
本版本已實際新增 `concerts.html`：沿用原本網站的森林綠、奶油白、卡片、共用導覽列和手機版排版。`AGENTS.md` 新增「未來網站內容擴充規則」章節，列明未來如何加入歌曲、成員、歷程、演唱會或全新頁面，並要求更新來源和檢查連結。

**作業說明範例：**「我透過 AGENTS.md 事先制定網站配色、頁面結構、檔案規則和新增內容的方式。需要新內容時，只要讓 AI 閱讀 AGENTS.md 與現有程式碼，就能依照相同規則新增頁面。本次示範新增 concerts.html 演唱會頁面，並同步更新導覽列、CSS、資料來源，讓網站延伸後仍維持一致風格。」

### 可再次嘗試的 AI 指令
「請先讀 AGENTS.md，再依官方資訊於 concerts.html 新增下一筆經確認的演唱會資料，沿用相同卡片樣式，補來源，並驗證手機版及所有導覽連結。」

### 修改到的檔案
- 新增：`concerts.html`
- 修改：`AGENTS.md`、`README.md`、`assets/css/style.css`、`sources.html`，以及每一個 `.html` 頁面的導覽列及頁尾。
- 未修改：`assets/images/nct-dream-group.jpg`（你指定的首頁照片）。
