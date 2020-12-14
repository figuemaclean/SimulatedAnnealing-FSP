# SimulatedAnnealing-FSP
 Simulated Annealing approach for the Fire Scheduling Problem
 Este proyecto contiene el código utlizado en Java y AMPL para reoslver el problema además de las instancias utilizadas tanto en Java como en AMPL
 Se incluye un archivo explicativo para leer los archivos txt que contienen las instancias de Java.
 Clases del código:
 - ArrayParameters: Contiene listas de listas de los parámetros de cada operación de disparo
 - ArrayTiempos: Contiene listas de listas de los tiempos de cada operación de disparo
 - FileReader: Permite leer la instancia desde una archivo txt
 - FSP: Contiene el número de armas, targets y todas las operaciones de disparo
 - Operation: Contiene las operaciones de disparo; arma que dispara, blanco enemigo que se dispara, duración, tiempo setup, probabilidad de detsrucción (de ese ataque), amenaza   
              del blanco enemigo y el decreasing_rate)
 - Orden: Aquí se realizan todas las operaciones de; generar soluciones iniciales, vecindarios, obtener qué armas son disparadas por más de un blanco y cuáles son, etc
 - Parameters: CLase que contiene amenaza, decreasing rate, setup, probabilidades de destrucción
 - SimulatedAnnelaing (Main): Esta clase contiene al algoritmo
 - Solution: Es una clase que contiene la solución, con su valor en la función objetivo, los Parametros 
 - Tiempos: Aquí están almacenados todos los tiempos de inicio, término de un trabajo, tiempo total, etc
