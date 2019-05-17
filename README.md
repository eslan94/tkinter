# tkinter
Ejercicio 1: nos muestra una etiqueta en una ventana utilizando label
que declarar este widget en una ventana dándole una ubicación en la misma para esto utilizamos pack()

Ejercicio 2 :la ventana se llamara master la incialzamos como master=tk()
el mensaje aparece en una ventana en la que podemos seleccionar su color de fondo y definir el tipo de letra y el tamaño utilizando 
msg.config con pack ubicamos el widget en la ventana. 

Ejercicio3: creamos un cuadro dentro de las ventanas utilizando frame, 
hacemos que el cuadro sea boton con Button
posicionamos el boton y el texto dentro de la ventana con el comando self.button.pack(side=LEFT)
con self.button indicamons al boton dos opciones o salidas que puede tener dependiendo de lo que el usuario seleccione
con self.slogan configuramos para que el boton al ser presionado imprima un mensaje en consola 

Ejercicio4: creamos un cuadro de texto con label en el que imprimimos la instruccion
creamos unos botonos de seleccion unica con radiobutton podemos configurar el texto que acompañara el boton, el tamaño y a la variable que se le asignara

Ejercicio5: creamos una lista con tuplas para guardar los lenguajes 
la funcion ShowChoice hace que la variable imprima el valor asignado al lenguaje 
creamos una cuadro de texto con label 
creamos botones de seleccion unico con Radiobutton en la que la variable inicializada mostrada todos los lenguajes debibo a que esta en un bucle
y al seleccionar una llamamos a la funcion de ShowMessage el cual se imprime en consola 

Ejercicio6: creamos una lista con tuplas para guardar los lenguajes 
la funcion ShowChoice hace que la variable imprima el valor asignado al lenguaje 
creamos una cuadro de texto con label 
creamos botones de seleccion unico con Radiobutton pero en este caso les damos dimensiones de largo y ancho lo cual nos imprimira un cuadro en vez del circulo
en la que la variable inicializada mostrada todos los lenguajes debibo a que esta en un bucle
y al seleccionar una llamamos a la funcion de ShowMessage el cual imprime el valor en consola 

Ejercicio7: inicializamos dos variables, una por cada opcion que tengamos
creamos unos checkbox de seleccion multiple con Checkbutton en el que generamos la opcion dentro de la ventana, agregamos un texto que se adignara a la variable desginada
y el grid es para posicionar dentro de la ventana la ubicacin del mensaje. 

Ejercicio8: utilizando las herramientas del ejercicio anterior creamos una check box de seleccion multiple pero en este caso tambien se crea un boton con button  para salir y para imprimir la seleccion
si el cuadro esta marcado se imprime un 1 y si no un 0 acompañado del nombre del cuadro marcado

Ejercicio9: creados dos cuadros de lectura en los que imprimimos la instruccion con Label 
con Entry creamos una caja de texto en la que el usuario puede ingresar valores y como mencionamos antes el grid es para darle la ubicacion dentro de la ventana

Ejercicio 10: utilizando las herramientas del ejercico 9 creamos cuadros de texto de ingreso, cuadros de texto de lectura,
y tambien agregamos dos botones uno para salir que tiene asignado la funcion de salida del sistema y otro para que nos muestre el texto ingresado por el usuario
para esto asignamos dos variables para cada valor que ingrese el usuario que iran a la funcion que se encarga de imprimir los valores  en consola. 
