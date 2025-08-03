# GPT2-medium-LoRa-News-Summary

# GPT-2 Medium - LoRA Fine-Tuned for News Summarization

This repository contains a LoRA fine-tuned version of [`gpt2-medium`](https://huggingface.co/openai-community/gpt2-medium), optimized for abstractive news summarization using the PEFT (Parameter-Efficient Fine-Tuning) method. The final model has been merged and exported for seamless inference via Hugging Face Transformers.

## 🔗 Model on Hugging Face

➡️ [Hugging Face Model Hub: `deDgod/gpt2-medium-lora-news-summary`](https://huggingface.co/deDgod/gpt2-medium-lora-news-summary)

---

## 🧠 Model Details

- **Base Model**: `openai-community/gpt2-medium`
- **Fine-Tuning Method**: [LoRA](https://arxiv.org/abs/2106.09685) via [PEFT](https://github.com/huggingface/peft)
- **Task**: Abstractive summarization (news domain)
- **Training Framework**: Hugging Face Transformers + PEFT

---

## 🛠️ Usage

### Install Dependencies

```bash
pip install transformers peft
