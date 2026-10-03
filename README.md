# 🛠 Editor Tools

兩個純前端單檔工具，下載即用，無需安裝。

---

## 📝 markdown-editor.html

Markdown 即時預覽編輯器。

**功能**
- 即時分割預覽 / 純編輯 / 純預覽 / 筆記四種模式
- 手機預設全寬預覽，編輯與預覽可一鍵切換；格式工具列可左右滑動
- 筆記模式依發生日期分組，同一天按時間排列；補記另以小字顯示記錄時間
- 可修改匯出檔名，開啟檔案時保留月份檔名
- 顯示瀏覽器草稿與待匯出狀態，重新開啟可還原內容及檔名
- 支援 Mermaid 流程圖（含 render cache 與語法驗證）
- 全文搜尋與取代
- 匯出 .md / .html
- 深色模式

**使用方式**：
- [開啟 markdown-editor](https://narracottt.github.io/Editor/markdown-editor.html)
- 下載 `markdown-editor.html`，用瀏覽器開啟即可。

**手機使用**：用上述網址開啟編輯器，可透過瀏覽器選單加入主畫面。點「開啟」選取 Markdown 檔，點「編輯」修改，再按「匯出 .md」下載副本。

**儲存方式**：草稿只保存在目前瀏覽器，每次載入其他文件會取代草稿；不會同步到其他裝置。開新文件或載入檔案前，若目前內容尚未匯出，會先提醒。匯出不會直接覆寫原始檔案，需自行替換。首次使用會沿用舊版瀏覽器草稿。Mermaid 與完整 Markdown 解析仍透過既有 CDN 載入。

**Lifelog 閱讀**：開啟以 `- YYMMDD HH:MM 內容` 記錄的檔案，點「筆記」會將相同發生日期的記錄整理在一起，日期由早到晚，同一天按發生時刻排列。內容開頭若有有效的過去日期代碼（在記錄日前 365 天內），視為補記；有事件時刻就顯示，未填時刻的補記排在當天最後，並標示實際記錄時間。多行內容仍屬於原記錄。分組僅用於筆記模式，原有「預覽」保留一般 Markdown 呈現；編輯文字、Markdown／HTML 匯出與 HTML 複製都維持原始內容及檔案順序。分組範圍是目前開啟的文件；沒有日期記錄的文件，在筆記模式會提示並顯示一般內容。

<img width="1872" height="903" alt="markdown-editor" src="https://github.com/user-attachments/assets/c05f43f5-9550-439a-bdcd-33955d00143f" />


---

## 🔍 tmx_reviewer.html

TMX 翻譯記憶庫校對工具。

針對**OmegaT**開發。
**使用方式**：
- [開啟 tmx_reviewer](https://narracottt.github.io/Editor/tmx_reviewer.html)
- 下載 `tmx_reviewer.html`，用瀏覽器開啟即可。

---

## 授權
MIT
