# JupyterNBDesercion

El propósito de este repositorio es tener un motebook básico que nos permite probar la usabilidad de las diferentes plataforamas de inteligencia artificial, y específicamente el uso de Jupyter Notebooks que es un estándar de la industria para Notebooks que permiten generar resultados a partir de inteligencia artificial.
El notebook base PrediccionDesercion.ipynb puede ser usado en AWS Sagemaker
El noteboook PrediccionDesercionIBM.ipynb puede ser usado con IBM Watson Studio

Los notebook soportan varios algoritmos:
* Adeline
* Perceptrón multicapa
* Perceptrón regresor
* Random Forest

La red se puede configurar con dos hiperparámetros:
* Epochs o ciclos de iteración de entrenamiento de la red neuronal
* Taza de aprendizaje, valor pequeño entre  0.0 y 1.0 que determina el tamaño del paso en cada iteración mientras se mueve hacia un mínimo de una función de pérdida. 

