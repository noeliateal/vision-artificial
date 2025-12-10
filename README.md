# 🧠 Reconocimiento de Emociones Faciales con CNN

Proyecto de Visión Artificial cuyo objetivo es reconocer emociones faciales a partir de imágenes en escala de grises utilizando una **red neuronal convolucional (CNN)**. Desarrollado en **Python**, con **TensorFlow**, **Keras**, **OpenCV** y **Jupyter Notebook**.

---

## 🎯 Objetivo

Entrenar un modelo capaz de clasificar rostros humanos en distintas emociones:

😀 Felicidad  
😢 Tristeza  
😠 Enfado  
😮 Sorpresa  
😐 Neutral  
😖 Disgusto  
😨 Miedo  

---

## 🧩 Tecnologías utilizadas

- Python  
- TensorFlow  
- Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 📚 Dataset

El proyecto usa el dataset **FER2013**, ampliamente utilizado para clasificación de emociones. Además de **modelo_emociones.keras**.

Debido al tamaño de estos archivos, **no están incluidos en este repositorio**.

Puedes descargarlos aquí:

👉 https://drive.google.com/tu-enlace-aqui

---

## 🧠 Arquitectura del modelo CNN

- Capas Convolucionales (Conv2D) con activación ReLU  
- Capas de MaxPooling  
- Dropout para evitar overfitting  
- Flatten  
- Capas Densas (Fully Connected)  
- Softmax como activación final  

**Compilación:**
- Optimizer: Adam  
- Loss: Categorical Crossentropy  
- Métrica: Accuracy  




