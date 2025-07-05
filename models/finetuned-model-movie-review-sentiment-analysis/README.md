---
library_name: transformers
tags:
- generated_from_trainer
metrics:
- accuracy
- f1
- precision
- recall
model-index:
- name: finetuned-model-movie-review-sentiment-analysis
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# finetuned-model-movie-review-sentiment-analysis

This model was trained from scratch on the None dataset.
It achieves the following results on the evaluation set:
- Loss: 0.3178
- Accuracy: 0.925
- F1: [0.9101796407185628, 0.9356223175965666]
- Precision: [1.0, 0.8790322580645161]
- Recall: [0.8351648351648352, 1.0]
- Auc: 0.9770

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

| Training Loss | Epoch | Step | Validation Loss | Accuracy | F1                                       | Precision                 | Recall                    | Auc    |
|:-------------:|:-----:|:----:|:---------------:|:--------:|:----------------------------------------:|:-------------------------:|:-------------------------:|:------:|
| No log        | 1.0   | 100  | 0.3178          | 0.925    | [0.9101796407185628, 0.9356223175965666] | [1.0, 0.8790322580645161] | [0.8351648351648352, 1.0] | 0.9770 |


### Framework versions

- Transformers 4.51.3
- Pytorch 2.7.1+cpu
- Datasets 3.3.2
- Tokenizers 0.21.0
