# 🎵 Spotify Popularity Predictor: Deep Learning with Keras
### Modelización con Redes Neuronales Profundas (DNN) para el Éxito Musical

Este proyecto desarrolla un modelo de aprendizaje profundo para predecir el índice de popularidad de las canciones en Spotify basándose en sus características de audio (energy, danceability, tempo, etc.). Se implementa una arquitectura de red neuronal multicapa diseñada para capturar relaciones no lineales complejas en la industria del streaming.

---

## 🛡️ Visión de Gobierno de IA y Model Governance
El despliegue de redes neuronales en entornos corporativos exige un marco de **AI Governance** para asegurar la robustez y la transparencia de los sistemas:

1. **Gobernanza de la Arquitectura:** El diseño de la red (128 → 64 → 32 → 1) sigue un protocolo de control de complejidad, utilizando capas de **Dropout** y **BatchNormalization** para prevenir el sobreajuste (overfitting) y garantizar la estabilidad del activo de IA.
2. **Ética en la Recomendación:** Se integra una visión crítica sobre el sesgo algorítmico en la industria musical, promoviendo que las predicciones de popularidad no refuercen disparidades preexistentes, sino que sirvan como herramientas de análisis objetivo.
3. **Control de Entrenamiento:** Uso de callbacks inteligentes como `ReduceLROnPlateau` y `EarlyStopping`. Desde el gobierno del modelo, esto garantiza una optimización eficiente de recursos computacionales y evita la degradación del rendimiento.
4. **Validación de Robustez:** Evaluación sistemática en datos no vistos (Test Set) con métricas de MAE y RMSE, asegurando que el modelo sea un activo de información confiable para departamentos de marketing y A&R.

---

## 🎯 Capacidades Técnicas
- **Arquitectura de Deep Learning:** Implementación de una red densa secuencial con más de 13,000 parámetros entrenables.
- **Ingeniería de Features:** Preprocesamiento avanzado con escalado estándar (`StandardScaler`) y codificación de variables categóricas.
- **Optimización Avanzada:** Uso del optimizador **Adam** con tasas de aprendizaje dinámicas para una convergencia más rápida y precisa.
- **Visualización de Aprendizaje:** Análisis de curvas de pérdida (Loss) y métricas (MAE) para diagnosticar la salud del entrenamiento en tiempo real.

---

## 📊 Fuente de los Datos
- **Dataset:** `datos_spotify (2).csv`.
- **Atributos:** Features de audio (Acousticness, Valence, Loudness, etc.) y metadatos de la plataforma Spotify.

---

## 🛠️ Stack Tecnológico
- **Deep Learning Framework:** `Keras` / `TensorFlow`.
- **Machine Learning:** `Scikit-learn`.
- **Procesamiento de Datos:** `Pandas`, `Numpy`.
- **Visualización:** `Seaborn`, `Matplotlib`.

---

## 🚀 Cómo utilizar este proyecto
1. Clona el repositorio.
2. Asegúrate de tener el archivo de datos `datos_spotify (2).csv` en la carpeta raíz.
3. Instala las dependencias necesarias:
   ```bash
   pip install pandas numpy tensorflow scikit-learn matplotlib seaborn
