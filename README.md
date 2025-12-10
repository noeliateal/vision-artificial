🧠 Proyecto: Reconocimiento de Emociones Faciales con CNN

Este proyecto implementa un modelo de Visión Artificial capaz de reconocer emociones faciales a partir de imágenes en escala de grises.
Fue desarrollado en Python, usando Keras, TensorFlow, OpenCV y ejecutado en Jupyter Notebook.

🚀 Objetivo del proyecto

Entrenar una red neuronal convolucional (CNN) capaz de clasificar imágenes faciales en distintas emociones como:

😊 Felicidad
😢 Tristeza
😠 Enfado
😮 Sorpresa
😐 Neutral

🧩 Tecnologías y librerías utilizadas

Python

Keras

TensorFlow

OpenCV

NumPy / Pandas

Matplotlib

Jupyter Notebook

📂 Estructura del repositorio
vision-artificial/
 ├── modelo_entrenado/ (si aplica)
 ├── imagenes_resultados/
 ├── notebook.ipynb
 ├── utils.py (si aplica)
 ├── README.md
 └── .gitignore

📁 Dataset utilizado

El modelo se entrenó con el dataset FER2013, un conjunto de imágenes en escala de grises ampliamente usado para clasificación de emociones faciales.

Debido al gran tamaño del dataset, no se incluye directamente en GitHub.

📥 Puedes descargarlo aquí:
👉 (Añade aquí tu enlace de Google Drive cuando lo tengas)

🧠 Arquitectura del modelo

La CNN utilizada sigue esta estructura básica:

Capas Conv2D con activación ReLU

Capas MaxPooling2D

Capas Dropout para reducir overfitting

Flatten

Dense (Fully Connected)

Softmax para la clasificación final

El modelo se entrenó durante varias épocas utilizando categorical crossentropy como función de pérdida y el optimizador Adam.

📉 Resultados del entrenamiento

Incluye aquí tus gráficas cuando las subas:

Accuracy vs. Epochs

Loss vs. Epochs

Puedes añadirlas así:

![Accuracy](./imagenes_resultados/accuracy.png)
![Loss](./imagenes_resultados/loss.png)

🧪 Ejemplos de predicciones

Añade imágenes de pruebas reales, por ejemplo:

![Ejemplo](./imagenes_resultados/prediccion1.png)

▶️ Cómo ejecutar el proyecto

Clonar este repositorio:

git clone https://github.com/TU_USUARIO/vision-artificial


Abrir el notebook:

jupyter notebook


Asegurarse de tener instalado:

pip install tensorflow keras opencv-python numpy matplotlib


Ejecutar las celdas del notebook.

📝 Notas

El dataset no está incluido por su tamaño.

Los modelos entrenados (.h5) solo pueden subirse si pesan menos de 25MB.

En caso contrario, deben añadirse mediante un enlace externo (Drive).

✨ Autora

Noelia Terrón
Estudiante de Tecnología Digital y Multimedia — UPV

📄 Licencia

MIT © 2025 Noelia Terrón

🔚 FIN DEL README
