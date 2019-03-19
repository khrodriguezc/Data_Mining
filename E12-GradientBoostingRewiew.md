# E12 - Gradient Boosting Review

Search for and comment about the main differences between the algorithms implemented in: 

(1) [ Gradient Boosting Classifier ](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)

(2) [ XGB Classifier ](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)

Write at least 300 words explaining the difference.

Entre los algoritmos de “Boosting” más famosos se encuentra el algoritmo de “Gradient Boosting” que ajusta los errores de las predicciones previas mediante la minimización de la función de costos vía gradiente decreciente. El proceso de construcción de la secuencia del algoritmo se hace con base a los errores de las predicciones de la fase anterior.
Uno de los inconvenientes de este procedimiento es su alto grado de exigencia computacional debido a que para bases de datos muy grandes exige una gran capacidad de procesamiento y almacenamiento, además para optimizar su funcionamiento requiere de la programación adicional de un algoritmo que detenga el proceso de iteraciones una vez que no se generen resultados que mejoren de forma significativa las predicciones previas generadas por el modelo.
Con el propósito de optimizar el proceso de creación de algoritmos de predicción bajo la metodología de “Boosting” el científico de datos Tianqui Chen de la Universidad de Washington creo el algoritmo “XGBoost” (Extreme Gradient Boosting) que potencializa los resultados obtenidos por la metodología “Gradient Boosting” optimizando la eficiencia computacional de tal manera que se ha convertido en uno de los algoritmos que con mayor frecuencia usan los ganadores de competencias como Kaggle.
Entre las ventajas del uso de este algoritmo se encuentran>
1.	Usa un innovador algoritmo de aprendizaje para árboles de decisión para mejorar los resultados al trabajar con data dispersa y escasa.
2.	Se caracteriza por ser un algoritmo que distribuye y paraleliza los procesos de estimación de los algoritmos más simples por lo que su velocidad de procesamiento es mucho mayor a la de la metodología de “Gradient Boosting” tradicional.
3.	Explota el potencial de computación “Out of Core” debido a que tiene como fin usar la mayor capacidad disponible de la máquina al particionar la data en Bloques y almacenarla en el disco para que después sea procesada.
Bibliografía:
XG Boost: A Scalable Tree Boosting System (Tianqui Chen, Carlos Guestrin)
A gentle introduction to XGBoost for aplied Machine Learning( Jason Brownlee)








