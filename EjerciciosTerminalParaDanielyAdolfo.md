Ejercicios Terminal

Julián F. Martínez
Noviembre 17 de 2021


1)	Debemos actualizar el sistema operativo Ubuntu

R1: 

sudo apt-get update 

sudo apt-get upgrade 

R2:

sudo software -i -a  


2)	Determinar con un comando cuál es nuestra posición en el árbol del usuario

R1: 

pwd

R2: 

pwd

3)	Visualizar con un comando el árbol del usuario desde /home/nuestroUsuario/

R1:

tree

R2:

tree


4)	Crear en /home/nuestroUsuario/ un folder llamado “ejercicios”

R1:

mkdir ejercicios

R2:

mkdir ejercicios

5)	Verificar que lo hemos creado en el lugar correcto y su posición en el árbol

R1:

ls -l 

pwd

R2:

ls 

pwd


6)	Movernos a la carpeta “ejercicios” y verificar con el comando que estemos ahí

R1:

Cd ejercicios

Pwd = /home/JulianFMartinez/Ejercicios

R2:

Cd ejercicios

Pwd = /Users/apple/ejercicios


7)	Creamos un archivo de texto dentro del folder “ejercicios”, escribimos texto y lo salvamos adecuadamente con el nombre parte_1

R1: 

nano + escribir “texto” + control O + guardar “parte_1” + control x

R2: 

nano + escribir “texto” + control O + guardar “parte_1” + control x


8)	Retrocedemos a /home/nombreUsuario/ utilizando el comando de retroceso o bien el comando de path absoluto. Verificamos con un comando nuestra posición

R1:

cd

pwd

R2:

cd

pwd


9)	Con el comando y los parámetros adecuados generamos un listado

R1:

ls -l

R2:

ls -l


10)	Con el comando anterior agregamos otro parámetro y visualizamos los archivos ocultos también

R1:

ls -a

R2:

ls -a


11)	Desde /home/nombreUsuario/ creamos otro archivo de texto llamado “parte_2”, escribimos un texto, lo salvamos

R1:

nano + escribir texto + control O + guardar “parte_2”

R2:

nano + escribir texto + control O + guardar “parte_2”


12)	Desde la raíz del usuario creamos un folder llamado “trabajos”

R1:

mkdir trabajos

R2:

mkdir trabajos


13)	Desde la raíz del usuario creamos un archivo de texto plano llamado “parte_3”, lo salvamos, salimos y verificamos que este en lugar adecuado. 

R1:

nano + escribir texto + control O + guardar “parte_3”

R2:

nano + escribir texto + control O + guardar “parte_3”


14)	Desde la raíz del usuario abrimos los tres archivos creados, agregamos en cada uno de ellos nuestro nombre al final del texto, lo salvamos y salimos del editor. 

R1: 

No se pueden modificar los tres a la vez porque el primero archivo está dentro de la carpeta “ejercicios”. Los otros dos que están en la raíz del usuario sí se pueden modificar con el editor de texto.

nano parte_2 parte_3

R2: 

nano parte_1 parte_2 parte_3


15)	Nos dirigimos al folder donde está ubicado el archivo “parte_3”. Verificamos la ubicación con el comando adecuado.

R1:

pwd

tree

R2:

cd ejercicios

pwd


16)	 Con el comando adecuado copiamos el archivo “parte_3” en el folder donde están los otros dos archivos y verificamos con el comando “tree”

R1:

cp parte_3 ejercicios
cp parte_2 ejercicios

R1:

cp parte_1 ejercicios


17)	Desde la actual posición en el árbol nos movemos al folder donde están los tres archivos recién creados (ejercicios). Verificamos nuestra posición

R1:

cd ejercicios
pwd

R2:

pwd

18)	Con el comando adecuado listamos los archivos del folder donde estamos ubicados

R1:

ls 

R2:

ls 

19)	Utilizamos el comando adecuado para leer los tres archivos simultáneamente, los visualizaremos sus textos en líneas separadas (en el terminal)

R1:

cat parte_1 parte_2 parte_3

R2:

cat parte_1 parte_2 parte_3


20)	Concatenamos los tres archivos y al nuevo archivo o llamados “textoTotal”

R1:

cat parte_1 parte_2 parte_3 > textoTotal

R2:

cat parte_1 parte_2 parte_3 > textoTotal


21)	Listamos los archivos del folder y verificamos si esta “textoTotal”

R1:

ls

R2:

ls


22)	Con el editor abrimos “textoTotal” y escribimos “trabajo finalizado”. Lo salvamos y salimos

R1:

nano textoTotal + guardar 

R2:

nano textoTotal + guardar 


23)	Ahora borramos o removemos el folder “trabajos”

R1:

rmdir trabajos

R2:

rmdir trabajos


24)	Nos movemos desde nuestra posición actual a /home/nuestroUsuario/ 

R1:

cd

R2:

cd

25)	Desde la raíz del usuario creamos un folder llamado “final”

R1:

mkdir final

R2:

mkdir final


26)	Copiamos el archivo “textoTotal”, de donde está archivo, a folder “final”, utilizamos el path absoluto

R1:

cd ejercicios

sudo cp textoTotal ../

sudo mv TextoTotal ../final/

R2:

mv textoTotal final

ls + cd final + ls 

27)	Finalmente borramos el folder “ejercicios”

R1:

rm -r ejercicios

R2:

rm -r ejercicios


28)	Utilizamos el comando: man cat y leemos las definiciones del comando y los diferentes parámetros. Salimos de este editor de man con la “q”

R1:

man cat

R2:

man cat


29)	Practicamos diferente comandos cat, whoami y ping

