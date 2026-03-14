# Build do SilvioLinux

Este documento explica como compilar o SilvioLinux usando Yocto Project.

## Dependências

Ubuntu/Debian:

sudo apt install git build-essential chrpath socat python3

## Baixar Yocto

git clone git://git.yoctoproject.org/poky

## Inicializar ambiente

source oe-init-build-env

## Compilar

bitbake silviolinux-image

## Resultado

A imagem será gerada em:

tmp/deploy/images/
