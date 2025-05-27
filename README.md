🧠 Brain Tumor Detection with MRI Images Using SRGAN

---

📌 Project Overview

This project leverages **Super-Resolution Generative Adversarial Networks (SRGAN)** to enhance the resolution of MRI brain images, significantly improving tumor detection and classification accuracy. By combining SRGAN with **deep learning models** such as EfficientNetV2 and advanced segmentation networks like U-Net and Mask R-CNN, the system enables accurate and reliable brain tumor detection, supporting medical professionals in clinical decision-making.

---

🚀 Features

* 🏥 **Super-Resolution Enhancement**: SRGAN enhances low-resolution MRI scans to high-resolution, preserving anatomical details.
* 🎯 **Deep Learning Classification**: EfficientNetV2-based CNN architecture classifies MRI scans into tumorous and non-tumorous.
* 🌐 **Tumor Segmentation**: U-Net and Mask R-CNN provide precise tumor boundary segmentation.
* 📊 **Performance Evaluation**: Utilizes PSNR, SSIM, accuracy, precision, recall, and F1-score for comprehensive assessment.
* 💻 **User-Friendly Interface**: GUI built with Tkinter for streamlined image upload and diagnosis.

---

📂 Project Structure

```
📦 Brain-Tumor-Detection-SRGAN
│── 📂 dataset/                     # MRI scans (Tumorous & Non-Tumorous)
│── 📂 model_weights/               # Pretrained SRGAN and classifier weights
│── 📂 gui/                         # GUI application files
│── 📂 notebooks/                   # Jupyter Notebooks for EDA & training
│── ├── train.py                    # Model training script
│── ├── predict.py                  # MRI image prediction script
│── ├── app.py                      # Flask/FastAPI-based web application
│── ├── gui.py                      # Tkinter-based GUI application
│── ├── requirements.txt            # Dependencies
│── ├── README.md                   # Project documentation
```

---

🔧 Installation & Setup

1️⃣ Clone the repository:

```bash
git clone https://github.com/yourusername/Brain-Tumor-Detection-SRGAN.git
cd Brain-Tumor-Detection-SRGAN
```

2️⃣ Install the required dependencies:

```bash
pip install -r requirements.txt
```

3️⃣ Run the GUI application:

```bash
python gui.py
```

4️⃣ (Optional) Train the model:

```bash
python train.py
```

---

🎯 Usage

1. Open the **GUI application**.
2. Upload a **low-resolution MRI image**.
3. Click **Enhance** to generate a high-resolution version using SRGAN.
4. Click **Predict** to classify the image as **tumorous** or **non-tumorous** and perform segmentation.

---

## ⚡ SRGAN Image Enhancement

* **Generator Network**: Reconstructs high-resolution MRI images from low-resolution inputs while preserving anatomical details.
* **Discriminator Network**: Validates the authenticity of generated images to ensure structural accuracy.
* **Evaluation Metrics**:

  * **PSNR (Peak Signal-to-Noise Ratio)**
  * **SSIM (Structural Similarity Index)**

---

## 📊 Model Performance

* **Image Enhancement Metrics**:

  * **PSNR**: High-quality enhancement preserving details.
  * **SSIM**: Ensures structural similarity between enhanced and original high-resolution images.
* **Classification Accuracy**: 98.5%
* **Validation Accuracy**: 95.7%
* **Precision/Recall (Tumor)**: 96.3% / 94.1%

---

## 🤝 Contributors

* **Dhanush Kumar S**
* **Hari Prasath D**
* **Harish Kumar M**
* **Guide**: Mr. T. Dinesh Kumar

---

## 📜 License

This project is **open-source** under the **MIT License**.

---

## 📩 Contact

For feature requests, queries, or contributions:
📧 **[haridharmaraj2128@gmail.com](mailto:haridharmaraj2128@gmail.com)**

---

