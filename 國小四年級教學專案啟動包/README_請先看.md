# 國小四年級教學專案啟動包

這個資料夾是一套可攜式專案骨架。把「資料夾裡面的全部內容」複製到新的 GitHub 專案根目錄，就能延續目前影片與首頁的製作品質，不必重新向另一個帳號或 AI 工具解釋整套流程。

## 第一次使用

1. 建立新的專案資料夾或 GitHub repository。
2. 將本啟動包內的全部檔案複製到新專案根目錄；包含以點開頭的 `.gitignore`。
3. 打開 `PROJECT_PROFILE.yaml`，填入新專案的 Google Drive 教材資料夾與 GitHub 網址。
4. 在新的 AI 對話中，先上傳或提供整個專案，再貼上 `提示詞_新聊天直接貼上.md` 的文字。
5. AI 必須先讀 `START_HERE.md`、製作規格、專案設定與品質檢查表，再開始工作。
6. 課本與製作中的影片放在 `local-content/`，不要提交 GitHub。
7. 影片上傳 YouTube 後，只要編輯 `data/lessons.js`，首頁就會顯示新的課程連結。

## 重要檔案

- `START_HERE.md`：任何 AI 或協作者最先讀的入口。
- `AGENTS.md`：給 Codex 類工具的專案層級規則。
- `國小四年級漫畫教學影片製作規格.md`：教學、動畫、旁白與輸出的共同標準。
- `PROJECT_PROFILE.yaml`：可修改的專案資料、角色、聲音與網址。
- `QUALITY_CHECKLIST.md`：每支影片與首頁上線前的檢查表。
- `影片設計說明/影片設計說明範本.md`：每一課獨立保存的設計紀錄。
- `data/lessons.js`：首頁課程清單。
- `index.html`：可直接開啟的靜態首頁。
- `assets/characters/`：固定角色小甯、小霖的原始參考圖。
- `assets/fugglers/`：首頁使用的吉祥物圖片。

## 不要複製到 GitHub 的內容

課本 PDF、下載的參考檔、旁白音檔、動畫影格、剪輯專案及輸出的 MP4，全部放在 `local-content/`。`.gitignore` 已排除這些大型檔案。完成的影片上傳 YouTube，GitHub 只保留首頁、設定、說明與必要圖片。

## 新課程的固定流程

教材研讀 → 提出影片設計 → 等使用者同意 → 製作全新影片 → 品質檢查 → 使用者上傳 YouTube → 更新首頁 → 使用者明確要求後才推送 GitHub。
