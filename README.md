# 🧠 Metacognition Lab | 學習歷程實驗室

這是一個專為高中生設計的互動式學習歷程檔案製作平台。我們運用獨創的「雞腿理論」與 Google Gemini AI 技術，引導學生將零散的學習經驗，轉化為有架構、有深度的反思檔案。

## 📖 核心理念：雞腿理論

製作學習歷程就像處理一隻雞腿：

1.  **去骨 (De-bone) - 架構確立**：使用 Simon Sinek 的黃金圈法則 (Why, How, What)，抓出學習動機與核心主軸。
2.  **切塊 (Slice) - 細節具象**：運用 STAR 原則 (Situation, Task, Action, Result) 描寫具體情境，並針對不同學科（自然、社會、藝術）提供專屬的深究工具。
3.  **擺盤 (Plate) - 反思昇華**：透過 AI 蘇格拉底式提問，引導學生進行 4F 或 ORID 深度反思，最後進行美學排版與輸出。

## ✨ 主要功能

*   **AI 即時教練**：
    *   撰寫「黃金圈」時，AI 會即時檢核內容邏輯（例如：Why 是否包含內在動機）。
    *   進入反思前，AI 會閱讀全文並提出 3 個深層追問，刺激思考。
    *   完稿時，AI 協助檢查是否包含百字簡述及學術語氣。
*   **學科專屬模組**：
    *   🧪 **自然科學**：實驗錯誤分析 (Error Analysis)，記錄失敗與修正過程。
    *   📚 **社會人文**：問題意識轉換器，將描述性題目轉化為論證性題目。
    *   🎨 **專案實作**：迭代歷程展示，對比草圖 (Draft) 與成品 (Final)。
*   **強制圖說機制**：上傳圖片時強制要求填寫「圖說」與「我在哪裡 (Location Marker)」，確保佐證資料的真實性。
*   **PDF 預覽與輸出**：一鍵生成符合排版規範的頁面，支援列印或另存 PDF。

## 🛠️ 技術棧

*   **Frontend**: React 19, TypeScript
*   **Styling**: Tailwind CSS
*   **AI**: Google Gemini API (`gemini-3-flash-preview`) via `@google/genai` SDK

## 📝 使用流程

1.  **Step 1 設定與分類**：輸入基本資料，選擇檔案類別（一般、自然、社會、藝術）。
2.  **Step 2 敘事架構 (De-bone)**：填寫 Why/How/What，AI 協助檢核邏輯完整性。
3.  **Step 3 具體細節 (Slice)**：填寫 STAR 表格，並使用學科專屬工具與上傳照片（需附圖說）。
4.  **Step 4 反思與教練 (Plate)**：回答 AI 的引導提問，選擇 4F 或 ORID 模板撰寫反思。
5.  **Step 5 預覽與輸出**：檢查 AI 完稿評分 (Pre-flight Checklist)，確認無誤後列印或另存 PDF。

## ⚠️ 注意事項

*   本平台需要網路連線以存取 Google Gemini API。
*   建議使用電腦版瀏覽器以獲得最佳編輯與列印體驗。

---
*Built with ❤️ for Students.*
