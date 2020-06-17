Proyecto Daniel Rodriguez Gomez (Restaurador)

Dependencias globales
Docker
Docker-compose
## Installación

### Clonando el repo

Este repositorio de git contiene un submódulo de git, por lo que es necesario tenerlo en cuenta antes de clonar el repositorio. Para clonar el repositorio junto con el submódulo, hay que ejecutar el comando:

$ git clone --recursive https://github.com/Zeremiel/Proyecto-Daniel-Rodriguez-Restauraci-n-.git

Si por lo que sea ya has clonado el repositorio sin la orden --recursive, debes añadir el submódulo a posteriori:

$ git submodule update --init

### Instalación del proyecto

Para instalar el proyecto hay un fichero install.sh. Primero, debes hacerlo ejecutable:

$ chmod +x install.sh

Tras ello, ejecútalo:

$ ./install.sh
