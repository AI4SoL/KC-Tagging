# Towards Scalable Annotation of Math Word Problems

This repository contains the code and data accompanying the ICCE 2025 paper:

**“Towards Scalable Annotation of Math Word Problems: Knowledge Component Tagging via LLMs and Sentence Embeddings”**  
by Chor Seng Tan, Chengwei Wei, and Jung-Jae Kim  (Institute for Infocomm Research, A*STAR, Singapore)

📄 Accepted at **The 33rd International Conference on Computers in Education (ICCE 2025)**.


## 📊 Dataset

We release the **Knowledge Component (KC) Tagging Dataset**, a collection of mathematical word problems annotated with step-level **knowledge components (KCs)**.

- **Hugging Face Datasets**: 👉 [AI4SoL/KC_Tagging](https://huggingface.co/datasets/AI4SoL/KC_Tagging)  
- Includes splits from **ASDiv, GSM8K, and MATH**  
- KC taxonomy provided in [`coherence_map.csv`](https://github.com/AI4SoL/KC-Tagging/blob/main/coherence_map.csv)  
- **Status:**  
  - ✅ ASDiv fully annotated  
  - ⚠️ GSM8K and MATH splits under construction (partial annotations available)


## 📂 Repository Structure

- `coherence_map.csv` – Unified KC taxonomy across datasets  
- `README.md` – Project overview (this file)


## 📖 Citation

If you use this dataset or code, please cite our ICCE 2025 paper and the original source datasets (ASDiv, GSM8K, MATH).

```
@inproceedings{tan2025kc,
  author    = {Chor Seng Tan and Chengwei Wei and Jung-Jae Kim},
  title     = {Towards Scalable Annotation of Math Word Problems: Knowledge Component Tagging via LLMs and Sentence Embeddings},
  booktitle = {Proceedings of the 33rd International Conference on Computers in Education (ICCE 2025)},
  year      = {2025},
  publisher = {Asia-Pacific Society for Computers in Education},
}
```
