# Electro-3

Cambiar solo los valores de entrada, si las condiciones de frontera son diferentes a la que se establecen para este problema, de debe cambiar los parámetros que se encuentran en el diccionario V_borde en la sección principal del código, justo antes de llamar a la función resolver_laplace_y_graficar. Este diccionario define los valores de potencial que se aplican a los bordes de la matriz.

Para el test solo basta con cambiar las condiciones dentro de la función inicializar_matriz_con_condiciones.
