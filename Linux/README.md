# Curso de Linux Unhatched 

## ¿Por qué aprender Linux?

El campo de la Tecnología de la Información (TI) está lleno de oportunidades. Para las personas que desean seguir una carrera en TI, uno de los mayores desafíos puede ser decidir dónde y cómo comenzar. A menudo, las personas están motivadas para adquirir nuevos conocimientos y aprender nuevas técnicas que les permitan acceder a mejores oportunidades tanto en su vida personal como profesional. Aprender una nueva habilidad requiere tiempo y disciplina, pero con la motivación correcta, esto no tiene por qué ser doloroso. En esta sección vamos a discutir por qué el tiempo y el esfuerzo invertido en aprender Linux le puede ser beneficioso; y recuerde, todos los que trabajan en TI tuvieron que empezar en algún lugar.

Aprender Linux es una gran manera de empezar. ¿Por qué es importante aprender Linux en un mundo impulsado por la tecnología como el actual?

La línea de comandos de Linux es una interfaz basada en texto que acepta comandos que se escriben en ella. Estos comandos hacen que una acción se ejecute en el sistema operativo del equipo. Por supuesto, las ventanas y los iconos son fáciles de usar, sin embargo, la línea de comandos es a menudo el héroe cuando se trata de la administración del sistema y la solución de problemas, ya que proporciona una imagen clara de lo que el sistema está haciendo en cualquier momento dado.

Teniendo en cuenta todo esto, ¿por qué aprender Linux es un buen comienzo para alguien que está considerando una carrera en TI? Como se ha dicho anteriormente, el uso de Linux está muy extendido y continúa creciendo en todas las áreas de la tecnología. ¿Qué tienen en común empresas y organizaciones como NASA, McDonald's, New York Stock Exchange (NYSE), DreamWorks Animation y el Departamento de Defensa de los Estados Unidos? Sí, lo adivinó correctamente, todos usan Linux.

Estas empresas tienen algo más en común porque reconocen que invertir en tecnología es importante en un mundo que está ansioso para adoptar nuevas tecnologías para innovar y resolver problemas. La proliferación de tecnología en casi todos los aspectos de nuestra vida ha resuelto muchos problemas pero también ha creado nuevos retos. Por ejemplo, ahora que casi todo se puede hacer en línea, estamos creando datos digitales a un ritmo muy rápido, lo cual está creando una demanda para esos datos. Por lo tanto, el conocimiento y las capacidades técnicas para analizar, procesar, proteger y transmitir estos datos también está en alta demanda. Aprender Linux puede ayudarle a avanzar en el camino hacia la adquisición de estos conocimientos y capacidades. Los siguientes son ejemplos de algunas profesiones de TI que requieren conocimientos de Linux:

- **Ingeniería de redes**: los ingenieros de redes son responsables de administrar los equipos de red que se utilizan para transmitir datos. El conocimiento de Linux es fundamental para los ingenieros de red, ya que más de la mitad de los servidores del mundo están basados en Linux. La mayoría de los sistemas operativos de red se basan en una variación de Linux.

- **Ciberseguridad**: los profesionales de la ciberseguridad supervisan e investigan las amenazas a la seguridad de los datos de los sistemas. Linux se utiliza en ciberseguridad para llevar a cabo pruebas de penetración del sistema y evaluar la vulnerabilidad de un sistema.

- **Desarrollo/Programación**: los diseñadores y programadores crean aplicaciones informáticas. La línea de comandos de Linux permite a los diseñadores y programadores ejecutar secuencias de comandos; una función que permite al usuario unir comandos para ejecutar acciones complejas en un ordenador. Linux también se utiliza en este campo porque sólo Linux permite a los usuarios acceder a su código fuente (o código source), dándoles la oportunidad de experimentar con el código y aprender mientras lo hacen.

- **Análisis de datos**: los científicos y los analistas de datos clasifican y analizan conjuntos de datos para encontrar patrones con el fin de informar y predecir tendencias y comportamientos. Los analistas de datos utilizan Linux debido a la amplia gama de herramientas y comandos disponibles para el análisis de datos, como MySQL y más.

Los sistemas operativos Linux vienen en muchas formas. Hay una variedad de distribuciones disponibles para adaptarse a las necesidades y demandas de muchos sectores de TI. Por ejemplo, los profesionales de la ciberseguridad pueden usar Linux Kali, los programadores y diseñadores pueden usar Linux Ubuntu, los usuarios habituales pueden usar Linux Mint y los servidores empresariales pueden funcionar con Red Hat Enterprise Linux.

Los ordenadores Linux utilizan una GUI, pero también poseen una herramienta más eficiente para llevar a cabo las mismas acciones que una GUI, la interfaz de línea de comandos (CLI, command line interface).

```bash
ls ~/Documents
```

## Sintaxis de comandos básicos

Este módulo se ocupa exclusivamente de la CLI o interfaz de línea de comandos, en lugar de la GUI o interfaz gráfica de usuario con la que quizás esté más familiarizado. El terminal CLI es una poderosa herramienta y a menudo es el método principal utilizado para administrar dispositivos pequeños de bajo consumo, servidores de computación de gran capacidad en la nube, y mucho más. Una comprensión básica del terminal es esencial para diagnosticar y reparar la mayoría de los sistemas basados en Linux. Puesto que Linux se ha vuelto tan omnipresente, incluso aquellos que planean trabajar con sistemas que no utilizan el núcleo Linux pueden beneficiarse de tener una comprensión básica del terminal.

¿Qué es un comando? Un comando es un programa de software que, cuando se ejecuta en la CLI (interfaz de línea de comandos), realiza una acción en el ordenador. Cuando usted escribe un comando, el sistema operativo ejecuta un proceso para leer su entrada, manipular datos y producir resultados. Un comando ejecuta un proceso en el sistema operativo, que luego hace que el ordenador realice una tarea determinada.

Para ejecutar un comando, el primer paso es escribir el nombre del comando. Haga clic en el terminal de la derecha. Escriba ls (letras minúsculas **L** y **S**) y pulse **Enter**. Obtendrá un resultado parecido al del siguiente ejemplo:
```Bash
ls
```

Generalmente, el nombre del comando se basa en la tarea que hace o en lo que el programador que creó el comando cree que mejor describe la función del comando. Por ejemplo, el comando ls muestra una lista de información sobre archivos. Asociar el nombre del comando con algo mnemotécnico sobre lo que hace puede ayudarle a recordar los comandos más fácilmente.

**A tener en cuenta**

Generalmente, los comandos distinguen entre mayúsculas y minúsculas. Por ejemplo **LS** es incorrecto y generará un mensaje de error, pero **ls** es correcto y se ejecutará normalmente.

```bash
sysadmin@localhost:~$ LS                                                        
-bash: /usr/games/LS: Permission denied 
```

La mayoría de los comandos siguen un patrón de sintaxis simple:

`comando [opciones…] [argumentos…]`

En otras palabras, escriba un comando, seguido de las opciones y/o argumentos antes de presionar la tecla Enter. Generalmente, las opciones (options) alteran el comportamiento del comando y los argumentos (arguments) son elementos o valores sobre los que debe actuar el comando. Aunque hay algunos comandos en Linux que no son completamente consistentes con estas normas de sintaxis, la mayoría de los comandos usan esta sintaxis o alguna similar.

En el ejemplo anterior, el comando `ls` se ejecutó sin opciones ni argumentos. Cuando este es el caso, su comportamiento predeterminado es el de devolver una lista de los archivos contenidos en el directorio actual.

##  Argumentos

`comando [opciones…] [argumentos…]`

Un argumento (argument) se puede usar para especificar algo sobre lo que el comando debe actuar. Si al comando ls se le da el nombre de un directorio como argumento, obtendremos como resultado una lista del contenido de ese directorio. En el siguiente ejemplo, el directorio Documents se utilizará como argumento:

```bash
sysadmin@localhost:~$ ls Documents                                              
School           alpha-second.txt  food.txt     linux.txt     os.csv            
Work             alpha-third.txt   hello.sh     longfile.txt  people.csv        
adjectives.txt   alpha.txt         hidden.txt   newhome.txt   profile.txt       
alpha-first.txt  animals.txt       letters.txt  numbers.txt   red.txt 
```

El resultado es una lista de los archivos incluidos en el directorio Documents.

Debido a que Linux es de código abierto, contiene algunas funciones curiosas que han ido siendo agregadas por sus programadores y usuarios. Por ejemplo, el comando aptitude es una función de gestión de paquetes disponible en algunas versiones de Linux. Este comando acepta moo como argumento:

```bash
sysadmin@localhost:~$ aptitude moo                                              
There are no Easter Eggs in this program.
```

Este comando no solamente es lo que parece. ¡Siga leyendo para saber qué más hay detrás de este truco!

## Opciones

`comando [opciones…] [argumentos…]`

Las opciones (options) se pueden utilizar para modificar el comportamiento de un comando. En la página anterior, el comando `ls` se utilizó para enumerar el contenido de un directorio. En el ejemplo siguiente, la opción `-l` se agrega al comando `ls` para obtener un resultado de “pantalla larga”, y proporcionar más información sobre cada uno de los archivos enumerados:
```bash
sysadmin@localhost:~$ ls -l                                                     
total 4                                                                         
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Desktop                        
drwx------ 4 sysadmin sysadmin 4096 Dec 20  2017 Documents                      
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Downloads                      
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Music                          
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Pictures                       
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Public                         
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Templates                      
drwx------ 2 sysadmin sysadmin    6 Dec 20  2017 Videos  
```
A menudo, el carácter elegido para el comando es mnemotécnico de su propósito en inglés. Por ejemplo, la letra l para indicar largo (*long*) o r para *invertir (reverse en inglés)*. De forma predeterminada, el comando `ls` imprime los resultados en orden alfabético, al agregar la opción `-r se imprimirán los resultados en orden alfabético inverso.
```bash
sysadmin@localhost:~$ ls -r                                                     
Videos  Templates  Public  Pictures  Music  Downloads  Documents  Desktop 
```

Se pueden usar varias opciones a la vez, ya sea como opciones separadas como en `-l -r` o combinadas como `-lr`. El resultado de los siguientes ejemplos sería el mismo:

`ls -l -r`
`ls -rl`
`ls -lr`

Como se ha explicado anteriormente, `-l` proporciona un formato de listado largo y `-r` invierte el listado. El resultado de usar ambas opciones será un listado largo en orden alfabético inverso:

```bash
sysadmin@localhost:~$ ls -l -r
total 32
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Videos                         
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Templates                      
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Public                         
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Pictures                       
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Music                          
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Downloads                      
drwx------ 4 sysadmin sysadmin 4096 Dec 20  2017 Documents                      
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Desktop   
sysadmin@localhost:~$ ls -rl
total 32
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Videos                         
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Templates                      
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Public                         
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Pictures                       
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Music                          
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Downloads                      
drwx------ 4 sysadmin sysadmin 4096 Dec 20  2017 Documents                      
drwx------ 2 sysadmin sysadmin 4096 Dec 20  2017 Desktop
```

Los comandos pueden utilizar muchas combinaciones de opciones y argumentos. Las posibilidades para cada comando serán únicas. ¿Recuerda los huevos de Pascua (*Easter Eggs*) del comando `aptitude`?

```bash
sysadmin@localhost:~$ aptitude moo
There are no Easter Eggs in this program.
```

Es posible modificar el comportamiento de este comando usando opciones. Vea lo que sucede cuando se agrega la opción `-v (verbose):

```bash
sysadmin@localhost:~$ aptitude -v moo
There really are no Easter Eggs in this program.
```

Mediante la combinación de múltiples opciones `-v`, podemos obtener una variedad de respuestas:

```bash
sysadmin@localhost:~$ aptitude -vv moo
Didn't I already tell you that there are no Easter Eggs in this program?
sysadmin@localhost:~$ aptitude -vvv moo
Stop it!
```

Recuerde que las varias opciones se pueden denotar por separado o combinadas:

`aptitude -v -v moo` 
`aptitude -vv moo`

¡Siga añadiendo opciones `-v` para ver cuántas respuestas únicas puede obtener!

## Imprimir el directorio de trabajo

Para descubrir dónde se encuentra actualmente dentro del sistema de archivos, puede utilizar el comando `pwd`. El comando `pwd` imprime el directorio de trabajo (print working directory), su ubicación actual dentro del sistema de archivos:

`pwd [OPCIONES]`

**A tener en cuenta**

¡No encienda su impresora todavía! En los inicios de la computación, el resultado de un comando se enviaba directamente a impresoras físicas. Este método ha sido reemplazado por pantallas de vídeo que muestran información más rápidamente. Aún así, actualmente seguimos utilizando la palabra imprimir (print) aunque el resultado se esté mostrando en una pantalla.

```bash
sysadmin@localhost:~$ pwd
/home/sysadmin
```

El resultado del comando anterior indica que el usuario está actualmente en su carpeta de inicio, tal y como muestra el sistema de archivos siguiente.

![sysadmin](images/sysadmin.png)

**Considere esto**

Observe que nuestras máquinas virtuales emplean un indicador para mostrar el directorio de trabajo actual, resaltado en color azul. En el primer mensaje, el carácter `~` azul es equivalente a `/home/sysadmin`, y representa el directorio de inicio del usuario.

`sysadmin@localhost:~$`

Después de cambiar de directorio (aprenderemos cómo hacerlo en la siguiente sección), la nueva ubicación también se puede confirmar en el nuevo indicador, que nuevamente se muestra en azul.

`sysadmin@localhost:/etc/calendar$`

## Cambio de Directorios

Los archivos se utilizan para almacenar datos como texto, gráficos y programas. Los directorios son un tipo de archivo utilizado para almacenar otros archivos: proporcionan una estructura organizativa jerárquica. La siguiente imagen muestra una versión abreviada de la estructura del sistema de archivos de nuestras máquinas virtuales.

![Filesystem hierarchy](imeges/Filesystemhierarchy.png)


Al iniciar una máquina virtual nueva, ya sea abriendo el curso o después de usar el botón de reinicio, usted inicia una sesión como usuario sysadmin en su directorio principal, resaltado en azul a continuación:

![Filesystem showing root directory](imeges/Filesystemshowingrootdirectory.png)


Utilice el comando cd (change directory) para cambiar de directorio y navegar por la estructura del sistema de archivos.

`cd [opciones] [ruta]`

Si examina el gráfico anterior, notará que el directorio Documents se encuentra dentro del directorio de inicio home, donde usted se encuentra actualmente. Para desplazarse al directorio Documents, utilícelo como argumento para el comando cd:

```bash
sysadmin@localhost:~$ cd Documents                                              
sysadmin@localhost:~/Documents$
```

Los directorios son equivalentes a las carpetas en Windows y Mac OS. Al igual que estos sistemas operativos más populares, una estructura de directorios Linux también tiene un nivel superior. No se llama “Mi PC”, sino directorio raíz (root) y está representado por el carácter /. Para desplazarse al directorio root, utilice el carácter / como argumento del comando `cd`.

```bash
sysadmin@localhost:~/Documents$ cd /
sysadmin@localhost:/$
```

![Filesystem hierarchy with highlighted root directory at the top](images/directorioroot.png)

El argumento para el comando `cd` es más que el nombre de un directorio, en realidad es una ruta (path). Una ruta es una lista de directorios separados por el carácter /. Por ejemplo, /home/sysadmin es la ruta a su directorio de inicio:

![directory.png](images/directorioroot.png)

Imagine que el sistema de archivos es un mapa, las rutas son las instrucciones que indican paso a paso la ubicación de cualquier archivo dentro del sistema de archivos. Hay dos tipos de rutas: absolutas y relativas. Las rutas absolutas comienzan en la raíz del sistema de archivos, las rutas relativas comienzan en su ubicación actual.

### Rutas absolutas

Una ruta absoluta le permite especificar la ubicación exacta de un directorio. Siempre comienza en el directorio root, por lo tanto siempre comienza con el carácter /. La ruta al directorio de inicio (home) /home/sysadmin es una ruta absoluta. La ruta comienza en el directorio root /, se mueve al directorio de inicio home y, a continuación, al directorio sysadmin. Esta ruta en una interfaz gráfica de usuario (GUI) como la de su ordenador personal aparecería así:

![rutes](images/4_9.gif)

Utilice esta ruta como argumento para el comando cd para volver al directorio principal del usuario sysadmin.

```bash
sysadmin@localhost:/$ cd /home/sysadmin
sysadmin@localhost:~$
```

Que no aparezca un resultado en la línea de comandos significa que el comando se ha ejecutado correctamente. Continúe y confirme que es así usando el comando pwd:

```bash
sysadmin@localhost:~$ pwd                                                       
/home/sysadmin
```

### Rutas relativas

Una ruta relativa ubica un archivo en relación con la ubicación actual del usuario en el sistema de archivos. Las rutas relativas no comienzan con el carácter /, comienzan con el nombre de un directorio. Eche otro vistazo al primer ejemplo de comando cd. En este caso, el argumento es un ejemplo de la ruta relativa más simple: el nombre de un directorio en su ubicación actual.

```bash
sysadmin@localhost:~$ cd Documents                                              
sysadmin@localhost:~/Documents$
```

![Highlighted sysadmin directory](images/Highlightedsysadmindirectory.png)

La siguiente imagen muestra un mapa de los archivos contenidos en el directorio sysadmin. Actualmente se encuentra en el directorio Documents y desea desplazarse al directorio Art:

![The highlighted Art directory](images/thehighlightedArtdirectory.png)

Una ruta relativa comienza con el directorio actual, sin embargo, éste no se incluye en la ruta. El primer paso sería pasar al directorio School y, a continuación, pasar al directorio Art. Utilice el carácter / para separar los nombres de directorio. El resultado School/Art es una ruta relativa desde el directorio Documents hasta el directorio Art:

![Filesystem system hierarchy showing sysadmin directory at the top and a relative path to the Art directory.](images/4_7.png)

Utilice la ruta relativa como argumento para el comando cd para desplazarse al directorio Art.

```bash
sysadmin@localhost:~/Documents$ cd School/Art
sysadmin@localhost:~/Documents/School/Art$
```

Utilice el comando `pwd` para confirmar que el cambio ha ocurrido:

```bash
sysadmin@localhost:~/Documents/School/Art$ pwd                                      
/home/sysadmin/Documents/School/Art
```

**A tener en cuenta**

El resultado del comando pwd es la ruta absoluta al directorio Art.

![Filesystem system hierarchy showing root directory at the top and a relative path to the Art directory.](images/4_8.png)

**A tener en cuenta**

En el ejemplo anterior, el comando cd siguió la ruta School/Art:

`cd School/Art`

Una ruta también se puede dividir en varios comandos cd. El siguiente conjunto de comandos lograría los mismos resultados:

```bash
cd School
cd Art
```

### Accesos Directos o Atajos

**Dos puntos ..**

Independientemente del directorio en el que se encuentre, el carácter .. siempre representa un directorio superior en relación al directorio actual, a veces denominado directorio padre. Por ejemplo, para pasar del directorio Art al directorio School:

```bash
sysadmin@localhost:~/Documents/School/Art$ cd ..                                
sysadmin@localhost:~/Documents/School$
```

**Un punto .**

Independientemente del directorio en el que se encuentre, el carácter . siempre representa su directorio actual. Para el comando `cd`, este atajo no es muy útil, pero será útil para los comandos que estudiaremos en las secciones siguientes.

**El símbolo ~**

El directorio principal del usuario actual está representado por el carácter ~ . Como se indicó anteriormente, siempre comienza su sesión como usuario sysadmin, cuyo directorio de inicio se encuentra en /home/sysadmin. Para volver a su directorio de inicio en cualquier momento, puede ejecutar el siguiente comando:

```bash
sysadmin@localhost:~/Documents/School$ cd ~
sysadmin@localhost:~$
```