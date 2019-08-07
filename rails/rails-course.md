# Ruby on Rails

----------------------------------------
## Información adicional
**[instalación de Ruby on Rails](./install_ubu.md)**.

**[Información de SQLite3](../sqlite3/sqlite3.md).**

**[Instalación PostgreSQL](./../postgresql/install.md).**

**[Información PostgreSQL](./../postgresql/info.md).**

----------------------------------------
A continuación se explicaran varios comandos utiles en el desarrollo de proyectos usando **Ruby on Rails**.

## Instalación en ubuntu
**pendiente**

## Comandos
*   ```rails new NameProject```: Para poder crear un proyecto usando como base de datos sqlite3.

*   ```rails db```: Para acceder a la base de datos sqlite3 de nuestro proyecto.

*   ```rails new NameProject --database=postgresql```: Para crear un proyecto usando como motor de base de datos postgresql.

*   ```rails new NameProject -d postgresql```: Otra forma de crear un proyecto usando de motor postgresql.

*   ```rails db:drop```: Elimina la base de datos del proyecto.

*   ```rails db:create```: Crea la base de datos del proyecto.

*   ```rails db:migrate```: Migra la información respecto a la estructura de la BD definida en el proyecto para crearla en la BD en nuestro motor.

*   ```rails db:drop db:create db:migrate```: Se puede poner en una sola linea las acciones a tomar, las acciones se ejecutan de izquierda a derecha.

**Nota: a partir de ahora se separara por un " / " cuando se aga referencia a comandos con las misma funcion pero escritos diferentes.**

*   ```rails server /  rails s```: Para arrancar el servidor de nuestro proyecto.

*   **Convenciones**: Es importante checar información sobre las convenciones en rails, para eso puede dirigirse a [aquí.](http://rubyni.com/2017/08/07/convenciones-de-nombres-de-rails/)


*   ```rails g model publication origin:string destiny:string date_exit:date time_exit:time time_finish:time number_rider:integer```: Ejemplo para generar un modelo.

*   **Tipos de datos**: Los tipos de datos que pueden tener nuestro campos en la definición del modelo de nuestro proyecto se muestran en la tabla de abajo.
En el caso del string se puede definir una longitud Ejemplo: **string{5}**.

No. |   Datos en Ruby on rails 
-- | --
1 | :binary
2 | :boolean
3 | :date
4 | :datetime
5 | :decimal
6 | :float
7 | :integer
8 | :string
9 | :text
10 | :time
11 | :timestamp