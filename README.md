# Towards Scalable Annotation of Math Word Problems

This repository provides the **code** and **datasets** for our ICCE 2025 paper:

> **“Towards Scalable Annotation of Math Word Problems: Knowledge Component Tagging via LLMs and Sentence Embeddings”**  
> *Chor Seng Tan, Chengwei Wei, and Jung-Jae Kim*  
> Institute for Infocomm Research, A*STAR, Singapore

📄 Accepted at the **33rd International Conference on Computers in Education (ICCE 2025)**.

---

## 📊 Knowledge Component (KC) Tagging Dataset

We release the **KC Tagging Dataset**, a collection of mathematical word problems annotated at the **step level** with **knowledge components (KCs)**.  

**Key resources:**
- 🤗 Hugging Face dataset: [AI4SoL/KC_Tagging](https://huggingface.co/datasets/AI4SoL/KC_Tagging)  
- KC taxonomy: [`coherence_map.csv`](https://github.com/AI4SoL/KC-Tagging/blob/main/coherence_map.csv)  

**Included splits:**
- **ASDiv** (fully annotated)  
- **GSM8K** (in progress; partial annotations available)  
- **MATH** (in progress; partial annotations available)  

**Status:**  
- ✅ **ASDiv** complete  
- ⚠️ **GSM8K** and **MATH** under construction (updates will follow)  



## 📂 Repository Structure

- `coherence_map.csv` – KC description
- `README.md` – Project overview


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
