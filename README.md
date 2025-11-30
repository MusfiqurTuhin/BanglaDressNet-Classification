# 🇧🇩 BanglaDressNet: Fine-Grained Classification of Traditional Bangladeshi Dress

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Official repository for the conference paper:
**"Multi-Level Ensemble Learning for Fine-Grained Classification of Traditional Bangladeshi Dress Using Deep Transfer Models"**

> *Accepted at: 2025 7th International Conference on Electrical Information and Communication Technology (EICT)*
> *18–20 December 2025, Khulna University of Engineering & Technology, Khulna-9203, Bangladesh*

---

## 📄 Abstract
The fine-grained classification of traditional costumes is challenging due to subtle differences between categories and significant internal variations. This paper introduces **BanglaDressNet**, an 8,000-image dataset of **16 categories** of Bangladeshi dresses (e.g., Saree, Panjabi, Lungi) collected through web scraping and filtered with perceptual hashing.

We evaluated 10 ImageNet-pretrained CNNs via transfer learning. The best three models—**DenseNet121**, **EfficientNetB1**, and **Xception**—achieved test accuracies of 95.75%, 95.58%, and 94.75%, respectively. To enhance performance, we proposed three ensemble strategies: validation accuracy-weighted averaging, stacked logistic regression, and stacked MLP. The **Weighted Averaging Ensemble** achieved the highest performance with **96.75% test accuracy**, **96.75% F1-score**, and **99.91% macro ROC-AUC**.

---

## 🔗 Quick Links

| Resource | Link |
| :--- | :--- |
| 📄 **Paper** | *Awaiting Publication* |
| 🐍 **Kaggle Dataset** | [![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?style=flat&logo=kaggle)](https://www.kaggle.com/datasets/musfiqurtuhin/bangladressnet) |
| 🤗 **Hugging Face** | [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Dataset-yellow?style=flat&logo=huggingface)](https://huggingface.co/datasets/musfiqurtuhin/bangladressnet) |

---

## 💾 Dataset Description

**BanglaDressNet** is a fine-grained dataset for traditional Bangladeshi dress classification.

-   **Total Images:** 8,000
-   **Classes:** 16 Traditional Dress Categories
-   **Split:** 70% Train, 15% Validation, 15% Test
-   **Preprocessing:** Resized to 224x224, Normalized

### Class List
1.  Blouse
2.  Dhoti
3.  Dupatta
4.  Fatua
5.  Frock
6.  Gamcha
7.  Koti
8.  Lungi
9.  Maxi
10. Muffler
11. Panjabi
12. Petticoat
13. Salwar-Kameez
14. Sando-Genji
15. Saree
16. Shawl

---

## 🧠 Methodology

We employed a **Multi-Level Ensemble Learning** approach to capture diverse features from different architectures.

### Models Implemented
-   **DenseNet121** (Texture features)
-   **EfficientNetB1** (Multi-scale features)
-   **Xception** (Shape features)
-   **Ensemble Strategies:**
    -   Weighted Averaging
    -   Stacked Logistic Regression
    -   Stacked MLP

---

## 📊 Result Analysis

Our proposed **Weighted Averaging Ensemble** outperformed individual models and other ensemble techniques.

| Model | Test Accuracy | F1-Score | ROC-AUC |
| :--- | :---: | :---: | :---: |
| **Weighted Avg. Ensemble** | **96.75%** | **0.9675** | **0.9991** |
| Stacking LR | 96.58% | 0.9659 | 0.9980 |
| Stacking MLP | 96.50% | 0.9651 | 0.9970 |
| DenseNet121 | 95.75% | 0.9579 | 0.9989 |
| EfficientNetB1 | 95.58% | 0.9558 | 0.9991 |
| Xception | 94.75% | 0.9472 | 0.9981 |

---

## 📝 Citation

If you use this dataset or code in your research, please cite our paper:

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

---

## 👥 Authors

-   **Md. Musfiqur Rahman**
-   **Sudipa Biswas**
-   **S.N.M. Rayhan**
-   **Md Shohan Mia**
-   **Md Mahbubur Rahman Tusher**

---

## 📬 Contact

For any questions, please open an issue in this repository or contact the authors.