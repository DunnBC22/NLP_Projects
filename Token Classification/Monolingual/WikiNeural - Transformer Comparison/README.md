<div style="text-align: center">
<h1>
    Token Classification Transformer Comparison
</h1>

<p>
    For this comparison, I chose about a dozen transformers to find the optimal transformer for a Token Classification/Named Entity Recognition Dataset.
</p>

<h2>
    HuggingFace Profile/Portfolio
</h2>
<a href="https://huggingface.co/DunnBC22">
    Brian Dunn's HuggingFace Profile/Portfolio
    </a>

<h2>
    Dataset Images
</h2>

<h3>
    Histogram of Input Token Lengths
</h3>

<img src="Images/Input Token Lengths.png" />

<h3>Bar Plot of Classes (Initial)</h3>

<img src="Images/Tag Classification (Initial).png" />

<h3>
    Bar Plot of Classes (Without 'O')
</h3>

<img src="Images/Tag Classification (Without O).png" />

<h3>
    Project Constants
</h3>

| Parameter | Value |
| ---------: | :--------- |
| Dataset | [WikiNeural](https://huggingface.co/datasets/Babelscape/wikineural) |
| # of Epochs | 2 | 
| Batch Size | 16 |
| Processor Type | CPU |
| Learning Rate | 2e-5 |
| Weight Decay | 0.01 |

<h3>
    Results
</h3>

| Project Link | Transformer Checkpoint Used | Memory (GB) | Training Duration (Minutes) | Accuracy | Evaluation Precision | Evaluation Recall | Evaluation F1-Score |
| :-------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: |
| [![X](Images/checkmark.png "bert-base-cased")]() | [`bert-base-cased`](https://huggingface.co/bert-base-cased) | 3.45 | 773 | 0.9912 | 0.9145 | 0.9380 | 0.9261 |
| [![X](Images/checkmark.png "amazon/bort")]() | [`amazon/bort`](https://huggingface.co/amazon/bort) | 2.42 | 249 | 0.9709 | 0.7050 | 0.7868 | 0.7437 |
| [![X](Images/checkmark.png "google/fnet-base")]() | [`google/fnet-base`](https://huggingface.co/google/fnet-base) | 2.65 | 568 | 0.9853 | 0.8521 | 0.8934 | 0.8722 |
| [![X](Images/checkmark.png "funnel-transformer/medium")]() | [`funnel-transformer/medium`](https://huggingface.co/funnel-transformer/medium) | 4.20 | 939 | 0.9856 | 0.8722 | 0.9102 | 0.8908 |
| [![X](Images/checkmark.png "kssteven/ibert-roberta-base")]() | [`kssteven/ibert-roberta-base`](https://huggingface.co/kssteven/ibert-roberta-base) | 5.97 | 803 | 0.9909 | 0.9107 | 0.9360 | 0.9232 |
| [![X](Images/checkmark.png "mnaylor/mega-base-wikitext")]() | [`mnaylor/mega-base-wikitext`](https://huggingface.co/mnaylor/mega-base-wikitext) | 0.2462 | 57 | 0.9619 | 0.6312 | 0.7324 | 0.6781 |
| [![X](Images/checkmark.png "roberta-base")]() | [`roberta-base`](https://huggingface.co/roberta-base) | 3.98 | 794 | 0.9910 | 0.9124 | 0.9352 | 0.9237 |
| [![X](Images/checkmark.png "squeezebert/squeezebert-uncased")]() | [`squeezebert/squeezebert-uncased`](https://huggingface.co/squeezebert/squeezebert-uncased) | 1.63 | 506 | 0.9803 | 0.8278 | 0.8866 | 0.8562 |
| [![X](Images/checkmark.png "xlnet-base-cased")]() | [`xlnet-base-cased`](https://huggingface.co/xlnet-base-cased)]() | 3.75 | 1081 | 0.9904 | 0.9068 | 0.9324 | 0.9194 |

<h3>
    Conclusions
</h3>

</div>

<ul>
    <li>
        Despite much shorter training durations, both BORT and MEGA performed poorly (as expected).
    </li>
    <li>
        Although BERT, RoBERTa, I-BERT, and XLNet all performed very well and had very similar metrics, the best transformer for this model is between BERT and RoBERTa. While BERT's performance was a sliver better, when you compare the Confusion Matrix for each you notice that it truly comes down to which individual token class is more important to you.
    </li>
    <li>
        To keep my HuggingFace portfolio tidy, I am going to remove the following projects:
        <ol>
            <li>amazon/bort</li>
            <li>google/fnet-base</li>
            <li>funnel-transformer/medium</li>
            <li>mnaylor/mega-base-wikitext</li>
            <li>squeezebert/squeezebert-uncased</li>
        </ol>
    </li>
</ul>

