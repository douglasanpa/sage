# SAGE
Para utilizar você precisa do [docker-compose](https://docs.docker.com/compose/install/)
faça o clone desse repositório
> git clone https://github.com/douglasanpa/sage.git ; cd sage

Configure o SAGE
> nano docker-compose.yml

Inicie o sistema
> docker-compose up -d sage mariadb

Caso necessite do PHPMYADMIN
> docker-compose up phpmyadmin

Finalizando o PHPMYADMIN
> docker-compose down phpmyadmin

Para logar utilize o usuário admin@admin.com e senha secret

Testar com Play With Docker
---------------------------
[Abra o PWD e execute os comandos acima](http://labs.play-with-docker.com/)
