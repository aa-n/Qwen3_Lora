---
library_name: peft
license: other
base_model: /dev/shm/Qwen/Qwen3-14B
tags:
- llama-factory
- lora
- generated_from_trainer
model-index:
- name: train_2025-04-29-14-28-08
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# train_2025-04-29-14-28-08

This model is a fine-tuned version of [/dev/shm/Qwen/Qwen3-14B](https://huggingface.co//dev/shm/Qwen/Qwen3-14B) on the tcm, the mdk and the NLI datasets.

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
- train_batch_size: 2
- eval_batch_size: 8
- seed: 42
- distributed_type: multi-GPU
- num_devices: 7
- gradient_accumulation_steps: 8
- total_train_batch_size: 112
- total_eval_batch_size: 56
- optimizer: Use adamw_torch with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: cosine
- num_epochs: 3.0

### Training results



### Framework versions

- PEFT 0.15.1
- Transformers 4.51.3
- Pytorch 2.7.0+cu126
- Datasets 3.5.0
- Tokenizers 0.21.1