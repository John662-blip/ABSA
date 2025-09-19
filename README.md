# 📝 Aspect-Based Sentiment Analysis (ABSA) 
## Link Kaggle : https://www.kaggle.com/code/hungphanmj/notebook5a049ccddf

## 📌 Giới thiệu
Dự án triển khai **ABSA** với 2 bước:
1. **Aspect Extraction** – phát hiện các khía cạnh (aspects).
2. **Aspect Sentiment Classification** – phân loại cảm xúc (positive / neutral / negative) cho từng khía cạnh.

Dataset: **[SemEval 2014 Task 4 (Kaggle)]([https://www.kaggle.com/datasets/ivan-bilan/semeval-2014-task-4-aspect-based-sentiment-analysis](https://www.kaggle.com/datasets/charitarth/semeval-2014-task-4-aspectbasedsentimentanalysis))**  

---

## ⚙️ Mô hình & Kết quả
- **Model 1 – Aspect Extraction** (`bert-base-uncased`, TokenClassification)  
  - F1-score: **94%**

- **Model 2 – Sentiment Classification** (`bert-base-uncased`, SequenceClassification)  
  - Accuracy: **98%**

---

## 📊 Ví dụ
Input:  "The screen is bright and clear, but the battery life is disappointing."
Output:  
- `screen → positive`  
- `battery life → negative`

