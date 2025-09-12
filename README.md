# Clasificación de noticias en español utilizando técnicas de aprendizaje profundo

Descripción

Este proyecto implementa un sistema de clasificación multiclase de noticias en español utilizando aprendizaje profundo.
Se propone una arquitectura híbrida que combina:

BETO (modelo BERT preentrenado en español).

BiLSTM para capturar dependencias secuenciales largas.

Pooling (mean + max) y Dropout para mejorar la generalización.

El objetivo es comparar el rendimiento del modelo con dos configuraciones de longitud máxima de tokens: 256 y 512.
