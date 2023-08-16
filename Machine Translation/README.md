<div style="text-align: center">

<h1>Machine Translation</h1>

<h2>
    Summary of Repository
</h2>

This repository houses Machine Translation models fine-tuned using checkpoints from HuggingFace. More information about each model can be found in their respective subdirectory. 

To see this project as well as many other projects that I have completed, please visit my HuggingFace Profile/Portfolio: <a href="https://huggingface.co/DunnBC22">https://huggingface.co/DunnBC22</a>.

<h2>
    Models & Results
</h2>
</div>

| Project Name | Checkpoint | Loss | Bleu | Rouge1 | Rouge2 | RougeL | RougeLsum | Meteor |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| [NLP Translation Project-EN to FR](https://www.kaggle.com/datasets/hgultekin/paralel-translation-corpus-in-22-languages) | `facebook/mbart-large-50` | 0.3902 | 35.1914 | 0.6420 | 0.4573 | 0.6070 | 0.6069 | 0.5917 |
| [NLP Translation Project-EN_DE](https://www.kaggle.com/datasets/hgultekin/paralel-translation-corpus-in-22-languages) | `facebook/mbart-large-50` | 1.2342 | 35.5931 | 0.5803 | 0.3939 | 0.5439 | 0.5442 | 0.5501 |
| [NLP Translation Project-EN_ES](https://www.kaggle.com/datasets/hgultekin/paralel-translation-corpus-in-22-languages) | `facebook/mbart-large-50` | 1.0290 | 41.4437 | 0.6751 | 0.4977 | 0.6372 | 0.6376 | 0.6479 |
| [Biomedical Dataset - EN to IT](https://huggingface.co/datasets/paolo-ruggirello/biomedical-dataset) | `facebook/mbart-large-50` | 1.0290 | 41.4437 | 0.6751 | 0.4977 | 0.6372 | 0.6376 | 0.6479 |
| [Korean Parallel Corpora (Korean to English)](https://huggingface.co/datasets/Moo/korean-parallel-corpora) | `Helsinki-NLP/opus-mt-ko-en` | 2.6620 | 14.3395 | 0.4391 | 0.2022 | 0.3671 | 0.3671 | - |
| [Medical - German to English](https://huggingface.co/datasets/ahazeemi/opus-medical-en-de) | `Helsinki-NLP/opus-mt-de-en` | 0.8723 | 53.8820 | 0.7664 | 0.6284 | 0.7370 | 0.7370 | - |


Notes:
<ul>
    <li>All Metrics are the Evaluation version of the metrics.</li>
    <li>If you click on the project name, it takes you to the data source for that project.</li>
<ul>
