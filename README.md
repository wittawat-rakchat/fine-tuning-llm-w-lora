# fine-tuning-llm-w-lora
Parameter-Efficient Fine-Tuning (PEFT) for text classification

What's LoRA?

In this repository, I used a popular technique in efficient fine-tuning known as LoRA (Low-Rank Adaptation) of Large Language Models (LLMs). LoRA is all about speeding up the process of fine-tuning big language models while using less computer memory.

Here's the core idea: LoRA represents changes in the model's weights using two smaller matrices made through a clever method called low-rank decomposition. These matrices can be adjusted to fit new data without making lots of changes. The original weight matrix doesn't get altered further. We get the final results by combining both the original and the adjusted weights.

LoRA has a bunch of benefits. It makes fine-tuning more efficient by reducing the number of things the model needs to learn. It's also flexible and can be used with other techniques for efficiency. Models fine-tuned with LoRA perform just as well as fully fine-tuned models. Plus, there's no extra time delay when using LoRA because the added weights work seamlessly with the base model.
