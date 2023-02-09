## Day 18 Task: Docker for DevOps Engineers.

Day 18 article : [Medium](https://medium.com/@rejani2906/day-18-docker-compose-and-yaml-d4c9d033b44f)

## Task-1

Learn how to use the docker-compose.yml file, to set up the environment, configure the services and links between different containers, and also to use environment variables in the docker-compose.yml file. 

![yaml](/2023/day18/Screenshots/docker-compose-yaml.png)

![config](/2023/day18/Screenshots/docker-compose-config.png)

![compose-up](/2023/day18/Screenshots/docker-compose-up.png)

![ps](/2023/day18/Screenshots/docker-compose-ps.png)

## Task-2
- Pull a pre-existing Docker image from a public repository (e.g. Docker Hub) and run it on your local machine. Run the container as a non-root user (Hint- Use `usermod ` command to give user permission to docker). Make sure you reboot instance after giving permission to user.

![pull](/2023/day18/Screenshots/docker-pull.png)

![run](/2023/day18/Screenshots/docker-run.png)


- Inspect the container's running processes and exposed ports using the docker inspect command.

![1](/2023/day18/Screenshots/inspect-1.png)

![2](/2023/day18/Screenshots/inspect-2.png)

![3](/2023/day18/Screenshots/inspect-3.png)

![4](/2023/day18/Screenshots/inspect-4.png)

![5](/2023/day18/Screenshots/inspect-5.png)

- Use the docker logs command to view the container's log output.

![logs](/2023/day18/Screenshots/docker-logs.png)

- Use the docker stop and docker start commands to stop and start the container.

![](/2023/day18/Screenshots/docker-stop.png)

![](/2023/day18/Screenshots/socker-start.png)

- Use the docker rm command to remove the container when you're done.

![rm1](/2023/day18/Screenshots/docker-rm-1.png)

![rm2](/2023/day18/Screenshots/docker-rm-2.png)

## How to run Docker commands without sudo?
- Make sure docker is installed and system is updated (This is already been completed as a part of previous tasks):
- sudo usermod -a -G docker $USER 
- Reboot the machine.

![ps](/2023/day18/Screenshots/docker-ps.png)
