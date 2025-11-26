# Medical Image Segmentation – Brain Tumor Detection

This project applies deep learning to **segment brain tumors** in MRI scans. Two models were explored: a **CNN** (main model) and a **Feedforward Neural Network (FNN)** (for testing/comparison). The CNN model is now available on **Hugging Face**, and a live demo allows anyone to try it.

---

## Project Highlights

- Deep learning-based brain tumor segmentation using **CNN**  
- Evaluation metrics: **Dice Coefficient**, **IoU**, **Precision**, **Recall**  
- Feedforward model included for comparison; not suitable for segmentation  
- Fully implemented and tested in **Google Colab**  
- CNN model available for **direct use via Hugging Face Hub**  
- **Interactive demo** hosted for instant testing  

---

## Dataset

- Brain MRI images: [Kaggle – Brain Tumor Segmentation](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation)  
- Preprocessed with **resizing** and **normalization**  
- Split into **train/validation/test** sets  

---

## Results

| Model | Dice Score | IoU | Precision | Recall |
|-------|------------|-----|-----------|--------|
| CNN   | 0.7019     | 0.4996 | 0.7860 | 0.7714 |
| FNN   | 0.3478     | 0.4959 | 0.5319 | 0.4377 |

> CNN clearly outperforms FNN and is the main working model.

---

## Try It

- **Model**: [yaraa11/brain-tumor-segmentation](https://huggingface.co/yaraa11/brain-tumor-segmentation)  
- **Demo **: [Try the Model Online](https://huggingface.co/spaces/yaraa11/brain-tumor-segmentation-app)
- **CNN Colab Notebook**: [Open in Colab](./CNN_Model.ipynb)  
- **FNN Colab Notebook**: [Open in Colab](./FeedForwardModel.ipynb)  

> You can directly use the model in your own projects or test it live via the demo.

---

## Tools & Libraries

- **Python**, **TensorFlow**  
- **NumPy**, **Matplotlib**  
- **Google Colab** for training and testing  
- **Hugging Face Hub** for model hosting and demo  

---

## Notes

- CNN is the **main working model**; FNN is included for experimentation  
- Hugging Face integration makes it easy to **reuse the model or try it without setup**
