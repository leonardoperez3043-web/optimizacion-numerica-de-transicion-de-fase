# Análisis de Transiciones de Fase Fuertes de Primer Orden

Estudio numérico de transiciones de fase fuertes de primer orden en la teoría cuántica de campos mediante técnicas de optimización implementadas en Python.

## Resumen del Proyecto

En el presente proyecto se obtendrán las combinaciones de parámetros
libres m, g y ω del modelo de Yukawa, donde ω que es la constante acoplamiento de
auto-interacción de los campos escalares, m la masa del bosón escalar y g que es el
parámetro que cuantifica la intensidad de la interacción entre el campo escalar; donde
se busca reproducir la curvatura de la linea de transición de fase reportada por Lattice
QCD [1], mediante técnicas de optimización de parámetros, en este caso di!erential
evolution, en el lenguaje de Python y tener un conjunto amplio de combinaciones de
estos parámetros que satisfacen dichas condiciones.

## Métodos Utilizados

- Evolución Diferencial
- Búsqueda de raíces (root_scalar)
- Integración numérica (Gauss-Legendre)
- Cálculo paralelo con Numba

## Tecnologías

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib
- Numba

## Ejemplo de Resultado

Gráficos de potencial de transición de fase y análisis de temperatura crítica.

## Aplicaciones

Aunque desarrolladas para física teórica, las técnicas de optimización numérica y análisis de datos utilizadas en este proyecto son directamente aplicables a:

- Optimización de aprendizaje automático
- Computación científica
- Procesos de análisis de datos

## Para entender los archivos

-El notebook optimizacion numerica (optimización-numérica-de-transición-de-fase) da los resultados de los parametros para lamnda de 0 a 1 y lo gualda en un archivo xlsx (resutados completos para lamda 01 a 1), el notebook de grafico de resultados le el xlsx y crea un grafico intercativo.
-El Proyecto fue realizado por mi y mi compañero por lo que se uso google colab por ende, en el notebook de graficacion estan los comentarios para montar el drive de cada quien.
