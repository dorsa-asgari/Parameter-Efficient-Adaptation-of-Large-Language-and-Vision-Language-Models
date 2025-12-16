## Parameter-Efficient Adaptation of Large Language and Vision-Language Models

---

### Key Contributions

- **DeepSeek-OCR Fine-Tuning**  
  Fine-tuned DeepSeek-OCR on a 200K-sample Persian transcript dataset using Unsloth + LoRA (PEFT), achieving a 59% reduction in Character Error Rate (CER) compared to the base model.

- **Vision-Language Model Adaptation for Medical Imaging**  
  Fine-tuned LLaMA 3.2 Vision on the ROCO radiography dataset (X-rays, CT scans, and ultrasounds) using LoRA, enabling automated expert-level report generation for medical images.

- **Efficient NLP Model Adaptation**  
  Applied:
  - Prompt Tuning on T5 for text summarization  
  - Prefix-Tuning on T5-Large for financial sentiment classification  
  - P-Tuning** on RoBERTa for semantic equivalence detection  

  These methods achieved strong task-specific performance with significantly reduced training cost and memory usage.

---


