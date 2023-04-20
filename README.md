# Medical Data Protection with Bayesian Methods

## Overview

Medical datasets contain a plethora of information about patients that are considered confidential, but they are also regarded as crucial sources for studying diseases, economics, and other areas of discussion. We found the [__*Personal Medical Cost*__](https://www.kaggle.com/datasets/mirichoi0218/insurance) dataset from Kaggle and deemed it important in terms of predicting how much an individual spends on medical insurance, and other inferences. We hope to provide this dataset with protection so that when the dataset is released to the public, the contractors’ private personal information will not be leaked yet users can examine associations between medical cost and contractors’ attributes.

To that end, we employed Bayesian statistical models to partially synthesize information about variables that we deemed sensitive. Afterwards, we conducted utility and risk evaluations to examine whether our synthetic dataset could serve for analytical purposes while also providing sufficient protection of the confidential information. We also applied differential privacy methods to further protect the summary statistics of the confidential dataset.

For modeling and analysis details, please refer to the Rmd and the report files in this repository. This the final project for my senior intensive __*Statistical Data Privacy*__, instructed by [__Professor Jingchen (Monika) Hu__](https://www.vassar.edu/faculty/jihu). All work was made using R in collaboration with my amazing partner [__Jade Wilkinson__](https://www.linkedin.com/in/jadewilkinson345/).

