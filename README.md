# DataMining Final Project

## 專案簡介 (Project Overview)
在災難發生時，社群媒體（如 Twitter）是獲取即時資訊的重要管道。
然而，許多推文可能只是使用了災難性字眼（如 "on fire"）來表達隱喻，而非真實災難發生。
本專案利用 Natural Language Processing (NLP) 與 Machine Learning 技術，
建立一個預測模型，旨在準確辨識哪些推文描述的是真實災難（Real Disasters），哪些則不是。

# 核心流程 (Core Workflow)

1.資料預處理 (Data Preprocessing):
清洗原始文字數據（移除標點符號、停用詞過濾、轉為小寫）。

2.文本標記化 (Tokenization) 與詞幹提取。

3.特徵工程 (Feature Engineering):
利用 TF-IDF 將非結構化文本轉化為高維數值向量，保留關鍵詞的重要性。

4.模型訓練與評估 (Model Training & Evaluation):

實作多種分類演算法進行對比,評估指標：Accuracy, Precision, Recall, F1-score。

手冊說明
---
[操作手冊.pdf](https://github.com/luyuxuan0414/movie.github.io/blob/main/%E6%93%8D%E4%BD%9C%E6%89%8B%E5%86%8A.pdf):說明整個系統的操作流程，及功能操作說明。

[測試報告書.pdf](https://github.com/luyuxuan0414/movie.github.io/blob/main/%E6%B8%AC%E8%A9%A6%E5%A0%B1%E5%91%8A%E6%9B%B8%20.pdf)：顯示我們的系統回測效果。

[需求規格書.pdf](https://github.com/luyuxuan0414/movie.github.io/blob/main/%E9%9C%80%E6%B1%82%E8%A6%8F%E6%A0%BC%E6%9B%B8.pdf)

[設計規格書.pdf](https://github.com/luyuxuan0414/movie.github.io/blob/main/%E8%A8%AD%E8%A8%88%E8%A6%8F%E6%A0%BC%E6%9B%B8.pdf)：此設計規格書之撰寫建立於需求規格書上，根據目標系統的各種需求，將系統化繁為簡，設計出過程中需要使用到的元件、模組和物件，使得日後當軟體工程師撰 寫軟體時能夠更有依循，將效率發揮到最大值，以此減少軟體開發的成本，並維持整個系統的穩定性。

