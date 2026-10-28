# 嗨，我是 Ashley！我的中文名字是劉桂均 👋

__[English Version of README.md](https://github.com/ashley90621-max/ashley90621-max/blob/main/README.md)__

> 資料科學家，專注於工業數據分析、AI 金融科技與 AI 應用轉型，將資料轉化為決策系統。

我的工作橫跨機器學習、工業數據分析、金融科技與 AI 驅動的企業轉型。
專注於建立端對端的數據驅動系統，尤其在預測、風險與決策時機至關重要的領域，
從製造設備到放款決策皆是。

擁有財務背景並轉型為 ML 驅動的分析，我不只把問題當作建模練習，
而是致力於從資料管道到產品的完整解決方案，協助團隊從原始資料走向 AI 輔助決策。

- 完成 **預測性維護決策支援助理**（可解釋 ML + RAG），為 UCL 碩士論文
- 設計 **信用風險與二次貸款時機預測框架**，為與 Amplifi Capital 合作的產學專案
- 開發 **CV Web**，中英雙語履歷平台，提供逐句 ACR（Action、Context、Result）診斷
- 打造 **BizVital**，針對中小企業的 ML 商業分析平台

[![LINKEDIN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kuei-chun-liu-86182a25b/)
[![BIZVITAL](https://img.shields.io/badge/BizVital-FF6B6B?style=for-the-badge&logoColor=white)](https://biz-vital.vercel.app/)

---

如果你有興趣，歡迎先看看我的精選專案。

## 精選專案

**1️⃣ 預測性維護決策支援助理（UCL 碩士論文）**
端對端系統，將設備故障預測轉化為可追溯、工程師可直接執行的維護行動。
- 兩階段 XGBoost 架構：整體故障預警（ROC-AUC 0.984）加上故障類型診斷
- 以 SHAP 解釋模型結果，結合 FMEA 風險優先排序，輸出至維護分流儀表板
- 混合式 RAG 助理（ModernBERT-SetFit 意圖分類 + 證據檢索）：4 項回答品質指標較一般 LLM 提升 45.8 至 91.7 個百分點，引用正確率 100%

**2️⃣ CV Web（開發中）**
中英雙語履歷平台，約 3 分鐘即可產出 A4 履歷。
- 規則式 ACR 引擎逐句檢查 Action、Context、Result，並依句子內容提供具體建議
- 引導式問答填寫、即時 A4 預覽與自動分頁，支援 PDF 與 Word 匯出
- 隱私優先設計：履歷內容預設只儲存在使用者的瀏覽器
- 使用 HTML/CSS/JS 開發，部署於 Vercel

**3️⃣ [飯店訂房取消預測](https://github.com/ashley90621-max/hotel-booking-cancellation-prediction)**
針對 119K 筆訂房記錄的端對端 ML 取消預測管線。
- 比較 Random Forest、XGBoost 與 TabNet 三種模型
- 應用 SMOTE、閾值調整與細分市場錯誤分析
- 最終模型：XGBoost（Recall 0.708，ROC-AUC 0.833，可回收營收約 €130 萬）

**4️⃣ [餐廳推薦對話機器人](https://github.com/ashley90621-max/restaurant-chatbot-nlp)**
專為費城餐廳推薦設計的任務導向對話系統。
- 微調 ModernBERT 進行意圖分類與槽填充
- 從 5,854 間餐廳的 687,499 則 Yelp 評論建構知識圖譜
- 多輪對話搭配對話狀態追蹤器（DST）與 session 管理

**5️⃣ [市場研究助理](https://github.com/ashley90621-max/market-research-assistant)**
結合 Wikipedia 檢索與 GPT 合成的 RAG 產業報告生成器。
- 使用 LangChain、Streamlit 與 OpenAI API 建構
- 語意驗證層在檢索前過濾無效輸入
- [線上 Demo](https://market-research-assistant-jryprcyvq4w2zkzcmagxlm.streamlit.app/)

**6️⃣ [行銷因果推論](https://github.com/ashley90621-max/causal-inference-marketing-r)**
將因果方法應用於電視零售面板數據，超越相關性，估計真實效果。
- 使用品牌與週固定效應的行銷組合模型（fixest）
- Amazon Virtual Try-On 功能的 A/B 實驗設計（80/10/10 分組）
- 斷點回歸設計：行銷支出前 20% 閾值 → 因果提升 +172 單位

**7️⃣ [ML 精準行銷](https://github.com/ashley90621-max/targeted-marketing-ml-r)**
RFM 分群與監督式 ML，最大化 Amazon Prime 訂閱的行銷 ROI。
- 比較全量郵寄（ROI −0.22）vs 決策樹精準投放（ROI +0.68）
- 使用 R 的 dplyr、rpart 與 ranger（Random Forest）建構

**8️⃣ [共享單車需求預測](https://github.com/ashley90621-max/bike-sharing-demand-prediction)**
比較 SVM、GBM 與 XGBoost 進行每小時單車租借需求預測。
- XGBoost 達到最佳表現：R²=0.82，RMSE=74.75
- 針對天氣、時間與季節變數的特徵工程

**9️⃣ [損益平衡與顧客終身價值分析](https://github.com/ashley90621-max/break-even-analysis-r)**
使用 R 進行 CAC、CLV 與忠誠度計畫 ROI 的行銷分析案例。
- 計算美食愛好者與非美食愛好者的 CLV（£162.65 vs £26.94）
- 忠誠度計畫分析：美食愛好者 CLV 提升 +20%

**🔟 [BizVital](https://github.com/ashley90621-max/BizVital)**
專為台灣中小企業設計的 AI 分析平台，4 大智能 Agent 整合於單一儀表板。
- 使用 HTML/CSS/JS 全端開發，部署於 Vercel
- Finance / Sales / Operations / Marketing Agent，含 20+ 個 Chart.js 視覺化圖表
- [線上 Demo](https://biz-vital.vercel.app/)

---

## 📊 核心技術主題

比起列出工具，我更專注於以下維度的應用影響力：

**工業與營運分析**
* 以機台感測器資料進行預測性維護（故障偵測與故障診斷）
* 以 FMEA / RPN 進行故障風險優先排序與維護分流
* 運用可解釋 AI（SHAP / LIME），將模型結果轉化為工程師可執行的行動
* 營運分析，支援流程與產能決策

**ML 商業決策**
* 信用風險建模與貸款時機預測
* 顧客終身價值與流失預測
* 行銷組合模型與因果推論

**AI 應用**
* RAG 管線設計與評估
* 任務導向對話系統（NLU + DST）
* LLM 驅動的商業智能工具

**產品與分析**
* 端對端 ML 管線開發
* 中小企業數據驅動產品策略
* 全端網頁部署（HTML/JS + Vercel）

---

## 研究方向

**碩士論文：結合 RAG 決策支援的可解釋預測性維護（UCL，2026）**
* 兩階段故障預測，並提供各故障類型的 SHAP 解釋
* 以證據為基礎的 RAG 助理，將模型輸出轉化為維護行動

**產學專案：以混合治癒存活模型預測二次貸款時機（Amplifi Capital，2026）**
* 以發生機率與發生時間兩階段建模，預測回頭借款客戶
* 框架獲信用風險與行銷團隊採用

我特別感興趣的領域：
* 讓 ML 預測結果可解釋、可執行，幫助決策者使用
* 讓 LLM 的輸出有可驗證的證據支撐
* 將 ML 應用於信用風險與另類借貸決策

長期願景：ML 模型不應只是預測結果，**它們應該提供可執行的信號，幫助企業與個人做出更好的決策。**
