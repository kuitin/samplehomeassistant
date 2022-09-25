

docker build --build-arg BUILD_FROM="homeassistant/amd64-base:latest" -t myaddon .

docker run --rm -it --entrypoint /bin/bash myaddon:latest

docker-compose up
