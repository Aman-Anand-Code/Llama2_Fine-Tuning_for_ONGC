# Llama2_Fine-Tuning_for_ONGC

# 🛢️ Fine-Tuning LLaMA 2 for Domain-Specific Knowledge Extraction in Oil and Gas

> Winter Internship Project at **ONGC (Oil and Natural Gas Corporation)**  
> **By:** Aman Anand | **KIIT University** | Roll No: 22052187

---

## 📌 Project Overview

This project focuses on fine-tuning Meta’s **LLaMA 2-7B Chat** model using domain-specific data from the *Oil and Gas Production Handbook*. The goal was to improve the model's ability to respond accurately and contextually to queries related to oil and gas production, history, and technical details.

---

## 🧠 Model & Techniques Used

- **Base Model:** LLaMA 2-7B Chat (from Hugging Face)
- **Fine-Tuning Method:** QLoRA (Quantized Low-Rank Adaptation)
- **Libraries:** PEFT, Transformers, BitsAndBytes, Datasets
- **Optimization:** 4-bit quantization for efficient training on limited hardware

---

## 📁 Dataset

The dataset was custom-built using the *Oil and Gas Production Handbook*. It includes instruction-style prompts aligned with oil and gas terminology, processes, and historical data.

- **File Name:** `oil_gas_dataset.json`
- **Format:** Instruction → Input → Output
- **Total Samples:** ~100 (curated and structured)

---

## 📊 Results

### 📉 Training Loss Progression:
| Step | Training Loss |
|------|----------------|
| 10   | 6.93           |
| 50   | 0.22           |
| 100  | 0.17           |
| 150  | 0.19           |
| 250  | 0.15           |

### ✅ Comparative Evaluation:

| Criteria | Base Model | Fine-Tuned Model |
|---------|-------------|------------------|
| Domain Relevance | 65% | 91% |
| Hallucination Rate | ~18% | <5% |
| Factual Consistency | Moderate | High |
| Contextual Accuracy | Inconsistent | Robust |

---

## 📦 Folder Structure


---

## 📅 Weekly Progress

- **Week 1:** Literature review & dataset curation  
- **Week 2:** Model setup and fine-tuning with QLoRA  
- **Week 3:** Evaluation and comparison with base model  
- **Week 4:** Documentation, results, and final reporting  

---

## 🖼️ Visuals

- ✅ LoRA & QLoRA Architecture Diagrams
- 📊 Training Loss Graphs
- 📄 Sample Output Comparisons

---

## 🧾 References

1. Meta AI - LLaMA 2: [https://ai.meta.com/llama](https://ai.meta.com/llama)
2. Hugging Face Transformers: [https://huggingface.co/docs/transformers](https://huggingface.co/docs/transformers)
3. QLoRA Paper: [https://arxiv.org/abs/2305.14314](https://arxiv.org/abs/2305.14314)
4. Oil and Gas Production Handbook (PDF Source)
5. PEFT Library: [https://github.com/huggingface/peft](https://github.com/huggingface/peft)
6. BitsAndBytes: [https://github.com/TimDettmers/bitsandbytes](https://github.com/TimDettmers/bitsandbytes)
7. Dataset Formatting Guide: [https://huggingface.co/docs/datasets](https://huggingface.co/docs/datasets)
8. LoRA GitHub: [https://github.com/microsoft/LoRA](https://github.com/microsoft/LoRA)
9. HuggingFace QLoRA Example: [https://huggingface.co/docs/peft/quicktour](https://huggingface.co/docs/peft/quicktour)
10. Training Framework (TRLLM): [https://github.com/huggingface/trl](https://github.com/huggingface/trl)
11. Visualization Tools: Matplotlib, Seaborn

---

## 🤝 Acknowledgements

- **ONGC** for providing the opportunity and domain insights  
- **IIT Madrs || KIIT University ** for academic support  
- **Hugging Face** community for open-source models and tools

---

## 📬 Contact

**Aman Anand**  
KIIT University  
✉️ Email: amananandsocial@gmail.com  


---

⭐ *If you found this useful, please star the repo and follow for more projects!*

