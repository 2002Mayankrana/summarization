---
base_model: google/pegasus-x-base
tags:
- generated_from_trainer
model-index:
- name: pegasusx-AMI-text-summarizer
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# pegasusx-AMI-text-summarizer

This model is a fine-tuned version of [google/pegasus-x-base](https://huggingface.co/google/pegasus-x-base) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 1.9024

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 1
- eval_batch_size: 1
- seed: 42
- gradient_accumulation_steps: 16
- total_train_batch_size: 16
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- lr_scheduler_warmup_steps: 500
- num_epochs: 35

### Training results

| Training Loss | Epoch | Step | Validation Loss |
|:-------------:|:-----:|:----:|:---------------:|
| 4.6836        | 0.77  | 10   | 4.2972          |
| 4.6013        | 1.53  | 20   | 4.1099          |
| 4.5902        | 2.3   | 30   | 3.9257          |
| 4.3479        | 3.06  | 40   | 3.8087          |
| 4.1995        | 3.83  | 50   | 3.6779          |
| 4.0121        | 4.59  | 60   | 3.5480          |
| 3.8925        | 5.36  | 70   | 3.4199          |
| 3.7548        | 6.12  | 80   | 3.2936          |
| 3.4644        | 6.89  | 90   | 3.1752          |
| 3.2484        | 7.66  | 100  | 3.0529          |
| 3.2456        | 8.42  | 110  | 2.9345          |
| 3.2281        | 9.19  | 120  | 2.8282          |
| 2.9944        | 9.95  | 130  | 2.7188          |
| 2.8439        | 10.72 | 140  | 2.6208          |
| 2.8192        | 11.48 | 150  | 2.5434          |
| 2.631         | 12.25 | 160  | 2.4852          |
| 2.5715        | 13.01 | 170  | 2.4277          |
| 2.5404        | 13.78 | 180  | 2.3876          |
| 2.4297        | 14.55 | 190  | 2.3507          |
| 2.4243        | 15.31 | 200  | 2.3110          |
| 2.4517        | 16.08 | 210  | 2.2733          |
| 2.3127        | 16.84 | 220  | 2.2454          |
| 2.3058        | 17.61 | 230  | 2.2127          |
| 2.1694        | 18.37 | 240  | 2.1808          |
| 2.1908        | 19.14 | 250  | 2.1532          |
| 2.1474        | 19.9  | 260  | 2.1234          |
| 2.1264        | 20.67 | 270  | 2.1139          |
| 2.0156        | 21.44 | 280  | 2.0933          |
| 2.0264        | 22.2  | 290  | 2.0611          |
| 2.0338        | 22.97 | 300  | 2.0448          |
| 2.055         | 23.73 | 310  | 2.0302          |
| 1.7735        | 24.5  | 320  | 2.0117          |
| 1.8999        | 25.26 | 330  | 2.0005          |
| 1.8606        | 26.03 | 340  | 1.9795          |
| 1.7847        | 26.79 | 350  | 1.9744          |
| 1.7478        | 27.56 | 360  | 1.9614          |
| 1.8806        | 28.33 | 370  | 1.9514          |
| 1.6817        | 29.09 | 380  | 1.9436          |
| 1.689         | 29.86 | 390  | 1.9351          |
| 1.649         | 30.62 | 400  | 1.9292          |
| 1.715         | 31.39 | 410  | 1.9181          |
| 1.5847        | 32.15 | 420  | 1.9077          |
| 1.6016        | 32.92 | 430  | 1.9112          |
| 1.532         | 33.68 | 440  | 1.9018          |
| 1.4849        | 34.45 | 450  | 1.9024          |


### Framework versions

- Transformers 4.37.2
- Pytorch 2.1.0+cu121
- Datasets 2.17.0
- Tokenizers 0.15.2
