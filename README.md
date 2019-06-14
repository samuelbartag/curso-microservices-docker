# Curso Micro Serviços

Projeto para o módulo docker do curso de microserviços.

## Iniciando

Instruções para você baixar e executar esse projeto em sua máquina para testes e estudos.

### Imagens

#### Web

O source da imagem do container com o servidor web pode ser acessado [aqui](https://github.com/samuelbartag/curso-microservices-docker-web). E executado [daqui](https://hub.docker.com/r/samuelbartag/web).

#### PHP

O source da imagem do container PHP pode ser acessado [aqui](https://github.com/samuelbartag/curso-microservices-docker-php). E executado [daqui](https://hub.docker.com/r/samuelbartag/php).

## Execução

Para executar o projeto primeiro clone o repositório para sua máquina:
```sh
git clone git@github.com:samuelbartag/curso-microservices-docker.git
```

Acesse a pasta criada para o projeto:
```sh
cd curso-microservices-docker
```

Renomeie o arquivo *.env-example* para *.env*:
```sh
cp .env-example .env
```

Abra seu editor de textos preferido e especifique as portas que deseja para executar o servidor web:
```
HTTP_PORT=80
HTTPS_PORT=443
```

Agora é executar o docker-compose
```sh
docker-compose up -d
```

E acessar seu localhost com a porta descrita no *HTTP_PORT* no arquivo *.env*

## Autor

**Samuel Bartag** (https://github.com/samuelbartag)
