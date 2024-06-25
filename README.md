A simple Todo application created using Python Flask and SQLalchemy

![image](https://github.com/Ashwanthbala/Todo-app/assets/88878831/2a8b4960-f28e-48cf-aa1e-bb578fbfbc2d)

Instructions to pull and run the docker image from Docker Hub:

1) Install Docker Desktop in your PC (https://www.docker.com/products/docker-desktop/)
2) docker pull docker push ashwanthbala/python-todo:0.2
3) Verify using "docker images" command whether the image has been successfully downloaded on your system
4) docker run -d -p 5000:5000 ashwanthbala/python-todo:0.2 (To run the python application). You can verify using "docker ps" command whether the container is running.
5) Once the container is in running state, check whether you are able to access the application on your localhost using port 5000.(http://localhost:5000)

Instructions to remove and delete the image:

1) stop the running container - docker stop <container-name>
2) remove the container - docker rm <container-name>. verify using "docker ps -a" command.
3) Remove the image - docker rmi ashwanthbala/python-todo:0.2


Happy Learning !!!

