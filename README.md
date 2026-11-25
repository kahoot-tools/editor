# Kahoot 題目製作編輯器

https://kahoot-tools.github.io/editor/

上傳 PDF、圖片、TXT、Word、PPT、Excel 或貼上文字，自動辨識題目並轉成可匯入 Kahoot 的 Excel（有圖片時另附 ZIP）。

也可以直接上傳 Kahoot「詳細資料」頁列印成的題目 PDF，會讀出每一題的題型、題目、選項、正確答案（✓）、題目圖與選項圖，圖標答題會自動標出正確位置。

也可以直接上傳 Kahoot 匯出的「遊戲報告」Excel（Overview、1 Quiz、2 Quiz…），會直接讀出每一題的題型、題目、選項、正確答案與秒數（報告 Excel 沒有圖片）。

- 純前端單一頁面（`index.html`），檔案只在使用者瀏覽器內處理
- 編輯內容自動儲存在使用者自己的瀏覽器（IndexedDB）
- 在 GitHub Pages 上使用規則辨識＋瀏覽器文字辨識；AI 圖片生成預留 `IMAGE_API` 設定

skyeva / 羿璇（小天）製作
