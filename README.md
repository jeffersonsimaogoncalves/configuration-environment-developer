# Configuração do ambiente de desenvolvimento

Dependencias:

sudo apt install curl git

Instalação ASDF

git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.10.2

Dependencias NodeJS:

asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
asdf nodejs update-nodebuild

Dependencias PHP:

sudo apt-get install dirmngr gpg curl gawk
sudo apt-get install build-essential
sudo apt-get install libwebp-dev
sudo apt-get install libfreetype6-dev
sudo apt-get install libjpeg-turbo8-dev
sudo apt-get install gdlib
sudo apt-get install libwebp

asdf plugin-add php https://github.com/asdf-community/asdf-php.git

asdf install php 8.0.23 (PHP 8.0)
asdf install php 7.4.31 (PHP 7.4)
