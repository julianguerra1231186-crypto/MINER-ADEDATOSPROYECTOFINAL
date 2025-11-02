# 🧠 Proyecto Final - Minería de Datos  
**Autor:** Julián Guerra  
**Materia:** Minería de Datos  
**Universidad:** Quimbayo  
**Repositorio:** MINER-ADEDATOSPROYECTOFINAL  
**Creado en:** Google Colab  

---

## 📌 Descripción del Proyecto  
Este proyecto tiene como objetivo analizar el conjunto de datos **Wine Quality (Red Wine)** proveniente de UCI Machine Learning Repository.  
Se realiza un análisis exploratorio de datos (EDA) completo y se implementa un modelo de **regresión lineal** para predecir la calidad del vino tinto a partir de sus características fisicoquímicas.  

---

## ⚙️ Pasos Realizados  

1. **Importación y revisión de datos**  
2. **Limpieza de valores nulos y duplicados**  
3. **Normalización con MinMaxScaler**  
4. **Análisis de correlación y mapa de calor**  
5. **Test de normalidad (Shapiro-Wilk)**  
6. **Modelo de regresión lineal (LinearRegression)**  
7. **Evaluación del modelo con MSE y R²**  
8. **Visualización: valores reales vs. predichos**  

---

## ❓ Pregunta de Investigación  
> ¿Qué variables fisicoquímicas influyen con mayor fuerza en la calidad del vino tinto,  
> y en qué medida puede predecirse dicha calidad mediante un modelo de regresión lineal?  

---

## 📊 Resultados Principales  

| Variable | Influencia | Relación |
|-----------|-------------|----------|
| **Alcohol** | Alta | Positiva (+) |
| **Volatile Acidity** | Alta | Negativa (−) |
| **Sulphates** | Moderada | Positiva (+) |
| **Density** | Baja | Negativa (−) |

**R² ≈ 0.38 – 0.42** → El modelo explica cerca del 40 % de la variabilidad en la calidad.  
**MSE ≈ 0.4** → Error moderado aceptable.  

---

## 🧠 Conclusiones  
- La calidad del vino tinto depende principalmente del **contenido de alcohol** y de la **acidez volátil**.  
- El modelo de regresión lineal presenta una **precisión moderada**, adecuada para un primer enfoque predictivo.  
- Se recomienda probar modelos no lineales (como **Random Forest** o **Árboles de Decisión**) para mejorar la predicción.  

---

## 🔗 Acceso Directo  
Haz clic abajo para abrir el notebook en Google Colab:  
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julianguerra1231186-crypto/MINER-ADEDATOSPROYECTOFINAL/blob/main/Modelodeproyectomineriadedatos1.ipynb)
