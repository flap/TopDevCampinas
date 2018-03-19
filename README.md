# TopDevCampinas
A elite dos profissionais de TI Campinas engajados em um desenvolvimento colaborativo para ajudar instituições.

# Como surgiu o projeto
Em 17 de Janeiro de 2018 tivemos um encontro com as comunidades de AWS, Spring e Dev/Test Campinas e para o planejamento de atividades dos meetups de 2018 foi sugerida a criação de um projeto de verdade onde todas as áreas poderão colaborar. 

# Escolha do tema e escopo do projeto
Após uma rodada de coleta de ideias, tivemos um contato com a [Phomenta][lPhomenta] que nos apresentou demandas reais as quais podemos colaborar! A necessidade mais prioritária é um facilitador para o processo de doações em dinheiro de forma padronizada, fácil e segura. Em uma segunda etapa, ampliaremos para doações de objetos que podem ser úteis para bazares beneficientes, por exemplo. Existe também a doação de "tempo", onde as pessoas podem dedicar horas de sua especialidade profissional em prol das Ongs.

# Produto Entregável na fase 1:
Um app, pwa, site onde uma pessoa física ou jurídica possa efetuar uma doação em dinheiro para uma instituição escolhida pelo usuário.

# Frentes de trabalho:
Sugestão inicial para divisão dos trabalhos. Os Responsáveis de cada frente serão responsáveis por aprovar os PR (Pull Requests).

### PO's (Product Owner's): 
#### Responsáveis: 
Phomenta, (quem mais?)
#### Responsabilidades: 
Auxiliar nas definições de negócio, nos requisitos funcionais que os sistemas devem possuir. Resumindo: são os PO's que colocam o desejo de como tem que ser e como deve funcionar.

### Arquitetura
#### Responsáveis: 
Flávio Pimenta,  (quem mais ?)
#### Responsabilidade: 
Modelar e validar tecnicamente a arquitetura das soluções definidas junto aos PO's e ser o ponto focal das equipes de desenvolvimento. Sugerir padrões para garantir qualidade de código (PMD, CheckStyle, Sonar).

### Desenvolvimento - FrontEnd
#### Responsáveis: 
(quem ?) 
#### Responsabilidades: 
Desenvolvimento do frontend (site, app, pwa). Porporcionais excelente experiência do usuário (UX). Esta frente pode ser dividida em outras caso haja necessidade.

### Desenvolvimento - BackEnd
#### Responsáveis: 
Flávio Pimenta, (quem mais?)
#### Responsabilidades: 
Desenvolvimento do backend, modelagem de banco de dados. Sugestão: microserviços para exposição como API's.
#### Tecnologias: 
SpringBoot5, python, nodeJS (podemos até desenvolver nestas 3 ou mais a partir dos mesmos requisitos!)

### Testes
#### Responsáveis: 
(quem ?)
#### Responsabilidades: 
Elaboração de cenários de teste, execução e automatização dos mesmos. 
#### Tecnologias: 
##### FrontEnd: 
Selenium, Sikuli
##### BackEnd: 
Robot, Postman + Newman
##### Performance: 
jMeter
##### Segurança: 
[zap][lZap]


### CI/CD (Continuous Integration / Continuos Delivery / Continuos Deployment)
#### Responsáveis: 
Flávio Pimenta, (quem mais?)
#### Responsabilidades: 
Criação dos ambiente de forma automatizada(Docker, Terraform, CloudFormation...). Construir pipelines integradas para cobrir o fluxo mínimo de : build -> testes unitários -> testes integrados -> testes de performance -> testes de segurança -> deploy de acordo com o ambiente (local, aws, gpc ...).
#### Tecnologias: 
Jenkins, Nexus, Docker, Terraform, CloudFormation ...
#### Deploy local: 
Docker (na minha máquina funciona!):
##### Passos para subir o docker local:
No diretório raiz do projeto, onde de encontra o Dockerfile execute os comandos:
```
  docker build . -t topdevcampinas/backend-spring:latest
  docker run -rm --name backend-spring topdevcampinas/backend-spring:latest
```
#### Deploy AWS
#####  CloudFormation + ECS
#### Deploy GCP
##### ...

# [Sprint 1 - Modelagem do projeto (Arquitetura, Modelo de dados, tecnologias)][lSP0001]
# Sprint 2 ...
# Sprint 3 ...


[lPhomenta]: <http://www.phomenta.com.br>
[lZap]: <https://github.com/jenkinsci/zap-plugin>

[lSP0001]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0001.md>
[lSP0002]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0002.md>
[lSP0003]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0003.md>
[lSP0004]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0004.md>
[lSP0005]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0005.md>
[lSP0006]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0006.md>
[lSP0007]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0007.md>
[lSP0008]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0008.md>
[lSP0009]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0009.md>
[lSP0010]: <https://github.com/flap/TopDevCampinas/edit/master/sprints/SP0010.md>




