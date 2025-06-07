# 🧠👀 VA_workshops: Talleres de Visión por Computador

Este repositorio contiene cinco talleres que ponen en práctica el aprendizaje de técnicas de **visión por computador** en python. Cada taller está diseñado para abordar un aspecto del temario necesario para comprender los aspectos básicos y avanzados de la visión por computador.

---

## ✍ Talleres incluidos

1. **Taller 1: Introducción a modelos de clasificación**
   - Corta descripcion de los datos usados y tecnicas
![Diagrama](Results\Taller_1_output.png)
2. **Taller 2: Clasificación de deficiencia de fósforo**
   - Uso de una CNN como extractor de características + cabeza de clasificación con LightGBM
   - Introducción a arquitecturas preentrenadas (VGG) y aprovechamiento de las capacidades de extracción de características de las mismas.
   - Puesta en práctica de arquitecturas híbridas.

3. **Taller 3: Sistema de recuperación texto-imagen**
   - Corta descripción
`![ViTs](Results\Taller_3_output.png)`
4. **Taller 4: Tarea de pretexto**
   - Corta descripción
![Taller_4_results](Results\Taller_4_output.png)
5. **Taller 5: Localización de objetos por regresión de bounding boxes**  
   - Estrategia de detección de aviones en dos fases: Extracción de características con un modelo preentrenado y cabeza de regresión.
   - Evaluación con IoU y visualización sobre imágenes originales.
![Taller_5_results](Results\Taller_5_output.png)

---

## 🚀 Requisitos
Los requisitos varían de taller en taller (especificados en `requirements.txt` en cada carpeta), pero de forma general se tiene:
- Python 3.8+
- PyTorch >= 1.10
- OpenCV, matplotlib, pandas, scikit-learn

---

## 📂 Estructura del repositorio
```bash 
VA_workshops/
├── README.md                    # Introducción general al repositorio y talleres
├── Results/                    # Algunas imagenes de ejemplificación de cada taller
│
├── Taller_1/                   # Taller 1: Introducción a modelos de clasificación
│   └── ...
│
├── Taller_2/                   # Taller 2: Clasificación de deficiencia de fósforo
│   └── ...
│
├── Taller_3/                  # Taller 3: Sistema de recuperación texto-imagen
│   └── ...
│
├── Taller_4/                  # Taller 4: Tarea de pretexto
│   └── ...
│
└── Taller_5/                  # Taller 5: Regresión directa de bounding boxes
    ├── data/
    │   ├── images/            # Imagenes del Dataset
    │   └── Airplanes.csv      # csv con etiquetas
    └── ...
```

