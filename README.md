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
  - F1-score: **89%**

- **Model 2 – Sentiment Classification** (`bert-base-uncased`, SequenceClassification)  
  - Accuracy: **80%**

---

## 📊 Ví dụ
Input:  "The screen is bright and clear, but the battery life is disappointing."
Output:  
- `screen → positive`  
- `battery life → negative`
## Giao diện 
![b7f1549149cfc3919ade](https://github.com/user-attachments/assets/ba904360-1eb5-420d-b7e8-6ede4e7edba3)
