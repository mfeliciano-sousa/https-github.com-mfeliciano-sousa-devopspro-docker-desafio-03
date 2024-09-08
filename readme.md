# DevOpsPro-Desafio03 - Banco de dados MongoDB
Pra finalizar essa etapa, crie o comando pra criar o banco de dados MongoDB usando os requisitos abaixo:

O usuário root do banco deve ser mongo_usr
A senha do usuário root deve ser mongo_pwd
Lembrando que a execução em container deve ser transparente pra quem está desenvolvendo. E que aqui você não precisa se preocupar com a perda dos dados do banco e nem nada disso, é apenas para desenvolvimento pontual.

Coloque aqui embaixo o comando que a equipe deve usar pra criar um banco de dados MongoDB com esses requisitos:

Acesse o terminal e digite o seguinte comando:

docker run --name devopspro-mongo -e ME_CONFIG_MONGODB_ADMINUSERNAME=docker_usr -e ME_CONFIG_MONGODB_ADMINPASSWORD=docker_pwd -d mongo