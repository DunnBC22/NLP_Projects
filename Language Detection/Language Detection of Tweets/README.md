<h1 align='center'>
    Language Detection of Tweets
</h1>

<h2 align='center'>
    <strong>
        Project Purpose
    </strong>
</h2>

<p align='center'>
    The purpose of this project was to detect the language of the tweets. There are three (3) different languages included in this dataset (French, Darija, and English). The checkpoint used was the <strong><em>distilbert-base-multilingual-cased</em></strong> and it ran for <strong><em>three (3) epochs</em></strong> on a <strong><em>CPU</em></strong>. The datasest includes <strong><em>over 13,000 samples</em></strong>.
</p>

<hr />

<h2 align='center'>
    <strong>
        Dataset Name & Source Link
    </strong>
</h2>

<p align='center'>
    <a href='https://www.kaggle.com/datasets/lailaboullous/language-detection-dataset'>
        Language Detection Dataset
    </a>
</p>

<hr />

<h2 align='center'>
    <strong>
        Histogram of Input Text Lengths (in Words)
    </strong>
</h2>

<p align='center'>
    <img src="./Images/Input Word Length.png" alt="Input Word Lengths" height=320 width=650>
</p>

<h2 align='center'>
    <strong>
        Histogram of Input Text Lengths (in Words) By Class
    </strong>
</h2>

<p align='center'>
    <img src="./Images/Input Word Length by Class.png" alt="Input Word Length By Class" height=320 width=650>
</p>

<h2 align='center'>
    <strong>
        Class Distribution
    </strong>
</h2>

<p align='center'>
    <img src="./Images/Class Distribution.png" alt="Class Distribution" height=320 width=650>
</p>

<hr />

<h2 align='center'>
    <strong>
        Results
    </strong>
</h2>

<table align='center'border='1px'>
    <thead>
        <tr>
            <td align='right'><strong>Metric</strong></td>
            <td align='left'><strong>Value</strong></td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align='right'>Evaluation Loss</td>
            <td align='left'>0.005155991297215223</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Accuracy</td>
            <td align='left'>0.9992378048780488</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro F1</td>
            <td align='left'>0.9992274968166693</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro Precision</td>
            <td align='left'>0.9992301770592764</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro Recall</td>
            <td align='left'>0.9992266047950503</td>
        </tr>
                <tr>
            <td align='right'>Evaluation Micro F1</td>
            <td align='left'>0.9992378048780488</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Micro Precision</td>
            <td align='left'>0.9992378048780488</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Micro Recall</td>
            <td align='left'>0.9992378048780488</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted F1</td>
            <td align='left'>0.9992378028312418</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted Precision</td>
            <td align='left'>0.9992395651439193</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted Recall</td>
            <td align='left'>0.9992378048780488</td>
        </tr>
    </tbody>
</table>

<hr />

<h2 align='center'>
    <strong>
        Conclusions
    </strong>
</h2>
<p align='center'>
    The results are fantastic.
</p>
<hr />
