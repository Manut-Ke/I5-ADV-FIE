# TP03 – Introduction to Hugging Face and Unsloth

## Introduction

In this lesson, the teacher introduced two important tools used in AI and Large Language Model (LLM) development: **Hugging Face** and **Unsloth**. We learned about their purposes, key features, and how they support the development and fine-tuning of machine learning models.

### Hugging Face

Hugging Face is an open-source AI platform and community, often described as the "GitHub for AI." It allows developers, researchers, and organizations to discover, share, train, fine-tune, and deploy machine learning models.

Its main features include:
- **Models:** Provides access to pretrained models such as Llama, Gemma, and Qwen.
- **Datasets:** Offers datasets for model training, evaluation, and testing.
- **Libraries:** Provides tools such as Transformers, PEFT, and Tokenizers.
- **Spaces:** Allows users to build, share, and demonstrate AI applications.
- **Documentation:** Provides guides and technical references to help developers work with its tools.

### Unsloth

Unsloth is an open-source framework designed to make Large Language Model (LLM) fine-tuning more efficient. It helps developers train and fine-tune models faster while reducing GPU memory (VRAM) consumption.

Its main features include:
- Accelerates LLM fine-tuning and training.
- Reduces GPU memory requirements.
- Supports efficient fine-tuning techniques such as LoRA and QLoRA.
- Supports popular models, including Gemma, Llama, and Qwen.
- Integrates with Hugging Face libraries and tools.
- Makes fine-tuning possible with more limited computational resources.

## Differences Between Hugging Face and Unsloth

Although both tools are used in AI and LLM development, they serve different purposes.

**Hugging Face**
- An AI platform and ecosystem for machine learning and LLM development.
- Provides pretrained models and datasets.
- Offers libraries for loading, training, and fine-tuning models.
- Allows users to share and publish their models.
- Provides tools for deploying and demonstrating AI applications.

**Unsloth**
- A framework focused on optimizing LLM fine-tuning.
- Improves training speed and computational efficiency.
- Reduces GPU memory consumption.
- Supports LoRA and QLoRA fine-tuning.
- Works with Hugging Face models and libraries.

**In summary:** Hugging Face provides a broad ecosystem for discovering, developing, sharing, and deploying AI models, whereas Unsloth focuses on making LLM fine-tuning faster and more memory-efficient.

## Key Concepts Learned

During the lesson, the teacher introduced several important concepts related to LLM development.

### Fine-Tuning

Fine-tuning is the process of adapting a pretrained model to perform a specific task by training it further on a smaller, task-specific dataset. It helps the model improve its performance in a particular domain or application.

### Model Selection

Model selection is the process of choosing the most suitable LLM for a specific task. Several factors should be considered:
- Task requirements and expected performance.
- Model size and architecture.
- Available computational resources.
- Training and inference costs.
- Model licensing and availability.

### Model Loaders

Hugging Face Transformers provides the `AutoModel` family of classes to simplify loading pretrained models. These classes automatically select the appropriate model architecture based on a pretrained model's configuration.

Examples include:
- `AutoModelForCausalLM`: For causal language modeling and text generation.
- `AutoModelForSequenceClassification`: For text classification tasks.
- `AutoModelForQuestionAnswering`: For question-answering tasks.
- `AutoTokenizer`: For converting text into tokens that a model can process.

### Unsloth

Unsloth is a framework that improves the efficiency of LLM fine-tuning by optimizing training operations and reducing GPU memory usage. It is particularly useful when computational resources are limited.

## Class Activities

During the practical session, we carried out several activities to become familiar with the Hugging Face ecosystem and LLM development tools.

The activities included:
- Creating a Hugging Face account.
- Exploring the Hugging Face platform, including Models, Spaces, and Documentation.
- Exploring different pretrained models and understanding model selection.
- Learning the basic concepts of fine-tuning and model loaders.
- Getting introduced to Unsloth and its role in efficient LLM fine-tuning.

## Conclusion

In this lesson, I gained a better understanding of Hugging Face and Unsloth and their roles in modern AI development. I learned that Hugging Face provides a comprehensive ecosystem for working with pretrained models, datasets, and AI applications, while Unsloth helps optimize the fine-tuning process by reducing training time and GPU memory consumption.

I also learned important concepts such as fine-tuning. 
