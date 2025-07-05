---
library_name: transformers
tags:
- generated_from_trainer
model-index:
- name: finetuned_model
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# finetuned_model

This model was trained from scratch on the None dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 3.2306249035382145e-05
- train_batch_size: 2
- eval_batch_size: 2
- seed: 42
- optimizer: Use adamw_torch with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: linear
- num_epochs: 1

### Training results

| Training Loss | Epoch | Step | Validation Loss | Accuracy | F1                      | Precision             | Recall      | Auc    |
|:-------------:|:-----:|:----:|:---------------:|:--------:|:-----------------------:|:---------------------:|:-----------:|:------:|
| No log        | 1.0   | 100  | 0.2252          | 0.95     | [0.94845361 0.95145631] | [0.9787234 0.9245283] | [0.92 0.98] | 0.9898 |


### Framework versions

- Transformers 4.51.3
- Pytorch 2.7.1+cpu
- Datasets 3.3.2
- Tokenizers 0.21.0
