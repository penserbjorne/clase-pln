#Practica 1

*Objetivo:* Obtener la curva de Zipf de los tipos de un corpus en escala logaritmica y determinar el parametro α correspondiente a esa distribucion.

Pasos a seguir:

- Escoger un corpus de cualquier idioma y de un tamaño mayor a 10 000 tokens (se puede tomar este corpus de la paqueteria nltk.corpus).
- Limpiar el corpus: eliminar signos de puntuacion, de interrogacion, admiracion y elementos no lexicos.
- Aplicar un algoritmo de Stemming a los tokens limpios.
- Obtener las frecuencias de los tipos en el corpus.
- Ordenar por el rango estadistico de mayor a menor.
- Graficar el diagrama de dispersion rango-frecuencia en escala logaritmica.
- Obtener el parametro de la distribucion de Zipf, α (a partir de un procedimiento de regresion).
