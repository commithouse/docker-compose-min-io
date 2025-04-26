# docker-compose-min-io

Este repositório contém um arquivo `docker-compose.yaml` para configurar e executar o MinIO, um armazenamento de objetos compatível com S3.

## Pré-requisitos

- [Docker](https://www.docker.com/) instalado
- [Docker Compose](https://docs.docker.com/compose/) instalado

## Como usar

1. Clone este repositório:

   ```bash
   git clone https://github.com/commithouse/docker-compose-min-io
   cd docker-compose-min-io
    ```
2. Suba os serviços com o Docker Compose:

    ```bash
    docker-compose up -d
    ```
# Acesse o MinIO:

Interface web: `http://localhost:9001`
## Credenciais padrão:
-    Usuário: admin
-    Senha: minha_senha

## Configure o bucket inicial chamado bucket-images.

