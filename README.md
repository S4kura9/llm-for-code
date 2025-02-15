# llm-for-code
## Collection on Large Language Models for Code Generation


## Development of LLM
| Name|Date                                         |Link                                     |method |
|----------------------|--------------------------------|-------------------------------------------------|-----|
|Transformer|2017.6|[Attention is all you need](https://arxiv.org/abs/1706.03762)|attention|
|GPT|2018.6|[Improving Language Understanding by Generative Pre-Training](https://www.semanticscholar.org/paper/Improving-Language-Understanding-by-Generative-Radford-Narasimhan/cd18800a0fe0b668a1cc19f2ec95b5003d0a5035)|pretraining + fine tuning|
|BERT|2018.10|[BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805) |双向|
|GPT-2|2019.2|[Language Models are Unsupervised Multitask Learners](https://www.semanticscholar.org/paper/Language-Models-are-Unsupervised-Multitask-Learners-Radford-Wu/9405cc0d6169988371b2755e573cc28650d14dfe) |zero-shot+ prompt |
|T5|2019.11|[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)|
|GPT-3|2020.5|[Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) |few-shot+不做梯度更新(不微调) |

## Development of LLM for coding
| Name|Date                                         |Link                                     |method |
|----------------------|--------------------------------|-------------------------------------------------|-----|
|Codex|2021.7|[Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374)| 预训练+微调 |
|AlphaCode|2022.3|[Competition-Level Code Generation withAlphaCode](https://www.semanticscholar.org/paper/Competition-level-code-generation-with-AlphaCode-Li-Choi/5cbe278b65a81602a864184bbca37de91448a5f5)| 预训练+微调|
|CodeGeeX|2023.8|[CodeGeeX: A Pre-Trained Model for Code Generation with Multilingual Benchmarking on HumanEval-X](https://arxiv.org/abs/2303.17568)| 预训练+微调|
|PET|2021?|[Exploiting Cloze Questions for Few Shot Text Classification and Natural Language Inference](https://arxiv.org/abs/2001.07676)|指令微调|
|CodeT5|2021.9|[CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation](https://arxiv.org/abs/2109.00859v1)||
|CodeT5+|2023.5|[CodeT5+: Open Code Large Language Models for Code Understanding and Generation](https://arxiv.org/abs/2305.07922)|InstructCodeT5基于其指令微调|
|Code Llama|2023.8|[Code Llama: Open Foundation Models for Code](https://arxiv.org/abs/2308.12950)||
|RLHF|2019.9|[Fine-Tuning Language Models from Human Preferences](https://arxiv.org/abs/1909.08593)||
|CodeRL|2022.7|[CodeRL: Mastering Code Generation through Pretrained Models and Deep Reinforcement Learning](https://arxiv.org/abs/2207.01780)||
|RAG|2020.5|[Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401)||
|MetaGPT|2023.8|[MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352)|多智能体|
|MAD|2023.5|[Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate](https://arxiv.org/abs/2305.19118)|多智能体|