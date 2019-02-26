# E5 - Decision Trees Overview

Dentro de los algoritmos de árboles de decisión existen dos grandes tipos que dependen del tipo de objetivo de su estimación, arboles de clasificación y árboles de decisión.

Los árboles de clasificación tal y como su nombre lo indican, son modelos que permiten predecir con cierto nivel de precisión la categoría a la que pertenecerá un individuo, elemento, etc…, dado ciertas características (variables exógenas), adicionalmente estima la probabilidad de que dado cierta combinación de características “exógenas” un elemento o individuo pertenezca a dicha categoría.

El otro tipo de árbol al que se hace referencia anteriormente son los árboles de decisión de tipo regresión que tienen el objetivo de predecir variables continuas que son explicadas por la variación de un conjunto de variables “explicativas” o “independientes”, estos arboles estiman bajo cierto nivel de certeza el valor de la variable respuesta dada la combinación de un conjunto de variables “independientes”.

Una de las más grandes diferencias, a parte del objetivo de cada modelo, es el tipo de algoritmo que define la agrupación de elementos y creación de nodos el “impurity coefficient”; los arboles de decisión de tipo clasificación usan los indicadores Gini o entropía que se enfoca en la creación de nodos a partir de la maximización de la ganancia de información en cada “Split”.

Por otro lado, los arboles de decisión de tipo regresión se caracterizan por usar como “impurity coefficient” el error de predicción que compara la predicción que tendría una rama del modelo al hacer un “Split”  dado ciertos variables que alimentan el modelo y los valores reales de la variable objetivo observadas.
