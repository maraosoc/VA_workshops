# 🧠👀 VA_workshops: Talleres de Visión por Computador

Este repositorio contiene una serie de talleres prácticos enfocados en el aprendizaje de técnicas modernas de **visión artificial** utilizando Python, PyTorch y herramientas complementarias. Cada taller está diseñado para abordar un aspecto fundamental del procesamiento de imágenes y detección de objetos, con implementaciones desde cero y análisis didáctico.

---

## 🧩 Talleres incluidos

1. **VA101: Fundamentos de imágenes y transformaciones**
   - Lectura, visualización y manipulación de imágenes.
   - Transformaciones geométricas, convoluciones y detección de bordes.

2. **VA102: Clasificación de imágenes con redes convolucionales**
   - Entrenamiento de una CNN para clasificación de objetos.
   - Introducción a arquitecturas preentrenadas (ResNet, VGG).

3. **VA103: Segmentación semántica básica**
   - Uso de U-Net para segmentación binaria.
   - Métricas de intersección sobre unión y visualización de máscaras.

4. **VA104: Detección de objetos con YOLOv5 (uso práctico)**
   - Entrenamiento con PyTorch Lightning y YOLOv5.
   - Anotación, inferencia y evaluación.

5. **VA105: Localización de objetos por regresión de bounding boxes**  
   _(Este taller)_

---

## 🎯 VA105 — Localización de Objetos por Regresión Directa

En este taller se implementa desde cero un modelo de detección de objetos basado en **regresión directa de bounding boxes**, sin propuestas de región. Inspirado parcialmente en el enfoque de **Faster R-CNN**, pero simplificado.

### 🧱 Componentes principales:

- Uso de un modelo **preentrenado ResNet18** como extractor de características.
- Cabeza de regresión personalizada para predecir `[x_min, y_min, x_max, y_max]`.
- Entrenamiento con pérdida `SmoothL1Loss` y coordenadas **normalizadas**.
- Evaluación con la métrica **IoU** y visualización sobre imágenes originales.

### 📦 Dataset utilizado

- Dataset propio de 800 imágenes de aviones.
- Anotaciones en `.csv` con coordenadas de bounding boxes.

### 📊 Resultados

- Visualización clara de predicciones vs ground truth.
- Implementación de una métrica propia de IoU para evaluar desempeño.

---

## 🚀 Requisitos

- Python 3.8+
- PyTorch >= 1.10
- OpenCV, matplotlib, pandas, scikit-learn

---

## 📂 Estructura del repositorio


