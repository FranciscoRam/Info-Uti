# Información para desarrolladores

En este repositorio se documentara información util en la programación.

## Sistema de control de versiones
-------------
Un control de versiones es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones específicas más adelante.

***[fuente](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Acerca-del-Control-de-Versiones).***

### [Git](git/git-course.md)

Git, que presenta una arquitectura distribuida, es un ejemplo de DVCS (sistema de control de versiones distribuido, por sus siglas en inglés). En lugar de tener un único espacio para todo el historial de versiones del software, en Git, la copia de trabajo del código de cada desarrollador es también un repositorio que puede albergar el historial completo de todos los cambios realizados. 

***[fuente](https://www.atlassian.com/es/git/tutorials/what-is-git).***

## Base de Datos
---------------
Una Base de Datos es una herramienta que funciona como “almacén”, es decir, guarda grandes cantidades de información de forma organizada para poder encontrarla y utilizarla de manera fácil y ordenada. Todos usamos bases de datos, solo que no tenemos conciencia de que eso es lo que son. Por ejemplo, una agenda con nombres, direcciones y números telefónicos es una base de datos. Es decir, la agenda almacena información, la puedes tener ordenada alfabéticamente para facilitar la búsqueda y de vez en cuando debes actualizarla.

***[fuente](https://www.hn.cl/blog/para-que-sirven-la-bases-de-datos/).***

### [Sqlite3](sqlite3/sqlite3.md)
A diferencia de los sistema de gestión de bases de datos cliente-servidor, el motor de SQLite no es un proceso independiente con el que el programa principal se comunica. En lugar de eso, la biblioteca SQLite se enlaza con el programa pasando a ser parte integral del mismo.

En su versión 3, SQLite permite bases de datos de hasta 2 Terabytes de tamaño, y también permite la inclusión de campos tipo BLOB.

SQLite está integrado en todos los teléfonos móviles y la mayoría de las computadoras y viene incluido dentro de innumerables aplicaciones que la gente usa todos los días.

El formato de archivo SQLite es estable, multiplataforma y compatible con versiones anteriores, y los desarrolladores se comprometen a mantenerlo así hasta el año 2050. 

***[fuente 1](https://es.wikipedia.org/wiki/SQLite).***
***[fuente 2](https://www.sqlite.org/index.html).***


### [PostgreSQL](postgresql/info.md)
PostgreSQL, también llamado Postgres, es un sistema de gestión de bases de datos relacional orientado a objetos y de código abierto.

Una característica interesante de PostgreSQL es el control de concurrencias multiversión; o MVCC por sus siglas en inglés. Este método agrega una imagen del estado de la base de datos a cada transacción. Esto nos permite hacer transacciones eventualmente consistentes, ofreciéndonos grandes ventajas en el rendimiento.

***[fuente 1](https://platzi.com/blog/que-es-postgresql/).***
***[fuente 2](https://lwn.net/Articles/660468/).***

## Framework
---
Un framework es un entorno de trabajo que tiene como objetivo facilitar la labor de programación ofreciendo una serie de características y funciones que aceleran el proceso, reducen los errores, favorecen el trabajo colaborativo y consiguen obtener un producto de mayor calidad.

Los desarrolladores pueden crear una web o un programa sin la necesidad de utilizar un framework, sobre todo en el caso de pequeños proyectos. Sin embargo, cuando dicho proyecto va creciendo en complejidad se necesitará una organización, seguir unas pautas, desarrollar código fácil de entender por otros desarrolladores, y otros aspectos que harán necesario el uso de un framework.

***[fuente](https://www.seoestudios.es/blog/que-es-un-framework/).***

### [Ruby on Rails](rails//rails-course.md)
Ruby on Rails es un entorno de desarrollo web de código abierto que está optimizado para la satisfacción de los programadores y para la productividad sostenible. Te permite escribir un buen código evitando que te repitas y favoreciendo la convención antes que la configuración.

***[fuente](https://rubyonrails.org.es/).***

## Editor de código
---
Un editor de código fuente es un editor de texto diseñado específicamente para editar el código fuente de programas informáticos. Puede ser una aplicación individual o estar incluido en un entorno de desarrollo integrado.

Los editores de código fuente tienen características diseñadas para simplificar y acelerar la escritura de código fuente, como resaltado de sintaxis, autocompletar y pareo de llaves. Estos editores también proveen un modo conveniente de ejecutar un compilador, un intérprete, un depurador, o cualquier otro programa que sea relevante en el proceso de desarrollo de software.

***[fuente](https://es.wikipedia.org/wiki/Editor_de_c%C3%B3digo_fuente).***

### [Visual Studio Code](vscode/vscode.md)
Visual Studio Code es un editor de código fuente ligero pero potente que se ejecuta en su escritorio y está disponible para Windows, macOS y Linux. Viene con soporte integrado para JavaScript, TypeScript y Node.js y tiene un rico ecosistema de extensiones para otros lenguajes (como C ++, C #, Java, Python, PHP, Go) y tiempos de ejecución (como .NET y Unity).

***[fuente](https://code.visualstudio.com/docs).***
