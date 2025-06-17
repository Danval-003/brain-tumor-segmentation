# Brain Tumor Segmentation with U-Net

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)]()

---

## 🌟 Project Overview

This repository demonstrates a deep learning solution for segmenting brain tumors from MRI scans using a U-Net architecture. It generates binary masks that precisely highlight tumor regions by applying advanced preprocessing techniques and rigorous evaluation metrics.

All implementation details can be found in the Jupyter Notebook:

* **`brain_tumor_seg.ipynb`** – End-to-end pipeline: data loading, preprocessing, model training, evaluation, and visualization.

---

## ⚙️ Features

* **Custom Preprocessing**: Implements CLAHE, Sobel filters, and Difference of Gaussians (DoG) to enhance tumor boundaries.
* **Core U-Net Architecture**: Utilizes an encoder–decoder structure for accurate segmentation.
* **Attention U-Net Extension**: Optional attention gates to prioritize relevant image regions.
* **Comprehensive Metrics**: Evaluates performance with Intersection over Union (IoU), precision, recall, and F1-score.
* **Visualization Tools**: Overlays predicted masks on MRI slices and generates performance curves.

---

## 📋 Requirements

* Python 3.8 or higher
* Jupyter Notebook
* TensorFlow (>=2.4)
* NumPy
* OpenCV
* Matplotlib
* scikit-learn
* tqdm

---

## 📈 Results & Evaluation

- Performance metrics (IoU, precision, recall, F1-score) are calculated and displayed.
- Visual comparison of ground-truth vs. predicted masks included.

![image](https://github.com/user-attachments/assets/5c09c1f9-70d6-45cd-bb02-fbc033ced5ed)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m "Add feature"`
4. Push branch: `git push origin feature/YourFeature`
5. Open a Pull Request

Please follow existing code style and include tests where applicable.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- **U-Net paper** by Ronneberger et al.
- Public MRI datasets and preprocessing techniques.

---

*Happy segmenting!*


