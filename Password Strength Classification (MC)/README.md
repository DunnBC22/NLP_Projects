<h1 align='center'>
    Password Strength Classifier
</h1>

<h2 align='center'>
    <strong>
        Project Purpose
    </strong>
</h2>

<p align='center'>
    The purpose of this project was to classify the strength of passwords. The checkpoint used was the <strong><em>microsoft/codebert-base</em></strong> and it ran for <strong><em>three (3) epoch</em></strong> on a <strong><em>CPU</em></strong>. The datasest includes <strong><em>almost 670,000 samples</em></strong>.
</p>

<p align='center'>
    This project was inspired by <a href='https://huggingface.co/SAPOSS/password-model'>SAP OSS's (Online Service System) password-model</a> listed on HuggingFace's Model Hub.
</p>

<hr />

<h2 align='center'>
    <strong>
        Dataset Name & Source Link
    </strong>
</h2>

<p align='center'>
    <a href='https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset'>
        Password Strength Classifier Dataset
    </a>
</p>

<hr />

<h2 align='center'>
    <strong>
        Histogram of Password Lengths (in Characters)
    </strong>
</h2>

<p align='center'>
    <img src="./Images/Context Word Length.png" alt="Password lengths" height=320 width=650>
</p>

<h2 align='center'>
    <strong>
        Histogram of Password Lengths (in Characters) By Class
    </strong>
</h2>

<p align='center'>
    <img src="./Images/Context Word Length By Class.png" alt="Password lengths By Class" height=320 width=650>
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
            <td align='left'>0.0077</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Accuracy</td>
            <td align='left'>0.9975</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro F1</td>
            <td align='left'>0.9963</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro Precision</td>
            <td align='left'>0.9948</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Macro Recall</td>
            <td align='left'>0.9978</td>
        </tr>
                <tr>
            <td align='right'>Evaluation Micro F1</td>
            <td align='left'>0.9975</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Micro Precision</td>
            <td align='left'>0.9975</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Micro Recall</td>
            <td align='left'>0.9975</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted F1</td>
            <td align='left'>0.9975</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted Precision</td>
            <td align='left'>0.9975</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Weighted Recall</td>
            <td align='left'>0.9975</td>
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
    The results are fantastic. Out of 133,922 samples included in the evaluation dataset, only 335 samples were incorrectly predicted.
</p>
<hr />
