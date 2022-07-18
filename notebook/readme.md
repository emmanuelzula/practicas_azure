# Uso de recursos computacionales de Azure mediante un notebook

En azure existe la posibilidad de que un archivo .ipynb (Jupyter notebook) utilice recursos computacionales de un servidor de microsoft.

## Creación del grupo de recursos

Primero, entramos al marketplace de azure y buscamos el servicio Azure machine learning

![Marketplace](images\2022-07-18_001552.png)

Entramos en el recurso y seleccionamos crear

![Recurso](images\2022-07-18_002015.png)

Seleccionamos el tipo se suscripción y creamos un nuevo grupo de recursos con el nombre Notebook en caso de no tener uno 

![Grupo de recursos](images\2022-07-18_002331.png)

Nombramos al área de trabajo como queramos, en este caso Prueba_Notebook, y elegimos la regíon del servidor, todo lo demas lo dejamos por defecto.

Seleccionamos revision y creación

![Area de trabajo](images\2022-07-18_003009.png)

Una vez superada la validación seleccionamos crear

![Validación](images\2022-07-18_003259.png)

Esperamos hasta que se complete la implementación

![Implementacion](images\2022-07-18_003546.png)

Nuestra area de trabajo aparecera en la pagina "www.azure.com\home" la seleccionamos

![ml.azure](images\2022-07-18_003941.png)

Una vez dentro, en el apartado de administrar seleccionamos proceso

![proceso](images\2022-07-18_004622.png)

En instancias de proceso seleccionamos nuevo

![instancia de proceso](images\2022-07-18_004758.png)

Nombramos el proceso y seleccionamos la configuracion que mas se ajuste a nuestras necesidades y seleccionamos crear

![Creacion del proceso](images\2022-07-18_011008.png)

Una vez creado el proceso seleccionamos notebooks

![Proceso terminado](images\2022-07-18_012033.png)

En este espacio de trabajo podemos crear archivos o subirlos desde la computadora para despues ejecutarlos con los recursos del servidor de azure.

![CreacionNotebook](images\2022-07-18_012926.png)

El clasico hola mundo ejecutado desde la nube seria algo así

![HolaMundo](images\2022-07-18_013427.png)