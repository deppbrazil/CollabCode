# Instalando zsh

## Abrir terminal
* Digitar: bash 
* sudo apt-get install zsh
* zsh --version

## Usar o zsh
* Abrir terminal e digitar: zsh

## Verificando se o Ubuntu está usando zsh ou bash 
* Abrir o Ubuntu 
* echo $SHELL
  
## Configurando o SHELL para o zsh
* Abrir terminal
* chsh -h 
* which zsh
* chsh -s /usr/bin/zsh
* Ou: chsh -s $(which zsh)
* Fechar e abrir terminal do Ubuntu
* echo $SHELL

## Configurando o SHELL para o bash
* Abrir terminal
* which bash 
* chsh -s /bin/bash
* Ou: chsh -s $(which bash)
* Fechar e abrir terminal do Ubuntu
* echo $SHELL

## Bônus
### zsh
* [zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)

### sudo => comando administrador
* echo Hello!
* sudo echo Hello!
* colocar senha

### apt-get => gerenciador/repositório de pacotes do Ubuntu
* [Doc](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)