# Instalar PostgreSQL
Para poder instalar PostgreSQL en sus sistema Ubuntu siga los pasos a continuación.

*   Es necesario primero instalar una libreria ```sudo apt-get install libpq-dev```

*   Actualizamos ```sudo apt-get update```

*   Instalamos **PostgreSQL** ```sudo apt-get install postgresql postgresql-contrib```

*   Necesitamos agregar ahora el role para nuestro usuario ```sudo -u postgres createuser --interactive Name_User```

**NOTA:** En caso de querer verificar el nombre de usuario, cree el proyecto y ejecute el servidor, al ir a localhost:3000 le saldra un error de que falta el rol seguido del nombre del que falta.