# docker_image_custom

Use o comando docker para listar as imagens:
docker image list

Para verificar imagens ativas:
docker ps

Faça build da imagem com:
docker build .

Para iniciar o container:
docker run -d -p 3000:3000 --name node-docker-default "nome da imagem"

Para finalizar tudo:
docker system prune
