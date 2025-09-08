# 🩺 Explainable AI for Pneumonia Detection

This project explores the use of **Explainable Artificial Intelligence (XAI)** in medical imaging.  
We developed a **Convolutional Neural Network (CNN)** trained on the [PneumoniaMNIST dataset](https://medmnist.com/) and integrated a custom explainability algorithm inspired by **LIME** to detect pneumonia in chest X-ray scans.  

Unlike traditional “black-box” AI, this model highlights the **specific pixels that most influenced predictions**, allowing doctors to better understand and trust the system’s outputs.  

---

## 🚀 Features
- **CNN Model** built in **PyTorch** with ~90% accuracy on 28×28 chest X-rays.  
- **XAI Module** that identifies and overlays the most important pixels for each prediction.  
- **Visualization Tools** for medical professionals to see where pneumonia is most likely located.  
- **Model-Agnostic Approach** – explainability method can be applied to other ML models.  
- **Proof-of-Concept Tool** for integrating AI into healthcare with transparency and trust.  

---

## 🛠️ Tech Stack
- **Python** (Google Colab environment, PyTorch 2.1, CUDA 11.8)
- **Deep Learning**: Convolutional Neural Networks (CNNs)  
- **Dataset**: PneumoniaMNIST (5,856 grayscale X-rays)  
- **XAI**: Custom pixel-perturbation method (inspired by LIME)  

---

## 📊 Results
- **Accuracy**: ~90% after 15 epochs  
- **Explainability**: Visual heatmaps highlight pneumonia regions in lungs  
- **Interpretability**: Identifies false predictions by analyzing unusual pixel activation patterns  

---

## 📸 Example Outputs
![Original X-ray](https://github.com/AntNeedsHelp/ExplainableAI/blob/main/images/originalchest.png)
![Heatmap of Important Pixels](https://github.com/AntNeedsHelp/ExplainableAI/blob/main/images/heatmap.png)
![Overlayed Pixels](https://github.com/AntNeedsHelp/ExplainableAI/blob/main/images/overlayed.png)

---

## 📥 Usage
Simply open the linked GoogleCollab notebook and run it using the **T4 GPU** runtime
