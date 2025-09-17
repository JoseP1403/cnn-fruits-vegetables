# Examen Final: Text Mining & Image Recognition  

Este repositorio contiene el trabajo final desarrollado en el curso de Text Mining & Image Recognition. El proyecto se divide en dos partes: la primera corresponde a la generación de una nube de palabras a partir de un conjunto de datos de texto, y la segunda al diseño y entrenamiento de redes neuronales convolucionales (CNN) para la clasificación de frutas y verduras.  

## Parte 1: Word Cloud  

En la primera parte se utilizó el archivo tw_source.csv como base para el análisis de texto. A partir de este corpus se procesaron las palabras más frecuentes y se generó una nube de palabras (word cloud). Esta visualización permite identificar rápidamente los términos con mayor presencia en los datos. La nube fue exportada como imagen (`wordcloud.png`) para facilitar su revisión y documentación.  

## Parte 2: Clasificación de Frutas y Verduras con CNN  

La segunda parte del proyecto consistió en el desarrollo de modelos de clasificación de imágenes. Se trabajó con un dataset de frutas y verduras previamente organizado, aplicando técnicas de preprocesamiento como el redimensionamiento de imágenes, normalización y aumento de datos para mejorar la robustez del modelo.  

Se diseñaron y entrenaron tres arquitecturas de redes neuronales convolucionales, cada una con diferente número de capas y parámetros. Los modelos fueron evaluados en conjuntos de entrenamiento, validación y prueba. Los resultados mostraron que el primer modelo (m1) alcanzó un desempeño superior en comparación con los otros, con una precisión aproximada del 74% en validación y un 72% en el conjunto de prueba.  

Este resultado permite concluir que, dentro de las arquitecturas probadas, el modelo m1 logró un mejor balance entre complejidad y capacidad de generalización.  

## Archivos incluidos  

- `Examen Final.ipynb`: notebook principal con el desarrollo completo del proyecto.  
- `best_fvd_model.keras`: archivo del modelo guardado.  
- `resumen_resultados.txt`: resumen con las métricas obtenidas en validación y prueba.  
- `wordcloud.png`: imagen generada de la nube de palabras.  

