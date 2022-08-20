# Parcial-Gestion-de-Datos-

Nombre: Nicolas Andres Rey Ospina 

Materia: Gestion de Datos 

Parcial

19 de Agosto de 2022







1. ¿Qué tipo de variables tiene el dataset? Detalle el tipo de variable de cada columna.

El dataset cuenta con las siguientes variables categóricas (cualitativas) y escalares(cuantitativas):
gender: Categórica Nominal 

-race/ethnicity: Categórica Nominal

-parental level of education: Categórica Nominal

-lunch: Categórica Nominal

-test preparation course: Categórica Nominal

-math score: Cuantitativa Continua

-reading score: Cuantitativa Continua

-writing score: Cuantitativa Continua


2.¿Qué tipo de problemas de calidad de datos logra identificar? Defina e implemente las estrategias de limpieza de datos que correspondan. 

En cuanto a problemas con la calidad de los Datos el único y principal problema es la presencia de Nulos en cada una de las columnas del df. Para estos casos no es recomendable realizar un proceso de imputación ya que las unicas variables que tenemos son variables independientes y utilizar media/mediana/moda podría llegar a afectar el analisis posterior. Se mira con mayor detenemiento a los valores nulos en las variables escalares, pero son independientes.


3. ¿En qué asignatura en promedio los estudiantes obtuvieron un mejor puntaje? ¿Hay evidencia de algún sesgo en la distribución de dichos puntajes?

A nivel general la materia de reading fue en donde los estudiantes tuvieron en promedio un mejor puntaje. Al mirar detalladamente el comportamiento de estos promedios con las demas variables se encuentra que los estudiantes que tomaron el curso de preparación, son mujeres y pertenecen al race/ethnicity Grupo E tienden a tener un promedio mas alto que los demas. 

De igual manera se hizo el detalle variable por variable donde se evidencia que los estudiantes Grupo E, las mujeres y con el curso tuvieron un promedio mas alto. 


4. ¿Existe alguna correlación entre los puntajes obtenidos en las tres asignaturas?

Parece existir una correlación alta en los puntajes obtenidos en las tres materias. La correlación mas baja es del 0.80 (Esto nos puede llevar a indicar que si el estudiante saca una buena nota en alguna de las materias muy probablemente cuente con una buena nota en los demas. 

	            math score 	  readingscore	  writing score
math score	   1.000000	    0.818880	      0.800733
reading score	 0.818880	    1.000000	      0.955338
writing score	 0.800733	    0.955338	      1.000000


5. ¿Hay alguna diferencia observable en los puntajes de la asignatura de matemáticas entre géneros? ¿Qué género obtuvo en promedio los mejores puntajes?

Para la materia de matemáticas los tres generos: male, female y non-binary tuvieron un promedio bastante similar, sin embargo, se observa que los hombres para este materia tuvieron un promedio mas alto que los demas

male          68.667582
non-binary    67.800000
female        63.457921


6. ¿Qué nivel de escolaridad tienen los padres de los estudiantes que obtuvieron un puntaje por encima del percentil 85 en la asignatura de escritura? ¿Cómo se distribuye la escolaridad entre esta población?.

Los estudiantes de padres cuentan con cada uno de las 6 valores, sin embargo, se observa que aprox. el 80% de los padres cuentan con alguno estudio superior (posteriores a la secundaria), bien sea un bachelors degree, assciate degree, masters, some college


7. ¿Qué porcentaje de los estudiantes obtuvieron puntajes iguales o superiores a 90 en las tres asignaturas? De estos estudiantes¿que porcentaje estudió para los exámenes?

Solamente el 2.3% del total de los estudiantes sacaron 90 o mas en las tres asignaturas. 

De estos estudiantes que sacaron 90 o mas en las tres asignaturas, el 56% se preparo para los examenes.
