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
	
	Es básicamente un programa en ejecución. 

	La ejecución de un proceso debe progresar de forma secuencial.

    Un proceso se define como una entidad que representa la unidad básica de trabajo que debe implementarse en el sistema.

	Para simplificarlo, escribimos nuestros programas informáticos en un archivo de texto y cuando ejecutamos este programa, se convierte en un proceso que realiza todas las tareas mencionadas en el programa.

	Cuando un programa se carga en la memoria y se convierte en un proceso, puede dividirse en cuatro secciones: pila, montón, texto y datos. 


	Diagrama de un proceso (programa) en la memoria: 

		Es una pila (stack) con una estructura LIFO (Last In First Out), el ultimo elemento apilado es el primero que se completa. 


		1. Pila: 

			La pila del proceso contiene los datos temporales, como los parámetros de métodos/funciones, la dirección de retorno y las variables locales.


		2. Heap (Montículo): 

			Estructura con un elemento principal o raíz (siendo el más grande o el más pequeño) que mantiene el orden de la estructura. 

			Es la memoria asignada dinámicamente a un proceso durante su tiempo de ejecución.
		 	

		3. Texto: 

			Incluye la actividad actual representada por el valor del Contador de Programa y el contenido de los registros del procesador.


		4. Datos: 

			Esta sección contiene las variables globales y estáticas.


	Programa:

		Es un fragmento de código que puede ser de una sola línea o de millones de líneas. 

		Un programa de ordenador lo suele escribir un programador informático en un lenguaje de programación. 

		Por ejemplo, he aquí un programa sencillo escrito en lenguaje de programación C:

			```
				#include <stdio.h>

				int main() {
				   printf("Hello, World! \n");
				   return 0;
				}

			```

		Un programa informático es un conjunto de instrucciones que realizan una tarea específica cuando son ejecutadas por un ordenador. 

		Si comparamos un programa con un proceso, podemos concluir que un proceso es una instancia dinámica de un programa informático.

		La parte de un programa informático que realiza una tarea bien definida se conoce como algoritmo. 

		Un conjunto de programas informáticos, bibliotecas y datos relacionados se denomina software.


	Ciclo de vida de un proceso

		Cuando un proceso se ejecuta, pasa por diferentes estados.

		Estos estados pueden diferir en los distintos sistemas operativos, y los nombres de estos estados tampoco están estandarizados.

		En general, un proceso puede tener uno de los cinco estados siguientes a la vez.


	Diagrama de flujo de estados de un programa: 	

		Muestra que un programa pasa por diferentes etapas. 


		1. Inicio/Start

			Es el estado inicial cuando se inicia/crea un proceso por primera vez.
		 	

		2. Listo/Ready

			El proceso está esperando a que se le asigne un procesador. 

			Los procesos listos están esperando a que el sistema operativo les asigne un procesador para poder ejecutarse. 

			El proceso puede entrar en este estado después del estado de inicio o mientras se está ejecutando, pero puede ser interrumpido por el programador para asignar la CPU a otro proceso.
		

		3. Ejecutando/Running

			Una vez que el proceso ha sido asignado a un procesador por el programador del sistema operativo, el estado del proceso pasa a ejecución y el procesador ejecuta sus instrucciones.
			

		4. En espera/Waiting

			El proceso pasa al estado de espera si necesita esperar un recurso, como la entrada de un usuario o la disponibilidad de un archivo.
			

		5. Terminado o Salida/Terminated or Exit

			Una vez que el proceso termina su ejecución, o es terminado por el sistema operativo, pasa al estado terminado donde espera a ser eliminado de la memoria principal.


	Bloque de control de procesos (PCB)

		Un Bloque de Control de Proceso es una estructura de datos mantenida por el Sistema Operativo para cada proceso. 

		El PCB se identifica mediante un ID de proceso entero (PID). 

		Un PCB mantiene toda la información necesaria para realizar el seguimiento de un proceso como se indica a continuación.


		1. Estado del proceso:

			El estado actual del proceso, es decir, si está listo, en ejecución, en espera o en los estados mencionados anteriormente. 
		 	

		2. Privilegios del proceso:

			Es necesario para permitir/prohibir el acceso a los recursos del sistema.
			

		3. ID del proceso:

			Identificación única para cada uno de los procesos en el sistema operativo.
		 	

		4. Puntero/Pointer:

			Puntero al proceso padre.
		 	

		5. Contador de programa/Program counter:

			El contador de programa es un puntero a la dirección de la siguiente instrucción a ejecutar para este proceso.
		 	

		6. Registros de la CPU/Entradas:

			Varios registros de la CPU donde el proceso necesita ser almacenado para su ejecución en estado de ejecución.
		 	

		7. Información de programación de la CPU/CPU Scheduling Information:

			Prioridad del proceso y otra información de programación necesaria para programar el proceso.
		 	

		8. Información de gestión de memoria/Memory management information:

			Incluye la información de tabla de páginas, límites de memoria, tabla de segmentos en función de la memoria utilizada por el sistema operativo.
		 	

		9. Información de contabilidad/Accounting information:

			Incluye la cantidad de CPU utilizada para la ejecución de procesos, límites de tiempo, ID de ejecución, etc.
		 	

		10. Información de estado de E/S. /IO status information:

			Incluye una lista de los dispositivos de E/S asignados al proceso.


		El diagrama del bloque puede verse como una pila para depende. 

		La arquitectura de una PCB depende completamente del sistema operativo y puede contener información diferente en distintos sistemas operativos.

		El PCB se mantiene para un proceso durante toda su vida, y se elimina una vez que el proceso termina.



|| Programación de procesos del Sistema Operativo / Process Scheduling OS

	La programación de procesos es la actividad del gestor de procesos (process manager) que se encarga de retirar de la CPU el proceso en ejecución y de seleccionar otro proceso en función de una estrategia determinada.

	La programación de procesos es una parte esencial de los sistemas operativos multiprogramación (Multiprogramming OS). 

	Estos sistemas operativos permiten cargar más de un proceso a la vez en la memoria ejecutable y que el proceso cargado comparta la CPU mediante multiplexación temporal (time multiplexing).
	
	
	Existen dos categorías de programación (scheduling):

    	No preferente (Non-preemptive): 

    		Aquí el recurso no puede ser tomado de un proceso hasta que el proceso complete la ejecución.

    		La conmutación de recursos se produce cuando el proceso en ejecución termina y pasa a un estado de espera.
    	

    	Preemptivo (Preemptive): 

    		El sistema operativo asigna los recursos a un proceso durante un tiempo determinado. 

    		Durante la asignación de recursos, el proceso pasa del estado en ejecución al estado listo o del estado de espera al estado listo. 

    		Este cambio se produce porque la CPU puede dar prioridad a otros procesos y sustituir el proceso con mayor prioridad por el proceso en ejecución.


	Colas de programación de procesos / Process Scheduling Queues 

		El SO mantiene todos los Bloques de Control de Procesos (PCBs) en Colas de Programación de Procesos. 

		El SO mantiene una cola separada para cada uno de los estados del proceso y los PCBs de todos los procesos en el mismo estado de ejecución se colocan en la misma cola. 

		Cuando se cambia el estado de un proceso, su PCB se desvincula de su cola actual y se mueve a la cola de su nuevo estado.


		El Sistema Operativo mantiene las siguientes colas importantes de programación de procesos: 


		    Cola de trabajos/Job queue: 

		    	Esta cola mantiene todos los procesos del sistema.


		    Cola de listos/Ready queue:

		    	Esta cola mantiene un conjunto de todos los procesos que residen en la memoria principal, listos y esperando para ejecutarse. 

		    	Un nuevo proceso se coloca siempre en esta cola.


		    Cola de dispositivos/Device queues: 

		    	Los procesos que están bloqueados debido a la falta de disponibilidad de un dispositivo de E/S constituyen esta cola.


    	Diagrama de flujo de la programación de procesos: 

    		Presenta una cola que se va dividiendo cuando llega al CPU, espera a la entrada de datos y vuelve a Ready Queue. 

	
		El SO puede utilizar diferentes políticas para gestionar cada cola (FIFO, Round Robin, Prioridad, etc.). 

		El planificador del SO (OS scheduler) determina cómo mover los procesos entre las colas de listos y de ejecución, que sólo pueden tener una entrada por núcleo de procesador en el sistema; en el diagrama anterior, se ha fusionado con la CPU.


	Modelo de proceso de dos estados/Two-State Process Model:

		El modelo de proceso de dos estados se refiere a los estados de ejecución y no ejecución que se describen a continuación:

		1. En ejecución:

			Cuando se crea un nuevo proceso, éste entra en el sistema en estado de ejecución.


		2. No en ejecución:

			Los procesos que no se están ejecutando se mantienen en cola, esperando su turno para ejecutarse. 

			Cada entrada en la cola es un puntero a un proceso concreto. 

			La cola se implementa utilizando una lista enlazada. 

			El uso del despachador (the dispatcher) es el siguiente. 

			Cuando se interrumpe un proceso, ese proceso se transfiere a la cola de espera. 

			Si el proceso se ha completado o abortado, el proceso se descarta. 

			En cualquier caso, el despachador (the dispatcher) selecciona un proceso de la cola para ejecutarlo.
	

	Programadores/Schedulers:

		Los programadores son programas especiales del sistema que se encargan de la programación de los procesos de diversas maneras.

		Su tarea principal es seleccionar los trabajos que se van a enviar al sistema y decidir qué proceso se va a ejecutar. 

		Los programadores son de tres tipos:

		    Programador a largo plazo
		    Programador a corto plazo
    		Programador a medio plazo


    Programador a largo plazo:

		También se denomina programador de trabajos. 

		Un programador a largo plazo determina qué programas se admiten en el sistema para su procesamiento. 

		Selecciona los procesos de la cola y los carga en la memoria para su ejecución. 

		Los procesos se cargan en la memoria para ser programados por la CPU.

		El objetivo principal del programador de trabajos (job scheduler) es proporcionar una mezcla equilibrada de trabajos, como los vinculados a la E/S y los vinculados al procesador. 

		También controla el grado de multiprogramación. 

		Si el grado de multiprogramación es estable, entonces la tasa media de creación de procesos debe ser igual a la tasa media de salida de procesos del sistema.

		En algunos sistemas, el programador a largo plazo puede no estar disponible o ser mínimo.

		Los sistemas operativos de tiempo compartido no tienen programador a largo plazo. 

		Cuando un proceso cambia el estado de nuevo a listo, entonces se utiliza el planificador a largo plazo.


	Planificador a corto plazo:

		También se denomina planificador de CPU. 

		Su objetivo principal es aumentar el rendimiento del sistema de acuerdo con el conjunto de criterios elegidos. 

		Es el cambio del estado listo al estado en ejecución del proceso. El programador de la CPU selecciona un proceso entre los que están listos para ejecutarse y asigna la CPU a uno de ellos.

		Los planificadores a corto plazo, también conocidos como despachadores, deciden qué proceso se ejecutará a continuación. 

		Los programadores a corto plazo son más rápidos que los programadores a largo plazo.

	
	Programador a medio plazo:

		La programación a medio plazo forma parte del intercambio (Swapping). 

		Elimina los procesos de la memoria. 

		Reduce el grado de multiprogramación. 

		El programador a medio plazo se encarga de gestionar los procesos intercambiados.

		Un proceso en ejecución puede quedar suspendido si realiza una solicitud de E/S.

		Un proceso suspendido no puede avanzar hacia su finalización. 

		En este caso, para eliminar el proceso de la memoria y hacer espacio para otros procesos, el proceso suspendido se mueve al almacenamiento secundario. 

		Este proceso se llama swapping, y se dice que el proceso ha sido swapped out o rolled out. 

		El swapping puede ser necesario para mejorar la mezcla de procesos.	


	Comparación entre planificadores/programadores (scheduling process)

		Programador a largo plazo:

			Es un programador de trabajos.

			La velocidad es inferior a la del programador a corto plazo.

			Controla el grado de multiprogramación.

			Es casi inexistente o mínimo en el sistema de tiempo compartido.

			Selecciona procesos del pool y los carga en memoria para su ejecución.


		Programador a corto plazo

			Es un programador de CPU.

			Es el más rápido de los otros dos.

			Proporciona menos control sobre el grado de multiprogramación.

			También es mínimo en el sistema de tiempo compartido.

			Selecciona los procesos que están listos para ejecutarse.


		Planificador a medio plazo:

			Es un planificador de intercambio de procesos.

			Su velocidad se encuentra entre los planificadores de corto y largo plazo.

			Reduce el grado de multiprogramación.

			Forma parte de los sistemas de tiempo compartido.

			Puede reintroducir el proceso en memoria y continuar la ejecución.


	Conmutación de contexto/Context Switching

		Un conmutador de contexto es el mecanismo para almacenar y restaurar el estado o contexto de una CPU en el bloque de control de procesos, de forma que la ejecución de un proceso pueda reanudarse desde el mismo punto en un momento posterior. 

		Mediante esta técnica, un conmutador de contexto permite que varios procesos compartan una única CPU. 

		El cambio de contexto es una parte esencial de las características de un sistema operativo multitarea.

		Cuando el programador cambia la CPU de la ejecución de un proceso a la ejecución de otro, el estado del proceso en ejecución actual se almacena en el bloque de control del proceso. 

		Después de esto, el estado del proceso que se ejecutará a continuación se carga desde su propio PCB y se utiliza para configurar el PC, los registros, etc. 

		En ese momento, el segundo proceso puede empezar a ejecutarse.

		Los cambios de contexto son intensivos desde el punto de vista computacional, ya que el estado de los registros y la memoria debe guardarse y restaurarse. 

		Para evitar el tiempo de cambio de contexto, algunos sistemas de hardware emplean dos o más conjuntos de registros del procesador. 


		Diagrama de stack CPU/Context Switching:

			El CPU apila todos los procesos. Activa, los salva en un estado para restaurarlos en caso de necesitarlos. 


		Cuando se conmuta el proceso, se almacena la siguiente información para su uso posterior.

	    	Contador de programa.

	    	Información de programación.

	    	Valor del registro base y límite.

	    	Registro utilizado actualmente.

	    	Estado cambiado.

	    	Información de estado de E/S.

	    	Información contable.



|| Algoritmos de programación/Scheduling algorithms


	Un Programador de Procesos (Process Scheduler) programa diferentes procesos para ser asignados a la CPU basándose en algoritmos de programación particulares. 

	Hay seis algoritmos populares de programación de procesos que vamos a discutir en este capítulo.


	    Programación por orden de llegada (FCFS).

	    Programación del trabajo más corto al siguiente (SJN).

	    Programación por prioridades.

	    Tiempo restante más corto.

	    Programación Round Robin (RR).

	    Programación de colas de varios niveles.


	Estos algoritmos pueden ser no preferentes o preferentes (non-preemptive or preemptive). 

	Los algoritmos no preferentes están diseñados de tal forma que, una vez que un proceso entra en estado de ejecución, no puede ser adelantado hasta que complete el tiempo que se le ha asignado, mientras que la programación preferente se basa en la prioridad, por lo que un planificador puede adelantar un proceso en ejecución de baja prioridad en cualquier momento cuando un proceso de alta prioridad entra en estado listo.


	Por orden de llegada/First Come First Serve (FCFS)

    	Los trabajos se ejecutan por orden de llegada.

    	Se trata de un algoritmo de planificación no preferente y preferente.

    	Fácil de entender e implementar.
   		Su implementación se basa en la cola FIFO.

    	Su rendimiento es bajo, ya que el tiempo medio de espera es elevado.


    	Tabla o vista de procesos: 

    		Tenemos cuatro columnas: ID o nombre del proceso, hora de llegada (arrival time), hora de ejecución (execute time) y service time (tiempo de servicio)

    		Aumentará el tiempo de espera de cada proceso. 


    Trabajo más corto determina el siguiente/Shortest Job Next (SJN)

	    También conocido como trabajo más corto primero o SJF.

	    Se trata de un algoritmo de programación no preferente y preferente.

	    Es el mejor método para minimizar el tiempo de espera.

	    Fácil de implementar en sistemas por lotes en los que el tiempo de CPU necesario se conoce de antemano.

	    Imposible de aplicar en sistemas interactivos en los que no se conoce el tiempo de CPU necesario.

	    El procesador debe saber de antemano cuánto tiempo tardará el proceso.


	Programación por prioridades/Priority Based Scheduling

	    La programación por prioridades es un algoritmo no preferente y uno de los algoritmos de programación más comunes en los sistemas por lotes.

	    A cada proceso se le asigna una prioridad. 

	    El proceso con mayor prioridad se ejecuta primero y así sucesivamente.

	    Los procesos con la misma prioridad se ejecutan por orden de llegada.

	    La prioridad puede decidirse en función de los requisitos de memoria, tiempo o cualquier otro requisito de recursos.

		Aquí consideramos que 1 es la prioridad más baja.


	Tiempo restante más corto/Shortest Remaining Time

	    El tiempo restante más corto (SRT) es la versión preferente del algoritmo SJN.

	    El procesador se asigna al trabajo más próximo a la finalización, pero puede ser adelantado por un trabajo más reciente con un tiempo más corto hasta la finalización.

	    Imposible de aplicar en sistemas interactivos en los que no se conoce el tiempo de CPU necesario.

	    Suele utilizarse en entornos por lotes en los que hay que dar preferencia a los trabajos cortos.


	Programación Round Robin/Round Robin Scheduling

	    Round Robin es el algoritmo de programación de procesos preferente.

	    A cada proceso se le proporciona un tiempo fijo de ejecución, que se denomina quantum.

	    Una vez que un proceso se ejecuta durante un periodo de tiempo determinado, se le da preferencia y otro proceso se ejecuta durante un periodo de tiempo determinado.

	    El cambio de contexto se utiliza para guardar los estados de los procesos adelantados.


	Programación de colas de varios niveles

		Las colas de varios niveles no son un algoritmo de programación independiente. 
		
		Hacen uso de otros algoritmos existentes para agrupar y programar trabajos con características comunes.

		    Se mantienen múltiples colas para procesos con características comunes.

		    Cada cola puede tener sus propios algoritmos de programación.

		    Se asignan prioridades a cada cola.

		Por ejemplo, los trabajos vinculados a la CPU pueden programarse en una cola y todos los trabajos vinculados a la E/S en otra cola. 

		A continuación, el Programador de Procesos selecciona alternativamente los trabajos de cada cola y los asigna a la CPU en función del algoritmo asignado a la cola.    



|| Multiproceso/Multi-Threading


	Un hilo es un flujo de ejecución a través del código del proceso, con su propio contador de programa que mantiene la pista de qué instrucción ejecutar a continuación, registros de sistema que mantienen sus variables de trabajo actuales, y una pila que contiene el historial de ejecución.

	Un subproceso comparte con sus compañeros información como el segmento de código, el segmento de datos y los archivos abiertos. 

	Cuando un hilo altera un elemento de memoria del segmento de código, todos los demás hilos lo ven.

	Un hilo también se denomina proceso ligero. 

	Los hilos proporcionan una forma de mejorar el rendimiento de la aplicación a través del paralelismo.

	Los hilos representan un enfoque de software para mejorar el rendimiento del sistema operativo mediante la reducción de la sobrecarga.

	Cada hilo pertenece exactamente a un proceso y ningún hilo puede existir fuera de un proceso. 

	Cada hilo representa un flujo de control independiente. 

	Los hilos se han utilizado con éxito en la implementación de servidores de red y servidores web. 

	También proporcionan una base adecuada para la ejecución paralela de aplicaciones en multiprocesadores de memoria compartida. 


	Diagrama sobre el funcionamiento de un proceso monohilo y uno multihilo: 

		En el proceso monohilo vemos que todo el proceso se desarrolla sobre un solo hilo y el el multithilo la información puede multiplicarse. 


	Diferencia entre proceso e hilo: 

		Proceso:

			El proceso es pesado o consume muchos recursos.

			El cambio de proceso requiere interacción con el sistema operativo.

			En entornos de procesamiento múltiple (multiple processing environments), cada proceso ejecuta el mismo código pero tiene sus propios recursos de memoria y archivos.

			Si un proceso se bloquea, ningún otro proceso puede ejecutarse hasta que el primero se desbloquee.

			Los procesos múltiples que no utilizan hilos consumen más recursos.

			En los procesos múltiples, cada proceso funciona independientemente de los demás.


		Hilos: 

			Los hilos son ligeros y consumen menos recursos que los procesos.

			El cambio de hilo no necesita interactuar con el sistema operativo.

			Todos los hilos pueden compartir el mismo conjunto de archivos abiertos, procesos hijos.

			Mientras un hilo está bloqueado y esperando, un segundo hilo en la misma tarea puede ejecutarse.

			Los procesos con múltiples hilos utilizan menos recursos.

			Un hilo puede leer, escribir o cambiar los datos de otro hilo.


	Ventajas de los hilos:

	    Los hilos minimizan el tiempo de cambio de contexto.

	    El uso de hilos proporciona concurrencia dentro de un proceso.

	    Comunicación eficiente.

	    Es más económico crear y cambiar de contexto hilos.

	    Los hilos permiten la utilización de arquitecturas multiprocesador a una mayor escala y eficiencia.


	Tipos de hilos:

		Se implementan de dos formas:

	    Hilos a nivel de usuario:

	    	Hilos gestionados por el usuario.


	    Hilos a nivel de núcleo:	

	    	Hilos gestionados por el sistema operativo que actúan sobre el núcleo, un núcleo del sistema operativo.


	Hilos a nivel de usuario

		En este caso, el núcleo de gestión de hilos no es consciente de la existencia de hilos. 

		La librería de hilos contiene código para crear y destruir hilos, para pasar mensajes y datos entre hilos, para programar la ejecución de hilos y para guardar y restaurar contextos de hilos. 

		La aplicación se inicia con un único subproceso.


		Diagrama: 	

			Sobre el CPU se ejecuta el kernel y este provee un espacio para que el usuario ejecute procesos multihilo.  


		Ventajas:

    		La conmutación de hilos no requiere privilegios de modo Kernel.

    		El hilo de nivel de usuario puede ejecutarse en cualquier sistema operativo.

    		La programación puede ser específica de la aplicación en el hilo de nivel de usuario.

    		Los hilos a nivel de usuario son rápidos de crear y gestionar.


		Desventajas:

			En un sistema operativo típico, la mayoría de las llamadas al sistema son de bloqueo.

			Las aplicaciones multihilo no pueden aprovechar las ventajas del multiprocesamiento.


	Hilos a nivel de núcleo:

		En este caso, la gestión de hilos la realiza el Kernel.

		No hay código de gestión de hilos en el área de aplicación.

		Los hilos del Kernel son soportados directamente por el sistema operativo. 

		Cualquier aplicación puede ser programada para ser multihilo.

		Todos los hilos dentro de una aplicación son soportados dentro de un único proceso.

		El Kernel mantiene información de contexto para el proceso como un todo y para los hilos individuales dentro del proceso.

		La programación por parte del Kernel se realiza en base a hilos. 

		El Kernel realiza la creación, programación y gestión de hilos en el espacio del Kernel. 

		La creación y gestión de los hilos del núcleo suele ser más lenta que la de los hilos de usuario.


		Ventajas:

		   	El Kernel puede programar simultáneamente múltiples hilos del mismo proceso en múltiples procesos.

		    Si un hilo de un proceso se bloquea, el Kernel puede programar otro hilo del mismo proceso.

			Las propias rutinas del Kernel pueden ser multihilo.


		Desventajas:

		    Los hilos del Kernel son generalmente más lentos de crear y gestionar que los hilos de usuario.

		    La transferencia de control de un hilo a otro dentro del mismo proceso requiere un cambio de modo en el Kernel.


	Modelos multihilo:

		Algunos sistemas operativos ofrecen una función combinada de subprocesos a nivel de usuario y subprocesos a nivel de núcleo.

		Solaris es un buen ejemplo de este enfoque combinado. 

		En un sistema combinado, varios subprocesos de la misma aplicación pueden ejecutarse en paralelo en varios procesadores y no es necesario que una llamada al sistema bloqueante bloquee todo el proceso. 

		Los modelos de multithreading son de tres tipos

		    Relación muchos a muchos.
		    Relación muchos a uno.
		    Relación uno a uno.


	Modelo muchos a muchos:

		El modelo muchos a muchos multiplexa cualquier número de hilos de usuario en un número igual o menor de hilos de núcleo.

		El siguiente diagrama muestra el modelo de hilos muchos a muchos donde 6 hilos de nivel usuario se multiplexan con 6 hilos de nivel kernel. 

		En este modelo, los desarrolladores pueden crear tantos subprocesos de usuario como sea necesario y los correspondientes subprocesos del núcleo pueden ejecutarse en paralelo en una máquina multiprocesador. 

		Este modelo proporciona la mejor precisión en concurrencia y cuando un hilo realiza una llamada al sistema bloqueante, el núcleo puede programar otro hilo para su ejecución.


	Diferencia entre hilo de nivel de usuario y de nivel de núcleo:

		Hilo a nivel de usuario:

			Los subprocesos a nivel de usuario son más rápidos de crear y gestionar.

			Se implementan mediante una biblioteca de hilos a nivel de usuario.

			Los hilos a nivel de usuario son genéricos y pueden ejecutarse en cualquier sistema operativo.

			Las aplicaciones multihilo no pueden aprovechar las ventajas del multiprocesamiento.


		Hilo a nivel de núcleo:

			Los hilos a nivel de núcleo son más lentos de crear y gestionar.

			El sistema operativo soporta la creación de hilos a nivel de Kernel.

			Los hilos a nivel de núcleo son específicos del sistema operativo.

			Las propias rutinas del núcleo pueden ser multihilo.



|| Gestión de memoria en el Sistema Operativo 

	La gestión de memoria es la funcionalidad de un sistema operativo que maneja o gestiona la memoria primaria y mueve los procesos de un lado a otro entre la memoria principal y el disco durante la ejecución. 

	La gestión de memoria realiza un seguimiento de todas y cada una de las posiciones de memoria, independientemente de si está asignada a algún proceso o está libre. 

	Comprueba cuánta memoria debe asignarse a los procesos. 

	Decide qué proceso obtendrá memoria y en qué momento. 

	Realiza un seguimiento cada vez que se libera o se desasigna memoria y, en consecuencia, actualiza el estado.


	Espacio de Direcciones de Proceso/Process Address Space:

		El espacio de direcciones del proceso es el conjunto de direcciones lógicas a las que un proceso hace referencia en su código. 

		Por ejemplo, cuando se utiliza el direccionamiento de 32 bits, las direcciones pueden ir de 0 a 0x7fffffff; es decir, 2^31 números posibles, para un tamaño teórico total de 2 gigabytes.

		El sistema operativo se encarga de asignar las direcciones lógicas a direcciones físicas en el momento de la asignación de memoria al programa. 

		Hay tres tipos de direcciones que se utilizan en un programa antes y después de asignar la memoria:


	Direcciones de memoria (Memory Addresses) y descripción:

		1. Direcciones simbólicas

			Son las direcciones utilizadas en un código fuente. 

			Los nombres de variables, constantes y etiquetas de instrucciones son los elementos básicos del espacio de direcciones simbólicas.	


		2. Direcciones relativas

			En el momento de la compilación, un compilador convierte las direcciones simbólicas en direcciones relativas.
		 	

		3. Direcciones físicas

			El cargador genera estas direcciones en el momento en que se carga un programa en la memoria principal.


		Las direcciones virtuales y físicas son las mismas en los esquemas de vinculación de direcciones en tiempo de compilación y en tiempo de carga.

		Las direcciones virtuales y físicas difieren en el esquema de vinculación de direcciones en tiempo de ejecución.

		El conjunto de todas las direcciones lógicas generadas por un programa se denomina espacio de direcciones lógicas (logical address space). 

		El conjunto de todas las direcciones físicas correspondientes a estas direcciones lógicas se denomina espacio de direcciones físicas (physical address space).

		La unidad de gestión de memoria (MMU), que es un dispositivo de hardware, realiza la asignación en tiempo de ejecución de la dirección virtual a la física. 

		La MMU utiliza el siguiente mecanismo para convertir la dirección virtual en dirección física.

		    El valor del registro base se añade a cada dirección generada por un proceso de usuario, que se trata como offset en el momento en que se envía a la memoria. 

		    Por ejemplo, si el valor del registro base es 10000, entonces un intento del usuario de utilizar la ubicación de dirección 100 se reasignará dinámicamente a la ubicación 10100.

		    El programa de usuario trata con direcciones virtuales; nunca ve las direcciones físicas reales.


	Carga estática frente a carga dinámica/Static vs Dynamic Loading:

		La elección entre Carga Estática o Dinámica debe hacerse en el momento de desarrollar el programa informático. 

		Si tiene que cargar su programa estáticamente, entonces en el momento de la compilación, los programas completos se compilarán y enlazarán sin dejar ninguna dependencia de programas o módulos externos. 

		El enlazador combina el programa objeto con otros módulos objeto necesarios en un programa absoluto, que también incluye direcciones lógicas.

		Si estás escribiendo un programa cargado dinámicamente, entonces tu compilador compilará el programa y para todos los módulos que quieras incluir dinámicamente, sólo se proporcionarán referencias y el resto del trabajo se hará en el momento de la ejecución.

		En el momento de la carga, con la carga estática (static loading), el programa absoluto (y los datos) se cargan en memoria para que comience la ejecución.

		Si se utiliza la carga dinámica (dynamic loading), las rutinas dinámicas (dynamic routines) de la biblioteca se almacenan en disco en forma reubicable y se cargan en memoria sólo cuando el programa las necesita.


	Vinculación estática frente a dinámica/Static vs Dynamic Linking: 

		Como se ha explicado anteriormente, cuando se utiliza el enlazado estático, el enlazador combina todos los demás módulos que necesita un programa en un único programa ejecutable para evitar cualquier dependencia en tiempo de ejecución.

		Cuando se utiliza el enlazado dinámico, no es necesario enlazar el módulo o biblioteca real con el programa, sino que se proporciona una referencia al módulo dinámico en el momento de la compilación y el enlazado. 

		Las bibliotecas de enlace dinámico(Dynamic Link Libraries/DLL) en Windows y los objetos compartidos en Unix son buenos ejemplos de bibliotecas dinámicas.


	Intercambio/Swapping:

		El intercambio es un mecanismo por el cual un proceso puede ser intercambiado temporalmente de la memoria principal (o moverse) al almacenamiento secundario (disco) y poner esa memoria a disposición de otros procesos. 

		Más adelante, el sistema vuelve a intercambiar el proceso desde el almacenamiento secundario a la memoria principal.

		Aunque el rendimiento suele verse afectado por el proceso de intercambio, ayuda a ejecutar múltiples y grandes procesos en paralelo y esa es la razón por la que el intercambio también se conoce como una técnica de compactación de memoria.

		El tiempo total que tarda el proceso de intercambio incluye el tiempo que se tarda en mover todo el proceso a un disco secundario y luego copiar el proceso de nuevo a la memoria, así como el tiempo que el proceso tarda en recuperar la memoria principal.

		Supongamos que el proceso de usuario tiene un tamaño de 2048 KB y que en un disco duro estándar en el que se realizará el intercambio tiene una velocidad de transferencia de datos de alrededor de 1 MB por segundo. 

		La transferencia real del proceso 1000K hacia o desde la memoria tardará

		2048KB / 1024KB por segundo
		= 2 segundos
		= 2000 milisegundos

		Teniendo en cuenta el tiempo de entrada y salida, tardará 4000 milisegundos más otros gastos generales en los que el proceso compite por recuperar la memoria principal.


	Asignación de memoria/Memory Allocation:

		La memoria principal suele tener dos particiones

		    Memoria baja/Low Memory:

		    	El sistema operativo reside en esta memoria.

		    Memoria Alta/High Memory:

		    	Los procesos de usuario se alojan en la memoria alta.

		El sistema operativo utiliza el siguiente mecanismo de asignación de memoria.


		Asignación de partición única/Single-partition allocation:

			En este tipo de asignación, se utiliza el esquema de registro de reubicación para proteger a los procesos de usuario entre sí, y de cambiar el código y los datos del sistema operativo. 

			El registro de reubicación contiene el valor de la dirección física más pequeña, mientras que el registro límite contiene el rango de direcciones lógicas. 

			Cada dirección lógica debe ser menor que el registro límite.


		Asignación de particiones múltiples/Multiple-partition allocation: 

			En este tipo de asignación, la memoria principal se divide en un número de particiones de tamaño fijo donde cada partición debe contener sólo un proceso.

			Cuando una partición está libre, se selecciona un proceso de la cola de entrada y se carga en la partición libre. 

			Cuando el proceso termina, la partición queda disponible para otro proceso.


	Fragmentación

		A medida que los procesos se cargan y se eliminan de la memoria, el espacio de memoria libre se rompe en pequeños trozos. 

		A veces ocurre que los procesos no pueden asignarse a bloques de memoria teniendo en cuenta su pequeño tamaño y los bloques de memoria quedan sin utilizar. 

		Este problema se conoce como Fragmentación.

		Fragmentación externa

			El espacio total de memoria es suficiente para satisfacer una petición o para que resida en él un proceso, pero no es contiguo, por lo que no se puede utilizar.


		Fragmentación interna

			El bloque de memoria asignado a un proceso es mayor. Alguna porción de memoria queda sin utilizar, ya que no puede ser utilizada por otro proceso.


		El siguiente diagrama muestra cómo la fragmentación puede causar un desperdicio de memoria y cómo se puede utilizar una técnica de compactación para crear más memoria libre a partir de la memoria fragmentada.

		La fragmentación externa puede reducirse mediante la compactación o barajando el contenido de la memoria para colocar toda la memoria libre junta en un gran bloque. 

		Para que la compactación sea factible, la reubicación debe ser dinámica.

		La fragmentación interna puede reducirse asignando efectivamente la partición más pequeña pero lo suficientemente grande para el proceso.


	Paginación/Paging

		Un ordenador puede direccionar más memoria que la cantidad físicamente instalada en el sistema. 

		Esta memoria extra se llama en realidad memoria virtual y es una sección de un disco que está configurada para emular la RAM del ordenador. 

		La técnica de paginación juega un papel importante en la implementación de la memoria virtual.

		La paginación es una técnica de gestión de memoria en la que el espacio de direcciones del proceso se divide en bloques del mismo tamaño llamados páginas (el tamaño es potencia de 2, entre 512 bytes y 8192 bytes). 

		El tamaño del proceso se mide en número de páginas.

		Del mismo modo, la memoria principal se divide en pequeños bloques de tamaño fijo de memoria (física) llamados marcos y el tamaño de un marco se mantiene igual que el de una página para tener una utilización óptima de la memoria principal y evitar la fragmentación externa.


	Traducción de direcciones/Address Translation:

		La dirección de página se denomina dirección lógica y está representada por el número de página y el offset.

		Dirección lógica = Número de página + offset de página/Logical Address = Page number + page offset.

		La dirección de trama se denomina dirección física y se representa por un número de trama y el offset.

		Dirección física = Número de trama + desplazamiento de página/Physical Address = Frame number + page offset.

		Una estructura de datos llamada tabla de mapeo de páginas se utiliza para mantener un registro de la relación entre una página de un proceso y un marco en la memoria física.


		Cuando el sistema asigna un marco a cualquier página, traduce esta dirección lógica en una dirección física y crea una entrada en la tabla de páginas que se utilizará durante la ejecución del programa.

		Cuando se va a ejecutar un proceso, sus páginas correspondientes se cargan en cualquier marco de memoria disponible. 

		Supongamos que tenemos un programa de 8Kb pero nuestra memoria sólo puede acomodar 5Kb en un momento dado, entonces el concepto de paginación entrará en escena. 

		Cuando un ordenador se queda sin RAM, el sistema operativo (SO) mueve las páginas de memoria ociosas o no deseadas a la memoria secundaria para liberar RAM para otros procesos y las devuelve cuando el programa las necesita.

		Este proceso continúa durante toda la ejecución del programa en el que el sistema operativo sigue eliminando páginas ociosas de la memoria principal y las escribe en la memoria secundaria y las devuelve cuando el programa las necesita.


		Ventajas y desventajas de la paginación:

		    La paginación reduce la fragmentación externa, pero sigue sufriendo la fragmentación interna.

		    La paginación es simple de implementar y se asume como una técnica eficiente de gestión de memoria.

		    Debido al mismo tamaño de las páginas y los marcos, el intercambio es muy fácil.

		    La tabla de páginas requiere espacio de memoria extra, por lo que puede no ser buena para un sistema con poca RAM.


	Segmentación:

		La segmentación es una técnica de gestión de memoria en la que cada trabajo se divide en varios segmentos de diferentes tamaños, uno para cada módulo que contiene piezas que realizan funciones relacionadas. 

		Cada segmento es en realidad un espacio de direcciones lógicas diferente del programa.

		Cuando se va a ejecutar un proceso, sus segmentaciones correspondientes se cargan en memoria no contigua, aunque cada segmento se carga en un bloque contiguo de la memoria disponible.

		La gestión de la memoria de segmentación funciona de forma muy similar a la paginación, pero en este caso los segmentos son de longitud variable, mientras que en la paginación las páginas son de tamaño fijo.

		Un segmento de programa contiene la función principal del programa, funciones de utilidad, estructuras de datos, etc. 

		El sistema operativo mantiene una tabla de asignación de segmentos para cada proceso y una lista de bloques de memoria libres junto con los números de segmento, su tamaño y las posiciones de memoria correspondientes en la memoria principal. 

		Para cada segmento, la tabla almacena la dirección de inicio del segmento y la longitud del segmento. 

		Una referencia a una posición de memoria incluye un valor que identifica un segmento y un offset.



|| Memoria Virtual/Virtual Memory
	
	Un ordenador puede direccionar más memoria que la cantidad instalada físicamente en el sistema. 

	Esta memoria extra se llama en realidad memoria virtual y es una sección del disco duro configurada para emular la memoria RAM del ordenador.

	La principal ventaja visible de este esquema es que los programas pueden ser más grandes que la memoria física. 

	La memoria virtual sirve para dos cosas. 

	En primer lugar, nos permite ampliar el uso de la memoria física mediante el disco. 

	Segundo, nos permite tener protección de memoria, porque cada dirección virtual es traducida a una dirección física.

	A continuación se presentan las situaciones en las que no es necesario cargar todo el programa en la memoria principal.

	    Las rutinas de tratamiento de errores escritas por el usuario se utilizan sólo cuando se produce un error en los datos o en el cálculo.

	    Ciertas opciones y características de un programa pueden utilizarse raramente.

	    A muchas tablas se les asigna una cantidad fija de espacio de direcciones aunque en realidad sólo se utilice una pequeña parte de la tabla.

	    La capacidad de ejecutar un programa que sólo está parcialmente en memoria contrarrestaría muchos beneficios.

	    Se necesitaría un menor número de E/S para cargar o intercambiar cada programa de usuario en memoria.

	    Un programa ya no estaría limitado por la cantidad de memoria física disponible.

	    Cada programa de usuario podría ocupar menos memoria física, se podrían ejecutar más programas al mismo tiempo, con el correspondiente aumento de la utilización de la CPU y del rendimiento.

		En los microprocesadores modernos destinados a un uso general, el hardware lleva incorporada una unidad de gestión de memoria (memory management unit), o MMU. 

		El trabajo de la MMU consiste en traducir las direcciones virtuales en direcciones físicas. A continuación se ofrece un ejemplo básico

		La memoria virtual se suele implementar mediante paginación por demanda. 

		También puede implementarse en un sistema de segmentación. 

		La segmentación por demanda también puede utilizarse para proporcionar memoria virtual.


	Paginación bajo demanda/Demand Paging:

		Un sistema de paginación bajo demanda es bastante similar a un sistema de paginación con intercambio en el que los procesos residen en la memoria secundaria y las páginas se cargan sólo bajo demanda, no por adelantado. 

		Cuando se produce un cambio de contexto, el sistema operativo no copia ninguna de las páginas del programa anterior en el disco ni ninguna de las páginas del nuevo programa en la memoria principal.

		En su lugar, simplemente comienza a ejecutar el nuevo programa después de cargar la primera página y obtiene las páginas de ese programa a medida que son referenciadas.

		Mientras se ejecuta un programa, si el programa hace referencia a una página que no está disponible en la memoria principal porque se ha intercambiado hace poco, el procesador trata esta referencia de memoria no válida como un fallo de página (Page Fault) y transfiere el control del programa al sistema operativo para solicitar que la página vuelva a la memoria.

		Ventajas:

		    Amplia memoria virtual.
		    Uso más eficiente de la memoria.
		    No hay límite en el grado de multiprogramación.


		Desventajas:

		    El número de tablas y la sobrecarga del procesador para gestionar las interrupciones de página son mayores que en el caso de las técnicas simples de gestión de paginación.


	Algoritmo de sustitución de páginas/Page Replacement Algorithm:

		Los algoritmos de reemplazo de páginas son las técnicas mediante las cuales un sistema operativo decide qué páginas de memoria intercambiar o escribir en disco cuando es necesario asignar una página de memoria. 

		El cambio de páginas se produce cuando se produce un fallo de página y no se puede utilizar una página libre para la asignación debido a que no hay páginas disponibles o a que el número de páginas libres es inferior al de páginas necesarias.

		Cuando la página que fue seleccionada para ser reemplazada y paginada, es referenciada de nuevo, tiene que ser leída desde el disco, y esto requiere que la E/S se complete. 

		Este proceso determina la calidad del algoritmo de reemplazo de páginas: 

			cuanto menor sea el tiempo de espera de paginación, mejor será el algoritmo.

		Un algoritmo de reemplazo de páginas mira la información limitada sobre el acceso a las páginas proporcionada por el hardware, e intenta seleccionar qué páginas deben ser reemplazadas para minimizar el número total de páginas perdidas, mientras lo equilibra con los costes de almacenamiento primario y tiempo de procesador del propio algoritmo. 

		Existen muchos algoritmos diferentes de sustitución de páginas. 

		Evaluamos un algoritmo ejecutándolo en una cadena determinada de referencias de memoria y calculando el número de fallos de página.


	Cadena de referencias/Reference String:

		La cadena de referencias de memoria se denomina cadena de referencias. 

		Las cadenas de referencias se generan artificialmente o rastreando un sistema determinado y registrando la dirección de cada referencia de memoria. 

		Esta última opción produce un gran número de datos, donde observamos dos cosas.

		    Para un tamaño de página dado, tenemos que considerar sólo el número de página, no la dirección completa.

		    Si tenemos una referencia a una página p, entonces cualquier referencia inmediatamente siguiente a la página p nunca causará un fallo de página. 

		    La página p estará en memoria después de la primera referencia; las referencias inmediatamente siguientes no producirán fallos.

		    Por ejemplo, considere la siguiente secuencia de direcciones - 123,215,600,1234,76,96

		    Si el tamaño de página es 100, entonces la cadena de referencia es 1,2,6,12,0,0


	Algoritmo FIFO/First In First Out (FIFO) algorithm (primero en entrar, primero en salir):

	    La página más antigua de la memoria principal es la que se selecciona para ser reemplazada.

	    Fácil de implementar, mantenga una lista, reemplace las páginas de la cola y añada nuevas páginas en la cabecera.


	Algoritmo de página óptima/Optimal Page algorithm:

	    Un algoritmo de sustitución de páginas óptimo tiene la tasa de fallos de página más baja de todos los algoritmos. 

	    Existe un algoritmo de sustitución de páginas óptimo, que se denomina OPT o MIN.

	    Sustituye la página que no se va a utilizar durante más tiempo.

	    Utilizar el tiempo en el que se va a utilizar una página.


	Algoritmo de uso menos reciente (LRU)/Least Recently Used (LRU) algorithm:

    	La página que no se ha utilizado durante más tiempo en la memoria principal es la que se seleccionará para su sustitución.

    	Fácil de implementar, mantiene una lista, reemplaza las páginas mirando hacia atrás en el tiempo.


	Algoritmo de búfer de página/Page Buffering algorithm:

	    Para que un proceso arranque rápidamente, mantenga un pool de frames libres.

	    En caso de fallo de página, seleccione una página para reemplazarla.

	    Escriba la nueva página en el marco del pool libre, marque la tabla de páginas y reinicie el proceso.

	    Ahora escriba la página sucia fuera del disco y coloque el marco que contiene la página reemplazada en el pool libre.


	Algoritmo de uso menos frecuente (LFU)/Least frequently Used(LFU) algorithm:

	    La página con el recuento más pequeño es la que se seleccionará para la sustitución.

	    Este algoritmo sufre la situación en la que una página se utiliza mucho durante la fase inicial de un proceso, pero luego no se vuelve a utilizar.


	Algoritmo de uso más frecuente (MFU)/Most frequently Used(MFU) algorithm:

	    Este algoritmo se basa en el argumento de que la página con el recuento más bajo probablemente se acaba de introducir y aún no se ha utilizado.



|| I/O Hardware (entrada y salida):

	Una de las tareas más importantes de un sistema operativo es gestionar varios dispositivos de E/S, como ratones, teclados, touchpads, unidades de disco, adaptadores de pantalla, dispositivos USB, pantallas con mapa de bits, LED, convertidores analógico-digitales, interruptores de encendido/apagado, conexiones de red, E/S de audio, impresoras, etc.

	Un sistema de E/S es requerido para tomar una solicitud de E/S de una aplicación y enviarla al dispositivo físico, luego tomar cualquier respuesta que regrese del dispositivo y enviarla a la aplicación. 

	Los dispositivos de E/S pueden dividirse en dos categorías:

	    Dispositivos de bloque (Block devices):

	    	Un dispositivo de bloque es aquel con el que el controlador se comunica enviando bloques enteros de datos. Por ejemplo, discos duros, cámaras USB, Disk-On-Key, etc.

	    Dispositivos de caracteres (Character devices):

	    	Un dispositivo de caracteres es aquel con el que el controlador se comunica enviando y recibiendo caracteres individuales (bytes, octetos). Por ejemplo, puertos serie, puertos paralelos, tarjetas de sonido, etc.


	Controladores de dispositivos/Device Controllers

		Los controladores de dispositivos son módulos de software que se pueden conectar a un sistema operativo para manejar un dispositivo en particular. 

		El sistema operativo se ayuda de los controladores de dispositivos para manejar todos los dispositivos de E/S.

		El controlador de dispositivo funciona como una interfaz entre un dispositivo y un controlador de dispositivo. 

		Las unidades de E/S (teclado, ratón, impresora, etc.) suelen constar de un componente mecánico y un componente electrónico, donde el componente electrónico se denomina controlador de dispositivo.

		Siempre hay un controlador de dispositivo y un controlador de dispositivo para que cada dispositivo se comunique con los sistemas operativos. 

		Un controlador de dispositivos puede gestionar varios dispositivos. 

		Como interfaz, su tarea principal es convertir el flujo de bits serie en bloques de bytes y realizar la corrección de errores necesaria.

		Cualquier dispositivo conectado al ordenador se conecta mediante una clavija y una toma, y la toma se conecta a un controlador de dispositivos. 

		A continuación se muestra un modelo para conectar la CPU, la memoria, los controladores y los dispositivos de E/S en el que la CPU y los controladores de dispositivos utilizan un bus común para la comunicación.


	E/S síncrona vs. asíncrona/Synchronous vs asynchronous I/O:

    	E/S síncrona: 

    		En este esquema la ejecución de la CPU espera mientras la E/S procede

    	E/S asíncrona: 

    		la E/S se ejecuta simultáneamente a la ejecución de la CPU.


	Comunicación con los dispositivos de E/S (Communication to I/O Devices):

		La CPU debe tener una forma de pasar información hacia y desde un dispositivo de E/S. 

		Hay tres enfoques disponibles para comunicarse con la CPU y el dispositivo:

		    E/S de instrucción especial.

		    E/S mapeada en memoria.

		    Acceso directo a memoria (DMA).


	E/S con instrucciones especiales/Special Instruction I/O:

		Utiliza instrucciones de la CPU específicamente diseñadas para controlar dispositivos de E/S.

		Estas instrucciones normalmente permiten enviar datos a un dispositivo de E/S o leerlos de un dispositivo de E/S.


	E/S asignada a memoria/Memory-mapped I/O:

		Cuando se utiliza la E/S mapeada en memoria, la memoria y los dispositivos de E/S comparten el mismo espacio de direcciones. 

		El dispositivo se conecta directamente a ciertas ubicaciones de memoria principal para que el dispositivo de E/S pueda transferir bloques de datos a/desde la memoria sin pasar por la CPU.

		Cuando se utiliza E/S mapeada en memoria, el SO asigna un buffer en memoria e informa al dispositivo de E/S que utilice ese buffer para enviar datos a la CPU. 

		El dispositivo de E/S opera de forma asíncrona con la CPU e interrumpe a la CPU cuando termina.

		La ventaja de este método es que cualquier instrucción que pueda acceder a la memoria puede ser utilizada para manipular un dispositivo de E/S. 

		La E/S mapeada en memoria se utiliza para la mayoría de los dispositivos de E/S de alta velocidad como discos, interfaces de comunicación.


	Acceso directo a memoria (DMA):

		Los dispositivos lentos, como los teclados, generan una interrupción a la CPU principal después de transferir cada byte.

		Si un dispositivo rápido como un disco generara una interrupción por cada byte, el sistema operativo pasaría la mayor parte de su tiempo gestionando estas interrupciones. 

		Por eso, un ordenador típico utiliza hardware de acceso directo a memoria (DMA) para reducir esta sobrecarga.

		Acceso Directo a Memoria (DMA) significa que la CPU concede al módulo de E/S autoridad para leer o escribir en memoria sin intervención. 

		El propio módulo DMA controla el intercambio de datos entre la memoria principal y el dispositivo de E/S. 

		La CPU sólo interviene al principio y al final del proceso.

		La CPU sólo interviene al principio y al final de la transferencia y sólo se interrumpe cuando se ha transferido el bloque completo.

		El Acceso Directo a Memoria necesita un hardware especial llamado controlador DMA (DMAC) que gestiona las transferencias de datos y arbitra el acceso al bus del sistema. 

		Los controladores se programan con punteros de origen y destino (dónde leer/escribir los datos), contadores para realizar un seguimiento del número de bytes transferidos y configuraciones, que incluyen tipos de E/S y memoria, interrupciones y estados para los ciclos de la CPU.


		1. Se ordena al controlador del dispositivo que transfiera los datos del disco a una dirección X del búfer.

		2. A continuación, el controlador del dispositivo ordena a la controladora del disco que transfiera los datos a la memoria intermedia.

		3. El controlador de disco inicia la transferencia DMA.

		4. El controlador de disco envía cada byte al controlador DMA.

		5. El controlador DMA transfiere los bytes al búfer, aumenta la dirección de memoria y disminuye el contador C hasta que C se convierte en cero.

		6. Cuando C se convierte en cero, la DMA interrumpe a la CPU para señalar la finalización de la transferencia.


	Polling vs Interrupciones E/S (Polling vs Interrupts I/O):

		Un ordenador debe tener una forma de detectar la llegada de cualquier tipo de entrada.

		Existen dos formas de hacerlo, conocidas como sondeo e interrupciones. 

		Ambas técnicas permiten al procesador hacer frente a eventos que pueden ocurrir en cualquier momento y que no están relacionados con el proceso que está ejecutando en ese momento.


	Sondeo de E/S:

		El sondeo es la forma más sencilla de que un dispositivo de E/S se comunique con el procesador. 

		El proceso de verificar periódicamente el estado del dispositivo para ver si es tiempo de la siguiente operación de E/S, se llama sondeo. 

		El dispositivo de E/S simplemente pone la información en un registro de Estado, y el procesador debe venir y obtener la información.

		La mayoría de las veces, los dispositivos no requerirán atención y cuando uno lo haga tendrá que esperar hasta que sea interrogado de nuevo por el programa de sondeo. 

		Este es un método ineficiente y gran parte del tiempo del procesador se pierde en sondeos innecesarios.

		Compare este método con el de un profesor que pregunta continuamente a todos los alumnos de una clase, uno tras otro, si necesitan ayuda. 

		Obviamente, el método más eficiente sería que un alumno informara al profesor siempre que necesitara ayuda.


	Interrupciones E/S (Interrupts I/O):

		Un esquema alternativo para tratar las E/S es el método basado en interrupciones. 

		Una interrupción es una señal al microprocesador desde un dispositivo que requiere atención.

		Un controlador de dispositivo pone una señal de interrupción en el bus cuando necesita la atención de la CPU cuando la CPU recibe una interrupción, Guarda su estado actual e invoca al manejador de interrupción apropiado usando el vector de interrupción (direcciones de rutinas del SO para manejar varios eventos). 

		Cuando el dispositivo que interrumpe ha sido atendido, la CPU continúa con su tarea original como si nunca hubiera sido interrumpida.		



|| Programas de E/S (I/O Softwares):
	
	El software de E/S suele organizarse en los siguientes niveles.

    Bibliotecas de nivel de usuario/User Level Libraries:

    	Esto proporciona una interfaz sencilla al programa de usuario para realizar la entrada y salida. 

    	Por ejemplo, stdio es una librería proporcionada por los lenguajes de programación C y C++.


	Módulos de Nivel de Kernel/Kernel Level Modules:

		Esto proporciona al controlador de dispositivo interactuar con el controlador de dispositivo y los módulos de E/S independientes del dispositivo utilizados por los controladores de dispositivo.

	Hardware:

		Esta capa incluye el hardware real y el controlador de hardware que interactúa con los controladores de dispositivos y hace que el hardware esté vivo.


	Un concepto clave en el diseño de software de E/S es que debe ser independiente del dispositivo donde debe ser posible escribir programas que puedan acceder a cualquier dispositivo de E/S sin tener que especificar el dispositivo de antemano. 

	Por ejemplo, un programa que lee un archivo como entrada debe ser capaz de leer un archivo en un disquete, en un disco duro o en un CD-ROM, sin tener que modificar el programa para cada dispositivo diferente.


	Controladores de dispositivos/Device Drivers:

		Los controladores de dispositivos son módulos de software que pueden conectarse a un sistema operativo para gestionar un dispositivo concreto. 

		El sistema operativo se ayuda de los controladores de dispositivos para gestionar todos los dispositivos de E/S. 

		Los controladores de dispositivos encapsulan el código dependiente del dispositivo e implementan una interfaz estándar de tal manera que el código contiene lecturas/escrituras de registros específicos del dispositivo. 

		El controlador de dispositivo suele ser escrito por el fabricante del dispositivo y se entrega junto con éste en un CD-ROM.

		Un controlador de dispositivo realiza las siguientes tareas

		    Aceptar la solicitud del software independiente del dispositivo por encima de él.

		    Interactuar con el controlador del dispositivo para tomar y dar E/S y realizar la gestión de errores requerida.

		    Asegurarse de que la solicitud se ejecuta correctamente.


		Cómo un controlador de dispositivo maneja una solicitud es como sigue: 

			Supongamos que llega una solicitud para leer un bloque N. 

			Si el controlador está inactivo en el momento en que llega una solicitud, comienza a llevarla a cabo inmediatamente.

			De lo contrario, si el controlador ya está ocupado con alguna otra solicitud, coloca la nueva solicitud en la cola de solicitudes pendientes.


	Manejadores de interrupciones/Interrupt handlers

		Un gestor de interrupciones, también conocido como rutina de servicio de interrupciones/interrupt service routine (ISR), es una pieza de software o, más concretamente, una función de devolución de llamada en un sistema operativo o, más específicamente, en un controlador de dispositivo, cuya ejecución se desencadena por la recepción de una interrupción.

		Cuando se produce la interrupción, el procedimiento de interrupción hace lo que tiene que hacer para gestionar la interrupción, actualiza las estructuras de datos y despierta el proceso que estaba esperando que se produjera una interrupción.

		El mecanismo de interrupción acepta una dirección ─ un número que selecciona una rutina/función específica de gestión de interrupciones de entre un pequeño conjunto. En la mayoría de las arquitecturas, esta dirección es un offset almacenado en una tabla llamada tabla de vectores de interrupción. Este vector contiene las direcciones de memoria de los gestores de interrupciones especializados.


	Software de E/S independiente del dispositivo/Device-Independent I/O Software:

		La función básica del software independiente del dispositivo es realizar las funciones de E/S que son comunes a todos los dispositivos y proporcionar una interfaz uniforme al software de nivel de usuario. 

		Aunque es difícil escribir software completamente independiente del dispositivo, podemos escribir algunos módulos que son comunes entre todos los dispositivos. 

		La siguiente es una lista de funciones de Software de E/S independiente del dispositivo: 

		    Interfaz uniforme para los controladores de dispositivos.

		    Nomenclatura de dispositivos:

		    	Nombres mnemotécnicos asignados a los números de dispositivo Mayor y Menor.

		    Protección de dispositivos.

		    Proporcionar un tamaño de bloque independiente del dispositivo.

		    Almacenamiento en búfer porque los datos que salen de un dispositivo no pueden almacenarse en el destino final.

		    Asignación de almacenamiento en dispositivos de bloque.

		    Asignación y liberación de dispositivos dedicados.

		    Notificación de errores


	Software de E/S para el espacio de usuario/User-Space I/O Software:

		Son las bibliotecas que proporcionan una interfaz más rica y simplificada para acceder a la funcionalidad del núcleo o, en última instancia, interactiva con los controladores de dispositivos. 

		La mayoría del software de E/S a nivel de usuario consiste en procedimientos de librería con alguna excepción como el sistema spooling que es una forma de tratar con dispositivos de E/S dedicados en un sistema multiprogramación.

		Las librerías de E/S (por ejemplo, stdio) están en el espacio de usuario para proporcionar una interfaz al SW de E/S independiente del dispositivo residente en el SO.

		Por ejemplo putchar(), getchar(), printf() y scanf() son ejemplos de librerías stdio de E/S a nivel de usuario disponibles en programación C.	    


	Subsistema de E/S del núcleo/Kernel I/O Subsystem:

		El Subsistema de E/S del Kernel es responsable de proporcionar muchos servicios relacionados con la E/S. 

		A continuación se enumeran algunos de los servicios prestados:

	    Programación:

	    	El Kernel programa un conjunto de peticiones de E/S para determinar un buen orden en el que ejecutarlas. 

	    	Cuando una aplicación emite una llamada al sistema de E/S bloqueante, la petición se coloca en la cola para ese dispositivo.

	    	El programador de E/S del Kernel reorganiza el orden de la cola para mejorar la eficiencia global del sistema y el tiempo medio de respuesta experimentado por las aplicaciones.


	    Buffering:

	    	El Subsistema de E/S del Kernel mantiene un área de memoria conocida como buffer que almacena datos mientras son transferidos entre dos dispositivos o entre un dispositivo con una operación de aplicación. 

	    	El almacenamiento en búfer se realiza para hacer frente a un desajuste de velocidad entre el productor y el consumidor de un flujo de datos o para adaptarse entre dispositivos que tienen diferentes tamaños de transferencia de datos.


	    Caché:

	    	El núcleo mantiene una memoria caché que es una región de memoria rápida que contiene copias de datos. 

	    	El acceso a la copia en caché es más eficiente que el acceso al original.


	    Spooling y reserva de dispositivos:

	    	Un spool es un búfer que almacena la salida de un dispositivo, como una impresora, que no puede aceptar flujos de datos intercalados.

	    	El sistema de spooling copia los archivos de spool en cola a la impresora de uno en uno.

			En algunos sistemas operativos, la cola de impresión es gestionada por un proceso demonio del sistema. 

			En otros sistemas operativos, es gestionado por un hilo del núcleo.


|| Sistema de archivos/File System:
	
	Archivo/File:

		Un archivo es una colección con nombre de información relacionada que se graba en un almacenamiento secundario como un disco magnético, una cinta magnética o un disco óptico. 

		En general, un archivo es una secuencia de bits, bytes, líneas o registros cuyo significado lo definen el creador y el usuario del archivo.


	Estructura de los ficheros/File Structure:

		La estructura de un fichero debe ajustarse a un formato requerido que el sistema operativo pueda comprender.

		    Un fichero tiene una estructura definida en función de su tipo.

		    Un fichero de texto es una secuencia de caracteres organizados en líneas.

		    Un fichero fuente es una secuencia de procedimientos y funciones.

		    Un fichero objeto es una secuencia de bytes organizados en bloques comprensibles por la máquina.

		    Cuando el sistema operativo define diferentes estructuras de archivos, también contiene el código para soportar estas estructuras de archivos. 

		    Unix y MS-DOS admiten un número mínimo de estructuras de archivos.


	Tipo de archivo/File Type: 

		El tipo de archivo hace referencia a la capacidad del sistema operativo para distinguir diferentes tipos de archivos, como archivos de texto, archivos fuente, archivos binarios, etc.

		Muchos sistemas operativos admiten muchos tipos de archivos. Los sistemas operativos como MS-DOS y UNIX tienen los siguientes tipos de archivos


		Ficheros ordinarios/Ordinary files:

		    Son los archivos que contienen información del usuario.

		    Pueden contener texto, bases de datos o programas ejecutables.

		    El usuario puede realizar varias operaciones en estos archivos, como añadir, modificar, borrar o incluso eliminar el archivo completo.


		Archivos de directorio/Directory files:

		    Estos archivos contienen una lista de nombres de archivos y otra información relacionada con estos archivos.


		Archivos especiales/Special files:

		    Estos archivos también se conocen como archivos de dispositivo.

		    Estos archivos representan dispositivos físicos como discos, terminales, impresoras, redes, unidades de cinta, etc.


		Estos archivos son de dos tipos:

		    Ficheros especiales de caracteres/Character special files: 

		    	los datos se tratan carácter por carácter, como en el caso de los terminales o las impresoras.


		    Archivos especiales de bloque/Block special files: 

		    	los datos se manejan en bloques, como en el caso de los discos y las cintas.


	Mecanismos de acceso a los ficheros/File Access Mechanisms:

		El mecanismo de acceso a los ficheros se refiere a la forma en que se puede acceder a los registros de un fichero. 

		Existen varias formas de acceder a los ficheros:

		    Acceso secuencial.

		    Acceso directo/aleatorio.

		    Acceso secuencial indexado.


		Acceso secuencial/Sequential access:

			Un acceso secuencial es aquel en el que se accede a los registros en alguna secuencia, es decir, la información del fichero se procesa en orden, un registro tras otro. 

			Este método de acceso es el más primitivo. 

			Por ejemplo: Los compiladores suelen acceder a los ficheros de este modo.


		Acceso directo/aleatorio (Direct/Random access):

		    La organización de archivos de acceso aleatorio permite acceder directamente a los registros.

		    Cada registro tiene su propia dirección en el archivo con la ayuda de la cual se puede acceder directamente para leer o escribir.

		    No es necesario que los registros estén en secuencia dentro del archivo ni que se encuentren en ubicaciones adyacentes en el medio de almacenamiento.


		Acceso secuencial indexado/Indexed sequential access:

		    Este mecanismo se basa en el acceso secuencial.

		    Se crea un índice para cada fichero que contiene punteros a varios bloques.

		    El índice se busca secuencialmente y su puntero se utiliza para acceder directamente al fichero.


	Asignación de espacio/Space Allocation:

		El sistema operativo asigna espacio en disco a los archivos.

		Los sistemas operativos utilizan tres formas principales para asignar espacio de disco a los archivos.

		    Asignación contigua.

		    Asignación vinculada.

		    Asignación indexada.

		    Contiguous, Linked, Indexed/Allocation.


		Asignación contigua

		    Cada archivo ocupa un espacio de dirección contiguo en el disco.

		    Las direcciones de disco asignadas siguen un orden lineal.

		    Fácil de implementar.

		    La fragmentación externa es un problema importante con este tipo de técnica de asignación.


		Asignación vinculada

		    Cada archivo contiene una lista de enlaces a bloques de disco.

		    El directorio contiene el enlace / puntero al primer bloque de un archivo.

		    Sin fragmentación externa
		    Eficaz en caso de archivo de acceso secuencial.

		    Ineficiente en caso de archivo de acceso directo.


		Asignación indexada

		    Proporciona soluciones a los problemas de asignación contigua y vinculada.

		    Se crea un bloque índice que contiene todos los punteros a los ficheros.

		    Cada archivo tiene su propio bloque de índice que almacena las direcciones del espacio de disco ocupado por el archivo.

		    El directorio contiene las direcciones de los bloques de índice de los archivos.



|| Seguridad en el Sistema Operativo/OS Security

	La seguridad se refiere a proporcionar un sistema de protección a los recursos del sistema informático, como la CPU, la memoria, el disco, los programas de software y, lo que es más importante, los datos/información almacenados en el sistema informático. 

	Si un usuario no autorizado ejecuta un programa informático, puede causar graves daños al ordenador o a los datos almacenados en él. 

	Por lo tanto, un sistema informático debe estar protegido contra accesos no autorizados, accesos maliciosos a la memoria del sistema, virus, gusanos, etc. 

	En este capítulo vamos a tratar los siguientes temas.

	    Autenticación.

	    Contraseñas de un solo uso.

	    Amenazas de programa.

	    Amenazas al sistema.

	    Clasificaciones de seguridad informática.


	Autenticación/Authentication

		La autenticación se refiere a la identificación de cada usuario del sistema y a la asociación de los programas en ejecución con dichos usuarios. 

		Es responsabilidad del Sistema Operativo crear un sistema de protección que garantice que el usuario que ejecuta un determinado programa es auténtico. 

		Los Sistemas Operativos generalmente identifican/autentican a los usuarios usando las siguientes tres formas:

		    Nombre de usuario / Contraseña:

		    	El usuario necesita introducir un nombre de usuario y una contraseña registrados en el sistema operativo para iniciar sesión en el sistema.


		    Tarjeta/llave de usuario: 

		    	El usuario debe introducir una tarjeta en la ranura o una llave generada por un generador de llaves en la opción proporcionada por el sistema operativo para iniciar sesión en el sistema.


		    Atributos del usuario (huella dactilar, patrón retiniano, firma): 

		    	El usuario debe introducir sus atributos a través del dispositivo de entrada designado utilizado por el sistema operativo para iniciar sesión en el sistema.


	Contraseñas de un solo uso/One Time passwords:

		Las contraseñas de un solo uso proporcionan seguridad adicional junto con la autenticación normal. 

		En el sistema de contraseñas de un solo uso, se requiere una contraseña única cada vez que el usuario intenta iniciar sesión en el sistema. 

		Una vez que se utiliza una contraseña de un solo uso, no se puede volver a utilizar. 

		Las contraseñas de un solo uso se implementan de varias formas.

		    Números aleatorios: 

		    	los usuarios reciben tarjetas con números impresos junto con los alfabetos correspondientes. 

		    	El sistema pide los números correspondientes a unos cuantos alfabetos elegidos al azar.


		    Clave secreta: 

		    	se proporciona al usuario un dispositivo de hardware que puede crear una identificación secreta asociada a la identificación del usuario. 

		    	El sistema solicita dicha clave secreta, que debe generarse cada vez antes del inicio de sesión.


		    Contraseña de red: 

		    	algunas aplicaciones comerciales envían contraseñas de un solo uso al usuario a través del móvil/correo electrónico registrado, que debe introducir antes de iniciar sesión.


	Amenazas del programa/Program Threats:

		Los procesos del sistema operativo y el kernel realizan la tarea designada según las instrucciones. 

		Si un programa de usuario hace que estos procesos realicen tareas maliciosas, entonces se conoce como Amenazas de Programa.

		Uno de los ejemplos más comunes de amenaza de programa es un programa instalado en un ordenador que puede almacenar y enviar credenciales de usuario a través de la red a algún hacker.

		A continuación se enumeran algunas amenazas de programa muy conocidas.

		    Caballo de Troya/Trojan Horse:

		    	Este tipo de programa atrapa las credenciales de inicio de sesión del usuario y las almacena para enviarlas a un usuario malintencionado que posteriormente puede iniciar sesión en el ordenador y acceder a los recursos del sistema.


		    Trampilla/Trap Door:

		    	Si un programa que está diseñado para trabajar como se requiere, tiene un agujero de seguridad en su código y realiza una acción ilegal sin el conocimiento del usuario, entonces se le llama trampilla.


		    Bomba lógica/Logic Bomb:

		    	Una bomba lógica es una situación en la que un programa se comporta mal sólo cuando se cumplen ciertas condiciones, de lo contrario funciona como un programa genuino. Es más difícil de detectar.


		    Virus:

		    	Como su nombre indica, los virus pueden replicarse en el sistema informático. 

		    	Son muy peligrosos y pueden modificar/borrar archivos de usuario y bloquear sistemas. 

		    	Un virus es generalmente un pequeño código incrustado en un programa. 

		    	A medida que el usuario accede al programa, el virus comienza a incrustarse en otros archivos/programas y puede hacer que el sistema sea inutilizable para el usuario.


	Amenazas al sistema/System Threats:

		Las amenazas del sistema se refieren al mal uso de los servicios del sistema y las conexiones de red para poner al usuario en problemas. 

		Las amenazas del sistema se pueden utilizar para lanzar amenazas de programa en una red completa denominada ataque de programa. 

		Las amenazas del sistema crean un entorno en el que se hace un uso indebido de los recursos del sistema operativo y de los archivos de usuario. 

		A continuación se muestra la lista de algunas amenazas del sistema bien conocidos:

		    Gusano/Worm:

		    	El gusano es un proceso que puede ahogar el rendimiento de un sistema mediante el uso de los recursos del sistema a niveles extremos. 

		    	Un proceso Gusano genera sus múltiples copias donde cada copia utiliza los recursos del sistema, impide que todos los demás procesos para obtener los recursos necesarios. 

		    	Los procesos de gusanos pueden incluso apagar una red entera.


		    Escaneo de puertos/Port Scanning:

		    	El escaneo de puertos es un mecanismo o medio por el cual un hacker puede detectar vulnerabilidades del sistema para realizar un ataque al mismo.


		    Denegación de servicio/Denial of Service:

		    	Los ataques de denegación de servicio normalmente impiden al usuario hacer un uso legítimo del sistema. 

		    	Por ejemplo, es posible que un usuario no pueda utilizar Internet si la denegación de servicio ataca la configuración de contenido del navegador.


	Clasificaciones de seguridad informática/:

		Según los Criterios de Evaluación de Sistemas Informáticos de Confianza del Departamento de Defensa de EE.UU. (U.S. Department of Defense Trusted Computer System's Evaluation Criteria), existen cuatro clasificaciones de seguridad en los sistemas informáticos: A, B, C y D. 

		Se trata de especificaciones ampliamente utilizadas para determinar y modelar la seguridad de los sistemas y de las soluciones de seguridad. 


		1. Tipo A:

			Nivel más alto:

				Utiliza especificaciones formales de diseño y técnicas de verificación.

				Otorga un alto grado de garantía de la seguridad del proceso.


		2. Tipo B:

			Proporciona un sistema de protección obligatorio. Tiene todas las propiedades de un sistema de clase C2. 

			Adjunta una etiqueta de sensibilidad a cada objeto. Es de tres tipos.

		    B1:

		    	Mantiene la etiqueta de seguridad de cada objeto del sistema. 

		    	La etiqueta se utiliza para tomar decisiones de control de acceso.


		    B2:
		    	Extiende las etiquetas de sensibilidad a cada recurso del sistema, como objetos de almacenamiento, soporta canales encubiertos y auditoría de eventos.


		    B3:
		    	Permite crear listas o grupos de usuarios para el control de acceso para conceder acceso o revocar el acceso a un objeto con nombre determinado.


		3. Tipo C

			Proporciona protección y responsabilidad del usuario mediante capacidades de auditoría. 

			Es de dos tipos:

		    C1:

		    	Incorpora controles para que los usuarios puedan proteger su información privada y evitar que otros usuarios lean/borren accidentalmente sus datos. 

		    	Las versiones UNIX son mayoritariamente de tipo Cl.


		    C2:
		    	Añade un control de acceso de nivel individual a las capacidades de un sistema de nivel Cl.


		4. Tipo D:

			Nivel más bajo. 

			Protección mínima. 

			MS-DOS, Window 3.1 entran en esta categoría.



|| Linux

	Linux es una de las versiones más populares del sistema operativo UNIX. Es de código abierto, ya que su código fuente está disponible libremente. 

	Su uso es gratuito. 

	Linux se diseñó teniendo en cuenta la compatibilidad con UNIX. 

	Su lista de funcionalidades es bastante similar a la de UNIX.

	
	Componentes del sistema Linux:

		El sistema operativo Linux tiene principalmente tres componentes

	    Kernel:

	    	Kernel es la parte central de Linux. 

	    	Es responsable de todas las actividades principales de este sistema operativo. 

	    	Consta de varios módulos e interactúa directamente con el hardware subyacente. 

	    	El núcleo proporciona la abstracción necesaria para ocultar los detalles de hardware de bajo nivel al sistema o a los programas de aplicación.


	    Librería del Sistema:

	    	Las librerías del sistema son funciones o programas especiales mediante los cuales los programas de aplicación o las utilidades del sistema acceden a las características del Kernel. 

	    	Estas bibliotecas implementan la mayoría de las funcionalidades del sistema operativo y no requieren derechos de acceso al código del módulo del núcleo.


	    Utilidad del Sistema:

	    	Los programas de Utilidad del Sistema son responsables de realizar tareas especializadas a nivel individual.


	Diagrama de Linux: 	

		Los módulos del sistema operatativo como el software del sistema, los procesos de los usuarios, las utilidades del usuario y los compiladores (system software, user process, user utility, compilers) se cargan sobre las librerias del sistema, el kernel y los módulos del kernel que interactúan con el hardware del ordenador (CPU, RAM, puertos E/S). 


	Modo Kernel vs Modo Usuario/Kernel Mode vs User Mode:

		El código del componente kernel se ejecuta en un modo privilegiado especial llamado modo kernel con acceso completo a todos los recursos del ordenador.

		Este código representa un único proceso, se ejecuta en un único espacio de direcciones y no requiere ningún cambio de contexto, por lo que es muy eficiente y rápido. 

		El núcleo ejecuta cada proceso y proporciona servicios de sistema a los procesos, proporciona acceso protegido al hardware a los procesos.

		El código de soporte que no es necesario ejecutar en modo kernel se encuentra en la biblioteca del sistema. 

		Los programas de usuario y otros programas del sistema funcionan en Modo Usuario, que no tiene acceso al hardware del sistema ni al código del núcleo. 

		Los programas de usuario/utilidades utilizan las bibliotecas del sistema para acceder a las funciones del núcleo y realizar tareas de bajo nivel del sistema.


	Características básicas:

		Las siguientes son algunas de las características importantes del sistema operativo Linux.

	    Portable:

	    	Portabilidad significa que el software puede funcionar en diferentes tipos de hardware de la misma manera. 

	    	El núcleo Linux y los programas de aplicación soportan su instalación en cualquier tipo de plataforma de hardware.


	    Código abierto:

	    	El código fuente de Linux está disponible gratuitamente y es un proyecto de desarrollo basado en la comunidad.

	    	Múltiples equipos trabajan en colaboración para mejorar la capacidad del sistema operativo Linux y está en continua evolución.


	    Multiusuario:

	    	Linux es un sistema multiusuario, lo que significa que varios usuarios pueden acceder a los recursos del sistema como memoria / ram / programas de aplicación al mismo tiempo.


	    Multiprogramación:

	    	Linux es un sistema multiprogramación, lo que significa que múltiples aplicaciones pueden ejecutarse al mismo tiempo.


	    Sistema de archivos jerárquico:

	    	Linux proporciona una estructura de archivos estándar en la que se organizan los archivos de sistema y los archivos de usuario.


	    Shell:

	    	Linux proporciona un programa intérprete especial que se puede utilizar para ejecutar comandos del sistema operativo. 

	    	Se puede utilizar para realizar varios tipos de operaciones, llamar a programas de aplicación, etc.


	    Seguridad:

	    	Linux proporciona seguridad al usuario mediante funciones de autenticación como protección por contraseña/acceso controlado a archivos específicos/encriptación de datos.


	Arquitectura/Architecture:

		La arquitectura de un Sistema Linux consiste en las siguientes capas.

	    Capa de Hardware:

	    	El Hardware consiste en todos los dispositivos periféricos (RAM/ HDD/ CPU etc).


	    Kernel:

	    	Es el componente central del Sistema Operativo, interactúa directamente con el hardware, proporciona servicios de bajo nivel a los componentes de la capa superior.


	    Shell:

	    	Interfaz del núcleo que oculta al usuario la complejidad de sus funciones.

	    	El shell recibe órdenes del usuario y ejecuta las funciones del núcleo.


	    Utilidades:

	    	Programas utilitarios que proporcionan al usuario la mayoría de las funcionalidades de un sistema operativo.


	    




