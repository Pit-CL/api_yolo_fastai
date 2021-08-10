## Desarrollo de Productos de Datos
## Tarea 1: Modelo de ML Cliente-Servidor

# Descripción General
	
## Preguntas Prácticas (Código)

2.1 (1 punto) Agregue al programa servidor la opción de consultar al endpoint /predict agregando como parámetro el nivel de confianza (si necesita orientación, lea el punto 5: Recursos)

2.2 (1 punto) Realice los cambios necesarios en el programa cliente para comprobar que la consulta con nivel de confianza funciona correctamente. Pruebe con la imagen fruits.jpg para distintos niveles de confianza y comente los resultados. ¿Se le ocurre alguna otra imagen que sea interesante evaluar en este escenario? (puede buscar cualquier imagen en Internet, no necesariamente las adjuntas en los archivos)

2.3 (1 punto) En el programa servidor implemente un nuevo endpoint /countObjects para realizar un contador de un objeto en particular, por ejemplo un contador de naranjas (o de cualquier objeto que usted desee) apuntando al endpoint /countOranges. La idea es que esta funcionalidad reciba un modelo, nivel de confianza y modelo pero entregue como salida la cantidad de naranjas que existen en la imagen. 

2.4 (1 punto) Agregue al cliente las funcionalidades necesarias para probar el funcionamiento del endpoint /countObjects. Pruebe con imágenes que presenten: 1, 2, 3, 4, 5 o más ocurrencias del objeto en cuestión.

## Preguntas Teóricas (No Código)

3.1 (1 punto) En base a la disponibilidad de un servidor con el endpoint /countObjects, es decir, un modelo de Machine Learning que realice conteo de objetos en imágenes, plantee una aplicación cliente que pueda crearse para construir un Producto de Datos. Detalle qué tipo de problema resolvería, si se puede aplicar a alguna industria en particular, que usuarios tendría y cómo podría entregar valor a dichos usuarios. ¿Qué métricas de desempeño para el Producto de Datos serían adecuadas en este escenario?

3.2 (1 punto) En el escenario que su producto se implemente y comience a tener usuarios. En base a lo visto en clases: ¿Qué dificultades puede tener en el futuro? Enumere 5 de esas dificultades y comente cuál es la importancia de cada una.
