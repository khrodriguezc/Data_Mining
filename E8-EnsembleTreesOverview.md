# E8 - Ensemble Trees Overview

Write at least 300 words explaining why ensemble is a succesful strategy in machine learning.

Los ‘Esemble methods’ son una herramienta efectiva para la elaboración de Modelos de Machine Learning debido a que mediante la aplicación de metodologías complementarias como “Bagging” o “Boosting” se logran generalmente mejores resultados en términos de Precisión y disminución del error de predicción de los modelos.

Estas herramientas complementarias (“Bagging”y “Boosting”) también traen consigo mejoras en otras características importantes para un modelo de Machine Learning, ya sea de regresión o de clasificación, como son la disminución de factores como la volatilidad, el “bias” y la presencia de “overfitting” por lo que son actualmente una herramienta imprescindible en la elaboración de Modelos de Machine Learning; tanto así que han estado presente en muchos de los modelos que ganan las competencias de predicción de modelos de Machine Learning.
La modelación vía Bagging permite hacer el modelo mucho más robusto dado a que con el uso de técnicas de Bootstrap (creación de muestras con remplazamiento) en la fase de entrenamiento de veces permite disminuir la varianza sobre el modelo y a su vez mejorar todos los indicadores que miden la precisión de una estimación.

La implementación de Boosting en la modelación, principalmente el algoritmo AdaBoost (uno de sus desarrollos más usados por los usuarios de Machine Learning) permite reducir una gran proporción de los errores por clasificación debido a que cada vez que tiene problemas con las particiones sobre algunas de las observaciones impone un “weight” adicional sobre esta muestra, posteriormente va reuniendo muestras con dificultad de clasificación hasta que en cierto punto determina una clasificación mucho más aproximada a las realizadas por modelos que no implementan el uso del algoritmo AdaBoost.

