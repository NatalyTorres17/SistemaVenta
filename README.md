# Sistema de Venta en Java y Mysql

## Descripcion

Es una herramienta de gestion y venta  que cuenta con una base de datos para el manejo y analisis de la informacion y desarrollo de reportes de lo que sale y tiene la empresa de productos. La aplicacion fue desarrollada por el lenjuage de Java y modules como lo son el  Apache y MYSQL con el objetivo de poder resolver la problematica de registro de reportes de venta o gestion que se presenta en la empresa.

## Problema identificado

El problema identificado era que no tenían un punto de ventas donde se podía saber el stock de los productos, el proveedor, el cliente, la venta y entre otras cosas que no contaba el departamento de venta y gestión. Se requería realizar reportes finales que se entregan a El Regino, como ellos reciben la información de los análisis de la venta y producto en una base de datos a mano, se les hace muy complicado el poder organizar, y administrar la información, ya que son muchos datos y muchos valores. Es por ello que el hacer los reportes con tan pocos recursos, se vuelve confundo y no tienen organización de lo que se está llevando a cabo en la empresa.

## Tabla de contenidos

### SistemaVenta

- Build
-- classes
-- empty
-- generated-sources
- ap_source_output
-- test
--- classes
--- results
- librerias
-- AbsoluteLayout
-- itextpdf-5.5.1
-- jcalendar-1.4
-- jcommon-1.0.23
-- jfreechart-1.0.19
-- mysql-connector-java-8.0.19
####- nbproject
-- private
--- config
--- provate
--- private
-- build-impl
-- genfiles
-- project
-- project
- src
-- img
-- Modelo
-- reportes
-- sistemaventa
-- Vista
- test
- .gitignore
- build
- manifest.mf
- venta.sql


### Diseño

- Login.
- Interfazes para visualizar el archivo.
- Ventana en podemos agregar una venta y ver el stock del prodcuto
- Ventana de reporte.
- Interfaz con botones para diferentes acciones
- Opción de imprimir.
- Opcion de PDF de registro
- Ventana/interfaz para agregar administradores 
- Interfazes para visualizar el inicio de credenciales
- Interfazes para visualizar las ventas en el mes 

## Requerimientos Funcionales:

-Registro de Productos
-	Registro de Ventas
-	Cambio de información del Producto
-	Eliminación de producto
-	El sistema debe de contar con un módulo para realizar reportes por usuario

## Requerimientos no Funcionales.

-Funcionalidad del sistema
-	Disponibilidad del sistema al usuario 24/7
-	La aplicación solo es compatible con el sistema operativo Windows de la empresa
-	La aplicación contara con un instalador al escritorio
-	La aplicación debe de contar con la estabilidad 

### Bases de datos
-   phpMyAdmin 
- pro_java
1. NuevaNueva
2. clientes
3. config
4. detalle
5. productos
6. proveedor
7. usuarios
8. ventas

### Servidores de aplicación

- Apache 
- Servidor Base de datos
- Servidor Proxy


### Versión de Java
- Apache NetBeans IDE 12.6

### Instalación:
- Descargar el proyecto del repositorio
- Descomprimir el archivo para obtener la carpeta del proyecto ZIP
- Abrimos la carpeta del proyecto en NetBeans o otra app para modficiar el codigo
- O tambien abrimos la carpeta de bin en la cual encontraremos el archivo .jar e niciamos el ejecutable


### Configuracion

- Instalamos la version Apache NetBeans IDE 12.6
- Configuracion del ambiente JAVA
- Obtenemos  la informacion que necesitamos para pasarla a la aplicacion por defaul
- agregamos la base de datos
- configuramos nuestra base de datos en la plantlla del sistema del software y la cargamos.

### Uso

El software sera para uso interno del departamento de gestion y ventas, donde ambos departamentos (administradores )tienen acceso agregar ventas, ver informacion de las ventas, el dia y mes cuando se hicieron, los provedores, agregar productos, entre otras cosas que solo esos dos despartamentos tienen acceso. Se requiere contar con credenciales para entrar a la applicacion, solo se agregan personsas una vez dentro del sistema en donde dice Usuarios. 


### Contribucion

- Abrimos el repositorio
- Link del repositorio ()
- En el branch "master" podemos encontrar la version mas actual del software y la mas completa y estable
- Del lado derecho tenemos la opcion de clone or download
- Tenemos dos opciones a elegir (abrir en el equipo o descargar como zip)
- Cualquiera de las 2 opciones nos puede servir
- ejecuta el programa o modificalo 
- en netbeand para poder agregar branch debes de seguir los sigueintes pasos
1. click derecho en el proyecto o en el folder del proyecto, lo conectas a un git (posteriormente tener un repository en github).
2. Se depliega varias opciones, click en git, despues click en Branch/Tag y por ultimo Create Branch
3. Creas tu branch y listo 

- Una vez con los branch, puedes agregar archivos desde github, 
### Roadmap

Con forme la aplicacion se va usando dentro de la empresa, podremos identificar errores y con eso ellos nos podimaos guiar para llegar a obejtivos de mejora y asi contruir un mejor una hoja de ruta donde se rediseñara el sistema para actualizaciones. Se planea tener updates de la aplicacion cada 2 meses para darle mantenimmiento al punto de venta. Se necesitara de una vista de perspectiva de alto nivel de todas las entragas de mejora en el sistema donde se estara vizualisando lo bueno y malo para estableces indicadores de rendimiento en el sistema. 


Debe contar con pasos específicos para clonar repositorio, crear un nuevo branch, enviar el pull request, esperar a hacer el merge.


