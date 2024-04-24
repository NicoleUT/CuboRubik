# CuboRubik
# Analisis
1. Crear el cubo
   Para crear el cubo se definio la notacion
      F: Front (Frente)
      B: Back (Atrás)
      U: Up (Arriba)
      D: Down (Abajo)
      R: Right (Derecha)
      L: Left (Izquierda)
   Despues definimos los colores del cubo que seran
      W: white
      Y: Yellow
      G: Green
      B: Black
      O: Orange
      R: Red
     Empezamos a codificar y en la clase cubo rubik creamos el algoritmo mostrar y un algoritmo girar cara donde al definir la cara decimos a que lado la girara y realiza dicha operacion.
Despues definimos que realizariamos este trabajo usando A* por la manera funcional y eficiente que tiene para este caso de problema.
Luego se debia definir una heuristica, en este caso se trato de implementar 4 heurisiticas.
1. EL numero de fichas mal colocadas, consiste en contar las fichas mal colocadas en dicha cara.
2. DIstancia Manhattan: suma las distancias horizontales mas las distancias verticales entre la posicion de cada ficha y la posicion correcta
3. Distancia de fichas mal colocadas: se calcula la suma de las distancias entre la posición actual y la posición correcta de cada ficha.'
4. Patrones y subpatrones: Buscar patrones especificos, en este caso se lo realizo con esquinas o aristas
No se logro la eficiencia de este algoritmo.

