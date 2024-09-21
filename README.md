# Devops
Documentation on devops course


**Exercise 1.1**: Getting started
Since we already did "Hello, World!" in the material let's do something else.

Start 3 containers from an image that does not automatically exit (such as nginx) in detached mode.

Stop two of the containers and leave one container running.

Submit the output for docker ps -a which shows 2 stopped containers and one running.

**Solution** : 

![e1 1](https://github.com/user-attachments/assets/fa3252c1-f137-4f59-8940-9cad665842df)


**Exercise 1.2**: Cleanup
We have containers and an image that are no longer in use and are taking up space. Running docker ps -a and docker image ls will confirm this.

Clean the Docker daemon by removing all images and containers.

Submit the output for docker ps -a and docker image ls

**Solution** : 

![w1 2](https://github.com/user-attachments/assets/dc204fa0-6bd6-4fbe-9b33-b2f87d68c537)


**Exercise 1.3** : Secret message
Now that we've warmed up it's time to get inside a container while it's running!

Image devopsdockeruh/simple-web-service:ubuntu will start a container that outputs logs into a file. Go inside the running container and use tail -f ./text.log to follow the logs. Every 10 seconds the clock will send you a "secret message".

Submit the secret message and command(s) given as your answer.

**Solution** : 

![e1 3](https://github.com/user-attachments/assets/ea765db4-f294-45a9-9ab3-a43c9423b0c6)



