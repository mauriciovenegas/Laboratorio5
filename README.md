# Laboratorio5

En el laboratorio 5 se abarca el tema de cadenas de Markov. Más específicamente se trabaja los procesos aleatorios donde existen "estados" y "transiciones" entre estos estados. Donde las cadenas de Markov modelan las probabilidades de transición y el tiempo de permanencia entre cada estado. En particular, la teoría de colas describe la evolución del número de elementos en la fila, dado un flujo de entrada y un flujo de salida. Se evalúa con el código del labora
torio brindado un servidor web,  modelado como un sistema M/M/1, con una tasa de arribo de 2 solicitudes por minuto. Se busca tener al menos 1 solicituds en fila el 90% del tiempo. 

Se establece entonces una distribución de los tiempos de llegada y servicio para cada cliente, los intervalos y tiempos de llegada de cada cliente, un vector para establecer los eventos, y una serie de fórmulas para obtener los valores de tiempo.  En los resultados se obtiene dos gráficas, que muestran la cantidad de clientes en el tiempo de servicio. La primer gráfica muestra el resultado incorrecto para un valor de diseño nu, que permite ver cuando no se cumple la condición. Mientras que la segunda gráfica muestra un escenario donde se cumple la condición esperada para otro valor de nu. Se trabaja con el tiempo en segundos. 

