# Telecom X – Parte 2: Predicción de Cancelación de Clientes (Churn)
#### Este proyecto se enfoca en el desarrollo de un pipeline de Machine Learning para predecir la cancelación de clientes (churn) en la empresa ficticia de telecomunicaciones "TelecomX". A través del análisis de datos y la creación de modelos predictivos, se busca entender los factores clave que impulsan la decisión de un cliente de abandonar la compañía.

# 🎯 Objetivo del Proyecto
El objetivo principal es construir modelos de clasificación capaces de identificar a los clientes con mayor probabilidad de cancelar sus servicios. Esto permite a la empresa pasar de una estrategia reactiva a una proactiva, diseñando campañas de retención dirigidas y personalizadas para reducir la tasa de churn y maximizar el valor de vida del cliente.

# 🛠️ Tecnologías y Herramientas Utilizadas
* Lenguaje: Python 3
* Manipulación de Datos: Pandas, NumPy
* Visualización de Datos: Matplotlib, Seaborn
* Modelado y Preprocesamiento: Scikit-learn, Imbalanced-learn
* Entorno de Desarrollo: Google Colab

# 📂 Estructura del Proyecto
Todo el flujo de trabajo, desde la carga de datos hasta el informe final, está contenido en el notebook TelecomX_LATAM_parte2.ipynb. El proyecto se organiza en las siguientes secciones dentro del notebook:

* Preparación de los datos: Carga, limpieza, corrección de tipos de datos, codificación de variables categóricas (one-hot encoding) y estandarización.
* Correlación y Selección de Variables: Análisis visual y cuantitativo para identificar las variables más relacionadas con la cancelación.
* Modelado Predictivo: Creación, entrenamiento y evaluación de dos modelos (Regresión Logística y Random Forest).
* Interpretación y Conclusiones: Análisis de la importancia de las variables según cada modelo.
* Informe Ejecutivo: Resumen de hallazgos y propuestas de estrategias de retención accionables.

# 🚀 Cómo Ejecutar el Proyecto
Para replicar este análisis, sigue estos pasos en Google Colab:

1. Clona el Repositorio: Abre un nuevo notebook en Google Colab y ejecuta la siguiente celda de código para clonar el repositorio que contiene los datos y el notebook del proyecto.

Bash

!git clone https://github.com/ccontreras30/ch_telecomX_parte2.git

%cd nombre-del-repo


2. Abre el Notebook: En el panel de archivos de la izquierda, navega a la carpeta ch_telecomX_parte2 y abre el archivo TelecomX_LATAM_parte2.ipynb.Si no abre el archivo directamente, descargalo en tu computadora y ejecutalo directamente, se abrirá el cuaderno en el entorno de Colab.

3. Ejecuta las Celdas: Para asegurar la consistencia y el correcto flujo de los datos, ejecuta todas las celdas del notebook en orden secuencial (de arriba hacia abajo). La forma más fácil es ir al menú "Entorno de ejecución" y seleccionar "Ejecutar todo".

# 📈 Principales Resultados
* Identificación de Factores Clave: Se determinó que las variables más influyentes en la predicción del churn son el tipo de contrato (siendo "mes a mes" el de mayor riesgo), la antigüedad del cliente (tenure) y los cargos mensuales (MonthlyCharges).

* Rendimiento de Modelos: Se entrenaron dos modelos con resultados distintos:
  * La Regresión Logística demostró ser un modelo estable y con excelente capacidad para identificar a los clientes que cancelan (alto Recall).
  * El Random Forest mostró una alta precisión pero con tendencia al sobreajuste (overfitting), lo que indica la necesidad de optimizar sus hiperparámetros en futuras iteraciones.

* Conclusión Estratégica: La cancelación de clientes es un fenómeno predecible. Los modelos desarrollados pueden ser utilizados para segmentar a los clientes en riesgo y aplicar estrategias de retención focalizadas, como ofrecer contratos a largo plazo o programas de lealtad.

# ✍️ Autor
Carlos Contreras Lillo

LinkedIn: https://www.linkedin.com/in/carlos-contreras-lillo
