# Instalación de Ruby On Rails en ubuntu

A continuacion se explicara como instalar **Ruby on Rails** en ubuntu.

*   Verificamos si tenemos instalados **npm, node, gnupg2 y curl**, **npm** y **node** nos ayudaran para poder correr el servidor, mietras que **gnupg2** y **curl** lo usaremos para la instalación de **ruby on rails**.

**Consola**
```sh
npm -v
node -v
gpg2 --version
curl --version
```

*   De no tenerlo instalado tendremos que instalarlo.

**Consola**
```sh
sudo apt install npm
sudo apt install gnupg2
sudo apt install curl
```

*   Un extra seria **git**, para el manejo del versionamiento.

**Consola**
```sh
sudo apt install git
```

*   Para poder instalar la versión mas reciente de **ruby on rails** se necesita instalar con rvm, para ello primero necesitamos cambiar el modo de ejecución.

*   Nos dirigimos a la consola -> Editar -> Preferencia -> Comando -> Ejecutar la orden como un interprete de acceso.

*   Ahora necesitamos ejecutar los siguientes comandos

**Consola**
```sh
gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

\curl -sSL https://get.rvm.io | bash -s stable

\curl -sSL https://get.rvm.io | bash -s stable --rails
```

* Ya tenemos instalado Ruby on Rails, solo necesitamos comprobarlo

**Consola**
```sh
ruby -v
rails -v
```

**NOTA:** En caso de no mostrar la versión reinicie.
