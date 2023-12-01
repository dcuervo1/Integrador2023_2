# Integrador2023_2
Este repositorio se crea con fines académicos, busca presentar los resultados de final de semestre 2023-2 para la Maestría en Ciencia de Datos de la Universidad Eafit
Equipo: Cindy Vanessa Aguirre Marín,Jhohann Andrés Giraldo Jiménez, Dairo Alberto Cuervo Garcia

Acontinuación se presenta el EDA, Preprocesamiento y modelos usados en el proyecto.

[EDA y preprocesamiento de datos](Project/1.%20EDA_Preprocessing.ipynb)
  
Modelos tradicionales para clásificación:

[a. Regresión logística](Project/2.%20LogisticRegression_RandomForest_Isoletion%20Forest.ipynb)

[b. Random Forest](Project/2.%20LogisticRegression_RandomForest_Isoletion%20Forest.ipynb)

[c. Isolation Forest](Project/2.%20LogisticRegression_RandomForest_Isoletion%20Forest.ipynb)

  
Procesos de AutoML con Databricks:

Ambos notebook son autogenerados en el ambiente de Databricks, para reproducir estos resultados, es necesario conectar
a clúster con la versión de tiempo de ejecución 13.3.x-gpu-ml-scala2.12. Se dejan los notebooks con su respectiva ejecución
de los 2 mejores modelos encontrados con AutoML para su revisión.
  
[AutoML con XGBoostClassifier](Project/3.1%20AutoML_XGBoostClassifier.ipynb)
[AutoML con lightGBM](Project/3.2%20AutoML_lightGBM.ipynb)
