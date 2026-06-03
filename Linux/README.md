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

## Listados de archivos

El comando `ls` se utiliza para enumerar el contenido de un directorio. Ha visto cómo se utiliza en varios ejemplos anteriores. Esta página le ayudará a sentirse más cómodo con su uso.

`ls [OPCIONES] [ARCHIVO]`

De forma predeterminada, el comando ls usado sin opciones o argumentos mostrará los archivos contenidos en el directorio actual:

```bash 
sysadmin@localhost:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  Templates Videos
```

Para obtener información detallada sobre los archivos, como el tipo de archivo, los permisos, las propiedades o el sello horario, ejecute una lista larga utilizando la opción -l con el comando ls. En el ejemplo siguiente, se utiliza una lista del directorio /var/log, ya que proporciona una variedad de resultados:

```bash
sysadmin@localhost:~$ ls -l /var/log/
total 844                                                                       
-rw-r--r-- 1 root   root  18047 Dec 20  2017 alternatives.log                   
drwxr-x--- 2 root   adm    4096 Dec 20  2017 apache2                            
drwxr-xr-x 1 root   root   4096 Dec 20  2017 apt                                
-rw-r----- 1 syslog adm    1346 Oct  2 22:17 auth.log                           
-rw-r--r-- 1 root   root  47816 Dec  7  2017 bootstrap.log                      
-rw-rw---- 1 root   utmp      0 Dec  7  2017 btmp                               
-rw-r----- 1 syslog adm     547 Oct  2 22:17 cron.log                           
-rw-r----- 1 root   adm   85083 Dec 20  2017 dmesg                              
-rw-r--r-- 1 root   root 325238 Dec 20  2017 dpkg.log                           
-rw-r--r-- 1 root   root  32064 Dec 20  2017 faillog                            
drwxr-xr-x 2 root   root   4096 Dec  7  2017 fsck                               
-rw-r----- 1 syslog adm     106 Oct  2 19:57 kern.log                           
-rw-rw-r-- 1 root   utmp 292584 Oct  2 19:57 lastlog                            
-rw-r----- 1 syslog adm   19573 Oct  2 22:57 syslog                             
drwxr-xr-x 2 root   root   4096 Apr 11  2014 upstart                            
-rw-rw-r-- 1 root   utmp    384 Oct  2 19:57 wtmp 
```

Cada línea corresponde a un archivo contenido en el directorio. La información sobre cada archivo se puede dividir en campos separados por espacios. Los campos son los siguientes:

**Tipo de archivo**

`-rw-r--r-- 1 root   root  18047 Dec 20  2017 alternatives.log`    
                
`drwxr-x--- 2 root   adm    4096 Dec 20  2017 apache2`

El primer campo contiene en realidad diez caracteres. El primer carácter indica el tipo de archivo y los nueve siguientes especifican permisos. Los tipos de archivo son:

Símbolo | Tipo de archivo | Descripción |
|---|---|---|
| d | directorio | Un archivo usado para contener otros archivos. |
| - | archivo ordinario | Incluye archivos leíbles, imágenes, archivos binarios, y archivos comprimidos. |
| l | enlaces simbólicos | Apunta a otro archivo. |
| s | socket | Permite la comunicación entre procesos. |
| p | tubería (pipe) | Permite la comunicación entre procesos. |
| b | archivo bloque | Usado para comunicaciones con el equipo (hardware). |
| c |archivo carácter | Usado para comunicaciones con el equipo (hardware). |

El primer archivo alternatives.log es un archivo normal -, mientras que el segundo archivo apache2 es un directorio d.

**Permisos**

`drwxr-xr-x 2 root   root   4096 Apr 11  2014 upstart`

Los permisos indican cómo determinados usuarios pueden acceder a un archivo. Siga leyendo para obtener más información sobre los permisos.

**Número de enlaces directos**

`-rw-r----- 1 syslog adm    1346 Oct  2 22:17 auth.log`

Este número indica cuántos enlaces directos apuntan a este archivo. Los enlaces directos están fuera del alcance de este módulo, pero están cubiertos en el curso NDG Linux Essentials.

**Propietario del archivo**

`-rw-r----- 1 syslog adm     106 Oct  2 19:57 kern.log`

El usuario syslog posee este archivo. Cada vez que se crea un archivo, la propiedad se asigna automáticamente al usuario que lo creó.

**Grupo propietario del archivo**

`-rw-rw-r-- 1 root   utmp 292584 Oct  2 19:57 lastlog`

Indica qué grupo posee este archivo.

**Tamaño del archivo**

`-rw-r----- 1 syslog adm   19573 Oct  2 22:57 syslog`

Los directorios y archivos más grandes pueden mostrarse en kilobytes ya que mostrar su tamaño en bytes resultaría en un número demasiado grande. Por lo tanto, en el caso de un directorio, este número podría ser un múltiplo del tamaño de bloque utilizado por el sistema de archivos. El tamaño de bloque es el tamaño de una serie de datos almacenados en el sistema de archivos.

**Sello horario o de tiempo**

`drwxr-xr-x 2 root   root   4096 Dec  7  2017 fsck`

Indica la fecha y hora en que el contenido del archivo se modificó por última vez.

**Nombre del archivo**

`-rw-r--r-- 1 root   root  47816 Dec  7  2017 bootstrap.log`

El campo final contiene el nombre del archivo o directorio.

**A tener en cuenta**

En el caso de enlaces simbólicos, un archivo que apunta a otro archivo, el nombre del enlace se mostrará junto a una flecha y el nombre de la ruta del archivo original.

`lrwxrwxrwx. 1 root root 22 Nov 6 2012 /etc/grub.conf -> ../boot/grub/grub.conf`

Los enlaces simbólicos están fuera del alcance de este módulo, pero están cubiertos en el curso [NDG Linux Essentials](https://www.netacad.com/courses/linux-essentials/).

### Ordenar archivos

Por defecto, el resultado del comando ls está ordenado alfabéticamente según el nombre del archivo. Pero también se puede ordenar usando otros método.

**Siga leyendo**

Las opciones en los siguientes ejemplos se combinarán con la opción -l para mostrar los detalles relevantes de cada archivo. Preste atención a los campos correspondientes a la opción de búsqueda.

La opción `-t` ordenará los archivos por su sello de tiempo (timestamp):

```bash
sysadmin@localhost:~$ ls -lt /var/log                                           
total 844                                                                       
-rw-r----- 1 syslog adm   19573 Oct  2 22:57 syslog                             
-rw-r----- 1 syslog adm    1346 Oct  2 22:17 auth.log                           
-rw-r----- 1 syslog adm     547 Oct  2 22:17 cron.log                           
-rw-rw-r-- 1 root   utmp 292584 Oct  2 19:57 lastlog                            
-rw-rw-r-- 1 root   utmp    384 Oct  2 19:57 wtmp                               
-rw-r----- 1 syslog adm     106 Oct  2 19:57 kern.log                           
-rw-r--r-- 1 root   root  18047 Dec 20  2017 alternatives.log                   
-rw-r--r-- 1 root   root  32064 Dec 20  2017 faillog                            
-rw-r----- 1 root   adm   85083 Dec 20  2017 dmesg                              
-rw-r--r-- 1 root   root 325238 Dec 20  2017 dpkg.log                           
drwxr-x--- 2 root   adm    4096 Dec 20  2017 apache2                            
drwxr-xr-x 1 root   root   4096 Dec 20  2017 apt                                
-rw-r--r-- 1 root   root  47816 Dec  7  2017 bootstrap.log                      
drwxr-xr-x 2 root   root   4096 Dec  7  2017 fsck                               
-rw-rw---- 1 root   utmp      0 Dec  7  2017 btmp                               
drwxr-xr-x 2 root   root   4096 Apr 11  2014 upstart  
```            

La opción `-S` (size) ordenará los archivos por tamaño de archivo:

```bash
sysadmin@localhost:~$ ls -l -S /var/log                                         
total 844                                                                       
-rw-r--r-- 1 root   root 325238 Dec 20  2017 dpkg.log                           
-rw-rw-r-- 1 root   utmp 292584 Oct  2 19:57 lastlog                            
-rw-r----- 1 root   adm   85083 Dec 20  2017 dmesg                              
-rw-r--r-- 1 root   root  47816 Dec  7  2017 bootstrap.log                      
-rw-r--r-- 1 root   root  32064 Dec 20  2017 faillog                            
-rw-r----- 1 syslog adm   19573 Oct  2 22:57 syslog                             
-rw-r--r-- 1 root   root  18047 Dec 20  2017 alternatives.log                   
drwxr-x--- 2 root   adm    4096 Dec 20  2017 apache2                            
drwxr-xr-x 1 root   root   4096 Dec 20  2017 apt                                
drwxr-xr-x 2 root   root   4096 Dec  7  2017 fsck                               
drwxr-xr-x 2 root   root   4096 Apr 11  2014 upstart                            
-rw-r----- 1 syslog adm    1346 Oct  2 22:17 auth.log                           
-rw-r----- 1 syslog adm     547 Oct  2 22:17 cron.log                           
-rw-rw-r-- 1 root   utmp    384 Oct  2 19:57 wtmp                               
-rw-r----- 1 syslog adm     106 Oct  2 19:57 kern.log                           
-rw-rw---- 1 root   utmp      0 Dec  7  2017 btmp
```

La opción `-r` (reverse) invertirá el orden de cualquier tipo de ordenación. Observe la diferencia cuando se agrega al ejemplo anterior:

```bash
sysadmin@localhost:~$ ls -lSr /var/log
total 844                                                                       
-rw-rw---- 1 root   utmp      0 Dec  7  2017 btmp                               
-rw-r----- 1 syslog adm     106 Oct  2 19:57 kern.log                           
-rw-rw-r-- 1 root   utmp    384 Oct  2 19:57 wtmp                               
-rw-r----- 1 syslog adm     654 Oct  2 23:17 cron.log                           
-rw-r----- 1 syslog adm    1669 Oct  2 23:17 auth.log                           
drwxr-xr-x 2 root   root   4096 Apr 11  2014 upstart                            
drwxr-xr-x 2 root   root   4096 Dec  7  2017 fsck                               
drwxr-xr-x 1 root   root   4096 Dec 20  2017 apt                                
drwxr-x--- 2 root   adm    4096 Dec 20  2017 apache2                            
-rw-r--r-- 1 root   root  18047 Dec 20  2017 alternatives.log                   
-rw-r----- 1 syslog adm   19680 Oct  2 23:17 syslog                             
-rw-r--r-- 1 root   root  32064 Dec 20  2017 faillog                            
-rw-r--r-- 1 root   root  47816 Dec  7  2017 bootstrap.log                      
-rw-r----- 1 root   adm   85083 Dec 20  2017 dmesg                              
-rw-rw-r-- 1 root   utmp 292584 Oct  2 19:57 lastlog                            
-rw-r--r-- 1 root   root 325238 Dec 20  2017 dpkg.log
```        

Los números en el campo del tamaño de archivo cambian de descendente a ascendente.

Utilizando solo la opción `-r` con la lista de los archivos en orden alfabético inverso:

```bash
sysadmin@localhost:~$ ls -r /var/log                                            
wtmp     lastlog   faillog   cron.log       auth.log  alternatives.log
upstart  kern.log  dpkg.log  btmp           apt
syslog   fsck      dmesg     bootstrap.log  apache2
```

# Acceso administrativo

Hay muchos comandos de Linux que tratan con información confidencial como contraseñas, hardware del sistema, u otros que operan bajo circunstancias excepcionales. Evitar que usuarios ordinarios ejecuten estos comandos ayuda a proteger el sistema. Iniciar una sesión como usuario root proporciona acceso administrativo, y permite la ejecución de algunos de los comandos privilegiados.

### El comando `su`

`su OPCIONES NOMBRE-DE-USUARIO`

El comando `su`le permite actuar temporalmente como un usuario diferente. Lo hace creando un nuevo shell. El shell es simplemente una consola de entrada de texto que le permite escribir comandos. De forma predeterminada, si no se especifica una cuenta de usuario, el comando su abrirá un nuevo shell como usuario root, proporcionando privilegios administrativos.

**Siga leyendo**

Se recomienda utilizar la opción shell para iniciar la sesión, ya que el shell de inicio de sesión configura completamente el nuevo shell con la configuración del nuevo usuario. Esta opción se puede especificar de tres maneras:

```bash
su -
su -l
su --login
```

Después de ejecutar el comando `su`, se requiere una contraseña. En nuestras máquinas virtuales, la contraseña para las cuentas root y sysadmin es netlab123 . Si alguna vez olvida la contraseña, ésta se muestra cada vez que se inicia una nueva máquina virtual. Como medida de seguridad, la contraseña no será visible mientras la escribe.

```bash
sysadmin@localhost:~$ su  -
Password:
root@localhost:~#
```

Tenga en cuenta que el símbolo del sistema ha cambiado para reflejar que ahora ha iniciado sesión como usuario root. Para cerrar la sesión y volver a la cuenta sysadmin, use el comando `exit`. Note como el símbolo vuelve a cambiar

```bash
root@localhost:~# exit
logout
sysadmin@localhost:~$
```
Para evitar ejecutar comandos sensibles o privilegiados, hemos configurado el comando steam locomotive, `sl`, para que requiera acceso administrativo. Si el comando se ejecuta como sysadmin, aparece un mensaje de error:

```bash
sysadmin@localhost:~$ sl
-bash: /usr/bin/sl: Permission denied
```

Utilice el comando su para cambiar a la cuenta root y ejecute el comando sl con acceso administrativo:

```bash
sysadmin@localhost:~$ su  -
Password:
root@localhost:~# sl
```

```bash

                            (@@) (  ) (@)  ( )  @@    ()    @     O   @
                         (   )
                     (@@@@)
                  (    )
                (@@@)
            ====        ________                ___________
        _D _|  |_______/        \__I_I_____===__|_________|
         |(_)---  |   H\________/ |   |        =|___ ___|
_________________
         /     |  |   H  |  |     |   |         ||_| |_||     _|
        |      |  |   H  |__--------------------| [___] |   =|
        | ________|___H__/__|_____/[][]~\_______|       |   -|
        |/ |   |-----------I_____I [][] []  D   |=======|____|__________________
      __/ =| o |=-~~\  /~~\  /~~\  /~~\ ____Y___________|__|____________________
       |/-=|___|=    ||    ||    ||    |_____/~\___/          |_D__D__D_|  |_D__
        \_/      \_O=====O=====O=====O/      \_/               \_/   \_/  \_/ 

```
Vuelva a utilizar el comando exit para volver a la cuenta sysadmin.

```bash
root@localhost:~# exit
logout
sysadmin@localhost:~$
```

## El comando `sudo`

`sudo [OPCIONES] COMANDO`

El comando `sudo` permite a un usuario ejecutar un comando como otro usuario sin tener que crear un nuevo shell. Para ejecutar un comando con privilegios administrativos utilice el comando como argumento para el comando `sudo`. Al igual que pasa con el comando `su`, el comando `sudo` asume por defecto que la cuenta de usuario root debe usarse para ejecutar comandos.

**A tener en cuenta**

El comando `sudo` también puede usarse para cambiar a otras cuentas de usuario. Para especificar una cuenta de usuario diferente, utilice la opción `-u`.

Ejecute el comando `sl` como usuario root poniendo `sudo` delante de él:

**Nota**

Recuerde que la contraseña es netlab123. La solicitud de contraseña no aparecerá de nuevo mientras el usuario continúe ejecutando comandos sudo a intervalos inferiores a cinco minutos.

```bash
sysadmin@localhost:~$  sudo sl
[sudo] password for sysadmin:
```

```bash


                            (@@) (  ) (@)  ( )  @@    ()    @     O   @
                         (   )
                     (@@@@)
                  (    )
                (@@@)
            ====        ________                ___________
        _D _|  |_______/        \__I_I_____===__|_________|
         |(_)---  |   H\________/ |   |        =|___ ___|
_________________
         /     |  |   H  |  |     |   |         ||_| |_||     _|
        |      |  |   H  |__--------------------| [___] |   =|
        | ________|___H__/__|_____/[][]~\_______|       |   -|
        |/ |   |-----------I_____I [][] []  D   |=======|____|__________________
      __/ =| o |=-~~\  /~~\  /~~\  /~~\ ____Y___________|__|____________________
       |/-=|___|=    ||    ||    ||    |_____/~\___/          |_D__D__D_|  |_D__
        \_/      \_O=====O=====O=====O/      \_/               \_/   \_/  \_/ 
```

Una vez completado el comando, observe que el símbolo del sistema no ha cambiado, usted continua bajo la cuenta de inicio sysadmin. El comando `sudo` sólo proporciona acceso administrativo para la ejecución del comando especificado. Esto es una ventaja ya que reduce el riesgo de que un usuario ejecute accidentalmente un comando como usuario root. La intención de ejecutar un comando es clara; el comando se ejecuta como root si se prefija con el comando `sudo`. De lo contrario, el comando se ejecuta como usuario ordinario.


## Permisos

Los permisos determinan la forma en que los diferentes usuarios pueden interactuar con un archivo o directorio. Al enumerar un archivo con el comando ls -l, el resultado incluye información sobre sus permisos. Para nuestro ejemplo usaremos un script llamado hello.sh ubicado en el directorio Documents:

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

```bash
sysadmin@localhost:~/Documents$ ls -l hello.sh                                  
-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh
```

A continuación repasamos los campos más relevantes para los permisos.

**Tipo de archivo**

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

El primer carácter de esta salida indica el tipo de archivo. Recuerde que si el primer carácter es un -, este es un archivo ordinario. Si el carácter fuera una d, se trataría de un directorio.

**Permisos**

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

Después del carácter de tipo de archivo, se muestran los permisos. Los permisos se dividen en tres grupos de tres caracteres:

**Propietario**

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

El primer grupo se refiere al usuario que posee el archivo. Si su cuenta actual es la propietaria del archivo, se usará el primer grupo de permisos y los demás permisos no tendrán efecto.

El usuario propietario del archivo y a quién se refieren estos permisos se puede determinar mediante el campo que muestra el usuario propietario:

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

**Grupo**

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

El segundo conjunto se refiere al grupo que posee el archivo. Si su cuenta actual no es la del propietario del archivo pero es miembro del grupo que posee el archivo, se aplicarán los permisos del grupo y los demás permisos no tendrán efecto.

El grupo propietario para este archivo puede ser determinado en el campo grupo propietario:

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

**Otros**

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

El último grupo es para todos los demás, cualquiera a quien los dos primeros conjuntos de permisos no sean aplicables. Si no es el usuario que posee el archivo o un miembro del grupo que posee el archivo, se le aplicará el tercer conjunto de permisos.

**Tipos de permisos**

Un archivo o directorio puede presentar tres permisos diferentes: leer, escribir y ejecutar. La forma en que se aplican estos permisos difiere entre archivos y directorios, como se muestra en la tabla siguiente:

| Permiso | Efectos sobre los Archivos | Efectos sobre los Directorios |
|---|---|---|
| leer (read) (r) | Permite que el contenido del archivo sea leído o copiado. | Sin el permiso para ejecutar, permite obtener un listado poco detallado de los archivos que contiene el directorio. Con el permiso para ejecutar, ls -l proporciona un listado detallado de archivos. |
| escribir (write) (w) | Permite modificar o reescribir el contenido del archivo. Permite añadir o eliminar archivos en un directorio. | 	Para que este permiso funcione, el directorio debe tener permiso para ejecutar. |
| ejecutar (execute) (x) | Permite que un archivo funcione como un proceso, aunque archivos script también requerirán el permiso leer (read). | Permite que el usuario se traslade del directorio si en el directorio padre también posee permiso escribir (write). |

**A tener en cuenta**

Comprender qué permisos se aplican en cada momento es una aptitud importante cuando trabajamos con Linux. Por ejemplo, considere el siguiente conjunto de permisos:

`-r--rw-rwx. 1 sysadmin staff 999 Apr  10  2013 /home/sysadmin/test`

En este escenario, el usuario sysadmin termina teniendo menos acceso a este archivo que los miembros del grupo staff o todos los demás. El usuario sysadmin sólo tiene los permisos de r--. No importa si sysadmin es miembro del grupo staff; una vez establecida la propiedad del usuario, solo se aplican los permisos del usuario propietario.git 

## Cambiar los permisos de los archivos

El comando `chmod `se utiliza para cambiar los permisos de un archivo o directorio. Sólo el usuario raíz o el usuario propietario del archivo puede cambiar los permisos de un archivo.

*Considere esto*

¿Por qué el comando se llama **chmod** en lugar de chperm? Los permisos solían denominarse modos de acceso, por lo que el comando **chmod** realmente significa cambiar los modos de acceso (change access mode).

Hay dos métodos para cambiar permisos usando el comando **chmod:** el método simbólico y el método octal. El método simbólico es útil para cambiar un conjunto de permisos a la misma vez. El método octal o numérico requiere conocer el valor octal de cada uno de los permisos y requiere que los tres conjuntos de permisos (usuario, grupo, otros) se especifiquen cada vez. Para simplificar las cosas, solamente trataremos el método simbólico. Para obtener más información sobre el método octal eche un vistazo al curso [NDG Linux Essentials](https://www.netdevgroup.com/online/courses/ndg_linux_essentials.html.)

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

## El método simbólico

`chmod [<COJUNTO DE PERMISOS><ACCIÓN><PERMISOS>]... ARCHIVO`

Para usar el método simbólico de `chmod` primero debe indicar qué conjunto de permisos se está cambiando:

`chmod [<CONJUNTO DE PERMISOS><ACCIÓN><PERMISOS>]... ARCHIVO`

| Símbolo | Significado |
|---|---|
| u | Usuario: El usuario propietario del archivo. |
| g | Grupo: El grupo propietario del archivo. |
| o | Otros: Cualquier otro que no sea el usuario propietario o un miembro del grupo propietario. |
| a | Todos: Se refiere al usuario, grupo, y todos los demás. |

A continuación, especifique un símbolo para la acción:

`chmod [<CONJUNTO DE PERMISOS><ACCIÓN><PERMISOS>]... ARCHIVO`

| Símbolo | Significado |
|---|---|
| + | Añadir permiso, si es necesario |
| = | Especificar el permiso exacto |
| - | Eliminar el permiso, si es necesario |

Después del símbolo de acción, especifique uno o más permisos.

`chmod [<CONJUNTO DE PERMISOS><ACCIÓN><PERMISOS>]... ARCHIVO`

| Símbolo | Significado |
|---|---|
| r | leer (read) |
| w | escribir (write) |
| x | ejecutar (execute) |

Finalmente, añada un espacio y los nombres de ruta para los archivos a los que quiere asignar los permisos.

`chmod [<CONJUNTO DE PERMISOS><ACCIÓN><PERMISOS>]... ARCHIVO`

El archivo hello.sh utilizado en los ejemplos de la página anterior es un script. Un script es un archivo que se puede ejecutar, similar a un comando:

```bash
ysadmin@localhost:~/Documents$ ls -l hello.sh                                  
-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh
```

Sin embargo, actualmente, el permiso de ejecución no ha sido establecido para ninguno de los grupos de permisos:

`-rw-r--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

De esta manera, intentar ejecutar este script utilizando la siguiente sintaxis produce un error:

```bash
sysadmin@localhost:~/Documents$ ./hello.sh                                      
-bash: ./hello.sh: Permission denied
```

Dado que el sistema está actualmente conectado como usuario sysadmin, y sysadmin es el propietario de este archivo, otorgar el permiso de ejecución al usuario propietario debería permitirle ejecutar este script. Usando el comando `chmod` con el carácter u para representar el conjunto de permisos del usuario propietario, y agregando el carácter + para indicar que se añade ­un permiso y el carácter x para representar el permiso de ejecución, el comando deberá ejecutarse con la siguiente sintaxis:

`sysadmin@localhost:~/Documents$ chmod u+x hello.sh`

No obtener un resultado/mensaje indica que el comando se ha realizado correctamente. Confírmelo examinando los permisos con el comando l`s -l`:

```bash
sysadmin@localhost:~/Documents$ ls -l hello.sh                                  
-rwxr--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh
```

El usuario propietario ahora posee permiso para ejecutar:

`-rwxr--r-- 1 sysadmin sysadmin 647 Dec 20  2017 hello.sh`

Finalmente, intente ejecutar el script de nuevo. Utilice la sintaxis de comando que se muestra a continuación:

`./hello.sh`

```bash
sysadmin@localhost:~/Documents$ ./hello.sh                                      
 ______________                                                                 
( Hello World! )                                                                
 --------------                                                                 
        \                                                                       
         \                                                                      
           <(^)                                                                 
            ( ) 
```

*A tener en cuenta*

Observe que para ejecutar el script en el ejemplo anterior, la siguiente combinación de caracteres ./ se colocó antes del nombre del script.

`./hello.sh`

Esto indica que el comando debe ejecutarse desde el directorio actual.

## Cambiar el propietario de un archivo

Inicialmente, el propietario de un archivo es el usuario que lo crea. El comando `chown` se utiliza para cambiar el propietario de los archivos y directorios. Cambiar el usuario propietario requiere acceso administrativo. Un usuario ordinario no puede utilizar este comando para cambiar el usuario propietario de un archivo, ni tan solo para otorgar propiedad de uno de sus propios archivos a otro usuario. Sin embargo, el comando `chown` permite cambiar el grupo propietario, lo cual puede ser realizado por el usuario root o el propietario del archivo.

Para cambiar el usuario propietario de un archivo, se puede utilizar la siguiente sintaxis. El primer argumento, [PROPIETARIO], especifica qué usuario debe ser el nuevo propietario. El segundo argumento, ARCHIVO, especifica el archivo al cual se está cambiando el propietario.

`chown [OPCIONES] [PROPIETARIO] ARCHIVO`

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

Actualmente, todos los archivos del directorio Documents son propiedad del usuario sysadmin. Esto se puede verificar mediante el comando `ls -l`. Recuerde que la tercera columna indica cual es el usuario propietario.

```bash
sysadmin@localhost:~/Documents$ ls -l                                           
total 144                                                                       
drwx------ 5 sysadmin sysadmin  4096 Dec 20  2017 School                        
drwx------ 2 sysadmin sysadmin  4096 Dec 20  2017 Work                          
-rw-r--r-- 1 sysadmin sysadmin    39 Dec 20  2017 adjectives.txt                
-rw-r--r-- 1 sysadmin sysadmin    90 Dec 20  2017 alpha-first.txt               
-rw-r--r-- 1 sysadmin sysadmin   106 Dec 20  2017 alpha-second.txt              
-rw-r--r-- 1 sysadmin sysadmin   195 Dec 20  2017 alpha-third.txt               
-rw-r--r-- 1 sysadmin sysadmin   390 Dec 20  2017 alpha.txt                     
-rw-r--r-- 1 sysadmin sysadmin    42 Dec 20  2017 animals.txt                   
-rw-r--r-- 1 sysadmin sysadmin    14 Dec 20  2017 food.txt                      
-rwxr--r-- 1 sysadmin sysadmin   647 Dec 20  2017 hello.sh                      
-rw-r--r-- 1 sysadmin sysadmin    67 Dec 20  2017 hidden.txt                    
-rw-r--r-- 1 sysadmin sysadmin    10 Dec 20  2017 letters.txt                   
-rw-r--r-- 1 sysadmin sysadmin    83 Dec 20  2017 linux.txt                     
-rw-r--r-- 1 sysadmin sysadmin 66540 Dec 20  2017 longfile.txt                  
-rw-r--r-- 1 sysadmin sysadmin   235 Dec 20  2017 newhome.txt                   
-rw-r--r-- 1 sysadmin sysadmin    10 Dec 20  2017 numbers.txt                   
-rw-r--r-- 1 sysadmin sysadmin    77 Dec 20  2017 os.csv                        
-rw-r--r-- 1 sysadmin sysadmin    59 Dec 20  2017 people.csv                    
-rw-r--r-- 1 sysadmin sysadmin   110 Dec 20  2017 profile.txt                   
-rw-r--r-- 1 sysadmin sysadmin    51 Dec 20  2017 red.txt
```   

Para cambiar el propietario actual del script hello.sh al usuario root, use root como primer argumento y hello.sh como segundo argumento. No olvide usar el comando `sudo` para obtener los privilegios administrativos necesarios. Utilice la contraseña netlab123 cuando se le solicite:

```bash
sysadmin@localhost:~/Documents$ sudo chown root hello.sh                        
[sudo] password for sysadmin:
```

Confirme que el usuario propietario ha cambiado ejecutando el comando `ls -l`. Utilice el nombre del archivo como argumento para limitar la salida:

```bash
sysadmin@localhost:~/Documents$ ls -l hello.sh                                  
-rwxr--r-- 1 root sysadmin 647 Dec 20  2017 hello.sh  
```

El campo de usuario propietario es ahora root, lo que indica que el cambio se ha realizado correctamente.

`-rwxr--r-- 1 root sysadmin 647 Dec 20  2017 hello.sh`

**A tener en cuenta**

Intente ejecutar el script hello.sh de nuevo. ¡Error! ¿Por qué?

```bash
sysadmin@localhost:~/Documents$ ./hello.sh                                      
-bash: ./hello.sh: Permission denied
```

Sólo el usuario propietario tiene permiso para ejecutar. Ahora el usuario root es el usuario propietario. Ahora este archivo requiere acceso administrativo para ejecutarse. Utilice el comando `sudo` para poder ejecutar el script como usuario root.

```bash
sysadmin@localhost:~/Documents$ sudo ./hello.sh                                 
[sudo] password for sysadmin:                                                   
 ______________                                                                 
( Hello World! )                                                                
 --------------                                                                 
        \                                                                       
         \                                                                      
           <(^)                                                                 
            ( )  
```

## Visualización de archivos

Existen varios comandos en Linux disponibles para visualizar el contenido de los archivos. El comando `cat`, que significa “concatenar”, a menudo se usa para ver rápidamente el contenido de archivos pequeños.

El comando `cat` mostrará todo el contenido del archivo, por lo que se recomienda principalmente para archivos pequeños para los que el resultado es limitado y no requiere desplazamientos de pantalla. Para ver el contenido de un archivo utilizando el comando `cat`, simplemente escriba el comando y utilice el nombre del archivo que desea ver como argumento:

`cat [OPCIONES] [ARCHIVO]`

Nuestra máquina virtual tiene algunos pequeños archivos de texto que puede visualizar con el comando cat. Uno de estos archivos es el archivo animals.txt:

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

```bash
sysadmin@localhost:~/Documents$ cat animals.txt                            
1 retriever                                                             
2 badger                                                                
3 bat                                                                  
4 wolf                                                                  
5 eagle
```

El comando `cat` muestra las cinco líneas del archivo de interés. Si lo usa para visualizar archivos más grandes, el comando `cat` puede generar un resultado muy largo que no puede pausarse o verse en secciones en la pantalla. Un mejor método para ver archivos de texto largos, es utilizar un comando de paginación con funcionalidad de pausa y que permite ver el contenido del archivo de interés en secciones.

**Nota**

Ejemplos de comandos de paginación incluyen los comandos `more` y `less`. Estos y otros comandos adicionales usados para visualizar archivos en Linux se examinan en el curso [NDG Linux Essentials](https://www.netdevgroup.com/online/courses/ndg_linux_essentials.html).

Otra forma de ver el contenido de los archivos es utilizando los comandos `head` y `tail` . Estos comandos se utilizan para ver un número seleccionado de líneas desde la parte superior o inferior de un archivo. Echar un vistazo a algunas líneas de un archivo puede ser útil para asegurarse de que el archivo es realmente el que desea utilizar.

Obtener una vista previa de las primeras o últimas líneas de un archivo es también útil para algunos archivos, como los archivos de registro del sistema, porque se actualizan con nuevas entradas frecuentemente. Al igual que el comando `cat`, los comandos `head` y `tail` utilizan el nombre del archivo a visualizar como argumento del comando:

`head [OPCIONES] [ARCHIVO]`

`tail [OPCIONES] [ARCHIVO]`

Para comparar la salida de los comandos `head` y `tail` con la del comando `cat`, utilice el comando `cat` para ver todo el archivo alpha.txt:

```bash
sysadmin@localhost:~/Documents$ cat alpha.txt       
A is for Apple                    
B is for Bear           
C is for Cat                      
D is for Dog                               
E is for Elephant                                      
F is for Flower       
G is for Grapes                     
H is for Happy                                     
I is for Ink                                                         
J is for Juice                                   
K is for Kangaroo
L is for Lol                                                             
M is for Monkey                       
N is for Nickel                             
O is for Oval                  
P is for Pickle       
Q is for Quark                         
R is for Rat                          
S is for Sloth                       
T is for Turnip                        
U is for Up                                     
V is for Velvet                       
W is for Walrus                    
X is for Xenon                        
Y is for Yellow         
Z is for Zebra           
sysadmin@localhost:~/Documents$
```

En el ejemplo anterior, se muestran las veintiséis líneas del archivo.

Para visualizar solamente las primeras líneas del resultado anterior para el archivo alpha.txt, utilice el comando `head`:

```bash
sysadmin@localhost:~/Documents$ head alpha.txt                          
A is for Apple                                                        
B is for Bear                                                         
C is for Cat                                                        
D is for Dog                                                         
E is for Elephant                                                     
F is for Flower                                                       
G is for Grapes                                                        
H is for Happy                                                        
I is for Ink                                                          
J is for Juice
```

A continuación, para ver las últimas líneas del archivo alpha.txt, utilice el comando `tail`:

```bash
sysadmin@localhost:~/Documents$ tail alpha.txt                          
Q is for Quark                                                         
R is for Rat                                                           
S is for Sloth                                                        
T is for Turnip                                                        
U is for Up                                                            
V is for Velvet                                                      
W is for Walrus                                                        
X is for Xenon                                                        
Y is for Yellow                                                        
Z is for Zebra
```

Al examinar la salida de los comandos `head` y `tail` anteriores, puede ver que el comportamiento predeterminado de los comandos `head` y `tail` en este shell es mostrar diez líneas.

La opción `-n` con los comandos head y tail se puede utilizar para especificar la cantidad de líneas a mostrar. Para utilizar la opción `-n`, especifique la cantidad de líneas del archivo que desea mostrar después de la opción y utilice el nombre de archivo como argumento:

`head -n número_de_líneas archivo`

Por ejemplo, para cambiar la salida por defecto del comando `head` y ver las cinco primeras líneas del archivo alpha.txt:

```bash
sysadmin@localhost:~/Documents$ head -n 5 alpha.txt                    
A is for Apple                                                         
B is for Bear                                                          
C is for Cat                                                           
D is for Dog                                                           
E is for Elephant
```

Para ver las últimas cinco líneas del archivo alpha.txt:

```bash
sysadmin@localhost:~/Documents$ tail -n 5 alpha.txt 
V is for Velvet                                                        
W is for Walrus                                                         
X is for Xenon                                                          
Y is for Yellow                                                         
Z is for Zebra            
sysadmin@localhost:~/Documents$
```

## Copiar archivos

Crear copias de archivos puede ser útil por numerosas razones:

  - Si se ha creado una copia del archivo antes de que se hayan realizado cambios, siempre podremos revertir al archivo original.
  - La copia de un archivo puede utilizarse para transferirlo a un dispositivo extraíble.
  - La copia de un documento puede utilizarse como plantilla para un documento nuevo.

`cp [OPCIONES] ORIGEN DESTINO`

**Continuemos...**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

El comando `cp` se utiliza para copiar archivos. Similar al comando `mv`, requiere al menos dos argumentos: *un origen* y *un destino*. Por ejemplo, para copiar el archivo /etc/passwd en el directorio actual, utilice el siguiente comando:

`sysadmin@localhost:~/Documents$ cp /etc/passwd .`

**Nota**

El segundo argumento es el carácter (.). Recuerde la sección Cambio de Directorio, este carácter es un atajo al directorio actual.

Ejecutar el comando anterior resulta en una copia del contenido del archivo /etc/passwd en el directorio Documents, ya que este es nuestro directorio actual. Esto se puede confirmar usando el comando ls:

```bash
sysadmin@localhost:~/Documents$ ls
School            alpha-third.txt  hidden.txt    numbers.txt  red.txt           
Work              alpha.txt        letters.txt   os.csv                         
adjectives.txt    animals.txt      linux.txt     passwd                         
alpha-first.txt   food.txt         longfile.txt  people.csv                     
alpha-second.txt  hello.sh         newhome.txt   profile.txt
```

**A tener en cuenta**

Los permisos pueden afectar a los comandos de administración de archivos, como el comando `cp`. Para copiar un archivo, es necesario tener permiso de ejecución para acceder al directorio donde se encuentra el archivo y permiso de lectura para el archivo que se está copiando.

También es necesario tener permiso de escritura y ejecución en el directorio al que se está copiando el archivo. Normalmente, hay dos lugares en los que siempre debe tener permisos de escritura y ejecución: su directorio home y el directorio /tmp.
Copy files

## Copiar archivos

El comando **dd** se utiliza para copiar archivos o particiones enteras al nivel de bits.

`dd [OPCIONES] OPERANDO`

Este comando tiene varias características útiles, entre las que se incluyen:

  - Se puede usar para clonar o eliminar (wipe) discos o particiones enteras.
  - Se puede usar para copiar datos no procesados (raw) a dispositivos extraíbles como dispositivos USB o CD ROMS.
  - Se puede usar para realizar una copia de reserva (backup) y restituir el MBR (Master Boot Record).
  - Se puede usar para crear un archivo de un tamaño específico lleno de ceros binarios, el cual puede utilizarse como archivo de intercambio (swap file) (memoria virtual).

Examinemos el siguiente ejemplo. El comando `dd` creará un archivo denominado */tmp/swapex* con 50 bloques de ceros de un megabyte de tamaño:

Siga leyendo

Utilice el siguiente comando `cd` para volver al directorio principal:

`sysadmin@localhost:~/Documents$ cd ~`

```bash
sysadmin@localhost:~$ dd if=/dev/zero of=/tmp/swapex bs=1M count=50 
50+0 records in
50+0 records out
52428800 bytes (52 MB) copied, 0.825745 s, 635 MB/s
```

El comando `dd` utiliza argumentos especiales para especificar cómo funcionará. A continuación se muestran algunos de los argumentos más utilizados:
| Argumento | Descripción |
|---|---|
| if | Archivo de entrada (Input File): El archivo de entrada que se va a leer. `dd if=/dev/zero of=/tmp/swapex bs=1M count=50`El ejemplo lee el archivo /dev/zero, un archivo especial que contiene un número ilimitado de ceros. |
| of | Archivo de salida (Output File): El archivo de salida que se va a escribir. `dd if=/dev/zero of=/tmp/swapex bs=1M count=50` |
| bs | Tamaño de bloque (*Block Siz*e): El tamaño de bloque que se va a utilizar. De forma predeterminada, el valor se presenta en bytes. Utilice los sufijos siguientes para especificar otras unidades: K, M, G y T para kilobytes, megabytes, gigabytes y terabytes respectivamente. `dd if=/dev/zero of=/tmp/swapex bs=1M count=50` En el ejemplo se utiliza un tamaño de bloque de un megabyte.
| count | Recuento: El número de bloques que se van a leer desde el archivo de entrada. `dd if=/dev/zero of=/tmp/swapex bs=1M count=50` En este ejemplo se leen 50 bloques. |

**A tener en cuenta**

No es necesario especificar el tamaño de bloque ni el recuento al copiar dispositivos enteros. Por ejemplo, para clonar de un disco duro (/dev/sda) a otro (/dev/sdb) ejecute el siguiente comando:

`dd if=/dev/sda of=/dev/sdb`

## Mover archivos

El comando `mv` se utiliza para mover un archivo de una ubicación en el sistema de archivos a otra.

`mv ORIGEN DESTINO`

El comando `mv` requiere dos argumentos como mínimo. El primer argumento es la fuente u origen, la ruta al archivo que va a ser movido. El segundo argumento es el destino, la ruta al lugar donde se moverá el archivo. Generalmente, los archivos que se van a mover se denominan origen, y el lugar donde se van a colocar se denomina destino.

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

Para mover el archivo people.csv al directorio *Work*, utilice el nombre del archivo como origen y el nombre del directorio como destino:

`sysadmin@localhost:~/Documents$ mv people.csv Work`

Si un archivo se mueve de un directorio a otro sin especificar un nuevo nombre para el archivo, éste conservará su nombre original. El movimiento anterior se puede confirmar mediante el comando `ls` en el directorio *Work*:

```bash
sysadmin@localhost:~/Documents$ ls Work                                         
people.csv
```

El comando `mv` puede utilizarse para mover varios archivos, siempre y cuando el argumento final proporcionado al comando sea el destino. Por ejemplo, para mover tres archivos al directorio *School*:

```bash
sysadmin@localhost:~/Documents$ mv numbers.txt letters.txt alpha.txt School        
sysadmin@localhost:~/Documents$ ls School                                       
Art  Engineering  Math  alpha.txt  letters.txt  numbers.txt 
```

Mover un archivo dentro del mismo directorio es una forma eficaz de cambiarlo de nombre. Por ejemplo, en el ejemplo siguiente, el archivo animals.txt recibe un nuevo nombre *zoo.txt*:

`mv animals.txt zoo.txt`

```bash
sysadmin@localhost:~/Documents$ ls                                              
School           alpha-second.txt  hello.sh      newhome.txt  red.txt           
Work             alpha-third.txt   hidden.txt    os.csv                         
adjectives.txt   animals.txt       linux.txt     passwd                         
alpha-first.txt  food.txt          longfile.txt  profile.txt 
sysadmin@localhost:~/Documents$ mv animals.txt zoo.txt                          
sysadmin@localhost:~/Documents$ ls                                              
School           alpha-second.txt  hidden.txt    os.csv       zoo.txt           
Work             alpha-third.txt   linux.txt     passwd                         
adjectives.txt   food.txt          longfile.txt  profile.txt                    
alpha-first.txt  hello.sh          newhome.txt   red.txt   
```

**A tener en cuenta**

Los permisos pueden afectar comandos de administración de archivos, incluyendo el comando `mv`. Mover un archivo requiere tener permisos de escritura y ejecución tanto en los directorios de origen como de destino.
Penguins in Space! Nasa Uses Linux. International Space Station runs on Linux. Curiosity the Mars Rover. We migrated key functions from Windows to Linux because we needed an operating system that was stable and reliable.
![Penguins In Space](images/messaging_4.png)

*«¡Pingüinos en el espacio! NASA utiliza Linux. La Estación Espacial Internacional funciona con Linux. "Migramos funciones esenciales de Windows a Linux porque necesitábamos un sistema operativo más estable y fiable." Keith Chuvala, manager de Operaciones Informáticas Espaciales de NASA. Curiosity, el Rover en Marte.»*

## Eliminar archivos

El comando `rm` (remove) se utiliza para eliminar archivos y directorios. Es importante tener en cuenta que los archivos y directorios eliminados no aparecen en una “papelera” como ocurre con los sistemas operativos orientados a escritorio. Cuando un archivo se elimina con el comando rm, generalmente siempre desaparece de manera permanente.

`rm [OPCIONES] ARCHIVO`

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

Sin ninguna opción, el comando rm normalmente se utiliza para eliminar archivos ordinarios:

```bash
sysadmin@localhost:~/Documents$ rm linux.txt
sysadmin@localhost:~/Documents$ ls linux.txt
ls: cannot access linux.txt: No such file or directory
```

El comando `rm` ignorará los directorios que se le pida eliminar. Para eliminar un directorio, utilice una opción recursiva, por ejemplo, las opciones `-r` o `-R`. Tenga cuidado ya que estas opciones son “recursivas”, y eliminarán todos los archivos y todos los subdirectorio:

```bash
sysadmin@localhost:~/Documents$ rm Work
rm: cannot remove 'Work': Is a directory
sysadmin@localhost:~/Documents$ rm -r Work
sysadmin@localhost:~/Documents$ ls Work                                         
ls: cannot access Work: No such file or directory
```

`Advertencia`

El comando `rm` elimina los archivos de forma permanente. Para repetir los ejemplos anteriores, restablezca el terminal usando el botón de reinicio.

**A tener el cuenta**

Los permisos pueden afectar a los comandos de administración de archivos, como el comando `rm`.

Para eliminar un archivo dentro de un directorio, el usuario debe tener permiso de escritura y ejecución en ese directorio. Normalmente, los usuarios ordinarios solo tienen este tipo de permiso en su directorio principal y subdirectorios correspondientes.

## Filtrado de entradas

El comando grep es un filtro de texto que busca líneas en una entrada y devolverá aquellas que coincidan con un patrón determinado.

`grep [OPCIONES] PATRÓN [ARCHIVO]`

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

Si el siguiente ejemplo le devuelve un mensaje de error, repita el ejemplo de la Sección 11:

`sysadmin@localhost:~/Documents$ cp /etc/passwd .`

Por ejemplo, el archivo passwd que copiamos anteriormente al directorio Documents contiene los detalles de cuentas especiales del sistema y cuentas de usuarios en el sistema. Este archivo puede ser muy grande, sin embargo, el comando `grep` se puede utilizar para filtrar y obtener información sobre un usuario específico, como por ejemplo el usuario sysadmin. Utilice sysadmin como argumento de patrón y passwd como argumento de archivo:

```bash
sysadmin@localhost:~/Documents$ grep sysadmin passwd                               
sysadmin:x:1001:1001:System Administrator,,,,:/home/sysadmin:/bin/bash 
```

El comando anterior devolvió la línea del passwd que contiene el patrón sysadmin.

**Nota**

Esta línea es la entrada */etc/passwd* que pertenece al usuario sysadmin y proporciona información que está más allá del alcance de este curso. Para obtener más información sobre este archivo, consulte [NDG Linux Essentials](https://www.netdevgroup.com/online/courses/ndg_linux_essentials.html).

El ejemplo anterior utiliza un término de búsqueda simple como patrón; sin embargo `grep` es capaz de interpretar patrones de búsqueda mucho más complejos.

## Expresiones regulares

Las expresiones regulares tienen dos formas comunes: la forma básica y la forma extendida. La mayoría de los comandos que utilizan expresiones regulares pueden interpretar expresiones regulares básicas. Sin embargo, las expresiones regulares extendidas no están disponibles para todos los comandos y normalmente requieren una opción de comando para funcionar correctamente.

En la siguiente tabla se resumen los caracteres básicos de las expresiones regulares:
| Caracteres Básicos Regex | Significado |
|---|---|
| . | Cualquier carácter individual |
| [ ] | Cualquier carácter especificado |
| [^] | Cualquier carácter que no es el carácter especificado |
| * | Cero o más del carácter anterior |
| ^ | Si es el primer carácter del patrón, el patrón deberá estar al principio de la línea para coincidir, si no es así se tratará como un ^ literal. |
| $ | Si es el último carácter del patrón, el patrón deberá estar al final de la línea para coincidir, si no es así se tratará como un $ literal. |

En la siguiente tabla se resumen las expresiones regulares extendidas, que se deben utilizar con el comando `egrep` o la opción `-E` con el comando `grep`:
| Caracteres Básicos Regex | Significado |
|---|---|
|+ | Uno o más del patrón anterior |
| ? | El patrón es opcional |
| { } | Especificar mínimo, máximo, o coincidencias exactas en el patrón anterior
| pipe | Alternancia - el “o” lógico |
| ( ) | Se usa para crear grupos |

En esta sección solamente hemos tratado expresiones regulares básicas. Para obtener más información sobre las expresiones regulares extendidas consulte los cursos [NDG Linux Essentials](https://www.netdevgroup.com/online/courses/ndg_linux_essentials.html) y [NDG Introduction to Linux](https://www.netdevgroup.com/online/courses/ndg_introduction_to_linux_1.html).

## Patrones básicos

Las expresiones regulares son patrones que sólo ciertos comandos pueden interpretar. Las expresiones regulares se pueden expandir para que coincidan con ciertas secuencias de caracteres en el texto. Los ejemplos que se muestran en esta página harán uso de expresiones regulares para demostrar su potencia cuando se utilizan con el comando `grep`. Además, estos ejemplos proporcionan una demostración muy visual de cómo funcionan las expresiones regulares, el texto que resulta de estas expresiones se mostrará en color rojo en el resultado (*output*).

**Siga leyendo**

Utilice el siguiente comando cd para cambiar al directorio Documents.

`sysadmin@localhost:~$ cd ~/Documents`

La más simple de todas las expresiones regulares solo usa caracteres de significado literal, como el ejemplo de la página anterior:

sysadmin@localhost:~/Documents$ grep sysadmin passwd                               
sysadmin:x:1001:1001:System Administrator,,,,:/home/sysadmin:/bin/bash

### Caracteres de anclaje

Los caracteres de anclaje son una de las formas con que se pueden utilizar expresiones regulares para limitar los resultados de una búsqueda. Por ejemplo, el patrón root aparece muchas veces en el archivo /etc/passwd:

```bash
sysadmin@localhost:~/Documents$ grep 'root' passwd
root:x:0:0:root:/root:/bin/bash                                                 
operator:x:1000:37::/root:
```

Para evitar que el shell los malinterprete como caracteres especiales del shell, estos patrones deben escribirse protegidos por comillas sólidas, lo que simplemente significa colocarlos entre comillas.

El primer carácter de anclaje ^ se utiliza para indicar que el patrón debe aparecer al principio de la línea. Por ejemplo, para encontrar todas las líneas en */etc/passwd* que comienzan con *root* use el patrón *^root*. Tenga en cuenta que ^ debe ser el primer carácter del patrón para ser efectivo.

```bash
sysadmin@localhost:~/Documents$ grep '^root' /etc/passwd
root:x:0:0:root:/root:/bin/bash
```

Para el siguiente ejemplo, examine primero el archivo `alpha-first.txt`. El comando `cat` se puede utilizar para mostrar el contenido del archivo:

```bash
sysadmin@localhost:~/Documents$ cat alpha-first.txt                             
A is for Animal                                                                 
B is for Bear                                                                   
C is for Cat                                                                    
D is for Dog                                                                    
E is for Elephant                                                               
F is for Flower
```

El segundo carácter de anclaje `$` se puede utilizar para indicar que el patrón debe aparecer al *final de la línea*, reduciendo eficazmente los resultados de la búsqueda. Para encontrar las líneas que terminan con una `r` en el archivo `alpha-first.txt`, utilice el patrón `r$`:

```bash
sysadmin@localhost:~/Documents$ grep 'r$' alpha-first.txt
B is for Bear
F is for Flower
```

Una vez más, la posición de este carácter es importante; el $ debe ser el último carácter en el patrón para ser eficaz como anclaje.

### Encontrar caracteres coincidentes usando .

Los siguientes ejemplos usan el archivo `red.txt`:

```bash
sysadmin@localhost:~/Documents$ cat red.txt
Red
Reef
Rot
Reeed
Rd
Rod
Roof
Reed
Root
reel
read
```

Una de las expresiones más útiles es el carácter . (punto). Representa cualquier carácter excepto el carácter de nueva línea. El patrón `r..f` encontrará cualquier línea que contenga la letra `r` seguida de exactamente dos caracteres (que pueden ser cualquier carácter excepto el de nueva línea) y luego la letra `f`:

```bash
sysadmin@localhost:~/Documents$ grep 'r..f' red.txt
reef
roof
```

El mismo concepto se puede repetir usando otras combinaciones. El comando en el ejemplo siguiente encontrará palabras de cuatro letras que comienzan con `r` y acaban con `d`:

```bash
sysadmin@localhost:~/Documents$ grep 'r..d' red.txt
reed
read
```

Este carácter se puede utilizar tantas veces como se desee. Para encontrar todas las palabras de al menos cuatro caracteres se puede utilizar el siguiente patrón:

```bash
sysadmin@localhost:~/Documents$ grep '....' red.txt                             
reef
reeed
roof           
reed
root
reel
read
```

La línea no tiene que coincidir exactamente, simplemente debe contener el patrón, como se ve a continuación cuando se busca `r..t` en el archivo `/etc/passwd`:

```bash
sysadmin@localhost:~/Documents$ grep 'r..t' /etc/passwd
root:x:0:0:root:/root:/bin/bash
operator:x:1000:37::/root:
```

### Encontrar un carácter único usando []

Los corchetes `[ ]` se utilizan para indicar caracteres *único*s o rangos de caracteres posibles en una lista.

Por ejemplo, dado el archivo `profile.txt`:

```bash
sysadmin@localhost:~/Documents$ cat profile.txt
Hello my name is Joe.
I am 37 years old.
3121991
My favorite food is avocados.
I have 2 dogs.
123456789101112
```

Para encontrar todas las líneas en el archivo `profile.txt` que contienen un número, utilice el patrón `[0123456789]` o `[0-9]`:

```bash
sysadmin@localhost:~/Documents$ grep '[0-9]' profile.txt
I am 37 years old.
3121991
I have 2 dogs.
123456789101112
```

Por otro lado, para encontrar todas las líneas que contienen caracteres no numéricos, inserte un ^ como primer carácter dentro de los corchetes. Este carácter *niega* los caracteres que lo siguen:

```bash
sysadmin@localhost:~/Documents$ grep '[^0-9]' profile.txt
Hello my name is Joe.
I am 37 years old.
My favorite food is avocados.
I have 2 dogs.
```

**Nota**

No confunda el resultado de `[^ 0-9]` con las líneas que no contienen números. En realidad, esta expresión se refiere a líneas que contienen *no-números* (caracteres no numéricos). Examine el archivo original para ver la diferencia. Las líneas tercera y sexta sólo contienen números, no contienen caracteres no numéricos, y por lo tanto no han sido incluidas en este último resultado.

Cuando otros caracteres de expresión regular se colocan dentro de corchetes, se tratan como caracteres literales. Por ejemplo, el carácter . normalmente indica cualquier carácter. Pero si se coloca dentro de corchetes simplemente se referirá al carácter . (punto). En el siguiente ejemplo, sólo las líneas que contienen el carácter . se mostrarán en el resultado.

```bash
sysadmin@localhost:~/Documents$ grep '[.]' profile.txt
Hello my name is Joe.
I am 37 years old.
My favorite food is avocados.
I have 2 dogs.
```

### Indicar un carácter o patrón repetido utilizando el *

El carácter de expresión regular * se utiliza para indicar la ausencia o la presencia una o más veces del carácter o patrón que lo precede. Por ejemplo, e* indicaría la ausencia (cero) o la presencia, una o más veces, de la letra e:

```bash
sysadmin@localhost:~/Documents$ cat red.txt
red
reef
rot
reeed
rd
rod
roof
reed
root
reel
read
sysadmin@localhost:~/Documents$ grep 're*d' red.txt
red
reeed
rd
reed
```

También es posible indicar la ausencia o presencia una o más veces de una lista de caracteres utilizando los corchetes. El patrón `[oe]*` utilizado en el siguiente ejemplo se refiere a líneas con ausencia o presencia una o más veces del carácter `o` o del carácter `e`:

```bash
sysadmin@localhost:~/Documents$ grep 'r[oe]*d' red.txt
red
reeed
rd
rod
reed
```

Cuando se usa con un solo carácter, `*` no resulta muy útil. Note que cualquiera de los siguientes patrones coincide con cada una de las líneas (string) del archivo: `.*` `e*` `b*` `z*`.

```bash
sysadmin@localhost:~/Documents$ grep 'z*' red.txt
red
reef
rot
reeed
rd
rod
roof
reed
root
reel
read
```
```bash
sysadmin@localhost:~/Documents$ grep 'e*' red.txt
red
reef
rot
reeed
rd
rod
roof
reed
root
reel
read
```

Esto se debe a que `*` puede indicar cero ocurrencias de un patrón. Para que el `*` sea útil, es necesario crear un patrón que incluya algo más que el carácter que precede al `*`. Por ejemplo, los resultados anteriores se pueden refinar agregando otra `e` para hacer que el patrón `ee*` coincida efectivamente con cada línea que contenga al menos una `e`.

```bash
sysadmin@localhost:~/Documents$ grep 'ee*' red.txt
red
reef
reeed
reed
reel
read
```

### Entrada estándar

Si no se proporciona un nombre de archivo, el comando `grep` actuará sobre la entrada estándar, que normalmente proviene del teclado y de la entrada proporcionada por el usuario que está ejecutando el comando. Esto permite que el uso de `gre`p se convierta en una experiencia interactiva donde el usuario escribe y `grep` filtra la entrada a medida que avanza. Pruébelo. Simplemente presione **Ctrl+D** cuando esté listo para volver al intérprete de comandos (*prompt*).

![entada estandar](images/comptia_1.gif)

**Siga leyendo**

Utilice el siguiente comando `cd` para volver al directorio principal:

`sysadmin@localhost:~/Documents$ cd ~`
![Linux is Open Source which makes it extremely versatile! Internet of Things, Big Data, Cloud Computing, Cyber Security, Networking and more.](images/messaging_5.png)

«Linux es open source. ¡Esto lo hace extremadamente versátil!»

## Apagar

El comando `shutdown` prepara el sistema para un apagado seguro. Todos los usuarios que han iniciado una sesión reciben la notificación de que el sistema se está apagando y se evitan nuevos inicios de sesión en los cinco minutos previos al apagado completo del sistema.

`shutdown [OPCIONES] HORA [MENSAJE]`

**Siga leyendo**

El comando `shutdown` requiere acceso administrativo, cambie a la cuenta `root` para esta sección utilizando el siguiente comando. Use *netlab123* como contraseña.

```bash
sysadmin@localhost:~$ su -                      
Password:                         
root@localhost:~#
```

¡En realidad nuestras máquinas virtuales no se apagan! Use el comando pero tenga en cuenta que, en lugar de apagar el sistema, solamente regresará a la línea de comandos. Quizás tenga que presionar **Enter** o **Ctrl+C** para volver a ver la línea de comandos.

```bash
root@localhost:~# shutdown now                                         
                                
Broadcast message from sysadmin@localhost                                       
        (/dev/pts/0) at 2:05 ...                                              
                
The system is going down for maintenance NOW!
```

A diferencia de otros comandos utilizados para apagar el sistema, el comando shutdown requiere un argumento de tiempo para especificar cuándo debe comenzar el apagado. Los formatos de este argumento de tiempo pueden ser la palabra now (ahora), una hora del día en el formato *hh:mm* o el número de minutos de retraso utilizando el formato *+minutos*.

**Piense sobre lo siguiente**

El reloj de nuestro sistema puede estar configurado en una zona horaria diferente a la que se encuentra usted. Para verificar la hora en la terminal, use el comando `date`. En nuestras máquinas, el formato predeterminado de la salida del comando `date` es el siguiente:

`dia_de_la_semana  mes  hora:minuto:segundo  UTC  año`

o en ingles:

`weekday month day hour:minute:second UTC year`

Las letras UTC presentes en la salida indican que la hora se muestra de acuerdo con el Horario Coordinado Universal.

```bash
root@localhost:~# date                                                      
Sat Oct  3 01:50:07 UTC 2020 
root@localhost:~# shutdown 01:51                                                
                                                                                
Broadcast message from sysadmin@localhost                                       
        (/dev/pts/0) at 1:50 ...                                              
                                                                                
The system is going down for maintenance in 1 minute!

Broadcast message from sysadmin@localhost                                       
        (/dev/pts/0) at 1:51 ...                                              
                                                                                
The system is going down for maintenance NOW!
```

El comando `shutdown` también posee la opción de añadir un mensaje como argumento. Este mensaje aparecerá en las terminales de todos los usuarios. Por ejemplo:

```bash
root@localhost:~# shutdown +1 "Goodbye World!"                                  
                                                                                
Broadcast message from sysadmin@localhost                                       
        (/dev/pts/0) at 3:07 ...                                              
                                                                                
The system is going down for maintenance in 1 minute!                           
Goodbye World!                                                                  
shutdown: Unable to shutdown system                                             
root@localhost:~#                                                             
Broadcast message from sysadmin@localhost                                       
        (/dev/pts/0) at 3:08 ...                                              
                                                                                
The system is going down for maintenance NOW!                                   
Goodbye World!
```

## Configuración de redes

El comando `ifconfig` significa “configuración de interfaz” (*interface configuration*) y se utiliza para mostrar información sobre la configuración de red.

`ifconfig [OPCIONES]`

**Nota**

El comando `iwconfig` es similar al comando `ifconfig`, pero se refiere a interfaces de redes inalámbricas (wireless).

No todas las configuraciones de red son importantes para este módulo, pero en el siguiente ejemplo es importante tener en cuenta que la dirección IPv4 del dispositivo de red principal `eth0` es `192.168.1.2` y que el dispositivo está activo actualmente (UP):

```bash
root@localhost:~# ifconfig                                     
eth0      Link encap:Ethernet  HWaddr 02:42:c0:a8:01:02                         
          inet addr:192.168.1.2  Bcast:192.168.1.255  Mask:255.255.255.0        
          UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1                    
          RX packets:59 errors:0 dropped:0 overruns:0 frame:0                   
          TX packets:86 errors:0 dropped:0 overruns:0 carrier:0                 
          collisions:0 txqueuelen:1000                                          
          RX bytes:4346 (4.3 KB)  TX bytes:5602 (5.6 KB)                        
                                                                                
lo        Link encap:Local Loopback                                             
          inet addr:127.0.0.1  Mask:255.0.0.0                                   
          UP LOOPBACK RUNNING  MTU:65536  Metric:1                              
          RX packets:2 errors:0 dropped:0 overruns:0 frame:0                    
          TX packets:2 errors:0 dropped:0 overruns:0 carrier:0                  
          collisions:0 txqueuelen:1000                                          
          RX bytes:100 (100.0 B)  TX bytes:100 (100.0 B)
```        

### Piense sobre lo siguiente

El dispositivo lo se conoce como dispositivo de *loopback*. Es un dispositivo de red especial utilizado por el sistema cuando envía datos basados en red a sí mismo.

El comando `ifconfig` también se puede utilizar para modificar temporalmente la configuración de red. Normalmente, estos cambios deben ser permanentes, por lo que raramente se usa el comando `ifconfig` para realizar dichos cambios.

El comando `ping` se utiliza para verificar la conectividad entre dos equipos. Para hacer esto, envía paquetes a otra máquina a través de la red. Que el remitente reciba una respuesta indica que es posible conectarse a esa máquina.

La información se envía mediante “paquetes”; que es la unidad encapsulada de datos enviada a través de una red. Para que los paquetes encuentren la otra computadora, necesitan una dirección. El comando `ping` utiliza direcciones IP para identificar un equipo en la red al que desea conectarse.

De forma predeterminada, el comando `ping` continuará enviando paquetes hasta que se introduzca el comando break (**CTL +C**) en la consola. Para limitar el número de pings que se envían, utilice la opción `-c` seguida del número de pings que desea enviar. El siguiente ejemplo muestra un `ping` limitado a 4 iteraciones usando `-c 4`.

Si el comando `ping` funciona, obtendrá un resultado como el siguiente:

```bash
root@localhost:~# ping -c 4 192.168.1.2                                       
PING 192.168.1.2 (192.168.1.2) 56(84) bytes of data.                          
64 bytes from 192.168.1.2: icmp_req=1 ttl=64 time=0.051 ms                    
64 bytes from 192.168.1.2: icmp_req=2 ttl=64 time=0.064 ms                    
64 bytes from 192.168.1.2: icmp_req=3 ttl=64 time=0.050 ms                    
64 bytes from 192.168.1.2: icmp_req=4 ttl=64 time=0.043 ms                    
                                                                              
--- 192.168.1.2 ping statistics ---                                           
4 packets transmitted, 4 received, 0% packet loss, time 2999ms                
rtt min/avg/max/mdev = 0.043/0.052/0.064/0.007 ms                             
root@localhost:~#
```

Si el comando `ping` falla, recibirá un mensaje indicando que no se encontró el ordenador de destino o máquina remota (Destination Host Unreachable):

```bash
root@localhost:~# ping -c 4 192.168.1.3                                       
PING 192.168.1.3 (192.168.1.3) 56(84) bytes of data.                            
From 192.168.1.2 icmp_seq=1 Destination Host Unreachable                        
From 192.168.1.2 icmp_seq=2 Destination Host Unreachable                        
From 192.168.1.2 icmp_seq=3 Destination Host Unreachable                        
From 192.168.1.2 icmp_seq=4 Destination Host Unreachable                        
                                                                                
--- 192.168.1.3 ping statistics ---                                             
4 packets transmitted, 0 received, +4 errors, 100% packet loss, time 3065ms     
pipe 4  
root@localhost:~#
```

El comando `ping` puede fallar aunque la máquina remota esté conectada a la red. Esto se debe a que, como medida de seguridad, algunos administradores configuran sus equipos, o incluso redes enteras, para que no respondan a solicitudes `ping`. El comando `ping` también funciona con un nombre de host, o con un nombre de dominio como yahoo.com. Usar ésto primero puede ahorrar tiempo, ya que si ese comando `ping` tiene éxito, indica que hay una resolución de nombre adecuada Y que la dirección IP también funciona correctamente.

**Siga leyendo**

Salga de la cuenta root mediante el comando `exit`:

```bash
root@localhost:~# exit                    
logout
```

## Visualización de procesos

Ejecutar un comando da como resultado algo llamado proceso. En el sistema operativo Linux, los procesos se ejecutan en función de los privilegios del usuario que ejecuta el comando. Esto permite que los procesos se limiten a ciertas funciones dependiendo de la identidad del usuario.

Aunque hay excepciones, generalmente el sistema operativo diferenciará entre los usuarios en función de si son o no el administrador. Normalmente, los usuarios habituales, como el usuario sysadmin, no pueden controlar los procesos de otro usuario. Los usuarios que tienen privilegios administrativos, como la cuenta root, pueden controlar cualquier proceso de cualquier usuario, incluyendo la detención de cualquier proceso.

El comando ps se puede utilizar para enumerar los procesos.

`ps [OPCIONES]`

```bash
sysadmin@localhost:~$ ps
  PID TTY          TIME CMD
   80 pts/0        00:00:00 bash
   94 pts/0        00:00:00 ps
```

Por defecto, el comando ps mostrará los procesos que se están ejecutando en la terminal actual. En el ejemplo anterior, la última línea corresponde al proceso generado al ejecutar el comando ps. La salida incluye las siguientes columnas de información:

 - PID: El identificador para el proceso (process identifier), el cual es único para cada proceso. Esta información es útil cuando necesitamos controlar los procesos según su número identificador (ID).

 - TTY: El nombre de la terminal en la que está funcionando el proceso. Esta información es útil para distinguir entre diferentes procesos que tienen el mismo nombre.

 - TIME: La cantidad total de tiempo de procesado que utiliza un proceso determinado. Normalmente, los usuarios normales no utilizan esta información.

 - CMD: El comando que inició el proceso.

En lugar de ver sólo los procesos que se están ejecutando en la terminal actual, los usuarios pueden querer ver todos los procesos que se están ejecutando en el sistema. La opción `-e` muestra todos estos procesos:

```dash
sysadmin@localhost:~$ ps -e
  PID TTY          TIME CMD                                                     
    1 pts/0        00:00:00 init                                                    
   33 ?            00:00:00 rsyslogd                                                
   37 ?            00:00:00 cron                                                    
   39 ?            00:00:00 sshd                                                    
   56 ?            00:00:00 named                                                   
   69 pts/0        00:00:00 login                                                   
   79 pts/0        00:00:00 bash                                                    
   94 pts/0        00:00:00 ps 
```

Muchas veces se puede utilizar la opción `-f` para proporcionar un resultado más detallado que incluya las opciones y los argumentos de cada proceso. Localice el comando `ps` en la última línea, la columna CMD ahora incluye las opciones utilizadas con el comando:

```bash
sysadmin@localhost:~$ ps -ef
UID        PID  PPID  C STIME TTY          TIME CMD                             
root         1     0  0 19:16 pts/0        00:00:00 /sbin??? /init                  
syslog      33     1  0 19:16 ?            00:00:00 /usr/sbin/rsyslogd              
root        37     1  0 19:16 ?            00:00:00 /usr/sbin/cron                  
root        39     1  0 19:16 ?            00:00:00 /usr/sbin/sshd                  
bind        56     1  0 19:16 ?            00:00:00 /usr/sbin/named -u bind         
root        69     1  0 19:16 pts/0        00:00:00 /bin/login -f                   
sysadmin    79    69  0 19:16 pts/0        00:00:00 -bash                           
sysadmin    95    79  0 19:43 pts/0        00:00:00 ps -ef  
```

![Imagen de mujer en una entrevista de trabajo. Contratar talento de código abierto es una alta prioridad para el 97 por ciento de los gerentes de contratación encuestados en 2021.](images/OpenSourceImages-01.png)

«Contratar talento de Open Source (código abierto) es una alta prioridad para el 97% de los gerentes de contratación encuestados en 2021.»

## Administración de paquetes

La administración de paquetes es un sistema mediante el cual un software puede ser instalado, actualizado, consultado o eliminado de un sistema de archivos. En Linux, hay muchos sistemas de gestión de paquetes de software diferentes, pero los dos más populares son Debian y Red Hat. Las máquinas virtuales de este curso utilizan Ubuntu, un derivado de Debian.

En el nivel más bajo del sistema de administración de paquetes Debian se encuentra el comando dpkg. Este comando puede ser complicado para los usuarios más nuevos a Linux. La herramienta Advanced Package Tool, `apt-get`, un programa front-end para la herramienta `dpkg`, facilita la gestión de paquetes.

**Nota:**

Un programa front-end es un programa que los usuarios pueden ver y con el que pueden interactuar.

**Siga leyendo**

Muchos de los comandos de administración de paquetes requieren acceso administrativo, por lo que se precederán del comando `sudo`. Use netlab123 como contraseña cuando se le solicite.

### Instalación de paquetes

Los paquetes de archivos normalmente se instalan por descarga directa desde repositorios ubicados en servidores de Internet. Los repositorios Debian contienen más de 65.000 paquetes de software diferentes. Antes de instalar un paquete, es recomendable actualizar la lista de paquetes disponibles usando el comando `apt-get update`.

Los siguientes comandos pueden tardar unos minutos en ejecutarse.

`sudo apt-get update`

```bash
sysadmin@localhost:~$ sudo apt-get update                                       
[sudo] password for sysadmin:                                                   
Ign file: amd64/ InRelease                                                      
Ign file: amd64/ Release.gpg                                                    
Ign file: amd64/ Release                                                        
Reading package lists... Done
```

Para buscar palabras clave (keyword) dentro de estos paquetes, puede utilizar el comando apt-cache search.

`apt-cache search [keyword]`

La palabra clave que se utiliza debe coincidir con parte del nombre o descripción del paquete que se intenta localizar. Se pueden usar varias palabras clave para especificar aún más la búsqueda; por ejemplo, el término de búsqueda web server proporcionará mejores resultados que web o server.

Para buscar paquetes asociados con la palabra clave cow:

```bash
sysadmin@localhost:~$ apt-cache search cow
cowsay - configurable talking cow
```

Una vez encontrado el paquete (package) que desea instalar, puede utilizar el comando apt-get install para instalarlo:

`sudo apt-get install [package]`

```bash
sysadmin@localhost:~$ sudo apt-get install cowsay
[sudo] password for sysadmin:                
Reading package lists... Done             
Building dependency tree                   
Reading state information... Done
Suggested packages:
  filters                                                                       
The following NEW packages will be installed:
  cowsay
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.                  
Need to get 0 B/18.5 kB of archives.
After this operation, 90.1 kB of additional disk space will be used.
                                                                                
Selecting previously unselected package cowsay.
(Reading database ... 24313 files and directories currently installed.) 
Preparing to unpack .../cowsay_3.03+dfsg1-6_all.deb ...
Unpacking cowsay (3.03+dfsg1-6) ...             
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Setting up cowsay (3.03+dfsg1-6) ...
```

**A tener en cuenta**

¡El comando `cowsay` es una vaca parlante configurable! Use una palabra o frase como argumento:

```bash
sysadmin@localhost:~$ cowsay 'NDG Linux Unhatched'                              
 _____________________                                                          
< NDG Linux Unhatched >                                                         
 ---------------------                                                          
        \   ^__^                                                                
         \  (oo)\_______                                                        
            (__)\       )\/\                                                    
                ||----w |                                                       
                ||     ||
```

Recomendamos incluir el argumento entre comillas simples para evitar que el shell interprete caracteres especiales.

### Actualización de paquetes

El comando `apt-get install` también puede actualizar un paquete, si ese paquete ya está instalado y existe una versión más reciente disponible. Si el paquete aún no está en el sistema, se instalará; si está en el sistema, se actualizará.

La actualización de todos los paquetes del sistema debe realizarse en dos pasos. Primero, actualice la caché de todos los paquetes disponibles utilizando `apt-get update`. En segundo lugar, ejecute el comando `apt-get upgrade` para actualizar todos los paquetes y sus dependencias.

`apt-get update`

`apt-get upgrade`

```bash
sysadmin@localhost:~$ sudo apt-get update 
[sudo] password for sysadmin:
Ign file: amd64/ InRelease
Ign file: amd64/ Release.gpg
Ign file: amd64/ Release
Reading package lists... Done 
sysadmin@localhost:~$ sudo apt-get upgrade
Reading package lists... Done
Building dependency tree
Reading state information... Done
Calculating upgrade... Done
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
```

### Eliminación de paquetes

El comando `apt-get` puede eliminar o purgar un paquete. La diferencia entre los dos es que purgar suprime todos los archivos del paquete, mientras que eliminar suprime todos los archivos del paquete, excepto los archivos de configuración.

Un administrador puede ejecutar el comando `apt-get remove` para eliminar un paquete o el comando `apt-get purge` para purgar un paquete completamente del sistema.

`apt-get remove [package]`

`apt-get purge [package]`

Por ejemplo, para purgar `cowsay` por completo, ejecute el siguiente comando. Escriba Y cuando se le solicite:

```bash
sysadmin@localhost:~$ sudo apt-get purge cowsay 
Reading package lists... Done 
Building dependency tree
Reading state information... Done
The following packages will be REMOVED:
  cowsay*
0 upgraded, 0 newly installed, 1 to remove and 0 not upgraded.
After this operation, 90.1 kB disk space will be freed.
Do you want to continue? [Y/n] y
(Reading database ... 24377 files and directories currently installed.)
Removing cowsay (3.03+dfsg1-6) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
```

## Actualización de contraseñas de usuario

El comando `passwd` se utiliza para actualizar la contraseña de un usuario. Los usuarios solo pueden cambiar sus propias contraseñas, mientras que el usuario root puede actualizar la contraseña para cualquier usuario.

`passwd [OPCIONES] [USUARIO]`

Por ejemplo, ya que hemos iniciado sesión como usuario sysadmin, podemos cambiar la contraseña de esa cuenta. Ejecute el comando `passwd`. Se le pedirá que introduzca la contraseña actual una vez y la contraseña nueva dos veces. Por razones de seguridad, no se muestra ningún resultado mientras se está escribiendo la contraseña. La salida se muestra de la siguiente manera:

```bash
sysadmin@localhost:~$ passwd                                                    
Changing password for sysadmin.                                                 
(current) UNIX password: netlab123                                                       
Enter new UNIX password:                                                       
Retype new UNIX password:                                                       
passwd: password updated successfully
```

Si el usuario desea ver información sobre su contraseña, puede utilizar la opción -S:

```bash
sysadmin@localhost:~$ passwd -S sysadmin                                        
sysadmin P 12/20/2017 0 99999 7 -1
```

Los campos de salida se explican a continuación:

| Campo | Ejemplo | Significado |
|---|---|---|
| Nombre del usuario | sysadmin | El nombre del usuario. |
| Estado de la contraseña | P | P indica que es una contraseña utilizable. L indica que la contraseña está bloqueada. NP indica que no hay contraseña. |
| Fecha de actualización | 03/01/2015 | La fecha en la que la contraseña fue actualizada por última vez. |
| Mínimo | 0 | El número mínimo de días que deben pasar antes de que el usuario pueda cambiar la contraseña actual. |
| Máximo | 99999 | El máximo número de días que restan hasta que expire la contraseña. |
| Aviso | 7 | El número de días precedentes a la expiración de la contraseña para que el usuario reciba el aviso. |
| Inactividad | -1 | El número de días después de la expiración de la contraseña que la cuenta del usuario se mantendrá activa. |

**Siga leyendo**

Cambie a la cuenta root mediante el siguiente comando:

```sysadmin@localhost:~$ su root                                                   
Password:    
root@localhost:~#
```

Use netlab123 como contraseña.

El usuario root puede cambiar la contraseña de cualquier usuario. Si el usuario root desea cambiar la contraseña de sysadmin, ejecutará el siguiente comando:

```bash
root@localhost:~# passwd sysadmin
Enter new UNIX password:        
Retype new UNIX password: 
passwd: password updated successfully
```

**Siga leyendo**

Salga de la cuenta root mediante el comando exit:

```bash
root@localhost:~# exit              
exit
```

## Redirección

Agregar contenido a archivos en Linux puede hacerse de varias maneras. Linux posee algunos editores de texto que pueden usarse para agregar contenido a un archivo. Sin embargo, este método requiere cierta familiaridad con los comandos del editor de texto de Linux.

**Nota**

Los editores de texto de Linux están cubiertos en la siguiente sección de este curso.

En Linux, se puede agregar contenido a un archivo rápidamente usando una función de línea de comandos llamada redirección de entrada/salida (E/S) (input/output; I/O). La redirección E/S (I/O) permite enviar la información de la línea de comandos a archivos, dispositivos y otros comandos. La entrada o salida de un comando se redirige desde su destino predeterminado a una ubicación diferente. La redirección E/S es como una serie de vías de tren, donde se puede habilitar un conmutador para dirigir la salida de un comando a una vía diferente que vaya a otro lugar en el shell. En esta sección, escribiremos a archivos a través de la redirección de la salida de un comando hacia otro archivo.

Cuando se trata de comandos de entrada y salida, existen tres rutas, o “vías”. Estas rutas se denominan descriptores de archivos. El primer descriptor de archivo es la entrada estándar, abreviada como STDIN (standard input). La entrada estándar es la información que el comando recibe y procesa cuando se ejecuta, esencialmente lo que un usuario escribe en el teclado. El segundo descriptor de archivo es la salida estándar, abreviada como STDOUT (standard output). La salida estándar es la información que muestra el comando, la salida del comando. El último descriptor de archivo es el error estándar, abreviado como STDERR (standard error). STDERR, son los mensajes de error generados por comandos que no se ejecutan correctamente. Los siguientes son ejemplos de cómo aparecerán los descriptores de archivos en la terminal:

**Entrada estándar (STDIN)**

`sysadmin@localhost:~$ ls ~/Documents`

**Salida estándar (STDOUT)**

```bash
sysadmin@localhost:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos
```
**Error estándar (STDERR)**

```bash
sysadmin@localhost:~$ ls fakefile 
ls: cannot access fakefile: No such file or directory
```

Esta sección cubrirá uno de los tres descriptores de archivos, STDOUT, y cómo redirigir STDOUT desde donde normalmente aparece en el terminal, a un archivo en el sistema de archivos. Para ejecutar la redirección, simplemente use el símbolo “mayor que” > junto al nombre del archivo:

`[COMANDO] > [ARCHIVO]`

Para demostrar cómo funciona la redirección, usaremos la salida del comando `cat`. Sin redirección, la salida del comando cat se mostrará en el terminal:

**Siga leyendo**

Utilice el siguiente comando para cambiar al directorio Documents:

`sysadmin@localhost:~$ cd ~/Documents`

```bash
sysadmin@localhost:~/Documents$ cat food.txt
Food is good.
```

Ahora utilice el carácter > para redirigir el STDOUT del comando cat food.txt anterior a un nuevo archivo llamado *newfile1.txt*:

`sysadmin@localhost:~/Documents$ cat food.txt > newfile1.txt`

Como puede ver, no se muestra ninguna salida ya que el STDOUT se ha redirigido al archivo newfile1.txt. Compruebe que el STDOUT del comando `cat food.txt` se encuentra en newfile1.txt:

```bash
sysadmin@localhost:~/Documents$ cat newfile1.txt                     
Food is good.
```

Esta función es útil si necesita copiar contenido de un archivo importante a otro archivo para editar su contenido sin modificar el archivo original. Sin embargo, ¿qué sucede si desea agregar un comentario o una nota a un archivo ya existente? Para hacer esto, puede usar el comando `echo`. El comando `echo` se utiliza para imprimir una salida en la terminal:

```bash
sysadmin@localhost:~/Documents$ echo "Hello"           
Hello  
```                                                                 
Imprimir comentarios en la pantalla es una función curiosa, pero el comando echo puede ser más útil cuando se usa con la redirección. Mediante el comando echo, puede agregar contenido al archivo newfile1.txt:

```bash
sysadmin@localhost:~/Documents$ cat newfile1.txt         
Food is good.     
sysadmin@localhost:~/Documents$ echo "I like food." > newfile1.txt
sysadmin@localhost:~/Documents$ cat newfile1.txt             
I like food.
```

Observe que el STDOUT del comando echo ha reemplazado el contenido original del archivo. Esto se debe a que el carácter > sobrescribe cualquier contenido de un archivo existente. Para añadir contenido a un archivo, en lugar de sobrescribir, utilice el símbolo “mayor que” dos veces >>:

```bash
sysadmin@localhost:~/Documents$ echo "This food is good." >> newfile1.txt
sysadmin@localhost:~/Documents$ cat newfile1.txt              
I like food.                                                      
This food is good.
```

**Importante**

Para redirigir la información a un archivo existente, el usuario debe tener permisos de escritura para ese archivo.

## Editor de texto

El principal editor de texto para Linux y UNIX es un programa llamado vi. Si bien hay numerosos editores disponibles para Linux incluyendo desde el pequeño editor nano hasta el editor masivo emacs, el editor vi tiene varias ventajas:

 - El editor `vi` está disponible en todas las distribuciones Linux del mundo. Esto no ocurre con ningún otro editor.

 - El editor `vi` se puede ejecutar tanto en una CLI (interfaz de línea de comandos) como en una GUI (interfaz gráfica de usuario).

 - Aunque se han añadido nuevas características al editor `vi`, las funciones principales han existido durante décadas. Esto significa que si alguien aprendió a usar el editor `vi` en la década de 1970, podrá usar la versión moderna sin ningún problema. Aunque eso pueda parecer trivial, puede que dentro de veinte años no sea tan trivial.

**A tener en cuenta**

La forma correcta de pronunciar el nombre del editor vi es *vi-ay*. Las letras vi representan visual, pero nunca se pronunció de esta manera. En su lugar se pronuncia la letra v (*vi*) seguida de la letra i (*ay*) en inglés.

En realidad, la mayoría de los sistemas Linux no incluyen el editor `vi` original, sino una versión mejorada del mismo conocida como `vim` (vi mejorada) (vi improved). Este hecho puede estar oculto en la mayoría de las distribuciones de Linux. En su mayor parte, `vim` funciona igual que `vi`, pero presenta funciones adicionales. Para los temas que se tratan en este curso, tanto `vi` como `vim` funcionarán perfectamente

Para comenzar a usar `vi`, simplemente escriba el comando seguido del nombre de ruta del archivo que quiere editar o crear:

`sysadmin@localhost:~$ vi newfile.txt`

Los tres modos utilizados en `vi` son los siguientes: modo de comando, modo de inserción y modo ex.

### Modo de comando: Movimiento

Inicialmente, el programa empieza en modo de comando. El modo de comando se utiliza para escribir comandos, como los utilizados para desplazarse por un documento, manipular texto o acceder a los otros dos modos. Para volver al modo de comando en cualquier momento, presione la tecla **Esc**.

Una vez haya agregado texto a un documento, deberá presionar la tecla **Esc** para volver al modo de comando y realizar acciones como mover el cursor. Esto parece que sea mucho trabajo, pero recuerde que `vi` funciona en un entorno terminal en el cual un mouse es inservible.

Los comandos de movimiento en `vi` tienen dos aspectos, el movimiento (*motion*) y un prefijo numérico opcional (*count*) que indica cuántas veces se debe repetir ese movimiento. El formato general es el siguiente:

`[número] movimento`

En la siguiente tabla se resumen las teclas de movimiento disponibles:

| Movimiento | Resultado |
|---|---|
| h | Un carácter a la izquierda |
| j | A la línea siguiente |
| k | A la línea anterior |
| l | Un carácter a la derecha |
| w | Una palabra adelante |
| b | Una palabra hacia atrás |
| ^ | Al principio de la línea |
| $ | Al final de la línea |

**Nota**

En la actualización `vim` también es posible usar las teclas de flecha ← ↓ ↑ → en lugar de los caracteres h j k l respectivamente.

Estos movimientos se pueden anteponer con un número para indicar cuántas veces se debe realizar el movimiento. Por ejemplo, 5h moverá el cursor cinco caracteres a la izquierda y 3w moverá el cursor tres palabras a la derecha.

Para mover el cursor a un número de línea específico, escriba ese número de línea seguido del carácter G. Por ejemplo, para llegar a la quinta línea del archivo, escriba 5G. Puede usar 1G o gg para moverse a la primera línea del archivo, mientras que una G única le llevará a la última línea. Para averiguar en qué línea se encuentra el cursor, utilice **CTRL+G**.

### Modo de comando: Acciones

La convención estándar para editar contenido con procesadores de texto es usando copiar, cortar y pegar. El programa vi no tiene ninguno de estos. En su lugar, vi utiliza los tres comandos siguientes:

| Estándar | Vi | Significado |
|---|---|---|
| cortar | d	eliminar (delete) |
| copiar | y | sacar (yank) |
| pegar | P o p | poner (put) |

Los movimientos aprendidos en la página anterior se utilizan para especificar dónde se llevará a cabo la acción, comenzando siempre con la ubicación actual del cursor. Cualquiera de los siguientes formatos generales es aceptable para comandos de acción:

`acción [número] movimento`
`[número] acción movimento`

### Eliminar

Eliminar (*delete)* suprime el texto indicado de la página y lo guarda en el búfer, siendo el búfer el equivalente al “portapapeles” (*clipboard*) utilizado en Windows o Mac OSX. En la siguiente tabla se proporcionan algunos ejemplos de uso comunes:

| Acción | Resultado |
|---|---|
| dd | Elimina la línea actual |
| 3dd | Elimina las tres líneas siguientes |
| dw | Elimina la palabra actual |
| d3w | Elimina las tres palabras siguientes |
| d4h | Elimina cuatro caracteres hacia la izquierda |

### Cambiar

La función cambiar (change) es muy similar a la de eliminar; el texto se elimina y se guarda en el búfer. Sin embargo, el programa cambia a modo de inserción y permite la introducción de cambios inmediatos en el texto. En la siguiente tabla se proporcionan algunos ejemplos de uso comunes:

| Acción | Resultado |
|---|---|
| cc | Cambiar la línea actual | 
| cw | Cambiar la palabra actual |
| c3w | Cambiar las tres palabras siguientess |
| c5h | Cambiar cinco caracteres hacia la izquierda |

### Sacar

Sacar (*yank*) coloca el contenido en el búfer sin eliminarlo. En la siguiente tabla se proporcionan algunos ejemplos de uso comunes:

| Acción | Resultado |
|---|---|
| yy | Sacar la línea actual |
| 3yy | Sacar las tres líneas siguientes |
| yw | Sacar la palabra actual |
| y$ | Sacar el fragmento desde el cursor hasta el final de la línea actual |

### Poner

Poner (put) coloca el texto guardado en el búfer antes o después de la posición del cursor. Tenga en cuenta que estas son las dos únicas opciones, poner no utiliza movimientos como los comandos de acción anteriores.

Acción	Resultado
p	Poner o pegar después del cursor
P	Poner antes del cursor

### Buscar en vi

Otra función estándar que ofrecen los procesadores de texto es la función de búsqueda (find). A menudo, las personas usan **CTRL+F** o miran en el menú de edición. El programa vi utiliza la búsqueda. La función de búsqueda es más potente que la función find porque admite patrones de texto literales y expresiones regulares.

Para buscar hacia adelante desde la posición actual del cursor, use la / para iniciar la búsqueda, escriba un término de búsqueda y, a continuación, presione la tecla **Enter** para iniciar la búsqueda. El cursor se moverá al primer resultado que coincida con su término de búsqueda.

Para proceder al siguiente resultado coincidente usando el mismo patrón, presione la tecla n. Para volver al resultado anterior, presione la tecla N. Si se alcanza el final o el comienzo del documento, la búsqueda se ajustará automáticamente para continuar con el resto del documento.

Para empezar a buscar desde la posición del cursor hacia atrás, empiece por escribir ?, entonces escriba el patrón de búsqueda y presione la tecla Enter.

### Modo Insertar

El modo Insertar se utiliza para agregar texto a un documento. Hay algunas maneras de entrar en el modo de inserción desde el modo de comando, cada una diferenciada por donde comienza la inserción de texto. La siguiente tabla presenta los más comunes:

| Entrada | Función |
|---|---|
| a | Comenzar a insertar justo después del cursor |
| A | Comenzar a insertar al final de la línea |
| I | Comenzar a insertar justo antes del cursor |
| I | Comenzar a insertar al principio de la línea |
| o | Comenzar a insertar en una nueva línea después del cursor |
| O | Comenzar a insertar en una nueva línea antes del cursor |

### Modo Ex

Originalmente, el editor `vi` se llamaba editor `ex`. El nombre `vi` era la abreviatura del comando visual en el editor `ex` que cambiaba el editor al modo “visual”.

En el modo normal original, el editor `ex` sólo permitía a los usuarios ver y modificar una línea cada vez. En el modo visual, los usuarios podían ver la mayor parte del documento que podía caber en la pantalla. Dado que la mayoría de los usuarios preferían el modo visual al modo de edición por línea, el archivo de programa `ex `se vinculó a un archivo `vi`. De este modo los usuarios podían iniciar `ex` directamente en modo visual al ejecutar el enlace `vi`.

Eventualmente, el archivo de programa fue renombrado `vi` y el editor `ex` se convirtió en un enlace que apuntaba al editor `vi`.

Cuando se utiliza el modo ex del editor `vi`, es posible ver o cambiar su configuración, así como ejecutar comandos de archivo como abrir, guardar o cancelar cambios en un documento. Para acceder al modo ex, escriba el carácter : en el modo de comando. En la tabla siguiente se enumeran algunas acciones comunes realizadas en modo ex:

| Entrada | Función |
|---|---|
| :w | Escribir el documento actual al sistema de archivos |
| :w nombre_del_archivo | Guardar una copia del documento actual bajo el nombre nombre_del_archivo |
| :w!	Forzar escritura al documento actual |
| :1 | Ir a la primera línea (o otra línea indicada por el número) |
| :e | nombre_del_archivo	Abrir nombre_del_archivo |
| :q | Suspender (salir) (quit) si no se han realizado cambios al documento |
| :q! | Suspender sin guardar los cambios realizados al documento |

Un análisis rápido de la tabla anterior revela que cuando un signo de exclamación, ! , se agrega a un comando, se intentará forzar la operación. Por ejemplo, imagine que realiza cambios a un archivo en el editor vi y luego intenta salir usando :q, solo para descubrir que el comando falla. En este caso, el editor vi no quiere salir del documento sin guardar los cambios realizados, pero usted puede forzar la salida con el comando ex :q!.

**A tener en cuenta**

Aunque el modo ex ofrece varias maneras de guardar y salir, también está disponible el comando ZZ; éste es el equivalente a :wq. Hay muchas más funciones que se solapan entre el modo ex y el modo de comando. Por ejemplo, el modo ex se puede utilizar para navegar a cualquier línea del documento escribiendo : seguido del número de línea, mientras que G se puede utilizar en modo de comando como se ha demostrado anteriormente.

**Siga leyendo**

Si tiene un archivo de texto abierto, salga ejecutando el comando :q!. Esto lo cerrará sin guardar cambios.

```bash
~
~
:q!_
```

## Cómo seguir avanzando

Esperamos que haya disfrutado de esta breve introducción al mundo de Linux. El contenido de este curso se alinea con los conocimientos de Linux cubiertos por los objetivos del examen LPI Linux Essentials. ¡Pero hay mucho más! Avance en su carrera profesional adquiriendo más conocimientos sobre Linux con una certificación.

### NDG Linux Essentials

Si está interesado en ampliar sus conocimientos sobre Linux, Cisco Networking Academy ofrece tres cursos de Linux. [NDG Linux Essentials](https://www.netacad.com/courses/os-it/ndg-linux-essentials) es perfecto para principiantes que buscan comprender conceptos básicos. La [NDG Linux Series](https://www.netacad.com/courses/os-it/ndg-linux-I), también está dirigida a principiantes, pero presenta el contenido con más profundidad y rigor.

![NDG Linux Essentials. Learn the fundamentals of the Linux operating system and command line and basic open source concepts. Image of students looking at monitors.](images/linux_essentials.png)

«*NDG Linux Essentials. Adquiera conocimientos fundamentales sobre el sistema operativo Linux, la línea de comandos y conceptos básicos sobre sistemas de código abierto.*»

El curso NDG Linux Essentials está diseñado para prepararlo para el certificado de desarrollo profesional Linux Essentials Professional Development Certificate del Linux Professional Institute, que valida que usted posee una comprensión demostrada de los conceptos siguientes:

 - FOSS, las diferentes comunidades y licencias
 - Conocimientos sobre aplicaciones de código abierto en el lugar de trabajo y cómo se comparan a aplicaciones equivalentes de código cerrado
 - Conceptos básicos sobre hardware, procesos, programas y los componentes del Sistema Operativo Linux
 - Cómo usar la línea de comando y trabajar con archivos
 - Cómo crear y restaurar copias de seguridad y archivos comprimidos
 - Seguridad del sistema, usuarios/grupos y permisos para directorios públicos y privados
 - Cómo crear y ejecutar scripts simples

Para obtener el certificado de desarrollo profesional de Linux Essentials debe completar el curso Linux Essentials (LPI-010) que cubre:

 - La comunidad Linux y una carrera profesional trabajando con código abierto
 - Saber moverse en el entorno Linux
 - El poder de la línea de comando
 - El sistema operativo Linux
 - Seguridad y permisos de archivos
El certificado de desarrollo profesional de Linux Essentials es el comienzo de su camino hacia convertirse en un profesional certificado Linux. Puede encontrar información sobre las certificaciones del Linux Professional Institute en [http://www.lpi.org](https://content.netdevgroup.com/contents/unhatched/bCdL9YLvTR/).

No se preocupe si tiene poca o ninguna experiencia con Linux. Este curso es el punto de partida perfecto. Está diseñado para enseñarle todos los conceptos partiendo de cero. Sin embargo, si encuentra que este material no es lo suficientemente estimulante, considere comenzar con NDG Introduction to Linux I, un curso introductorio más riguroso.

### [NDG Linux Series](https://www.netacad.com/courses/ndg-intro-linux/)

![NDG Linux I and II. Learn Linux system administration skills and prepare for LPI LPIC-1 or CompTIA Linux+ powered by LPI certification. Image of two male students looking at a monitor.](images/NDG_Introduction_to_Linux_Course___Cisco_NetAcad.png)
«*Aprenda sobre la administración de sistemas Linux y prepárese para las certificaciones LPI LPIC-1 o CompTIA Linux+. Inscríbase ahora.*»

La serie NDG Linux está diseñada para prepararle para la certificación de nivel 1 del Linux Professional Institute (LPIC-1). LPIC-1 es una certificación Linux Server Professional para administradores de Linux que confirma que usted está capacitado para realizar las siguientes tareas:

 - Trabajar con la línea de comandos Linux
 - Completar tareas de mantenimiento simples: asistir a usuarios, añadir usuarios a sistemas más grandes, realizar copias de seguridad (backups) y restaurar, cerrar y reiniciar el sistema.
 - Instalar y configurar una estación de trabajo (incluyendo X) y conectarla a la LAN, o un PC a internet.

Para obtener la certificación LPIC-1 debe aprobar los exámenes 101 y 102. NDG Introduction to Linux I está diseñado para prepararle para el examen 101, que abarca:

 - Arquitectura del Sistema
 - Instalación de Linux y Administración de Paquetes
 - GNU y Comandos Unix
 - Dispositivos, Sistemas de Archivos Linux, Estándares de Jerarquía en el Sistema de Archivos

NDG Introduction to Linux II se alinea con los objetivos del examen 102, que abarcan:

 - Shells, Scripts y Administración de Datos
 - Interfaces y Escritorios (Desktops)
 - Tareas Administrativas
 - Servicios de Sistema Esenciales
 - Fundamentos sobre Gestión de Redes
 - Seguridad
La certificación LPIC-1 es la primera de tres certificaciones profesionales LPI. Información sobre todas las certificaciones del Linux Professional Institute está disponible en http://www.lpi.org.

###[IT Essentials](https://www.netacad.com/courses/it-essentials/)

Para obtener más información sobre conceptos fundamentales de informática y carreras profesionales y trabajos de iniciación en TI, consulte el resto de [IT Essentials](https://www.netacad.com/courses/it-essentials/).

![IT Essentials. Learn how to build and set up a computer and connect it securely to a network, your first step to an IT career. Students looking at interior of a computer.](images/it_essentials.png)

«*IT Essentials. Aprenda a configurar una computadora y conectarla de manera segura a la red. Sus primeros pasos hacia una carrera en TI.*»

IT Essentials cubre los conceptos fundamentales de informática y las posibles carreras y empleos de TI de nivel básico. El plan de estudios de IT Essentials incluye horas de prácticas que proporcionan experiencia real. Además, las herramientas virtuales ayudan a perfeccionar su capacidad para resolver problemas y practicar lo que aprende.

 - Obtener conocimientos prácticos sobre el funcionamiento de las computadoras
 - Desarrollar pensamiento crítico y capacidad para resolver problemas complejos mediante clases prácticas y herramientas de aprendizaje virtual
 - Emplear conceptos y procedimientos para instalar y actualizar hardware y software y solucionar problemas de sistemas
 - Practicar y aplicar lo aprendido sobre equipos reales y utilizando la herramienta de simulación Cisco Packet Tracer
 - Obtener feedback inmediato sobre su trabajo mediante cuestionarios y tests incorporados
 - Conectarse a la comunidad global Cisco Networking Academy

![Gráfico de encuesta de los aspectos más destacados del trabajo en código abierto. El código abierto lo ejecuta todo. Más oportunidades para trabajar de forma remota. Modelo de desarrollo colaborativo. El 58% de los profesionales informa que siguió una carrera de código abierto porque la tecnología moderna se ejecuta en código abierto. Informe de trabajo de código abierto 2021 - Linux Foundation Research.](images/Open_Source_Images-02.png)
«*Lo más destacado sobre trabajar con código abierto. El código abierto lo ejecuta todo. Más oportunidades para trabajar de forma remota. Modelo de desarrollo colaborativo. El 58% de los profesionales informa que siguió una carrera de código abierto porque la tecnología moderna se ejecuta en código abierto.*»

## Linux para Cisco Certified CyberOps Associate

¡Enhorabuena, ha terminado este breve curso introductorio de Linux! Acaba de aprender muchos conceptos de Linux que le ayudarán a avanzar su carrera en TI. Hemos destacado que Linux está en todas partes. También hemos hecho hincapié en que aprender Linux es beneficioso para una amplia variedad de carreras tecnológicas. Puede continuar sus estudios de TI en una variedad de áreas, incluyendo redes, IoT y en una de las especialidades de TI con más demanda actualmente, la ciberseguridad.

Uno de los retos más importantes al que nos enfrentamos actualmente en nuestro universo digital es la ciberseguridad. Hay una cantidad creciente de dispositivos inteligentes que se pueden conectar a redes, cosa que es muy conveniente para los usuarios que desean permanecer conectados. Sin embargo, esto también puede resultar en redes vulnerables a personas y organizaciones que intentan obtener acceso malintencionado a tales dispositivos y redes. Como resultado, el campo de la ciberseguridad está creciendo y en los últimos años la formación de profesionales en ciberseguridad se ha convertido en una prioridad para las instituciones de tecnología de la información.

Cisco Network Academy ha desarrollado un programa de certificación para aquellas personas interesadas en una trayectoria profesional en ciberseguridad. La certificación Cisco Certified CyberOps Associate está diseñada para proporcionar conocimientos sobre las tareas específicas necesarias para monitorear los sistemas de información. Con esto en mente, si usted está comenzando sus estudios de TI, o si está interesado en explorar carreras en TI, vale la pena señalar que existe una demanda de profesionales formados en Cisco Certified CyberOps Associate.

![Sea el arma de seguridad cibernética de TI de su empresa. Cursos NDG Linux - la manera inteligente de prepararse para Cisco Certified CyberOps Associate.](images/Cisco_CCNA_Social_Posts_V2_Cisco-CCNA-4.jpg)
«*Sea el arma de seguridad cibernética de TI de su empresa. Cursos NDG Linux - la manera inteligente de prepararse para Cisco Certified CyberOps Associate.*»

La mejor parte es que los conocimientos básicos de Linux cubiertos en este curso son aplicables, junto con aprendizaje adicional, a una carrera de formación Cisco Certified CyberOps Associate. Aprender conceptos básicos de Linux puede mejorar su capacidad para realizar tareas específicas en el curso Cisco Certified CyberOps Associate, así como comprender los conceptos y objetivos que se enseñan en Cisco Certified CyberOps Associate.

Tenga en cuenta que mientras aprenden a monitorear y detectar amenazas, los estudiantes de Cisco Certified CyberOps Associate también deben aprender cómo funcionan los diferentes sistemas operativos y cómo resolver problemas y analizar tales sistemas operativos. Dado que Linux se utiliza en dispositivos móviles, servidores y máquinas cliente, resulta muy útil saber navegar por el sistema operativo Linux. Por esta razón, muchos de los objetivos de aprendizaje del curso Cisco Certified CyberOps Associate se refieren al análisis de servidores que ejecutan Linux.

Una buena comprensión de Linux permite que los estudiantes de ciberseguridad puedan analizar pericialmente el sistema de archivos Linux, monitorear servidores Linux, así como máquinas cliente, dispositivos y otras tecnologías que ejecutan Linux. Algunos de los comandos y herramientas cubiertos en este curso son requisitos básicos para las aptitudes mencionadas anteriormente. La siguiente tabla muestra los conceptos que ha aprendido en este curso que serán beneficiosos para una formación futura Cisco Certified CyberOps Associate:

| Objetivos de Aprendizaje de Linux Unhatched	| Aptitudes Cisco Certified CyberOps Associate |
|---|---|
Listar Archivos
Visualizar Archivos
Filtrar Entradas
Patrones Básicos
Redireccionamiento
| Analizar Archivos |
Visualizar Archivos
Copiar Archivos
Redireccionamiento
Editores de Texto
Permisos de Archivos
Cambios de Propietario de Archivos
Manipulación de Archivos
Editores de Texto
Modificar y Crear Archivos de Configuración
Permisos de Archivos
Permisos de Usuario y de Grupo
Acceso Administrativo
Actualizar Contraseñas de Usuario
Permisos
Configuración de Redes
Configuración de Redes
Con el presente curso usted aprendió a realizar operaciones básicas con Linux, incluyendo tareas administrativas y aquellas relacionadas con la seguridad. Los expertos en ciberseguridad deben saber cómo realizar estas tareas en una variedad de sistemas operativos, Windows, MacOS y Linux incluidos. Los cursos NDG Linux están diseñados para enseñarle una variedad de comandos, términos y utilidades que le ayudarán a prepararse para una carrera profesional en ciberseguridad. Vea a continuación algunos de los comandos de Linux necesarios para Cisco Certified CyberOps Associate:

[Linux commands for Cisco Certified CyberOps Associate. Commands include apt, cat, cd, ls, sudo, tail, ssh, and more!](images/Unhatched_ccna_commands.png)
«*Comandos Linux para Cisco Certified CyberOps Associate. Cursos NDG Linux - la manera inteligente de prepararse paraCisco Certified CyberOps Associate.*»

Para obtener más información sobre Linux y los comandos y utilidades necesarios para crear una base de conocimientos fundamentales sobre Linux que le ayuden a ir más lejos en la carrera de formación Cisco Certified CyberOps Associate, eche un vistazo a otros cursos NDG Linux. Para obtener más información sobre el curso Cisco Certified CyberOps Associate haga clic aquí.