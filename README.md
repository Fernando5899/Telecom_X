# 📊 Análisis de Evasión de Clientes (Churn) - Telecom X

## 📝 Descripción del Proyecto
Este proyecto es un análisis de datos enfocado en identificar los factores principales que impulsan la evasión de clientes (Churn) en una empresa de telecomunicaciones ficticia, Telecom X. A través de un proceso completo de ETL (Extracción, Transformación y Carga) y un Análisis Exploratorio de Datos (EDA), se identificaron patrones críticos de comportamiento y factores de riesgo para ayudar a la toma de decisiones estratégicas.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Entorno:** Jupyter Notebook

## 🚀 Proceso y Metodología
1. **Limpieza y Normalización (ETL):** Procesamiento de datos desde un formato anidado, limpieza de valores nulos, conversión de tipos de datos (como variables binarias 1/0) y traducción de columnas al español.
2. **Análisis Exploratorio Categórico:** Visualización de la evasión frente a variables como el tipo de contrato, servicio de internet y método de pago.
3. **Análisis Exploratorio Numérico:** Evaluación de la distribución de los cargos mensuales y el tiempo de permanencia usando Boxplots.
4. **Análisis de Correlación:** Implementación de un Heatmap (Matriz de correlación de Pearson) para descubrir la sensibilidad al precio y el impacto de tener múltiples servicios contratados.

## 💡 Resultados Clave (Insights)
* La tasa de evasión global de la base de datos es del **26.6%**.
* Los clientes con **contratos "Mes a mes"** y pago mediante **cheque electrónico** presentan el mayor riesgo de abandono.
* Existe una **correlación negativa fuerte** entre el tiempo de contrato y el churn: a mayor antigüedad, la probabilidad de fuga se desploma.
* Los clientes con múltiples servicios contratados simultáneamente están más fidelizados.

## 👨‍💻 Autor
**Fernando Jose Reynosa Vidal**
Estudiante de Ingeniería en Sistemas Computacionales en la Universidad Tres Culturas.
* GitHub: [Fernando5899](https://github.com/Fernando5899)