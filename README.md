# 📊 Análisis de Evasión de Clientes – Telecom X

[![GitHub repo](https://img.shields.io/badge/GitHub-mafenavas/challenge__telecom__x-blue?logo=github)](https://github.com/mafenavas/challenge_telecom_x)

Este repositorio contiene un análisis exploratorio de datos orientado a identificar los principales factores que influyen en la evasión (*churn*) de clientes del servicio de Internet ofrecido por la compañía **Telecom X**.

## 🎯 Objetivo

El propósito del análisis es entender las causas detrás del abandono del servicio por parte de los clientes, mediante la exploración de variables relacionadas como el tipo de contrato, método de pago, tipo de servicio de Internet, género, y tiempo de permanencia. A partir de los hallazgos, se buscan oportunidades para **reducir la tasa de cancelaciones** y mejorar la **retención de usuarios**.

## 🛠️ Proceso de Análisis

1. **Exploración preliminar de los datos**:
   - Revisión de columnas y tipos de datos.
   - Identificación de valores nulos, registros duplicados y errores de formato.

2. **Normalización del dataset**:
   - Transformación de columnas con estructuras anidadas (diccionarios) en columnas individuales.
   - Generación de un DataFrame limpio y estructurado para análisis posterior.

3. **Análisis exploratorio (EDA)**:
   - Visualización de la distribución de evasión de clientes mediante gráficos (pie charts, barras, etc.).
   - Análisis cruzado entre la variable `Evasión de clientes` y variables categóricas como género, contrato, servicio de Internet y método de pago.

4. **Detección de patrones y comportamiento temporal**:
   - Evaluación de la evasión en función del tiempo (meses de permanencia).

## 🔍 Principales Hallazgos

- **Fuga temprana**: El primer mes concentra la mayor cantidad de cancelaciones (380 clientes), lo que sugiere fallas en la experiencia inicial del usuario.
- **Tipo de contrato**: Los contratos mes a mes presentan mayor probabilidad de cancelación frente a los contratos a uno o dos años.
- **Tipo de servicio de Internet**: Mayor evasión en usuarios con servicio de fibra óptica.
- **Método de pago**: El cheque electrónico se asocia con mayor tasa de cancelación comparado con métodos automáticos como transferencias o tarjetas.
- **Género**: No se detectaron diferencias significativas entre hombres y mujeres.

## 💡 Recomendaciones

- Optimizar el proceso de **onboarding** para reducir la evasión en el primer mes.
- Incentivar **contratos de largo plazo** mediante promociones o descuentos.
- Evaluar la calidad del servicio de **fibra óptica** y su percepción por parte del cliente.
- Fomentar el uso de **métodos de pago automáticos**, que están asociados con mayor retención.
- Usar estos hallazgos como base para construir un **modelo predictivo de churn**.

## 🧠 Tecnologías Utilizadas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 🚀 Próximos Pasos

- Construcción de un modelo de predicción de evasión (churn).
- Análisis multivariado con técnicas estadísticas o machine learning.
- Implementación de un dashboard interactivo (Power BI o Streamlit).

## 📬 Contacto

**María Fernanda Navas**  
GitHub: [@mafenavas](https://github.com/mafenavas)  


---

