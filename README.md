# Credit_Scoring_Prediction

## Descripción del Proyecto

<p align="justify"> El proyecto se enfoca en la implementación de modelos de machine learning de clasificación, con el objetivo de predecir con precisión el cumplimiento de los créditos otorgados a nuevos clientes. Esto permitirá reducir posibles riesgos crediticios al identificar a los clientes que probablemente cumplirán con sus obligaciones crediticias, mejorando de está manera la eficacia y eficiencia de la entidad financiera en la futura toma de decisiones.  </p>

## Recursos Usados

  1.	Google Colaboratory.
  2.	Python.
  3.	Librerías de Python Pandas, NumPy, Matplolib, seaborn y sklearn.
  4.	Dataset del banco, que tiene por nombre german_credit en formato csv.
  5.	Dataset de nuevos clientes que tiene por nombre DatosNuevosClientes con formato csv.
  6.	Diccionario german_dataset_dictionary en formato txt.

## Pasos 

  1.	Configuración del entorno e importar las librerías a usar.
  2.	Preprocesamiento de Datos. Para ello creamos una función llamada procesar_datos().
  3.	Análisis exploratorio de los datos (EDA). Para ello creamos una función llamada feature_engineering().
  4.	Construcción de modelos de Machine Learning con sus métricas.
  5.	Evaluación y selección del mejor modelo, a través de los resultados de las métricas para cada modelo.
    	![image](https://github.com/Marioarellano21/Credit_Scoring_Prediction/assets/146877817/9b3841dc-ba74-4d2e-9f71-ae25fc74ad5e)

  6.	Probar el modelo en los nuevos clientes(DatosNuevosClientes.csv). El modelo seleccionado fue el random forest y se creo un función llamada prediccion_cliente_nuevo() la cuál permite predecir con el modelo de estudio el resultado de los clientes evaluados.
      ![image](https://github.com/Marioarellano21/Credit_Scoring_Prediction/assets/146877817/a1bbbc3e-aae2-49fe-9a33-978f2bd4aadf)


     
## Conclusión y recomendaciones.

<p align="justify"> Con la evaluación de los modelos de machine learning realizados, se determinó que el mejor modelo para el caso de estudio fue el de Random Forest, obteniendo puntajes más altos en 4 de 5 métricas evaluadas. Gracias a la implementación de este modelo, se espera obtener resultados precisos que permitan, dentro de la entidad financiera, mitigar posibles riesgos a futuro, lo cual permitirá un mejor desenvolvimiento de la institución y una mejora de los procesos de selección de candidatos a crédito. </p>
