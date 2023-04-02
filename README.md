# Multi-Choice-Test-Task

## Dataset generating

I used GPT-3.5 via ChatGPT API to generate dataset. It is the legal solution by itself, but it has few drawbacks:

- Internet connection is needed

- Not possible to fine-tune model for some specific tasks.

File [dataset_generating.ipynb](dataset_generating.ipynb) contain code to generate the dataset.

File [dataset.csv](dataset.csv) contain dataset itself.

## Model training

I fine-tuned GPT-2 using this dataset.

File [fine_tuning.ipynb](fine_tuning.ipynb) contain code of model fine-tuning.
