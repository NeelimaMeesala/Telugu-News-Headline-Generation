# Telugu News Headline Generation Project

## Overview
This project focuses on finetuning models for generating headlines from Telugu news articles. It includes datasets, code files for model finetuning, and generated summaries/headlines.

## Datasets
The datasets were created by scraping news articles and headlines from the Telugu news website "Sakshi":
- **final_train.csv**: Training dataset in Telugu consisting of article and headline pairs.
- **final_test.csv**: Test dataset in Telugu consisting of article and headline pairs.

## Code Files
There are three main code files provided to finetune the models:
1. **finetuning_mBART50.ipynb**: Code for finetuning mBART50-large.
2. **finetuning_mT5.ipynb**: Code for finetuning mT5-small.
3. **finetuning_IndicBART.ipynb**: Code for finetuning IndicBART.

## Generated Summaries/Headlines
After finetuning each model, the following files contain generated summaries/headlines:
- **mBART50_generated_summaries.csv**: Generated summaries/headlines from mBART50-large.
- **mT5_generated_summaries.csv**: Generated summaries/headlines from mT5-small.
- **IndicBART_generated_summaries.csv**: Generated summaries/headlines from IndicBART.

## Usage
1. **Datasets**: Use `final_train.csv` for training and `final_test.csv` for evaluation.
   
2. **Model Finetuning**: Open and execute the respective `.ipynb` files to finetune each model.

3. **Generated Summaries/Headlines**: Review the generated summaries/headlines stored in the CSV files after finetuning each model.
