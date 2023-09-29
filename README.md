# SAIT-challenge

This repository is the implementation of a challenge hosted by SAIT.
More information about the challenge can be found at https://cechallenge.github.io/.

The challenge addresses the following objectives:
- improving 1) inference time, 2) accuracy of [LLaMA-30B](https://github.com/facebookresearch/llama) on the [hellaswag](https://paperswithcode.com/dataset/hellaswag) validation set from system perspectives.




For our optimization, the following codes are utilized:
1. [LLaMA-30B weights](https://huggingface.co/decapoda-research/llama-30b-hf) revealed in huggingface
2. [lm-evaluation harness](https://github.com/YounghunGo/lm-evaluation-harness) for evaluation (also support model parallelism)
3. [deepspeed](https://github.com/microsoft/DeepSpeed) to apply tensor parallelism and inference-optimized kernel technique 
   
