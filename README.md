# Fleet Management Software API

Issue: 
-Quiero repasar los conceptos que aprendi en este proyecto
-agregar mas verbos http
-agregar autentificacion
-instalar DB local
-Dockerizar la app
-Optimizar la base de datos
-Exportar DB a excel

Adicional a eso quiero mejorar la seguridad de la aplicacion
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

# Isuues:

## Verbos HTTP

Repasar los conceptos relacionados con los verbos HTTP utilizados en el proyecto.

## Autenticación

Agregar un sistema de autenticación robusto para proteger la aplicación. Considerar opciones como JWT, OAuth, o cualquier otro método seguro.

## Instalación de Base de Datos Local

Configurar una base de datos local para el desarrollo y pruebas.

## Dockerización de la Aplicación

Crear contenedores Docker para la aplicación y sus dependencias, facilitando el despliegue y la gestión del entorno.

## Optimización de la Base de Datos

Realizar ajustes y optimizaciones en la base de datos para mejorar el rendimiento. Esto puede incluir índices, normalización, o cualquier otra técnica relevante.

## Exportar Base de Datos a Excel

Implementar una funcionalidad para exportar datos de la base de datos a un archivo Excel. Buscar bibliotecas que lo hagan.

## Mejoras en la Seguridad

### Protección contra Inyección de SQL

Implementar medidas para prevenir ataques de inyección SQL, como el uso de consultas preparadas o ORM.

### Validación de Entradas

Asegurar la validación adecuada de todas las entradas de usuario para prevenir ataques de XSS y CSRF.

### Gestión de Sesiones

Revisar y mejorar la gestión de sesiones para evitar vulnerabilidades.

### Actualizaciones Regulares de Dependencias

Mantener actualizadas todas las dependencias de la aplicación para abordar posibles vulnerabilidades de seguridad.

### Configuración Segura de Servidores y Entornos

Asegurar que la configuración del servidor y del entorno sea segura, siguiendo las mejores prácticas de seguridad.

### Registro de Eventos y Monitoreo

Implementar un sistema de registro de eventos y monitoreo para detectar y responder rápidamente a posibles amenazas.



## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)
* [4. Consideraciones generales](#4-consideraciones-generales)
* [5. Criterios de aceptación del proyecto](#5-criterios-de-aceptación-del-proyecto)
* [6. Stack de tecnologías](#6-stack-de-tecnologías)
* [7. Pistas, tips y lecturas complementarias](#7-pistas-tips-y-lecturas-complementarias)
* [8. Funcionalidades opcionales](#8-funcionalidades-opcionales)

***

## 1. Preámbulo

De acuerdo con
[Wikipedia](https://es.wikipedia.org/wiki/Internet_de_las_cosas),
la internet de las cosas (IoT, por sus siglas en inglés)​ es un concepto que
se refiere a una interconexión digital de objetos cotidianos con internet.
Constituye un cambio radical en la calidad de vida de las personas en la
sociedad, ofreciendo nuevas oportunidades en el acceso a
datos, educación, seguridad, asistencia
sanitaria y en el transporte, entre otros campos. Por ejemplo,
en logística y manejo de flotas, se puede hacer seguimiento en
todo momento de la ubicación y las condiciones de vehículos
mediante sensores inalámbricos conectados a internet que envían alertas en
caso de eventualidades (demoras, daños, robos, etc.).

![zach-vessels-utMdPdGDc8M-unsplash](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fthumb.jpg?alt=media)

La IoT también plantea retos como el almacenamiento, análisis y
visualización de la gran cantidad de información que genera.
Se calcula que para el 2025 los dispositivos IoT generen
[79.4 zettabytes](https://www.statista.com/statistics/1017863/worldwide-iot-connected-devices-data-size/)
(1 zettabyte equivale a 1 trillón de gigabytes).
Como desarrolladoras debemos estar al tanto de estos retos y contribuir para
su solución desde nuestra experiencia, conocimiento y ganas de aprender.

## 2. Resumen del proyecto

En este proyecto construirás la API REST de un
[Fleet Management Software](https://en.wikipedia.org/wiki/Fleet_management)
para consultar las ubicaciones de los vehículos de una empresa
de taxis en Beijing, China.

Te entregaremos las ubicaciones de casi 10 mil
taxis. Esperamos que como desarrolladora explores nuevas alternativas y
técnicas para almacenar y consultar esta
información y puedas garantizar la mejor experiencia de usuaria en tu
API REST.

## 3. Objetivos de aprendizaje


Reflexiona y luego marca los objetivos que has llegado a entender y aplicar en tu proyecto. Piensa en eso al decidir tu estrategia de trabajo.

### Java

- [ ] **Modificadores de acesso (public, private, protected)**

- [ ] **Variables**

- [ ] **Uso de condicionales**

- [ ] **Uso de bucles (Loops)**

- [ ] **Primitivos**

- [ ] **Datos primitivos vs no primitivos**

- [ ] **Cadenas**

- [ ] **Arreglos**

- [ ] **ArrayList**

- [ ] **HashMap**

- [ ] **HashSet**

- [ ] **JUnit**

- [ ] **Mockito**

- [ ] **Beans**

- [ ] **Inversión de Control**

- [ ] **Anotaciones**

- [ ] **Initializr**

  <details><summary>Links</summary><p>

  * [Spring Initializr](https://start.spring.io/)
</p></details>

- [ ] **Spring Boot**

  <details><summary>Links</summary><p>

  * [Spring Boot Reference Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/)
</p></details>

- [ ] **Controladores**

- [ ] **Servicios**

- [ ] **Spring Data JPA**

  <details><summary>Links</summary><p>

  * [Spring Data JPA - Reference Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
</p></details>

- [ ] **Entidad**

- [ ] **Repositorio**

- [ ] **RestController**

- [ ] **RequestMapping**

- [ ] **spring-framework/spring-web/request-param**

- [ ] **Spring Test**

- [ ] **Hamcrest**

- [ ] **Configuración**

- [ ] **Esquema**

- [ ] **Entidad**

- [ ] **Tabla**

- [ ] **Columna**

- [ ] **Identificadores**

- [ ] **Asociaciones**

- [ ] **Colecciones**

- [ ] **Persistencia**

- [ ] **Consultas**

### Programación Orientada a Objetos (OOP)

- [ ] **Clases**

- [ ] **Objetos**

- [ ] **Métodos**

- [ ] **Atributos**

- [ ] **Constructores**

- [ ] **Encapsulamiento**

- [ ] **Abstracción**

- [ ] **Composición**

- [ ] **Interfaces**

- [ ] **Herencia (super, extends, override)**

- [ ] **Lenguaje de Modelado Unificado (UML, class diagrams)**

### Node.js

- [ ] **Instalar y usar módulos con npm**

  <details><summary>Links</summary><p>

  * [Sitio oficial de npm (en inglés)](https://www.npmjs.com/)
</p></details>

- [ ] **Configuración de package.json**

  <details><summary>Links</summary><p>

  * [package.json - Documentación oficial (en inglés)](https://docs.npmjs.com/files/package.json)
</p></details>

- [ ] **Configuración de npm-scripts**

  <details><summary>Links</summary><p>

  * [scripts - Documentación oficial (en inglés)](https://docs.npmjs.com/misc/scripts)
</p></details>

- [ ] **process (env, argv, stdin-stdout-stderr, exit-code)**

  <details><summary>Links</summary><p>

  * [Process - Documentación oficial (en inglés)](https://nodejs.org/api/process.html)
</p></details>

- [ ] **File system (fs, path)**

  <details><summary>Links</summary><p>

  * [File system - Documentación oficial (en inglés)](https://nodejs.org/api/fs.html)
  * [Path - Documentación oficial (en inglés)](https://nodejs.org/api/path.html)
</p></details>

### SQL

- [ ] **Creación y modificación de tablas**

  <details><summary>Links</summary><p>

  * [SQL CREATE TABLE Statement - w3schools (en inglés)](https://www.w3schools.com/sql/sql_create_table.asp)
  * [CREATE TABLE Statement - PostgreSQL Docs (en inglés)](https://www.postgresql.org/docs/9.1/sql-createtable.html)
  * [ALTER TABLE Statement - PostgreSQL Docs (en inglés)](https://www.postgresql.org/docs/9.1/sql-altertable.html)
</p></details>

- [ ] **Operaciones CRUD (Create-Read-Update-Delete)**

  <details><summary>Links</summary><p>

  * [INSERT](https://www.postgresql.org/docs/9.5/sql-insert.html)
  * [SELECT](https://www.postgresql.org/docs/9.5/sql-select.html)
  * [UPDATE](https://www.postgresql.org/docs/9.1/sql-update.html)
  * [DELETE](https://www.postgresql.org/docs/8.1/sql-delete.html)
</p></details>

- [ ] **Borrado de tablas o bases de datos enteras con DROP**

  <details><summary>Links</summary><p>

  * [DROP TABLE](https://www.postgresql.org/docs/8.2/sql-droptable.html)
  * [DROP DATABASE](https://www.postgresql.org/docs/8.2/sql-dropdatabase.html)
</p></details>

### Bases de datos

- [ ] **Modelado de datos**

- [ ] **Conexión**

- [ ] **Índices y limitaciones**

### PostgreSQL

- [ ] **Tipos de datos**

  <details><summary>Links</summary><p>

  * [Chapter 8. Data Types - Docs (en inglés)](https://www.postgresql.org/docs/14/datatype.html)
</p></details>

- [ ] **Índices**

  <details><summary>Links</summary><p>

  * [Chapter 11. Indexes - Docs (en inglés)](https://www.postgresql.org/docs/14/indexes.html)
</p></details>

## 4. Consideraciones generales

* Este proyecto se debe "resolver" en duplas.
* El rango de tiempo estimado para completar el proyecto es de 4 a 6 Sprints.

## 5. Criterios de aceptación del proyecto

Nuestra cliente ha instalado dispositivos GPS en sus taxis.
Estos dispositivos utilizan señales satelitales para determinar
con precisión las coordenadas geográficas del taxi.

Nuestra clienta requiere:

1. Cargar la información de archivos SQL a una
base de datos Postgresql.
2. Desarrollar una API REST que permita consultar, mediante
peticiones HTTP, la información almancenada en la base de datos.

### Definición del producto

El [_Product Owner_](https://www.youtube.com/watch?v=r2hU7MVIzxs&t=202s)
nos presenta este _backlog_ que es el resultado de su trabajo con la clienta
hasta hoy.

***

#### [Historia de usuario 1] Cargar información a base de datos

Yo, como desarrolladora, quiero cargar la información almacenada hasta ahora en
[archivos sql](https://drive.google.com/file/d/1T5m6Vzl9hbD75E9fGnjbOiG2UYINSmLx/view?usp=drive_link)
en una base de datos PostgreSQL, para facilitar su consulta y análisis.

##### Criterios de aceptación

* Se debe tener en cuenta el siguiente diagrama para la implementación de las
relaciones entre las tablas

![mer](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fsql-diagram.png?alt=media)

* La tabla de _trajectories_ se debe crear con el "id" que se incremente
automáticamente (SERIAL) para poder insertar los valores sin necesidad
de especificar un identificador

##### Definición de terminado

* La base de datos tiene creada la tabla de taxis
* La tabla de taxis tiene cargada la data de taxis
* La base de datos tiene creada la tabla de trayectorias
* La tabla de taxis tiene cargada la data de trayectorias

***

##### [Historia de usuario 2] Endpoint listado de taxis

Yo como clienta de la API REST requiero un _endpoint_ para
listar todos los taxis.

##### Criterios de aceptación

* El _endpoint_ responde para cada taxi: id y placa.
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

#### [Historia de usuario 3] Endpoint historial de ubicaciones

Yo como clienta de la API REST requiero un _endpoint_ para
consultar todas las ubicaciones de un taxi dado el id y una fecha.

##### Criterios de aceptación

* El _endpoint_ responde para el id del taxi consultado la siguiente
información: latitud, longitud y fecha y hora.
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

#### [Historia de usuario 4] Endpoint última ubicación

Yo como clienta de la API REST requiero un _endpoint_ para
consultar la última ubicación reportada por cada taxi.

##### Criterios de aceptación

* El _endpoint_ responde para cada taxi la siguiente información:
id, placa, latitud, longitud y fecha y hora.
* El _endpoint_ paginamos los resultados para asegurar que las
respuestas sean más fáciles de manejar.

##### Definición de terminado

* Se cuenta con una documentación en [Swagger](https://swagger.io/)
para el _endpoint_ desarrollado especificando
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).
* El código del _endpoint_ debe recibir _code review_ de al
menos una compañera.
* El código _endpoint_ debe estar cargado en un repositorio de Github.
* El código _endpoint_ debe contar con test unitarios y e2e.

***

## 6. Stack de tecnologías

Puedes implementar este proyecto en JavaScript o Java.

* [Java](./docs/README-java.md#stack-de-tecnologías)
* [NodeJs](./docs/README-node.md#stack-de-tecnologías)

## 7. Pistas, tips y lecturas complementarias

### Modelamiento de datos

La base de datos recomendada para tu aplicación es PostgreSQL. Te
recomendamos usar [vercel Postgresql](https://vercel.com/docs/storage/vercel-postgres)
para que no tengas que instalar PostgreSQL en tu computadora.

Una vez tengas acceso a una instancia de PostgreSQL, deberás crear tablas en
tu base de datos para almacenar la información entregada. Te recomendamos
entonces crear dos tablas, una para almacenar la información de taxis y otra
para almacenar la información de ubicaciones. Deberás definir las columnas
de cada tabla de acuerdo a la información entregada.

Puedes crear una tabla en PostgreSQL usando
[SQL](https://www.postgresqltutorial.com/postgresql-create-table/).

### Definir endpoints de API

Deberás definir y documentar los endpoints de tu API.
Debes usar [Swagger](https://swagger.io/) para esto.

Para una API REST debes definir para cada endpoint entre otras cosas el
[método HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods),
url, parámetros,
[encabezados](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers),
[códigos HTTP de respuesta](https://shorturl.at/bdegB)
y
[cuerpo](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages).

Por ejemplo, en la siguiente figura se define un endpoint para consultar la
información de los taxis en la aplicación. El método del endpoint es _GET_,
la url es _/taxis_. Recibe un parámetro _query_, retorna la información con
_código HTTP_ 200 en formato json gracias al _header_
`Content-type` con valor `application/json`.

![Ejemplo Endpoint API Rest](https://firebasestorage.googleapis.com/v0/b/laboratoria-945ea.appspot.com/o/fleet-management-api-java%2Fexample-endpoint-api-rest.png?alt=media)

## 8. Funcionalidades opcionales

Si completaste todas las funcionalidades del proyecto te invitamos a trabajar en
las [funcionalides opcionales](./docs/README.extension.md)
