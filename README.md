<h1 align="center">
  Curso Python - Listas y bucles
  <br/>
</h1>

---

## Listas o tuplas
La lista se usa para recoger un número de valores o variables en una secuencia ordenada. Una lista puede contener objetos de python, 
números, strings, funciones y otras listas dentre de ella.
<br/>
### Listas
Una lista puede ser de la siguiente manera:
```
>>> milista = [t, dt, T, 'mynumbers.dat', 100]
```
Además las listas tienen diferentes acciones con las que crearlas, eliminarlas, modificarlas o para recoger informacion sobre ellas.
```
milista = [] 	                #Inicializar una lista vacias
milista = [1, 4.4, 'run.py'] 	#Inicializar una lista
milista.append(elem) 	        #Añadir elemento al final
milista + [1,3] 	            #Añadir dos listas
milista.insert(i, e) 	        #Añadir elemente después de la posición indicada
milista.count(v) 	            #Contar cuantos elementos hay en el valor v
len(milista) 	                #Numero de elementos de la lista
min(milista) 	                #El elemento más pequeño de la lista
max(milista) 	                #El elemento más grande de la lista
sum(milista) 	                #Sumar todos los elementos de la lista
sorted(milista) 	            #Ordenar todos los valores de la lista
milista[3] 	                  #Recoger el elemento número 3
milista[-1] 	                #Recoger el último elemento
milista a[3] 	                #Eliminar el elemento número 3
milista.remove(e) 	          #Eliminar el elemento con valor e
milista.index('run.py') 	    #Buscar el índice del elemento con el valor 'run.py'

```
### Tuplas
La tupla se puede representar como una lista constante, es decir, que no permite cambios de contenido en ella.
Se utiliza de la misma manera que las listas pero la declaración cambia. Podemos ver a continuación unos ejemplos:
```
>>> mytuple = (t, dt, T, 'mynumbers.dat', 100)
>>> mytuple =  t, dt, T, 'mynumbers.dat', 100
```

## Bucles

### Bucle for
Se utiliza para recorer los elementos de una lista o tupla
```
>>> for elem in [10, 20, 25, 27, 28.5]:
        print(elem)
```

### Bucle while
Se utilizan para repetir una coleccion de sentencias de programa varias veces.
```
>>> t = 0; dt = 0.5; T = 2
>>> while t <= T:
...      print t
...      t += dt
...
0
0.5
1.0
1.5
2.0
>>> print 'Final t:', t, '; t <= T is', t <= T
Final t: 2.5 ; t <= T is False
```

## Licencia

###### Realizado por Unai Puelles bajo licencia MIT. 2020.
