HOST_PORT:=8000
CONTAINER_PORT:=8000
APPLICATION_NAME:= kittygram

build:
	sudo docker build -t kittygram_backend .
run:
	sudo docker run --${APPLICATION_NAME}_backend_container --rm -p ${HOST_PORT}:${CONTAINER_PORT} ${APPLICATION_NAME}_backend
