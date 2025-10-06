## Docker Demo

pip install -r requirements.txt

uvicorn main:app --reload

docker build -t docker-demo .

docker run -d -p 8000:8000 docker-demo

docker ps → shows running containers

docker images → shows built images

docker exec -it <container_id> bash → enter the container

docker logs <container_id> → view logs

docker stop <container_id> → stop it
