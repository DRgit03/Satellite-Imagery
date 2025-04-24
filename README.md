# Satellite-Imagery
Deep Learning-based Semantic Segmentation of Satellite Imagery using U-Net and TensorFlow for land cover classification and geospatial analysis


# 🛰️ Satellite Image Segmentation with U-Net (Tutorial-Based Project)

This project demonstrates how to perform **semantic segmentation on satellite imagery** using the U-Net deep learning architecture. The repository is built as a hands-on learning project, guided by a YouTube tutorial from DigitalSreeni, and explores both data preparation and deep learning model training for land cover classification.

📺 Tutorial reference: [https://www.youtube.com/@650AILab](https://www.youtube.com/watch?v=UBzMgr6yfpw&t=602s)

---

## 📌 Overview

Semantic segmentation of satellite imagery involves classifying each pixel in an image into meaningful categories (e.g., buildings, roads, vegetation). This project covers:

- Satellite image preprocessing
- Mask and label generation for semantic segmentation
- Deep learning model training using U-Net
- Model evaluation and interpretation using activation and gradient maps

---

## 🔧 Workflow Summary

### 📘 Part 1: Data Preparation
- Collect satellite imagery (e.g., from Google Maps or APIs)
- Divide large maps into smaller **image tiles**
- Generate corresponding **mask images** that label each pixel
- Assign **class labels** to pixel values in the mask
- Structure the dataset for deep learning

### 📗 Part 2: Deep Learning Model
- Implement the **U-Net architecture** in TensorFlow/Keras
- Preprocess images and masks (resize, normalize)
- Train the model using binary/categorical cross-entropy + Dice loss
- Evaluate model using metrics like IoU and pixel accuracy
- Visualize predictions and model performance
- Extract and visualize **activation maps and gradients** for model interpretability

---

## 🧰 Tech Stack

- **Python**
- **TensorFlow/Keras**
- **NumPy**, **OpenCV**, **Matplotlib**, **PIL**, **Patchify**, **Scikit-learn**
- **Jupyter Notebook** (Google Colab-ready)

---

## 📂 Project Structure

```
├── Satellite imagery base.ipynb      # Full pipeline: preprocessing, training, evaluation
├── models/                           # Saved trained models (.keras/.h5)
├── images/                           # Sample outputs (original, masks, predictions)
├── README.md                         # Project documentation
└── requirements.txt                  # Dependencies (to be added)
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/satellite-segmentation-unet.git
cd satellite-segmentation-unet
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook "Satellite imagery base.ipynb"
```

---

## 💡 Use Cases

- Land cover and urban feature classification
- Agricultural monitoring
- Forest and vegetation segmentation
- Disaster response mapping (floods, deforestation)

---

## 📊 Example Outputs

| Input Image | Ground Truth Mask | Predicted Mask |
|-------------|-------------------|----------------|
| ![](images/original.png) | ![](images/ground_truth.png) | ![](images/predicted.png) |

---

## 📜 License

This project is open-source and educational. Core tutorial credit goes to:
- [https://www.youtube.com/@650AILab on YouTube](https://www.youtube.com/watch?v=UBzMgr6yfpw&t=602s)

---

## 🙋‍♂️ Maintainer

**Dasaradaramu Munnangi**  
📧 ramumunnangi03@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dasarada-munnangi/)
