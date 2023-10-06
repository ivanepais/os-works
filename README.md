# os-works

|| OS 
	
	Es una interfaz entre el usuario y el hardware de computadora. 

	Es un software que realiza todas las tareas básicas como la administración de archivos, administración de memoria, administración de procesos, manejo de entrada y salida y control de dispositivos periféricos como unidades de disco e impresoras.

	Permite que las aplicaciones interactúen con el hardware de una computadora. 

	El software que contiene los componentes principales del sistema operativo se llama kernel.

	Los sistemas operativos de escritorio más populares son Windows, MacOS y Linux.

	Los sistemas operativos de móviles más populares de escritorio son Android y iOS. 

	Hoy en día, los sistemas operativos se encuentran en casi todos los dispositivos, como teléfonos móviles, computadoras personales, computadoras centrales, automóviles, televisores. , juguetes, etc.



|| Arquitectura de un Sistema Operativo
	
	Hardware: 

		CPU: 


		RAM: 


		I/O 


	Software: 

		Sistema Operativo: 


		Software del Sistema: 


		Applicaciones para el usuario: 


	La idea es que los usuarios de una computadora interactuen con el sistema operativo para que sea facil de usar. 

	El sistema operativo es el que se encargará de interactuar con el hardware de la computadora para resolver tareas complejas.



|| Generaciones de Sistemas Operativos 
	
	Los sistemas operativos han ido evolucionando a lo largo de los años. 

	Podemos clasificar esta evaluación en función de las diferentes generaciones:
	

	Generación 0:

		Se utiliza para referirse al periodo de desarrollo de la informática cuando Charles Babbage inventó la Máquina Analítica y más tarde John Atanasoff creó un ordenador en 1940. 

		La tecnología de los componentes hardware de este periodo eran los tubos electrónicos de vacío. 

		No existía ningún sistema operativo para esta generación de ordenadores y los programas se escribían en lenguaje máquina. 

		Los ordenadores de esta generación eran ineficaces y dependían de las distintas competencias del programador individual como operador.


	Primera Generación (1951-1956):

		La primera generación marcó el comienzo de la informática comercial, 

		incluyendo la introducción del UNIVAC I de Eckert y Mauchly a principios de 1951, y un poco más tarde, el IBM 701.

		El funcionamiento del sistema se llevó a cabo con la ayuda de operadores expertos y sin la ventaja de un sistema operativo durante un tiempo, aunque los programas empezaron a escribirse en lenguajes de alto nivel y orientados a procedimientos, con lo que se amplió la rutina del operador. 

		Más tarde se desarrolló el sistema operativo monoprogramado, que eliminaba parte de la intervención humana en la ejecución del trabajo y proporcionaba a los programadores una serie de funciones deseables.

		Estos sistemas seguían funcionando bajo el control de un operador humano que solía seguir una serie de pasos para ejecutar un programa.

		El lenguaje de programación FORTRAN fue desarrollado por John W. Backus en 1956.


	Segunda generación (1956-1964):

		La segunda generación de hardware informático se caracterizó sobre todo porque los transistores sustituyeron a los tubos de vacío como tecnología de componentes de hardware. 

		El primer sistema operativo GMOS, fue desarrollado por IBM Computer. 

		GMOS se basaba en un sistema de procesamiento por lotes de flujo único, ya que recopila todos los trabajos similares en grupos o lotes y, a continuación, envía los trabajos al sistema operativo mediante una tarjeta perforada para completar todos los trabajos de una máquina. 

		El sistema operativo se limpia después de completar un trabajo y luego continúa leyendo e inicia el siguiente trabajo en la tarjeta perforada.

		Los investigadores empezaron a experimentar con la multiprogramación y el multiprocesamiento en sus servicios informáticos denominados sistema de tiempo compartido. 

		Un ejemplo notable es el Sistema de Tiempo Compartido Compatible (CTSS), desarrollado en el MIT a principios de los años sesenta.


	Tercera generación (1964-1979):

		La tercera generación comenzó oficialmente en abril de 1964 con el anuncio por parte de IBM de su familia de ordenadores System/360.

		La tecnología de hardware comenzó a utilizar circuitos integrados (IC), lo que supuso ventajas significativas tanto en velocidad como en economía.

		El desarrollo de sistemas operativos continuó con la introducción y adopción generalizada de la multiprogramación.

		Continuó desarrollándose la idea de aprovechar al máximo las capacidades de E/S de los canales de datos del ordenador.

		Otro progreso que lleva al desarrollo de los ordenadores personales de cuarta generación es el nuevo desarrollo de los miniordenadores con el DEC PDP-1.

		La tercera generación fue una época apasionante, sin duda, para el desarrollo tanto del hardware informático como del sistema operativo que lo acompañaba.


	Cuarta generación (1979 - Actualidad):

		La cuarta generación se caracteriza por la aparición del ordenador personal y la estación de trabajo. 

		La tecnología de componentes de la tercera generación fue sustituida por la integración a muy gran escala -VLSI- (proceso de crear un circuito integrado compuesto por millones de transistores en un único chip.). 

		Muchos de los sistemas operativos que utilizamos hoy en día, como Windows, Linux, MacOS, etc., se desarrollaron en la cuarta generación.

		A continuación se enumeran algunas de las funciones más importantes de un sistema operativo:

	    Gestión de la memoria.
	    Gestión del procesador.
	    Gestión de dispositivos.
	    Gestión de archivos.
	    Gestión de redes.
	    Seguridad.
	    Control del rendimiento del sistema.
	    Contabilidad de trabajos.
	    Ayudas para la detección de errores
	    Coordinación entre otros programas y usuarios.


|| Gestión de la memoria RAM (Random Acces Memory)

	Se refiere a la gestión de la memoria primaria o memoria principal. 

	La memoria principal es una gran matriz de palabras o bytes en la que cada palabra o byte tiene su propia dirección.

	La memoria principal proporciona un almacenamiento rápido al que la CPU puede acceder directamente. 

	Para que un programa se ejecute, debe estar en la memoria principal. 

	Un sistema operativo realiza las siguientes actividades para la gestión de la memoria:

		Realiza un seguimiento de la memoria principal, es decir, qué parte de ella está en uso por quién, qué parte no está en uso.

    	En multiprogramación, el SO decide qué proceso obtendrá memoria, cuándo y cuánta.

    	Asigna la memoria cuando un proceso se lo pide.

   		Desasigna la memoria cuando un proceso ya no la necesita o ha finalizado.



|| Gestión del procesador CPU (Central Processing Unit)

	En un entorno multiprogramación, el sistema operativo decide qué proceso obtiene el procesador, cuándo y durante cuánto tiempo. 

	Esta función se denomina programación de procesos. 

	Un sistema operativo realiza las siguientes actividades para la gestión del procesador

	    Realiza un seguimiento del procesador y del estado del proceso. 

	    El programa responsable de esta tarea se conoce como controlador de tráfico.

	    Asigna el procesador (CPU) a un proceso.

	    Desasigna el procesador cuando un proceso ya no es necesario.
	


|| Gestión de dispositivos (Devices)

	Un Sistema Operativo gestiona la comunicación de dispositivos a través de sus respectivos drivers. 

	Realiza las siguientes actividades para la gestión de dispositivos

	    Mantiene un registro de todos los dispositivos. 

	    El programa responsable de esta tarea se conoce como controlador de E/S o I/O (entrada y salida o input and output).

	    Decide qué proceso obtiene el dispositivo, cuándo y durante cuánto tiempo.

	    Asigna el dispositivo de manera eficiente.

	    Desasigna dispositivos.



|| Gestión de archivos (Files)

	Un sistema de archivos se organiza normalmente en directorios para facilitar la navegación y el uso.

	Estos directorios pueden contener ficheros y otras direcciones.

	Un Sistema Operativo realiza las siguientes actividades para la gestión de archivos.

	    Realiza un seguimiento de la información, ubicación, usos, estado, etc. 

	    Las instalaciones colectivas se conocen a menudo como sistema de archivos.

	    Decide quién obtiene los recursos.

	    Asigna los recursos.

	    Desasigna los recursos.



|| Otras actividades importantes

	A continuación se enumeran algunas de las actividades importantes que realiza un sistema operativo.

	Seguridad:

		Mediante contraseñas y otras técnicas similares, impide el acceso no autorizado a programas y datos.


	Control del rendimiento del sistema:

		Registro de los retrasos entre la solicitud de un servicio y la respuesta del sistema.


	Contabilidad de trabajos: 

		Llevar un registro del tiempo y los recursos utilizados por los distintos trabajos y usuarios.


	Ayudas para la detección de errores:

		Producción de volcados, trazas, mensajes de error y otras ayudas para la depuración y detección de errores.


	Coordinación entre otros programas y usuarios:

		Coordinación y asignación de compiladores, intérpretes, ensambladores y otros programas a los distintos usuarios de los sistemas informáticos.



|| Componentes del Sistema Operativo en detalle
	
	Hay varios componentes de un Sistema Operativo para realizar tareas bien definidas. 

	Aunque la mayoría de los sistemas operativos difieren en su estructura, lógicamente tienen componentes similares. 

	Cada componente debe ser una parte bien definida de un sistema que describa adecuadamente las funciones, entradas y salidas.

	Existen los siguientes 8 componentes de un Sistema Operativo:

	    Gestión de Procesos
	    Gestión de dispositivos de E/S
	    Gestión de archivos
	    Gestión de red
	    Gestión de la memoria principal
	    Gestión del almacenamiento secundario
	    Gestión de la seguridad
	    Sistema de interpretación de comandos


	Gestión de procesos:

		Un proceso es un programa o una fracción de un programa que se carga en la memoria principal. 

		Un proceso necesita ciertos recursos, como tiempo de CPU, memoria, archivos y dispositivos de E/S para llevar a cabo su tarea. 

		El componente de gestión de procesos gestiona los múltiples procesos que se ejecutan simultáneamente en el sistema operativo.

    	Un programa en estado de ejecución se denomina proceso.

		El sistema operativo es responsable de las siguientes actividades relacionadas con la gestión de procesos:

		    Crear, cargar, ejecutar, suspender, reanudar y terminar procesos.

		    Conmuta el sistema entre varios procesos en la memoria principal.

		    Proporciona mecanismos de comunicación para que los procesos puedan comunicarse entre sí.

		    Proporciona mecanismos de sincronización para controlar el acceso concurrente a los datos compartidos para mantener la coherencia de los datos compartidos.

		    Asigna/desasigna recursos adecuadamente para prevenir o evitar situaciones de bloqueo.


	Gestión de dispositivos de E/S:

		Uno de los propósitos de un sistema operativo es ocultar al usuario las peculiaridades de dispositivos hardware específicos.

		La Gestión de Dispositivos de E/S proporciona un nivel abstracto de los dispositivos H/W y oculta los detalles a las aplicaciones para garantizar el uso adecuado de los dispositivos, evitar errores y proporcionar a los usuarios un entorno de programación cómodo y eficiente.

		Las siguientes son las tareas del componente I/O Device Management:

		    Ocultar los detalles de los dispositivos H/W.

		    Gestionar la memoria principal de los dispositivos mediante caché, buffer y spooling.

		    Mantener y proporcionar controladores personalizados para cada dispositivo.


	Gestión de archivos:

		La gestión de archivos es uno de los servicios más visibles de un sistema operativo. 

		Los ordenadores pueden almacenar información en diferentes formas físicas; la cinta magnética, el disco y el tambor son las formas más comunes.

		Un fichero se define como un conjunto de información correlacionada y es definido por el creador del fichero. 

		En su mayoría, los archivos representan datos, formas fuente y objeto, y programas. 

		Los ficheros de datos pueden ser de cualquier tipo como alfabéticos, numéricos y alfanuméricos.

		    Un fichero es una secuencia de bits, bytes, líneas o registros cuyo significado es definido por su creador y usuario.

		El sistema operativo implementa el concepto abstracto de fichero mediante la gestión de dispositivos de almacenamiento masivo, como tipos y discos. 

		Además, los archivos se organizan normalmente en directorios para facilitar su uso. 

		Estos directorios pueden contener archivos y otros directorios, etc.

		El sistema operativo es responsable de las siguientes actividades relacionadas con la gestión de archivos:

		    Creación y borrado de ficheros
		    Creación y eliminación de directorios.

		    El soporte de primitivas para manipular ficheros y directorios.

		    Asignación de archivos al almacenamiento secundario
		    Copia de seguridad de archivos en medios de almacenamiento estables (no volátiles).


	Gestión de redes:

		La definición de gestión de redes suele ser amplia, ya que la gestión de redes implica varios componentes diferentes. 

		La gestión de redes es el proceso de gestionar y administrar una red informática. 

		Una red informática es un conjunto de varios tipos de ordenadores conectados entre sí.

		La gestión de redes comprende el análisis de fallos, el mantenimiento de la calidad del servicio, el aprovisionamiento de redes y la gestión del rendimiento.

		    La gestión de redes es el proceso de mantener la red en buen estado para que la comunicación entre los distintos ordenadores sea eficaz.

		A continuación se describen las características de la gestión de redes:

		    Administración de redes.

		    Mantenimiento de la red.

		    Funcionamiento de la red.

		    Aprovisionamiento de la red
		    Seguridad de la red.


	Gestión de la memoria principal:

		La memoria es una gran matriz de palabras o bytes, cada uno con su propia dirección. 

		Es un repositorio de datos de acceso rápido compartido por la CPU y los dispositivos de E/S.

		La memoria principal es un dispositivo de almacenamiento volátil, lo que significa que pierde su contenido en caso de fallo del sistema o en cuanto éste se apaga.

		    La principal motivación detrás de la Gestión de Memoria es maximizar la utilización de la memoria en el sistema informático.

		El sistema operativo es responsable de las siguientes actividades relacionadas con la gestión de memoria:

		    Llevar un registro de qué partes de la memoria están siendo utilizadas actualmente y por quién.

		    Decidir qué procesos cargar cuando haya espacio de memoria disponible.
		    d
		    Asignar y desasignar espacio de memoria según sea necesario.


	Gestión del almacenamiento secundario:

		El objetivo principal de un sistema informático es ejecutar programas. 

		Estos programas, junto con los datos a los que acceden, deben estar en la memoria principal durante la ejecución. 

		Dado que la memoria principal es demasiado pequeña para alojar permanentemente todos los datos y programas, el sistema informático debe proporcionar almacenamiento secundario para respaldar la memoria principal.

		La mayoría de los sistemas informáticos modernos utilizan discos como principal medio de almacenamiento en línea, tanto para los programas como para los datos. 

		La mayoría de los programas, como compiladores, ensambladores, rutinas de clasificación, editores, formateadores, etc., se almacenan en el disco hasta que se cargan en la memoria, y luego utilizan el disco como origen y destino de su procesamiento.

		El sistema operativo es responsable de las siguientes actividades relacionadas con la gestión del disco:

		    Gestión del espacio libre.

		    Asignación de almacenamiento.

		    Programación del disco.		    

	Gestión de la seguridad:

		El sistema operativo es el principal responsable de todas las tareas y actividades que tienen lugar en el sistema informático.

		Los distintos procesos de un sistema operativo deben estar protegidos de las actividades de los demás. 

		Para ello, se pueden utilizar varios mecanismos para garantizar que los archivos, el segmento de memoria, la cpu y otros recursos sólo puedan ser utilizados por aquellos procesos que hayan obtenido la autorización adecuada del sistema operativo.

		    La gestión de la seguridad se refiere a un mecanismo para controlar el acceso de programas, procesos o usuarios a los recursos definidos por un ordenador controles que deben imponerse, junto con algunos medios de aplicación.

		Por ejemplo, el hardware de direccionamiento de memoria garantiza que un proceso sólo pueda ejecutarse dentro de su propio espacio de direcciones. 

		El temporizador garantiza que ningún proceso pueda hacerse con el control de la CPU sin renunciar a él. 

		Por último, no se permite a ningún proceso realizar su propia E/S, para proteger la integridad de los distintos dispositivos periféricos.


	Sistema de intérprete de comandos:

		Uno de los componentes más importantes de un sistema operativo es su intérprete de comandos. 

		El intérprete de comandos es la interfaz principal entre el usuario y el resto del sistema.

		El sistema intérprete de comandos ejecuta un comando de usuario llamando a uno o varios programas subyacentes del sistema o llamadas al sistema.

		    El sistema intérprete de comandos permite a los usuarios humanos interactuar con el sistema operativo y proporciona un entorno de programación cómodo para los usuarios.

		Muchos comandos se dan al sistema operativo mediante sentencias de control. 

		Un programa que lee e interpreta las sentencias de control se ejecuta automáticamente. 

		Este programa se llama shell y algunos ejemplos son la ventana de comandos de Windows DOS, Bash de Unix/Linux o C-Shell de Unix/Linux.


	Otras actividades importantes:

		Un Sistema Operativo es un Sistema de Software complejo: 

	    Seguridad:

	    	Mediante contraseñas y otras técnicas similares, impide el acceso no autorizado a programas y datos.


	    Control del rendimiento del sistema:

	    	Registrando los retrasos entre la solicitud de un servicio y la respuesta del sistema.


	    Contabilidad de trabajos:

	    	Llevar un registro del tiempo y los recursos utilizados por los distintos trabajos y usuarios.


	    Ayudas para la detección de errores: 

	    	Producción de volcados, trazas, mensajes de error y otras ayudas para la depuración y detección de errores.


	    Coordinación entre otros programas y usuarios:

	    	Coordinación y asignación de compiladores, intérpretes, ensambladores y otros programas a los distintos usuarios de los sistemas informáticos.



|| Tipos de Sistemas Operativos
	
	Los sistemas operativos existen desde la primera generación de ordenadores y siguen evolucionando con el tiempo. 

	
	Sistema operativo por lotes (batch OS):

		Los usuarios de un sistema operativo por lotes no interactúan directamente con el ordenador. 

		Cada usuario prepara su trabajo en un dispositivo fuera de línea, como tarjetas perforadas, y lo envía al operador del ordenador. 

		Para acelerar el procesamiento, los trabajos con necesidades similares se agrupan en lotes y se ejecutan como un grupo. 

		Los programadores dejan sus programas al operador y éste clasifica los programas con necesidades similares en lotes.


		Los problemas de los sistemas por lotes:

		    Falta de interacción entre el usuario y el trabajo.

		    La CPU está a menudo inactiva, porque la velocidad de los dispositivos mecánicos de E/S es más lenta que la de la CPU.

		    Dificultad para proporcionar la prioridad deseada.


	Sistemas operativos de tiempo compartido (Time Sharing):

		El tiempo compartido es una técnica que permite que varias personas, situadas en distintos terminales, utilicen al mismo tiempo un determinado sistema informático.

		El tiempo compartido o multitarea es una extensión lógica de la multiprogramación. 

		El tiempo de procesador que se comparte entre varios usuarios simultáneamente se denomina tiempo compartido.

		La principal diferencia entre los sistemas multiprogramados por lotes y los sistemas de tiempo compartido es que en el caso de los sistemas multiprogramados por lotes, el objetivo es maximizar el uso del procesador, mientras que en los sistemas de tiempo compartido, el objetivo es minimizar el tiempo de respuesta.

		La CPU ejecuta varios trabajos cambiando de uno a otro, pero los cambios se producen con mucha frecuencia. 

		Así, el usuario puede recibir una respuesta inmediata.

		Por ejemplo, en un procesamiento de transacciones, el procesador ejecuta cada programa de usuario en una breve ráfaga o quantum de computación. 

		Es decir, si hay n usuarios, cada uno puede recibir un quantum de tiempo. 

		Cuando el usuario envía el comando, el tiempo de respuesta es de unos pocos segundos como máximo.

		El sistema operativo utiliza la programación de la CPU y la multiprogramación para proporcionar a cada usuario una pequeña porción de tiempo. 

		Los sistemas informáticos que se diseñaron principalmente como sistemas por lotes se han modificado a sistemas de tiempo compartido.


		Las ventajas de los sistemas operativos de tiempo compartido son las siguientes:

		    Proporciona la ventaja de una respuesta rápida.

		    Evita la duplicación de software.

		    Reduce el tiempo de inactividad de la CPU.


		Las desventajas de los sistemas operativos de tiempo compartido son las siguientes:

    		Problema de fiabilidad.

    		Problema de seguridad e integridad de los programas y datos de usuario.
    		
    		Problema de comunicación de datos.


   	Sistema operativo distribuido (Distributed OS):

		Los sistemas distribuidos utilizan múltiples procesadores centrales para dar servicio a múltiples aplicaciones en tiempo real y múltiples usuarios. 

		Los trabajos de procesamiento de datos se distribuyen entre los procesadores en consecuencia.

		Los procesadores se comunican entre sí a través de varias líneas de comunicación (como buses de alta velocidad o líneas telefónicas). 

		Estos sistemas se denominan sistemas de acoplamiento débil o sistemas distribuidos. 

		Los procesadores de un sistema distribuido pueden variar en tamaño y función. 

		Estos procesadores se denominan sitios, nodos, ordenadores, etc.


		Las ventajas de los sistemas distribuidos:

		    Gracias a la posibilidad de compartir recursos, un usuario de un sitio puede utilizar los recursos disponibles en otro.

		    Aceleran el intercambio de datos entre los usuarios a través del correo electrónico.

		    Si falla un sitio en un sistema distribuido, los demás sitios pueden seguir funcionando.

		    Mejor servicio a los clientes.
		    Reducción de la carga del ordenador central.

		    Reducción de los retrasos en el procesamiento de datos.


	Sistema operativo de red:

		Un sistema operativo de red se ejecuta en un servidor y le proporciona la capacidad de gestionar datos, usuarios, grupos, seguridad, aplicaciones y otras funciones de red. 

		El objetivo principal del sistema operativo de red es permitir el acceso compartido a archivos e impresoras entre varios ordenadores de una red, normalmente una red de área local (LAN), una red privada o a otras redes.

		Algunos ejemplos de sistemas operativos de red son Microsoft Windows Server 2003, Microsoft Windows Server 2008, UNIX, Linux, Mac OS X, Novell NetWare y BSD.

		Las ventajas de los sistemas operativos de red:

		    Los servidores centralizados son muy estables.

		    La seguridad está gestionada por el servidor.

		    Las actualizaciones a nuevas tecnologías y hardware pueden integrarse fácilmente en el sistema.

		    El acceso remoto a los servidores es posible desde diferentes ubicaciones y tipos de sistemas.


		Las desventajas de los sistemas operativos:

		    Alto coste de adquisición y funcionamiento de un servidor.

		    Dependencia de una ubicación central para la mayoría de las operaciones.

		    Necesidad de mantenimiento y actualizaciones periódicas.


	Sistema operativo en tiempo real:

		Un sistema en tiempo real se define como un sistema de tratamiento de datos en el que el intervalo de tiempo necesario para procesar y responder a las entradas es tan pequeño que controla el entorno. 

		El tiempo que tarda el sistema en responder a una entrada y mostrar la información actualizada requerida se denomina tiempo de respuesta. 

		En este método, el tiempo de respuesta es muy inferior al del procesamiento en línea.

		Los sistemas en tiempo real se utilizan cuando existen requisitos de tiempo rígidos en el funcionamiento de un procesador o en el flujo de datos, y los sistemas en tiempo real pueden utilizarse como dispositivo de control en una aplicación específica. 

		Un sistema operativo en tiempo real debe tener restricciones temporales fijas y bien definidas, de lo contrario el sistema fallará. 

		Por ejemplo, experimentos científicos, sistemas de imágenes médicas, sistemas de control industrial, sistemas de armas, robots, sistemas de control del tráfico aéreo, etc.


		Existen dos tipos de sistemas operativos en tiempo real:


			Sistemas de Hard real-time:
				
				Garantizan que las tareas críticas se completen a tiempo. 

				En los sistemas de tiempo real duro, el almacenamiento secundario es limitado o inexistente y los datos se almacenan en ROM. 

				En estos sistemas, la memoria virtual casi nunca existe.


			Sistemas de Soft real-time:

				Los sistemas de tiempo real blandos son menos restrictivos. 

				Una tarea crítica en tiempo real tiene prioridad sobre otras tareas y conserva la prioridad hasta que finaliza. 

				Los sistemas de tiempo real blandos tienen una utilidad limitada en comparación con los sistemas de tiempo real duros. 

				Por ejemplo, multimedia, realidad virtual, proyectos científicos avanzados como exploración submarina y rovers planetarios, etc.



|| Servicios del Sistema Operativo
	
	Un Sistema Operativo proporciona servicios tanto a los usuarios como a los programas.

    Proporciona a los programas un entorno para ejecutarse.

    Proporciona a los usuarios los servicios para ejecutar los programas de una manera conveniente.

	    Ejecución de programas.

	    Operaciones de E/S.

	    Manipulación del sistema de archivos.

	    Comunicación.

	    Detección de errores.

	    Asignación de recursos
	    Protección.


	Ejecución de programas:

		Los sistemas operativos gestionan muchos tipos de actividades, desde programas de usuario hasta programas de sistema como spooler de impresora, servidores de nombres, servidor de archivos, etc. 

		Cada una de estas actividades se encapsula como un proceso.

		Un proceso incluye el contexto de ejecución completo (código a ejecutar, datos a manipular, registros, recursos del sistema operativo en uso). 


		Gestión de programas: 
	    	
	    	Carga un programa en memoria.

		    Ejecuta el programa.

		    Maneja la ejecución del programa.

		    Proporciona un mecanismo para la sincronización de procesos.

		    Proporciona un mecanismo para la comunicación de procesos.

		    Proporciona un mecanismo para la gestión de bloqueos.


	Funcionamiento de E/S:

		Un subsistema de E/S se compone de dispositivos de E/S y su correspondiente software controlador. 

		Los controladores ocultan a los usuarios las peculiaridades de determinados dispositivos de hardware.

		Un Sistema Operativo gestiona la comunicación entre el usuario y los controladores de dispositivos.

		    Una operación de E/S significa una operación de lectura o escritura con cualquier archivo o dispositivo de E/S específico.

		    El sistema operativo proporciona el acceso al dispositivo de E/S requerido cuando es necesario.


	Manipulación del sistema de archivos:

		Un archivo representa una colección de información relacionada. 

		Los ordenadores pueden almacenar archivos en el disco (almacenamiento secundario), con fines de almacenamiento a largo plazo. 

		Algunos ejemplos de medios de almacenamiento son la cinta magnética, el disco magnético y las unidades de disco óptico como CD, DVD. 

		Cada uno de estos medios tiene sus propias propiedades, como la velocidad, la capacidad, la velocidad de transferencia de datos y los métodos de acceso a los datos.

		Un sistema de archivos suele organizarse en directorios para facilitar la navegación y el uso.

		Estos directorios pueden contener archivos y otras direcciones. 

		principales actividades de un sistema operativo con respecto a la gestión de archivos:

		    El programa necesita leer un archivo o escribir un archivo.

		    El sistema operativo da el permiso al programa para operar sobre el archivo.

		    El permiso varía entre sólo lectura, lectura-escritura, denegado, etc.

		    El sistema operativo proporciona una interfaz al usuario para crear/borrar archivos.

		    El sistema operativo proporciona una interfaz al usuario para crear/borrar directorios.

		    El sistema operativo proporciona una interfaz para crear copias de seguridad del sistema de archivos.


	Comunicación:

		En el caso de los sistemas distribuidos, que son un conjunto de procesadores que no comparten memoria, dispositivos periféricos ni reloj, el sistema operativo gestiona las comunicaciones entre todos los procesos. 

		Múltiples procesos se comunican entre sí a través de líneas de comunicación en la red.

		El sistema operativo gestiona las estrategias de enrutamiento y conexión, así como los problemas de contención y seguridad. 

		Principales actividades de un sistema operativo con respecto a la comunicación:

		    A menudo, dos procesos necesitan transferir datos entre ellos.

		    Ambos procesos pueden estar en un ordenador o en ordenadores diferentes, pero están conectados a través de una red informática.

		    La comunicación puede implementarse por dos métodos, ya sea por Memoria Compartida o por Paso de Mensajes.


	Gestión de errores

		Los errores pueden producirse en cualquier momento y lugar. 

		Un error puede producirse en la CPU, en los dispositivos de E/S o en el hardware de la memoria. 

		A continuación se describen las principales actividades de un sistema operativo en relación con el tratamiento de errores.

	   	 	El SO comprueba constantemente posibles errores.

	    	El SO toma la acción apropiada para asegurar una computación correcta y consistente.


	Gestión de recursos:

		En un entorno multiusuario o multitarea, los recursos como la memoria principal, los ciclos de CPU y el almacenamiento de archivos deben asignarse a cada usuario o trabajo. 

		Principales actividades de un sistema operativo en relación con la gestión de recursos:

		    El sistema operativo gestiona todo tipo de recursos mediante programadores.

		    Los algoritmos de programación de la CPU se utilizan para una mejor utilización de la CPU.


	Protección:

		Teniendo en cuenta que un sistema informático tiene múltiples usuarios y la ejecución simultánea de múltiples procesos, los distintos procesos deben estar protegidos de las actividades de los demás.

		La protección se refiere a un mecanismo o forma de controlar el acceso de programas, procesos o usuarios a los recursos definidos por un sistema informático. 

		Principales actividades de un sistema operativo con respecto a la protección.

		    El SO se asegura de que todos los accesos a los recursos del sistema están controlados.

		    El SO asegura que los dispositivos externos de E/S están protegidos de intentos de acceso no válidos.

		    El SO proporciona funciones de autenticación para cada usuario mediante contraseñas.



|| Propiedades de los Sistemas Operativos
	
	Las diferentes propiedades de un sistema operativo:

	    Procesamiento por lotes (Batch processing)

	    Multitarea (Multitasking)

	    Multiprogramación (Multiprogramming)

	    Interactividad (Interactivity).

	    Sistema en tiempo real (Real Time System)

	    Entorno distribuido (    Distributed Environment).

	    SPOOLING 


	Procesamiento por lotes:

		El procesamiento por lotes es una técnica en la que un sistema operativo reúne los programas y los datos en un lote antes de iniciar el procesamiento. 

		Actividades relacionadas con el procesamiento por lotes:

		    El sistema operativo define un trabajo que tiene una secuencia predefinida de comandos, programas y datos como una sola unidad.

		    El SO mantiene un número de trabajos en memoria y los ejecuta sin ninguna información manual.

		    Los trabajos se procesan por orden de presentación, es decir, por orden de llegada.

		    Cuando un trabajo finaliza su ejecución, su memoria se libera y la salida del trabajo se copia en un spool de salida para su posterior impresión o procesamiento.


		Diagrama de flujo: 

			El sistema Operativo capta todas las tareas a realizar, crea un lote que interactúa con el CPU. 


		Ventajas

		    El procesamiento por lotes traslada gran parte del trabajo del operario al ordenador.

		    Mayor rendimiento, ya que un nuevo trabajo se inicia en cuanto termina el anterior, sin intervención manual.


		Desventajas

		    Programa difícil de depurar.

		    Un trabajo puede entrar en un bucle infinito.

		    Debido a la falta de un esquema de protección, un trabajo por lotes puede afectar a los trabajos pendientes.


	Multitarea:

		La multitarea es cuando la CPU ejecuta varios trabajos simultáneamente cambiando entre ellos. 

		Los cambios se producen con tanta frecuencia que los usuarios pueden interactuar con cada programa mientras se está ejecutando. 
	
		Actividades relacionadas con la multitarea:

		    El usuario da instrucciones al sistema operativo o a un programa directamente, y recibe una respuesta inmediata.

		    El SO maneja la multitarea de forma que puede manejar múltiples operaciones/ejecutar múltiples programas a la vez.

		    Los sistemas operativos multitarea también se conocen como sistemas de tiempo compartido.

		    Estos Sistemas Operativos se desarrollaron para proporcionar un uso interactivo de un sistema informático a un coste razonable.

		    Un sistema operativo de tiempo compartido utiliza el concepto de programación y multiprogramación de la CPU para proporcionar a cada usuario una pequeña porción de una CPU de tiempo compartido.

		    Cada usuario tiene al menos un programa independiente en memoria.


		Diagrama de flujo: 

			Todas las aplicaciones o programas se juntan en un proceso y el sistema operativo lo carga al CPU. 


		Un programa que se carga en memoria y se está ejecutando se conoce comúnmente como proceso.

	    Cuando un proceso se ejecuta, normalmente lo hace durante muy poco tiempo antes de que termine o de que necesite realizar una E/S.

	    Dado que la E/S interactiva se ejecuta normalmente a velocidades más lentas, puede tardar mucho tiempo en completarse. 

	    Durante este tiempo, una CPU puede ser utilizada por otro proceso.

	    El sistema operativo permite a los usuarios compartir el ordenador simultáneamente.

	    Como cada acción o comando en un sistema de tiempo compartido tiende a ser corto, sólo se necesita un poco de tiempo de CPU para cada usuario.

	    Como el sistema cambia la CPU rápidamente de un usuario/programa al siguiente, cada usuario tiene la impresión de que tiene su propia CPU, cuando en realidad una CPU está siendo compartida entre muchos usuarios.


	Multiprogramación:

		Compartir el procesador, cuando dos o más programas residen en memoria al mismo tiempo, se denomina multiprogramación. 

		La multiprogramación supone un único procesador compartido. 

		La multiprogramación aumenta la utilización de la CPU organizando los trabajos de forma que la CPU siempre tenga uno para ejecutar.


		Diagrama de flujo: 

			Las tareas se aplican a la espera de que el sistema operativo las ejecute. Deja espacio libre para las entrantes. 	


		Actividades relacionadas con la multiprogramación:

		    El sistema operativo mantiene varios trabajos en memoria a la vez.

		    Este conjunto de trabajos es un subconjunto de los trabajos mantenidos en la reserva de trabajos.

		    El sistema operativo elige y comienza a ejecutar uno de los trabajos en la memoria.

		    Los sistemas operativos multiprogramación controlan el estado de todos los programas activos y los recursos del sistema mediante programas de gestión de memoria para garantizar que la CPU nunca esté inactiva, a menos que no haya trabajos que procesar.


		Ventajas

		    Utilización alta y eficiente de la CPU.

		    El usuario siente que muchos programas tienen asignada la CPU casi simultáneamente.


		Desventajas

		    Es necesario programar la CPU.

		    Para acomodar muchos trabajos en memoria, se requiere gestión de memoria.


	Interactividad:

		La interactividad se refiere a la capacidad de los usuarios para interactuar con un sistema informático. 

		Actividades relacionadas con la interactividad:

		    Proporciona al usuario una interfaz para interactuar con el sistema.

		    Gestiona los dispositivos de entrada para recibir entradas del usuario. 

		    Por ejemplo, el teclado.

		    Gestiona los dispositivos de salida para mostrar las salidas al usuario. 

		    Por ejemplo, el monitor.


		El tiempo de respuesta del sistema operativo debe ser corto, ya que el usuario envía y espera el resultado.


	Sistemas en tiempo real:

		Los sistemas de tiempo real suelen ser sistemas embebidos dedicados.

		Actividades relacionadas con la actividad del sistema en tiempo real:

		    En estos sistemas, los sistemas operativos suelen leer los datos de los sensores y reaccionar ante ellos.

		    El sistema operativo debe garantizar la respuesta a los eventos en periodos de tiempo fijos para asegurar un rendimiento correcto.


	Entorno distribuido:

		Un entorno distribuido hace referencia a múltiples CPU o procesadores independientes en un sistema informático. 

		Actividades relacionadas con el entorno distribuido:

		    El sistema operativo distribuye la lógica de cálculo entre varios procesadores físicos.

		    Los procesadores no comparten memoria ni reloj. 

		    En su lugar, cada procesador tiene su propia memoria local.

		    El SO gestiona las comunicaciones entre los procesadores. 

		    Éstos se comunican entre sí a través de varias líneas de comunicación.


	Spooling:

		Spooling es un acrónimo de operaciones periféricas simultáneas en línea. 

		Spooling se refiere a poner los datos de varios trabajos de E/S en un buffer.

		Este búfer es un área especial en la memoria o en el disco duro que es accesible a los dispositivos de E/S.

		Actividades relacionadas con el entorno distribuido:

		    Maneja el spooling de datos del dispositivo de E/S ya que los dispositivos tienen diferentes velocidades de acceso a los datos.

		    Mantiene el buffer de spooling que proporciona una estación de espera donde los datos pueden descansar mientras el dispositivo más lento se pone al día.

		    Mantiene la computación paralela debido al proceso de spooling ya que un ordenador puede realizar E/S de forma paralela.

		    Es posible que el ordenador lea datos de una cinta, escriba datos en el disco y escriba en una impresora de cinta mientras realiza su tarea de cálculo.


		Diagrama de flujo: 

			Los dispositivos E/S interactuan con la memoria y el disco. 


		Ventajas

		    La operación de spooling utiliza un disco como un búfer muy grande.

		    El spooling es capaz de solapar operaciones de E/S de un trabajo con operaciones de procesador de otro trabajo.



|| Procesos del Sistema Operativo
	
	
