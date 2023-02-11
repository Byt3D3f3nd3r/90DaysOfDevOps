## Day 19 Task: Docker for DevOps Engineers.

Day 19 article : [Medium](https://medium.com/@rejani2906/day-19-docker-volume-and-docker-network-6281081452c2)

## Task-1

- Create a multi-container docker-compose file which will bring _UP_ and bring _DOWN_ containers in a single shot ( Example - Create application and database container )

![yaml](/2023/day19/Screenshots/compose-yaml.png)

_hints:_

- Use the `docker-compose up` command with the `-d` flag to start a multi-container application in detached mode.

![up](/2023/day19/Screenshots/compose-up.png)

- Use the `docker-compose scale` command to increase or decrease the number of replicas for a specific service. You can also add [`replicas`](https://stackoverflow.com/questions/63408708/how-to-scale-from-within-docker-compose-file) in deployment file for _auto-scaling_.

![scale](/2023/day19/Screenshots/compose-scale.png)

- Use the `docker-compose ps` command to view the status of all containers, and `docker-compose logs` to view the logs of a specific service.

![ps](/2023/day19/Screenshots/compose-ps.png)

![logs](/2023/day19/Screenshots/compose-logs.png)

- Use the `docker-compose down` command to stop and remove all containers, networks, and volumes associated with the application

![down](/2023/day19/Screenshots/compose-down.png)

## Task-2

- Learn how to use Docker Volumes and Named Volumes to share files and directories between multiple containers.

![mkdir](/2023/day19/Screenshots/mkdir-volume.png)

![create](/2023/day19/Screenshots/volume-create.png)

- Create two or more containers that read and write data to the same volume using the `docker run --mount` command.

![ubuntu-vol](/2023/day19/Screenshots/ubuntu-volume.png)

![mongo-vol](/2023/day19/Screenshots/mongo-volume.png)

- Verify that the data is the same in all containers by using the docker exec command to run commands inside each container.

![ubuntu-vol](/2023/day19/Screenshots/ubuntu-data-vol.png)

![mongo-vol](/2023/day19/Screenshots/mongo-data-vol.png)

- Use the docker volume ls command to list all volumes and docker volume rm command to remove the volume when you're done.

![ls](/2023/day19/Screenshots/volume-ls.png)

![remove](/2023/day19/Screenshots/stop-rm.png)

![local](/2023/day19/Screenshots/data.png)
