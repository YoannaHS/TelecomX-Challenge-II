# 📊 TelecomX Challenge II – Predicción de Evasión de Clientes

## 📌 Descripción del Proyecto  
Este repositorio contiene el desarrollo del **Challenge TelecomX – Parte II**, cuyo objetivo es **predecir la evasión (churn) de clientes** en una empresa de telecomunicaciones, aplicando técnicas de **análisis de datos** y **modelos de Machine Learning**.  

El proyecto cubre todo el flujo: desde la limpieza y exploración de datos hasta la evaluación de modelos predictivos.

---

## 🗂️ Contenido del Repositorio  
- `Telecom-Challenge-II.ipynb` → Notebook principal con el desarrollo.  
- `df_limpo.csv` → Dataset limpio y procesado.  
- Gráficos de análisis exploratorio y matrices de correlación.  

---

## 🔍 Flujo de Trabajo  
1. **Importación de librerías** → Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels, Imbalanced-learn.  
2. **Carga del dataset** y verificación de estructura.  
3. **Limpieza y transformación**:  
   - Eliminación de columnas irrelevantes (`customerID`).  
   - Agrupación de `"No internet service"` como `"No"`.  
4. **Codificación** de variables categóricas con *One-Hot Encoding* (sin dummy trap).  
5. **Tratamiento de valores nulos** → Eliminación de registros incompletos.  
6. **Normalización** de variables numéricas con *Min-Max Scaling*.  
7. **Análisis de correlación** y filtrado de variables relevantes.  
8. **Análisis de Multicolinealidad
9. **Modelos Predictivos
