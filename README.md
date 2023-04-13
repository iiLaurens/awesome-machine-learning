## Awesome libraries
[Composer](https://github.com/mosaicml/composer):
A library that applies optimizations to speed up training process of large neural nets

## Awesome articles
[Making Deep Learning go Brrrr](https://horace.io/brrr_intro.html):
An article that introduces first principles of performance optimization in deep learning

[How Nvidia’s CUDA Monopoly In Machine Learning Is Breaking - OpenAI Triton And PyTorch 2.0](https://www.semianalysis.com/p/nvidiaopenaitritonpytorch)

## Awesome papers
### LLMs
[Decoder-Only or Encoder-Decoder? Interpreting Language Model as a Regularized Encoder-Decoder](https://arxiv.org/abs/2304.04052) (2023)

[Eight Things to Know about Large Language Models](https://arxiv.org/abs/2304.00612) (2023)

[Cerebras-GPT: Open Compute-Optimal Language Models Trained on the Cerebras Wafer-Scale Cluster](https://arxiv.org/abs/2304.03208)  
Paper showing how to train large scale models, and compares different decoder-only models trained with different sizes and flops.

[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683) (2019)  
Introduction of T5 model. Also explores many different styles of language modeling (encoder-decoder vs prefix LM vs decoder-only). Encoder-decoder & prefix models might be better for certain tasks.

[Transcending Scaling Laws with 0.1% Extra Compute](https://arxiv.org/abs/2210.11399) (2022)  
Shows that decoder-only models with causal mask can be converted to models with PrefixLM by continuing training with UL2 objectives, a method dubbed **UL2R**. This helps with many downstream tasks. GPT JT is an example of this.

### Knowledge graphs
[Crawling the internal knowledge graphs of large language models](https://arxiv.org/abs/2301.12810) 

### Quantization
[The case for 4-bit precision: k-bit Inference Scaling Laws](https://arxiv.org/abs/2212.09720)

[GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers](https://arxiv.org/abs/2210.17323)
