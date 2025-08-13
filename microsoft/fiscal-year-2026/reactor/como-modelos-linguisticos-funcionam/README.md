
# How Languages Model Work?

This page contains resources referenced during my talk on how language models work. It includes tools for prompt engineering, code examples from real model implementations, links to model repositories, and utilities for understanding tokenization and GPU acceleration. These materials provide practical insights into the inner workings and development of large language models.

The deck I used is [here](./como-modelos-linguisticos-funcionam.pdf) and the notebook [here](./como-modelos-linguisticos-funcionam.ipynb).

## Links I used

### GitHub Copilot

- [VS Code Extension](https://github.com/microsoft/vscode-copilot-chat)
- [Typescript Library to build Prompts](https://github.com/microsoft/vscode-prompt-tsx)

### Code Llama Model Code

- [Transfomer class implementation](https://github.com/meta-llama/codellama/blob/main/llama/model.py#L257)
- [Model loading](https://github.com/meta-llama/codellama/blob/main/llama/generation.py#L121)
- [Token generation](https://github.com/meta-llama/codellama/blob/main/llama/generation.py#L164)
- [Token Sampling](https://github.com/meta-llama/codellama/blob/main/llama/generation.py#L173)

### CUDA

- [Sample Kernel](https://github.com/glzbcrt/cuda-python/blob/main/kernel.cu)

### gps-oss Model

- [openai/gpt-oss-20b](https://huggingface.co/openai/gpt-oss-20b)

### OpenAI Tokenizer

- [Tokenizer](https://platform.openai.com/tokenizer)
