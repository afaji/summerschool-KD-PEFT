# Mexican NLP 2024 Summer School Tutorial on Knowledge Distillation and Parameter Efficient Fine-tuning

The slides can be found here

## Code Examples:
* [Baseline Training](https://colab.research.google.com/drive/1ZIesmJ9v5QO5tAOEDtDZDfaj-6xlKcRi?usp=sharing): This notebook shows an example of fine-tuning BERT for a standard classification task.
* [Small Model Training](https://colab.research.google.com/drive/1CrMo2k1kc8ZJCbmOMmJjNg81ZjYAX4lP?usp=sharing): Similar to Baseline Training, but now we train a significantly smaller model from scratch.
* [Small Model Training + KD](https://colab.research.google.com/drive/1d4AKfg5bLIyuTdP7Jsp-VnH_vgbYckts?usp=sharing): We train the small model from scratch with knowledge distillation, using the baseline training as the teacher.
* [Small Model Training + Optimized KD](https://colab.research.google.com/drive/1ZuXhQufB-4Nu_pwaLlZpJ3X0409J3A2k?usp=sharing): We optimize the knowledge distillation by caching the teacher's logits.
* [Baseline Training with LoRA](https://colab.research.google.com/drive/1ZIesmJ9v5QO5tAOEDtDZDfaj-6xlKcRi?usp=sharing): We re-train the baseline model with LoRA.
