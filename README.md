# TopDevCampinas
A elite dos profissionais de TI Campinas engajados em um desenvolvimento colaborativo para ajudar instituições.

# Como surgiu o projeto
Em 17 de Janeiro de 2018 tivemos um encontro com as comunidades de AWS, Spring e Dev/Test Campinas e para o planejamento de atividades dos meetups de 2018 foi sugerida a criação de um projeto de verdade onde todas as áreas poderão colaborar. 

# Escolha do tema e escopo do projeto
Em andamento... novidades em breve.

# Sprint 1 - Modelagem do projeto (Arquitetura, Modelo de dados, tecnologias)

# Sugestões
## FrontEnd: 
Qual/quais tecnologias?
## BackEnd: 
SpringBoot5, python, node (podemos desenvolver nas 3 a partir dos mesmos requisitos)
## CI/CD:
### Testes Automatizados:
#### FrontEnd
Selenium, Sikuli
#### BackEnd
Robot, Postman + Newman
### Deploy local - Docker (na minha máquina funciona):
#### Passos para subir o docker local:
No diretório raiz do projeto, onde de encontra o Dockerfile execute os comandos:
  docker build . -t topdevcampinas/backend-spring:latest
  docker run -rm --name backend-spring topdevcampinas/backend-spring:latest
### Deploy AWS
####  CodeBuild + CodeDeploy + CodePipeline
####  CloudFormation + ECS
### Deploy Google
### Deploy AlibabaCloud (sim, existe e está crescendo!!)
