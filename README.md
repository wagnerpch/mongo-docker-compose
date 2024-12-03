# Mongo docker compose

[![Static Badge](https://img.shields.io/badge/license-GNU-green)](https://github.com/wagnerchc/chess-system-java/blob/master/LICENSE)

# Sobre o projeto

Docker compose para utilizar os serviços do Mongo e Mongo-Express

# Tecnologias utilizadas

- Docker Compose
-- network para conexão entre containers
-- volume para persistência de dados

# Como executar o projeto

Pré-requisitos:

- WSL
- Docker
- Docker-compose

```bash

# altere a indicação do volume no docker-compose.yml
seu-diretorio/data/db:/data/db

# após clonar o projeto, execute o seguinte comando no terminal
docker-compose up

# acesse o mongo-express com usuário e senha do docker-compose.yml
http://localhost:8081/

```
# Autor

Wagner Pereira Chequeleiro

https://www.linkedin.com/in/wagnerpch/
