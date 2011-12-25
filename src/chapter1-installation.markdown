Capítulo 1 : Instalación
========================

Para instalar Magento vas a necesitar un ordenador con sistema operativo 
GNU/Linux. Microsoft Windows no está soportado y, aunque puedas conseguir 
instalar Magento en una máquina que lo utilize, se desaconseja y no recibe 
ningún soporte por parte de la comunidad ni por parte de ninguno de sus 
partners.

Magento además, esta diseñado para que se integre en tu servidor de desarrollo 
y/o de test de manera que puedas tener diferentes instáncias de la aplicación 
que faciliten su uso para los diferentes equipos que tengas trabajando con el 
ya sean diseñadores, programadores o entornos para testear los cambios antes de 
ponerlos en producción.

Requerimientos del sistema
--------------------------

A continuación te mostramos los requerimientos en cuanto a software que Magento 
tiene actualmente, así como alguna modificación recomendada en la configuración 
para su correcto funcionamiento.

*	**Plataforma LAMP, WAMP, OAMP**

	La plataforma donde Magento funciona se compone de la conjunción del Sistema 
	Operativo elegido, Apache, MySQL y PHP. Hay que tener en cuenta no obstante 
	que sólo GNU/Linux está soportado de manera oficial con lo que se recomienda 
	encarecidamente no utilizar otro sistema operativo en entornos de producción.
	
*	**Apache Web Server 1.x, 2.x**

	Magento incluye soporte para las versiones más comunes de Apache tanto en su 
	rama 1.X como 2.x. Puedes no obstante usar Magento con otros servidores web 
	como *Nginx*, *Cherokee* o *Lighthttpd* pero en servidores en producción su uso 
	está desaconsejado y no soportado.

*	**PHP5.2 o superior ( funciona bien con 5.3 )**

	Por supuesto es necesario que tengas instalada una versión de PHP. Magento 
	necesita como mínimo la versión 5.2 y funciona correctamente con versiones 
	superiores.

*	**php5-mysql**

	El soporte para MySQL tambien es necesario para PHP ya que Magento utiliza 
	MySQL como depósitorio de datos.

*	**php5-mcrypt**

	Magento de forma interna utiliza encriptación para los datos que pueden ser 
	comprometidos por ejemplo contraseñas de las cuentas de clientes, las cuentas 
	de administradores etc ...

*	**php5-mhash**

	Ciertas partes del funcionamiento de Magento también utilizan hashes para 
	identificar de forma única partes de su funcionamiento como pueden ser las 
	sesiones de cada usuario o sus carritos de compra. Esta es la libreria que 
	Magento utiliza para generarlos.

*	**php5-curl**

	A veces, Magento necesita crear URLs o descargar contenido externo ( por 
	ejemplo de un webservice ) esta es la libreria que ayuda a gestionar estas 
	descargas y la construcción de URLs.

*	**php5-gd**

	Cualquier tarea que Magento tenga que realizar con imágenes, ya sea 
	redimensionarlas, recortarlas etc ... se realiza grácias a esta libreria.

*	**php-apc**

	Magento se beneficia del caché PHP APC para mejorar s rendimiento. Con solo 
	activar esta extensión de PHP Magento utilizará este caché de forma 
	transparente sin que tengas que configurar nada ni cambiar una sola línia de 
	código.

*	**Configuration ( memory_limit=128M, max_execution_time=18000 )**

	La configuración predeterminada de PHP no es sufucientemente permisiva para 
	que una aplicación grande como Magento funcione de manera adecuada. Por eso 
	es mejor modificarla para adaptarla a nuestras necesidades. Para saber como 
	aplicar esta configuración por favor consulta la ayuda de PHP.

Tipos de instalación
--------------------

### Instalación automática

instalación automática

#### Listado de Hostings que soportan Magento

listado de hostings que soportan magento

### Instalación manual

La instalación manual permite poder configurar todos los aspectos de Magento ya
que seras tu mismo quien tenga el control de toda la aplicación.

#### Paso 1: Material a descargar

Lo principal a descargar es el paquete de Magento que poduedes encontrar en 
http://www.magentoecommerce.com.

#### Paso 2: Subir el instalador para su ejecución

subir el instalador para su ejecución

#### Paso 3: Permisos del material subido

permisos del material subido

#### Paso 4: Configura la base de datos de Magento

configura la base de datos

#### Paso 5: Finaliza la instalación

finaliza la instalación

Actualización de una instalación previa
---------------------------------------

actualización de una instalación previa

*[PHP]: PHP Hypertext Pre-processor 
*[APC]: Alternative PHP Caché
*[LAMP]: Linux, Apache, MySQL y PHP
*[WAMP]: Windows, Apache, MySQL y PHP
*[OAMP]: OsX, Apache, MySQL y PHP
