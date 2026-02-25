# MNIST Baseline MLP

Este proyecto contiene implementaciones y exploraciones de modelos Multi-Layer Perceptron (MLP) aplicados al famoso conjunto de datos MNIST (clasificación de dígitos escritos a mano). El objetivo principal del repositorio es comparar distintas bibliotecas de Machine Learning y Deep Learning en la misma tarea, así como documentar los resultados obtenidos.

## 📂 Estructura del Proyecto

El repositorio está organizado de la siguiente manera:

### 📓 Notebooks Principales (Raíz)
- **`main.ipynb`**: Notebook principal del proyecto. Implementa el modelo MLP utilizando TensorFlow/Keras, manejando el flujo de entrenamiento principal y la evaluación del modelo.
- **`pytorch.ipynb`**: Implementación de la red neuronal MLP utilizando el framework **PyTorch**.
- **`sklearn.ipynb`**: Implementación de un MLP clasificador utilizando la librería **Scikit-learn** (`MLPClassifier`), ideal para establecer un modelo base de comparación.

### 📁 Directorios

- **`notebooks/`**:
  - `exploration.ipynb`: Notebook dedicado al Análisis Exploratorio de Datos (EDA) del conjunto MNIST, visualización de imágenes y análisis estadístico de las clases.

- **`docs/`**: Contiene los informes detallados y reportes finales del proyecto:
  - `Informe_MLP_MNIST_Pytorch.pdf`: Documento explicativo centrado en la implementación en PyTorch.
  - `Informe_MLP_MNIST.pdf`: Reporte general de los resultados y la metodología del proyecto.

- **`results/`**: Almacena las visualizaciones y gráficas generadas durante el entrenamiento y la evaluación de los modelos:
  - `confusion_matrix_tensorflow.png`: Matriz de confusión generada a partir del modelo entrenado en TensorFlow.
  - `linear_graphic_accuracy.png`: Gráfico lineal que muestra la evolución de la precisión (accuracy) durante las épocas de entrenamiento.

### 📄 Otros Archivos
- **`requirements.txt`**: Archivo reservado para listar las dependencias de Python necesarias para replicar el entorno del proyecto.

- **`.venv/`**: Entorno virtual de Python (no se debe incluir en control de versiones).
- **`.gitignore`**: Archivos y directorios ignorados por Git.

## 🚀 Cómo empezar

1. Clona el repositorio.
2. Crea un entorno virtual e instala las dependencias (por ejemplo, desde `requirements.txt` cuando se definan, o instala manualmente `tensorflow`, `torch`, `scikit-learn`, `jupyter`, `matplotlib`).
3. Abre los Jupyter Notebooks ubicados en la raíz y en el directorio `notebooks/` para visualizar los flujos de trabajo de PyTorch, TensorFlow y Scikit-Learn.

## 📝 Autor
Proyecto desarrollado por **Xavi Far**.
