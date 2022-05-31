# Clustering_Groups_Exercise
Ejercicio completo de clustering para determinar grupos homogéneos de estudiantes de acuerdo con sus habilidades técnicas.

# Objetivo General
Este ejercicio contempla una propuesta para determinar grupos de estudiantes con habilidades muy similares entre grupo, lo anterior dado que estos grupos desarrollarán proyectos basados en datos, por ende, se requiere que los grupos estén conformados por personas con una similitud en distintas habilidades.

# Datos
Los datos fueron recolectados a través de un formulario de Google donde se plantaron 9 preguntas que buscaban conocer la perspectiva propia de los estudiantes según ciertas habilidades de interés.
Dichas habilidades estaban enfocadas en matemáticas, estadística, programación, oratoria, desarrollo de proyectos, análisis. 
Si bien esta información es subjetiva y puede llegar a contemplar información errónea sobre las verdaderas habilidades, para el caso de uso se requería recolectar esta información de manera rápida, por lo que este planteamiento permite resolver esta necesidad.
Hay un total de 22 registros y 7 variables validas para analizar, cada habilidad dentro del formulario tuvo una escala de 1 a 10, siendo uno un conocimiento muy bajo y un valor de 10 cuando el estudiante considere que tiene un nivel muy alto en cierta habilidad.

# Metodología
Con los datos recopilados, se planteó inicialmente aplicar varios modelos de clustering para determinar la similitud de los asistentes. Para este caso se usaron varios métodos adicionales que sugieren la cantidad de clústeres ideales según la composición interna y externa de los mismos, métodos como el del codo o silueta que se basan en métricas de cohesión y separación sobre la matriz de distancias de las observaciones.
Una vez determinados esos clústeres se valido la composición de los mismos por variable para definir el perfil de los estudiantes que lo componen.
Si bien la composición de los clústeres garantiza similitud entre los estudiantes que lo componen, la necesidad final era poder balancear grupos para desarrollar proyectos basados en datos, por lo que se requiere asignar cada individuo a nuevos grupos de tal manera que se garantice que las habilidades que tengan serán tan variadas que no representarán una ventaja frente a otro grupo con habilidades menores.

# Resultados Generales


# Conclusiones


