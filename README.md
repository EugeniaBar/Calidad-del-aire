# 🌱 Análisis Exploratorio de Datos para la Predicción de la Calidad del Aire Urbano (Proyecto Educativo)

## Introducción

Este informe presenta un Análisis Exploratorio de Datos (EDA) realizado sobre un dataset de calidad del aire recopilado en una ciudad italiana entre marzo de 2004 y febrero de 2005. El objetivo principal de este proyecto, con fines educativos y de aprendizaje, es comprender las características, las relaciones entre las variables y sentar las bases para futuros esfuerzos de modelado predictivo de la calidad del aire.

## Dataset

Los datos provienen del [UCI Machine Learning Repository - Air Quality Data Set](https://archive.ics.uci.edu/dataset/360/air+quality) y se encuentran en el archivo `AirQualityUCI.csv`. El dataset contiene aproximadamente 9,000 registros horarios e incluye concentraciones de diversos gases contaminantes (Monóxido de Carbono (CO), Óxidos de Nitrógeno (NOx), Dióxido de Nitrógeno (NO2), Benceno (C6H6), Hidrocarburos No Metánicos (NMHC)) y variables meteorológicas (Temperatura (T), Humedad Relativa (RH), Humedad Absoluta (AH)).

## Metodología (Análisis Exploratorio)

El análisis EDA realizado incluyó las siguientes etapas:

* **Carga e Inspección Inicial de los Datos:** Se cargó el dataset y se examinó su estructura, tipos de datos y presencia de valores faltantes.
* **Preprocesamiento:** Se realizó la conversión de las columnas de fecha y hora en un formato `datetime` unificado para facilitar el análisis temporal.
* **Visualización de Distribuciones:** Se utilizaron histogramas y boxplots para comprender la distribución de las variables y la presencia de valores atípicos (outliers).
* **Análisis de Correlaciones:** Se generaron mapas de calor para identificar las relaciones lineales entre las diferentes variables.
* **Análisis de Patrones Temporales:** Se exploraron patrones horarios, diarios y mensuales para identificar ciclos y tendencias en la concentración de contaminantes.
* **Modelado Predictivo Inicial (Random Forest):** Como una exploración preliminar de la capacidad predictiva, se implementó un modelo de Random Forest Regressor para predecir la concentración de Monóxido de Carbono (CO), demostrando la potencialidad de las variables para el modelado.

## Hallazgos Clave (Resumen)

El análisis EDA reveló información importante sobre el dataset:

* La calidad del aire presenta patrones temporales definidos, con variaciones diarias y estacionales notables en la concentración de CO.
* Las concentraciones de contaminantes muestran correlaciones significativas entre sí y con las lecturas de los sensores.
* Variables meteorológicas como la temperatura y la humedad presentan relaciones complejas con los niveles de contaminación.
* El modelo de Random Forest demostró ser capaz de predecir la concentración de CO con un rendimiento inicial prometedor.

## Conclusión

Este análisis exploratorio proporciona una comprensión fundamental de la estructura y las dinámicas presentes en el dataset de calidad del aire. Los hallazgos sientan las bases para futuras investigaciones, incluyendo un preprocesamiento más exhaustivo, la selección de características relevantes y el desarrollo de modelos predictivos más robustos para anticipar la calidad del aire en la ciudad estudiada. Este proyecto subraya el valor del análisis de datos en la comprensión de fenómenos ambientales complejos con fines educativos y de potencial aplicación práctica.

---

"Este proyecto fue desarrollado con un fin estrictamente educativo, buscando aprender y aplicar técnicas de análisis de datos a información climática real. Se utilizaron datos de concentraciones de metano y dióxido de carbono, así como registros de temperatura global, para explorar las relaciones entre estos factores y el fenómeno del calentamiento global. Dado el carácter educativo del proyecto, se reconoce que los análisis y conclusiones presentados podrían contener errores o interpretaciones limitadas. El objetivo principal fue practicar y mejorar mis habilidades en el manejo y análisis de datos, utilizando un tema de relevancia científica y social."


![image](https://github.com/user-attachments/assets/b4f27044-69ae-485d-8ff4-fdadba88a986)
