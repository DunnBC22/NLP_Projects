# Transformer Comparison Using Binary Classification Dataset

**Project Purpose Statement:** The purpose of this project was to train six (6) different Transformers (mainly Encoder-only transformers) on the same dataset to see which one is the most efficient and effective. All six projects are the same with the exception of both the transformer and (potentially) the length of the tokenized input.

**Further Details on Methodology:** I trained each model for 5 epochs (iterations of all samples).

**Dataset Name:**  Disaster Tweets
**Dataset Source:** https://www.kaggle.com/datasets/vstepanenko/disaster-tweets

## Results

| Transformer Model | Checkpoint                      | Training Duration (Min) | Memory (GB) |  Loss  | Accuracy |   F1   | Recall | Precision |
| :---------------: |  :----------------------------: |  :----------------: | :---------: | :----: | :------: | :----: | :----: | :-------: |
| **DistilBERT**    | `distilbert-base-uncased`       | 71      | 4.56  | 0.2557 | 0.9138 | 0.7752 | 0.8204 |   0.7348  |
| **ERNIE**         | `nghuyong/ernie-2.0-base-en`    | 242         | 7.45    | 0.2292 |  0.9156  | 0.7876 | 0.8436 |   0.7386  |
| **ELECTRA**       | `bhadresh-savani/electra-base-emotion`| 39    | 2.29   | 0.3276 |  0.8857  | 0.7246 | 0.7991 |   0.6628  |
| **RoBERTa**       | `roberta-base`                  | 994           | 8.5   | 0.2640 |  0.8989  | 0.7569 | 0.8211 |   0.7020  |
| **DeBERTa**       | `microsoft/deberta-v3-small`    | 443          | 9.72   | 0.2942 |  0.9050  | 0.7453 | 0.7453 |   0.7453  |
| **ALBERT**        | `albert-base-v2`                | 241           | 0.815  | 0.2899 |  0.8989  | 0.7784 | 0.8523 |   0.7163  |

**Notes on Above Table:** 
Training durations are rounded to the nearest whole minute. Memory includes all 5 epochs and files saved to local hard drive.

**Conclusion:** 
- ELECTRA was the quickest project to train, even faster than DistilBERT, but had the lowest accuracy.
- Even though ERNIE was slightly more accurate, it took more than three times as long to train.
- The difference in accuracy of the best performing model was only three (3) percent better than the worst performing model.
- Given these results, it looks like distilbert is still the transformer to use for smaller projects like this!
