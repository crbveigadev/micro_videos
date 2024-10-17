buildar uma imagem

docker build -t my-app-python .

ver a imagem
docker image ls

rodar o docker
docker run my-app-python

executar o docker
docker ps
docker exec -it xxx bash

parar o containter
docker ps
docker stop xxx

Criar um volume para o desenvolvimento do projeto
docker run -v $(pwd):/app my-app-python

Executar novamente o container
docker exec -it xxx bash
