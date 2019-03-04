# php7-mongodb-nginx
Docker-compose file para montar ambiente com PHP7, Mongo DB e Nginx como http server, neste caso usando linux para hospedar o container. O mesmo foi usado para teste de trabalho.

## Como usar (How to)

* Tenha previamente instalado o [docker](https://www.docker.com/products/overview) e o [docker compose](https://docs.docker.com/compose/install/)
* Crie um diretorio no seu HOME chamado ```workspace_teste```
* Entre na pasta com ```cd workspace_teste```
* Clone este repositório dentro da pasta
* Entre na pasta com o comando ```cd php7-mongodb-nginx```
* Execute ```docker-compose up -d```

* Basta colocar seus arquivos .php dentro da pasta "workspace_teste"
* Faça o teste acessando no browser http://localhost

* Quando quiser parar os containers, entre na pasta "php7-mongodb-nginx" e execute ```docker-compose stop```

## Dúvidas
* Entre em contato: corintho@gmail.com

## License

[The MIT License (MIT) Copyright (c) 2013](http://opensource.org/licenses/MIT)