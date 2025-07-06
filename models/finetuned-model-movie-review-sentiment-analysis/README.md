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
- Loss: 0.2338
- Accuracy: 0.95
- F1: [0.946236559139785, 0.9532710280373832]
- Precision: [0.946236559139785, 0.9532710280373832]
- Recall: [0.946236559139785, 0.9532710280373832]
- Auc: 0.9885

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 1.2090707659718472e-05
- train_batch_size: 4
- eval_batch_size: 4
- seed: 42
- gradient_accumulation_steps: 4
- total_train_batch_size: 16
- optimizer: Use OptimizerNames.ADAMW_8BIT with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: linear
- lr_scheduler_warmup_ratio: 0.09356655990374085
- num_epochs: 4
- mixed_precision_training: Native AMP

### Training results

| Training Loss | Epoch | Step | Validation Loss | Accuracy | F1                                       | Precision                                | Recall                                   | Auc    |
|:-------------:|:-----:|:----:|:---------------:|:--------:|:----------------------------------------:|:----------------------------------------:|:----------------------------------------:|:------:|
| No log        | 1.0   | 13   | 0.2963          | 0.935    | [0.9281767955801105, 0.9406392694063926] | [0.9545454545454546, 0.9196428571428571] | [0.9032258064516129, 0.9626168224299065] | 0.9884 |
| No log        | 2.0   | 26   | 0.2338          | 0.95     | [0.946236559139785, 0.9532710280373832]  | [0.946236559139785, 0.9532710280373832]  | [0.946236559139785, 0.9532710280373832]  | 0.9885 |
| No log        | 3.0   | 39   | 0.2641          | 0.94     | [0.9347826086956522, 0.9444444444444444] | [0.945054945054945, 0.9357798165137615]  | [0.9247311827956989, 0.9532710280373832] | 0.9878 |
| No log        | 4.0   | 52   | 0.2627          | 0.94     | [0.9347826086956522, 0.9444444444444444] | [0.945054945054945, 0.9357798165137615]  | [0.9247311827956989, 0.9532710280373832] | 0.9878 |


### Framework versions

- Transformers 4.53.1
- Pytorch 2.7.1+cu118
- Datasets 3.6.0
- Tokenizers 0.21.2
