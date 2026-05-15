# 🌤️ Proyecto Integrador ABP: Predicción Climática para Estación Meteorológica
**Instituto Superior Politécnico Córdoba (ISPC)** | Práctica Profesionalizante - 3er Año [4]

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## 🎯 Comprensión del Proyecto (Proyect Understanding)
Este proyecto nace ante la necesidad de diseñar e instalar una **Estación Meteorológica en la ciudad de Río Tercero, Córdoba**. Dado que no se cuenta con datos históricos propios, utilizamos un dataset representativo de ciudades clave de la zona centro de Argentina (Córdoba Capital, Rosario, Buenos Aires) para establecer una línea base [5-7]. 

**Problema a resolver:** ¿Cómo podemos estimar la Temperatura Máxima esperada en función de la Humedad Relativa y otras variables climáticas, para poder calibrar y validar los nuevos sensores de la estación?

## 📊 Comprensión y Preparación de los Datos (Data Understanding & Preparation)
Para el análisis se procesó un dataset climático con las siguientes rutinas de limpieza y exploración:
* 🧹 **Limpieza:** Tratamiento de nulos, eliminación de duplicados y casteos de tipos de datos (fechas y numéricos) [8-10].
* 🚫 **Outliers:** Detección y manejo mediante rangos intercuartílicos (IQR) [11, 12].
* 📈 **Análisis Exploratorio (EDA):** Visualizaciones univariadas y bivariadas. Destaca la creación de la *Matriz de Correlación S.I.M.A.*, donde se comprobó la relación inversa entre humedad y temperatura en algunas localidades [6, 7, 13].



