# DataMining Final Project

## 專案簡介 (Project Overview)
在災難發生時，社群媒體（如 Twitter）是獲取即時資訊的重要管道。
然而，許多推文可能只是使用了災難性字眼（如 "on fire"）來表達隱喻，而非真實災難發生。
本專案利用 Natural Language Processing (NLP) 與 Machine Learning 技術，
建立一個預測模型，旨在準確辨識哪些推文描述的是真實災難（Real Disasters），哪些則不是。

## 核心流程 (Core Workflow)

1.資料預處理 (Data Preprocessing):
清洗原始文字數據（移除標點符號、停用詞過濾、轉為小寫）。

2.文本標記化 (Tokenization) 與詞幹提取。

3.特徵工程 (Feature Engineering):
利用 TF-IDF 將非結構化文本轉化為高維數值向量，保留關鍵詞的重要性。

4.模型訓練與評估 (Model Training & Evaluation):

實作多種分類演算法進行對比,評估指標：Accuracy, Precision, Recall, F1-score。

## 書面報告
---
[書面報告.pdf](書面報告.pdf):說明整個系統的操作流程，及功能操作說明。

[簡報.pdf](https://github.com/luyuxuan0414/DataMining/blob/main/Disaster%20tweets%20or%20not.pdf)
