# Repositório com container Docker configurado com Rails 6 e Ruby 2.7.1

Para construir a imagem do container, execute:

````
docker-compose build
````

Esse comando deverá ser executado logo após clonar o repositório em sua máquina. Somente será necessário criar a imagem novamente quando precisar instalar uma nova gem, pois as imagens do Docker possuem acesso somente de leitura.


Para iniciar a execução do container, execute o seguinte comando:

````
docker-compose up
````

Para executar comandos específicos dentro do container, execute o seguinte comando: 

````
docker-compose exec web comando
````

Por exemplo:

````
docker-compose exec web rake routes
````
