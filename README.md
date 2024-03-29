# Configuração do ambiente de desenvolvimento

# Dependencias Ubuntu 20.04.5 LTS

```bash
sudo apt install curl git
```

# Instalação ASDF

```bash
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.10.2
```

# NodeJS

```bash
asdf plugin add nodejs https://github.com/asdf-vm/asdf-nodejs.git
```

```bash
asdf nodejs update-nodebuild
```


# PHP

```bash
sudo apt-get install dirmngr gpg curl gawk build-essential libwebp-dev libfreetype6-dev libjpeg-turbo8-dev gdlib libwebp
```

```bash
asdf plugin-add php https://github.com/asdf-community/asdf-php.git
```

```bash
asdf install php 8.1.10 (PHP 8.1)
```

```bash
asdf install php 8.0.23 (PHP 8.0)
```

```bash
asdf install php 7.4.31 (PHP 7.4)
```

# Java

```bash
asdf plugin-add java https://github.com/halcyon/asdf-java.git
```

```bash
asdf install java openjdk-19
```

# Fnpm

```bash
asdf plugin add nfpm https://github.com/ORCID/asdf-nfpm.git
```

```bash
asdf install nfpm latest
```
