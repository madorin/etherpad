

# Etherpad+


## Features

Custom [Etherpad](https://etherpad.org/) Docker file to suit your project needs.
Based on [official](https://github.com/ether/etherpad-lite/blob/develop/Dockerfile) Docker image.

Includes a set of features:
 - Preinstalled custom Etherpad [plugins](https://static.etherpad.org/)
 - Integrate it with [Abiword](https://gitlab.gnome.org/World/AbiWord) or [Libreoffice](https://www.libreoffice.org/)
 - Other preconfigured settings and tweaks
 - Docker compose sample to connect it to your projects


## Usage

 - Clone / download the repository in a folder
 - Launch it using `docker compose up -d --build`
 - Open your browser on http://localhost:9001 and see the magic
 - Admin area is available on http://localhost:9001/admin/ with admin & password credentials
 - Customize docker files according to your needs
 - Enjoy!

## Contribute

Feel free to adjust it according to your needs.

© Dorin Marcoci, www.marcodor.com
