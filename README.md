# Fashion classifier


## Integrantes
- **Ricardo Coronado**
- **Diego Espejo** diego dot espejo at alumnos dot uach dot cl
- **Javier Mancilla**
- **Diego Sandoval**

## Descripcion

Tarea grupal numero cuatro de la asignatura *Inteligencia Artifical* INFO257 de la carrera Ingenieria Civil Informatica.


### Instrucciones específicas

En esta tarea ustedes deben diseñar, entrenar y evaluar un modelo de red convolucional  para resolver el problema anteriormente presentado

1. Implemente una red convolucional con arquitectura Lenet5
1. Diseñe e implemente una nueva arquitectura de red convolucional que proponga mejoras sobre Lenet5
1. Para cada arquitectura experimente con distintos optimizadores (SGD, RMSProp y Adam), tasa de aprendizaje y tamaño de batch de entrenamiento

### Indicaciones

- Separe las imágenes del conjunto de entrenamiento en dos subconjuntos para ajustar los parámetros (entrenamiento propiamente tal) y evitar sobreajuste (validación), respectivamente. 
- Utilice *early stopping*, decida experimentalmente la paciencia y el número de épocas de entrenamiento
- Implemente un esquema de aumentación aleatoria de datos para el conjunto de entrenamiento, considere al menos recortes aleatorios. Compare contra la opción de no realizar aumentación aleatoria
- Compare sus modelos y entrenamientos en base a las curvas de aprendizaje y acompañe sus figuras con observaciones 
- Evalue la capacidad de generalización de la mejor Lenet5 y red propia midiendo su rendimiento en el subconjunto de prueba. Utilice matrices de confusión y reportes de clasificación (precisión, recall y *f1-score*). ¿Cuáles clases son más difíciles de clasificar? ¿Cuáles clases tienden a confudirse entre sí?
- Reporte el proceso, justifique sus decisiones y discuta sus resultados

## Caracteristicas de maquina y entorno

### Maquina
Estos experimentos fueron desarrollados en el computador *Waldner* del laboratorio de procesamiento de señales del instituto de Acústica UACh. La principal caracteristica de dicha maquina es su tarjeta grafica GeForce RTX 2080.


### Entorno virtual conda
|Elemento|Versión|
|--------|-------|
|python|3.9.5|
|pip|21.1.3|
|cudatoolkit|10.2.89|
|pytorch|1.9.0|
|torchvision|0.10.0|
|ignite|1.1.0|
|tensorboard|2.5.0|
|scikit-learn|0.24.2|
|numpy|1.20.3|
|matplotlib|3.3.4|

## Referencias
