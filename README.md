<div align='center'>
    <h1>
        Natural Language Processing
    </h1>

<p>
    This repository houses Natural Language Processing (NLP) projects that I have completed (other than projects completed using Spark & Databricks).
</p>

<h2>
    HuggingFace Profile
</h2>

<p>
    To view and use the models, travel over my HuggingFace portfolio: <a href="https://huggingface.co/DunnBC22">huggingface.co/DunnBC22</a>
</p>

<h2>
    Text Classification
</h2>

<details open>
<summary>Multiclass Classification</summary>

| Project Name | Model Checkpoint | Accuracy | Macro F1 Score | Macro Precision | Macro Recall |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [Apple iPhone SE Reviews*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Apple%20iPhone%20SE%20Reviews/Apple%20IPhone%20Reviews%20-%20MC%20CLF%20-%20Bert-Base.ipynb) | `bert-base-uncased` | 0.9712 | 0.9561 | 0.9538 | 0.9598 |
| [Apple iPhone SE Reviews*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Apple%20iPhone%20SE%20Reviews/Apple%20IPhone%20Reviews%20-%20MC%20CLF%20-%20MPNet.ipynb) | `microsoft/mpnet-base` | 0.9460 | 0.7242 | 0.7007 | 0.7594 |
| [CNN News Articles](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/CNN%20News%20Articles/Multiclass_Classification%20of%20News%20Articles-CNN%20News.ipynb) | `distilbert-base-uncased` | 0.9643 | 0.9640 | - | - |
| [Hate & Offensive Speech*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Transformer%20Comparison/Hate%20%26%20Offensive%20Speech%20-%20BERT.ipynb) | `bert-base-uncased` | 0.9213 | 0.9161 | 0.9241 | 0.9144 |
| [Hate & Offensive Speech*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Transformer%20Comparison/Hate%20%26%20Offensive%20Speech%20-%20BERT-Large.ipynb) | `bert-large-uncased` | 0.9869 | 0.9863 | 0.987 | 0.9857 |
| [Hate & Offensive Speech*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Transformer%20Comparison/Hate%20%26%20Offensive%20Speech%20-%20DistilBERT.ipynb) | `distilbert-base-uncased` | 0.9607 | 0.9592 | 0.9613 | 0.9579 |
| [Hate & Offensive Speech*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Transformer%20Comparison/Hate%20%26%20Offensive%20Speech%20-%20fBERT.ipynb) | `diptanu/fBERT` | 0.9607 | 0.9581 | 0.9596 | 0.9571 |
| [Hate & Offensive Speech*](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Transformer%20Comparison/Hate%20%26%20Offensive%20Speech%20-%20hateBERT.ipynb) | `GroNLP/hateBERT`| 0.941 | 0.9351 | 0.951 | 0.9273 |
| [Password Strength](https://github.com/DunnBC22/NLP_Projects/blob/main/Password%20Strength%20Classification%20(MC)/CodeBERT-Base%20-%20Password_Classifier.ipynb) | `microsoft/codebert-base` | 0.9975 | 0.9963 | 0.9948 | 0.9978 |
| [Malicious URLs](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Malicious%20URLs/Malicious%20URLs%20-%20CodeBERT.ipynb) | `microsoft/codebert-base`| 0.7279 | 0.4611 | 0.5436 | 0.4422 |
| [Malicious URLs](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Malicious%20URLs/Malicious_URLs_CodeBERT-mlm.ipynb) | `microsoft/codebert-base-mlm`| 0.7322 | 0.4303 | 0.6034 | 0.4233 |
| [Malicious URLs](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Malicious%20URLs/Malicious_URLs_DeBERTa.ipynb) | `microsoft/deberta-base-mnli`| 0.7353 | 0.4533 | 0.5684 | 0.4315 |
| [Malicious URLs (Using PEFT)](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiclass%20Classification/Malicious%20URLs/PEFT_Malicious_URLs_Roberta_Large_Chkpt.ipynb) | `roberta-large`| 0.7160 | 0.4374 | 0.5237 | 0.4190 |


</details>

<details>
<summary>Binary Classification</summary>

| Project Name | Transformer Checkpoint | Accuracy | F1 Score | Precision | Recall |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [Malignant Comments - BERT-Base*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Malignant%20Comments/Malignant%20Comments%20-%20BERT-Base.ipynb) | `bert-base-uncased` | 0.972 | 0.759 | 0.6918 | 0.8406 |
| [Malignant Comments - I-BERT*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Malignant%20Comments/Malignant%20Comments%20-%20I-BERT.ipynb) | `kssteven/ibert-roberta-base` | 0.9741 | 0.7773 | 0.7084 | 0.861 |
| [Mental Health Classification](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Mental%20Health%20Classification/CANINE%20-%20Mental%20Health%20Classification.ipynb) | `google/canine-c` | 0.9226 | 0.9096 | 0.9113 | 0.9079 |
| [OnionOrNot](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/OnionOrNot/DunnBC22-distilbert-base-uncased-OnionOrNot.ipynb) | `distilbert-base-uncased` | 0.9224 | 0.9218 | - | - |
| [Spam Filter (Larger Dataset)](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Spam%20Filter-%20Larger%20Dataset/DunnBC22-distilbert-base-uncased-SpamFilter-LG.ipynb) | `distilbert-base-uncased` | 0.9845 | 0.9848 | - | - |
| [Spam Filter (Smaller Dataset)](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Spam%20Filter%20-%20Smaller%20Dataset/DunnBC22-distilbert-base-uncased-SpamFilter-sm.ipynb) | `distilbert-base-uncased` | 0.9907 | 0.9906 | - | - |
| [Tweet About a Disaster or Not? - ALBERT*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Transformer%20Comparison/Is%20This%20Tweet%20Referring%20to%20a%20Disaster%20or%20Not%3F%20-%20ALBERT.ipynb) | `albert-base-v2` | 0.9138 | 0.7752 | 0.8204 | 0.7348 |
| [Tweet About a Disaster or Not? - DeBERTa*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Transformer%20Comparison/Is%20This%20Tweet%20Referring%20to%20a%20Disaster%20or%20Not%3F%20-%20DeBERTa.ipynb) | `microsoft/deberta-v3-small` | 0.9050 | 0.7453 | 0.7453 | 0.7453 |
| [Tweet About a Disaster or Not? - DistilBERT*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Transformer%20Comparison/Is%20This%20Tweet%20Referring%20to%20a%20Disaster%20or%20Not%3F%20-%20DistilBERT.ipynb) | `distilbert-base-uncased` | 0.9138 | 0.7752 | 0.8204 | 0.7348 |
| [Tweet About a Disaster or Not? - ERNIE*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Transformer%20Comparison/Is%20This%20Tweet%20Referring%20to%20a%20Disaster%20or%20Not%3F%20-%20ERNIE.ipynb) | `nghuyong/ernie-2.0-base-en` | 0.9156 | 0.7876 | 0.8436 | 0.7386 |
| [Tweet About a Disaster or Not? - ELECTRA*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Transformer%20Comparison/Is%20This%20Tweet%20Referring%20to%20a%20Disaster%20or%20Not%3F%20-%20ELECTRA.ipynb) | `bhadresh-savani/electra-base-emotion` | 0.8857 | 0.7246 | 0.7991 | 0.6628 |
| [Tweet About a Disaster or Not? - RoBERTa*](https://github.com/DunnBC22/NLP_Projects/blob/main/Binary%20Classification/Transformer%20Comparison/Is%20This%20Tweet%20Referring%20to%20a%20Disaster%20or%20Not%3F%20-%20RoBERTa.ipynb) | `roberta-base` | 0.8989 | 0.7569 | 0.8211 | 0.7020 |
</details>

<details>
<summary> Multilabel Classification</summary>

| Project Name| Model Checkpoint | Subset Accuracy | F1 Score | ROC-AUC |
| :---: | :---: | :---: | :---: | :---: | 
| [Go Emotions](https://github.com/DunnBC22/NLP_Projects/blob/main/Multilabel%20Classification/GoEmotions/GoEmotions%20-%20Multilabel%20clf.ipynb) | `distilbert-base-uncased` | 0.2184 | 0.3328 | 0.6102 |
| [Research Articles](https://github.com/DunnBC22/NLP_Projects/blob/main/Multilabel%20Classification/Research%20Articles/Research%20Articles-Multilabel%20clf.ipynb) | `distilbert-base-uncased` | 0.6977 | 0.8395 | 0.8909 |
| [Review Sentiments (with DistilBert)](https://github.com/DunnBC22/NLP_Projects/blob/main/Multilabel%20Classification/Review%20Sentiments/Sentiments%20-%20Multilabel%20clf.ipynb) | `distilbert-base-uncased` | 0.5787 | 0.8697 | 0.9107 |
| [Review Sentiments (with Bert)](https://github.com/DunnBC22/NLP_Projects/blob/main/Multilabel%20Classification/Review%20Sentiments/Sentiment_Analysis%20-%20Using%20BERT%20Instead%20of%20DistilBERT.ipynb) | `bert-base-uncased` | 0.5967 | 0.8737 | 0.9146 |
</details>

<details>
<summary>Token Classification</summary>

| Project Name | Overall Accuracy | Overall F1 Score | Overall Precision | Overall Recall | 
| :---: | :---: | :---: | :---: | :---: |
| [BC2GM-IOB (EMBO-BLURB)](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/EMBO-BLURB/NER%20Project%20Using%20EMBO-BLURB%20Dataset.ipynb) | 0.9736 | 0.7765 | 0.7521 | 0.8025 |
| [EMBO-BLURB with LoRA](https://github.com/DunnBC22/NLP_Projects/tree/main/Token%20Classification/Monolingual/EMBO-SourceData%20with%20LoRA) | 0.9584 | 0.8136 | 0.7999 | 0.8278 |
| [DFKI-SLT/few-nerd](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/DFKI%20SLT%20few%20NERd/NER_Project_Using_DFKI_SLT_few_NERd_Dataset.ipynb) | 0.9498 | 0.8041 | 0.8203 | 0.7886 |
| [NCBI Disease](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/NCBI_Disease/NER%20Project%20Using%20NCBI_Disease%20Dataset.ipynb) | 0.9825 | 0.8359 | 0.8064 | 0.8677 |
| [TNER Bio NLP 2004](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/tner-bionlp2004/NER%20Project%20Using%20tner-bionlp%202004%20Dataset%20(BERT-Base).ipynb) | 0.9367 | 0.7169 | 0.6628 | 0.7805 |
| [Stromberg NLP - Twitter (SeqEval)](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/StrombergNLP-Twitter_pos_vcb/NER%20Project%20Using%20StrombergNLP%20Twitter_pos_vcb%20Dataset.ipynb) | 0.9860 | 0.9824 | 0.9828 | 0.9820 |
| [Stromberg NLP - Twitter PoS_v2](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/StrombergNLP-Twitter_pos_vcb/NER%20Project%20Using%20StrombergNLP%20Twitter_pos_vcb%20Dataset%20with%20PosEval.ipynb) | 0.9853 | 0.8931 | 0.9296 | 0.8931 |
| [Stromberg NLP - Twitter PoS (SqueezeBERT Transformer)](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/StrombergNLP-Twitter_pos_vcb/NER%20Project%20Using%20StrombergNLP%20Twitter_pos_vcb%20Dataset%20with%20PosEval%20%26%20SqueezeBERT.ipynb) | 0.9771 | 0.7765 | 0.8046 | 0.7785 |
| [WikiNeural - BERT-Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20BERT-Base%20Transformer.ipynb) | 0.9912 | 0.9145 | 0.9380 | 0.9261 |
| [WikiNeural - Amazon's BORT](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20BORT%20Transformer.ipynb) | 0.9709 | 0.7050 | 0.7868 | 0.7437 |
| [WikiNeural - FNet-Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20FNet%20Transformer.ipynb) | 0.8521 | 0.8934 | 0.8722 | 0.9853 |
| [WikiNeural - Funnel Transformer](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20Funnel%20Transformer.ipynb) | 0.9856 | 0.8722 | 0.9102 | 0.8908 |
| [WikiNeural - I-BERT-Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20I-BERT%20Transformer.ipynb) | 0.9909 | 0.9107 | 0.9360 | 0.9232 |
| [WikiNeural - MEGA-Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20MEGA%20Transformer.ipynb) | 0.9619 | 0.6312 | 0.7324 | 0.6781 |
| [WikiNeural - RoBERTa-Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20Roberta-Base%20Transformer.ipynb) | 0.9910 | 0.9124 | 0.9352 | 0.9237 |
| [WikiNeural - SqueezeBERT](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20SqueezeBERT%20Transformer.ipynb) | 0.9803 | 0.8278 | 0.8866 | 0.8562 |
| [WikiNeural - XLNet-Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Token%20Classification/Monolingual/WikiNeural%20-%20Transformer%20Comparison/POS%20Project%20with%20Wikineural%20Dataset%20-%20XLNet%20Transformer.ipynb) | 0.9904 | 0.9068 | 0.9324 | 0.9194 |
</details>

<details>
<summary>Sentiment Analysis</summary>

| Project Name | Model Checkpoint | Accuracy | Macro F1 Score | Macro Precision | Macro Recall |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [Emotions Sentiment Analysis](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Emotions%20Sentiment%20Analysis/Emotions%20Sentiment%20Analysis%20Project.ipynb) | `distilbert-base-uncased` | 0.935 | 0.935 | - | - |
| [Financial Sentiment Analysis - Original](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Financial%20Sentiment%20Analysis/Financial%20Sentiment%20Analysis-Original%20Version.ipynb) | `distilbert-base-uncased` | 0.8425 | 0.8470 | - | - |
| [Financial Sentiment Analysis - Updated (v1.5)](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Financial%20Sentiment%20Analysis/Financial%20Sentiment%20Analysis-Updated%20Version.ipynb) | `distilbert-base-uncased` | 0.8529 | 0.8564 | - | - |
| [Financial Sentiment Analysis_v2](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Financial%20Sentiment%20Analysis/Financial_Sentiment_Analysis_v2.ipynb) | `google/fnet-base` | 0.8117 | 0.7472 | 0.7588 | 0.7394 |
| [Financial Sentiment Analysis_v3](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Financial%20Sentiment%20Analysis/Financial_Sentiment_Analysis_v3.ipynb) | `google/fnet-large` | 0.8618 | 0.8209 | 0.8084 | 0.8401 |
| [News About Gold - BORT*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20BORT%20with%20W%26B.ipynb) | `amazon/bort` | 0.8770 | 0.7791 | 0.8463 | 0.7539 |
| [News About Gold - BERT-Base*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20Bert-Base%20with%20W%26B.ipynb) | `bert-base-uncased` | 0.9139 | 0.8758 | 0.8885 | 0.8647 |
| [News About Gold - Funnel*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20Funnel%20with%20W%26B.ipynb) | `funnel-transformer/medium-base` | 0.9172 | 0.8854 | 0.8853 | 0.8859 |
| [News About Gold - MEGA*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20MEGA%20with%20W%26B.ipynb) | `mnaylor/mega-base-wikitext` | 0.5014 | 0.3283 | 0.4548 | 0.3835 |
| [News About Gold - MPNet-Base*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20MPNet-Base%20with%20W%26B.ipynb) | `microsoft/mpnet-base` | 0.9068 | 0.8351 | 0.831 | 0.8406 |
| [News About Gold - SqueezeBERT*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20SqueezeBERT%20with%20W%26B.ipynb) | `squeezebert/squeezebert-uncased` | 0.9168 | 0.8749 | 0.8822 | 0.8684 |
| [News About Gold - YOSO*](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20of%20Commodity%20News%20-%20Gold%20(Transformer%20Comparison)/News%20About%20Gold%20-%20Sentiment%20Analysis%20-%20YOSO%20with%20W%26B.ipynb) | `uw-madison/yoso-4096` | 0.4456 | 0.2272 | 0.3240 | 0.2912 |
| [Twitter Sentiment Analysis](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Twitter%20Sentiment%20Analysis/Twitter%20US%20Airlines%20Sentiment%20Analysis.ipynb) | `distilbert-base-uncased` | 0.8466 | 0.8471 | - | - |
| [Twitter Sentiment Analysis_v2](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Twitter%20Sentiment%20Analysis/Twitter%20Sentiment%20Analysis_v2.ipynb) | `bert-base-uncased` | 0.8474 | 0.788 | 0.8132 | 0.7747 |
| [Twitter Sentiment Analysis_v3](https://github.com/DunnBC22/NLP_Projects/blob/main/Sentiment%20Analysis/Twitter%20Sentiment%20Analysis/Twitter%20Sentiment%20Analysis_v3%20(Roberta).ipynb) | `vinai/bertweet-base` | 0.8588 | 0.8151 | 0.8463 | 0.7961 |

* Metrics are Macro Averaged version only if all 4 metric values are displayed (accuracy, f1-score, recall, and precision).
</details>
    
<details>
<summary>Language Detection</summary>

| Project Name| Accuracy | Macro F1 Score | Macro Precision | Macro Recall |
| :---: | :---: | :---: | :---: | :---: |
| [Language Detection of Tweets](https://github.com/DunnBC22/NLP_Projects/blob/main/Language%20Detection/Language%20Detection%20of%20Tweets/Language%20Detection%20of%20Tweets.ipynb) | 0.9992 | 0.9992 | 0.9992 | 0.9992 |
| [Language Detection- 10k](https://github.com/DunnBC22/NLP_Projects/blob/main/Language%20Detection/Language%20Detection-%2010k%20Samples/language_detection-10k.ipynb) | 0.9971 | 0.9977 | 0.9981 | 0.9974 |
| [Language Detection-20k](https://github.com/DunnBC22/NLP_Projects/blob/main/Language%20Detection/Language%20Detection-20k%20Samples/language_detection-20k.ipynb) | 0.9883 | 0.9882 | 0.9887 | 0.9879 |
</details>

<details>
<summary>Semantic Similarity</summary>

| Project Name| Accuracy | F1 Score | Precision | Recall | Average Precision |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [Semantic Similarity of Quora Pairs Dataset - Base](https://github.com/DunnBC22/NLP_Projects/blob/main/Semantic_Similarity/Semantic%20Similarity-base.ipynb) | 85.93 | 82.89 | 77.43 | 89.18 | 87.13 |
| [Semantic Similarity of Quora Pairs Dataset - Large](https://github.com/DunnBC22/NLP_Projects/blob/main/Semantic_Similarity/Semantic%20Similarity-large.ipynb) | 88.72 | 85.22 | 80.72 | 90.25 | 89.75 |

* Metrics shown for Semantic Similarity are measured using Cosine-Similarity.
</details>

<br />

<h2>
    Text Generation/Multiple Choice/Question&Answer
</h2>

<details>
<summary>Text Summarization</summary>

| Project Name | Rouge1 | Rouge2 | RougeL | RougeLsum |
| :---: | :---: | :---: | :---: | :---: |
| [Flan-T5 - Text Summarization-Data Dataset (1 Epoch)](https://github.com/DunnBC22/NLP_Projects/blob/main/Text%20Summarization/Text-Summarized%20Data%20-%20Comparison/Flan-T5%20-%20Text%20Summarization%20-%201%20Epoch.ipynb) | 43.6615 | 20.349 | 40.1032 | 40.1589 |
| [Flan-T5 - Text Summarization-Data Dataset (6 Epochs)](https://github.com/DunnBC22/NLP_Projects/blob/main/Text%20Summarization/Text-Summarized%20Data%20-%20Comparison/Flan-T5%20-%20Text%20Summarization%20-%206%20Epochs.ipynb) | 43.5994 | 0.4446 | 40.132 | 40.1692 |
| [LED - Text Summarization-Data Dataset (4 Epochs)](https://github.com/DunnBC22/NLP_Projects/blob/main/Text%20Summarization/Text-Summarized%20Data%20-%20Comparison/LED%20-%20Text%20Summarization%20-%204%20Epochs.ipynb) | 43.3689 | 19.9885 | 39.9887 | 40.0679 |
| [CNN News Text Summarization](https://github.com/DunnBC22/NLP_Projects/blob/main/Text%20Summarization/CNN%20News%20Text%20Summarization/CNN%20News%20Text%20Summarization.ipynb) | 0.834343 | 0.793822 | 0.823824 | 0.823778 |
| [Text Summarization BBC News (with Pegasus Transformer)](https://github.com/DunnBC22/NLP_Projects/blob/main/Text%20Summarization/BBC%20News%20Text%20Summarization/Text_Summarization_BBC_News-Pegasus.ipynb) | 0.584474 | 0.463574 | 0.408729 | 0.408431 |
</details>

<details>
<summary>Machine Translation</summary>

| Project Name | Bleu | Rouge1 | Rouge2 | RougeL | RougeLsum | Meteor |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| [English to French](https://github.com/DunnBC22/NLP_Projects/blob/main/Machine%20Translation/NLP%20Translation%20Project-EN%20to%20FR/NLP%20Translation%20Project-EN_FR.ipynb) | 35.1914 | 0.6420 | 0.4573 | 0.6070 | 0.6069 | 0.5917 |
| [English to German](https://github.com/DunnBC22/NLP_Projects/blob/main/Machine%20Translation/NLP%20Translation%20Project-EN%20to%20DE/NLP%20Translation%20Project-EN_DE.ipynb) | 35.5931 | 0.5803 | 0.3939 | 0.5439 | 0.5442 | 0.55 |
| [English to Spanish](https://github.com/DunnBC22/NLP_Projects/blob/main/Machine%20Translation/NLP%20Translation%20Project-EN%20to%20ES/NLP%20Translation%20Project-EN_ES.ipynb) | 41.4437 | 0.6751 | 0.4977 | 0.6372 | 0.6376 | 0.6479 |
| [BioMedical EN to IT Translation](https://github.com/DunnBC22/NLP_Projects/blob/main/Machine%20Translation/Biomedical%20Translation%20(EN%20to%20IT)/Biomedical%20-%20Translation%20Project.ipynb) | 38.9893 | 0.6826 | 0.4737 | 0.6586 | 0.6585 | 0.6270 |
</details>

<details>
<summary>Question & Answer</summary>

| Project Name | Exact Match | F1 Score |
| :---: | :---: | :---: |
| [ML QA](https://github.com/DunnBC22/NLP_Projects/blob/main/Question%26Answer/ML%20QA/ML_QA_Question%26Answer_with_BERT.ipynb) | 59.6146 | 73.3002 |
| [Answer Prediction Dataset](https://github.com/DunnBC22/NLP_Projects/blob/main/Question%26Answer/Question%20Answer%20Dataset/Answer%20Prediction%20Dataset%20-%20Question%26Answer%20with%20BERT.ipynb) | 65.7357 | 79.2835 |
</details>

<details>
<summary>Generate Docstrings</summary>

| Project Name | Model Checkpoint | Rouge1 | Rouge2 | RougeL | RougeLsum |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [CodeSearchNet Dataset to Generate Docstrings (Code T5 Project)](https://github.com/DunnBC22/NLP_Projects/blob/main/Generate%20Docstrings/Code%20Search%20Net%20Dataset%20-%20Small%20Checkpoint/Code_T5_Project.ipynb) | `Salesforce/codet5-small` | 0.3381 | 0.1541 | 0.3045 | 0.3214 |
| [Smol Dataset to Generate Docstrings](https://github.com/DunnBC22/NLP_Projects/blob/main/Generate%20Docstrings/Smol%20Dataset%20-%20Base%20Checkpoint/Code_T5_Project-Base%20Checkpoint.ipynb) | `Salesforce/codet5-base` | 0.4947 | 0.3661 | 0.4794 | 0.4791 |
| [Smol Dataset to Generate Docstrings](https://github.com/DunnBC22/NLP_Projects/blob/main/Generate%20Docstrings/Smol%20Dataset%20-%20Small%20Checkpoint/Code_T5_Project-Small%20Checkpoint.ipynb) | `Salesforce/codet5-small` | 0.38 | 0.2176 | 0.3554 | 0.3635 |
</details>

<details>
<summary>Multiple Choice</summary>

| Project Name | Accuracy |
| :---: | :---: |
| [CosmosQA](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/CosmosQA/CosmosQA%20-%20Multiple%20Choice%20Using%20BERT.ipynb) | 0.6000 |
| [Social IQa](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/Social%20IQa/Social%20IQa%20-%20Multiple%20Choice.ipynb) | 0.6128 |
| [Discourse Marker QA](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/Discourse%20Marker%20QA/Discourse_Marker_QA_Multiple_Choice_Using_BERT.ipynb) | 0.6207 |
| [Figurative Language](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/Figurative%20Language/Figurative%20Language%20-%20Multiple%20Choice%20Using%20BERT.ipynb) | 0.8124 |
| [Strategy QA](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/Strategy%20QA/Strategy%20QA%20-%20Multiple%20Choice%20Using%20BERT.ipynb) | 0.625 |
| [e-CARE](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/e-CARE/e_CARE_Multiple_Choice_Using_BERT.ipynb) | 0.7212 |
| [Vitamin C Fact Verification](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/Vitamin%20C%20Fact%20Verification/Vitamin_C_Fact_Verification_Multiple_Choice_Using_BERT.ipynb) | 0.7240 |
| [Winowhy](https://github.com/DunnBC22/NLP_Projects/blob/main/Multiple%20Choice/Winowhy/Winowhy%20-%20Multiple%20Choice%20Using%20BERT.ipynb) | 0.7118 |

</details>
 
<br />

<h2>
    NLP Regression
</h2>
<details>
<summary>NLP Regression</summary>

| Project Name | Mean Squared Error (MSE) | Root Mean Squared Error (RMSE) | Mean Absolute Error (MAE) |
| :---: | :---: | :---: | :---: |
| [Edmunds Car Reviews - All Brands (with Bert-Base)](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Edmunds%20Car%20Reviews%20(BERT-Base)/Edmunds_Consumer_car_Regression_All_Manufacturers_Bert_Base.ipynb) | 0.2324 | 0.4820 | 0.3089 |
| [Edmunds Car Reviews - All Brands](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Edmunds%20Car%20Reviews%20(All%20Brands)/Edmunds_Consumer_car-Regression-All%20Manufacturers.ipynb) | 0.2232 | 0.4724 | 0.3150 |
| [Edmunds Car Reviews - Brands Headquartered in America](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Edmunds%20Car%20Reviews%20(American)/HF-Edmunds_Consumer_car-Regression-American.ipynb) | 0.2486 | 0.4986 | 0.3469 |
| [Edmunds Car Reviews - Brands Headquartered in Europe](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Edmunds%20Car%20Reviews%20(European)/HF-Edmunds_Consumer_car-Regression-European.ipynb) | 0.1999 | 0.4471 | 0.2824 |
| [Edmunds Car Reviews - Brands Not Headquartered in America or Europe](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Edmunds%20Car%20Reviews%20(Non%20European%20Imports)/HF-Edmunds_Consumer_car-Regression-Non_European_Imports.ipynb) | 0.2240 | 0.4733 | 0.3140 |
| [Episode Reviews/Rating - The Simpsons](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Simpsons%20Episode%20Descriptions/NLP%20Regression%20-%20The%20Simpsons.ipynb) | 0.7632 | 0.8736 | 0.6622 |
| [Episode Reviews/Rating - The Simpsons & Other TV Shows](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/Descriptions%20of%20Simpsons%20Episodes%20%26%20Other%20TV%20Shows/NLP%20Regression%20-%20Simpsons%20Plus%20Other%20Series.ipynb) | 0.3754 | 0.6127 | 0.4651 |
| [TMDB 5000 Move Dataset](https://github.com/DunnBC22/NLP_Projects/blob/main/NLP%20Regression/TMDB%205000%20Movie%20Descriptions/NLP%20Regression%20-%20TMDB%205000%20Movie%20Dataset%20-%20Original.ipynb) | 0.7613 | 0.8725 | 0.6848 |
</details>

<br />

<h2>
    Language Modeling
</h2>

<details>
<summary>Causal Language Modeling</summary>

| Project Name | Perplexity |
| :---: | :---: |
| [2000 Clean Medical Articles](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20Language%20Modeling/2000%20Clean%20Medical%20Articles/2%2C000%20Clean%20Medical%20Articles%20-%20CLM.ipynb) | 18.67 |
| [AG News (DistilGPT2 Version)](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20Language%20Modeling/AG%20News/DistilGPT2%20Version/DistilGPT2%20-%20AG_News_CLM.ipynb) | 31.53 |
| [AG News (GPT2 Version)](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20Language%20Modeling/AG%20News/GPT2%20Version/GPT2%20-%20AG_News_CLM.ipynb) | 22.92 |
| [US Economic News Articles](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20Language%20Modeling/US%20Economic%20News%20Articles/US%20Economic%20News%20Articles%20-%20CLM.ipynb) | 31.41 |
</details>

<details>
<summary>Causal Language Modeling for Chatbot</summary>

| Project Name | Perplexity |
| :---: | :---: |
| [Large Company's FAQs (Medium) v1](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20LM%20for%20Chatbot/Company%20FAQs/v1/FAQs%20-%20CLM%20for%20DialoGPT%20Chatbot%20-%20Medium.ipynb) | 8.67 |
| [Large Company's FAQs (Large) v1](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20LM%20for%20Chatbot/Company%20FAQs/v1/FAQs%20-%20CLM%20for%20DialoGPT%20Chatbot-DialoGPT-Large_v1.ipynb) | 2.79 |
| [Large Company's FAQs v2](https://github.com/DunnBC22/NLP_Projects/blob/main/Causal%20LM%20for%20Chatbot/Company%20FAQs/v2/FAQs%20-%20CLM%20for%20DialoGPT%20Chatbot-DialoGPT-Large_v2.ipynb) | 1.70 |
</details>

<details>
<summary>Masked Language Modeling</summary>

| Project Name | Perplexity |
| :---: | :---: |
| [AG News](https://github.com/DunnBC22/NLP_Projects/blob/main/Masked%20Language%20Model/AG%20News/AG_News_MLM.ipynb) | 5.95 |
| [Reddit Comments](https://github.com/DunnBC22/NLP_Projects/blob/main/Masked%20Language%20Model/Datasets%20for%20NLP%20-%20Reddit%20Comments/Datasets_for_NLP_MLM.ipynb) | 12.70 |
| [US Economic News Articles](https://github.com/DunnBC22/NLP_Projects/blob/main/Masked%20Language%20Model/US%20Economic%20News%20Articles/US_Economic_News_Articles_MLM.ipynb) | 6.25 |
</details>

</div>

<hr />

Footnotes:

<ul>
    <li>The output format for rouge was changed somewhere along the way of training all of these projects. As a result, rouge metric values under 1 should be multiplied by 100 to accurately compare to the values over 1.</li>
    <li>PoS stands for Part of Speech.</li>
    <li>Projects that are apart of transformer comparisons using the same dataset are denoted with an asterisk (*) at the end of their project name.</li>
</ul>
