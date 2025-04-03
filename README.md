# Modelado Predictivo de Enfermedades Cardiometabólicas mediante Técnicas de Aprendizaje Automático 🤖🧠

##Autores:

- [@Aldair1306](https://github.com/Aldair1306)
- [@Ernesto2105](https://github.com/ernesto2105)
- [@OscVelazquez14](https://github.com/OscVelazquez14)
- [@IsaiPerez02033](https://github.com/IsaiPerez02033)



## Redacción:
- México es un país que históricamente ha sufrido de enfermedades cardiometabólicas, en especial de tres de ellas: la obesidad, la diabetes y la hipertensión.

	Ante esta situación, nos dimos a la tarea de analizar bases de datos relacionadas con 	 estas enfermedades para aplicar algoritmos de machine learning e inteligencia artificial con el objetivo de obtener información más detallada. Construimos modelos capaces de diferenciar entre personas que padecen o no estas enfermedades, e incluso modelos que clasifican a las personas en distintos niveles de obesidad.

	Además, realizamos regresiones para predecir valores de ciertas medidas, como el índice de masa corporal (IMC) o la presión arterial, en función de otras características y hábitos diarios. Por último, aplicamos técnicas de clusterización para identificar grupos con características en común, lo que nos permitió detectar posibles tendencias ocultas.

## 📁 Estructura del Proyecto

notebooks/

- obesidad.ipynb: Análisis completo sobre obesidad, incluye modelos de clasificación, regresión y clustering.

- diabetes.ipynb: Modelos de clasificación y análisis de grupos con técnicas de clusterización.

- hipertension.ipynb: Modelos de clasificación aplicados a datos clínicos de pacientes en México.


## 🧠 Técnicas Aplicadas
- Obesidad
		Clasificación con KNN, SVM y XGBoost.
		Regresión con SVR y redes neuronales para predecir peso.
		Clustering con K-Means para identificar patrones de alimentación y peso.

- Diabetes
		Análisis de factores de riesgo a partir de datos de los CDC.
		Clasificación con Random Forest, XGBoost y LightGBM.
		Clusterización tras reducción de dimensionalidad con PCA.

- Hipertensión
		Uso de datos de ENSANUT México.
		Preprocesamiento riguroso de datos clínicos.
		Clasificación con modelos robustos: Random Forest, XGBoost, LightGBM y Stacking.

## 📊 Herramientas y Bibliotecas
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

- XGBoost, LightGBM

- SHAP (explicabilidad en redes neuronales)

- Keras (para redes neuronales)

- PCA, K-Means

## 🎯 Resultados Destacados
- Modelos con precisión superior al 97% en la predicción de niveles de obesidad.

- Red neuronal con R² = 0.90 para predecir el peso a partir de hábitos y factores personales.

- Identificación de grupos vulnerables en diabetes mediante análisis de silueta y componentes principales.

- Clasificador de riesgo de hipertensión con recall de 0.99, minimizando falsos negativos.

## 👨‍⚕️ Relevancia del Proyecto
* La carga de enfermedades crónicas en México es alarmante. Este proyecto busca generar herramientas predictivas y explicables que puedan ser útiles tanto para investigadores como para instituciones médicas interesadas en enfoques preventivos.
