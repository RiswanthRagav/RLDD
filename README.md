# 🌾 Rice Leaf Disease Detection Using Fusion Optimization  

### 🚀 Overview  
This project presents an AI-powered web application designed to detect **rice leaf diseases** such as *Brown Spot*, *Leaf Blast*, and *Hispa* using **Deep Learning fusion techniques**.  
By combining the strengths of **ResNet** and a custom **CNN ensemble**, the system achieves high accuracy in identifying diseases from uploaded leaf images, supporting farmers and researchers with **real-time, data-driven insights** for sustainable agriculture.  

---

### 🧠 Key Features  
- **Fusion-Based Deep Learning Model:** Combines ResNet50 and CNN models to enhance prediction accuracy.  
- **Web Interface (Flask + HTML):** User-friendly platform for uploading leaf images and receiving instant results.  
- **Explainable Results:** Displays disease name, cause, and treatment recommendations.  
- **Real-Time Processing:** Fast image inference powered by TensorFlow/Keras.  
- **Precision Agriculture:** Enables early detection, improved crop yield, and reduced pesticide usage.  

---

### 🧩 Technical Architecture  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Flask (Python)  
- **Framework:** TensorFlow / Keras  
- **Models Used:**  
  - Custom Convolutional Neural Network (CNN)  
  - ResNet50 (pre-trained on ImageNet)  
  - Fusion Layer combining ensemble predictions  
- **Dataset:** Rice Leaf Disease Dataset (Kaggle) – 5,678 images (*Brown Spot*, *Leaf Blast*, *Hispa*, *Healthy*)  
- **Development Platform:** Google Colab  

---

### 📈 Model Performance  
| Metric | Score |
|:--|:--:|
| **Accuracy** | **95.43%** |
| Precision | 90.2% |
| Recall | 82.6% |
| F1-Score | 87.6% |

The **fusion ensemble model** outperformed standalone CNN and ResNet implementations, delivering higher robustness across lighting and environmental variations.  

---

### 🌿 Diseases Detected  
1. **Brown Spot (Bipolaris oryzae)** – Fungal infection causing circular brown lesions.  
2. **Leaf Blast (Magnaporthe oryzae)** – Greyish spots with dark margins that destroy tissues.  
3. **Hispa (Dicladispa armigera)** – Insect infestation creating shot-hole patterns on leaves.  
4. **Healthy** – Indicates no visible disease detected.  

---

### 🖥️ How It Works  
1. Upload an image of a rice leaf.  
2. The system preprocesses the image and passes it through the fusion model.  
3. Outputs from ResNet and CNN are merged for the final prediction.  
4. The app displays the detected disease, its cause, and suggested remedy. 
