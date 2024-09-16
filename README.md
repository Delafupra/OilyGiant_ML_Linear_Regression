# OilyGiant_ML_Linear_Regression

Proyecto: Selección Óptima de Pozos Petrolíferos para OilyGiant
Descripción
Este proyecto utiliza modelos de Machine Learning para predecir el volumen de reservas de petróleo en diferentes regiones y seleccionar los mejores lugares para la perforación de 200 nuevos pozos para la compañía de extracción petrolera OilyGiant.

El objetivo principal es identificar la región con el mayor potencial de ganancias y menor riesgo de pérdidas utilizando un enfoque basado en Regresión Lineal y Bootstrapping. Los datos incluyen características geológicas y el volumen de reservas de tres regiones distintas, permitiendo el análisis y la selección estratégica de las ubicaciones más rentables.

Objetivos
Predecir el volumen de reservas de petróleo utilizando un modelo de regresión lineal entrenado en datos geológicos.
Seleccionar los 200 pozos más productivos en cada región según las predicciones del modelo.
Calcular la ganancia potencial para cada región basada en los 200 pozos seleccionados.
Evaluar el riesgo de pérdidas mediante la técnica de Bootstrapping para simular escenarios y calcular la probabilidad de resultados negativos.
Recomendar la mejor región para el desarrollo de nuevos pozos en función del beneficio potencial y el riesgo asociado.
Resultados
El análisis determinó que la Región 2 tiene el mayor beneficio promedio, con un total estimado de 85.32 millones de dólares y un intervalo de confianza del 95% entre 82.70 y 87.71 millones de dólares, con un riesgo de pérdidas prácticamente nulo.
La Región 0 también presenta buenas oportunidades, con un beneficio promedio de 83.23 millones de dólares, mientras que la Región 1 es la menos rentable.
Tecnologías Utilizadas
Python (Pandas, NumPy, Scikit-learn)
Machine Learning (Regresión Lineal)
Estadística (Bootstrapping)
Jupyter Notebook para el análisis y desarrollo del proyecto.
Estructura del Proyecto
Análisis Exploratorio de los Datos: Se examinan las características geológicas de cada región y se preparan los datos para el modelado.
Modelado: Se entrena un modelo de regresión lineal para predecir el volumen de reservas de petróleo en función de las características geológicas.
Cálculo de Ganancias: Se seleccionan los 200 pozos más productivos y se calcula la ganancia potencial.
Evaluación de Riesgos: Se aplica la técnica de bootstrapping para simular escenarios y evaluar el riesgo de pérdidas en cada región.
Recomendación Final: Con base en los resultados, se recomienda la Región 2 para la expansión de pozos petrolíferos.

Conclusión
Este proyecto demuestra el uso eficaz de modelos predictivos y técnicas estadísticas avanzadas para la toma de decisiones estratégicas en la industria petrolera. La combinación de Machine Learning y Bootstrapping permite identificar oportunidades de inversión con alto potencial de retorno y bajo riesgo.
