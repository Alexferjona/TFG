# TFG
Algoritmos heurísticos para problemas de recogida de pedidos en tienda

Trabajo Fin de Grado de la Escuela Superior de Ingeniería Informática de Albacete

Tutor: Francisco Parreño Torres

Co-tutora: María Teresa Alonso Martínez

Alumno: Alejandro Fernández Arjona

El código se divide en las siguientes clases:
  - **almacen2**: Se encarga de crear el almacén, los pedidos y mostrar la interfaz gráfica.
  - **dinamica**: Resuelve las rutas mediante programación dinámica.
  - **genetico**: Clase donde implementamos el algoritmo genetico para resolver el batching. Se pueden cambiar los parámetros libremente para comparar resultados.
  - **tabu**: Clase donde implementamos el algoritmo de búsqueda tabú para resolver el batching. De nuevo, se pueden alterar los parámetros que se desee.
  - **noBatching**: Clase usada para los experimentos en la que no hay ningún algoritmo de batching, tan solo se crea un individuo y se resuelven sus rutas mediante programación dinámica. Esto recuerda al funcionamiento de los almacenes de hoy en día, ya que asignan los pedidos a los pickers manualmente.
  - **main**: Clase principal del programa. Al ejecutarla, indica por pantalla qué inputs introducir por teclado para ejecutar un algoritmo u otro, con o sin interfaz, y qué instancia resolver de las 16 disponibles.
