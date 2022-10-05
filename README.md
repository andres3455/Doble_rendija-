# Objetivo:
Estudiar y comprender el comportamiento de las particulas, en este caso, con un haz de electrones (laser)
# Explicación:
En nuestro experimento, usamos un láser para producir un haz de electrones sobre una placa de papel de aluminio con dos rendijas. Los electrones que componen esta luz tienen la misma probabilidad de pasar por una de las dos rendijas, pero no pueden pasar por ambas al mismo tiempo. Este estado inicial puede producir los siguientes resultados:

Los electrones pasarán por una de las dos rendijas y se reflejarán en la pared en forma de pepitas de oro. Como tenemos dos columnas, se crearán dos conjuntos de puntos, uno a la derecha y otro a la izquierda. Hay una ranura en frente de cada grupo. Pero si miramos hacia atrás a los resultados de los experimentos, vemos que esto no sucedió. Pero si esa es la explicación más lógica, ¿por qué? Una posibilidad es que los electrones que pasan por el hueco no salgan en línea recta, es decir, pueden cambiar de dirección y golpear cualquier parte de la pared. Pero esto solo sucede si algo o alguien afecta su trayectoria. Debido a la naturaleza del experimento, los electrones conservarán su orientación.
Aquí, la física cuántica explica este fenómeno. La teoría más ampliamente aceptada en la comunidad científica actual es que el "elemento" u "objeto" que afecta a ese electrón y hace que cambie de trayectoria es una historia diferente a la de la partícula, es decir, una historia diferente a la de la partícula. perteneciente a otro universo. ; esto afecta la trayectoria de nuestra partícula original y forma una mancha uniforme (mejor visto como una línea de manchas) en la pared.
Esta teoría abre la posibilidad de hablar de un multiverso, donde las partículas de nuestro universo tienen historias diferentes, pertenecen a otros universos y pueden interactuar entre sí.

# Doble_rendija-

Imagenes

![WhatsApp Image 2022-10-05 at 11 12 07 AM](https://user-images.githubusercontent.com/111390187/194109819-57346119-7347-4876-85fe-f374f78d81ca.jpeg)
![WhatsApp Image 2022-10-04 at 11 17 49 PM (1)](https://user-images.githubusercontent.com/111390187/194089925-db38e802-c7bb-4044-ae7c-bc04ea172f8f.jpeg)
![WhatsApp Image 2022-10-04 at 11 17 31 PM (1)](https://user-images.githubusercontent.com/111390187/194089972-d08d9307-06d2-4e8c-910a-1681963552bc.jpeg)
![WhatsApp Image 2022-10-04 at 11 17 49 PM](https://user-images.githubusercontent.com/111390187/194090006-b21c4aaf-955c-4eb2-9173-916f56cf2f39.jpeg)
![WhatsApp Image 2022-10-04 at 11 17 31 PM](https://user-images.githubusercontent.com/111390187/194090043-c68ce2a3-8bb8-4a0e-b497-651986c77520.jpeg)

		Uso de librería:
Vamos a utilizar las librerias del repositorio, 

Primero mostramos un ejemplo del sistema si usáramos el sistema cuántico:

# Para simplificar la escritura vamos a definir los complejos como c1, c2 y c3:
    c1 = (-1 / (6 ** 0.5), 1 / (6 ** 0.5))
		c2 = (-1 / (6 ** 0.5), -1 / (6 ** 0.5))
		c3 = (1 / (6 ** 0.5), -1 / (6 ** 0.5))
        
        # Primero llamamos la funcion que calcula las probabilidades en el sistema cuantico:
        
        
        print(rendijas_cuantico([[(0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0)], [(1/2, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0)], [(1/2, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0), (0, 0)], [(0, 0), c1, (0, 0), (1, 0), (0, 0), (0, 0), (0, 0), (0, 0)], [(0, 0), c2, (0, 0), (0, 0), (1, 0), (0, 0), (0, 0), (0, 0)], [(0, 0), c3, c1, (0, 0), (0, 0), (1, 0), (0, 0), (0, 0)], [(0, 0), (0, 0), c2, (0, 0), (0, 0), (0, 0), (1, 0), (0, 0)], [(0, 0), (0, 0), c3, (0, 0), (0, 0), (0, 0), (0, 0), (1, 0)]], [[(1, 0)], [(0, 0)], [(0, 0)], [(0, 0)], [(0, 0)], [(0, 0)], [(0, 0)], [(0, 0)]], 2))
    
    # Para que el sistema funcione de manera correcta, toca usar de 2 clicks en adelante.
    
    
  
A continuacion se demuestra de manera grafica los resultados (Vector inicial, matriz resultado)

![image](https://user-images.githubusercontent.com/112002572/193962457-b69faa19-0dd6-4589-980e-3d9e76ac205a.png)

A continuacion se procedera hacer el experimento con el sistema clasico.

# Llamamos la función que calcula las probabilidades de forma clásica:
        
        print(rendijas_clasico([[0, 0, 0, 0, 0, 0, 0, 0], [1/2, 0, 0, 0, 0, 0, 0, 0], [1/2, 0, 0, 0, 0, 0, 0, 0], [0, 1/3, 0, 1, 0, 0, 0, 0], [0, 1/3, 0, 0, 1, 0, 0, 0], [0, 1/3, 1/3, 0, 0, 1, 0, 0], [0, 0, 1/3, 0, 0, 0, 1, 0], [0, 0, 1/3, 0, 0, 0, 0, 1]], [[1], [0], [0], [0], [0], [0], [0], [0]], 2))


y podemos ver los resultados graficamente (Vector inicial, matriz resultado)

![image](https://user-images.githubusercontent.com/112002572/193963431-72b270e7-b906-422a-ab86-fdaac3841cd3.png)



# Materiales y Elaboracion : 
. Un laser
. un bisturi
. Carton Paja
. Caja de Zapatos
# Pasos:

1/ Con un pedazo de aluminio, hacemos cortes lo mas finamente posibles para conseguir dos rendijas que estan lo mas minimamente separadas
2/ Con el carton paja, hacemos una cuadricula para fijar el pedazo de papel aluminio 
3/ La caja de zapatos funcionara como recipiente para almacenar el experimento

# Autores:
. Sanchez Murcia Juan Daniel
. Rodriguez Chaparro Andres Felipe
. Robinson Maria Paula 

