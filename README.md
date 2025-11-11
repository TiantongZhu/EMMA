# 🚑 EMMA: Emergency Medicine Multimodal Assistant
⚠️ We will upload the core code during this period.
The complete code and pretrained models will be released after the paper is published.
## 📢 Introduction

**EMMA (Emergency Medicine Multimodal Assistant)** is the first **domain‑specific multimodal large language model (MLLM)** designed for emergency medicine.  
Emergency medical scenarios require rapid reasoning under uncertainty, involving medical images (X‑ray, CT, MRI, Ultrasound, etc.) and clinical text (chief complaints, triage records, physician notes).

However, existing medical MLLMs face two major limitations:

1. **Limited data diversity** — Most multimodal medical datasets focus on a single disease or imaging modality and cannot represent real hospital emergency cases.
2. **High deployment cost** — Existing MLLMs require expensive infrastructure (multi‑GPU servers), making deployment difficult in resource‑limited hospitals.

To address these issues, we propose **EMMA**, a lightweight yet powerful multimodal model that supports:

- Diagnostic reasoning
- Multi‑turn medical VQA
- Zero‑shot generalization to unseen diseases & modalities

---

## ✅ Key Features

| Capability | Description |
|------------|-------------|
| 🏥 **Domain‑specialized MLLM** | First model optimized for emergency medicine workflows. |
| 📚 **EMMA‑20M dataset** | 20 million image–text samples from *10 imaging modalities* and *60+ disease categories*. |
| 🔧 **Automatic weak‑supervision annotation pipeline** | Coarse caption → ROI localization → fine caption, *no manual labeling required*. |
| ⚙️ **Three‑stage progressive fine‑tuning** | Visual–text alignment → instruction tuning → VQA downstream adaptation. |
| 🖥 **Low‑cost deployment** | EMMA‑3B runs on **a single RTX 4090 GPU (≈USD $1000)**. |
| 🥇 **State‑of‑the‑art performance** | Outperforms GPT‑4V, Gemini 1.0, and DeepSeek‑VL‑7B on external clinical datasets (CheXpert, PadChest, GMAI‑MMBench). |

---
