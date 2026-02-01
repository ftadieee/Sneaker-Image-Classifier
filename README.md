# 👟 Sneaker Image Classifier (VibeCoded)

![Sneaker Classifier Header](C:/Users/adity/.gemini/antigravity/brain/9a0059ce-944b-43c9-acd7-547a7bdb8376/sneaker_classifier_mockup_1769934402635.png)

## 🚀 Overview
**Sneaker Image Classifier** is a deep learning project built using **TensorFlow** and **Keras** to identify and classify sneaker brands from images. The current version is optimized to recognize major brands: **Nike**, **Adidas**, and **Puma**.

This project was developed with a "VibeCoded" approach—combining powerful AI logic with a focus on ease of use and modern aesthetics.

---

## ✨ Features
- **Multi-Brand Recognition**: Accurately classifies shoes into Nike, Adidas, or Puma categories.
- **Data Augmentation**: Uses smart image preprocessing (flipping, rotation) to improve accuracy even with small datasets.
- **Interactive Testing**: Features a built-in upload prompt to test the model on your own sneaker photos instantly.
- **Confidence Scoring**: Displays a percentage confidence level for every prediction.

---

## 🛠️ Tech Stack
- **Core Framework**: TensorFlow 2.x & Keras
- **Environment**: Google Colab (with T4 GPU support)
- **Programming Language**: Python 3
- **Libraries**:
    - `NumPy`: For numerical operations
    - `OS`: For file and folder management
    - `Matplotlib`: For data visualization (potential feature)

---

## 🏗️ How it Works
The classifier follows a robust Convolutional Neural Network (CNN) pipeline:
1.  **Folder Setup**: Automatically organizes your training data into brand-specific subdirectories.
2.  **Preprocessing**: Rescales images to $224 \times 224$ and normalizes pixel values.
3.  **Model Architecture**:
    - **Convolutional Layers**: Extracts features like textures, stitching, and brand logos.
    - **Pooling Layers**: Reduces dimensionality while preserving key patterns.
    - **Dense Layers**: Performs the final classification using Softmax activation.
4.  **Training**: Runs for 10 epochs with the Adam optimizer for fast and stable convergence.

---

## 🚦 Getting Started

### Prerequisites
- A Google Account (to use Google Colab) or a local Python environment with GPU support.

### Running the Project
1.  Open the `sneaker_project_final_version.ipynb` file in **Google Colab**.
2.  Enable GPU Acceleration: `Runtime` > `Change runtime type` > `GPU`.
3.  Run the first cell. It will prompt you to:
    - Upload **Nike** images.
    - Upload **Adidas** images.
    - Upload **Puma** images.
4.  Once trained, use the final cell to upload a "mystery" sneaker image and see the model in action!

---

## 📊 Results & Future Scope
- **Current Performance**: Reaches stable accuracy within 10 epochs.
- **Roadmap**:
    - [ ] Support for more brands (Jordan, Converse, New Balance).
    - [ ] Real-time classification via webcam.
    - [ ] Mobile app integration.

---

## 🤝 Contributing
Contributions are welcome! If you have ideas to improve the model architecture or want to add support for new brands, feel free to fork the repo and submit a PR.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---
*Created with ❤️ by ftadieee*
