
# Run following command on terminal

docker build --tag=hellodocker .

docker image ls

docker run -d -p 4000:80 hellodocker

docker container stop CONTAINER_ID
docker rm CONTAINER_ID

docker container ls