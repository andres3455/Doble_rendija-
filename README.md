# Doble_rendija-


		Uso de librería:
Vamos a utilizar las librerias del repositorio, 

Primero mostramos un ejemplo del sistema si usáramos el sistema cuántico:

# Por comodidad en la escritura definimos los números complejos como c1, c2, c3:
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
