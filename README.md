# Detección de Intrusiones en Red (NIDS) mediante Ensambles de Machine Learning

Repositorio oficial de anexos, código fuente y modelos entrenados de la tesis sobre detección de ciberataques utilizando el dataset **CIC-IDS2017** auditado.

## Estructura del Repositorio
- `Notebooks/`: Notebooks de Análisis Exploratorio (`EDATesis.ipynb`), Entrenamiento (`Modelo`) y Evaluación (`Evaluacion`).
- `Anexos/Tablas/`: Tablas estadísticas completas, correlaciones, asimetría y métricas detalladas por clase (`.csv`).
- `Anexos/Graficas/`: Matrices de confusión, análisis de puertos y gráficas de importancia de características (`.png`).
- `Modelos/`: Modelos serializados (`XGBoost`, `Random Forest`, `CatBoost`, `LabelEncoder`) y registro de tiempos.

> **Nota de reproducibilidad:** Los notebooks fueron desarrollados en Google Colab conectados a Google Drive. Para ejecutarlos en otro entorno, actualice la variable de ruta al inicio de cada archivo con la ubicación local donde aloje el dataset CIC-IDS2017.
