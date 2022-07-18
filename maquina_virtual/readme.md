# Creación de una maquina virtual

En una maquina virtual podemos administrar practicamente todo desde el sistema operativo hasta los programas que estan instalados en el servidor.

Primero, nos dirigimos al portal.azure.com y buscamos maquina virtual en la market place y seleccionamos crear.

![MarketPlace](images\2022-07-18_152935.png)

Escogemos la suscripción y creamos un grupo de recursos en caso de no tener uno.

![GrupoRecursos](images\2022-07-18_153500.png)

Nombramos la maquina virtual, seleccionamos la region del servidor y el sistema operativo

![MaquinaVirtual](images\2022-07-18_154536.png)

Definimos los datos de acceso para acceder a la maquina virtual 

![Acceso](images\2022-07-18_155139.png)

En la sección de redes, en el apartado de interfaz de red, seleccionamos ninguno en Grupo de seguridad de red de NIC, esto para acceder mas facilmente a la maquina

![Seguridad](images\2022-07-18_155944.png)

Seleccionamos revisar y crear

![Validacion](images\2022-07-18_160418.png)

Una vez superada la validación seleccionamos crear

Una vez completada la implementación seleccionamos el recurso

![Recurso](images\2022-07-18_160858.png)

En conectar seleccionamos RDP

![RDP](images\2022-07-18_161346.png)

Descargamos el archivo RDP

![Instalador](images\2022-07-18_161547.png)

Para abrir el archivo, debemos tener instalado escritorio remoto de microsoft, se descarga de microsoft store

![EscritorioRemoto](images\2022-07-18_162448.png)

Abrimos el achivo con escritorio remoto

![AbrirArchivo](images\2022-07-18_162708.png)

Seleccionamos continuar

![Continuar](images\2022-07-18_162859.png)

Esperamos a que se inicie la secion remota

![secion](images\2022-07-18_162941.png)

Introducimos nuestras claves de acceso

![acceso](images\2022-07-18_164342.png)

Seleccionamos conectar de todos modos

![conectar](images\2022-07-18_164445.png)

Probablemente debamos hacer configuraciones menores en el arranque del sistema operativo, despues de lo cual estaremos en el escritorio remoto

![escritorio](images\escritorio.png)