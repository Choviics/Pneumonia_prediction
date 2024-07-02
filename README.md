# Modelo simple de machine learning
usando VGG16 para la predicción de pneumonía a partir de fotos de radiografías de pulmones en formato de 32x32x3, es decir, 32 píxeles por 32 píxeles en canal RGB. Este modelo se encargará de detectar los patrones asociados con la enfermedad.

![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/37cf31d0-05e5-422b-98cc-655ea248b036)



# Resultados del modelo con capas congeladas:

![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/90cdb19b-26f4-42cd-b4e6-3ff2fbe345bf)
![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/ce25f572-3fce-4efd-8eb0-a2310f162325)
![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/b868f194-58dc-4284-b83e-dbe5133f21a7)


# Resultados del modelo con fine tuning:

![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/1b6cc7d6-68af-4480-8f2c-b02af863cf49)
![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/66faefcb-6d6f-47e5-81b0-1a4533805324)
![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/289473e0-0136-405b-be38-aa2524e0103a)
![image](https://github.com/Choviics/Pneumonia_prediction/assets/152323865/950f966f-9a84-4845-a3e0-2fea562eaee7)

# Resultados
**Primer modelo**:

El primer modelo nos da un rendimiento bastante bueno con las siguientes métricas:

Accuracy: 0.87

Precisión: 0.85

Recall: 0.95

Puntuación F1: 0.90

Estas métricas son bastante buenas, pero pueden mejorarse ajustando los hiperparámetros, agregando capas, cambiando funciones, entre otras modificaciones.

**Segundo modelo**:

El segundo modelo presentó sobreentrenamiento, lo que indica que el modelo es demasiado complejo para la cantidad de datos disponibles. Las métricas obtenidas son:

Accuracy: 0.88

Precisión: 0.88

Recall: 0.94

Puntuación F1: 0.90

Aunque estas métricas son buenas, es necesario revisar los hiperparámetros para evitar el sobreentrenamiento y obtener mejores resultados.
