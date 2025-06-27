# 🦾 BART Large Fine-Tuning for Text2Text Generation

This project demonstrates how to fine-tune the **facebook/bart-large** model using custom JSONL data for text-to-text generation tasks.

---
## 📚 Dataset Format

The dataset files (`train.jsonl` and `val.jsonl`) are JSON Lines files with records like:

```json
{
  "input": "He is Rohit. He is very good guy, increase his salary to 5000",
  "output": "{\"instructions\": [\"raise salary to 5000\"], \"actions\": [\"modify prorated salary\"], \"user_info\": {\"name\": \"Rohit\"}}"
}
```

## Environment Setup
```
  pip install transformers datasets torch
```
