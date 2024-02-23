# Sharif-STR at SemEval-2024 Task 1: Transformer as a Regression Model for Fine-Grained Scoring of Textual Semantic Relations

This repository contains code and resources for computing the relatedness score between two samples using a transformer-based regression model. The primary purpose of this notebook is to apply a correlation metric on a test set, evaluating the model's success in measuring the relatedness between pairs of samples.

## Overview

The notebook is structured into several parts, with a focus on using a transformer-based regression model, specifically fine-tuning the BERT model (though other models can be used as well).
There is also a section to augment the dataset with a T5-paraphraser.

## Code
The `notebook.ipynb` script is dedicated to fine-tuning the BERT model for the relatedness scoring task. This part includes steps for:

- Loading and preprocessing the dataset.
- Configuring and fine-tuning the transformer model.
- Evaluating the model on a test set.
- Extracting and saving relatedness scores.
- Generating dataset with the T5-paraphraser

## Citation

If you find this work valuable for your research, please consider citing the relevant paper or source for the transformer model used.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to acknowledge the developers of the RoBERTa model and SemEval organizers for providing the datasets that contribute to this research.