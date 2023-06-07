# Transformer Comparison Using Sentiment Analysis of Gold Dataset (Multiclass Classification)

The purpose of this project was to train **_seven (7)_** different Transformers (mainly Encoder-only transformers) on the same dataset to see which one is the most efficient and effective. All projects are the same with the exception of both the transformer and (potentially) the length of the tokenized input.

**Further Details on Methodology:** I trained each model for 5 epochs.

**Dataset Name:** Sentiment Analysis of Commodity News (Gold)

**Dataset Source:** https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-in-commodity-market-gold

## Results

| Transformer Model | Checkpoint  | Training Duration (Min) | Memory (GB) |  Loss  | Accuracy |  F1  | Recall | Precision |
| :--------------:  | :---------------------: | :---------------: | :--------: | :-------: | :-------: | :-------: | :-------: | :-------: |
| **Bert (Base)**   | `bert-base-uncased`   |      101     |   7.45    | 0.1196 |  0.91391  | 0.87584 | 0.86468 |   0.8885  |
| **BORT**          | `amazon/bort`           |  43  |  5.2  | 0.37912 |  0.87701  | 0.77907 | 0.75389 |   0.8463  |
| **Funnel**        | `funnel-transformer/medium-base` | 111 | 7.91 | 0.28383 | 0.91722 | 0.88541 | 0.88592 | 0.88534 |
| **MEGA**          | `mnaylor/mega-base-wikitext` |    5    | 0.5215  | 1.0031 | 0.50142 |  0.32825  | 0.38348 | 0.4548 |
| **MPNet**         | `microsoft/mpnet-base`   |  108   | 7.45  |   0.30983 |  0.90681  | 0.83509 | 0.84056 |   0.83095  |
| **SqueezeBERT**   | `squeezebert/squeezebert-uncased` |  52  |  3.48  | 0.26429 |  0.91675  | 0.87494 | 0.86843 |   0.88219  |
| **YOSO**          | `uw-madison/yoso-4096`       |  105  |  8.69  | 1.09605 |  0.4456  | 0.22721 | 0.29124 |   0.32402  |

**Notes on Above Table** 
- Training durations are approximate because at times I trained two projects at the same time. Additionally, times are rounded to the nearest whole minute. They are just meant to be a relative idea of durations.
- Memory includes all 5 epochs and files saved to local hard drive.
- F1, Recall, and Precision are the **macro averaged** version for each of those calculations.

**Conclusion**
- The fastest model to train was the MEGA model, but it had the worst results. That said, with just how fast it was, one could train it for 25 epochs (instead of 5) and still have plnty of extra time.
- Bert, Funnel, and SqueezeBERT had very similar metrics and lead the comparison. SqueezeBERT trained the project in about half the time as BERT and is one that I will keep in mind for future projects.
- The most disappointing model was the YOSO (You Only Sample (almost) Once). It lagged behind all of the other models for metrics, required more memory and was one of the slowest models to train. MEGA produced better results than YOSO, and it took less than five (5) percent as much time to do so.