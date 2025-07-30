# Finetuning-Multimodal-LLMs

This project focuses on fine-tuning lightweight multimodal large language models (**MobileVLM-3B** and **Qwen2-VL-2B-Instruct**) for **Visual Question Answering (VQA)** tasks. It uses public datasets such as **SEED-Bench** and **K-MMStar (translated to English)** to adapt open-source VLMs for downstream multimodal reasoning.

## Models & Datasets
### MobileVLM-3B
- **Model**: [MobileVLM-3B](https://huggingface.co/mtgv/MobileVLM-3B)
- **Dataset**: [SEED-Bench](https://huggingface.co/datasets/lmms-lab/SEED-Bench)

### Qwen2-VL-2B-Instruct
- **Model**: [Qwen2-VL-2B](https://huggingface.co/Qwen/Qwen2-VL-2B-Instruct)
- **Dataset 1**: [K-MMStar](https://huggingface.co/datasets/NCSOFT/K-MMStar)
  - Translated to English using Qwen2-7B
- **Dataset 2**: [SCPC AI Contest Dataset](https://dacon.io/competitions/official/236500/data)

## Environment
- Google Colab Pro+
- 1 A100 40GB GPU, 80GB RAM
