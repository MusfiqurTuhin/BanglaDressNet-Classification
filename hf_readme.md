---
annotations_creators:
- expert-generated
language_creators:
- expert-generated
language:
- bn
license:
- cc-by-4.0
multilinguality:
- monolingual
size_categories:
- 1K<n<10K
source_datasets:
- original
task_categories:
- image-classification
task_ids:
- multi-class-image-classification
pretty_name: BanglaDressNet
tags:
- fashion
- clothing
- bangladesh
- culture
- classification
dataset_info:
  features:
  - name: image
    dtype: image
  - name: label
    dtype:
      class_label:
        names:
          '0': Blouse
          '1': Dhoti
          '2': Dupatta
          '3': Fatua
          '4': Frock
          '5': Gamcha
          '6': Koti
          '7': Lungi
          '8': Maxi
          '9': Muffler
          '10': Panjabi
          '11': Petticoat
          '12': Salwar-Kameez
          '13': Sando-Genji
          '14': Saree
          '15': Shawl
---

# 🇧🇩 BanglaDressNet: Traditional Bangladeshi Dress Dataset

![Language](https://img.shields.io/badge/Language-Bengali-green?style=for-the-badge&logo=google-translate&logoColor=white)
![Task](https://img.shields.io/badge/Task-Image%20Classification-red?style=for-the-badge&logo=mediafire&logoColor=white)
![Size](https://img.shields.io/badge/Size-8K%20Images-blue?style=for-the-badge&logo=files&logoColor=white)
![License](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey?style=for-the-badge)

## 📄 Context
**Official dataset** for the research paper:
> **"Multi-Level Ensemble Learning for Fine-Grained Classification of Traditional Bangladeshi Dress Using Deep Transfer Models"**
> *Accepted at: 2025 7th International Conference on Electrical Information and Communication Technology (EICT)*

This dataset, **BanglaDressNet**, contains **8,000 images** of **16 categories** of traditional Bangladeshi attire, collected to facilitate fine-grained classification and cultural heritage preservation.

---

## 🔗 Associated Resources

| Resource | Link |
| :--- | :--- |
| 📄 **Paper** | *Awaiting Publication* |
| 🐙 **GitHub Repository** | [![GitHub](https://img.shields.io/badge/GitHub-Repo-black?style=flat&logo=github)](https://github.com/MusfiqurTuhin/BanglaDressNet-Classification) |
| 🐍 **Kaggle Dataset** | [![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?style=flat&logo=kaggle)](https://www.kaggle.com/datasets/musfiqurtuhin/bangladressnet) |

---

## 💾 Dataset Specifications

| Feature | Details |
| :--- | :--- |
| **Total Images** | **8,000** |
| **Classes** | 16 |
| **Format** | JPG/PNG |
| **Preprocessing** | Resized to 224x224 |

### Class Breakdown
1.  **Blouse**
2.  **Dhoti**
3.  **Dupatta**
4.  **Fatua**
5.  **Frock**
6.  **Gamcha**
7.  **Koti**
8.  **Lungi**
9.  **Maxi**
10. **Muffler**
11. **Panjabi**
12. **Petticoat**
13. **Salwar-Kameez**
14. **Sando-Genji**
15. **Saree**
16. **Shawl**

---

## 🚀 Quick Start

```python
from datasets import load_dataset

# Load the dataset
dataset = load_dataset("musfiqurtuhin/bangladressnet")

# View a sample
print(dataset['train'][0])
```

---

## 🤝 Citation

If you use this dataset, please cite our work:

```bibtex
@misc{md__musfiqur_rahman_2025,
	title={BanglaDressNet},
	url={https://www.kaggle.com/dsv/13932271},
	DOI={10.34740/KAGGLE/DSV/13932271},
	publisher={Kaggle},
	author={Md. Musfiqur Rahman},
	year={2025}
}
```
