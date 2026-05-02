# PDF Mix & Match - 頁面編輯器與格式轉換工具

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

這是一個強大、隱私安全且完全運行於瀏覽器端的工具，讓你可以直覺地拆解、重組 PDF 頁面與圖片檔案。

## 🌟 核心特色

多格式支援：支援同時上傳 PDF 檔案與常見圖片格式 (PNG, JPG, JPEG)。
視覺化頁面編輯：
    拖曳排序：利用 SortableJS 實現直覺的頁面順序調整。
    靈活選取：支援單選、Shift+Click 連續多選，以及自定義數字範圍選取。
    旋轉頁面：支援對選定頁面進行 90 度旋轉。
多樣化匯出選項：
    匯出 PDF：依自定義順序合併並重新封裝為 PDF。
    匯出圖片：將選定頁面轉換為圖片並打包成 ZIP 下載。
    匯出 Markdown：擷取 PDF 內的文字層，或將圖片以 Base64 格式嵌入 MD 文件。
品質控制：提供高、中、低三種壓縮模式，平衡檔案大小與清晰度。
隱私保障：100% 在客戶端運算，您的檔案永遠不會上傳到伺服器。


## 🚀 如何使用

1.  匯入檔案：點擊右上角「新增 PDF / 圖片」或直接將檔案拖入視窗。
2.  調整頁面：
    使用滑鼠拖曳卡片來改變順序。
    勾選需要保留的頁面，或在工具列使用數字範圍選取。
    點擊「旋轉」按鈕調整頁面方向。
3.  選擇匯出格式：
    選擇品質選項（高、中、低）。
    點擊 匯出為 PDF、匯出圖片或 匯出 MD。

## 📖 Markdown 匯出邏輯

本工具的 Markdown 匯出功能會根據檔案性質自動調整：
文字型 PDF：提取頁面內的數位文字層，保留換行結構。
圖片與掃描檔：若偵測不到文字，則會將頁面轉換為 Base64 字串，以 `![image](data:...)` 語法直接嵌入 Markdown，確保在任何編輯器中都能預覽圖形內容。

## 📄 授權條款

本專案採用 MIT 授權。


## 贊助這個專案
✨ 喜歡這個專案嗎？ ✨
如果這個工具為你節省了時間 ⏱️，或者對你的研究有所啟發 💡
🧋 點擊圖示請我喝杯珍奶吧 🧋

[![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me) [![請我喝珍奶](https://s3.ap-southeast-1.amazonaws.com/media.anyonelab.com/images/boba/boba-embed-icon.png)](https://eledgetw.bobaboba.me)
←←(點擊珍奶圖示贊助作者)
這能讓程式碼持續穩定運行，也讓更多靈感不斷湧現！✨
