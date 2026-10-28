# Hi, I'm Ashley! My Chinese name is Kuei-Chun Liu

__[Chinese Version of Readme.md](https://github.com/ashley90621-max/ashley90621-max/blob/main/Chinese%20Version%20of%20readme.md)__

> Data Scientist specializing in Industrial Analytics, AI Fintech & AI Transformation, building systems that turn data into decisions.

I work at the intersection of machine learning, industrial analytics, financial technology, and AI-driven business transformation.
My focus is on building end-to-end data-driven systems, especially in domains where
prediction, risk, and timing matter, from manufacturing equipment to lending decisions.

With a background in finance and a transition into ML-driven analytics, I approach problems
not just as modeling exercises, but as complete solutions, from data pipeline to product,
helping teams move from raw data to AI-assisted decisions.

- Built a **predictive maintenance decision-support assistant** (explainable ML + RAG) for my MSc dissertation at UCL
- Designed a **credit risk & second-loan timing framework** in an industry project with Amplifi Capital
- Building **CV Web**, a bilingual resume builder with sentence-level ACR (Action, Context, Result) checks
- Building **BizVital**, an ML-powered business analytics platform for SMEs

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashley-liu-86182a25b/)
[![BizVital](https://img.shields.io/badge/BizVital-FF6B6B?style=for-the-badge&logoColor=white)](https://biz-vital.vercel.app/)
---

If you'd like, please take a look at my selected projects below.

## Selected Projects

**1️⃣ Predictive Maintenance Decision-Support Assistant (MSc Dissertation, UCL)**
End-to-end system that turns equipment failure predictions into traceable, engineer-facing maintenance actions.
- Two-stage XGBoost framework: overall failure alert (ROC-AUC 0.984) plus fault-specific diagnosis
- SHAP-based explanations and FMEA-inspired prioritisation feeding a maintenance triage dashboard
- Hybrid RAG assistant (ModernBERT-SetFit intent classification + evidence retrieval): improved four response-quality metrics by 45.8 to 91.7 pp versus a general-purpose LLM, with 100% citation validity

**2️⃣ CV Web (in progress)**
Bilingual (English / Chinese) resume builder that produces an A4 resume in about three minutes.
- Rule-based ACR engine checks every bullet for Action, Context and Result, with sentence-specific suggestions
- Guided questionnaire, live A4 preview with automatic pagination, PDF and Word export
- Privacy by design: resume content stays in the user's browser by default
- Built with HTML/CSS/JS, deployed on Vercel

**3️⃣ [Hotel Booking Cancellation Prediction](https://github.com/ashley90621-max/hotel-booking-cancellation-prediction)**
End-to-end ML pipeline for predicting hotel cancellations across 119K booking records.
- Benchmarked Random Forest, XGBoost, and TabNet
- Applied SMOTE, threshold tuning, and segment-level error analysis
- Final model: XGBoost (Recall 0.708, ROC-AUC 0.833, recoverable revenue ~€1.3M)

**4️⃣ [Restaurant Recommendation Chatbot](https://github.com/ashley90621-max/restaurant-chatbot-nlp)**
Task-oriented dialogue system for Philadelphia restaurant recommendations.
- Fine-tuned ModernBERT for joint intent classification and slot filling
- Knowledge Graph built from 687,499 Yelp reviews across 5,854 restaurants
- Multi-turn dialogue with Dialogue State Tracker (DST) and session management

**5️⃣ [Market Research Assistant](https://github.com/ashley90621-max/market-research-assistant)**
RAG-powered industry report generator using Wikipedia retrieval and GPT synthesis.
- Built with LangChain, Streamlit, and OpenAI API
- Semantic validation layer filters invalid inputs before retrieval
- [Live Demo](https://market-research-assistant-jryprcyvq4w2zkzcmagxlm.streamlit.app/)

**6️⃣ [Causal Inference in Marketing](https://github.com/ashley90621-max/causal-inference-marketing-r)**
Applied causal methods to TV retail panel data — moving beyond correlation to true effect estimation.
- Marketing Mix Modeling with brand and week fixed effects (fixest)
- A/B test design (80/10/10 split) for Amazon Virtual Try-On feature
- Regression Discontinuity Design: top-20% marketing spend → +172 units causal lift

**7️⃣ [Targeted Marketing with ML](https://github.com/ashley90621-max/targeted-marketing-ml-r)**
RFM segmentation and supervised ML to maximise marketing ROI on Amazon Prime subscriptions.
- Compared blanket mailing (ROI −0.22) vs decision tree targeting (ROI +0.68)
- Built in R with dplyr, rpart, and ranger (Random Forest)

**8️⃣ [Bike Sharing Demand Prediction](https://github.com/ashley90621-max/bike-sharing-demand-prediction)**
Benchmarking SVM, GBM, and XGBoost for hourly bike rental demand forecasting.
- XGBoost achieved best performance: R²=0.82, RMSE=74.75
- Feature engineering on weather, time, and seasonal variables

**9️⃣ [Break-Even & Customer Lifetime Value Analysis](https://github.com/ashley90621-max/break-even-analysis-r)**
Marketing analytics case study covering CAC, CLV, and loyalty programme ROI in R.
- Computed CLV for foodie vs non-foodie segments (£162.65 vs £26.94)
- Loyalty programme analysis: +20% CLV uplift for foodie segment

**🔟 [BizVital](https://github.com/ashley90621-max/BizVital)**
AI analytics platform for Taiwan SMEs — four intelligent agents in one dashboard.
- Built full-stack with HTML/CSS/JS, deployed on Vercel
- Finance / Sales / Operations / Marketing Agent with 20+ Chart.js visualisations
- [Live Demo](https://biz-vital.vercel.app/)

---

## 📊 Core Technical Themes

Rather than listing tools, I focus on applied impact across the following dimensions:

**Industrial & Operations Analytics**
* Predictive maintenance on machine sensor data (failure detection & fault diagnosis)
* Failure risk prioritisation with FMEA / RPN and maintenance triage
* Explainable AI (SHAP / LIME) to turn model outputs into engineer-facing actions
* Operations analytics for process and capacity decisions

**ML for Business Decisions**
* Credit risk modelling & loan timing prediction
* Customer lifetime value & churn prediction
* Marketing mix modelling & causal inference

**AI Applications**
* RAG pipeline design & evaluation
* Task-oriented dialogue systems (NLU + DST)
* LLM-powered business intelligence tools

**Product & Analytics**
* End-to-end ML pipeline development
* Data-driven product strategy for SMEs
* Full-stack web deployment (HTML/JS + Vercel)

---

## Research Direction

**MSc Dissertation: Explainable Predictive Maintenance with RAG Decision Support (UCL, 2026)**
* Two-stage failure prediction with fault-specific SHAP explanations
* Evidence-grounded RAG assistant that turns model outputs into maintenance actions

**Industry Project: Second-Loan Timing with Mixture Cure Survival Models (Amplifi Capital, 2026)**
* Two-stage incidence and latency modelling for repeat-borrower prediction
* Framework adopted by the Credit Risk and Marketing teams

I am particularly interested in:
* Making ML predictions explainable and actionable for decision-makers
* Grounding LLM outputs in verifiable evidence
* Applying ML to credit risk and alternative lending decisions

Long-term vision: ML models should not merely predict outcomes, **they should surface actionable signals that help businesses and individuals make better decisions.**
