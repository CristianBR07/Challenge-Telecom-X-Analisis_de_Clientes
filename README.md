# 📊 Telecom X - Análisis de Churn (Evasión de Clientes)

Este proyecto aborda el análisis de datos de la empresa **Telecom X**, con el objetivo de identificar patrones y factores asociados a la **evasión de clientes (Churn)**.  
A través de técnicas de limpieza, exploración y visualización de datos, se prepara la base para aplicar modelos de **Machine Learning** que permitan predecir la probabilidad de cancelación de un cliente.

---

## 🚀 Objetivos del Proyecto
- Cargar y transformar los datos desde una **API en formato JSON**.
- Realizar un **proceso de limpieza**: manejo de valores nulos, duplicados e inconsistencias.
- Estandarizar y transformar variables categóricas y numéricas para su análisis.
- Crear nuevas variables derivadas, como **Cuentas Diarias**.
- Realizar un **análisis exploratorio de datos (EDA)** con métricas y visualizaciones:
  - Distribución del Churn.
  - Relación del Churn con variables categóricas (género, contrato, método de pago, etc.).
  - Análisis de variables numéricas (tenure, MonthlyCharges, TotalCharges).
- Preparar un **dataset listo para Machine Learning** y exportarlo en formato CSV.

  ## 🛠️ Tecnologías Utilizadas
- **Python 3**
- **Pandas** → manipulación de datos
- **NumPy** → cálculos numéricos
- **Seaborn & Matplotlib** → visualización de datos
- **Scikit-learn** → preparación para Machine Learning (modelos posteriores)

---

## 📊 Resultados Clave
- La evasión de clientes se concentra en contratos **Month-to-Month** y métodos de pago con **Electronic Check**.
- Los clientes con mayor **MonthlyCharges** tienen una probabilidad más alta de cancelar.
- Variables como **tenure** y **TotalCharges** muestran que los clientes que permanecen suelen tener una relación más larga con la compañía.

---

## 📈 Próximos Pasos
- Aplicar modelos de clasificación (Logistic Regression, Random Forest, XGBoost).
- Comparar métricas de desempeño (Accuracy, Precision, Recall, F1-Score, ROC-AUC).
- Proponer **estrategias de retención** basadas en los insights encontrados.
