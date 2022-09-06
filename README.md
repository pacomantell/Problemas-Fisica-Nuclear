# Problemas Física Nuclear

Scripts que simulan pequeños modelos para diferentes cálculos de Física Nuclear.

## Modelo Gamow.
- Simulación de las ecuaciones de la Teoría de desintegración alfa nuclear, desarrollada por George Gamow en 1928, la cual se basa en la probabilidad de que una partícula alfa o un núcleo de carbono12 atraviese la barrera Culombiana de un núcleo por efecto túnel.
- Los diferentes scripts dentro del notebook obtienen, a partir de los valores de profundidad de la barrera Culombiana, tamaño del núcleo y masa reducida del sistema:
  - Altura de la barrera de potencial, calor de reacción y punto de corte con la barrera a atravesar.
  - Velocidad de la partícula (en unidades de c) y frecuencia estimada de colisión con la barrera de potencial.
  - Factor de Gamow, coeficiente de transmisión, probabilidad de transmisión por unidad de tiempo y vida mitad.

## Problema 2.
- Obtención de la curva de energía de ligadura por nucleón, para una serie isobária de núcleos (A=124), además de el Z máximo para dicha serie.

## Problema 3.
- Obtención gráfica de diferente calores de reacción en función de A, para dos tipos de emisiones: emisión alfa y emisión de un protón.

## Deuterón.
- Resolución de la Ecuación de Schrödinger del deuterón (núcleo formado por un protón y un neutrón).
- Obtención de secciones eficaces y comparación con modelo de alcance efectivo.

## Librerías empleadas:
- Numpy
- Matplotlib
- Scipy
- Pylab
- Sympy
- Pandas
