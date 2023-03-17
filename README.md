# todo_list
To build a Docker image using this Dockerfile , navigate to the directory containing the Dockerfile in a terminal window and run the following command:
```py
docker build -t my-app .
```
To run the Docker container using this image, run the following command:
```py
docker run -p 8080:8080 my-app
```
This command will run the Docker container using the "my-app" image and map port 8080 from the container to port 8080 on the host machine.
