# Telecom_x_2
Challenge telecomparte2
# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn Prediction)

Este proyecto corresponde al desafío final de Data Science de Alura LATAM y Oracle One, donde se desarrolló una solución integral para **predecir la cancelación de clientes (churn)** en una empresa de telecomunicaciones ficticia: **Telecom X**.

El objetivo fue aplicar el flujo completo de ciencia de datos, desde la carga y limpieza de datos, pasando por análisis exploratorio y modelado predictivo, hasta la generación de conclusiones estratégicas basadas en la importancia de las variables.

---

## 🧠 Tecnologías Utilizadas

- **Python 3.10+**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE)**
- **Jupyter Notebook / Google Colab**

---

## 🗂️ Estructura del Proyecto

### `TelecomX_LATAM_2.ipynb`

Notebook principal que contiene todo el flujo del proyecto dividido en secciones:

#### ✅ Sección 1 – Carga y Preparación de los Datos
- Flatten de columnas anidadas.
- Eliminación de columnas irrelevantes.
- One-Hot Encoding.
- Balanceo de clases con SMOTE.
- Escalado y separación en conjunto de entrenamiento y prueba.
- Exportación del dataset final limpio.

#### 🔍 Sección 2 – Análisis de Correlación y Variables Clave
- Matriz de correlación con visualización avanzada.
- Identificación de variables más correlacionadas con la cancelación.
- Análisis específico de variables clave como tipo de contrato y gasto total.

#### 🤖 Sección 3 – Modelado Predictivo
- Entrenamiento de modelos: **Regresión Logística** y **Random Forest**.
- Evaluación con:
  - Accuracy, Precision, Recall, F1-score.
  - Matrices de confusión visuales.
  - Curvas ROC.
  - Tabla comparativa entre modelos.
- Análisis de overfitting y underfitting.

#### 📌 Sección 4 – Interpretación y Conclusiones
- Visualización y análisis de la **importancia de variables**.
- Tabla exportable de importancia (`importancia_variables.csv`).
- Recomendaciones estratégicas para reducir el churn.

---

## 📁 Archivos Exportados

| Archivo                       | Descripción                                                 |
|------------------------------|-------------------------------------------------------------|
| `dataset_final.csv`          | Dataset limpio y preprocesado listo para modelado.          |
| `resumen_churn.csv`          | Tabla descriptiva por clase (Churn / No Churn).             |
| `importancia_variables.csv`  | Tabla con importancia de variables según Random Forest.     |

---

## 📈 Resultados Destacados

- El modelo **Random Forest** presentó el mejor desempeño general con alta precisión y robustez ante overfitting.
- Las variables más influyentes fueron:
  - Tipo de contrato (Contract)
  - Pago mensual (Monthly)
  - Total gastado (Total)
  - Número de servicios activos

---

## 💡 Conclusiones Estratégicas

Los clientes con **contratos mensuales, alto pago mensual** y **bajo uso de servicios** son los más propensos a cancelar. Se recomienda:

- Ofrecer descuentos o promociones en contratos mensuales.
- Crear bundles de servicios para aumentar engagement.
- Monitorear proactivamente el comportamiento de estos perfiles.

---

## 👨‍💻 Autor

**Sebastián Santana Bustos**  
Especialización en Data Science – Oracle + Alura LATAM  
🔗 [LinkedIn](https://www.linkedin.com/in/sebastian-santana-283753267)

---

## 📌 Nota

Este repositorio es parte de una iniciativa educativa. Los datos son ficticios y utilizados con fines de aprendizaje.
