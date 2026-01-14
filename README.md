
# 📊 Análisis de Churn – TelecomX

Este proyecto analiza la evasión de clientes (Churn) de la empresa TelecomX utilizando técnicas de análisis exploratorio de datos.

## 📌 Objetivo
Identificar los factores que influyen en la cancelación del servicio por parte de los clientes y proponer acciones de retención.

## 🧹 Limpieza de Datos
- Normalización de JSON desde API.
- Conversión de variables categóricas y numéricas.
- Eliminación de valores nulos y corrección de formatos.

## 📈 Análisis Realizado
- Distribución de churn.
- Análisis por género, tipo de contrato y método de pago.
- Relación entre churn y cargos / tenure.
- Visualizaciones con Seaborn y Matplotlib.

## 🧠 Conclusiones
- Menor tenure implica mayor probabilidad de churn.
- Los contratos mensuales presentan mayor tasa de cancelación.
- Cargos totales bajos están asociados a churn temprano.

## 🚀 Recomendaciones
- Incentivar contratos anuales.
- Programas de fidelización en los primeros meses.
- Seguimiento temprano de clientes con bajo gasto.

## 🛠 Tecnologías
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
"""

with open("README.md", "w") as f:
    f.write(readme)

print("README.md creado correctamente")
