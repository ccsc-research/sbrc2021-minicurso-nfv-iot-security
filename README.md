# Virtualização de Funções de Rede na IoT: Um Panorama do Gerenciamento de Desempenho x Segurança
# Capítulo 4

## Contents
+ [Introduction](#introduction)
+ [Code Changes](#req)
+ [Install on Ubuntu 16.04](#install)

<a name="introduction"></a>
## Introduction
Esta demonstração compreende empegar as ferramentas Kubernetes, KinD, Knetlab, entre outras, para avaliar uma proposta genérica de detecção de botnets em um cenário com topologias virtuais e de fácil customização. 
Recomendamos que executem em uma maquina virtual.



<a name="req"></a>
## Pré-requisitos

**1)** Executar o script install_dependencies.sh
**2)** Executar script kind-registry.sh


<a name="Devices"></a>
# Devices

> Cada device na pasta devices é um pod kubernetes executando um conjunto de aplicações containerizadas com docker
> Os contêineres são disponibilizados através de um registro de contêineres instalados localmente  
 
