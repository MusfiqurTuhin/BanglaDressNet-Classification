# 🇧🇩 BanglaDressNet: Traditional Bangladeshi Dress Dataset

![Language](https://img.shields.io/badge/Language-Bengali-green?style=for-the-badge&logo=google-translate&logoColor=white)
![Task](https://img.shields.io/badge/Task-Image%20Classification-red?style=for-the-badge&logo=mediafire&logoColor=white)
![Size](https://img.shields.io/badge/Size-8K%20Images-blue?style=for-the-badge&logo=files&logoColor=white)
![License](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey?style=for-the-badge)

## 📄 Context
**Official dataset** for the research paper:
> **"Multi-Level Ensemble Learning for Fine-Grained Classification of Traditional Bangladeshi Dress Using Deep Transfer Models"**
> *Accepted at: 2025 7th International Conference on Electrical Information and Communication Technology (EICT)*

**BanglaDressNet** is a fine-grained image dataset designed to classify traditional Bangladeshi clothing. It contains **8,000 images** across **16 distinct categories**, addressing the challenge of recognizing culturally significant attire with subtle visual differences.

---

## 🔗 Associated Resources

| Resource | Link |
| :--- | :--- |
| 📄 **Paper** | *Awaiting Publication* |
| 🐙 **GitHub Repository** | [![GitHub](https://img.shields.io/badge/GitHub-Repo-black?style=flat&logo=github)](https://github.com/MusfiqurTuhin/BanglaDressNet-Classification) |
| 🤗 **Hugging Face** | [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Dataset-yellow?style=flat&logo=huggingface)](https://huggingface.co/datasets/musfiqurtuhin/bangladressnet) |

---

## 💾 Dataset Specifications

The dataset was collected via web scraping and filtered using perceptual hashing to ensure quality and diversity.

-   **Total Images:** 8,000
-   **Classes:** 16
-   **Split:** 70% Train, 15% Validation, 15% Test
-   **Preprocessing:** Images are resized to 224x224 pixels.

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

## 🧠 Benchmarks

The dataset was benchmarked using 10 ImageNet-pretrained CNNs. The proposed **Weighted Averaging Ensemble** achieved state-of-the-art performance.

| Model | Test Accuracy | F1-Score |
| :--- | :---: | :---: |
| **Weighted Avg. Ensemble** | **96.75%** | **0.9675** |
| DenseNet121 | 95.75% | 0.9579 |
| EfficientNetB1 | 95.58% | 0.9558 |
| Xception | 94.75% | 0.9472 |

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

---

## 📬 Contact

For questions, please contact the authors via the [GitHub Repository](https://github.com/MusfiqurTuhin/BanglaDressNet-Classification).
