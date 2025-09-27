1.- git clone url repositorio.

2.- se utilizo select_related y prefetch_related  para optimizar las consultas, evitando los problems de n+1 en el query de la consulta de la bbdd en django.

3.- la utilizacion de las validaciones de fechas se realizan a traves de una funcion simple, con una solicitud a una libreria de python que hace la consulta al servidor local para saber el dia y la hora

4.- Las acciones masivas del admin, permiten simplificar procedimientos repetitivos, pero a la vez los hace sumamente delicados, ya que, en este caso podemos eliminar todos los seleccionados. simplificando a la vez el procedimiento, pero con mucho cuidado.
