<h1 align='center'>
    English to Spanish Translation (EN -> ES)
</h1>

<h2 align='center'>
    <strong>
        Project Purpose
    </strong>
</h2>

<p align='center'>
    The purpose of this project was to train a transformer to translate between English and Spanish. The checkpoint used was the <strong><em>facebook/mbart-large-50</em></strong> and it ran for <strong><em>two (2) epoch</em></strong> on a <strong><em>CPU</em></strong>.
</p>

<hr />

<h2 align='center'>
    <strong>
        Dataset Name & Source Link
    </strong>
</h2>

<p align='center'>
    <a href='https://www.kaggle.com/datasets/hgultekin/paralel-translation-corpus-in-22-languages'>
        Parallel Translation Corpus in 24 languages!
    </a>
</p>

<hr />

<h2 align='center'>
    <strong>
        Histograms for Both English & Spanish Context lengths
    </strong>
</h2>

<h4 align='center'>
    <strong>
        Histograms for English Context lengths
    </strong>
</h4>

<p align='center'>
    <img src="./Images/English Context Length.png" alt="English Text Input Lengths" height=320 width=650>
</p>

<h4 align='center'>
    <strong>
        Histograms for Spanish Context lengths
    </strong>
</h4>

<p align='center'>
    <img src="./Images/Spanish Context Length.png" alt="German Text Input Lengths" height=320 width=650>
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
            <td align='left'>1.0289689302444458</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Bleu</td>
            <td align='left'>41.443724393304315</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Rouge1</td>
            <td align='left'>0.6751402780531002</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Rouge2</td>
            <td align='left'>0.49769602014143044</td>
        </tr>
        <tr>
            <td align='right'>Evaluation RougeL</td>
            <td align='left'>0.6371513427059108</td>
        </tr>
        <tr>
            <td align='right'>Evaluation RougeLsum</td>
            <td align='left'>0.6376403149816605</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Meteor</td>
            <td align='left'>0.6479226630466496</td>
        </tr>
        <tr>
            <td align='right'>Evaluation Runtime</td>
            <td align='left'>40243.222 Seconds</td>
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
    The results are okay, but not great. The results were better than the results of the English to German Translation model, but not where they should be. Unfortunately, I had to downsize the training size significantly to make the training duration reasonable. If I had the opportunity to train on the full dataset (or nearly the full dataset), I am confident that this project would have stellar results!
</p>
<hr />
