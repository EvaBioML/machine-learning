# 📌 機器學習與 NLP 專案  

本專案分為兩大部分：  
1. **機器學習分析 (Scikit-learn)**  
2. **RAG 與 NLP (LangChain + ChromaDB)**  

---

## 🔹 機器學習分析  

本專案使用 **Scikit-learn** 建立並訓練 **機器學習與深度學習模型**，應用於多個領域。  

### 📊 應用場景  
- 股票市場分析與價格趨勢預測  
- 藥物活性與效果預測  
- 血液捐贈預測  

### ⚙️ 功能特色  
- 使用 Scikit-learn 提供的多種模型：  
  - 隨機森林 (Random Forest)  
  - 邏輯迴歸 (Logistic Regression)  
  - 多層感知器 (MLP)  等深度學習模型

- 完整流程：  
  - 資料前處理（標準化、特徵選取、缺失值處理）  
  - 訓練 / 測試集切分與交叉驗證  
  - 模型評估（Accuracy、MSE 等）  

- 可擴展至其他領域的數據分析與預測  

📂 **資料來源**：Kaggle、yfinance  

---

## 🔹 RAG 與 NLP  

本專案示範如何使用 **LangChain**、**HuggingFace Embeddings** 以及 **ChromaDB** 建立一個本地 Q&A 向量資料庫，並進行相似度檢索 (**Retrieval-based QA, RAG**)。  

### ⚙️ 功能特色  
- 將 CSV 問答資料轉換為向量嵌入 (embeddings)  
- 使用 **ChromaDB** 建立本地知識庫  
- 支援查詢問題並返回最相關的答案 (簡易 RAG Pipeline)  
- 可快速擴展至：  
  - 文件問答系統  
  - 聊天機器人  
  - 知識檢索應用  
