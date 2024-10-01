# Práctica 4. Automatización de movimientos repetitivos en robots, aplicando el bucle “For”
## Asesor 
Juan David López Regalado
## Integrantes 
Arriaga Ayala Juan Manuel
Ayala Bibriezca Antonio
# Objetivo
## Objetivo General
Aplicar los conocimientos previamente adquiridos e implementar el bucle “For”
## Objetivos específicos 
Programar un robot para realizar movimientos predefinidos de manera secuencial y automática, utilizando posiciones almacenadas en el código.
Aplicar ajustes dinámicos en la posición del robot, específicamente en el eje Z, para evitar colisiones y asegurar una correcta colocación de objetos en diferentes iteraciones.
Validar el correcto funcionamiento del código mediante simulación y pruebas físicas, asegurando que el robot ejecute las tareas de manera eficiente y sin errores.

# Introducción 
	 En esta práctica de laboratorio, se implementó el uso del bucle “For” para la realización de tareas repetitivas, permitiendo que el robot industrial ejecute una serie de movimientos y acciones de manera automática y en una secuencia establecida. El bucle “For” es una de las estructuras de control más importantes en la programación, ya que permite repetir un conjunto de instrucciones un número específico de veces, lo que resulta ideal para situaciones en las que es necesario que un robot realice una misma operación en diferentes posiciones o en distintas iteraciones.
#Desarrollo
	La práctica se llevó a cabo en el laboratorio, comenzando con la utilización del simulador para verificar el correcto funcionamiento del código. Este paso inicial permitió asegurar que las instrucciones programadas y el número de iteraciones del bucle se ejecutaran de manera adecuada. El desafío principal consistió en establecer un bucle “For” que repitiera una serie de acciones cuatro veces.
La rutina comenzó con la apertura de la garra del robot, establecida como la primera acción del ciclo. A continuación, se definieron las actividades a realizar y se integraron dentro del bucle para que se ejecutaran en cada iteración, tal como se muestra en la imagen. Durante la ejecución, el robot debía colocar un fusible en cada ciclo. Tras cada colocación, el robot "aprendía" que, en la siguiente iteración, debía ajustar su posición elevando la garra para colocar el siguiente fusible sin colisionar con el anterior.
Finalmente, una vez completadas todas las iteraciones y colocado el último fusible, el robot regresó a su posición neutral, marcando la conclusión del programa.
#Análisis de resultados
Analizando las rutinas se puede ver que se realizó de una forma correcta la programación del robot, mismo que ejecuto con exactitud todas sus iteraciones, en el video adjunto se muestra la evidencia.
# Conclusiones
	En el transcurso de la práctica, se logró comprender cómo es posible definir y almacenar posiciones específicas para que el robot las ejecute de forma automática mediante un código programado. Además, se exploró el uso de estructuras de control como los bucles, en este caso el bucle “For”, que permite ejecutar un conjunto de instrucciones repetidamente un número determinado de veces. Esta capacidad de repetir el código no solo optimiza la operación del robot, sino que también simplifica la ejecución de tareas repetitivas en un entorno controlado.
Asimismo, se destacó la importancia de realizar modificaciones dinámicas en tiempo real, como fue el ajuste en el eje Z durante cada iteración, lo que permitió al robot evitar colisiones al colocar fusibles en diferentes posiciones. Este enfoque no solo mejora la precisión del robot, sino que también aumenta la flexibilidad y seguridad en el proceso de automatización. En resumen, la práctica demostró la eficiencia que aporta el uso de bucles y modificaciones dinámicas en la programación robótica, optimizando tanto el tiempo de ejecución como la precisión en la realización de tareas complejas. -Arriaga Ayala Juan Manuel
