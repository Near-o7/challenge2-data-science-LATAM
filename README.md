# Telecom X - Análisis de Evasión de Clientes (Churn)

## Descripción del Proyecto

Este proyecto se desarrolla en el contexto de la empresa ficticia **Telecom X**, la cual enfrenta una alta tasa de cancelaciones de clientes (Churn). Como asistente de análisis de datos, el desafío es recopilar, procesar y analizar los datos de los clientes para comprender los factores que llevan a esta evasión.

El objetivo final de este análisis exploratorio es extraer información valiosa que permita al equipo de Ciencia de Datos avanzar en la creación de modelos predictivos y, a su vez, desarrollar estrategias de negocio enfocadas en reducir la pérdida de clientes.

## 🎯 Objetivo del Análisis

El propósito principal de este notebook (`TelecomX_LATAM.ipynb`) es realizar un Análisis Exploratorio de Datos para identificar los patrones y las características demográficas, contractuales y de servicio que están más fuertemente asociados con la decisión de un cliente de abandonar la empresa.

## 📊 Fuente de Datos

Los datos para este análisis se extraen de una URL pública que contiene un archivo en formato JSON. La carga se realiza directamente en el notebook utilizando la biblioteca `pandas`.

## 🛠️ Tecnologías y Dependencias

Este proyecto se desarrolla en Python y utiliza las siguientes bibliotecas principales:

* **`pandas`**: Para la manipulación, limpieza y análisis de datos.
* **`numpy`**: Para operaciones numéricas, utilizada específicamente para el manejo de valores nulos.
* **`matplotlib`**: Para la creación de visualizaciones y gráficos estáticos.
* **`seaborn`**: Para la creación de gráficos estadísticos más atractivos y complejos.

## 💡 Principales Hallazgos

El análisis reveló un perfil claro del cliente con alto riesgo de evasión y los factores más influyentes:

* **Tasa de Evasión:** La empresa tiene una tasa de churn general del **26.5%**.
* **Factores Contractuales:** Los contratos **"Mes a mes"**, el servicio de **Fibra Óptica** y el pago con **Cheque electrónico** son los indicadores más fuertes de un posible abandono.
* **Antigüedad (Tenure):** Es un factor crítico. Los clientes nuevos, especialmente durante los primeros meses, tienen una probabilidad mucho mayor de cancelar el servicio.
* **Servicios de "Adherencia":** Los clientes que no contratan servicios adicionales como `OnlineSecurity`, `TechSupport` o `OnlineBackup` son más propensos a irse.
* **Costo Mensual:** Una factura mensual elevada (`Charges.Monthly`) se asocia con un mayor riesgo de churn.
