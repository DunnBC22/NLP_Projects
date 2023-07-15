<div align="center">

<h1>Token Classification</h1>
<p>
    This subdirectory in this repository is for Token Classification projects. Currently, all projects are monolingual (English). 
    <!--It is broken down into two subdirectories: Monolingual and Multilingual (coming soon).-->
</p>

<h2>
    Monolingual
</h2>

<table style="border: 3px solid black;">
<tr style="border-bottom: 2.5px solid black;">
    <th style="text-align: center;">
        Model Name
    </th>
    <th style="text-align: center;">
        Loss
    </th>
    <th style="text-align: center;">
        Overall Evaluation Accuracy
    </th>
    <th style="text-align: center;">
        Overall Evaluation F1-Score
    </th>
    <th style="text-align: center;">
        Overall Evaluation Precision
    </th>
    <th style="text-align: center;">
        Overall Evaluation Recall
    </th>
    <th style="text-align: center;">
        Best Model/Transformer
    </th>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="Monolingual/EMBO-BLURB/NER%20Project%20Using%20EMBO-BLURB%20Dataset.ipynb">
            BC2GM-IOB [EMBO-BLURB]
        </a>
    </td>
    <td style="text-align: center;">
        0.0813
    </td>
    <td style="text-align: center;">
        0.9736
    </td>
    <td style="text-align: center;">
        0.7765
    </td>
    <td style="text-align: center;">
        0.7521
    </td>
    <td style="text-align: center;">
        0.8025
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="Monolingual/NCBI_Disease/NER%20Project%20Using%20NCBI_Disease%20Dataset.ipynb">
            NCBI Disease
        </a>
    </td>
    <td style="text-align: center;">
        0.0614
    </td>
    <td style="text-align: center;">
        0.9825
    </td>
    <td style="text-align: center;">
        0.8359
    </td>
    <td style="text-align: center;">
        0.8064
    </td>
    <td style="text-align: center;">
        0.8677
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="Monolingual/StrombergNLP-Twitter_pos_vcb/NER%20Project%20Using%20StrombergNLP%20Twitter_pos_vcb%20Dataset.ipynb">
            Stromberg NLP - Twitter (Part of Speech) (SeqEval)
        </a>
    </td>
    <td style="text-align: center;">
        0.0533
    </td>
    <td style="text-align: center;">
        0.9860
    </td>
    <td style="text-align: center;">
        0.9824
    </td>
    <td style="text-align: center;">
        0.9828
    </td>
    <td style="text-align: center;">
        0.9820
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="Monolingual/WikiNeural%20-%20Transformer%20Comparison">
            WikiNeural (Transformer Comparison)
        </a>
    </td>
    <td style="text-align: center;">
        0.093
    </td>
    <td style="text-align: center;">
        0.9912
    </td>
    <td style="text-align: center;">
        0.9261
    </td>
    <td style="text-align: center;">
        0.9145
    </td>
    <td style="text-align: center;">
        0.9380
    </td>
    <td style="text-align: center;">
        Bert-Base-Cased
    </td>
</tr>

<!-- 
<tr>
    <td style="text-align: center;">
        <a href="Monolingual/StrombergNLP-Twitter_pos_vcb/NER%20Project%20Using%20StrombergNLP%20Twitter_pos_vcb%20Dataset%20-%20Poseval%20Metrics.ipynb">
            Stromberg NLP-Twitter (Part of Speech) (PosEval)
        </a>
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
</tr>
-->
<tr>
    <td style="text-align: center;">
        <a href="">
            Bio NLP 2004
        </a>
    </td>
    <td style="text-align: center;">
        0.2066
    </td>
    <td style="text-align: center;">
        0.9367
    </td>
    <td style="text-align: center;">
        0.7169
    </td>
    <td style="text-align: center;">
        0.6628
    </td>
    <td style="text-align: center;">
        0.7805
    </td>
    <td style="text-align: center;">
        -
    </td>
</tr>

</table>


<br />

<!--
<h2>
    Multilingual
</h2>

<table style="border: 3px solid black;">
<tr style="border-bottom: 2.5px solid black;">
    <th style="text-align: center;">
        Model Name
    </th>
    <th style="text-align: center;">
        Loss
    </th>
    <th style="text-align: center;">
        Overall Evaluation Accuracy
    </th>
    <th style="text-align: center;">
        Overall Evaluation F1-Score
    </th>
    <th style="text-align: center;">
        Overall Evaluation Precision
    </th>
    <th style="text-align: center;">
        Overall Evaluation Recall
    </th>
</tr>
<tr>
    <td style="text-align: center;">
        <a href="">
            Project Name
        </a>
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="">
            Project Name
        </a>
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="">
            Project Name
        </a>
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="">
            Project Name
        </a>
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
</tr>

<tr>
    <td style="text-align: center;">
        <a href="">
            Project Name
        </a>
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
    <td style="text-align: center;">
        0.
    </td>
</tr>

</table> -->
</div>
