## Instalación de Ruby on Rails en Kali Linux

Primero tenemos que asegurarnos de las herramientas con las que ya contamos en nuestro OS, los siguientes comandos son para checar la versión de las herramientas que necesitaremos, en caso de no existir nos marcara que el comando no fue encontrado.

```
node -v
npm -v
yarn --version
ruby --version
rails --version
sqlite3 --version
psql --version
```
En este caso, ya contaba con node, ruby, sqlite3 y psql (PostgreSQL).

**Install NPM**
El comando para instalar NPM es el siguiente.
```sudo apt install npm```

**Install YARN**
El comando para instalar yarn es:
```sudo npm install --global yarn```

**Install Rails**
Si ya se tiene instalado Ruby en el sistemas solo basta usar el comando:
```sudo gem install rails```

### Bibliografia
*   [Instalación de yarn.](https://classic.yarnpkg.com/en/docs/install#debian-stable)
*   [Ruby on Rails](https://guides.rubyonrails.org/getting_started.html)
