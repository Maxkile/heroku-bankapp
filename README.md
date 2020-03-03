1) Create docker image named 'bankapp' with spring-boot application using command. You must choose working directory  as ../bankapp:
	sudo docker build -f Dockerfile -t bankapp .
2) Wait for all images to pull on your localhost
3) Create docker-compose container of ouer application, database and amdmire instrument to host and ping docker-based databases
	sudo docker-compose build
	sudo docker-compose up
