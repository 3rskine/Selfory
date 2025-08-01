🖥️ 系統相容性 / Compatibility
Selfory 是一款專為 Android 裝置設計的 AI 語言學習輔助工具，目前支援以下平台與版本：

📱 手機平台支援
平台	最低版本	建議版本	備註
Android	8.0 (API 26)	10.0+ (API 29+)	僅支援 Android，iOS 尚未開發

📌 注意： 需啟用「懸浮視窗權限」功能，以使用類google翻譯懸浮視窗。

🌐 網路相容性
✅ 支援 Wi-Fi 與行動數據連線

❌ 離線功能尚未實作（未來版本將支援部分離線句庫與翻譯緩存）

🔤 語言支援
目前支援的語言包含：

英文（主要語言）

中文（介面語言）

未來支援日文、德文、法文（規劃中）

📦 第三方服務與相依性
技術或服務	用途	狀態
ChatGPT API / Gemini API	AI 句子生成與語意理解	✅ 已整合
Google Translate API / DeepL API	翻譯服務	✅ 已整合
Android Text Selection API	選取文字時觸發	✅ 使用中
Room Database	本地資料儲存（例句與歷史）	✅ 使用中

⚙️ 系統權限需求
權限	用途	是否必要
SYSTEM_ALERT_WINDOW	顯示懸浮翻譯氣泡	✅ 必要
INTERNET	連接 AI 與翻譯 API	✅ 必要
FOREGROUND_SERVICE	長時間背景運行	✅ 建議啟用

🚧 開發中功能
 離線翻譯與 AI 本地推論（支援 ONNX / TFLite）

 使用者語料學習系統

 自訂介面語言與風格

