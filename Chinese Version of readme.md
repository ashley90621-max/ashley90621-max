# 嗨，我是 Ashley！我的中文名字是劉桂均 👋

__[English Version of README.md](https://github.com/ashley90621-max/ashley90621-max/blob/main/README.md)__

> 資料科學家，專注於 ML、NLP、RAG 與 AI 金融科技 — 將資料轉化為決策系統。

我的工作橫跨機器學習、金融風險建模與產品開發。
專注於建立端對端的數據驅動系統，尤其在預測、風險與決策時機至關重要的領域。

擁有財務背景並轉型為 ML 驅動的分析，我不只把問題當作建模練習，
而是致力於從資料管道到產品的完整解決方案。

- 在 Amplifi Capital 建立**信用風險與貸款時機預測模型**
- 開發基於 **RAG 的產業報告生成助理**，串接 LLM API
- 打造 **BizVital** — 針對中小企業的 ML 商業分析平台
- 建立基於 **ModernBERT 的餐廳推薦系統** chatbot

[![LINKEDIN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kuei-chun-liu-86182a25b/)
[![BIZVITAL](https://img.shields.io/badge/BizVital-FF6B6B?style=for-the-badge&logoColor=white)](https://biz-vital.vercel.app/)

---

如果你有興趣，歡迎先看看我的精選專案。

## 精選專案

**1️⃣ [飯店訂房取消預測](https://github.com/ashley90621-max/hotel-booking-cancellation-prediction)**
針對 119K 筆訂房記錄的端對端 ML 取消預測管線。
- 比較 Random Forest、XGBoost 與 TabNet 三種模型
- 應用 SMOTE、閾值調整與細分市場錯誤分析
- 最終模型：XGBoost（Recall 0.708，ROC-AUC 0.833，可回收營收約 €130 萬）

**2️⃣ [餐廳推薦對話機器人](https://github.com/ashley90621-max/restaurant-chatbot-nlp)**
專為費城餐廳推薦設計的任務導向對話系統。
- 微調 ModernBERT 進行意圖分類與槽填充
- 從 5,854 間餐廳的 687,499 則 Yelp 評論建構知識圖譜
- 多輪對話搭配對話狀態追蹤器（DST）與 session 管理

**3️⃣ [市場研究助理](https://github.com/ashley90621-max/market-research-assistant)**
結合 Wikipedia 檢索與 GPT 合成的 RAG 產業報告生成器。
- 使用 LangChain、Streamlit 與 OpenAI API 建構
- 語意驗證層在檢索前過濾無效輸入
- [線上 Demo](https://market-research-assistant-jryprcyvq4w2zkzcmagxlm.streamlit.app/)

**4️⃣ [行銷因果推論](https://github.com/ashley90621-max/causal-inference-marketing-r)**
將因果方法應用於電視零售面板數據——超越相關性，估計真實效果。
- 使用品牌與週固定效應的行銷組合模型（fixest）
- Amazon Virtual Try-On 功能的 A/B 實驗設計（80/10/10 分組）
- 斷點回歸設計：行銷支出前 20% 閾值 → 因果提升 +172 單位

**5️⃣ [ML 精準行銷](https://github.com/ashley90621-max/targeted-marketing-ml-r)**
RFM 分群與監督式 ML，最大化 Amazon Prime 訂閱的行銷 ROI。
- 比較全量郵寄（ROI −0.22）vs 決策樹精準投放（ROI +0.68）
- 使用 R 的 dplyr、rpart 與 ranger（Random Forest）建構

**6️⃣ [共享單車需求預測](https://github.com/ashley90621-max/bike-sharing-demand-prediction)**
比較 SVM、GBM 與 XGBoost 進行每小時單車租借需求預測。
- XGBoost 達到最佳表現：R²=0.82，RMSE=74.75
- 針對天氣、時間與季節變數的特徵工程

**7️⃣ [損益平衡與顧客終身價值分析](https://github.com/ashley90621-max/break-even-analysis-r)**
使用 R 進行 CAC、CLV 與忠誠度計畫 ROI 的行銷分析案例。
- 計算美食愛好者與非美食愛好者的 CLV（£162.65 vs £26.94）
- 忠誠度計畫分析：美食愛好者 CLV 提升 +20%

**8️⃣ [BizVital](https://github.com/ashley90621-max/BizVital)**
專為台灣中小企業設計的 AI 分析平台——四大智能 Agent 整合於單一儀表板。
- 使用 HTML/CSS/JS 全端開發，部署於 Vercel
- Finance / Sales / Operations / Marketing Agent，含 20+ 個 Chart.js 視覺化圖表
- [線上 Demo](https://biz-vital.vercel.app/)

---

## 📊 核心技術主題

比起列出工具，我更專注於以下維度的應用影響力：

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

**碩士論文：使用 ML 預測貸款時機**
* 論文主題：貸款時機預測 × ML × 金融科技
* 與 [Amplifi Capital UK](https://www.amplificapital.com/) 合作進行

我特別感興趣的領域：
* 將 ML 應用於信用風險與另類借貸決策
* 使用行為與交易信號預測最佳貸款時機
* 將學術 ML 研究與真實金融科技部署接軌

長期願景：ML 模型不應只是預測結果——**它們應該提供可執行的信號，幫助企業與個人做出更好的財務決策。**

---

## 📈 GitHub 統計

![Ashley's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ashley90621-max&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ashley90621-max&layout=compact&theme=default&hide_border=true)
