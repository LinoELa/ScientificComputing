# Scientific Computing

El plan de estudios de Computación Científica con Python me  dotará de las habilidades necesarias para analizar y manipular datos utilizando Python, un lenguaje de programación potente y versátil. Aprenderé conceptos clave como estructuras de datos, algoritmos, programación orientada a objetos y cómo realizar cálculos complejos utilizando diversas herramientas.

Este completo curso le guiará a través de los fundamentos de la computación científica, incluyendo estructuras de datos y algoritmos.
https://www.freecodecamp.org/espanol/learn/scientific-computing-with-python/


#### Markdown Preview Shortcuts

The cmd key for Windows is ctrl.

- Shortcuts	Functionality
- cmd-k v or ctrl-k v	Open preview to the Side
- cmd-shift-v or ctrl-shift-v	Open preview
- ctrl-shift-s	Sync preview / Sync source
- shift-enter	Run Code Chunk
- ctrl-shift-enter	Run all Code Chunks
- cmd-= or cmd-shift-=	Preview zoom in
- cmd-- or cmd-shift-_	Preview zoom out
- cmd-0	Preview reset zoom
- esc	Toggle sidebar TOC



## Cifrado Cesar & Vigenere

Python es un lenguaje de programación potente y popular ampliamente utilizado para la ciencia de datos, visualización de datos, desarrollo web, desarrollo de juegos, aprendizaje automático y mucho más.

En este proyecto, aprenderé conceptos fundamentales de programación en Python, como variables, funciones, bucles y sentencias condicionales. Los utilizarás para codificar tus primeros programas.


- PARTE 1 : Cifrado César

- [ ] para acceder a un string


- COMPLETADO EL CIFRADO CESAR Y EL CIFRADO VIGENERE 




## Luhm Algorithm

#### METODOS :
> maketrans (info : step 3)
    >> str.maketrans({'t': 'c', 'l': 'b'})

>  str 
    >> String 
    
> index operador [] : string[x:y:h]
    >> my_string = 'camperbot'
        camper = my_string[0:6]
        cp = my_string[0:6:3]

        -- Donde x es el índice inicial, y es el índice final, y h es el paso (la cantidad de caracteres a saltar).


## Expense Tracker : Control o Registro de Gastos 
En este proyecto, vamos a construir un simple, pero funcional rastreador de gastos en Python

 - Lista 
    - Una lista en Python es un tipo de datos incorporado que permite almacenar muchos elementos en una única estructura de datos.
    - In Python, you create a list by putting items inside square brackets [], with each item separated from the following one by a comma.
        >  numbers = [1, 2, 3, 4]
        
- Diccionario 
    - Un diccionario es otro tipo de datos incorporado en Python. Un diccionario es una colección de datos en forma de pares clave-valor. 
    - Los diccionarios se definen con llaves {} y contienen pares clave-valor separados por comas. Cada clave va seguida de dos puntos : y el valor:
        > {'amount': 50.0, 'category': 'Food'}
            - 'amount' & category : key - clave 
            - 50.0 & 'Food' : values - valor

    - Puede acceder a los valores de un diccionario a través de sus claves. Debe utilizar la notación de corchetes e incluir la clave entre los corchetes:
        > my_dict = {'amount': 50.0, 'category': 'Food'}
        my_dict['amount'] # 50.0
        - Acceder al valor de la clave "importe" y la clave "categoría" del diccionario de gastos.
        > print(f'Amount: {expense["amount"]}, Category: {expense["category"]}')
        



###### LOOPS : Bucle
- **WHILE**
    - Un bucle while es otro tipo de bucle que ejecuta una porción de código hasta que una condición especificada es True:
    >while condition:
    <-- codido -- >


- **FOR**



###### METODOS

En Python, **los objetos iterables** son aquellos que podemos recorrer usando un ciclo, entre ellos, las cadenas de texto o estructuras de datos como las listas, las tuplas o los diccionarios.

- **Analdir elementos** 
    > .append() 
    __
    my_list = [2, 4, 7]
    my_list.append(3)

- **Funtions** 
    - En Python, la función **map()** nos permite aplicar una función sobre los items de un objeto iterable (lista, tupla, etc...).
    - Las funciones lambda pueden combinarse valiosamente con la función map(), que ejecuta una función especificada para cada elemento de una colección de objetos, como una lista:


    > maps ()
    sintaxis : map(function, objeto iterable)
        > map(lambda x: x * 2, [1, 2, 3])
        - Resultado = [2, 4, 6]

        
    - La función **sum()** devuelve la suma de los elementos del iterable que se pasa como argumento. 
    > sum()


    - La función **filter()** permite seleccionar elementos de un iterable, como una lista, basándose en la salida de una función:
    - La funcion filter() devuelve un iterador en el que se incluyen los elementos de mi_lista, para los que mi_función devuelve True. Un iterador es un objeto especial que permite iterar sobre los elementos de una colección, como una lista.
    > filter(my_function, my_list)


    - La función **input()** recibe una entrada del usuario y la devuelve en forma de cadena.


    






###### Lambda Funtions

Desde el **step 11**  (paso 11)todo el resto sigue hablando de lambda auque las  funciones lo he puesto en el apartado de las funciones arriba

Las funciones lambda son funciones breves y anónimas de Python, ideales para tareas sencillas y puntuales. Se definen mediante la palabra clave lambda y utilizan la siguiente sintaxis:
-   x es un parámetro que se utilizará en la expresión expr. 

> lambda x: expr

- Para llamar a una función lambda puede utilizar la sintaxis de función habitual con un par de paréntesis después del nombre de la variable.

    - info Lambda pero en forma de funcion

        >def cuadrado(numero):
        return numero * numero
        --
        lista = [1,2,3,4,5]
        resultado = map(cuadrado, lista)
        --
        lista_resultado = list(resultado)
        print(lista_resultado)


    - info Lambda pero en forma de lambda

        > lista = [1,2,3,4,5]
        resultado = map(lambda numero: numero * numero , lista)
        lista_resultado = list(resultado)
        print(lista_resultado   




