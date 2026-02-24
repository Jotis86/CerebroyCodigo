# 🔬 Ruta de Estudio: Científico de Datos

![Científico Banner](https://img.shields.io/badge/Duración-12--16%20semanas-blue) ![Nivel](https://img.shields.io/badge/Nivel-Intermedio%20a%20Avanzado-red) ![Dedicación](https://img.shields.io/badge/Dedicación-15--20h%2Fsemana-orange)

## 🎯 Objetivo de la Ruta

Desarrollar modelos predictivos y soluciones avanzadas de machine learning para resolver problemas complejos de negocio, desde la experimentación hasta la puesta en producción de algoritmos inteligentes.

## 📋 ¿Qué lograrás al completar esta ruta?

- ✅ Dominar algoritmos de Machine Learning y Deep Learning
- ✅ Implementar pipelines completos de ML
- ✅ Desplegar modelos en producción
- ✅ Trabajar con APIs y web scraping avanzado
- ✅ Crear soluciones end-to-end con datos reales
- ✅ Construir un portafolio profesional de ML
- ✅ Entender MLOps y ciclo de vida de modelos

---

## 🗓️ Cronograma Detallado

### **Fase 1 (Semana 1-4): Base Sólida de Analista** 📊

**Objetivo**: Consolidar fundamentos de análisis de datos (versión condensada de la ruta de Analista).

**📚 Recursos del repositorio:**
- [Python (general)](../1_Fundamentos/Python.pdf)
- [Python en análisis de datos](../3_Analisis_Visualizacion/Python_Analisis_Datos.pdf)
- [Bases de datos](../2_Gestion_Datos/Bases_de_datos.pdf)
- [Limpieza de datos con Python](../2_Gestion_Datos/Limpieza_datos_Python.pdf)
- [Visualización de datos con Python](../3_Analisis_Visualizacion/Visualizacion_Python.pdf)

**🌐 Recursos complementarios:**
- [Google Colab](https://colab.research.google.com/) - Entorno con GPUs gratuitas
- [Kaggle Learn](https://www.kaggle.com/learn) - Cursos intro rápidos

**🎯 Proyecto intensivo:**
Análisis exploratorio completo de un dataset complejo con más de 100k registros, incluyendo feature engineering básico.

---

### **Fase 2 (Semana 5-8): Machine Learning Foundations** 🤖

**Objetivo**: Dominar algoritmos de ML supervisado y no supervisado.

**📚 Recursos del repositorio:**
- [Machine Learning](../4_ML_IA/Machine_Learning.pdf)
- [Proyectos de ML](../4_ML_IA/Proyectos_ML.pdf)
- [Herramientas de IA - Parte 1](../4_ML_IA/Herramientas_IA_1.pdf)
- [Herramientas de IA - Parte 2](../4_ML_IA/Herramientas_IA_2.pdf)

**🌐 Recursos complementarios:**
- [Kaggle Competitions](https://www.kaggle.com/competitions) - Competencias reales
- [ML Playground](https://ml-playground.com/) - Visualización de algoritmos
- [Papers with Code](https://paperswithcode.com) - Implementaciones de papers
- [Repositorio de 6 Proyectos de ML](https://github.com/Jotis86/Machine-Learning) - Proyectos completos educativos: clasificación, regresión, clustering, series temporales y NLP

**🎯 Proyectos de la fase:**
1. **Semana 5-6**: Modelo de clasificación para detección de fraude (Ver ejemplos en [repositorio de proyectos ML](https://github.com/Jotis86/Machine-Learning))
2. **Semana 7-8**: Sistema de recomendación con técnicas de clustering

---

### **Fase 3 (Semana 9-12): Deep Learning y Técnicas Avanzadas** 🧠

**Objetivo**: Implementar redes neuronales y técnicas de DL para problemas complejos.

**📚 Recursos del repositorio:**
- [Deep Learning](../4_ML_IA/Deep_Learning.pdf)
- [APIs](../2_Gestion_Datos/APIs.pdf)
- [Web Scraping](../2_Gestion_Datos/Web_Scraping.pdf)

**🌐 Recursos complementarios:**
- [TensorFlow Playground](https://playground.tensorflow.org/) - Experimentación visual
- [Fast.ai](https://course.fast.ai) - Curso práctico de DL
- [Hugging Face](https://huggingface.co/spaces) - Modelos pre-entrenados

**🎯 Proyectos de la fase:**
1. **Semana 9-10**: Red neuronal para clasificación de imágenes
2. **Semana 11-12**: Modelo de NLP para análisis de sentimientos de tweets

---

### **Fase 4 (Semana 13-16): Despliegue y MLOps** 🚀

**Objetivo**: Llevar modelos a producción y entender el ciclo completo de ML.

**📚 Recursos del repositorio:**
- [Streamlit](../6_Desarrollo/Streamlit.pdf)
- [Docker](../6_Desarrollo/Docker.pdf)
- [Roadmap to Data Scientist](../5_Roadmaps/Roadmap_Data_Scientist.pdf)
- [DevOps](../6_Desarrollo/DevOps.pdf)
- [Bash](../6_Desarrollo/Bash.pdf) 

**🌐 Recursos complementarios:**
- [MLflow](https://mlflow.org/) - Gestión del ciclo de vida ML
- [Render](https://render.com/) - Despliegue sencillo
- [GitHub Actions](https://github.com/features/actions) - CI/CD para ML

**🎯 Proyecto final integrador:**
API REST que sirva un modelo de ML dockerizada, con frontend en Streamlit y pipeline automatizado de reentrenamiento.

---

## 🛠️ Stack Tecnológico Completo

### Software Esencial:
- **Python 3.9+** con Anaconda/Miniconda
- **Jupyter Lab** o **VS Code** con extensiones de ML
- **Git** para versionado de código y modelos
- **Docker** para contenerización

### Librerías Core de ML:
```bash
# Análisis y manipulación
pip install pandas numpy scipy

# Machine Learning
pip install scikit-learn xgboost lightgbm

# Deep Learning
pip install tensorflow pytorch torchvision

# Visualización
pip install matplotlib seaborn plotly

# Despliegue y APIs
pip install streamlit fastapi uvicorn

# MLOps
pip install mlflow wandb

# Web scraping y APIs
pip install requests beautifulsoup4 scrapy