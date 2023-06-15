<h1 align='center'>
    Language Detection of 20,000 Samples
</h1>

<h2 align='center'>
    <strong>
        Project Purpose
    </strong>
</h2>

<p align='center'>
    The purpose of this project was to detect the language of the text. The checkpoint used was the <strong><em>distilbert-base-multilingual-cased</em></strong> and it ran for <strong><em>two (2) epoch</em></strong> on a <strong><em>CPU</em></strong>. The datasest includes <strong><em>20,000 samples</em></strong>.
</p>

<hr />

<h2 align='center'>
    <strong>
        Dataset Name & Source Link
    </strong>
</h2>

<p align='center'>
    <a href='https://www.kaggle.com/datasets/basilb2s/language-detection'>
        Language Detection
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
    <img src="./Images/Input Word Length by Class.png" alt="Input Word Lengths By Class" height=320 width=650>
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
            <td align='left'>0.1102</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Accuracy</td>
            <td align='left'>0.9883</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro F1</td>
            <td align='left'>0.9882</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro Precision</td>
            <td align='left'>0.9887</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro Recall</td>
            <td align='left'>0.9879</td>
        </tr>
                <tr>
            <td align='right'>Evaluation Micro F1</td>
            <td align='left'>0.9883</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Micro Precision</td>
            <td align='left'>0.9883</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Micro Recall</td>
            <td align='left'>0.9883</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted F1</td>
            <td align='left'>0.9884</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted Precision</td>
            <td align='left'>0.9888</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted Recall</td>
            <td align='left'>0.9883</td>
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
    The results are fantastic. Only 47 out of 4000 evaluation samples were incorrectly predicted.
</p>
<hr />
