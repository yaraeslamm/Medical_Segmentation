#  Medical Image Segmentation – Tumor Detection

This project applies deep learning to segment brain tumors in MRI scans. Two models were explored: a **CNN** (main model) and a **Feedforward Neural Network** (for testing/comparison).

---

## Project Highlights

- Used **TensorFlow** to train CNN on brain MRI data
- Evaluated segmentation using **Dice Coefficient** and **IoU**
- Feedforward model used only as a trial — not suited for segmentation
- Built and tested in **Google Colab**

---

## Dataset

- Brain MRI image dataset :https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation
- Preprocessed with resizing and normalization
- Split into train/val/test sets

---

## Results

| Model | Dice Score | IoU | Precision | Recall |
|-------|------------|-----|-----------|--------|
| CNN   | 0.7019     | 0.4996 |   0.7860     |    0.7714    |
| FNN   |  0.3478    | 0.4959  | 0.5319 |  0.4377    |

---

## Try It

- [Open the CNN Colab Notebook](https://colab.research.google.com/drive/1b5m5f4l37SRn7kx3XtKAgEEIrL2wI3U7?usp=sharing)
- [Open the FNN Colab Notebook](https://colab.research.google.com/drive/12EeE7GivImIqn3a3vpD9DhLajhTmLpmt?usp=sharing)
- Or view the full `.ipynb` in this repo

---

## 🔧 Tools

- Python, TensorFlow
- NumPy, Matplotlib
- Google Colab

---

## Notes

- The CNN is the main working model
- The feedforward model is included for learning/comparison
